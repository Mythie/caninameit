# Can I name it ? 
[![Build Status](https://travis-ci.org/SaraVieira/caninameit.svg?branch=master)](https://travis-ci.org/SaraVieira/caninameit)

A cli tool to help you see a npm name is already taken because this a problem now 😱

## Install

```
$ npm install --global caninameit
```

```
$ yarn global caninameit
```

## Examples

```
$ caninameit --help

  Usage
    caninameit [input]

  Examples
    $ caninameit react
     > Damn it, the name is already taken ☹️

	 $ caninameit react2
    > NICE! The name is not taken you can claim it! 🍕 🎉🎉🎉
```


## TODO

	- Add idc flag to not output version and creators of a package
	- Add publish flag to auto publish a package a secure your name


## License

MIT © [Sara Vieira](https://github.com/SaraVieira)
