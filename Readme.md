*This repository is a mirror of the [component](http://component.io) module [component/keyname](http://github.com/component/keyname). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/component-keyname`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# keyname

  Keyboard event key name utility

## Installation

    $ component install component/keyname

or

    $ npm install keyname

## API

```js
var keyname = require('keyname');

keyname(27);
// => "esc"

keyname(23123123);
// => undefined
```

## Keys

  The following are supported:

  - backspace
  - tab
  - enter
  - shift
  - ctrl
  - alt
  - capslock
  - esc
  - space
  - pageup
  - pagedown
  - end
  - home
  - left
  - up
  - right
  - down
  - ins
  - del
  - meta

## License

  MIT
