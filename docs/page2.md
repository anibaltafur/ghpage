---
layout: custom
---

# Page 2

Page example

## Heading 1


1. Install the theme as a Ruby Gem by adding it to your `Gemfile`
   like so:

   ```ruby
   gem 'uswds-jekyll'
   ```

1. Fetch and update your bundled gems by running:

   ```sh
   bundle
   ```

1. Set the `theme` in your site's Jekyll configuration,
   `_config.yml`:

   ```yml
   theme: uswds-jekyll
   ```

You will need to restart your Jekyll server to see the effects.

### Install as a new Jekyll site

1. Create a new Jekyll site:
   ```
   jekyll new
   ```
1. Replace the default `gem "minima", "~> 2.0"` gem with the `uswds-jekyll` gem in your `Gemfile`:

   ```ruby
   gem 'uswds-jekyll'
   ```

1. Set the `theme` in your site's Jekyll configuration, `_config.yml`:

   ```yml
   theme: uswds-jekyll
   ```

1. Fetch and update your bundled gems by running:

   ```sh
   bundle
   ```

## Heading 2


### Graphics list

```yml
# an optional list of graphics to display before or after the content
graphics:
  - image:
      # note the indentation here: graphics[n].image.src
      src: /path/to/image.ext
      alt: optional alt text
    title: Optional graphic title, rendered as an <h3>
    description: Graphic description text, processed as _Markdown_.

# optional
graphics_position: (before|after)
```
