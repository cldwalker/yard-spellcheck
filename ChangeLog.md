### 0.1.3 / 2011-06-08

* Require yard ~> 0.6.
* Fixed an option parsing issue with the `-D` option.

### 0.1.2 / 2011-05-17

* Added a work-around for FFI 1.0.8 not accepting frozen Strings.
* Filter words specified by `--ignore`.

### 0.1.1 / 2011-01-25

* Do not load `yard` within the plugin.
* Ignore all Acronyms and CamelCase words.
* Ignore all words containing underscores.
* Perform a soft-update of the YARD Cache when running `yard-spellcheck`.
* Exit with status `-1` if the `yard-spellcheck` command found any typos.

### 0.1.0 / 2011-01-25

* Initial release:
  * Added {YARD::Spellcheck::Checker}.
  * Added {YARD::Spellcheck::Printer}.
  * Added {YARD::CLI::Spellcheck}.

