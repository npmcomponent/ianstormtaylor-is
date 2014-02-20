*This repository is a mirror of the [component](http://component.io) module [ianstormtaylor/is](http://github.com/ianstormtaylor/is). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/ianstormtaylor-is`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# is
  
  Simple type checking.

## Installation

    $ component install ianstormtaylor/is
    $ npm install ianstormtaylor/is

## Example

```js
var is = require('is');

is.arguments(arguments);   // true
is.array([]);              // true
is.boolean(true);          // true
is.date(new Date);         // true
is.element(document.body); // true
is.function(function(){}); // true
is.fn(function(){});       // true
is.null(null);             // true
is.number(42);             // true
is.object({});             // true
is.regexp(/[A-Za-z0-9]+/); // true
is.string('A');            // true
is.undefined(undefined);   // true
is.nan(NaN);               // true
is.empty([]);              // true
```

_Note: If you need old browser support, use `.fn` instead of `.function`._

## License

  MIT
