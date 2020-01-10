## NOTES FROM MR.QUAIL

This project was a pre existing vuepress template that can be found at https://github.com/forestryio/portfolio-vuepress. I have customized it to serve as a MEVN Stack portfolio site to source clients. In no way was this my original work but my understanding of vuepress and Vue JS allows me to customize it for my use. visit the link above for instruction or use the one below. Be blessed!



```bash
# install VuePress locally
npm i -g vuepress

# Start local dev server
vuepress dev portfolio
```

## Build

```bash
# Build static files to .vuepress/dist
vuepress build portfolio
```

## Deploy with Netlify

Import your site in Netlify

1. Create a new site in Netlify and import your repository.
2. Set the build command to: `npm run site:build`
3. Set the publish directory to `portfolio/.vuepress/dist`

That's it, now your site gets deployed automatically on `git push`

## Forestry (Content Management)

This project has been pre-configured to work with Forestry, just import your repository ✨
Any changes you make will be commited back to the repo, and deployed if you're using Netlify.

[![Import this project into Forestry](https://assets.forestry.io/import-to-forestryK.svg)](https://app.forestry.io/quick-start?repo=forestryio/portfolio-vuepress&provider=github&engine=vuepress)
