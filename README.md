# Plotly::Js::Rails

plotly-js-rails provides the plotly.js library as a Rails engine to use it within the asset pipeline.

Original Git source - https://github.com/plotly/plotly.js

## Installation

Add this to your Gemfile:

    $ gem plotly-js-rails

and run bundle install.

## Usage

In your `application.js`, include the following:

```
//= require plotly.min
```

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

## Update Assets

Execute `bin/update` to update the assets and the version of the gem.
Then push your changes to github and create a release tag.

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
