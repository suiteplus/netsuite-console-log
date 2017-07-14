NOTE: Abandoned. The idea here was to split netsuite helpers into modules.

# netsuite-console-log

### Usage

Currently only used with browserify.

Require to define common js logging functions for netsuite server suitescripts.

console.
  - log(...inp)
  - debug(...inp)
  - profile(message)
  - error(...inp)
  - $stackTrace(errObj)
