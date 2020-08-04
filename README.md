# @akashv/treeformer

Convert a JSON/YAML into a Tree structure.

## Install

```
$ npm install @akashv/treeformer
```

## Usage

```
import { generateTree } from ("@akashv/treeformer");

const jsonData = {
  name:'John Doe',
  age: 20,
  children:[{name:'Jack', age:5}, {name:'Ann', age:8}],
  wife:{name:'Jane Doe', age:28 }
}

const result = generateTree(jsonData);
console.log(result)
```
