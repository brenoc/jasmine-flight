# jasmine-flight-standalone [![Build Status](https://travis-ci.org/brenoc/jasmine-flight.png?branch=master)](http://travis-ci.org/brenoc/jasmine-flight)

Fork of [jasmine-flight](https://github.com/flightjs/jasmine-flight) for Flight Standalone

Usage:
```js
'use strict';

describeComponent('component/Example', AddressList, function () {

  // Initialize the component and attach it to the DOM
  beforeEach(function () {
    setupComponent();
  });

  it('should be defined', function () {
    expect(this.component).toBeDefined();
  });

  it('should do something', function () {
    expect(true).toBe(false);
  });

});

```