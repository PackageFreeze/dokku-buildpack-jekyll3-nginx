This is a dokku buildpack for installing Jekyll 3.

### Usage

Add a `.buildpacks` file in the root of your jekyll project containing:

```
https://github.com/GlueDigital/dokku-buildpack-jekyll3.git
https://github.com/heroku/heroku-buildpack-static.git
```

And a `static.json` file (in the root too) containing:

```
{
  "root": "_site/"
}
```

### Credit

Based on [inket/dokku-buildpack-jekyll-nginx](https://github.com/inket/dokku-buildpack-jekyll-nginx).
