# How to install NVM, Node.js, NPM and PNPM
I know you will forget how to do this shit at some point, so, here's how to

## Before anything else...
I recommend cleaning up any existing versions of the programs using the following (if installed using apt):
> ```sudo apt remove -y nodejs npm```
>
> ```sudo apt autoremove -y```

## Install NVM (Node Version Manager)
> ```curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/master/install.sh | bash```
### Test in the shell
> ```nvm -v```

Now, you can install Node.js and NPM
### Then, apply
> ```nvm install --lts```
>
> ```nvm use --lts```

This will install the **latest lts version of node**. If you want some specific node's version, for example:
> ```nvm install 20.16.0```
>
> ```nvm use 20.16.0```

### Test in the shell
> ```node -v```
>
> ```npm -v```

## Install PNPM
> ```npm install -g pnpm```

### Test in the shell
> ```pnpm -v```
