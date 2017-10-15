# react-mdi-props

It's a fork from [react-mdi](https://github.com/gabriel-miranda/react-mdi) with realized pass props.

Material-UI community Material Design Icons.

[Community Material Design Icons](https://materialdesignicons.com/) as svg react components, built with [icon-builder](https://github.com/gabriel-miranda/material-ui/tree/master/icon-builder) from Material-UI.

Special thanks to [Austin Andrews](https://github.com/Templarian) for managing Material Design Icons.

## Installation

```sh
npm install react-mdi-props
```

## Usage

```js
import React from 'react';

import AccountIcon from 'react-mdi-props/icons/account';

export default class Account extends React.Component {
  onClick = () => { console.log('Click!'); };
  render() {
    const color = '#fff';
    return (
      <AccountIcon
        className="myClassName"
        fill={color}
        size={16}
        onClick={this.onClick}
      />
    );
  }
}
```

## Props
Icon component can get any props.

## Build

```sh
npm run build
```
