# gladys-devicetype-categories
Temporary repo to compile devicetype categories

Fill the ``./categories/index.js`` file like this : 
```
export default {
  sensors : {
    temperature: 'temperature-sensor',
    humidity: 'humidity-sensor'
    // ...
  },
  switches: {
    plug: 'plug',
    oneWay: 'one-way-switch',
    twoWay: 'two-way-switch',
    // ...
  },
  media: {
    tv: 'television',
    amplifier: 'amplifier',
    phone: 'phone',
  },
  light: {
    switch: 'light-switch',
    brightness: 'light-brightness'
    color: 'light-color',
    // ...
  }
  // ...
}
```

This way, you can separate categories into sub-categories and get a "key":"value" pair to have translations e.g.

