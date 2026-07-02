![Seneca](http://senecajs.org/files/assets/seneca-logo.png)
> A [Seneca.js](http://senecajs.org) plugin

# @seneca/eventbrite-provider

[![npm version](https://img.shields.io/npm/v/@seneca/eventbrite-provider.svg)](https://npmjs.com/package/@seneca/eventbrite-provider)
[![build](https://github.com/senecajs/seneca-eventbrite-provider/actions/workflows/build.yml/badge.svg)](https://github.com/senecajs/seneca-eventbrite-provider/actions/workflows/build.yml)
[![Known Vulnerabilities](https://snyk.io/test/github/senecajs/seneca-eventbrite-provider/badge.svg)](https://snyk.io/test/github/senecajs/seneca-eventbrite-provider)
[![Coverage Status](https://coveralls.io/repos/github/senecajs/seneca-eventbrite-provider/badge.svg?branch=main)](https://coveralls.io/github/senecajs/seneca-eventbrite-provider?branch=main)
[![DeepScan grade](https://deepscan.io/api/teams/5016/projects/19458/branches/505693/badge/grade.svg)](https://deepscan.io/dashboard#view=project&tid=5016&pid=19458&bid=505693)
[![Maintainability](https://api.codeclimate.com/v1/badges/562abed571a4f6412c3a/maintainability)](https://codeclimate.com/github/senecajs/seneca-eventbrite-provider/maintainability)

| ![Voxgig](https://www.voxgig.com/res/img/vgt01r.png) | This open source module is sponsored and supported by [Voxgig](https://www.voxgig.com). |
|---|---|

## Install

```sh
npm install @seneca/eventbrite-provider
```

## Quick Example

```js
require('seneca')()
  .use('@seneca/eventbrite-provider')
```

## More Examples

See [test/](test/) for more usage examples.

## Motivation

A [Seneca.js](http://senecajs.org) plugin.

## Support

If you're using this module and need help, you can:

- Post a [github issue](https://github.com/senecajs/seneca-eventbrite-provider/issues)
- Tweet to [@senecajs](http://twitter.com/senecajs)
- Ask on the [Gitter](https://gitter.im/senecajs/seneca)

## API

### Options

* `debug` : boolean <i><small>false</small></i>


Set plugin options when loading with:
```js


seneca.use('EventbriteProvider', { name: value, ... })


```


<small>Note: <code>foo.bar</code> in the list above means 
<code>{ foo: { bar: ... } }</code></small> 



<!--END:options-->

<!--START:action-list-->

### Action Patterns

* [role:entity,base:eventbrite,cmd:load,name:event,zone:provider](#-roleentitybaseeventbritecmdloadnameeventzoneprovider-)
* [role:entity,base:eventbrite,cmd:save,name:event,zone:provider](#-roleentitybaseeventbritecmdsavenameeventzoneprovider-)


<!--END:action-list-->

<!--START:action-desc-->

### Action Descriptions

### &laquo; `role:entity,base:eventbrite,cmd:load,name:event,zone:provider` &raquo;

Load an Eventbrite event data into an entity.



----------
### &laquo; `role:entity,base:eventbrite,cmd:save,name:event,zone:provider` &raquo;

Update an Eventbrite event data from an entity.



----------


<!--END:action-desc-->

## Contributing

The [Senecajs org](https://github.com/senecajs/) encourages open participation. If you feel you can help in any way, be it with documentation, examples, extra testing, or new features please get in touch.

### Running tests

```sh
npm run test
```

## Background

Part of the [Senecajs org](https://github.com/senecajs/).
