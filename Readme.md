# Truetone Color Logger

This is a simple logger that wraps some console methods in a class to group log messages with context and color. This is also my first npm package. The main purposes of publishing this are:

1. So I can reuse this code I like
1. To see what is needed to publish an npm package.

## Usage

* `yarn add truetone-color-logger`

```
const logger = require("truetone-color-logger")

class MyClass {
  constructor() {
    this.logger = new logger(MyClass.name);

    this.logger.log("Hello world!");
  }
}
```

## Where are the tests?

There aren't any yet. See my purposes listed above.

## Support and Upcoming Features

Maybe. See my purposes above. As of now I don't plan to develop this any further nor do I plan to add new features.
