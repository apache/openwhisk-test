[![License](https://img.shields.io/badge/license-Apache--2.0-blue.svg)](http://www.apache.org/licenses/LICENSE-2.0)

# hellowhisk

Containst the following actions:
- greeting.js
- HttpGet.swift

## HttpGet.swift

This action invokes: ```curl https://httpbin.org/get```

which returns JSON which appears something like:

```
{
  "args": {},
  "headers": {
    "Accept": "*/*",
    "Connection": "close",
    "Host": "httpbin.org",
    "User-Agent": "curl/7.54.0"
  },
  "origin": "47.220.153.242",
  "url": "https://httpbin.org/get"
}
```

and then serializes it for the response object.
