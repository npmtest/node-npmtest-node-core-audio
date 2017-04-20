# npmtest-node-core-audio

#### basic test coverage for  node-core-audio (v0.5.1)  [![npm package](https://img.shields.io/npm/v/npmtest-node-core-audio.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-node-core-audio) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-node-core-audio.svg)](https://travis-ci.org/npmtest/node-npmtest-node-core-audio)

#### Core native node.js audio functionality, including sound card access and audio streaming

[![NPM](https://nodei.co/npm/node-core-audio.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-core-audio)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-node-core-audio/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-core-audio/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-node-core-audio/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-node-core-audio/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-node-core-audio/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-node-core-audio/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-node-core-audio/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-node-core-audio/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-node-core-audio/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-core-audio/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-node-core-audio/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-node-core-audio/build/test-report.html](https://npmtest.github.io/node-npmtest-node-core-audio/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-node-core-audio/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-node-core-audio/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-node-core-audio/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-core-audio/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-core-audio/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-core-audio/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-node-core-audio/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-node-core-audio/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "node-core-audio",
    "version": "0.5.1",
    "author": "Mike Vegeto <michael.vegeto@gmail.com> (http://mikevegeto.com/)",
    "contributors": [
        "Marc J. Schmidt <marc@kryn.org> (http://marcjschmidt.de/)",
        "Jeremiah Senkpiel <fishrock123@rocketmail.com> (http://searchbeam.jit.su/)",
        "Daniel Church <CrazyNorman@gmail.com> (https://github.com/anprogrammer/)"
    ],
    "dependencies": {
        "audio-streamer": ">= 0.1.0",
        "fft": "~0.2.1",
        "nan": "^2.1.0",
        "node-waveheader": "git://github.com/mrose17/node-waveheader.git",
        "portfinder": "0.2.1"
    },
    "description": "Core native node.js audio functionality, including sound card access and audio streaming",
    "main": "./node-core-audio",
    "scripts": {
        "test": "node test/test.js"
    },
    "engines": {
        "node": ">=0.12.0"
    },
    "keywords": [
        "audio",
        "dsp",
        "processing",
        "portaudio",
        "sound",
        "synth",
        "signal",
        "streaming",
        "buffer"
    ],
    "license": "MIT",
    "repository": {
        "type": "git",
        "url": "http://github.com/ZECTBynmo/node-core-audio.git"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
