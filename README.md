Materi
===
This theme was created based on [Materi for jekyll](https://github.com/ogaclejapan/materi-for-jekyll).

## Features
- Responsive design
- Google Analytics

### Installation
```sh
cd path/to/hugo
git submodule add https://github.com/ress997/hugo-materi themes/materi
```

## `config.toml` example
```toml
baseurl = "https://example.com/"
title = "SiteTitle"
theme = "materi"

googleAnalytics = "UA-XXXXXXXX-XX" # Optional
disqusShortname = "XYW" # Optional

[params]
description = "This is site description"
dateformat = "Jan 2, 2006" # Optional

[params.author]
name = "John Doe"
thumbnail = "img/author.png"
description = "This is author description."

mastodon = "https://mastodon.social/@mastodon"
twitter = "twitter"
facebook = "XXXX"
github = "github"
```