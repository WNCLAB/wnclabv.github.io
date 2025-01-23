
# Wireless Networking and Computing Lab


[![Deploy Jekyll](https://github.com/WNCLAB/wnc-lab.com/actions/workflows/jekyll.yml/badge.svg)](https://github.com/WNCLAB/wnc-lab.com/actions/workflows/jekyll.yml)

The homepage for WNCL, generated from the [academicpages](academicpages/academicpages.github.io). 

## Running Locally

To work locally you will need to:

1. Clone the repository.
1. Make sure you have ruby-dev, bundler, and nodejs installed: `brew install ruby-dev ruby-bundler nodejs`
1. Run `bundle install` to install ruby dependencies. If you get errors, delete Gemfile.lock and try again.
1. Run `bundle exec jekyll serve` to generate the HTML and serve it from `localhost:4000` the local server will automatically rebuild and refresh the pages on change.