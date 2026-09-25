# Changelog

## Unreleased

- Require PHP 8.2 or newer. PHP 7.x, 8.0, and 8.1 are no longer supported.
- Declare the package as a Composer `library`. It does not implement a Composer plugin.
- Run the test suite on PHP 8.2, 8.3, 8.4, and 8.5.
- Mark `Payload::__construct()` as explicitly nullable so PHP 8.4 and 8.5 do not emit a deprecation.
