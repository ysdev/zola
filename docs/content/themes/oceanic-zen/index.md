
+++
title = "Oceanic Zen"
description = "Minimalistic blog theme"
template = "theme.html"
date = 2020-10-03T11:38:17+03:00

[extra]
created = 2020-10-03T11:38:17+03:00
updated = 2020-10-03T11:38:17+03:00
repository = "https://github.com/barlog-m/oceanic-zen.git"
homepage = "https://github.com/barlog-m/oceanic-zen"
minimum_version = "0.9.0"
license = "MIT"
demo = ""

[extra.author]
name = "Barlog M."
homepage = "https://barlog.li"
+++        

# Oceanic Zen

[![Netlify Status](https://api.netlify.com/api/v1/badges/e90897e9-f3e3-4906-b647-11a918af3a3b/deploy-status)](https://app.netlify.com/sites/oceanic-zen/deploys)

Oceanic Zen is a theme for [Zola](https://www.getzola.org/) static site generator

[Oceanic Zen](https://oceanic-zen.netlify.app/) is a minimalistic theme for personal blog.

![Screenshot](screenshot-index.png)
![Screenshot](screenshot.png)

## Installation

Download theme to your `themes` directory:

```bash
$ cd themes
$ git clone https://github.com/barlog-m/oceanic-zen.git
```

Or add as git submodule

```bash
$ git submodule add https://github.com/barlog-m/oceanic-zen.git themes/oceanic-zen
```

Enable it in your `config.toml`:

```toml
theme = "oceanic-zen"
```

## Options

Theme supported some extra options

```toml
[extra]
author = "blog author name"
github = "github author name"
twitter = "twitter author name"
```

Font [Iosevka](https://typeof.net/Iosevka/)

        