# Activa

A Jekyll-based development environment for www.activacontracts.co.uk.

---

This repo is where we maintain:

- the HTML (/)
- the CSS (/_scss)
- the JS (/_scripts)
- the PHP for the Contact form


## Dependencies

- Node
- Bundler
- Gulp


## Getting Started

```
npm install
bundle install
gulp server
```


## Development

### Browser Support

Should look good in:

- latest Chrome
- latest Firefox
- latest Safari
- the latest and previous iOS
- IE11+


## Sitemap

Added or deleted a page?
1) open sitemap.xml
2) save sitemap.xml
3) /_site/sitemap.xml should be updated


## Release to dev

1. working on the dev branch, you'll have been running gulp server during development so all changes are compiled into /_site
2. commit and push to Github
  1. CI will deploy to dev.activacontracts.co.uk


## Release to production

1. merge dev branch into master branch
2. push to Github
  1. CI will deploy to www.activacontracts.co.uk

