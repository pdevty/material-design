# Material-Design

Material-Design is a material design theme for [Hugo](http://gohugo.io/).

## Features

- Material Design
- Google Analytics
- Pagination
- Disqus
- Social links (Twitter, Facebook, GitHub)
- Tags
- Categories
- Highlighting source code

## Installation

```shell
$ mkdir themes
$ cd themes
$ git clone https://github.com/pdevty/material-design
```

## Configuration

`config.toml`

```toml
theme="material-design"
baseurl = "Your Site URL"
languageCode = "en-us"
title = "Your Site Title"
MetaDataFormat = "toml"
paginate = 9
disqusShortname = "Your Disqus Name"
copyright = "© 2015 Copyright Text"

[params]
  description = "Your Site Description"
  twitter = "Your Twitter Name"
  github = "Your Github Name"
  facebook = "Your facebook Name"
  headerCover = "images/default.png"
  footerCover = "images/default.png"
  googleAnalyticsUserID = "Your Analytics User Id"
```

## Usage

```shell
$ hugo server -t material-design -w -D
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request