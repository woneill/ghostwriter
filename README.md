# Ghostwriter

Enhanced port of the Ghost "[ghostwriter](https://github.com/roryg/ghostwriter)" theme to the [Hugo](http://gohugo.io) site generator.

## Example config.toml

```toml
baseurl = "http://example.com/"
title = "mytitle"
theme = "ghostwriter"
languageCode = "en-us"
copyright = "My Name"

[Author]
    name = "My Name"
    profile = "https://google.com/+XXX"

[Taxonomies]
    tag = "tags"

[Params]
    intro = true
    headline = "My headline"
    description = "My description"
    github = "https://github.com/XXX"
    linkedin = "https://linkedin.com/in/XXX/"
    gplus = "https://google.com/+XXX"
    twitter = "https://twitter.com/XXX"
    stackoverflow = "http://stackoverflow.com/users/XXX/YYY"
    ganalytics = "XXX"
    disqus = "XXX"

[Permalinks]
    post = "/:year/:month/:day/:filename/"

[[menu.main]]
    name = "Blog"
    url = "/"
    weight = 1

[[menu.main]]
    name = "Projects"
    url = "/project/"
    weight = 2

[[menu.main]]
    name = "Contact"
    url = "/page/contact/"
    weight = 3

[[menu.main]]
    name = "About"
    url = "/page/about/"
    weight = 4
```