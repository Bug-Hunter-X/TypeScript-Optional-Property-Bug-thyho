This repository demonstrates a common but subtle bug in TypeScript related to optional properties.  The `printCoord` function expects an object with both `x` and `y` properties. However, if you pass an object missing either property, TypeScript won't prevent a runtime error.  The solution demonstrates how to address this by using optional properties correctly and handling the potential absence of `x` or `y` gracefully.