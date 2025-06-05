Heroku Buildpack for [Metabase 55.1](https://downloads.metabase.com/v0.55.1.x/metabase.jar)

Add the following to your app.json:

```JSON
"buildpacks": [
  {
    "url": "https://github.com/wemersonblend/metabase-buildpack"
  }
]
```