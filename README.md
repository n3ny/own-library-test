# own-library-test

> Made with create-react-library

[![NPM](https://img.shields.io/npm/v/own-library-test.svg)](https://www.npmjs.com/package/own-library-test) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## Install

### with npm
```bash
npm install --save own-library-test
```

### with yalc
```bash
yalc add own-library-test
```

## Usage

```jsx
import React, { Component } from 'react'

import MyComponent from 'own-library-test'
import 'own-library-test/dist/index.css'

class Example extends Component {
  render() {
    return <MyComponent />
  }
}
```

### Update clients of the library after a change

```bash
 yalc publish; yalc push
```

### Note
Run `yalc check` in the client app before push to avoid the push of yalc packages on the dependencies
