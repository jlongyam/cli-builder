# cli-builder

## Install

```
npm install @jlongyam/cli-builder --save-dev
```

## Usage

__index.mjs__

```js
import { args } from "@jlongyam/cli-builder";
console.log(args)
```

__Shell__

```shell
node index.mjs --help
```

__result__:

```js
{ help: true }
```