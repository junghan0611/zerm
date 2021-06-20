# zerm

my personal **fork** of a minimalist and dark theme for [Zola](https://getzola.org).

![Screenshot](../master/zerm-preview.png?raw=true)

[**Live Preview!**](https://zwitt-zerm.netlify.app/)

Largely a port of Radek Kozieł's [Terminal
Theme](https://github.com/panr/hugo-theme-terminal) for Hugo.

## differences from original theme

This theme is largely true to the original by Radek, but there are some mild
differences. They are almost all stylistic in nature and are intended to
emphasize minimalism even more. Some of them are as follows:
- tags are now included in a post's meta data.
- no post image previews.
- categories are included in the taxonomy.
- bullet points have slightly more margin and different symbols for nesting.
- no social media or comment support.

Some of these might be added later and [PR's are always
welcomed](https://github.com/ejmg/zerm/pulls).

## differences from ejmg port

- math typesetting support with KaTeX.
- copy URL to clipboard function at the end of the page.
- pagination at the end of the page.
- optional `support us` and `follow me` boxes at the end of the page.
- theme switcher for dark/light mode (this requires a custom colorscheme).
- duckduckgo search popover.
- highly optimized cover images for posts and lists.
- 404 template.

## configuration

Please follow the Zola documentation for [how to use a
theme](https://www.getzola.org/documentation/themes/installing-and-using-themes/#installing-a-theme).

In `config.toml`, you will find all values for customization that are supported
thus far have documentation explaining how they are used. If there is any confusion or something is not working as intended, [please open an issue](https://github.com/ejmg/zerm/issues)!

## license

MIT. See `LICENSE.md` for more details.
