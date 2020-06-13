# Bootstrap Italia - Hugo Theme

Disclaimer: hugely WIP

## Install

Follow these steps to have a working Hugo site

* Create a new Hugo site with

  `hugo new site site_name`
* Add the content of this repo within `site_name/themes/hugo-theme-bootstrap-italia`, ensuring the resulting folder structure is as follows:

  ```
  site_name
  │
  └───themes
      │
      └───hugo-theme-bootstrap-italia
          │   config.toml
          │   theme.toml
          │   ...
          │
          └───archetypes
          │
          └───layouts
          │
          └───static
   ```

* Add this line to your `site_name/config.toml` file:

  `theme = "hugo-theme-bootstrap-italia"`

* Edit your website `site_name/config.toml` to override rules defined in `site_name/themes/hugo-theme-bootstrap-italia/config.toml`.

* Test your website with `hugo server`. For additional info about `hugo server` command options, refer to https://gohugo.io/commands/hugo_server/
 
## Getting Started

In order to add content to the website, you can just create a `site_name/content/_index.md` with some Markdown in it, ie.:

```
# h1

## h2

### h3

paragraph
```

That should just render to something like this:

<img src="https://github.com/francescozaia/hugo-theme-bootstrap-italia/blob/master/theme-preview.png" width="800"> 

_( ...more will follow)_

## Upgrading external dependencies

    yarnpkg upgrade
    make
