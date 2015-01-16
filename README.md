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

t('{thing} {thing} {thing}!', { thing: 'Developers' });
// Developers Developers Developers!
```

## LICENSE

MIT License (2015) Maximilian Hoffmann
