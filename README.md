# api documentation for  [docpad (v6.79.4)](https://github.com/docpad/docpad)  [![npm package](https://img.shields.io/npm/v/npmdoc-docpad.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-docpad) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-docpad.svg)](https://travis-ci.org/npmdoc/node-npmdoc-docpad)
#### DocPad is a dynamic static site generator. Write your content as files, or import your content from other external sources. Render the content with plugins. And deploy your static or dynamic website to your favourite hosting provider.

[![NPM](https://nodei.co/npm/docpad.png?downloads=true)](https://www.npmjs.com/package/docpad)

[![apidoc](https://npmdoc.github.io/node-npmdoc-docpad/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-docpad_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-docpad/build..beta..travis-ci.org/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-docpad/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-docpad/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "2012+ Bevry Pty Ltd",
        "email": "us@bevry.me",
        "url": "http://bevry.me"
    },
    "badges": {
        "list": [
            "travisci",
            "npmversion",
            "npmdownloads",
            "daviddm",
            "daviddmdev",
            "---",
            "patreon",
            "opencollective",
            "gratipay",
            "flattr",
            "paypal",
            "bitcoin",
            "wishlist",
            "---",
            "slackin"
        ],
        "config": {
            "patreonUsername": "bevry",
            "opencollectiveUsername": "bevry",
            "gratipayUsername": "bevry",
            "flattrUsername": "balupton",
            "paypalURL": "https://bevry.me/paypal",
            "bitcoinURL": "https://bevry.me/bitcoin",
            "wishlistURL": "https://bevry.me/wishlist",
            "slackinURL": "https://slack.bevry.me"
        }
    },
    "bin": {
        "docpad": "bin/docpad",
        "docpad-compile": "bin/docpad-compile",
        "docpad-debug": "bin/docpad-debug",
        "docpad-server": "bin/docpad-server",
        "docpad-trace": "bin/docpad-trace"
    },
    "bugs": {
        "url": "https://github.com/docpad/docpad/issues"
    },
    "contributors": [
        {
            "name": "Benjamin Lupton",
            "email": "b@lupton.cc",
            "url": "http://balupton.com"
        },
        {
            "name": "Aaron Powell",
            "email": "me@aaron-powell.com",
            "url": "http://www.aaron-powell.com"
        },
        {
            "name": "Adrian Olaru",
            "email": "adrian.olaru@me.com",
            "url": "https://github.com/adrianolaru"
        },
        {
            "name": "Alex Mesarosh",
            "email": "alex.mesarosh@meltmedia.com",
            "url": "https://github.com/amesarosh"
        },
        {
            "name": "alexwoehr",
            "url": "https://github.com/alexwoehr"
        },
        {
            "name": "Ivan Klimchuk",
            "email": "ivan@klimchuk.com",
            "url": "http://klimchuk.com"
        },
        {
            "name": "Andrew Patton",
            "email": "andrew@acusti.ca",
            "url": "http://www.acusti.ca"
        },
        {
            "name": "GÁBOR Áron Zsolt",
            "email": "ashnur@gmail.com",
            "url": "http://ashnur.com"
        },
        {
            "name": "Ben Barber",
            "url": "https://github.com/barberboy"
        },
        {
            "name": "Bruno Heridet",
            "url": "http://delapouite.com"
        },
        {
            "name": "Changwoo Park",
            "email": "pismute@gmail.com",
            "url": "http://pismute.github.io"
        },
        {
            "name": "Morgan Larosa",
            "url": "http://aptiture.com"
        },
        {
            "name": "Chase Colman",
            "email": "chase@colman.io",
            "url": "https://github.com/chase"
        },
        {
            "name": "Lukasz Gornicki",
            "email": "derberg@wp.pl",
            "url": "http://derberg.github.io/"
        },
        {
            "name": "eldios",
            "email": "lele@amicofigo.com",
            "url": "https://github.com/eldios"
        },
        {
            "name": "sylee",
            "email": "shiyung@gmail.com",
            "url": "blog.sylee.tw"
        },
        {
            "name": "Eduardo Lavaque",
            "email": "me@greduan.com",
            "url": "http://greduan.com"
        },
        {
            "name": "Homme Zwaagstra",
            "email": "hrz@geodata.soton.ac.uk",
            "url": "https://github.com/homme"
        },
        {
            "name": "JT Turner",
            "url": "http://www.jtwebman.com"
        },
        {
            "name": "Bahtiar 'kalkin-' Gadimov",
            "url": "http://blog.blase16.de/"
        },
        {
            "name": "Luke Hagan",
            "url": "lukehagan.com"
        },
        {
            "name": "Michael Duane Mooring",
            "email": "Mike@mdm.cc",
            "url": "http://mdm.cc"
        },
        {
            "name": "Neil Taylor",
            "email": "neil.t@myplanetdigital.com",
            "url": "www.myplanetdigital.com"
        },
        {
            "name": "Nathan Friedly",
            "email": "first name @ website",
            "url": "http://nfriedly.com/"
        },
        {
            "name": "Nick Crohn",
            "email": "nick.crohn+github@gmail.com",
            "url": "http://nickcrohn.com/"
        },
        {
            "name": "Olivier Bazoud",
            "url": "https://github.com/obazoud"
        },
        {
            "name": "Paul Armstrong",
            "email": "paul@paularmstrongdesigns.com",
            "url": "http://paularmstrongdesigns.com/"
        },
        {
            "name": "pavangupta",
            "url": "https://github.com/pavangupta"
        },
        {
            "name": "Pavan Gupta",
            "email": "pg8p@virginia.edu",
            "url": "http://pavgup.io"
        },
        {
            "name": "Peter Flannery",
            "url": "https://github.com/pflannery"
        },
        {
            "name": "Darío Villanueva",
            "email": "dario@alolo.co",
            "url": "http://www.alolo.co"
        },
        {
            "name": "Richard A",
            "email": "richard@antecki.id.au",
            "url": "https://github.com/rantecki"
        },
        {
            "name": "Rob Loach",
            "email": "robloach@gmail.com",
            "url": "http://robloach.net"
        },
        {
            "name": "RueMic",
            "email": "rumicdesign@gmail.com",
            "url": "http://www.ruemic.com"
        },
        {
            "name": "Ke Zhu",
            "url": "http://shawnzhu.tumblr.com"
        },
        {
            "name": "Sorin Ionescu",
            "email": "sorin.ionescu@gmail.com",
            "url": "https://github.com/sorin-ionescu"
        },
        {
            "name": "Stefanos Grammenos",
            "url": "https://github.com/stegrams"
        },
        {
            "name": "Sven Vetsch",
            "url": "https://github.com/disenchant"
        },
        {
            "name": "Anton Wilhelm",
            "url": "http://timaschew.github.io"
        },
        {
            "name": "Todd Anglin",
            "url": "kendoui.com"
        },
        {
            "name": "Tatu Tamminen",
            "url": "http://www.triplet.fi"
        },
        {
            "name": "Nick Matantsev",
            "url": "http://unframework.com"
        },
        {
            "name": "Vladislav Botvin",
            "email": "darkvlados@me.com",
            "url": "https://github.com/darky"
        },
        {
            "name": "vsopvsop",
            "url": "https://github.com/vsopvsop"
        },
        {
            "name": "Zearin",
            "url": "https://github.com/Zearin"
        },
        {
            "name": "Firede",
            "email": "firede@firede.us",
            "url": "http://firede.us"
        },
        {
            "name": "JT Turner",
            "email": "jtwebman@gmail.com",
            "url": "http://jtwebman.com"
        },
        {
            "name": "Anton Wilhelm",
            "url": "https://github.com/timaschew"
        },
        {
            "name": "Bahtiar Gadimov",
            "email": "bahtiar@gadimov.de",
            "url": "http://bahtiar.gadimov.de/"
        },
        {
            "name": "Ke Zhu",
            "url": "http://blog.shawnzhu.com"
        },
        {
            "name": "Morgan Larosa",
            "url": "https://github.com/chaos95"
        },
        {
            "name": "Paul Armstrong",
            "url": "https://github.com/paularmstrong"
        },
        {
            "name": "Prayag Verma",
            "email": "prayag.verma@gmail.com",
            "url": "http://www.prayagverma.com/"
        },
        {
            "name": "Steve Mc",
            "email": "contact@stevemcarthur.co.uk",
            "url": "http://www.stevemcarthur.co.uk"
        },
        {
            "name": "Todd Anglin",
            "url": "nativescript.org"
        },
        {
            "name": "Prayag Verma",
            "email": "prayag@stylifyyourblog.com",
            "url": "http://www.StylifyYourBlog.com/"
        }
    ],
    "dependencies": {
        "ambi": "^2.2.0",
        "backbone": "1.2.3",
        "bal-util": "~2.5.1",
        "caterpillar": "^2.0.9",
        "caterpillar-filter": "^2.0.3",
        "caterpillar-human": "^2.1.1",
        "commander": "^2.7.1",
        "csextends": "^1.0.3",
        "cson": "^3.0.1",
        "eachr": "^2.0.2",
        "encoding": "~0.1.11",
        "envfile": "^1.0.0",
        "event-emitter-grouped": "2.4.3",
        "express": "^3.21.2",
        "extendr": "^2.1.0",
        "extract-opts": "^3.0.1",
        "getmac": "^1.0.6",
        "hostenv": "^1.0.3",
        "ignorefs": "^1.0.0",
        "istextorbinary": "^1.0.0",
        "jschardet": "~1.3.0",
        "lazy-require": "^2.0.0",
        "method-override": "^2.3.2",
        "mime": "^1.3.4",
        "progressbar": "^1.0.3",
        "promptly": "~0.2.1",
        "query-engine": "~1.5.5",
        "rimraf": "^2.2.8",
        "safefs": "^3.1.2",
        "safeps": "^5.1.0",
        "scandirectory": "^2.5.0",
        "semver": "^5.0.1",
        "superagent": "^1.1.0",
        "taskgroup": "^4.2.1",
        "typechecker": "^2.0.8",
        "underscore": "^1.8.2",
        "watchr": "^2.4.13",
        "yamljs": "~0.2.1"
    },
    "description": "DocPad is a dynamic static site generator. Write your content as files, or import your content from other external sources. Render the content with plugins. And deploy your static or dynamic website to your favourite hosting provider.",
    "devDependencies": {
        "assert-helpers": "^4.5.0",
        "coffee-script": "^1.12.4",
        "coffeelint": "^1.16.0",
        "docpad-plugin-coffeekup": "2",
        "docpad-plugin-eco": "2",
        "docpad-plugin-marked": "2",
        "joe": "~1.6.1",
        "joe-reporter-console": "~1.2.1",
        "moment": "^2.13.0",
        "projectz": "^1.3.2",
        "yuidocjs": "^0.10.1"
    },
    "directories": {},
    "dist": {
        "shasum": "828cac98c1e72dbb9564ab0eaa13c99a6f5e3ddb",
        "tarball": "https://registry.npmjs.org/docpad/-/docpad-6.79.4.tgz"
    },
    "editions": [
        {
            "description": "Source + CoffeeScript + Require",
            "entry": "lib/docpad.coffee",
            "directory": "src",
            "syntaxes": [
                "coffeescript",
                "require"
            ]
        },
        {
            "description": "CoffeeScript Compiled JavaScript + ES5 + Require",
            "entry": "lib/docpad.js",
            "directory": "out",
            "syntaxes": [
                "javascript",
                "es5",
                "require"
            ]
        }
    ],
    "engines": {
        "node": ">=0.10",
        "npm": ">=2.5.0"
    },
    "gitHead": "e5e984604c53a064c44382fb653c1cbb77498a38",
    "homepage": "https://github.com/docpad/docpad",
    "installUrl": "https://docpad.org/install",
    "keywords": [
        "document management system",
        "dms",
        "content management system",
        "cms",
        "static site generator",
        "generator",
        "static file server",
        "server",
        "web",
        "web framework",
        "framework",
        "web development",
        "development",
        "dev",
        "build and deployment",
        "builder",
        "build",
        "compiler",
        "compile",
        "parser",
        "parse",
        "renderer",
        "render",
        "templating",
        "templates",
        "language agnostic",
        "website",
        "blog",
        "cli",
        "tool",
        "utility",
        "scaffold"
    ],
    "license": "MIT",
    "main": "out/lib/docpad.js",
    "maintainers": [
        {
            "name": "balupton",
            "email": "b@lupton.cc"
        },
        {
            "name": "bevry",
            "email": "us@bevry.me"
        },
        {
            "name": "mikeumus",
            "email": "mike@mdm.cc"
        },
        {
            "name": "robloach",
            "email": "robloach@gmail.com"
        },
        {
            "name": "stevemc",
            "email": "contact@stevemcarthur.co.uk"
        }
    ],
    "name": "docpad",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/docpad/docpad.git"
    },
    "scripts": {
        "our:clean": "rm -Rf ./docs ./es2015 ./es5 ./out",
        "our:compile": "npm run our:compile:coffee",
        "our:compile:coffee": "coffee -bco ./out ./src",
        "our:meta": "npm run our:meta:projectz",
        "our:meta:projectz": "projectz compile",
        "our:release": "npm run our:release:prepare && npm run our:release:check && npm run our:release:tag && npm run our:release:push",
        "our:release:check": "npm run our:release:check:changelog && npm run our:release:check:dirty",
        "our:release:check:changelog": "cat ./HISTORY.md | grep v$npm_package_version || (echo add a changelog entry for v$npm_package_version && exit -1)",
        "our:release:check:dirty": "git diff --exit-code",
        "our:release:prepare": "npm run our:clean && npm run our:compile && npm run our:test && npm run our:meta",
        "our:release:push": "git push origin master && git push origin --tags",
        "our:release:tag": "export MESSAGE=$(cat ./HISTORY.md | sed -n \"/## v$npm_package_version/,/##/p\" | sed 's/## //' | awk 'NR>1{print buf}{buf = $0}') && test \"$MESSAGE\" || (echo 'proper changelog entry not found' && exit -1) && git tag v$npm_package_version -am \"$MESSAGE\"",
        "our:setup": "npm run our:setup:npm",
        "our:setup:npm": "npm install",
        "our:test": "npm run our:verify && npm test",
        "our:verify": "npm run our:verify:coffeelint",
        "our:verify:coffeelint": "coffeelint ./src",
        "test": "node --harmony ./out/test/everything-test.js --joe-reporter=console"
    },
    "sponsors": [
        "Myplanet Digital <hello@myplanetdigital.com> (http://www.myplanetdigital.com)",
        "Meeho! <info@meeho.net> (http://www.meeho.net)",
        "Prismatik <hello@prismatik.com.au> (http://www.prismatik.com.au)",
        "hybris <yaas-feedback@sap.com> (http://yaas.io/)"
    ],
    "title": "DocPad. Streamlined web development.",
    "upgradeUrl": "https://docpad.org/upgrade",
    "version": "6.79.4"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module docpad](#apidoc.module.docpad)
1.  boolean <span class="apidocSignatureSpan">docpad.</span>usingDomains
1.  [function <span class="apidocSignatureSpan">docpad.</span>EventEmitter ()](#apidoc.element.docpad.EventEmitter)
1.  [function <span class="apidocSignatureSpan">docpad.</span>__super__.constructor ()](#apidoc.element.docpad.__super__.constructor)
1.  [function <span class="apidocSignatureSpan">docpad.</span>create ()](#apidoc.element.docpad.create)
1.  [function <span class="apidocSignatureSpan">docpad.</span>createInstance ()](#apidoc.element.docpad.createInstance)
1.  [function <span class="apidocSignatureSpan">docpad.</span>init ()](#apidoc.element.docpad.init)
1.  [function <span class="apidocSignatureSpan">docpad.</span>listenerCount (emitter, type)](#apidoc.element.docpad.listenerCount)
1.  [function <span class="apidocSignatureSpan">docpad.</span>require (relativePath)](#apidoc.element.docpad.require)
1.  number <span class="apidocSignatureSpan">docpad.</span>defaultMaxListeners
1.  object <span class="apidocSignatureSpan">docpad.</span>__super__

#### [module docpad.__super__](#apidoc.module.docpad.__super__)
1.  [function <span class="apidocSignatureSpan">docpad.__super__.</span>constructor ()](#apidoc.element.docpad.__super__.constructor)
1.  [function <span class="apidocSignatureSpan">docpad.__super__.</span>emitParallel ()](#apidoc.element.docpad.__super__.emitParallel)
1.  [function <span class="apidocSignatureSpan">docpad.__super__.</span>emitSerial ()](#apidoc.element.docpad.__super__.emitSerial)
1.  [function <span class="apidocSignatureSpan">docpad.__super__.</span>getListenerGroup ()](#apidoc.element.docpad.__super__.getListenerGroup)
1.  [function <span class="apidocSignatureSpan">docpad.__super__.</span>off ()](#apidoc.element.docpad.__super__.off)

#### [module docpad.__super__.constructor](#apidoc.module.docpad.__super__.constructor)
1.  boolean <span class="apidocSignatureSpan">docpad.__super__.constructor.</span>usingDomains
1.  [function <span class="apidocSignatureSpan">docpad.__super__.</span>constructor ()](#apidoc.element.docpad.__super__.constructor.constructor)
1.  [function <span class="apidocSignatureSpan">docpad.__super__.constructor.</span>EventEmitter ()](#apidoc.element.docpad.__super__.constructor.EventEmitter)
1.  [function <span class="apidocSignatureSpan">docpad.__super__.constructor.</span>init ()](#apidoc.element.docpad.__super__.constructor.init)
1.  [function <span class="apidocSignatureSpan">docpad.__super__.constructor.</span>listenerCount (emitter, type)](#apidoc.element.docpad.__super__.constructor.listenerCount)
1.  number <span class="apidocSignatureSpan">docpad.__super__.constructor.</span>defaultMaxListeners
1.  object <span class="apidocSignatureSpan">docpad.__super__.constructor.</span>__super__



# <a name="apidoc.module.docpad"></a>[module docpad](#apidoc.module.docpad)

#### <a name="apidoc.element.docpad.EventEmitter"></a>[function <span class="apidocSignatureSpan">docpad.</span>EventEmitter ()](#apidoc.element.docpad.EventEmitter)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.docpad.__super__.constructor"></a>[function <span class="apidocSignatureSpan">docpad.</span>__super__.constructor ()](#apidoc.element.docpad.__super__.constructor)
- description and source-code
```javascript
function EventEmitterGrouped() {
  return EventEmitterGrouped.__super__.constructor.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.docpad.create"></a>[function <span class="apidocSignatureSpan">docpad.</span>create ()](#apidoc.element.docpad.create)
- description and source-code
```javascript
create = function () {
  var args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  return (function(func, args, ctor) {
    ctor.prototype = func.prototype;
    var child = new ctor, result = func.apply(child, args);
    return Object(result) === result ? result : child;
  })(this, args, function(){});
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.docpad.createInstance"></a>[function <span class="apidocSignatureSpan">docpad.</span>createInstance ()](#apidoc.element.docpad.createInstance)
- description and source-code
```javascript
createInstance = function () {
  var args;
  args = 1 <= arguments.length ? slice.call(arguments, 0) : [];
  return (function(func, args, ctor) {
    ctor.prototype = func.prototype;
    var child = new ctor, result = func.apply(child, args);
    return Object(result) === result ? result : child;
  })(this, args, function(){});
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.docpad.init"></a>[function <span class="apidocSignatureSpan">docpad.</span>init ()](#apidoc.element.docpad.init)
- description and source-code
```javascript
init = function () {
  this.domain = null;
  if (EventEmitter.usingDomains) {
    // if there is an active domain, then attach to it.
    domain = domain || require('domain');
    if (domain.active && !(this instanceof domain.Domain)) {
      this.domain = domain.active;
    }
  }

  if (!this._events || this._events === Object.getPrototypeOf(this)._events) {
    this._events = new EventHandlers();
    this._eventsCount = 0;
  }

  this._maxListeners = this._maxListeners || undefined;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.docpad.listenerCount"></a>[function <span class="apidocSignatureSpan">docpad.</span>listenerCount (emitter, type)](#apidoc.element.docpad.listenerCount)
- description and source-code
```javascript
listenerCount = function (emitter, type) {
  if (typeof emitter.listenerCount === 'function') {
    return emitter.listenerCount(type);
  } else {
    return listenerCount.call(emitter, type);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.docpad.require"></a>[function <span class="apidocSignatureSpan">docpad.</span>require (relativePath)](#apidoc.element.docpad.require)
- description and source-code
```javascript
require = function (relativePath) {
  var absolutePath;
  absolutePath = pathUtil.normalize(pathUtil.join(__dirname, relativePath));
  if (absolutePath.replace(__dirname, '') === absolutePath) {
    throw new Error("docpad.require is limited to local docpad files only: " + relativePath);
  }
  return require(absolutePath);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.docpad.__super__"></a>[module docpad.__super__](#apidoc.module.docpad.__super__)

#### <a name="apidoc.element.docpad.__super__.constructor"></a>[function <span class="apidocSignatureSpan">docpad.__super__.</span>constructor ()](#apidoc.element.docpad.__super__.constructor)
- description and source-code
```javascript
function EventEmitterGrouped() {
  return EventEmitterGrouped.__super__.constructor.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.docpad.__super__.emitParallel"></a>[function <span class="apidocSignatureSpan">docpad.__super__.</span>emitParallel ()](#apidoc.element.docpad.__super__.emitParallel)
- description and source-code
```javascript
emitParallel = function () {
  var args;
  args = 1 <= arguments.length ? __slice.call(arguments, 0) : [];
  return this.getListenerGroup.apply(this, args).setConfig({
    concurrency: 0
  }).run();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.docpad.__super__.emitSerial"></a>[function <span class="apidocSignatureSpan">docpad.__super__.</span>emitSerial ()](#apidoc.element.docpad.__super__.emitSerial)
- description and source-code
```javascript
emitSerial = function () {
  var args;
  args = 1 <= arguments.length ? __slice.call(arguments, 0) : [];
  return this.getListenerGroup.apply(this, args).run();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.docpad.__super__.getListenerGroup"></a>[function <span class="apidocSignatureSpan">docpad.__super__.</span>getListenerGroup ()](#apidoc.element.docpad.__super__.getListenerGroup)
- description and source-code
```javascript
getListenerGroup = function () {
  var args, eventName, listenerObjects, me, next, tasks, _i;
  eventName = arguments[0], args = 3 <= arguments.length ? __slice.call(arguments, 1, _i = arguments.length - 1) : (_i = 1, []),
next = arguments[_i++];
  me = this;
  tasks = new TaskGroup("EventEmitterGrouped for " + eventName).done(next);
  listenerObjects = this.listeners(eventName).slice().map(function(listener) {
    var listenerObject;
    listenerObject = {};
    if (listener.listener) {
      listenerObject.actual = listener.listener;
      listenerObject.fire = [listener.bind(me), listener.listener];
    } else {
      listenerObject.actual = listener;
      listenerObject.fire = listener.bind(me);
    }
    listenerObject.priority = listenerObject.actual.priority || 0;
    listenerObject.name = listenerObject.name || ("Untitled listener for [" + eventName + "] with priority [" + listenerObject.priority
 + "]");
    return listenerObject;
  });
  listenerObjects.sort(function(a, b) {
    return b.priority - a.priority;
  });
  listenerObjects.forEach(function(listenerObject) {
    return tasks.addTask(listenerObject.name, function(complete) {
      return ambi.apply(null, [listenerObject.fire].concat(__slice.call(args), [complete]));
    });
  });
  return tasks;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.docpad.__super__.off"></a>[function <span class="apidocSignatureSpan">docpad.__super__.</span>off ()](#apidoc.element.docpad.__super__.off)
- description and source-code
```javascript
off = function () {
  var args;
  args = 1 <= arguments.length ? __slice.call(arguments, 0) : [];
  return this.removeListener.apply(this, args);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.docpad.__super__.constructor"></a>[module docpad.__super__.constructor](#apidoc.module.docpad.__super__.constructor)

#### <a name="apidoc.element.docpad.__super__.constructor.constructor"></a>[function <span class="apidocSignatureSpan">docpad.__super__.</span>constructor ()](#apidoc.element.docpad.__super__.constructor.constructor)
- description and source-code
```javascript
function Function() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.docpad.__super__.constructor.EventEmitter"></a>[function <span class="apidocSignatureSpan">docpad.__super__.constructor.</span>EventEmitter ()](#apidoc.element.docpad.__super__.constructor.EventEmitter)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.docpad.__super__.constructor.init"></a>[function <span class="apidocSignatureSpan">docpad.__super__.constructor.</span>init ()](#apidoc.element.docpad.__super__.constructor.init)
- description and source-code
```javascript
init = function () {
  this.domain = null;
  if (EventEmitter.usingDomains) {
    // if there is an active domain, then attach to it.
    domain = domain || require('domain');
    if (domain.active && !(this instanceof domain.Domain)) {
      this.domain = domain.active;
    }
  }

  if (!this._events || this._events === Object.getPrototypeOf(this)._events) {
    this._events = new EventHandlers();
    this._eventsCount = 0;
  }

  this._maxListeners = this._maxListeners || undefined;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.docpad.__super__.constructor.listenerCount"></a>[function <span class="apidocSignatureSpan">docpad.__super__.constructor.</span>listenerCount (emitter, type)](#apidoc.element.docpad.__super__.constructor.listenerCount)
- description and source-code
```javascript
listenerCount = function (emitter, type) {
  if (typeof emitter.listenerCount === 'function') {
    return emitter.listenerCount(type);
  } else {
    return listenerCount.call(emitter, type);
  }
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
