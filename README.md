# api documentation for  [remarkable (v1.7.1)](https://github.com/jonschlinkert/remarkable)  [![npm package](https://img.shields.io/npm/v/npmdoc-remarkable.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-remarkable) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-remarkable.svg)](https://travis-ci.org/npmdoc/node-npmdoc-remarkable)
#### Markdown parser, done right. 100% Commonmark support, extensions, syntax plugins, high speed - all in one.

[![NPM](https://nodei.co/npm/remarkable.png?downloads=true)](https://www.npmjs.com/package/remarkable)

[![apidoc](https://npmdoc.github.io/node-npmdoc-remarkable/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-remarkable_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-remarkable/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-remarkable/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-remarkable/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bin": {
        "remarkable": "./bin/remarkable.js"
    },
    "bugs": {
        "url": "https://github.com/jonschlinkert/remarkable/issues"
    },
    "contributors": [
        {
            "url": "https://github.com/dohliam"
        },
        {
            "url": "https://github.com/loveencounterflow"
        },
        {
            "url": "https://github.com/vyp"
        },
        {
            "name": "Adam Misiorny",
            "email": "adam.misiorny@gmail.com",
            "url": "http://bitnoi.se"
        },
        {
            "name": "Akuma",
            "email": "ihuangwj@gmail.com",
            "url": "https://github.com/akuma"
        },
        {
            "name": "Alex Kocharin",
            "email": "alex@kocharin.ru",
            "url": "https://github.com/rlidwka"
        },
        {
            "name": "Amila Welihinda",
            "email": "amilajack@gmail.com",
            "url": "http://amilawelihinda.com"
        },
        {
            "name": "Brenard Cubacub",
            "url": "bren.me"
        },
        {
            "name": "Denis Sokolov",
            "email": "denis@sokolov.cc",
            "url": "http://sokolov.cc"
        },
        {
            "name": "Eugene Sharygin",
            "url": "https://github.com/eush77"
        },
        {
            "name": "Harry Llewelyn",
            "email": "advocation@gmail.com",
            "url": "http://mynameisharry.com"
        },
        {
            "name": "Joey Baker",
            "email": "joey@byjoeybaker.com",
            "url": "https://byjoeybaker.com"
        },
        {
            "name": "Jon Schlinkert",
            "email": "jon.schlinkert@sellside.com",
            "url": "http://twitter.com/jonschlinkert"
        },
        {
            "name": "Julian Lam",
            "email": "julian@nodebb.org",
            "url": "https://www.nodebb.org"
        },
        {
            "name": "Lucas Parry",
            "url": "https://github.com/lparry"
        },
        {
            "name": "Luke Horvat",
            "email": "lukehorvat@gmail.com",
            "url": "http://lukehorvat.com"
        },
        {
            "name": "Mariusz Nowak",
            "email": "medyk@medikoo.com",
            "url": "http://www.medikoo.com"
        },
        {
            "name": "Mathias Bynens",
            "url": "https://mathiasbynens.be"
        },
        {
            "name": "Mathieu Lemoine",
            "url": "https://github.com/lemoinem"
        },
        {
            "name": "Matthew Mueller",
            "email": "mattmuelle@gmail.com",
            "url": "https://standupjack.com"
        },
        {
            "name": "Nik Nyby",
            "url": "http://nikolas.us.to"
        },
        {
            "name": "Per Kristian Næss-Fladset",
            "url": "https://github.com/pkfladset"
        },
        {
            "name": "Peter deHaan",
            "url": "http://about.me/peterdehaan"
        },
        {
            "name": "Rome Li",
            "url": "https://github.com/akaroml"
        },
        {
            "name": "Takezoe,Tomoaki",
            "email": "sumito3478@gmail.com",
            "url": "@sumito3478"
        },
        {
            "name": "Tom Byrer",
            "url": "https://github.com/tomByrer"
        },
        {
            "name": "Tom MacWright",
            "email": "tom@macwright.org",
            "url": "http://macwright.org"
        },
        {
            "name": "Una Ma",
            "email": "maruilian11@cdnjs.com.tw",
            "url": "https://github.com/maruilian11"
        },
        {
            "name": "Vitaly Puzrin",
            "email": "vitaly@rcdesign.ru",
            "url": "http://gravatar.com/puzrin"
        }
    ],
    "dependencies": {
        "argparse": "~0.1.15",
        "autolinker": "~0.15.0"
    },
    "description": "Markdown parser, done right. 100% Commonmark support, extensions, syntax plugins, high speed - all in one.",
    "devDependencies": {
        "ansi": "^0.3.0",
        "benchmark": "^1.0.0",
        "commonmark": "0.12.0",
        "gulp-format-md": "^0.1.10",
        "highlight.js": "^9.7.0",
        "marked": "0.3.2",
        "mocha": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "aaca4972100b66a642a63a1021ca4bac1be3bff6",
        "tarball": "https://registry.npmjs.org/remarkable/-/remarkable-1.7.1.tgz"
    },
    "engines": {
        "node": ">= 0.10.0"
    },
    "files": [
        "bin",
        "dist",
        "index.js",
        "lib"
    ],
    "homepage": "https://github.com/jonschlinkert/remarkable",
    "keywords": [
        "commonmark",
        "markdown",
        "md",
        "parse",
        "parser",
        "process",
        "remarkable",
        "render",
        "renderer",
        "text"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "doowb",
            "email": "brian.woodward@gmail.com"
        },
        {
            "name": "joeybaker",
            "email": "joey@byjoeybaker.com"
        },
        {
            "name": "jonschlinkert",
            "email": "github@sellside.com"
        },
        {
            "name": "matthewmueller",
            "email": "mattmuelle@gmail.com"
        },
        {
            "name": "nikolas",
            "email": "nikolas@gnu.org"
        },
        {
            "name": "pkfladset",
            "email": "fladset@gmail.com"
        },
        {
            "name": "spicyj",
            "email": "ben@benalpert.com"
        }
    ],
    "name": "remarkable",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jonschlinkert/remarkable.git"
    },
    "scripts": {
        "test": "make test"
    },
    "verb": {
        "toc": false,
        "layout": "nil",
        "tasks": [
            "readme"
        ],
        "plugins": [
            "gulp-format-md"
        ],
        "lint": {
            "reflinks": true
        }
    },
    "version": "1.7.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module remarkable](#apidoc.module.remarkable)
1.  [function <span class="apidocSignatureSpan">remarkable.</span>parser_block ()](#apidoc.element.remarkable.parser_block)
1.  [function <span class="apidocSignatureSpan">remarkable.</span>parser_core ()](#apidoc.element.remarkable.parser_core)
1.  [function <span class="apidocSignatureSpan">remarkable.</span>parser_inline ()](#apidoc.element.remarkable.parser_inline)
1.  [function <span class="apidocSignatureSpan">remarkable.</span>renderer ()](#apidoc.element.remarkable.renderer)
1.  [function <span class="apidocSignatureSpan">remarkable.</span>ruler ()](#apidoc.element.remarkable.ruler)
1.  object <span class="apidocSignatureSpan">remarkable.</span>parser_block.prototype
1.  object <span class="apidocSignatureSpan">remarkable.</span>parser_core.prototype
1.  object <span class="apidocSignatureSpan">remarkable.</span>parser_inline.prototype
1.  object <span class="apidocSignatureSpan">remarkable.</span>renderer.prototype
1.  object <span class="apidocSignatureSpan">remarkable.</span>ruler.prototype
1.  object <span class="apidocSignatureSpan">remarkable.</span>rules
1.  object <span class="apidocSignatureSpan">remarkable.</span>utils

#### [module remarkable.parser_block](#apidoc.module.remarkable.parser_block)
1.  [function <span class="apidocSignatureSpan">remarkable.</span>parser_block ()](#apidoc.element.remarkable.parser_block.parser_block)

#### [module remarkable.parser_block.prototype](#apidoc.module.remarkable.parser_block.prototype)
1.  [function <span class="apidocSignatureSpan">remarkable.parser_block.prototype.</span>parse (str, options, env, outTokens)](#apidoc.element.remarkable.parser_block.prototype.parse)
1.  [function <span class="apidocSignatureSpan">remarkable.parser_block.prototype.</span>tokenize (state, startLine, endLine)](#apidoc.element.remarkable.parser_block.prototype.tokenize)

#### [module remarkable.parser_core](#apidoc.module.remarkable.parser_core)
1.  [function <span class="apidocSignatureSpan">remarkable.</span>parser_core ()](#apidoc.element.remarkable.parser_core.parser_core)

#### [module remarkable.parser_core.prototype](#apidoc.module.remarkable.parser_core.prototype)
1.  [function <span class="apidocSignatureSpan">remarkable.parser_core.prototype.</span>process (state)](#apidoc.element.remarkable.parser_core.prototype.process)

#### [module remarkable.parser_inline](#apidoc.module.remarkable.parser_inline)
1.  [function <span class="apidocSignatureSpan">remarkable.</span>parser_inline ()](#apidoc.element.remarkable.parser_inline.parser_inline)

#### [module remarkable.parser_inline.prototype](#apidoc.module.remarkable.parser_inline.prototype)
1.  [function <span class="apidocSignatureSpan">remarkable.parser_inline.prototype.</span>parse (str, options, env, outTokens)](#apidoc.element.remarkable.parser_inline.prototype.parse)
1.  [function <span class="apidocSignatureSpan">remarkable.parser_inline.prototype.</span>skipToken (state)](#apidoc.element.remarkable.parser_inline.prototype.skipToken)
1.  [function <span class="apidocSignatureSpan">remarkable.parser_inline.prototype.</span>tokenize (state)](#apidoc.element.remarkable.parser_inline.prototype.tokenize)

#### [module remarkable.renderer](#apidoc.module.remarkable.renderer)
1.  [function <span class="apidocSignatureSpan">remarkable.</span>renderer ()](#apidoc.element.remarkable.renderer.renderer)

#### [module remarkable.renderer.prototype](#apidoc.module.remarkable.renderer.prototype)
1.  [function <span class="apidocSignatureSpan">remarkable.renderer.prototype.</span>render (tokens, options, env)](#apidoc.element.remarkable.renderer.prototype.render)
1.  [function <span class="apidocSignatureSpan">remarkable.renderer.prototype.</span>renderInline (tokens, options, env)](#apidoc.element.remarkable.renderer.prototype.renderInline)

#### [module remarkable.ruler](#apidoc.module.remarkable.ruler)
1.  [function <span class="apidocSignatureSpan">remarkable.</span>ruler ()](#apidoc.element.remarkable.ruler.ruler)

#### [module remarkable.ruler.prototype](#apidoc.module.remarkable.ruler.prototype)
1.  [function <span class="apidocSignatureSpan">remarkable.ruler.prototype.</span>__compile__ ()](#apidoc.element.remarkable.ruler.prototype.__compile__)
1.  [function <span class="apidocSignatureSpan">remarkable.ruler.prototype.</span>__find__ (name)](#apidoc.element.remarkable.ruler.prototype.__find__)
1.  [function <span class="apidocSignatureSpan">remarkable.ruler.prototype.</span>after (afterName, ruleName, fn, options)](#apidoc.element.remarkable.ruler.prototype.after)
1.  [function <span class="apidocSignatureSpan">remarkable.ruler.prototype.</span>at (name, fn, options)](#apidoc.element.remarkable.ruler.prototype.at)
1.  [function <span class="apidocSignatureSpan">remarkable.ruler.prototype.</span>before (beforeName, ruleName, fn, options)](#apidoc.element.remarkable.ruler.prototype.before)
1.  [function <span class="apidocSignatureSpan">remarkable.ruler.prototype.</span>disable (list)](#apidoc.element.remarkable.ruler.prototype.disable)
1.  [function <span class="apidocSignatureSpan">remarkable.ruler.prototype.</span>enable (list, strict)](#apidoc.element.remarkable.ruler.prototype.enable)
1.  [function <span class="apidocSignatureSpan">remarkable.ruler.prototype.</span>getRules (chainName)](#apidoc.element.remarkable.ruler.prototype.getRules)
1.  [function <span class="apidocSignatureSpan">remarkable.ruler.prototype.</span>push (ruleName, fn, options)](#apidoc.element.remarkable.ruler.prototype.push)

#### [module remarkable.rules](#apidoc.module.remarkable.rules)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>abbr_close ()](#apidoc.element.remarkable.rules.abbr_close)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>abbr_open (tokens, idx)](#apidoc.element.remarkable.rules.abbr_open)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>blockquote_close (tokens, idx)](#apidoc.element.remarkable.rules.blockquote_close)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>blockquote_open ()](#apidoc.element.remarkable.rules.blockquote_open)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>bullet_list_close (tokens, idx)](#apidoc.element.remarkable.rules.bullet_list_close)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>bullet_list_open ()](#apidoc.element.remarkable.rules.bullet_list_open)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>code (tokens, idx)](#apidoc.element.remarkable.rules.code)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>dd_close ()](#apidoc.element.remarkable.rules.dd_close)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>dd_open ()](#apidoc.element.remarkable.rules.dd_open)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>del_close ()](#apidoc.element.remarkable.rules.del_close)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>del_open ()](#apidoc.element.remarkable.rules.del_open)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>dl_close ()](#apidoc.element.remarkable.rules.dl_close)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>dl_open ()](#apidoc.element.remarkable.rules.dl_open)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>dt_close ()](#apidoc.element.remarkable.rules.dt_close)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>dt_open ()](#apidoc.element.remarkable.rules.dt_open)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>em_close ()](#apidoc.element.remarkable.rules.em_close)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>em_open ()](#apidoc.element.remarkable.rules.em_open)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>fence (tokens, idx, options, env, instance)](#apidoc.element.remarkable.rules.fence)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>footnote_anchor (tokens, idx)](#apidoc.element.remarkable.rules.footnote_anchor)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>footnote_block_close ()](#apidoc.element.remarkable.rules.footnote_block_close)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>footnote_block_open (tokens, idx, options)](#apidoc.element.remarkable.rules.footnote_block_open)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>footnote_close ()](#apidoc.element.remarkable.rules.footnote_close)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>footnote_open (tokens, idx)](#apidoc.element.remarkable.rules.footnote_open)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>footnote_ref (tokens, idx)](#apidoc.element.remarkable.rules.footnote_ref)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>getBreak (tokens, idx)](#apidoc.element.remarkable.rules.getBreak)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>hardbreak (tokens, idx, options)](#apidoc.element.remarkable.rules.hardbreak)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>heading_close (tokens, idx)](#apidoc.element.remarkable.rules.heading_close)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>heading_open (tokens, idx)](#apidoc.element.remarkable.rules.heading_open)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>hr (tokens, idx, options)](#apidoc.element.remarkable.rules.hr)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>htmlblock (tokens, idx)](#apidoc.element.remarkable.rules.htmlblock)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>htmltag (tokens, idx)](#apidoc.element.remarkable.rules.htmltag)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>image (tokens, idx, options)](#apidoc.element.remarkable.rules.image)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>ins_close ()](#apidoc.element.remarkable.rules.ins_close)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>ins_open ()](#apidoc.element.remarkable.rules.ins_open)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>link_close ()](#apidoc.element.remarkable.rules.link_close)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>link_open (tokens, idx, options)](#apidoc.element.remarkable.rules.link_open)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>list_item_close ()](#apidoc.element.remarkable.rules.list_item_close)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>list_item_open ()](#apidoc.element.remarkable.rules.list_item_open)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>mark_close ()](#apidoc.element.remarkable.rules.mark_close)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>mark_open ()](#apidoc.element.remarkable.rules.mark_open)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>ordered_list_close (tokens, idx)](#apidoc.element.remarkable.rules.ordered_list_close)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>ordered_list_open (tokens, idx)](#apidoc.element.remarkable.rules.ordered_list_open)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>paragraph_close (tokens, idx)](#apidoc.element.remarkable.rules.paragraph_close)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>paragraph_open (tokens, idx)](#apidoc.element.remarkable.rules.paragraph_open)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>softbreak (tokens, idx, options)](#apidoc.element.remarkable.rules.softbreak)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>strong_close ()](#apidoc.element.remarkable.rules.strong_close)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>strong_open ()](#apidoc.element.remarkable.rules.strong_open)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>sub (tokens, idx)](#apidoc.element.remarkable.rules.sub)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>sup (tokens, idx)](#apidoc.element.remarkable.rules.sup)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>table_close ()](#apidoc.element.remarkable.rules.table_close)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>table_open ()](#apidoc.element.remarkable.rules.table_open)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>tbody_close ()](#apidoc.element.remarkable.rules.tbody_close)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>tbody_open ()](#apidoc.element.remarkable.rules.tbody_open)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>td_close ()](#apidoc.element.remarkable.rules.td_close)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>td_open (tokens, idx)](#apidoc.element.remarkable.rules.td_open)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>text (tokens, idx)](#apidoc.element.remarkable.rules.text)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>th_close ()](#apidoc.element.remarkable.rules.th_close)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>th_open (tokens, idx)](#apidoc.element.remarkable.rules.th_open)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>thead_close ()](#apidoc.element.remarkable.rules.thead_close)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>thead_open ()](#apidoc.element.remarkable.rules.thead_open)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>tr_close ()](#apidoc.element.remarkable.rules.tr_close)
1.  [function <span class="apidocSignatureSpan">remarkable.rules.</span>tr_open ()](#apidoc.element.remarkable.rules.tr_open)
1.  object <span class="apidocSignatureSpan">remarkable.rules.</span>fence_custom

#### [module remarkable.utils](#apidoc.module.remarkable.utils)
1.  [function <span class="apidocSignatureSpan">remarkable.utils.</span>assign (obj)](#apidoc.element.remarkable.utils.assign)
1.  [function <span class="apidocSignatureSpan">remarkable.utils.</span>escapeHtml (str)](#apidoc.element.remarkable.utils.escapeHtml)
1.  [function <span class="apidocSignatureSpan">remarkable.utils.</span>fromCodePoint (c)](#apidoc.element.remarkable.utils.fromCodePoint)
1.  [function <span class="apidocSignatureSpan">remarkable.utils.</span>has (object, key)](#apidoc.element.remarkable.utils.has)
1.  [function <span class="apidocSignatureSpan">remarkable.utils.</span>isString (obj)](#apidoc.element.remarkable.utils.isString)
1.  [function <span class="apidocSignatureSpan">remarkable.utils.</span>isValidEntityCode (c)](#apidoc.element.remarkable.utils.isValidEntityCode)
1.  [function <span class="apidocSignatureSpan">remarkable.utils.</span>replaceEntities (str)](#apidoc.element.remarkable.utils.replaceEntities)
1.  [function <span class="apidocSignatureSpan">remarkable.utils.</span>unescapeMd (str)](#apidoc.element.remarkable.utils.unescapeMd)



# <a name="apidoc.module.remarkable"></a>[module remarkable](#apidoc.module.remarkable)

#### <a name="apidoc.element.remarkable.parser_block"></a>[function <span class="apidocSignatureSpan">remarkable.</span>parser_block ()](#apidoc.element.remarkable.parser_block)
- description and source-code
```javascript
function ParserBlock() {
  this.ruler = new Ruler();
  for (var i = 0; i < _rules.length; i++) {
    this.ruler.push(_rules[i][0], _rules[i][1], {
      alt: (_rules[i][2] || []).slice()
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.parser_core"></a>[function <span class="apidocSignatureSpan">remarkable.</span>parser_core ()](#apidoc.element.remarkable.parser_core)
- description and source-code
```javascript
function Core() {
  this.options = {};
  this.ruler = new Ruler();
  for (var i = 0; i < _rules.length; i++) {
    this.ruler.push(_rules[i][0], _rules[i][1]);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.parser_inline"></a>[function <span class="apidocSignatureSpan">remarkable.</span>parser_inline ()](#apidoc.element.remarkable.parser_inline)
- description and source-code
```javascript
function ParserInline() {
  this.ruler = new Ruler();
  for (var i = 0; i < _rules.length; i++) {
    this.ruler.push(_rules[i][0], _rules[i][1]);
  }

  // Can be overridden with a custom validator
  this.validateLink = validateLink;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.renderer"></a>[function <span class="apidocSignatureSpan">remarkable.</span>renderer ()](#apidoc.element.remarkable.renderer)
- description and source-code
```javascript
function Renderer() {
  this.rules = utils.assign({}, rules);

  // exported helper, for custom rules only
  this.getBreak = rules.getBreak;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.ruler"></a>[function <span class="apidocSignatureSpan">remarkable.</span>ruler ()](#apidoc.element.remarkable.ruler)
- description and source-code
```javascript
function Ruler() {
  // List of added rules. Each element is:
  //
  // { name: XXX,
  //   enabled: Boolean,
  //   fn: Function(),
  //   alt: [ name2, name3 ] }
  //
  this.__rules__ = [];

  // Cached rule chains.
  //
  // First level - chain name, '' for default.
  // Second level - digital anchor for fast filtering by charcodes.
  //
  this.__cache__ = null;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.remarkable.parser_block"></a>[module remarkable.parser_block](#apidoc.module.remarkable.parser_block)

#### <a name="apidoc.element.remarkable.parser_block.parser_block"></a>[function <span class="apidocSignatureSpan">remarkable.</span>parser_block ()](#apidoc.element.remarkable.parser_block.parser_block)
- description and source-code
```javascript
function ParserBlock() {
  this.ruler = new Ruler();
  for (var i = 0; i < _rules.length; i++) {
    this.ruler.push(_rules[i][0], _rules[i][1], {
      alt: (_rules[i][2] || []).slice()
    });
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.remarkable.parser_block.prototype"></a>[module remarkable.parser_block.prototype](#apidoc.module.remarkable.parser_block.prototype)

#### <a name="apidoc.element.remarkable.parser_block.prototype.parse"></a>[function <span class="apidocSignatureSpan">remarkable.parser_block.prototype.</span>parse (str, options, env, outTokens)](#apidoc.element.remarkable.parser_block.prototype.parse)
- description and source-code
```javascript
parse = function (str, options, env, outTokens) {
  var state, lineStart = 0, lastTabPos = 0;
  if (!str) { return []; }

  // Normalize spaces
  str = str.replace(SPACES_RE, ' ');

  // Normalize newlines
  str = str.replace(NEWLINES_RE, '\n');

  // Replace tabs with proper number of spaces (1..4)
  if (str.indexOf('\t') >= 0) {
    str = str.replace(TABS_SCAN_RE, function (match, offset) {
      var result;
      if (str.charCodeAt(offset) === 0x0A) {
        lineStart = offset + 1;
        lastTabPos = 0;
        return match;
      }
      result = '    '.slice((offset - lineStart - lastTabPos) % 4);
      lastTabPos = offset - lineStart + 1;
      return result;
    });
  }

  state = new StateBlock(str, this, options, env, outTokens);
  this.tokenize(state, state.line, state.lineMax);
}
```
- example usage
```shell
...

http.get('http://www.w3.org/TR/html5/entities.json', function (res) {
  var body = '';
  res.on('data', function(chunk) {
    body += chunk;
  });
  res.on('end', function() {
    var entities = JSON.parse(body);
    var out = {};

    Object.keys(entities).forEach(function (entity) {
// Skip legacy - not allosed in markdown
if (entity[entity.length - 1] !== ';') { return; }

out[entity.slice(1, -1)] = strToUni(entities[entity].characters);
...
```

#### <a name="apidoc.element.remarkable.parser_block.prototype.tokenize"></a>[function <span class="apidocSignatureSpan">remarkable.parser_block.prototype.</span>tokenize (state, startLine, endLine)](#apidoc.element.remarkable.parser_block.prototype.tokenize)
- description and source-code
```javascript
tokenize = function (state, startLine, endLine) {
  var rules = this.ruler.getRules('');
  var len = rules.length;
  var line = startLine;
  var hasEmptyLines = false;
  var ok, i;

  while (line < endLine) {
    state.line = line = state.skipEmptyLines(line);
    if (line >= endLine) {
      break;
    }

    // Termination condition for nested calls.
    // Nested calls currently used for blockquotes & lists
    if (state.tShift[line] < state.blkIndent) {
      break;
    }

    // Try all possible rules.
    // On success, rule should:
    //
    // - update 'state.line'
    // - update 'state.tokens'
    // - return true

    for (i = 0; i < len; i++) {
      ok = rules[i](state, line, endLine, false);
      if (ok) {
        break;
      }
    }

    // set state.tight iff we had an empty line before current tag
    // i.e. latest empty line should not count
    state.tight = !hasEmptyLines;

    // paragraph might "eat" one newline after it in nested lists
    if (state.isEmpty(state.line - 1)) {
      hasEmptyLines = true;
    }

    line = state.line;

    if (line < endLine && state.isEmpty(line)) {
      hasEmptyLines = true;
      line++;

      // two empty lines should stop the parser in list mode
      if (line < endLine && state.parentType === 'list' && state.isEmpty(line)) { break; }
      state.line = line;
    }
  }
}
```
- example usage
```shell
...
      result = '    '.slice((offset - lineStart - lastTabPos) % 4);
      lastTabPos = offset - lineStart + 1;
      return result;
    });
  }

  state = new StateBlock(str, this, options, env, outTokens);
  this.tokenize(state, state.line, state.lineMax);
};

/**
 * Expose 'ParserBlock'
 */

module.exports = ParserBlock;
...
```



# <a name="apidoc.module.remarkable.parser_core"></a>[module remarkable.parser_core](#apidoc.module.remarkable.parser_core)

#### <a name="apidoc.element.remarkable.parser_core.parser_core"></a>[function <span class="apidocSignatureSpan">remarkable.</span>parser_core ()](#apidoc.element.remarkable.parser_core.parser_core)
- description and source-code
```javascript
function Core() {
  this.options = {};
  this.ruler = new Ruler();
  for (var i = 0; i < _rules.length; i++) {
    this.ruler.push(_rules[i][0], _rules[i][1]);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.remarkable.parser_core.prototype"></a>[module remarkable.parser_core.prototype](#apidoc.module.remarkable.parser_core.prototype)

#### <a name="apidoc.element.remarkable.parser_core.prototype.process"></a>[function <span class="apidocSignatureSpan">remarkable.parser_core.prototype.</span>process (state)](#apidoc.element.remarkable.parser_core.prototype.process)
- description and source-code
```javascript
process = function (state) {
  var i, l, rules;
  rules = this.ruler.getRules('');
  for (i = 0, l = rules.length; i < l; i++) {
    rules[i](state);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.remarkable.parser_inline"></a>[module remarkable.parser_inline](#apidoc.module.remarkable.parser_inline)

#### <a name="apidoc.element.remarkable.parser_inline.parser_inline"></a>[function <span class="apidocSignatureSpan">remarkable.</span>parser_inline ()](#apidoc.element.remarkable.parser_inline.parser_inline)
- description and source-code
```javascript
function ParserInline() {
  this.ruler = new Ruler();
  for (var i = 0; i < _rules.length; i++) {
    this.ruler.push(_rules[i][0], _rules[i][1]);
  }

  // Can be overridden with a custom validator
  this.validateLink = validateLink;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.remarkable.parser_inline.prototype"></a>[module remarkable.parser_inline.prototype](#apidoc.module.remarkable.parser_inline.prototype)

#### <a name="apidoc.element.remarkable.parser_inline.prototype.parse"></a>[function <span class="apidocSignatureSpan">remarkable.parser_inline.prototype.</span>parse (str, options, env, outTokens)](#apidoc.element.remarkable.parser_inline.prototype.parse)
- description and source-code
```javascript
parse = function (str, options, env, outTokens) {
  var state = new StateInline(str, this, options, env, outTokens);
  this.tokenize(state);
}
```
- example usage
```shell
...

http.get('http://www.w3.org/TR/html5/entities.json', function (res) {
  var body = '';
  res.on('data', function(chunk) {
    body += chunk;
  });
  res.on('end', function() {
    var entities = JSON.parse(body);
    var out = {};

    Object.keys(entities).forEach(function (entity) {
// Skip legacy - not allosed in markdown
if (entity[entity.length - 1] !== ';') { return; }

out[entity.slice(1, -1)] = strToUni(entities[entity].characters);
...
```

#### <a name="apidoc.element.remarkable.parser_inline.prototype.skipToken"></a>[function <span class="apidocSignatureSpan">remarkable.parser_inline.prototype.</span>skipToken (state)](#apidoc.element.remarkable.parser_inline.prototype.skipToken)
- description and source-code
```javascript
skipToken = function (state) {
  var rules = this.ruler.getRules('');
  var len = rules.length;
  var pos = state.pos;
  var i, cached_pos;

  if ((cached_pos = state.cacheGet(pos)) > 0) {
    state.pos = cached_pos;
    return;
  }

  for (i = 0; i < len; i++) {
    if (rules[i](state, true)) {
      state.cacheSet(pos, state.pos);
      return;
    }
  }

  state.pos++;
  state.cacheSet(pos, state.pos);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.parser_inline.prototype.tokenize"></a>[function <span class="apidocSignatureSpan">remarkable.parser_inline.prototype.</span>tokenize (state)](#apidoc.element.remarkable.parser_inline.prototype.tokenize)
- description and source-code
```javascript
tokenize = function (state) {
  var rules = this.ruler.getRules('');
  var len = rules.length;
  var end = state.posMax;
  var ok, i;

  while (state.pos < end) {

    // Try all possible rules.
    // On success, the rule should:
    //
    // - update 'state.pos'
    // - update 'state.tokens'
    // - return true
    for (i = 0; i < len; i++) {
      ok = rules[i](state, false);

      if (ok) {
        break;
      }
    }

    if (ok) {
      if (state.pos >= end) { break; }
      continue;
    }

    state.pending += state.src[state.pos++];
  }

  if (state.pending) {
    state.pushPending();
  }
}
```
- example usage
```shell
...
      result = '    '.slice((offset - lineStart - lastTabPos) % 4);
      lastTabPos = offset - lineStart + 1;
      return result;
    });
  }

  state = new StateBlock(str, this, options, env, outTokens);
  this.tokenize(state, state.line, state.lineMax);
};

/**
 * Expose 'ParserBlock'
 */

module.exports = ParserBlock;
...
```



# <a name="apidoc.module.remarkable.renderer"></a>[module remarkable.renderer](#apidoc.module.remarkable.renderer)

#### <a name="apidoc.element.remarkable.renderer.renderer"></a>[function <span class="apidocSignatureSpan">remarkable.</span>renderer ()](#apidoc.element.remarkable.renderer.renderer)
- description and source-code
```javascript
function Renderer() {
  this.rules = utils.assign({}, rules);

  // exported helper, for custom rules only
  this.getBreak = rules.getBreak;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.remarkable.renderer.prototype"></a>[module remarkable.renderer.prototype](#apidoc.module.remarkable.renderer.prototype)

#### <a name="apidoc.element.remarkable.renderer.prototype.render"></a>[function <span class="apidocSignatureSpan">remarkable.renderer.prototype.</span>render (tokens, options, env)](#apidoc.element.remarkable.renderer.prototype.render)
- description and source-code
```javascript
render = function (tokens, options, env) {
  var _rules = this.rules;
  var len = tokens.length, i = -1;
  var result = '';

  while (++i < len) {
    if (tokens[i].type === 'inline') {
      result += this.renderInline(tokens[i].children, options, env);
    } else {
      result += _rules[tokens[i].type](tokens, i, options, env, this);
    }
  }
  return result;
}
```
- example usage
```shell
...

## Usage

'''js
var Remarkable = require('remarkable');
var md = new Remarkable();

console.log(md.render('# Remarkable rulezz!'));
// => <h1>Remarkable rulezz!</h1>
'''

If installed globally with 'npm':

'''sh
cat myfile.md | remarkable
...
```

#### <a name="apidoc.element.remarkable.renderer.prototype.renderInline"></a>[function <span class="apidocSignatureSpan">remarkable.renderer.prototype.</span>renderInline (tokens, options, env)](#apidoc.element.remarkable.renderer.prototype.renderInline)
- description and source-code
```javascript
renderInline = function (tokens, options, env) {
  var _rules = this.rules;
  var len = tokens.length, i = 0;
  var result = '';

  while (len--) {
    result += _rules[tokens[i].type](tokens, i++, options, env, this);
  }

  return result;
}
```
- example usage
```shell
...
Renderer.prototype.render = function (tokens, options, env) {
  var _rules = this.rules;
  var len = tokens.length, i = -1;
  var result = '';

  while (++i < len) {
    if (tokens[i].type === 'inline') {
      result += this.renderInline(tokens[i].children, options, env);
    } else {
      result += _rules[tokens[i].type](tokens, i, options, env, this);
    }
  }
  return result;
};
...
```



# <a name="apidoc.module.remarkable.ruler"></a>[module remarkable.ruler](#apidoc.module.remarkable.ruler)

#### <a name="apidoc.element.remarkable.ruler.ruler"></a>[function <span class="apidocSignatureSpan">remarkable.</span>ruler ()](#apidoc.element.remarkable.ruler.ruler)
- description and source-code
```javascript
function Ruler() {
  // List of added rules. Each element is:
  //
  // { name: XXX,
  //   enabled: Boolean,
  //   fn: Function(),
  //   alt: [ name2, name3 ] }
  //
  this.__rules__ = [];

  // Cached rule chains.
  //
  // First level - chain name, '' for default.
  // Second level - digital anchor for fast filtering by charcodes.
  //
  this.__cache__ = null;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.remarkable.ruler.prototype"></a>[module remarkable.ruler.prototype](#apidoc.module.remarkable.ruler.prototype)

#### <a name="apidoc.element.remarkable.ruler.prototype.__compile__"></a>[function <span class="apidocSignatureSpan">remarkable.ruler.prototype.</span>__compile__ ()](#apidoc.element.remarkable.ruler.prototype.__compile__)
- description and source-code
```javascript
__compile__ = function () {
  var self = this;
  var chains = [ '' ];

  // collect unique names
  self.__rules__.forEach(function (rule) {
    if (!rule.enabled) {
      return;
    }

    rule.alt.forEach(function (altName) {
      if (chains.indexOf(altName) < 0) {
        chains.push(altName);
      }
    });
  });

  self.__cache__ = {};

  chains.forEach(function (chain) {
    self.__cache__[chain] = [];
    self.__rules__.forEach(function (rule) {
      if (!rule.enabled) {
        return;
      }

      if (chain && rule.alt.indexOf(chain) < 0) {
        return;
      }
      self.__cache__[chain].push(rule.fn);
    });
  });
}
```
- example usage
```shell
...
* @param  {String} 'chainName'
* @return {Object}
* @api private
*/

Ruler.prototype.getRules = function (chainName) {
 if (this.__cache__ === null) {
   this.__compile__();
 }
 return this.__cache__[chainName] || [];
};

/**
* Expose 'Ruler'
*/
...
```

#### <a name="apidoc.element.remarkable.ruler.prototype.__find__"></a>[function <span class="apidocSignatureSpan">remarkable.ruler.prototype.</span>__find__ (name)](#apidoc.element.remarkable.ruler.prototype.__find__)
- description and source-code
```javascript
__find__ = function (name) {
  var len = this.__rules__.length;
  var i = -1;

  while (len--) {
    if (this.__rules__[++i].name === name) {
      return i;
    }
  }
  return -1;
}
```
- example usage
```shell
...
 * @param  {String} 'name' Rule name
 * @param  {Function 'fn'
 * @param  {Object} 'options'
 * @api private
 */

Ruler.prototype.at = function (name, fn, options) {
var idx = this.__find__(name);
var opt = options || {};

if (idx === -1) {
  throw new Error('Parser rule not found: ' + name);
}

this.__rules__[idx].fn = fn;
...
```

#### <a name="apidoc.element.remarkable.ruler.prototype.after"></a>[function <span class="apidocSignatureSpan">remarkable.ruler.prototype.</span>after (afterName, ruleName, fn, options)](#apidoc.element.remarkable.ruler.prototype.after)
- description and source-code
```javascript
after = function (afterName, ruleName, fn, options) {
  var idx = this.__find__(afterName);
  var opt = options || {};

  if (idx === -1) {
    throw new Error('Parser rule not found: ' + afterName);
  }

  this.__rules__.splice(idx + 1, 0, {
    name: ruleName,
    enabled: true,
    fn: fn,
    alt: opt.alt || []
  });

  this.__cache__ = null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.ruler.prototype.at"></a>[function <span class="apidocSignatureSpan">remarkable.ruler.prototype.</span>at (name, fn, options)](#apidoc.element.remarkable.ruler.prototype.at)
- description and source-code
```javascript
at = function (name, fn, options) {
  var idx = this.__find__(name);
  var opt = options || {};

  if (idx === -1) {
    throw new Error('Parser rule not found: ' + name);
  }

  this.__rules__[idx].fn = fn;
  this.__rules__[idx].alt = opt.alt || [];
  this.__cache__ = null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.ruler.prototype.before"></a>[function <span class="apidocSignatureSpan">remarkable.ruler.prototype.</span>before (beforeName, ruleName, fn, options)](#apidoc.element.remarkable.ruler.prototype.before)
- description and source-code
```javascript
before = function (beforeName, ruleName, fn, options) {
  var idx = this.__find__(beforeName);
  var opt = options || {};

  if (idx === -1) {
    throw new Error('Parser rule not found: ' + beforeName);
  }

  this.__rules__.splice(idx, 0, {
    name: ruleName,
    enabled: true,
    fn: fn,
    alt: opt.alt || []
  });

  this.__cache__ = null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.ruler.prototype.disable"></a>[function <span class="apidocSignatureSpan">remarkable.ruler.prototype.</span>disable (list)](#apidoc.element.remarkable.ruler.prototype.disable)
- description and source-code
```javascript
disable = function (list) {
  list = !Array.isArray(list)
    ? [ list ]
    : list;

  // Search by name and disable
  list.forEach(function (name) {
    var idx = this.__find__(name);
    if (idx < 0) {
      throw new Error('Rules manager: invalid rule name ' + name);
    }
    this.__rules__[idx].enabled = false;
  }, this);

  this.__cache__ = null;
}
```
- example usage
```shell
...


### Manage rules

'''js
var md = new Remarkable();
md.inline.ruler.enable([ 'ins', 'mark' ]);
md.block.ruler.disable([ 'table', 'footnote' ]);

// Enable everything
md = new Remarkable('full', {
  html: true,
  linkify: true,
  typographer: true,
});
...
```

#### <a name="apidoc.element.remarkable.ruler.prototype.enable"></a>[function <span class="apidocSignatureSpan">remarkable.ruler.prototype.</span>enable (list, strict)](#apidoc.element.remarkable.ruler.prototype.enable)
- description and source-code
```javascript
enable = function (list, strict) {
  list = !Array.isArray(list)
    ? [ list ]
    : list;

  // In strict mode disable all existing rules first
  if (strict) {
    this.__rules__.forEach(function (rule) {
      rule.enabled = false;
    });
  }

  // Search by name and enable
  list.forEach(function (name) {
    var idx = this.__find__(name);
    if (idx < 0) {
      throw new Error('Rules manager: invalid rule name ' + name);
    }
    this.__rules__[idx].enabled = true;
  }, this);

  this.__cache__ = null;
}
```
- example usage
```shell
...
**HEADS UP!**: Experimental extensions can be changed later for something like [Critic Markup](http://criticmarkup.com/), but you
 will still be able to use old-style rules via external plugins if you prefer.


### Manage rules

'''js
var md = new Remarkable();
md.inline.ruler.enable([ 'ins', 'mark' ]);
md.block.ruler.disable([ 'table', 'footnote' ]);

// Enable everything
md = new Remarkable('full', {
html: true,
linkify: true,
typographer: true,
...
```

#### <a name="apidoc.element.remarkable.ruler.prototype.getRules"></a>[function <span class="apidocSignatureSpan">remarkable.ruler.prototype.</span>getRules (chainName)](#apidoc.element.remarkable.ruler.prototype.getRules)
- description and source-code
```javascript
getRules = function (chainName) {
  if (this.__cache__ === null) {
    this.__compile__();
  }
  return this.__cache__[chainName] || [];
}
```
- example usage
```shell
...
 * @param  {Object} 'state' Has properties like 'src', 'parser', 'options' etc
 * @param  {Number} 'startLine'
 * @param  {Number} 'endLine'
 * @api private
 */

ParserBlock.prototype.tokenize = function (state, startLine, endLine) {
var rules = this.ruler.getRules('');
var len = rules.length;
var line = startLine;
var hasEmptyLines = false;
var ok, i;

while (line < endLine) {
  state.line = line = state.skipEmptyLines(line);
...
```

#### <a name="apidoc.element.remarkable.ruler.prototype.push"></a>[function <span class="apidocSignatureSpan">remarkable.ruler.prototype.</span>push (ruleName, fn, options)](#apidoc.element.remarkable.ruler.prototype.push)
- description and source-code
```javascript
push = function (ruleName, fn, options) {
  var opt = options || {};

  this.__rules__.push({
    name: ruleName,
    enabled: true,
    fn: fn,
    alt: opt.alt || []
  });

  this.__cache__ = null;
}
```
- example usage
```shell
...
*
* @api private
*/

function ParserBlock() {
 this.ruler = new Ruler();
 for (var i = 0; i < _rules.length; i++) {
   this.ruler.push(_rules[i][0], _rules[i][1], {
     alt: (_rules[i][2] || []).slice()
   });
 }
}

/**
* Generate tokens for the given input range.
...
```



# <a name="apidoc.module.remarkable.rules"></a>[module remarkable.rules](#apidoc.module.remarkable.rules)

#### <a name="apidoc.element.remarkable.rules.abbr_close"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>abbr_close ()](#apidoc.element.remarkable.rules.abbr_close)
- description and source-code
```javascript
abbr_close = function () {
  return '</abbr>';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.abbr_open"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>abbr_open (tokens, idx)](#apidoc.element.remarkable.rules.abbr_open)
- description and source-code
```javascript
abbr_open = function (tokens, idx) {
  return '<abbr title="' + escapeHtml(replaceEntities(tokens[idx].title)) + '">';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.blockquote_close"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>blockquote_close (tokens, idx)](#apidoc.element.remarkable.rules.blockquote_close)
- description and source-code
```javascript
blockquote_close = function (tokens, idx) {
  return '</blockquote>' + getBreak(tokens, idx);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.blockquote_open"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>blockquote_open ()](#apidoc.element.remarkable.rules.blockquote_open)
- description and source-code
```javascript
blockquote_open = function () {
  return '<blockquote>\n';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.bullet_list_close"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>bullet_list_close (tokens, idx)](#apidoc.element.remarkable.rules.bullet_list_close)
- description and source-code
```javascript
bullet_list_close = function (tokens, idx) {
  return '</ul>' + getBreak(tokens, idx);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.bullet_list_open"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>bullet_list_open ()](#apidoc.element.remarkable.rules.bullet_list_open)
- description and source-code
```javascript
bullet_list_open = function () {
  return '<ul>\n';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.code"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>code (tokens, idx)](#apidoc.element.remarkable.rules.code)
- description and source-code
```javascript
code = function (tokens, idx) {
  if (tokens[idx].block) {
    return '<pre><code>' + escapeHtml(tokens[idx].content) + '</code></pre>' + getBreak(tokens, idx);
  }
  return '<code>' + escapeHtml(tokens[idx].content) + '</code>';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.dd_close"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>dd_close ()](#apidoc.element.remarkable.rules.dd_close)
- description and source-code
```javascript
dd_close = function () {
  return '</dd>\n';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.dd_open"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>dd_open ()](#apidoc.element.remarkable.rules.dd_open)
- description and source-code
```javascript
dd_open = function () {
  return '<dd>';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.del_close"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>del_close ()](#apidoc.element.remarkable.rules.del_close)
- description and source-code
```javascript
del_close = function () {
  return '</del>';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.del_open"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>del_open ()](#apidoc.element.remarkable.rules.del_open)
- description and source-code
```javascript
del_open = function () {
  return '<del>';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.dl_close"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>dl_close ()](#apidoc.element.remarkable.rules.dl_close)
- description and source-code
```javascript
dl_close = function () {
  return '</dl>\n';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.dl_open"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>dl_open ()](#apidoc.element.remarkable.rules.dl_open)
- description and source-code
```javascript
dl_open = function () {
  return '<dl>\n';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.dt_close"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>dt_close ()](#apidoc.element.remarkable.rules.dt_close)
- description and source-code
```javascript
dt_close = function () {
  return '</dt>\n';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.dt_open"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>dt_open ()](#apidoc.element.remarkable.rules.dt_open)
- description and source-code
```javascript
dt_open = function () {
  return '<dt>';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.em_close"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>em_close ()](#apidoc.element.remarkable.rules.em_close)
- description and source-code
```javascript
em_close = function () {
  return '</em>';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.em_open"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>em_open ()](#apidoc.element.remarkable.rules.em_open)
- description and source-code
```javascript
em_open = function () {
  return '<em>';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.fence"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>fence (tokens, idx, options, env, instance)](#apidoc.element.remarkable.rules.fence)
- description and source-code
```javascript
fence = function (tokens, idx, options, env, instance) {
  var token = tokens[idx];
  var langClass = '';
  var langPrefix = options.langPrefix;
  var langName = '', fences, fenceName;
  var highlighted;

  if (token.params) {

    //
    // '''foo bar
    //
    // Try custom renderer "foo" first. That will simplify overwrite
    // for diagrams, latex, and any other fenced block with custom look
    //

    fences = token.params.split(/\s+/g);
    fenceName = fences.join(' ');

    if (has(instance.rules.fence_custom, fences[0])) {
      return instance.rules.fence_custom[fences[0]](tokens, idx, options, env, instance);
    }

    langName = escapeHtml(replaceEntities(unescapeMd(fenceName)));
    langClass = ' class="' + langPrefix + langName + '"';
  }

  if (options.highlight) {
    highlighted = options.highlight.apply(options.highlight, [ token.content ].concat(fences))
      || escapeHtml(token.content);
  } else {
    highlighted = escapeHtml(token.content);
  }

  return '<pre><code' + langClass + '>'
        + highlighted
        + '</code></pre>'
        + getBreak(tokens, idx);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.footnote_anchor"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>footnote_anchor (tokens, idx)](#apidoc.element.remarkable.rules.footnote_anchor)
- description and source-code
```javascript
footnote_anchor = function (tokens, idx) {
  var n = Number(tokens[idx].id + 1).toString();
  var id = 'fnref' + n;
  if (tokens[idx].subId > 0) {
    id += ':' + tokens[idx].subId;
  }
  return ' <a href="#' + id + '" class="footnote-backref">↩</a>';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.footnote_block_close"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>footnote_block_close ()](#apidoc.element.remarkable.rules.footnote_block_close)
- description and source-code
```javascript
footnote_block_close = function () {
  return '</ol>\n</section>\n';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.footnote_block_open"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>footnote_block_open (tokens, idx, options)](#apidoc.element.remarkable.rules.footnote_block_open)
- description and source-code
```javascript
footnote_block_open = function (tokens, idx, options) {
  var hr = options.xhtmlOut
    ? '<hr class="footnotes-sep" />\n'
    : '<hr class="footnotes-sep">\n';
  return hr + '<section class="footnotes">\n<ol class="footnotes-list">\n';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.footnote_close"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>footnote_close ()](#apidoc.element.remarkable.rules.footnote_close)
- description and source-code
```javascript
footnote_close = function () {
  return '</li>\n';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.footnote_open"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>footnote_open (tokens, idx)](#apidoc.element.remarkable.rules.footnote_open)
- description and source-code
```javascript
footnote_open = function (tokens, idx) {
  var id = Number(tokens[idx].id + 1).toString();
  return '<li id="fn' + id + '"  class="footnote-item">';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.footnote_ref"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>footnote_ref (tokens, idx)](#apidoc.element.remarkable.rules.footnote_ref)
- description and source-code
```javascript
footnote_ref = function (tokens, idx) {
  var n = Number(tokens[idx].id + 1).toString();
  var id = 'fnref' + n;
  if (tokens[idx].subId > 0) {
    id += ':' + tokens[idx].subId;
  }
  return '<sup class="footnote-ref"><a href="#fn' + n + '" id="' + id + '">[' + n + ']</a></sup>';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.getBreak"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>getBreak (tokens, idx)](#apidoc.element.remarkable.rules.getBreak)
- description and source-code
```javascript
function getBreak(tokens, idx) {
  idx = nextToken(tokens, idx);
  if (idx < tokens.length && tokens[idx].type === 'list_item_close') {
    return '';
  }
  return '\n';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.hardbreak"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>hardbreak (tokens, idx, options)](#apidoc.element.remarkable.rules.hardbreak)
- description and source-code
```javascript
hardbreak = function (tokens, idx, options) {
  return options.xhtmlOut ? '<br />\n' : '<br>\n';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.heading_close"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>heading_close (tokens, idx)](#apidoc.element.remarkable.rules.heading_close)
- description and source-code
```javascript
heading_close = function (tokens, idx) {
  return '</h' + tokens[idx].hLevel + '>\n';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.heading_open"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>heading_open (tokens, idx)](#apidoc.element.remarkable.rules.heading_open)
- description and source-code
```javascript
heading_open = function (tokens, idx) {
  return '<h' + tokens[idx].hLevel + '>';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.hr"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>hr (tokens, idx, options)](#apidoc.element.remarkable.rules.hr)
- description and source-code
```javascript
hr = function (tokens, idx, options) {
  return (options.xhtmlOut ? '<hr />' : '<hr>') + getBreak(tokens, idx);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.htmlblock"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>htmlblock (tokens, idx)](#apidoc.element.remarkable.rules.htmlblock)
- description and source-code
```javascript
htmlblock = function (tokens, idx) {
  return tokens[idx].content;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.htmltag"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>htmltag (tokens, idx)](#apidoc.element.remarkable.rules.htmltag)
- description and source-code
```javascript
htmltag = function (tokens, idx) {
  return tokens[idx].content;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.image"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>image (tokens, idx, options)](#apidoc.element.remarkable.rules.image)
- description and source-code
```javascript
image = function (tokens, idx, options) {
  var src = ' src="' + escapeHtml(tokens[idx].src) + '"';
  var title = tokens[idx].title ? (' title="' + escapeHtml(replaceEntities(tokens[idx].title)) + '"') : '';
  var alt = ' alt="' + (tokens[idx].alt ? escapeHtml(replaceEntities(unescapeMd(tokens[idx].alt))) : '') + '"';
  var suffix = options.xhtmlOut ? ' /' : '';
  return '<img' + src + alt + title + suffix + '>';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.ins_close"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>ins_close ()](#apidoc.element.remarkable.rules.ins_close)
- description and source-code
```javascript
ins_close = function () {
  return '</ins>';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.ins_open"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>ins_open ()](#apidoc.element.remarkable.rules.ins_open)
- description and source-code
```javascript
ins_open = function () {
  return '<ins>';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.link_close"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>link_close ()](#apidoc.element.remarkable.rules.link_close)
- description and source-code
```javascript
link_close = function () {
  return '</a>';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.link_open"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>link_open (tokens, idx, options)](#apidoc.element.remarkable.rules.link_open)
- description and source-code
```javascript
link_open = function (tokens, idx, options) {
  var title = tokens[idx].title ? (' title="' + escapeHtml(replaceEntities(tokens[idx].title)) + '"') : '';
  var target = options.linkTarget ? (' target="' + options.linkTarget + '"') : '';
  return '<a href="' + escapeHtml(tokens[idx].href) + '"' + title + target + '>';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.list_item_close"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>list_item_close ()](#apidoc.element.remarkable.rules.list_item_close)
- description and source-code
```javascript
list_item_close = function () {
  return '</li>\n';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.list_item_open"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>list_item_open ()](#apidoc.element.remarkable.rules.list_item_open)
- description and source-code
```javascript
list_item_open = function () {
  return '<li>';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.mark_close"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>mark_close ()](#apidoc.element.remarkable.rules.mark_close)
- description and source-code
```javascript
mark_close = function () {
  return '</mark>';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.mark_open"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>mark_open ()](#apidoc.element.remarkable.rules.mark_open)
- description and source-code
```javascript
mark_open = function () {
  return '<mark>';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.ordered_list_close"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>ordered_list_close (tokens, idx)](#apidoc.element.remarkable.rules.ordered_list_close)
- description and source-code
```javascript
ordered_list_close = function (tokens, idx) {
  return '</ol>' + getBreak(tokens, idx);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.ordered_list_open"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>ordered_list_open (tokens, idx)](#apidoc.element.remarkable.rules.ordered_list_open)
- description and source-code
```javascript
ordered_list_open = function (tokens, idx) {
  var token = tokens[idx];
  var order = token.order > 1 ? ' start="' + token.order + '"' : '';
  return '<ol' + order + '>\n';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.paragraph_close"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>paragraph_close (tokens, idx)](#apidoc.element.remarkable.rules.paragraph_close)
- description and source-code
```javascript
paragraph_close = function (tokens, idx) {
  var addBreak = !(tokens[idx].tight && idx && tokens[idx - 1].type === 'inline' && !tokens[idx - 1].content);
  return (tokens[idx].tight ? '' : '</p>') + (addBreak ? getBreak(tokens, idx) : '');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.paragraph_open"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>paragraph_open (tokens, idx)](#apidoc.element.remarkable.rules.paragraph_open)
- description and source-code
```javascript
paragraph_open = function (tokens, idx) {
  return tokens[idx].tight ? '' : '<p>';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.softbreak"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>softbreak (tokens, idx, options)](#apidoc.element.remarkable.rules.softbreak)
- description and source-code
```javascript
softbreak = function (tokens, idx, options) {
  return options.breaks ? (options.xhtmlOut ? '<br />\n' : '<br>\n') : '\n';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.strong_close"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>strong_close ()](#apidoc.element.remarkable.rules.strong_close)
- description and source-code
```javascript
strong_close = function () {
  return '</strong>';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.strong_open"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>strong_open ()](#apidoc.element.remarkable.rules.strong_open)
- description and source-code
```javascript
strong_open = function () {
  return '<strong>';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.sub"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>sub (tokens, idx)](#apidoc.element.remarkable.rules.sub)
- description and source-code
```javascript
sub = function (tokens, idx) {
  return '<sub>' + escapeHtml(tokens[idx].content) + '</sub>';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.sup"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>sup (tokens, idx)](#apidoc.element.remarkable.rules.sup)
- description and source-code
```javascript
sup = function (tokens, idx) {
  return '<sup>' + escapeHtml(tokens[idx].content) + '</sup>';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.table_close"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>table_close ()](#apidoc.element.remarkable.rules.table_close)
- description and source-code
```javascript
table_close = function () {
  return '</table>\n';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.table_open"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>table_open ()](#apidoc.element.remarkable.rules.table_open)
- description and source-code
```javascript
table_open = function () {
  return '<table>\n';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.tbody_close"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>tbody_close ()](#apidoc.element.remarkable.rules.tbody_close)
- description and source-code
```javascript
tbody_close = function () {
  return '</tbody>\n';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.tbody_open"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>tbody_open ()](#apidoc.element.remarkable.rules.tbody_open)
- description and source-code
```javascript
tbody_open = function () {
  return '<tbody>\n';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.td_close"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>td_close ()](#apidoc.element.remarkable.rules.td_close)
- description and source-code
```javascript
td_close = function () {
  return '</td>';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.td_open"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>td_open (tokens, idx)](#apidoc.element.remarkable.rules.td_open)
- description and source-code
```javascript
td_open = function (tokens, idx) {
  var token = tokens[idx];
  return '<td'
    + (token.align ? ' style="text-align:' + token.align + '"' : '')
    + '>';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.text"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>text (tokens, idx)](#apidoc.element.remarkable.rules.text)
- description and source-code
```javascript
text = function (tokens, idx) {
  return escapeHtml(tokens[idx].content);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.th_close"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>th_close ()](#apidoc.element.remarkable.rules.th_close)
- description and source-code
```javascript
th_close = function () {
  return '</th>';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.th_open"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>th_open (tokens, idx)](#apidoc.element.remarkable.rules.th_open)
- description and source-code
```javascript
th_open = function (tokens, idx) {
  var token = tokens[idx];
  return '<th'
    + (token.align ? ' style="text-align:' + token.align + '"' : '')
    + '>';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.thead_close"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>thead_close ()](#apidoc.element.remarkable.rules.thead_close)
- description and source-code
```javascript
thead_close = function () {
  return '</thead>\n';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.thead_open"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>thead_open ()](#apidoc.element.remarkable.rules.thead_open)
- description and source-code
```javascript
thead_open = function () {
  return '<thead>\n';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.tr_close"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>tr_close ()](#apidoc.element.remarkable.rules.tr_close)
- description and source-code
```javascript
tr_close = function () {
  return '</tr>\n';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.rules.tr_open"></a>[function <span class="apidocSignatureSpan">remarkable.rules.</span>tr_open ()](#apidoc.element.remarkable.rules.tr_open)
- description and source-code
```javascript
tr_open = function () {
  return '<tr>';
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.remarkable.utils"></a>[module remarkable.utils](#apidoc.module.remarkable.utils)

#### <a name="apidoc.element.remarkable.utils.assign"></a>[function <span class="apidocSignatureSpan">remarkable.utils.</span>assign (obj)](#apidoc.element.remarkable.utils.assign)
- description and source-code
```javascript
function assign(obj) {
  var sources = [].slice.call(arguments, 1);

  sources.forEach(function (source) {
    if (!source) { return; }

    if (typeof source !== 'object') {
      throw new TypeError(source + 'must be object');
    }

    Object.keys(source).forEach(function (key) {
      obj[key] = source[key];
    });
  });

  return obj;
}
```
- example usage
```shell
...

/**
* Renderer class. Renders HTML and exposes 'rules' to allow
* local modifications.
*/

function Renderer() {
 this.rules = utils.assign({}, rules);

 // exported helper, for custom rules only
 this.getBreak = rules.getBreak;
}

/**
* Render a string of inline HTML with the given 'tokens' and
...
```

#### <a name="apidoc.element.remarkable.utils.escapeHtml"></a>[function <span class="apidocSignatureSpan">remarkable.utils.</span>escapeHtml (str)](#apidoc.element.remarkable.utils.escapeHtml)
- description and source-code
```javascript
function escapeHtml(str) {
  if (HTML_ESCAPE_TEST_RE.test(str)) {
    return str.replace(HTML_ESCAPE_REPLACE_RE, replaceUnsafeChar);
  }
  return str;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.utils.fromCodePoint"></a>[function <span class="apidocSignatureSpan">remarkable.utils.</span>fromCodePoint (c)](#apidoc.element.remarkable.utils.fromCodePoint)
- description and source-code
```javascript
function fromCodePoint(c) {
<span class="apidocCodeCommentSpan">  /*eslint no-bitwise:0*/
</span>  if (c > 0xffff) {
    c -= 0x10000;
    var surrogate1 = 0xd800 + (c >> 10),
        surrogate2 = 0xdc00 + (c & 0x3ff);

    return String.fromCharCode(surrogate1, surrogate2);
  }
  return String.fromCharCode(c);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.utils.has"></a>[function <span class="apidocSignatureSpan">remarkable.utils.</span>has (object, key)](#apidoc.element.remarkable.utils.has)
- description and source-code
```javascript
function has(object, key) {
  return object
    ? hasOwn.call(object, key)
    : false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.utils.isString"></a>[function <span class="apidocSignatureSpan">remarkable.utils.</span>isString (obj)](#apidoc.element.remarkable.utils.isString)
- description and source-code
```javascript
function isString(obj) {
  return typeOf(obj) === '[object String]';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.utils.isValidEntityCode"></a>[function <span class="apidocSignatureSpan">remarkable.utils.</span>isValidEntityCode (c)](#apidoc.element.remarkable.utils.isValidEntityCode)
- description and source-code
```javascript
function isValidEntityCode(c) {
<span class="apidocCodeCommentSpan">  /*eslint no-bitwise:0*/
</span>  // broken sequence
  if (c >= 0xD800 && c <= 0xDFFF) { return false; }
  // never used
  if (c >= 0xFDD0 && c <= 0xFDEF) { return false; }
  if ((c & 0xFFFF) === 0xFFFF || (c & 0xFFFF) === 0xFFFE) { return false; }
  // control codes
  if (c >= 0x00 && c <= 0x08) { return false; }
  if (c === 0x0B) { return false; }
  if (c >= 0x0E && c <= 0x1F) { return false; }
  if (c >= 0x7F && c <= 0x9F) { return false; }
  // out of range
  if (c > 0x10FFFF) { return false; }
  return true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.remarkable.utils.replaceEntities"></a>[function <span class="apidocSignatureSpan">remarkable.utils.</span>replaceEntities (str)](#apidoc.element.remarkable.utils.replaceEntities)
- description and source-code
```javascript
function replaceEntities(str) {
  if (str.indexOf('&') < 0) { return str; }

  return str.replace(NAMED_ENTITY_RE, replaceEntityPattern);
}
```
- example usage
```shell
...
 * @return {Boolean}
 */

function validateLink(url) {
  var BAD_PROTOCOLS = [ 'vbscript', 'javascript', 'file', 'data' ];
  var str = url.trim().toLowerCase();
  // Care about digital entities "javascript&#x3A;alert(1)"
  str = utils.replaceEntities(str);
  if (str.indexOf(':') !== -1 && BAD_PROTOCOLS.indexOf(str.split(':')[0]) !== -1) {
    return false;
  }
  return true;
}

/**
...
```

#### <a name="apidoc.element.remarkable.utils.unescapeMd"></a>[function <span class="apidocSignatureSpan">remarkable.utils.</span>unescapeMd (str)](#apidoc.element.remarkable.utils.unescapeMd)
- description and source-code
```javascript
function unescapeMd(str) {
  if (str.indexOf('\\') < 0) { return str; }
  return str.replace(UNESCAPE_MD_RE, '$1');
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
