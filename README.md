# ttf website

## Copyright 

Theme ttf-hugo-future-imperfect is MIT LIcensed, and based on https://github.com/jpescador/hugo-future-imperfect - thanks jpescador!

All other content is copyright 2018, Shambhala USA.

## Commands

### Production


Build

```sh
hugo --noTimes
```

Deploy

```sh
firebase deploy
```

### Staging

Building for generic Firebase

```
hugo --noTimes -b "https://ttf-website.firebaseapp.com"
```

### Development

Setting up a new dev environment for firebase (I think)

```sh
firebase use --add ttf-website
```

Running locally on my Chromebook (in Termux and visible to the ChromeOS browser)

```sh
hugo server -b http://100.115.92.2:1313 --bind 100.115.92.2
```

Building locally on my Chromebook, so it can just be read as a file

```
hugo --noTimes -b "file:///home/chronos/u-01a80db448373b460d79ab9a9c7948c8ca94ba35/Downloads/ttf/appernetic-hugo-project/public/"
```
