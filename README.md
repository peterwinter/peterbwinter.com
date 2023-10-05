# peterbwinter.com

This is the build repo.
It uses vue + nuxt to 
let me develop and interate by serving the Vue code as a single page app.

Then when it's ready, I use the generate command to
create all the files for a static website.

[The suboptimal bit]
All that's left is to copy the generated code into my other repo:
`peterbwinter.github.io`
push the changes to github and the new site will be live.

## Build Setup

```bash
# install dependencies
$ yarn install

# serve with hot reload at localhost:3000
$ yarn dev

# build for production and launch server
$ yarn build
$ yarn start

# generate static project
$ yarn generate
```

For detailed explanation on how things work, check out [Nuxt.js docs](https://nuxtjs.org).
