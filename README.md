# Hugo Theme: Console

A fork of the [console
theme](https://github.com/mrmierzejewski/hugo-theme-console) for
[Hugo](https://gohugo.io/) I customized for [my
website](https://tyagdit.github.io)

## Changes

- Dark theme
- The terminal prompt header looks better 
- Can add an optional "command" at the end of the prompt (using front matter)
  and customize the beginning
- Changed the 404 page
- Removed the zoom in animation
- Removed footer from homepage
- Removed date from post list and replaced with "file permissions"
- Added a shortcode to show a blinking cursor: `{{< cursor >}}`
- Added an option to remove blinking cursor from header prompt
- Changed post list

## Installation

In your website's root directory:

```sh
$ git submodule add https://github.com/tyagdit/hugo-theme-console.git themes/hugo-theme-console
```
    
See the [Hugo documentation](https://gohugo.io/themes/installing/) for more
information.

## Configuration

Copy the `config.toml` file from the `exampleSite` directory to the root of your
website folder and customize it as you like.

## Example Site

To test the theme with the example site, navigate to the theme directory (not
`exampleSite`) and type `makefile hugo-server`

### Start page

The default start page template is located at
`themes/hugo-theme-console/layouts/index.html`. To change the page content, you
to need to copy this file to the `layouts` directory in your website's root
directory (`layouts/index.html`) and customize it as you like.

## License

Copyright © 2020 [Marcin Mierzejewski](https://mrmierzejewski.com/)

The theme is released under the MIT License. Check the [original theme
license](https://github.com/panr/hugo-theme-terminal/blob/master/LICENSE.md) for
additional licensing information.
