# hexo-index-anything

![npm](https://img.shields.io/npm/v/hexo-index-anything.svg) ![license](https://img.shields.io/npm/l/hexo-index-anything.svg) ![github-issues](https://img.shields.io/github/issues/leviwheatcroft/hexo-index-anything.svg)  ![Circle CI build status](https://circleci.com/gh/leviwheatcroft/hexo-index-anything.svg?style=svg)

Hexo plugin to generate a indexes from custom front matter variables. Suppose
you have an author variable in your front matter, this plugin will generate
files like /authors/author-name.html, listing each post by that author.

![nodei.co](https://nodei.co/npm/hexo-index-anything.png?downloads=true&downloadRank=true&stars=true)

![travis-status](https://img.shields.io/travis/leviwheatcroft/hexo-index-anything.svg)
![stars](https://img.shields.io/github/stars/leviwheatcroft/hexo-index-anything.svg)

## Install

`npm install --save hexo-index-anything`

## Configuration

an example. would be included in `_config.yml`

```yaml
indexAnything:
  author: authors
```

## Usage

Install, configure, then `hexo generate` as usual.

## Api

hexo-index-anything api

## Author

Levi Wheatcroft <levi@wht.cr>

## Contributing

Contributions welcome; Please submit all pull requests against the master
branch.

## License

 - **MIT** : http://opensource.org/licenses/MIT
