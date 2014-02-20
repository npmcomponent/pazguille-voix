*This repository is a mirror of the [component](http://component.io) module [pazguille/voix](http://github.com/pazguille/voix). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/pazguille-voix`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# Voix JS

A JavaScript library to add voice commands to your sites, apps or games.

**NOTE:** At this time, this library is only compatible with Google Chrome.

## Installation

    $ component install pazguille/voix

See: [https://github.com/component/component](https://github.com/component/component)

### Standalone
You can use the standalone version:
```html
<script src="voix.js"></script>
```

## How-to
Create a new instance of Voix.
```js
var voix = new Voix('en-US');
```

## API
### Voix(lang)
Create a new instance of `Voix`.
- `lang`: A given language.

```js
var voix = new Voix('en-US');
```

### Voix#setCommand(command, listener)
Sets a new `command` with a `listener` to the collection.
- `command` - A given `command`.
- `listener` - A given `listener`.

```js
voix.setCommand('play', playVideo);
```

### Voix#removeCommand(command, listener)
Removes a given `command` or its `listener` from the collection.
- `command` - A given `command` to remove.
- `listener` [optional] - A given `listener` to remove.

```js
voix.removeCommand('play', playVideo);

// or

voix.removeCommand('play');
```

### Voix#start()
Starts the recognition.

```js
voix.start();
```

### Voix#stop()
Stops the recognition.

```js
voix.stop();
```

## Maintained by
- Guille Paz (Front-end developer | Web standards lover)
- E-mail: [guille87paz@gmail.com](mailto:guille87paz@gmail.com)
- Twitter: [@pazguille](http://twitter.com/pazguille)
- Web: [http://pazguille.me](http://pazguille.me)

## License
Licensed under the MIT license.

Copyright (c) 2013 [@pazguille](http://twitter.com/pazguille).
