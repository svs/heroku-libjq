# Heroku Buildpack libjq

Heroku Buildpack [libjq](https://github.com/stedolan/jq/wiki/C-API:-libjq) allows for installing libraries that require it like [ruby-jq](https://github.com/winebarrel/ruby-jq) for example.

## Usage

This buildpack will need to be inserted into the list of buildpacks for your application. It is not intended to be a standalone buildpack that supports an application framework.

```sh
> heroku buildpacks:add -i 1 https://github.com/technekes/heroku-buildpack-libjq
Buildpack added. Next release on tk-qa-incent-api will use:
  1. https://github.com/technekes/heroku-buildpack-libjq
  2. heroku/ruby
Run git push heroku master to create a new release using these buildpacks.
```
