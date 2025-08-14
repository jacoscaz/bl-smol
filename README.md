# @jacoscaz/bl-smol

This is a _smol_ version of the [bl][0] package by [Rod Vagg][1] which removes
all runtime dependencies by replacing them with native Node.js alternatives:

- `buffer` is discarded in favour of Node.js' built-in `Buffer` class.
- `readable-stream` is replaced with Node.js' built-in `stream` module.
- `inherits` is replaced with Node.js' built-in `util.inherits` function.

Everything else is left untouched. Check out the original [bl][0] package for 
more information!

[0]: https://www.npmjs.com/package/bl
[1]: https://github.com/rvagg