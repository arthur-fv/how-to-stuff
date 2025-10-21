# How to install nvm, node, npm, pnpm
I know you will forget how to do this shit, so, here's how-to

## Install nvm (Node Version Manager)
> ```curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/master/install.sh | bash```

### Then, apply
> ```nvm install --lts```
>
> ```nvm use --lts```

This will install the **lts node version**. If you want some specific node's version, for example:
> ```nvm install 20.16.0```
>
> ```nvm use 20.16.0```

### Test in the shell
> ```node -v```
>
> ```npm -v```


## Install pnpm
> ```npm install -g pnpm```

### Test in the shell
> ```pnpm -v```
