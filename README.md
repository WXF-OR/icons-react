<!--
 * @Author: your name
 * @Date: 2021-08-06 15:07:32
 * @LastEditTime: 2021-08-17 14:30:45
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: /study/icons-react/README.md
-->
<h1 align="center">
Ant Design Icons for React
</h1>

<div align="center">

[![NPM version](https://img.shields.io/npm/v/@ant-design/icons.svg?style=flat)](https://npmjs.org/package/@ant-design/icons)
[![NPM downloads](http://img.shields.io/npm/dm/@ant-design/icons.svg?style=flat)](https://npmjs.org/package/@ant-design/icons)

</div>

## Install

```bash
yarn add @ant-design/icons@4.0.0
```

## Basic Usage

You can import it directly or destructure from `@ant-design/icons` when tree-shaking enabled.

```ts
import SmileOutlined from '@ant-design/icons/SmileOutlined';
import { SmileOutlined } from '@ant-design/icons';

import SmileFilled from '@ant-design/icons/SmileFilled';
import SmileTwoTone from '@ant-design/icons/SmileTwoTone';
import { SmileFilled, SmileTwoTone } from '@ant-design/icons';
```

## Component Interface

```ts
interface AntdIconProps {
  className?: string;
  onClick?: React.MouseEventHandler<SVGSVGElement>;
  style?: React.CSSProperties;
}
```

## Release

```bash
npm run generate
npm run compile
npm publish


```
