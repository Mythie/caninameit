# Can I name it ?

[![Greenkeeper badge](https://badges.greenkeeper.io/SaraVieira/caninameit.svg)](https://greenkeeper.io/)
[![Build Status](https://travis-ci.org/SaraVieira/caninameit.svg?branch=master)](https://travis-ci.org/SaraVieira/caninameit)

A cli tool to help you see a npm name is already taken because this a problem now 😱

<a target='_blank' rel='nofollow' href='https://app.codesponsor.io/link/TcwA1EShekGpPzRyQvGn9ysQ/SaraVieira/caninameit'>
  <img alt='Sponsor' width='888' height='68' src='https://app.codesponsor.io/embed/TcwA1EShekGpPzRyQvGn9ysQ/SaraVieira/caninameit.svg' />
</a>

## Install

```
$ npm install --global caninameit
```

```
$ yarn global add caninameit
```

## Examples

```
$ caninameit --help

  Usage
    caninameit [input] {--flag}

  Examples
    $ caninameit react
     > Damn it, the name is already taken ☹️

		 It was created by:
		   Jason Miller

		 It's at version:
		   8.2.1

		 You can find it at:
		   https://www.npmjs.com/package/preact

	 $ caninameit react --idc
 	 > Damn it, the name is already taken ☹️

	 $ caninameit wtv-name-you-want
    > NICE! The name is not taken you can claim it! 🍕 🎉🎉🎉
```


## TODO
	- Add publish flag to auto publish a package and secure your name


## License

MIT © [Sara Vieira](https://github.com/SaraVieira)
