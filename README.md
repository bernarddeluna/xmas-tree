# &lt;xmas-tree&gt;

Web Components Experiment using [Ambient Light API](http://www.w3.org/TR/ambient-light/).

> **Attention:** Ambient Light API only works in Firefox 22+ (Mac OS X).

## Demo

![Demo]()

> [Check it live](http://bernarddeluna.github.io/xmas-tree).

## Setup

1. Install [NodeJS](http://nodejs.org/download/), if you don't have it yet.

2. Install [GruntJS](http://gruntjs.com/) globally:

	```sh
$ [sudo] npm install -g grunt-cli
	```

3. Install local dependencies:

	```sh
$ npm install
	```

4. Run a local server:

	```sh
$ grunt
	```

Now you can see the website running in `http://localhost:9000` :D

## Usage

1. Import Web Components' polyfill:

	```xml
<script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.0.20130816/polymer.min.js"></script>
	```

2. Import Custom Element:

	```xml
<link rel="import" href="src/xmas-tree.html">
	```

3. Start using it!

	```xml
<xmas-tree></xmas-tree>
	```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## License

[MIT License](http://opensource.org/licenses/MIT) © Bernard de Luna & Zeno Rocha