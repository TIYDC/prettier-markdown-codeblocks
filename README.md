# Prettier Markdown Codeblocks

[![Build Status](https://travis-ci.org/rposborne/prettier-markdown-codeblocks.svg?branch=master)](https://travis-ci.org/rposborne/prettier-markdown-codeblocks)
[![Version](https://img.shields.io/npm/v/prettier-markdown-codeblocks.svg)](https://www.npmjs.com/package/prettier-markdown-codeblocks)
[![Downloads](https://img.shields.io/npm/dt/prettier-markdown-codeblocks.svg)](https://www.npmjs.com/package/prettier-markdown-codeblocks)

Format codeblocks in markdown files using [prettier](https://prettier.io/) and [rubocop](https://github.com/bbatsov/rubocop).  

![Autocorrecting markdown codeblocks](https://raw.github.com/rposborne/prettier-markdown-codeblocks/master/docs/demo.gif)

Supports

- JavaScript, including [ES2017](https://github.com/tc39/proposals/blob/master/finished-proposals.md)
- [JSX](https://facebook.github.io/jsx/)
- [Flow](https://flow.org/)
- [TypeScript](https://www.typescriptlang.org/)
- CSS, [LESS](http://lesscss.org/), and [SCSS](http://sass-lang.com)
- [JSON](http://json.org/)
- [GraphQL](http://graphql.org/)
- [Ruby](http://ruby-lang.org/) (via rubocop `gem install rubocop`)

We aslo support full customization using .eslintrc.js file and respctive .rubocop.yml configuration files to tweak the formatted style to your projects requirements.

Wishlist

- Java (in progress)
- C#
- Python

## Usage

Directory
```sh
prettier-markdown-codeblocks <directory>
```

File
```sh
prettier-markdown-codeblocks <file.md>
```

Stdin
```sh
cat <file.md> | prettier-markdown-codeblocks | tee <file.md>
```

## Contributing

👍🎉 First off, thanks for taking the time to contribute! 🎉👍

Bug reports and pull requests are welcome on GitHub at https://github.com/rposborne/prettier-markdown-codeblocks. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## License

The package is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
