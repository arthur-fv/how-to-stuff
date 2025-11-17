# Some Principles I took from docs

Probably its missing something... Read more!

## From [Essencials](https://angular.dev/essentials)

### Components
The basic fundamental block for Angular app

A Component is defined by inserting a decorator (@Component) before a class 

```bash
@Component({
    selector: 'user-profile',
    imports: [OtherComponent],
    templateUrl: 'path/to/template',
    styleUrl: 'path/to/style'
})
export class Profile {
    ...
}
```

Components have a bunch of features, but every component must have:
 - A TypeScript class
 - An HTML template
 - A CSS selector

To use the Profile component in others places, we use the selector name declared 'user-profile'.

You also can see the Angular aplicatition as a tree of components. This also provides dependency injection and child queries.