
# `$ emojer` [![PayPal](https://img.shields.io/badge/%24-paypal-f39c12.svg)][paypal-donations] [![Version](https://img.shields.io/npm/v/emojer-cli.svg)](https://www.npmjs.com/package/emojer-cli) [![Downloads](https://img.shields.io/npm/dt/emojer-cli.svg)](https://www.npmjs.com/package/emojer-cli) [![Get help on Codementor](https://cdn.codementor.io/badges/get_help_github.svg)](https://www.codementor.io/johnnyb?utm_source=github&utm_medium=button&utm_term=johnnyb&utm_campaign=github)

> Command line tool for emojer.

## :cloud: Installation

You can install the package globally and use it as command line tool:


```sh
$ npm i -g emojer-cli
```


Then, run `emojer --help` and see what the CLI tool can do.


```
$ emojer --help
Usage: emojer-cli [options]

Options:
  -t, --template <template>  The template snippet.
  -i, --input <message>      The input message containing :emoji: snippets
                             (note you can pipe the things in the stdin too).
  -p, --path <path>          The path to a file you want to emojify.
  -o, --output <path>        Specify an output file where to write the result.
  -h, --help                 Displays this help.
  -v, --version              Displays version information.

Examples:
  echo ':octocat:' | emojer -t 'https://github.global.ssl.fastly.net/images/icons/emoji/__EMOJI_NAME__.png'
  emojer -i 'octocat' -t 'https://github.global.ssl.fastly.net/images/icons/emoji/__EMOJI_NAME__.png'
  emojer -p some-file.html -t 'https://github.global.ssl.fastly.net/images/icons/emoji/__EMOJI_NAME__.png'
  emojer -p some-file.html -t 'https://github.global.ssl.fastly.net/images/icons/emoji/__EMOJI_NAME__.png' -o result.html

Emojify all the things!

Documentation can be found at https://github.com/IonicaBizau/emojer-cli#readme
```

## :memo: Documentation

For full API reference, see the [DOCUMENTATION.md][docs] file.

## :yum: How to contribute
Have an idea? Found a bug? See [how to contribute][contributing].


## :scroll: License

[MIT][license] © [Ionică Bizău][website]

[paypal-donations]: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=RVXDDLKKLQRJW
[donate-now]: http://i.imgur.com/6cMbHOC.png

[license]: http://showalicense.com/?fullname=Ionic%C4%83%20Biz%C4%83u%20%3Cbizauionica%40gmail.com%3E%20(http%3A%2F%2Fionicabizau.net)&year=2016#license-mit
[website]: http://ionicabizau.net
[contributing]: /CONTRIBUTING.md
[docs]: /DOCUMENTATION.md
