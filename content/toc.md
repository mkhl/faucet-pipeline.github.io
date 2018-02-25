```javascript
[{
    source: "./styles/index.scss",
    target: "./dist/bundle.css",
}]
```

```javascript
[{
    source: "./styles/index.scss",
    target: "./dist/bundle.css",
    esnext: true // activates ES6 transpiler
}]
```

* motivation and philosophy

  simple, painless management of web assets/resources

  reduces low-level config hassle as well as dependency-management chores

  we don't expect to change the underlying tooling frequently, but we'll be able
  to if something better comes along - without burdening users with the details
  e.g. dreading upgrade from Babel v6 to v7?

  relying on amazing work by people like … - faucet just provides a bit of glue
  code on top

* CSS
    * Sass

* JavaScript
    * ES6 (optional support for older browsers)
    * JSX
    * TypeScript (considered experimental due to lack of high-level config
      abstractions; suggestions welcome)

* manifest

* framework integration
    * Rails
    * Spring

* FAQ

* alternatives

  faucet is designed around intentional constraints (→ quote cdent) faucet works
  for us, but it's perfectly fine if you prefer something different

  faucet is not for everyone, as it's designed for simplicity based on certain
  assumptions and beliefs (e.g.
  [deletability](https://kellysutton.com/2017/05/29/deletability.html)/replaceability)

  cf.
  [Rails with Webpack - not for everyone](https://www.codementor.io/help/rails-with-webpack-not-for-everyone-feucqq83z)

    * webpack
    * [Parcel](https://parceljs.org)
    * [Neutrino](https://neutrino.js.org)
    * …
