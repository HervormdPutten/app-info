# App info | Hervormd Putten

[![Github Pages](https://github.com/HervormdPutten/app-info/actions/workflows/github-pages.yml/badge.svg)](https://github.com/HervormdPutten/ithelp/actions/workflows/build-and-deploy.yml)   
The live website can be visited at: [https://app.hervormdputten.nl](https://app.hervormdputten.nl)

## Local development

```bash
git clone --recurse-submodules --depth 1 https://github.com/HervormdPutten/app-info.git
```

You can now edit your own versions of the site’s source files.

If you want to do SCSS edits and want to publish these, you need to install `PostCSS`

```bash
npm install
```

## Running the website locally

Building and running the site locally requires a recent `extended` version of [Hugo](https://gohugo.io).
You can find out more about how to install Hugo for your environment in our
[Getting started](https://www.docsy.dev/docs/getting-started/#prerequisites-and-installation) guide.

Once you've made your working copy of the site repo, from the repo root folder, run:

```
hugo serve
```

