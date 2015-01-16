# fuchs-template
minimum templating engine by thomas fuchs

further information: http://mir.aculo.us/2011/03/09/little-helpers-a-tweet-sized-javascript-templating-engine/

## Installation

```bash
npm install fuchs-template
```

## Usage

```js
var t = require('fuchs-template');

t('Hello {name}, how are you?', { name: 'Max'});
// "Hello Max, how are you?"

t('I write {language} for a living, but it doesn’t mean I think {language} is the best language ever.', { language: 'JavaScript'});
// I write JavaScript for a living, but it doesn’t mean I think JavaScript is the best language ever.
```

## LICENSE

MIT License (2014) Maximilian Hoffmann
