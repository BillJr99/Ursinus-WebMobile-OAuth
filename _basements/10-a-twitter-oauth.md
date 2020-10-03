---
slide: 10-twitter-oauth
---

## Example: Twitter

- Parse url query arguments into json:

```
require('url');

// ...
function (req, res) {
    const queryObject = url.parse(req.url,true).query;
    // this is now json
}
```