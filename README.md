# Our Website [![lint-and-debug](https://github.com/Glitch-Entertainment/glitch-site/workflows/lint-and-debug/badge.svg)](https://github.com/Glitch-Entertainment/glitch-site/actions?query=workflow%3Alint-and-debug)[![Netlify Status](https://api.netlify.com/api/v1/badges/7c86ee23-817c-431c-9fdd-578d7176963a/deploy-status)](https://app.netlify.com/sites/silly-williams-269dd2/deploys)

We ♥ open-source since it lets us continue to deliver amazing games. Our website is completely open-source to both allow general transparency and a nice way to let others help improve our site.

### Building the Site

To build the site, ensure you have the latest version of [Ruby](https://www.ruby-lang.org), [Jekyll](https://rubygems.org/gems/jekyll), and [Bundler](https://rubygems.org/gems/bundler) installed. Afterwords, install the dependencies of the site by running `bundle install`. After the installation finishes, you can either build the site using `bundle exec jekyll build` or "serve" the site to see live changes by using `bundle exec jekyll serve`. 

### Acknowledgments

This site used [doamatto's Jekyll template](https://github.com/doamatto/jekylltemplate) to get up and running with the bare necessities lighting fast. This repo uses the GitHub action made by [doamatto for Nano](https://github.com/doamatto/nano/blob/master/.github/workflows/lint-and-debug.yml) for just-in-time linting and debugging, in case we forgot to do it.
