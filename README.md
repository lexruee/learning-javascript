# Learning Javascript/Node

## JS Setup on Arch Linux

``` 
sudo pacman -S nodejs npm yarn
```


## Version Management

``` 
asdf plugin-add nodejs
bash ~/.asdf/plugins/nodejs/bin/import-release-team-keyring
asdf install nodejs 12.0.0
```

## Node

``` 
node --version
```

## Testing

 * Jest
 * Jasmine

## Package Manager

 * npm
 * yarn
 
 
## Creating new projects

Set the local nodejs version:

``` 
asdf local nodejs 12.2.0
``` 

Create a new yarn-based project:
 
``` 
yarn init -y 
```

Install a testing framework:

``` 
yarn add jest --dev
``` 

Install a webframework:

``` 
yarn add expressjs
``` 
