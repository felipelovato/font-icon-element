# &lt;icon&gt;

Web Component wrapper for [Font-Awesome - The iconic font designed for Bootstrap](http://fortawesome.github.io/Font-Awesome/) using Polymer.

> Maintained by [Thiago Alves](https://github.com/taltk9).

## Usage

1. Add Font Awesome into your website with on line of code. You don't even have to download or install anything! Just paste the following code into the `<head>` section of your site's HTML. If you prefer, see the [Font Awesome get-started](http://fortawesome.github.io/Font-Awesome/get-started/).

	```html
		<link href="//netdna.bootstrapcdn.com/font-awesome/3.2.1/css/font-awesome.css" rel="stylesheet">
	```

2. Import Web Components' polyfill:

	```html
	<script src="lib/polymer.min.js"></script>
	```

3. Import Custom Element:

	```html
	<link rel="import" href="src/font-icon.html">
	```

4. Start using it!

	```html
	<icon name=""></icon>
	```


## Options

Attribute  		| Options                   													| Default             | Description
---        		| ---                       													| ---                 | ---
`name`     		| *[Font Awesome classes](http://fortawesome.github.io/Font-Awesome/icons/)* 	| `null`              | Font Awesome class without "icon" prefix
`size`     		| `large`, `1`, `2`, `3`, `4` 										        	| `null`              | Icon size
`combine`  		| *[Font Awesome classes](http://fortawesome.github.io/Font-Awesome/icons/)* 	| `null`              | Font Awesome class without "icon" prefix to combine icons
`combineClass`  | *string* 																		| `null`              | CSS classes to combined icon
`combineStyle`  | *string* 																		| `null`              | Some styles to combined icon


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

## History

* v0.0.1 August 25, 2013
	* Started project using [boilerplate-element](https://github.com/customelements/boilerplate-element)

## License

[MIT License](http://opensource.org/licenses/MIT)