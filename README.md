# Awesome Drupal & JSON:API

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

Check out [Ecosystem modules for JSON:API \| Drupal.org](https://www.drupal.org/project/jsonapi/ecosystem) to getlist of modules marked by maintainers as related to JSON:API

| Name | Core Compatibility | Short description |
|---| ---| ---|
|[Commerce API](https://www.drupal.org/project/commerce_api)| 8.x |  Extends the JSON:API implementation provided by Drupal for the Commerce module and its ecosystem. It adds capabilities beyond the default create, read, update, and delete operations for entities to support actions required to work with a decoupled ecommerce system.
|[Entity Router](https://www.drupal.org/project/entity_router)| 8.x | Lookup entities by their paths/redirects and convert to a given format.
|[Entity Share](https://www.drupal.org/project/entity_share) | 8.x | Entity Share is a collection of modules allowing you to share content entities like nodes, taxonomy terms, medias etc. between different Drupal instances.
|[EzContent API - Enhanced De-coupled CMS Experience](https://www.drupal.org/project/ezcontent_api) | 8.x | This module adds JSON API functionality to [EZContent](https://www.drupal.org/project/ezcontent) profile.
|[Fluid Comment](https://www.drupal.org/project/fluid_comment)| 8.x | Fluid comment provides a new comment field formatter that replaces Drupal's default comment field with a client-side component that lets you add new comments, reply to comments and moderate comments without ever leaving or reloading the page.
|[JSON:API Access](https://www.drupal.org/project/jsonapi_access)| 8.x | It provides access checks for any entity operations in the JSON response. Based on JSONAPI:Extras.
|[JSON:API Boost](https://www.drupal.org/project/jsonapi_boost) | 8.x | Improves the performance of the JSON:API module by cache warming your resource types.
|[JSON:API Comment](https://www.drupal.org/project/jsonapi_comment) | 8.x | This module adds additional JSON:API compliant routes that enhance the developer experience of creating progressively decoupled or fully decoupled comment functionality.
|[JSON:API Cross Bundles](https://www.drupal.org/project/jsonapi_cross_bundles) | 8.x | Add cross-bundle resource collections for Drupal's JSON API module.
|[JSON:API Etag](https://www.drupal.org/sandbox/gabesullice/3132553)| 8.x sandbox | Adds Etag and If-None-Match support to JSON:API routes. This is most useful for improving the performance of polling requests to JSON:API resources because it eliminates the browser's need to download an unchanged response body. Additionally, when coupled with client-side rendering, the difference between 200 OK and 304 Not modified response statuses can be used to limit unnecessary DOM rendering.
|[JSON:API Explorer](https://www.drupal.org/project/jsonapi_explorer)| 8.x | The JSON:API Explorer is an interactive web application for exploring your JSON:API server.
|[JSON:API Flag](https://www.drupal.org/project/jsonapi_flag)| 8.x| This module exposes current user flaggings and entity flag counts over JSON:API Resources.
|[JSON:API Extras](https://www.drupal.org/project/jsonapi_extras)| 8.x | The JSON:API module in code provides zero configuration out of the box. Use JSON:API Extras to customize your API. JSON:API Extras provides a means to override and provide limited configurations to the default zero-configuration implementation provided by the JSON:API in Core.|
|[JSON:API Hypermedia](https://www.drupal.org/project/jsonapi_hypermedia)|8.8^|It adds support for rich, dynamic linking between your application's resources. It does not add any links of its own. Instead, it provides a plugin system for other modules to leverage.
|[JSON:API Include](https://www.drupal.org/project/jsonapi_include)| 8.x | JSON API Include allow merge include and relationship data of JSON API.
|[JSON:API Reference](https://www.drupal.org/project/jsonapi_reference) | 8.x | Provides a field type Typed Resource Object, that is similar to an entity reference field. However, rather than refer to an entity on the same Drupal installation, this refers to a resource object exposed via JSON:API.
|[JSON:API Resources](https://www.drupal.org/project/jsonapi_resources)| 8.x | Makes it possible to define custom JSON:API routes. It does not define any custom routes of its own.
|[JSON:API Schema](https://www.drupal.org/project/jsonapi_schema)| 8.x | JSON:API Schema provides [JSON-Schema](https://json-schema.org/) formatted schemas for JSON:API resources.
|[JSON:API Search API](https://www.drupal.org/project/jsonapi_search_api) | 8.x | This module adds JSON:API resources that allows you to query your Search API indexes using the JSON:API spec.
|[JSON:API Server Push](https://www.drupal.org/project/jsonapi_push) | 8.x | Experimental module that adds HTTP/2 server push capabilities to JSON:API. Not tested for production use.
|[JSON:API User Resources](https://www.drupal.org/project/jsonapi_user_resources) | 8.x | Provides JSON:API enhancements for user accounts using the [JSON:API Resources \| Drupal.org](https://www.drupal.org/project/jsonapi_resources).
|[JSON:API Views](https://www.drupal.org/project/jsonapi_views) | 8.x | Creates [JSON:API Resources \| Drupal.org](https://www.drupal.org/project/jsonapi_resources) routes for [Views module](https://www.drupal.org/docs/8/core/modules/views).
|[JSONAPI Flysystem Uploader](https://www.drupal.org/project/jsonapi_flysystem_uploader)| 8.x | Entities may have a JSON API representation automatically uploaded to S3 or other file storage systems upon creation. This is handled using the Flysystem module and library. Data will be stored in a file named "[uuid].json" based upon the entity's UUID value.|
|[Open Social JSON:API](https://www.drupal.org/project/social_json_api)| 8.x | Social JSON API provides an API which can be used with various entities.
|[Subrequests](https://www.drupal.org/project/subrequests)| 8.x | Tell the system to execute several requests in a single bootstrap. Then return all the things.



### Clients

Please refer to the list maintained on jsonapi.org : [JSON:API — Implementations](https://jsonapi.org/implementations/)


### Distributions

| Name | Source | Short description |
|---| ---| ---|
| [Contenta CMS](http://www.contentacms.org/) | [GitHub](https://github.com/contentacms) | **Content deserves a special mention.** Contenta is an API-First Drupal distribution.
|[EZContent](https://www.drupal.org/project/ezcontent) | Drupal.org | EzContent is a Drupal installation profile that addresses common content management pain points and accelerates CMS implementations.

### Authentication


| Name | Core Compatibility | Short description |
|---| ---| ---|
|[OAuth2 JWT SSO](https://www.drupal.org/project/oauth2_jwt_sso) | 8.x | OAuth2 JWT Single Sign On Module configures Drupal to use remote and centralized authentication service. This module works with any SSO provider which uses OAuth2 as the authentication framework, and JWT as the Bearer token. Therefore, this module works with Drupal's own OAuth 2.0.
|[Simple OAuth](https://www.drupal.org/project/simple_oauth) | 8.x | Simple OAuth is an implementation of the [OAuth 2.0 Authorization Framework RFC](https://tools.ietf.org/html/rfc6749).






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
