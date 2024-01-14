# The site for the Benton County Career Convention


## Setup 
* Requires [Ruby](https://www.ruby-lang.org/en/documentation/installation/)

Set up rbenv
https://github.com/rbenv/rbenv

* Requires [Bundler](https://bundler.io)
  * `$ gem install bundler`

* `$ bundle install`

## Build
### Development
* `$ bundle exec jekyll s`

### Production
* `$ JEKYLL_ENV=production jekyll build`


## Deploy
This is hosted on GitHub so pushing to `master` will deploy the site.