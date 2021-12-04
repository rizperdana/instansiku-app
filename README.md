## Getting Started
- Install Nodejs from [Nodejs Official Page](https://nodejs.org/en/)
- Open your terminal
- Navigate to the project
- Run `yarn install`  [Yarn](https://yarnpkg.com/en/)
- Run `yarn serve` to start a local development server
- A new tab will be opened in your browser

You can also run additional npm tasks such as
- `yarn run build` to build your app for production
- `yarn run lint` to run linting.

## Git & App Versioning

#### Git Branch
 - `master`: production
 - `feature/XYZ`: new feature development

For development flow we are following [Trunk-based Development Workflow](https://trunkbaseddevelopment.com).

## Tech Stack

#### Vue-cli

We used the latest 3.x [Vue CLI](https://github.com/vuejs/vue-cli) which aims to reduce project configuration
to as little as possible. Almost everything is inside `package.json` + some other related files such as
`.babel.config.js`, `.eslintrc.js` and `.postcssrc.js`.

#### Vuex

Vuex is a state management pattern + library for Vue.js applications. It serves as a centralized store for all the components in an application, with rules ensuring that the state can only be mutated in a predictable fashion. It also integrates with Vue's official [devtools](https://github.com/vuejs/vue-devtools) extension to provide advanced features such as zero-config time-travel debugging and state snapshot export / import.


#### Vuetify
Vuetify is developed exactly according to Material Design spec. Every component is hand crafted to bring you the best possible UI tools to your next great app. The development doesn't stop at the core components outlined in Google's spec. Through the support of community members and sponsors, additional components will be designed and made available for everyone to enjoy.

## Libraries & Tools

* [Axios](https://github.com/axios/axios) - Promise based HTTP client for the browser and node.js.
* [Momentjs](https://momentjs.com) - Used to do parse, validate, manipulate, and display dates and times in JavaScript.
* [Eslint](https://eslint.org/) - Used to do find and fix problems in JavaScript code.
* [VeeValidate](https://logaretm.github.io/vee-validate/) - VeeValidate is a form validation framework for Vue.js.
* [unlayer](https://unlayer.com/) - Embeddable Email Editor and Page Builder. A plug and play editing JavaScript.

## Browser Support

At present, we officially aim to support the last two versions of the following browsers:

<img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/chrome.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/firefox.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/edge.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/safari.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/opera.png" width="64" height="64">