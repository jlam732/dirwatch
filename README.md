# dirwatch

Forked from [dirwatch](https://github.com/juxt/dirwatch)

Watch directories for changes.

Similar to watchtower (but uses JDK 7 async notification mechanisms rather than polling)

Similar to ojo (but simpler, unlimited watchers allowed and directory recursive)

## Installation

Add the following dependency to your `project.clj` file

[![Clojars Project](http://clojars.org/juxt/dirwatch/latest-version.svg)](http://clojars.org/juxt/dirwatch)

## Usage

```clojure
    (require '[juxt.dirwatch :refer (watch-dir)])

    (watch-dir println (clojure.java.io/file "/tmp"))
```

## License

Copyright © 2013 JUXT.

Distributed under the Eclipse Public License, the same as Clojure.
