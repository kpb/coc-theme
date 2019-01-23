# coc-theme

Hi! This is the default theme for the [Culture of Code](https://cultureofcode) blog.


## Installation

__NOTE__: This hasn't been pushed to [Ruby Gems](https://rubygems.org/), so you'll have to build and install it locally
for now.

Add this line to your Jekyll site's `Gemfile`:

```ruby
gem "coc-theme"
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
theme: coc-theme
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install coc-theme

## Development

To set up your environment to develop this theme, run `bundle install`.

Your theme is setup just like a normal Jekyll site! To test your theme, run `bundle exec jekyll serve` and open your browser at `http://localhost:4000`. This starts a Jekyll server using your theme. Add pages, documents, data, etc. like normal to test your theme's contents. As you make modifications to your theme and to your content, your site will regenerate and you should see the changes in the browser after a refresh, just like normal.

When your theme is released, only the files in `_layouts`, `_includes`, `_sass` and `assets` tracked with Git will be bundled.
To add a custom directory to your theme-gem, please edit the regexp in `coc-theme.gemspec` accordingly.

### Building and Installing (locally)

    $ gem build coc-theme.gemspec

    $ gem install coc-theme-0.1.0.gem

## License

The theme is available as open source under the terms of the [GNU General Public License version 3 or later]()

Copyright Kenneth Bowen 2019
