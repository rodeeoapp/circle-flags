# circle-flags FORK with missing flags

A collection of circular SVG country flags.
FORK FROM https://hatscripts.github.io/

## Usage

```
https://rodeeoapp.github.io/circle-flags/flags/xx.svg
```
(Where `xx` is the [ISO 3166-1 alpha-2 code](https://www.iso.org/obp/ui/#search/code/) of a country).

For example, the following code:
```html
<img src="https://rodeeoapp.github.io/circle-flags/flags/br.svg" width="48">
<img src="https://rodeeoapp.github.io/circle-flags/flags/cn.svg" width="48">
<img src="https://rodeeoapp.github.io/circle-flags/flags/gb.svg" width="48">
<img src="https://rodeeoapp.github.io/circle-flags/flags/id.svg" width="48">
<img src="https://rodeeoapp.github.io/circle-flags/flags/in.svg" width="48">
<img src="https://rodeeoapp.github.io/circle-flags/flags/ng.svg" width="48">
<img src="https://rodeeoapp.github.io/circle-flags/flags/ru.svg" width="48">
<img src="https://rodeeoapp.github.io/circle-flags/flags/us.svg" width="48">
```

...produces this:<br/><br/>
<img src="https://rodeeoapp.github.io/circle-flags/flags/br.svg" width="48">
<img src="https://rodeeoapp.github.io/circle-flags/flags/cn.svg" width="48">
<img src="https://rodeeoapp.github.io/circle-flags/flags/gb.svg" width="48">
<img src="https://rodeeoapp.github.io/circle-flags/flags/id.svg" width="48">
<img src="https://rodeeoapp.github.io/circle-flags/flags/in.svg" width="48">
<img src="https://rodeeoapp.github.io/circle-flags/flags/ng.svg" width="48">
<img src="https://rodeeoapp.github.io/circle-flags/flags/ru.svg" width="48">
<img src="https://rodeeoapp.github.io/circle-flags/flags/us.svg" width="48">

To view all the available flags, check [the gallery](https://rodeeoapp.github.io/circle-flags/all-flags.html).

### React

If you're using [React](https://reactjs.org), you may want to try the
[react-circle-flags](https://www.npmjs.com/package/react-circle-flags) package.

### NPM

If you want to install this package as dependency, you can install it from this GitHub repository:

```
npm install --save https://github.com/rodeeoapp/circle-flags
```

## Contributing

To contribute, you need to have [svgo](https://github.com/svg/svgo) installed
(version 1.2.0 or newer).

First, edit the relevant SVG files in the `flags/` directory.

Then run `svgo` to optimize the SVG files:

```sh
svgo ./flags --recursive --config=svgo.yml
```

Then commit the changes, and submit them as a pull request.

## License

This project is released under the [MIT license](LICENSE).
