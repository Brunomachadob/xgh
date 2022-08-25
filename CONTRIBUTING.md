# Contributing with a new language

There are two simple steps:
1. Create a new markdown file with the language code as name (e.g `pt-br.md`) on the root folder;
2. Update the [language selector](https://github.com/Brunomachadob/xgh/blob/f3ca2ed7cd3d1e84638ce7a00be654a14a05e04b/_layouts/default.html#L85) with it.
    1. Make sure the file name matches the `name` of the `option`

# Contributing with a correction

Feel free to just open a pull request or file an issue [here](https://github.com/Brunomachadob/xgh/issues/new).

# Running it locally

### Requirements

- `ruby 2.6+`
- `gem 3.0+`

### Initial setup

```bash
$ gem install jekyll bundler
$ bundle install
```

### Execute local server with hot reload

```bash
bundle exec jekyll s
```
