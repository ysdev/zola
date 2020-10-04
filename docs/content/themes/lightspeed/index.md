
+++
title = "lightspeed"
description = "Zola theme with a perfect Lighthouse score"
template = "theme.html"
date = 2020-10-03T11:38:17+03:00

[extra]
created = 2020-10-03T11:38:17+03:00
updated = 2020-10-03T11:38:17+03:00
repository = "https://github.com/carpetscheme/lightspeed"
homepage = "https://github.com/carpetscheme/lightspeed"
minimum_version = "0.10.0"
license = "MIT"
demo = "https://quirky-perlman-34d0da.netlify.com/"

[extra.author]
name = "El Carpet"
homepage = "https://github.com/carpetscheme"
+++        

# Light Speed

An insanely fast and performance-based Zola theme, ported from [Light Speed Jekyll](https://github.com/bradleytaunt/lightspeed).

Some fun facts about the theme:

* Perfect score on Google's Lighthouse audit
* Only ~600 bytes of CSS
* No JavaScript

Demo: [quirky-perlman-34d0da.netlify.com](https://quirky-perlman-34d0da.netlify.com)

-----

## Contents

- [Installation](#installation)
- [Options](#options)
  - [Title](#title)
  - [Sass](#Sass)
  - [Footer menu](#footer-menu)
  - [Author](#author)
  - [Netlify](#netlify)
- [Original](#original)
- [License](#license)

## Installation
First download this theme to your `themes` directory:

```bash
$ cd themes
$ git clone https://github.com/carpetscheme/lightspeed.git
```
and then enable it in your `config.toml`:

```toml
theme = "lightspeed"
```

Posts should be placed directly in the `content` folder.

To sort the post index by date, enable sort in your index section `content/_index.md`:

```toml
sort_by = "date"
```

## Options

### Title
Set a title and description in the config to appear in the site header:

```toml
title = "Different strokes"
description = "for different folks"

```

### Sass

Styles are compiled from sass and imported inline to the header :zap:

You can overide the styles by enabling sass compilation in the config:

```toml
compile_sass = true
```

...and placing a replacement `style.scss` file in your sass folder.

### Footer-menu
Set a field in `extra` with a key of `footer_links`:

```toml
[extra]

footer_links = [
    {url = "$BASE_URL/about", name = "About"},
    {url = "$BASE_URL/rss.xml", name = "RSS"},
    {url = "https://google.com", name = "Google"},
]
```

If you put `$BASE_URL` in a url, it will automatically be replaced by the actual
site URL.

Create pages such as `$BASE_URL/about` by placing them in a subfolder of the content directory, and specifying the path in the frontmatter:

```toml
path = "about"
```

### Author

To add author name to the head meta-data, set an `author` field in `extra`:

```toml
[extra]

author = "Grant Green"
```

### Netlify

Deployed on netlify? Add a link in the footer by setting `netlify` in `extra` as `true`.

```toml
[extra]

netlify = true
```

## Original
This template is based on the Jekyll template [Light Speed Jekyll](https://github.com/bradleytaunt/lightspeed) by **Bradley Taunt**:

- <https://github.com/bradleytaunt>
- <https://twitter.com/bradtaunt>


## License

Open sourced under the [MIT license](LICENSE.md).

This project is open source except for example articles found in `content`.


        