# Plain Hugo Theme

Modeled after the RFC text files, this is a very bare-bones theme that I use on my site https://xangelo.ca.

It has a very simple mobile layout and auto-swaps between light/dark mode based on user browser preferences. It also supports [utteranc.es](https://utteranc.es/) for comments. That's configurable by supplying valid configuration defined below.

# Screenshots
## Light, Home Page
![Home Page](https://github.com/AngeloR/plain-hugo-theme/blob/master/images/light-home-page.png)

## Light, Single
![Single](https://github.com/AngeloR/plain-hugo-theme/blob/master/images/light-single.png)

## Dark, Home Page
![Home Page](https://github.com/AngeloR/plain-hugo-theme/blob/master/images/dark-home-page.png)

## Dark, Single
![Single](https://github.com/AngeloR/plain-hugo-theme/blob/master/images/dark-single.png)

## Mobile, Single, Light
![Single](https://github.com/AngeloR/plain-hugo-theme/blob/master/images/mobile-light-single.png)

## Supported Parameters

In `config.toml`

```
[params]
subtitle = "Sub title of the site"
favicon = "/<path-to-site-icon>/logo.ico"
githubUrl = "https://github.com/<your-name>/<site-proj-name>/"
referrer = "always"
author = "..."
description = "..."
keywords = "..."
googleSiteVerification = "<google-site-verification-code>"

[params.utterances]
repo = "AngeloR/angelor.github.io"
issue_term="pathname"
label="comment"
theme="preferred-color-scheme"


```
