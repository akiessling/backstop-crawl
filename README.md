# $ backstop-crawl
[![Stories in Ready](https://badge.waffle.io/fffunction/backstop-crawl.svg?label=ready&title=Ready)](http://waffle.io/fffunction/backstop-crawl) [![Build Status](https://travis-ci.org/fffunction/backstop-crawl.svg?branch=master)](https://travis-ci.org/fffunction/backstop-crawl) [![Coverage Status](https://coveralls.io/repos/github/fffunction/backstop-crawl/badge.svg?branch=master)](https://coveralls.io/github/fffunction/backstop-crawl?branch=master)

> `backstop-crawl` is a tool for automatically generating the `backstop.json` required for `backstop` by crawling a website.

![](http://i.imgur.com/yv57RDo.gif)

## Install

```
$ npm install --global backstop-crawl
```

## Usage

```
$ npm install --global backstop-crawl
```

```
❯ backstop-crawl

  Crawl a site to generate a backstopjs config

  Usage
    $ backstop-crawl <url>

  Options
    --outfile, -o        Save the backstop config to this file
    --ignore-robots      Ignore the sites robots.txt
    --ignore-ssl-errors  Treat any certificate as valid (e.g. self-signed
                          or expired)
    --debug              Logs out errors produced while crawling
    --development-domain Insert the crawled url as reference url, replace the domain with the development domain in the generated json file to run the comparison against that

  Examples
    $ backstop-crawl http://localhost

```


## License

MIT © fffunction [fffunction.co](fffunction.co)
