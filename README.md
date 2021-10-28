# common_mimes
Common mime type mapping generate from [MDN](https://developer.mozilla.org/en-US/docs/Web/HTTP/Basics_of_HTTP/MIME_types/Common_types)

## Example:
```ts
import { MimeMapping, ExtMapping } from "https://deno.land/x/common_mime_types@0.1.1/mod.ts"

MimeMapping["text/javascript"] // [".js", ".mjs"]

ExtMapping[".js"] // ["text/javascript"]
```