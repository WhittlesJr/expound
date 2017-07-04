# expound

A Clojure library designed to ... well, that part is up to you.

## Usage

FIXME

## Clojurescript REPL

```
lein with-profile +test-web,+cljs-repl repl
````

```
M-x cider-connect
(use 'figwheel-sidecar.repl-api)
(start-figwheel!)
(cljs-repl)
```

```
open http://localhost:3446/index.html
```

## Running CLJS tests

`lein with-profile test-web cljsbuild auto test`
`ls ./resources/public/test-web/test.js | entr -s 'sleep 1; bin/tests'`


## License

Copyright © 2017 FIXME

Distributed under the Eclipse Public License either version 1.0 or (at
your option) any later version.
