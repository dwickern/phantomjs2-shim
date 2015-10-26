# phantomjs2-shim
Alias for phantomjs module to call phantomjs2

Intended for use with [ember-cli](http://www.ember-cli.com/) and [testem](https://github.com/airportyh/testem).

Motivated by memory leaks in phantomjs consuming several gigabytes of RAM when running ember acceptance tests.

Usage
---
Add to `package.json`:

```
{
  "dependencies": {
    "phantomjs": "dwickern/phantomjs2-shim"
  }
}
```
