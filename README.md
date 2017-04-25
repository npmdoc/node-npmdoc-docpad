# npmdoc-docpad

#### basic api documentation for  [docpad (v6.79.4)](https://github.com/docpad/docpad)  [![npm package](https://img.shields.io/npm/v/npmdoc-docpad.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-docpad) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-docpad.svg)](https://travis-ci.org/npmdoc/node-npmdoc-docpad)

#### DocPad is a dynamic static site generator. Write your content as files, or import your content from other external sources. Render the content with plugins. And deploy your static or dynamic website to your favourite hosting provider.

[![NPM](https://nodei.co/npm/docpad.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/docpad)

- [https://npmdoc.github.io/node-npmdoc-docpad/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-docpad/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-docpad/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-docpad/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-docpad/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-docpad/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "2012+ Bevry Pty Ltd",
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
            "url": "http://balupton.com"
        },
        {
            "name": "Aaron Powell",
            "url": "http://www.aaron-powell.com"
        },
        {
            "name": "Adrian Olaru",
            "url": "https://github.com/adrianolaru"
        },
        {
            "name": "Alex Mesarosh",
            "url": "https://github.com/amesarosh"
        },
        {
            "name": "alexwoehr",
            "url": "https://github.com/alexwoehr"
        },
        {
            "name": "Ivan Klimchuk",
            "url": "http://klimchuk.com"
        },
        {
            "name": "Andrew Patton",
            "url": "http://www.acusti.ca"
        },
        {
            "name": "GÁBOR Áron Zsolt",
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
            "url": "http://pismute.github.io"
        },
        {
            "name": "Morgan Larosa",
            "url": "http://aptiture.com"
        },
        {
            "name": "Chase Colman",
            "url": "https://github.com/chase"
        },
        {
            "name": "Lukasz Gornicki",
            "url": "http://derberg.github.io/"
        },
        {
            "name": "eldios",
            "url": "https://github.com/eldios"
        },
        {
            "name": "sylee",
            "url": "blog.sylee.tw"
        },
        {
            "name": "Eduardo Lavaque",
            "url": "http://greduan.com"
        },
        {
            "name": "Homme Zwaagstra",
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
            "url": "http://mdm.cc"
        },
        {
            "name": "Neil Taylor",
            "url": "www.myplanetdigital.com"
        },
        {
            "name": "Nathan Friedly",
            "url": "http://nfriedly.com/"
        },
        {
            "name": "Nick Crohn",
            "url": "http://nickcrohn.com/"
        },
        {
            "name": "Olivier Bazoud",
            "url": "https://github.com/obazoud"
        },
        {
            "name": "Paul Armstrong",
            "url": "http://paularmstrongdesigns.com/"
        },
        {
            "name": "pavangupta",
            "url": "https://github.com/pavangupta"
        },
        {
            "name": "Pavan Gupta",
            "url": "http://pavgup.io"
        },
        {
            "name": "Peter Flannery",
            "url": "https://github.com/pflannery"
        },
        {
            "name": "Darío Villanueva",
            "url": "http://www.alolo.co"
        },
        {
            "name": "Richard A",
            "url": "https://github.com/rantecki"
        },
        {
            "name": "Rob Loach",
            "url": "http://robloach.net"
        },
        {
            "name": "RueMic",
            "url": "http://www.ruemic.com"
        },
        {
            "name": "Ke Zhu",
            "url": "http://shawnzhu.tumblr.com"
        },
        {
            "name": "Sorin Ionescu",
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
            "url": "http://firede.us"
        },
        {
            "name": "JT Turner",
            "url": "http://jtwebman.com"
        },
        {
            "name": "Anton Wilhelm",
            "url": "https://github.com/timaschew"
        },
        {
            "name": "Bahtiar Gadimov",
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
            "url": "http://www.prayagverma.com/"
        },
        {
            "name": "Steve Mc",
            "url": "http://www.stevemcarthur.co.uk"
        },
        {
            "name": "Todd Anglin",
            "url": "nativescript.org"
        },
        {
            "name": "Prayag Verma",
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
            "name": "balupton"
        },
        {
            "name": "bevry"
        },
        {
            "name": "mikeumus"
        },
        {
            "name": "robloach"
        },
        {
            "name": "stevemc"
        }
    ],
    "name": "docpad",
    "optionalDependencies": {},
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



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
