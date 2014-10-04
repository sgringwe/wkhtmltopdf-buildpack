# Changes made in this branch



# WKHTMLTOPDF Buildpack

This is a [Heroku buildpack][0] for bundling a compatible [wkhtmltopdf][1]
binary with your environment.

Forked from https://github.com/dkaufman/wkhtmltopdf-buildpack.

## Versions

* Buildpack:   0.2
* WKHTMLTOPDF: 0.9.9

## Usage

```bash
$ heroku config:set BUILDPACK_URL=https://github.com/ddollar/heroku-buildpack-multi.git
$ echo 'https://github.com/sgringwe/wkhtmltopdf-buildpack.git' >> .buildpacks
$ echo 'https://codon-buildpacks.s3.amazonaws.com/buildpacks/heroku/ruby.tgz' >> .buildpacks
$ git add .buildpacks
$ git commit -m 'Add multi-buildpack'
```

[0]: http://devcenter.heroku.com/articles/buildpacks
[1]: http://code.google.com/p/wkhtmltopdf/
