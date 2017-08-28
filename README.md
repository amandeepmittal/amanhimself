# amanhimself

[![Greenkeeper badge](https://badges.greenkeeper.io/amandeepmittal/amanhimself.svg)](https://greenkeeper.io/)
An npm package about myself.

[![npm](https://img.shields.io/npm/v/amanhimself.svg?style=flat-square)](https://www.npmjs.org/package/amanhimself)
[![npm](https://img.shields.io/npm/dm/amanhimself.svg?style=flat-square)](https://www.npmjs.org/package/amanhimself)
[![npm](https://img.shields.io/npm/l/amanhimself.svg?style=flat-square)](https://www.npmjs.org/package/amanhimself)

### Installation
`$npm install -S amanhimself`

### Usage
```javascript
const aman = require('amanhimself');

console.log(aman.name.first);
//=> 'aman'
console.log(aman.projects.jade.description);
//=> Jade/Pug snippets package for Atom.
```

### API
* name
  * first
  * last
  * full
* description
* links
  * website
  * twitter
  * github
  * blog
  * medium
  * npm
  * atom
* skills
  * specialities
  * serverSide
  * clientSide
  * database
  * templateEngines
  * tools
  * editors
* projects