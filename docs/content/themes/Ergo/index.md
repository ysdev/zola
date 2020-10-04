
+++
title = "Ergo"
description = "A simple blog Theme focused on writing, inspired by svbtle"
template = "theme.html"
date = 2020-10-03T11:38:17+03:00

[extra]
created = 2020-10-03T11:38:17+03:00
updated = 2020-10-03T11:38:17+03:00
repository = "https://github.com/InsidiousMind/Ergo.git"
homepage = "https://github.com/insipx/Ergo"
minimum_version = "0.4.1"
license = "MIT"
demo = "https://ergo.liquidthink.net"

[extra.author]
name = "Andrew Plaza"
homepage = "https://liquidthink.net"
+++        

[ergo LIVE DEMO](http://ergo.liquidthink.net)



![Ergo Screenshot](https://i.imgur.com/l182IYg.jpg)

A light, simple & beautiful Zola theme made with a focus on writing. Inspired by sbvtle and Pixyll.

Like both those web designs, Ergo is a theme that emphasizes content, but still tries to be stylish. Frankly, the design is
most like sbvtle (http://sbvtle.com) but without the clever svbtle Engine, Javascript, community or kudos button (kudos is on the list of additions, though! But then i'll have to use JS...)
If you find that you like all those things, please check out [svbtle](http://svbtle.com); this theme is meant as a lighter (free) alternative,
and ergo's design will most likely diverge more in the future as this theme evolves with me and it's users (if there are any).
This is not meant as a svbtle clone.


Here's a timelapse:
[![Ergo Creation Timelapse](https://img.youtube.com/vi/ogEjvM-v_-s/0.jpg)](https://www.youtube.com/watch?v=ogEjvM-v_-s)


## Installation
Get [Zola](https://www.getzola.org/) and/or follow their guide on [installing a theme](https://www.getzola.org/documentation/themes/installing-and-using-themes/).
Make sure to add `theme = "ergo"` to your `config.toml`

#### Check zola version (only 0.4.1+)
Just to double-check to make sure you have the right version. It is not supported to use this theme with a version under 0.4.1.

### how to serve
go into your sites directory, and type `zola serve`. You should see your new site at `localhost:1111`.

### Deployment to Github Pages or Netlify
[Zola](https://www.getzola.org) already has great documentation for deploying to [Netlify](https://www.getzola.org/documentation/deployment/netlify/) or [Github Pages](https://www.getzola.org/documentation/deployment/github-pages/). I won't bore you with a regurgitated explanation.

### Customizing the Theme
All colors used on the site are from `sass/colors.scss`. There's only about 5-6 colors total.
Change them however you like! Feel free to go into theme and edit the colors. However, editing anything other than `sass/colors.scss` is strongly advised against. Continue at your own peril!

#### Theme Options
```toml
# Specify a profile picture to use for the logos in the theme. It can be svg, png, jpg, whatever, just make sure to copy the logo you want and put it in img/${YOUR_PROFILE}.*
# and update your config.toml accordingly
profile = 'profile.svg'

# Description. This is needed for SEO/site metadata purposes
description = "Simple blog theme focused on writing, inspired by svbtle"

# website, should not be preceded with `http://`
website = "code.liquidthink.net"

# github
github = "Insipx" # case does not matter
# twitter
twitter = "liquid_think"
# email
email = "${MY_EMAIL}@cool_domain.com"
# instagram
instagram = "${your_insta}"
# keybase
keybase = "${your_keybase}"
# linkedin
linkedin = "${your_linkedin}"
# reddit
reddit = "${your_reddit}"
# youtube
youtube = "${your_youtube_channel_id}"
# if any social networks are missing from this list that you want added, open an issue. I will add it for you ASAP
```

## Features
  - [x] Pagination
  - [ ] Dynamic Color Schemes
  - [ ] Edit Colors in `config.toml`
  - [x] NoJS
  - [ ] Analytics
  - [ ] Comments?
  - [ ] Like button http://kudosplease.com/
  - [ ] categories?
  - [ ] related posts? (would meaningful related posts, or unmeaningful ones, be worth it w/o database?)
  - [ ] user-requested: Open a Issue, or, if you're feeling up to it, a Pull Request

        