# Cafe Condor - App
> The best App for restaurant cafe's

[iofullstack-project](http://www.iofullstack.com/)

![condor-cafe app](https://raw.githubusercontent.com/iofullstack/condor-cafe/master/docs/cafe-condor.png)

## Technologies:
![angular](https://raw.githubusercontent.com/iofullstack/condor-cafe/master/docs/angular.png)

> The webapp is developed in Angular v6
### Install

0. You need [Angular Command-Line Interface](https://cli.angular.io/)
```sh
  npm install -g @angular/cli@latest
```

1. Install dependencies:
```sh
  cd webapp && npm install
```

2. Run the project in the file *webapp*
```sh
  ng serve -o
```


![MongoBD](https://raw.githubusercontent.com/iofullstack/condor-cafe/master/docs/mongodb.png)

### Install and Usage

```javascript
const setupDB = require('condor-db')

setupDB(config).then(db => {
  const { Table } = db
}).catch(err => console.error(err))
```

## Great!!
> This is a project development by:

### Dev. Gary Guzman
![Gary Guzman](https://raw.githubusercontent.com/iofullstack/condor-cafe/master/docs/perfil-gary.png)

[GitHub: garyDav](https://github.com/garyDav)

### Dev. Jose Chirinos
![Jose Chirinos](https://raw.githubusercontent.com/iofullstack/condor-cafe/master/docs/perfil-jose.png)

[GitHub: JoseChirinos](https://github.com/JoseChirinos)

