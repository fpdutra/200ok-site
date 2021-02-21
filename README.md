# [200ok.us](https://200ok.us/) source files

[![Netlify Status](https://api.netlify.com/api/v1/badges/10be3658-c444-423a-a7a2-9d326f1dd1fb/deploy-status)](https://app.netlify.com/sites/200ok/deploys)

This is a static website deployed on [Netlify](https://www.netlify.com/), built with [Hexo](https://hexo.io/).

### Installing

```console
$ git clone git@github.com:techlahoma/200ok-site.git
$ cd 200ok-site
$ npm install
```

### File Structure

All the copy documents are in `/source`, the theme is `/themes/200ok`, and the original front-end theme is located in `/wrapbootstrap` for reference. Run `hexo new page` to automatically generate a new page if you need more content. All of the `/source` files should be markdown. Posts aren't currently being used.

### Working locally on the site

```console
$ npm run start
```

Then go to http://localhost:4000

### Deploy Changes

The `main` branch is automatically deployed to [200ok.us](https://200ok.us/) with [Netlify site deploys](https://docs.netlify.com/site-deploys/overview/). See [netlify.toml](netlify.toml).

## Code of Conduct

This repository is governed by [Techlahoma’s Code of Conduct](https://www.techlahoma.org/code-of-conduct).

## License

This software is licensed under the MIT License. For more information, read this repository’s [LICENSE](LICENSE).
