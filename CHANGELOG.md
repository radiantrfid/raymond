# Raymond Changelog

### Raymond 2.0.0 _(May 01, 2016)_

- [BUGFIX] Fixes passing of context in helper options (issue #2) - Thanks @GhostRussia
- [BREAKING] Renames and unexports constants:

  - `handlebars.DUMP_TPL`
  - `lexer.ESCAPED_ESCAPED_OPEN_MUSTACHE`
  - `lexer.ESCAPED_OPEN_MUSTACHE`
  - `lexer.OPEN_MUSTACHE`
  - `lexer.CLOSE_MUSTACHE`
  - `lexer.CLOSE_STRIP_MUSTACHE`
  - `lexer.CLOSE_UNESCAPED_STRIP_MUSTACHE`
  - `lexer.DUMP_TOKEN_POS`
  - `lexer.DUMP_ALL_TOKENS_VAL`


### Raymond 1.1.0 _(June 15, 2015)_

- Permits templates references with lowercase versions of struct fields.
- Adds `ParseFile()` function.
- Adds `RegisterPartialFile()`, `RegisterPartialFiles()` and `Clone()` methods on `Template`.
- Helpers can now be struct methods.
- Ensures safe concurrent access to helpers and partials.

### Raymond 1.0.0 _(June 09, 2015)_

- This is the first release. Raymond supports almost all handlebars features. See https://github.com/aymerick/raymond#limitations for a list of differences with the javascript implementation.