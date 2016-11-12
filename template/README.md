#{{name}}

[![npm version](https://badge.fury.io/js/{{name}}.svg)](https://badge.fury.io/js/{{name}}) {{#test}}[![travis-ci](https://travis-ci.org/justinjmoses/{{name}}.svg?branch=master)](https://travis-ci.org/justinjmoses/{{name}}.svg?branch=master){{/test}}

{{description}}

![]({{imageUrl}})

###Installation
{{#bin}}
Install via `npm i -g {{name}}`
{{else}}
Run `npm i {{name}}`
{{/bin}}

###Examples
Run via `node examples`

{{#test}}
###Run Tests
Run via `npm test`
{{/test}}
