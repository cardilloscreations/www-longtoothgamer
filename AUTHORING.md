# Authoring Content

This website is based on a licensed copy of the Sera Jekyll Theme. However, it
has been highly customized at this point to better suit my needs.

The instructions below are useful reminders but it's a fairly common workflow for any Jekyll based website.

## System Preparation

To use this project, you'll need the following things installed on your machine.

1. [Jekyll](http://jekyllrb.com/docs/) - `$ gem install jekyll bundler`
2. [Jekyll-Gems](http://jekyllrb.com/docs/) - `$ bundle install`


## Usage

Since this is a Jekyll theme, every command described in the [Jekyll documentation](https://jekyllrb.com/docs/) is available.

### Development

To start the development workflow, run:

```
bundle exec jekyll serve --livereload
```

### Production

To build the project, run:

```
bundle exec jekyll build
```

### GitHub

In practice, the production step is not required because GitHub will compile the project and publish the new version when new commits are merged.
