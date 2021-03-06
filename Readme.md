*This repository is a mirror of the [component](http://component.io) module [matthewmueller/typewriter](http://github.com/matthewmueller/typewriter). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/matthewmueller-typewriter`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# typewriter

  animated typing

## Example

![animated](http://f.cl.ly/items/2z1A0V473f3G3n3O0e2P/typewriter.gif)

```js
typewriter('#typewriter', 'Hello world!').start();
```

## Installation

    $ component install matthewmueller/typewriter

## Events

  - `end` : emitted when `typewriter` finishes
  - `start` : emitted when `typewriter` starts typing
  - `stop` : emitted when we manually stop `typewriter`
  - `restart` : emitted when we manually restart `typewriter`

## API

### typewriter(el, str, [delay])

  Initialize `Typewriter` on a given `el`, with the string `str` and `delay`. If no `delay` is specified, it defaults to 100.

```js
typewriter('#header', 'Hello world!', 200);
```

### #start()

  Start the typewriter

```js
typewriter.start()
```

### #stop()

  Stop the typewriter

```js
typewriter.stop()
```

### #restart()

  Restart the typewriter. Clears the input

```js
typewriter.restart()
```

### #clear()

  Clear the typewriter input

```js
typewriter.clear();
```



## License

  MIT
