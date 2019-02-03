### chai
---
https://github.com/chaijs/chai

```
npm install chai

mocha spec.js -r chai/register-assert
mocha spec.js -r chai/register-expect
mocha spec.js -r chai/register-should
```

```js
var chai = require('chai');
var assert = chai.assert;
var expect = chai.expect;
var should = chai.should();

require('chai/register-assert');
require('chai/register-expect');
require('chai/register-should');

const { assert } = require('chai');
const { expect } = require('chai');
const { should } = require('chai');
should();

const { expect, use } = require('chai');

import 'chai/register-assert';
import 'chai/register-expect';
import 'chai/register-should';

import { assert } from 'chai';
import { expect } from 'chai';
import { should } from 'chai';

```

```
<script src="./node_modules/chai/chai.js"></script>
```


