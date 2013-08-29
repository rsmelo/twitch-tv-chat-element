# &lt;twitch-tv-chat&gt;

Web Component wrapper for [Twitch.tv chat](http://www.twitch.tv/) using Polymer.

> Maintained by [Rodrigo Silva de Melo](https://github.com/rsmelo).

## Demo

> [Check it live](http://rsmelo.github.io/twitch-tv-chat-element).

## Usage

1. Import Web Components' polyfill:

	```html
	<script src="http://cdnjs.cloudflare.com/ajax/libs/polymer/0.0.20130711/polymer.min.js"></script>
	```

2. Import Custom Element:

	```html
	<link rel="import" href="src/twitch-tv-chat-element.html">
	```

3. Start using it!

	```html
	<twitch-tv-chat></twitch-tv-chat>
	```

## Options

Attribute  | Options                   | Default          | Description
---        | ---                       | ---              | ---
`channel`         | *string*           | `joindotared`    | your channel in twitch.tv
`height`          | *int*              | 500              | height
`width`           | *int*              | 350              | width


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

* v0.1.0 August 28, 2013
	* First version of twitch-tv-chat
* v0.0.1 August 19, 2013
	* Started project using [boilerplate-element](https://github.com/customelements/boilerplate-element)

## License

[MIT License](http://opensource.org/licenses/MIT)