# Clarity

The Essence project done...right?

## What's Coming

1. Clarity::expect() and expect() are now the only 2 entry points.
2. Class `Chain` is now responsible for handling all the magic.
    - queries are cached in memory
    - no need to have an array of "links" anymore, Chain just ignores unknown identifiers
    - however, it'll let you know if no matcher was specified
3. Matchers are now that much better than before.
    - no "configuration" matchers, but now they have `options`
    - special syntax for matcher options: `...->withOptionName(optionValue, ...)`
    - aliases are supported too (1+ for any matcher)!
    - there are less matchers, but each one of them has more features than previously
4. Clarity::runLast() and Clarity::runAll() methods are all you need.
    - stupid things like `implicit_validation` were removed, ugh
    - integration with existing popular testing frameworks like *PhpUnit*
5. Later, Clarity will obtain its own test runner (and integration with code coverage tools!).
6. Even more cool stuff coming.

## License

The MIT license (MIT).
