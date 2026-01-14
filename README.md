Heroku Buildpack for [Metabase 58.1](https://downloads.metabase.com/v0.58.1.x/metabase.jar)

This buildpack installs Temurin JRE 18 by default. Override with `JAVA_VERSION`.

Add the following to your app.json:

```JSON
"buildpacks": [
  {
    "url": "https://github.com/wemersonblend/metabase-buildpack"
  }
]
```
