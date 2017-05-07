# MMM-chuck-joke
A `Chuck Norris joke generator` for <a href="https://github.com/MichMich/MagicMirror">MagicMirror</a> module.
Currently there are ~600 jokes available.

## Using the module
Add `MMM-chuck-joke` module to the `modules` array in the `config/config.js` file:
````javascript
modules: [
  {
    module: 'MMM-chuck-joke',
    position: 'top_right',
    config: {
      updateInterval: 300, // Seconds
	  fadeSpeed: 4, //Seconds
    }
  },
]
````

## Screenshot
![](preview.png?raw=true)

## Copyright
Copyright (C) 2017 by Christian Handorf with [MIT License](LICENSE.md).
