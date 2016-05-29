# require

This library brings Clojure-style requires to zepto,
using a simple macro.

## Installation

Please use zeps, as this module relies on it.

```
zeps install hellerve/require
```

## Usage

```clojure
(require "base64") ; => base64:encode and base64:decode are now visible
(require "base64" :as "b64") ; => b64:encode and b64:decode are now visible
(require "base64" :import ("encode")) ; => base64:encode is now visible
(require "base64" :as "b64" :import ("encode")) ; => b64:encode is now visible
```

That's all, folks!

<hr/>

Have fun!
