# Drupal & JSON:API

TOC

- [Drupal](#drupal)
- [Decoupled Frontend](#decoupled-frontend)
- [Support](#support)
- [Read](#read)
- [FAQ](#faq)
- [Contributing to this document](#contribute)

---

## Drupal

### Modules

| Name | Core Compatibility | Short description |
|---| ---| ---|
|[JSON:API Access](https://www.drupal.org/project/jsonapi_access)| 8.x | It provides access checks for any entity operations in the JSON response. Based on JSONAPI:Extras.
|[JSON:API Extras](https://www.drupal.org/project/jsonapi_extras)| 8.x | The JSON:API module in code provides zero configuration out of the box. Use JSON:API Extras to customize your API. JSON:API Extras provides a means to override and provide limited configurations to the default zero-configuration implementation provided by the JSON:API in Core.
|[JSON:API Hypermedia](https://www.drupal.org/project/jsonapi_hypermedia)|8.8^|It adds support for rich, dynamic linking between your application's resources. It does not add any links of its own. Instead, it provides a plugin system for other modules to leverage.
| [JSON:API Schema](https://www.drupal.org/project/jsonapi_schema)| 8.x | JSON:API Schema provides [JSON-Schema](https://json-schema.org/) formatted schemas for JSON:API resources.
|[Subrequests](https://www.drupal.org/project/subrequests)| 8.x | Tell the system to execute several requests in a single bootstrap. Then return all the things.




### Distributions

| Name | Source | Short description |
|---| ---| ---|
| [Contenta CMS](http://www.contentacms.org/) | [GitHub](https://github.com/contentacms) | **Content deserves a special mention.** Contenta is an API-First Drupal distribution.

## Decoupled Frontend

### Frameworks

| Name | Ecosystem | Short description |
|---| ---| ---|
| [ContentaJS](https://github.com/contentacms/contentajs) | Javascript | The Node.js counterpart for Contenta CMS distribution in Drupal.
| [Druxt.js](https://github.com/druxt/druxt.js)| [GitHub](https://github.com/druxt/druxt.js) | Druxt.js connects your Drupal backend to your Nuxt.js frontend through the power of Drupal's JSON API.

### Libraries

Node Packages
| Name | Ecosystem | Short description |
|---| ---| ---|
| [Drupal JSON:API Extractor](https://www.npmjs.com/package/drupal-jsonapi-extractor)| npm | Crawl through a Drupal produced json:api and save the resulting data to static json files in directory structures to allow easy access to the files.
| [Drupal JSON-API Params](https://www.npmjs.com/package/drupal-jsonapi-params)| npm | Provides a helper Class to create the required query.
| [juissy](https://www.npmjs.com/package/juissy) | npm/GitHub | Juissy is a minimal experimental JSON API client for Drupal.
|[jsona](https://www.npmjs.com/package/jsona) |npm/GitHub|Framework agnostic, customizable library that provide data formatters to simplify work with JSON API v1.0 specification.




GithHub Repo
| Name | Ecosystem | Short description |
|---| ---| ---|


### Support

- [Drupal Slack](https://drupal.slack.com) [#contenta](https://app.slack.com/client/T06GX3JTS/C5A70F7D1/thread/C5A70F7D1-1594978144.226100)

### Read

- [The JSON:API specification website](https://jsonapi.org/)
- [Drupal.org guide about JSON:API](https://www.drupal.org/docs/core-modules-and-themes/core-modules/jsonapi-module/jsonapi)


### FAQ


Q : Is this a question?

A : This is an answer.

...



---

### Contribute

Please feel free to clone this repo, add your module/library and create a Pull Request.

Guidelines
- Entries in tables are to be sorted alphabetically

Maintained By 
- [D34dMan](https://github.com/d34dman)
