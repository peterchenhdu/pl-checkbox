# pl-checkbox
---

### 该仓库基于 https://github.com/react-component/checkbox 进行修改，用于个人学习。

[![NPM version][npm-image]][npm-url]
[![build status][travis-image]][travis-url]
[![Test coverage][coveralls-image]][coveralls-url]
[![gemnasium deps][gemnasium-image]][gemnasium-url]
[![npm download][download-image]][download-url]

[npm-image]: https://img.shields.io/npm/v/pl-checkbox.svg?style=flat-square
[npm-url]: https://www.npmjs.com/package/pl-checkbox
[travis-image]: https://travis-ci.org/peterchenhdu/pl-checkbox.svg?branch=master
[travis-url]: https://travis-ci.org/peterchenhdu/pl-checkbox

[coveralls-image]: https://img.shields.io/coveralls/peterchenhdu/pl-checkbox.svg?style=flat-square
[coveralls-url]: https://coveralls.io/r/peterchenhdu/pl-checkbox?branch=master
[gemnasium-image]: http://img.shields.io/gemnasium/peterchenhdu/pl-checkbox.svg?style=flat-square
[gemnasium-url]: https://gemnasium.com/peterchenhdu/pl-checkbox

[download-image]: https://img.shields.io/npm/dm/pl-checkbox.svg?style=flat-square
[download-url]: https://www.npmjs.com/package/pl-checkbox

## install

[![pl-checkbox](https://nodei.co/npm/pl-checkbox.png)](https://npmjs.org/package/pl-checkbox)

## Usage

```js
import React from 'react'
import Checkbox from 'pl-checkbox';
export default class Index extends React.Component{
  constructor(props){
    super(props);
  }
  render(){
    return (
      <div >
        这是一个chechbox : <Checkbox />
      </div>
      );
  }
}
```

## API

### props

<table class="table table-bordered table-striped">
    <thead>
    <tr>
        <th style="width: 100px;">name</th>
        <th style="width: 50px;">type</th>
        <th style="width: 50px;">default</th>
        <th>description</th>
    </tr>
    </thead>
    <tbody>
        <tr>
          <td>prefixCls</td>
          <td>String</td>
          <td>rc-checkbox</td>
          <td></td>
        </tr>
        <tr>
          <td>className</td>
          <td>String</td>
          <td>''</td>
          <td>additional class name of root node</td>
        </tr>
         <tr>
          <td>name</td>
          <td>String</td>
          <td></td>
          <td>same with native input checkbox</td>
        </tr>
        <tr>
          <td>checked</td>
          <td>enum: 0,1,2</td>
          <td></td>
          <td></td>
        </tr>
        <tr>
          <td>defaultChecked</td>
          <td>enum: 0,1,2</td>
          <td>0</td>
          <td>same with native input checkbox</td>
        <tr>
          <td>onChange</td>
          <td>Function(e:Event, checked:Number)</td>
          <td></td>
          <td>called when checkbox is changed. e is native event, checked is original checked state.</td>
        </tr>
    </tbody>
</table>

## Development

```
npm install
npm start
```

## Example

http://localhost:8001/examples/

online example: http://react-component.github.io/checkbox/examples/

## Test Case

```
npm test
npm run chrome-test
```

## Coverage

```
npm run coverage
```

open coverage/ dir


## License

pl-checkbox is released under the MIT license.
