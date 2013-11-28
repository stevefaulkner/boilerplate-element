# &lt;my-element&gt;

TODO: Write a project description

> Maintained by [Steve Faulkner](https://github.com/stevefaulkner).

## Demo

> [Check it live](http://stevefaulkner.github.io/subhead-element/).

## Usage

1. Import Web Components' polyfill:

	```html
	<script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.0.20130711/polymer.min.js"></script>
	```

2. Import Custom Element:

	```html
	<link rel="import" href="src/subhead-element.html">
	```

3. Start using it!

	```html
	<subhead></subhead>
	```

## Options

Attribute  | Options                   | Default             | Description
---        | ---                       | ---                 | ---
`foo`      | *string*                  | `bar`               | Lorem ipsum
`bar`      | `abc`, `def`, `ghi` 	   | `foo`               | Lorem ipsum
`height`   | *int*                     | `100`               | Lorem ipsum


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

* v0.0.1 November, 2013
	* Started project using [boilerplate-element](https://github.com/customelements/boilerplate-element)

## License

[MIT License](http://opensource.org/licenses/MIT)
