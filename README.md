# Setup

## Environment

Before starting, make sure you have [Ruby](https://www.ruby-lang.org/en/documentation/installation/) and [NodeJS](https://nodejs.org/) installed.

Then install Jekyll:

```
$ gem install jekyll
```

And install Gulp client:

```
$ npm install gulp-cli -g
```

## Installing template

1. Fork the [Jekflix Template](https://github.com/thiagorossener/jekflix-template/fork)
2. Clone the repo you just forked:
```
$ git clone https://github.com/<your-github-username>/jekflix-template.git
```
3. Access the local project:
```
$ cd path/to/jekyll-template
```
4. Install npm packages:
```
$ npm install
```
5. Install Ruby dependencies:
```
$ bundle install
```
6. Build Jekyll:
```
$ bundle exec jekyll build
```
7. Then run Gulp:
```
$ gulp
```

## Running local

After the steps above, to run Jekyll locally, you'll just need to run Gulp:
```
$ gulp