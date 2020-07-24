## Custom version of just-the-docs

This fork is a custom version of
[pmarsceill/just-the-docs](https://github.com/pmarsceill/just-the-docs). We
customize the title banner, navigation side bar, and footer.

### Title banner

We add variables to define the layout of the full-width title banner:

* `title-background-color` Background color for title banner (default: black).
* `title-color` Color of text in title banner (default: white).
* `title-height` Height of title banner (default: 3.0rem).
* `title_image` Relative URL for image to use in title banner.

The background color, color, and height should be set using the color
scheme. The image URL should be set in `_config.yml`.

### Site navigation

The site navigation (table of contents) is generated manually using a
[three-level navigation list](https://jekyllrb.com/tutorials/navigation/#scenario-4-three-level-navigation-list). Note
that we use `subitems` and `subsubitems` for the list structure.

### Footer

The footer include the software version and time stamp of when the
documentation was generated. The software version is set using
`software-version` in `_config.yml`.

## Sites using baagaard-usgs/just-the-docs

These sites may require updating when this fork is changed.

* [usgs/groundmotion-processing](https://github.com/usgs/groundmotion-processing)
* [usgs/earthquake-cencalvm](https://github.com/usgs/cencalvm)
* [baagaard-usgs/geomodelgrids](https://github.com/baagaard-usgs/geomodelgrids)
* [geodynamics/pylith_installer](https://github.com/geodynamics/pylith_installer)


## Installation

Add this line to your Jekyll site's Gemfile:

```ruby
gem "just-the-docs"
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
remote_theme: baagaard-usgs/just-the-docs
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install just-the-docs

### View Jekyll site locally

To view the Jekyll site locally (for example from your `docs` directory), run:

	$ bundle exec jekyll serve

## Documentation

See [pmarsceill/just-the-docs/](https://pmarsceill.github.io/just-the-docs/) for additional documentation.

## License

The theme is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
