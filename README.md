# cardscript-table-of-contents

[![Tymly Cardscript](https://img.shields.io/badge/tymly-cardscript-blue.svg)](https://tymly.io/)
[![CircleCI](https://circleci.com/gh/wmfs/cardscript-table-of-contents.svg?style=svg)](https://circleci.com/gh/wmfs/cardscript-table-of-contents)
[![npm (scoped)](https://img.shields.io/npm/v/@wmfs/cardscript-table-of-contents.svg)](https://www.npmjs.com/package/@wmfs/cardscript-table-of-contents) 
[![codecov](https://codecov.io/gh/wmfs/cardscript-table-of-contents/branch/master/graph/badge.svg)](https://codecov.io/gh/wmfs/cardscript-table-of-contents) 
[![CodeFactor](https://www.codefactor.io/repository/github/wmfs/cardscript-table-of-contents/badge)](https://www.codefactor.io/repository/github/wmfs/cardscript-table-of-contents) 
[![Dependabot badge](https://img.shields.io/badge/Dependabot-active-brightgreen.svg)](https://dependabot.com/) 
[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/) 
[![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com) 
[![license](https://img.shields.io/github/license/mashape/apistatus.svg)](https://github.com/wmfs/tymly/blob/master/packages/concrete-paths/LICENSE)

> Extracts a table-of-contents from some Cardscript.

## <a name="install"></a>Install
```bash
$ npm install cardscript-table-of-contents --save
```

## <a name="usage"></a>Usage

```javascript
const extractToc = require('@wmfs/cardscript-table-of-contents')

const toc = extractToc(
  {
    "type": "AdaptiveCard",
    "body": [
      {
        "type": "TextBlock",
        "text": "Change me!",
        "color": "attention",
        "horizontalAlignment": "center"
      }
    ],
    "$schema": "http://adaptivecards.io/schemas/adaptive-card.json",
    "version": "1.0"
  }
)

```

## <a name="test"></a>Testing

```bash
$ npm test
```

## <a name="license"></a>License
[MIT](https://github.com/wmfs/cardscript/blob/master/LICENSE)
