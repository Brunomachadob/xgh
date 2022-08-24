# Running it locally

### Initial setup
```bash
$ gem install jekyll bundler
$ bundle install
```

### Execute local server with hot reload
```bash
bundle exec jekyll s
```

### Contributing with a new language

There are three simple steps:
1. Create a new markdown file with the language code as name (e.g `pt-br.md`) on the root folder
2. Update the [language selector](https://github.com/Brunomachadob/xgh/blob/main/_layouts/default.html#L82) with it
   1. Confirm the name of the value matches the `name` of the `option`
3. Please rememebr to update all anchor links on the document