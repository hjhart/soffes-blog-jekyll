# soffes-blog-jekyll

Welcome to your new Jekyll theme! In this directory, you'll find the files you need to be able to package up your theme into a gem. Put your layouts in `_layouts`, your includes in `_includes` and your sass in `_sass`. To experiment with this code, add some sample content and run `bundle exec jekyll serve` – this directory is setup just like a Jekyll site!

This is the soffes.blog theme, but made so that you can use jekyll.

## Installation

Add this line to your Jekyll site's `Gemfile`:

```ruby
gem "soffes-blog-jekyll"
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
theme: soffes-blog-jekyll
description: > # this means to ignore newlines until "full_name:"
  This is my blog. Enjoy.
full_name: James Hart
short_name: James
copyright_start_year: 2014
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install soffes-blog-jekyll

## TODO:

* Delete the fonts.css file in `assets` and set up a system for using cloud.typography.com subscriptions.
* The bourbon dependency was injected using the `bourbon install` command. Can we add a runtime / dev dependency and make this work, without muddying up the `_sass` directory?
* Pagination does not work yet (commented out in home.html)
* javascript doesn't load yet
* Never implemented cover images (not sure where one exists).
* Next post footer is not implemented in markdown world yet (see post.html)
* JSON feed not implemented - does it matter?
* Javascript does not have coffeescript pipeline

## Usage

### In progress below:

Sign up for a typography.com account, the fonts are essential. The cost is $99 / year for up to 250k page views.

	https://www.typography.com/account/your-account.php

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/hello. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## Development

To set up your environment to develop this theme, run `bundle install`.

Your theme is setup just like a normal Jekyll site! To test your theme, run `bundle exec jekyll serve` and open your browser at `http://localhost:4000`. This starts a Jekyll server using your theme. Add pages, documents, data, etc. like normal to test your theme's contents. As you make modifications to your theme and to your content, your site will regenerate and you should see the changes in the browser after a refresh, just like normal.

When your theme is released, only the files in `_layouts`, `_includes`, and `_sass` tracked with Git will be released.

## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

