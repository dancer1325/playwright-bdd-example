# playwright-bdd-example

* == project / run BDD tests -- via -- [playwright-bdd](https://github.com/vitalets/playwright-bdd)  

## how has it been created?

* | project's root
  * create "playwright.config.js"
* | [features/](features)
  * create "homepage.feature"
* | [features/steps](features/steps)
  * implement steps

## how to run locally?

* `npm install`
* `npm run test`
  * check the generated files| [here](.features-gen)
* `npx playwright show-report`
  * OPTIONAL
  * host HTML report | serve

## Notes

* if you are using [Yarn Plug'n'Play](https://yarnpkg.com/features/pnp) -> check out [yarn-pnp](https://github.com/vitalets/playwright-bdd-example/tree/yarn-pnp)
