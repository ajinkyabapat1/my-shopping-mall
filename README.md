# Angular (4) - Angular Shopping Basket 

# Author:
Ajinkya Bapat - ajinkyabapat1@gmail.com

# Steps to setup Workspace :
Install VS code Install Node js Install Angular CLI : npm install -g @angular/cli once done with all installation ,run following commands
ng update
npm install
install --save-dev @angular-devkit/build-angular
npm start



# Architectural Summary

* Angular 4 application (scaffolded with angular-cli)
* Built around RxJS Observables
* One way data flow and events based processing
* Immutable shopping cart to increase performance by enabling the OnPush change detention strategy that drastically reduces the change subtree Angular needs to process.
* Unit tested via Karma and Jasmine.
* SinonJS used for test mocking.
* Minimal styling with Foundation CSS used as the base framework and SCSS used to process custom styles.
* Basic example of async e2e test using new (async/await) Typescript syntax.


# Setup

Install the npm dependencies

```bash
npm install
```

# Build

```bash
npm run build
```

# Run Tests
```bash
npm run test
```

# Run E2E Tests
```bash
npm run e2e
```

# Serve

HTTP development server
```bash
npm run start
```

Then navigate to http://localhost:4200/



HTTPS development server (note: the development certificate will have to be added as a trusted CA)
```bash
npm run start:https
```

Then navigate to https://localhost:4200/
