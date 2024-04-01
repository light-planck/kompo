# Kompo

TODO: Delete this and the text below, and describe your gem

Welcome to your new gem! In this directory, you'll find the files you need to be able to package up your Ruby library into a gem. Put your Ruby code in the file `lib/kompo`. To experiment with that code, run `bin/console` for an interactive prompt.

## Installation
Install the gem and add to the application's Gemfile by executing:

    $ bundle add kompo

If bundler is not being used to manage dependencies, install the gem by executing:

    $ gem install kompo

## Usage

### prerequisites
Install [komp-vfs](https://github.com/ahogappa0613/kompo-vfs).

#### Homebrew
```sh
$ brew tap ahogappa0613/kompo-vfs https://github.com/ahogappa0613/kompo-vfs.git
$ brew install ahogappa0613/kompo-vfs/kompo-vfs
```

### Quick Start
If you want to try it out, `cd` to the `sample/` directory and execute the following:
```sh
$ kompo
```
This will read the Gemfile in the directory and create an executable file with `main.rb` as the entry point in the same directory as `./sample` in the same directory.



## Development

After checking out the repo, run `bin/setup` to install dependencies. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and the created tag, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/ahogappa0613/kompo.
