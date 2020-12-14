### Experian Health

# Registration Accelerator

Registration Accelerator is an add-on solution to the eCareNext platform that facilitates a text-to-mobile module experience that brings the registration process to the patient before time of service​.

### React/Redux Stack Backbone 🚀

This project features a React-Redux UI which contains a form that interacts with a mock API.

---

### Prerequisites ☑️

Before running this project be sure you have Node.js v12 or later installed.

We also recommend using Yarn over npm for package management.
Visit [Yarn](https://yarnpkg.com) to grab the latest binary.

### Configure Proxies 🔨

- Update your npm/yarn configuration as indicated in this [Confluence document.](https://confluence.passporthealth.com/display/NDT/Set+proxies+for+Yarn+and+npm+on+a+citrix+vm)

- Alternate approach to [set up proxies for npm/yarn on a Citrix VM.](https://confluence.experianhealth.com/display/UIUX/Fixing+proxies+for+Yarn+and+npm+on+a+citrix+vm).

### Install Project Dependencies 📈

```sh
$ npm install
```

or

```sh
$ yarn
```

### Get Up and Running 🏃‍♀️

- Run The UI: `yarn run dev` or `npm run dev`

- Run the mock API: `yarn run mock:service` or `npm run mock:service`

- To run the application locally in the browser use `localhost:3000/id/12345`

> Run `yarn run mock:service:slow` to emulate a slower connection when interacting with the service. This script adds a 2 sec delay to all responses.

## Testing

### Unit Tests 🧪

- `yarn run test` will run the unit tests.
- `yarn run test:cov` or `yarn run test --coverage` will execute tests and generate a coverage report.

### Cypress e2e Tests 🔄

[Install Cypress](https://docs.cypress.io/guides/getting-started/installing-cypress.html#System-requirements) v6 or later

```
npm install cypress --save-dev
```

or

```
yarn add cypress --dev
```

- To individually run tests through the Cypress app - `yarn cypress:dev`
- To run all Cypress tests - `yarn cypress:cicd`
