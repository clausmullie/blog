# Blog for Public Code

This is the Blog for Public Code by the [Foundation for Public Code](https://publiccode.net).

[![Test](https://github.com/publiccodenet/blog/actions/workflows/test.yml/badge.svg)](https://github.com/publiccodenet/blog/actions/workflows/test.yml)
[![pages-build-deployment](https://github.com/publiccodenet/blog/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/publiccodenet/blog/actions/workflows/pages/pages-build-deployment)
[![Scheduled link check](https://github.com/publiccodenet/blog/actions/workflows/link-check.yml/badge.svg)](https://github.com/publiccodenet/blog/actions/workflows/link-check.yml)

## How to contribute to the blog

Follow our [contributing guide](CONTRIBUTING.md) to learn how you can contribute.

## Building the site

This site builds with [Jekyll](http://jekyllrb.com/), as is the default of [GitHub pages](https://pages.github.com/) and uses the [Foundation for Public Code Jekyll Theme](https://github.com/publiccodenet/jekyll-theme).

## Installing locally

1. To build the site locally make sure you have [Ruby](https://www.ruby-lang.org/en/) and [Bundlr](https://bundler.io/) installed.
2. Install the dependencies of this repo with

```bash
bundle install
```

## Serving Locally

1. Run the Jekyll server with

```bash
bundle exec jekyll serve
```

1. You can now view the website locally on `http://localhost:4000`

The server will rebuild the site every time a file changes, with the exception of `_config.yml`.

## Statistics

We use [Plausible](https://about.publiccode.net/activities/tool-management/plausible-analytics.html) for statistics, and they can be viewed at [plausible.io/blog.publiccode.net](https://plausible.io/blog.publiccode.net).

## License

© 2020 Foundation for Public Code. All content licensed under [Creative Commons Zero v1.0 Universal, unless otherwise noted](LICENSE.md).
