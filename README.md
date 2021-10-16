# Gaucho Website

This website is built using [Docusaurus 2](https://docusaurus.io/), a modern static website generator.

## Development
* The docs branch is https://github.com/angrykoala/gaucho/tree/docs.
* Commands for Development:
   * npm install
   * npm docusaurus,
   * npm start
   * npm run build
   * npm run swizzle
   * npm run deploy
   * npm run clear
   * npm run serve
   * npm run write-translations
   * npm run write-heading-ids
* Folders:
   * /docs: Docs pages corresponding to items in menu(introduction,getting started etc) on Docs page.
   * /src/pages: Pages for each item in page menu.
**Modifications to Docs should be done against /docs branch.**
* Instructions to deploy (only for collaborators):
   * npm serve will upload source code to https://github.com/angrykoala/gaucho/tree/gh-pages)


## Deploy
* npm run deploy - This will deploy to GitHub pages (branch gh-pages)
