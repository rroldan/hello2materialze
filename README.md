# hello2materialize

 Ember application example materialize integration

## Steps
* installing ember-cli-materialize
* clean dependencies
* Some of the library's defaults can be set via your **config/environment.js** file

```javascript
module.exports = function(/* environment, appConfig */) {
  var ENV = {
    materializeDefaults: {
      modalIsFooterFixed:  false,
      buttonIconPosition:  'left',
      loaderSize:          'big',
      loaderMode:          'indeterminate',
      modalContainerId:    'materialize-modal-root-element',
      dropdownInDuration:  300,
      dropdownOutDuration: 300
    },
    ...
  };
}

```



## Prerequisites

You will need the following things properly installed on your computer.

* [Git](https://git-scm.com/)
* [Node.js](https://nodejs.org/) (with NPM)
* [Bower](https://bower.io/)
* [Ember CLI](https://ember-cli.com/)
* [PhantomJS](http://phantomjs.org/)

## Installation

* `git clone <repository-url>` this repository
* `cd hello2materialize`
* `npm install`
* `bower install`

## Running / Development

* `ember serve`
* Visit your app at [http://localhost:4200](http://localhost:4200).

### Code Generators

Make use of the many generators for code, try `ember help generate` for more details

### Running Tests

* `ember test`
* `ember test --server`

### Building

* `ember build` (development)
* `ember build --environment production` (production)

### Deploying

Specify what it takes to deploy your app.

## Further Reading / Useful Links

* [ember.js](http://emberjs.com/)
* [ember-cli](https://ember-cli.com/)
* Development Browser Extensions
  * [ember inspector for chrome](https://chrome.google.com/webstore/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi)
  * [ember inspector for firefox](https://addons.mozilla.org/en-US/firefox/addon/ember-inspector/)
