# Deno Elm Http

This is a XMLHttpRequest polyfill specifically for Elm to allow the use of Elm's `Platform.worker` to make requests since Elm uses XMLHttpRequest internally for HTTP requests. This is NOT intended to be a polyfill for all use cases.

## Use

Just import this at the top of your project before you initialize Elm, like so
```typescript
import "http://github.com/wolfadex/deno_elm_http/raw/master/http-polyfill.ts";
import Elm from "./elm.js"

Elm.Main.init();
```