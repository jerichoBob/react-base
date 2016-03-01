# react-base
A react base for personal projects. 

Based (mostly) on the Medium article by Fancois Ward (https://medium.com/@fward/state-of-the-art-javascript-in-2016-ab67fc68eb0b#.3o0nhzpg3)

TL;DR - here are the article's favored components (could easily get this from the package.json file as well)
   * **Core Library**: [React](http://facebook.github.io/react/index.html) - (duh)
   * **Application life cycle**: [Redux](https://github.com/reactjs/redux)
   * **Language: ES6 with Babel**. No types (yet) -- bobse: I'll sneak some in...
   * **Linting & style**: ESLint with AirBNB
   * **Dependency management**: It’s all about NPM, CommonJS and ES6 modules
   * **Build tool**: [webpack](https://webpack.github.io/)
   * **Testing**: [Mocha](https://mochajs.org/) + [Chai](http://chaijs.com/) + [Sinon](http://sinonjs.org/) (but it’s not that simple) -- bobse: I'm probably going to go with [Jasmine](http://jasmine.github.io/2.4/introduction.html)
    * also need to add E2E testing! 
   * **Utility library**: [lodash](https://lodash.com/)
   * **Http requests**: [Fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API) + [http-client](https://github.com/mjackson/http-client)
   * **Styling**: Consider CSS modules -- bobse: I'll probably want to be a little more opinionated here
   * **(Data) API**: [GraphQL](https://facebook.github.io/react/blog/2015/05/01/graphql-introduction.html)/[Relay](http://facebook.github.io/react/blog/2015/02/20/introducing-relay-and-graphql.html) & REST everywhere else

``` javascript
package.json == {
  "name": "react-base",
  "version": "1.0.0",
  "description": "A react base for personal projects.",
  "main": "index.js",
  "scripts": {
    "start": "webpack-dev-server"
  },
  "repository": {
    "type": "git",
    "url": "git+https://github.com/jerichoBob/react-base.git"
  },
  "keywords": [
    "react",
    "basic"
  ],
  "author": "bobse",
  "license": "ISC",
  "bugs": {
    "url": "https://github.com/jerichoBob/react-base/issues"
  },
  "homepage": "https://github.com/jerichoBob/react-base#readme",
  "dependencies": {
    "react": "^0.14.7",
    "react-dom": "^0.14.7",
    "react-redux": "^4.4.0",
    "redux": "^3.3.1"
  },
  "devDependencies": {
    "babel-core": "^6.6.0",
    "babel-loader": "^6.2.4",
    "babel-preset-es2015": "^6.6.0",
    "babel-preset-react": "^6.5.0",
    "eslint": "^2.2.0",
    "eslint-config-airbnb": "^6.0.2",
    "eslint-plugin-react": "^4.1.0",
    "redux-devtools": "^3.1.1",
    "webpack": "^1.12.14",
    "webpack-dev-server": "^1.14.1"
  }
}
```

