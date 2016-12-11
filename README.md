# Emacs Packages

[Emacs Packages](https://elpa.emacs-china.org/packages/) collects Emacs packages
from many Emacs Lisp Package Archives, currently they are:

- [GNU ELPA](https://elpa.gnu.org/)
- [MELPA](https://melpa.org/)
- [MELPA Stable](https://stable.melpa.org/)
- [Marmalade](https://stable.melpa.org/)
- [Org ELPA](http://orgmode.org/elpa.html)
- [Sunrise Commander ELPA](http://joseito.republika.pl/sunrise-commander/)
- [User42 ELPA](http://user42.tuxfamily.org/elpa/index.html)

## Build

Make sure that you have [Nanoc](http://nanoc.ws/) gem installed, then simply run

    nanoc

## Deploy

[![Build Status](https://travis-ci.org/emacs-china/packages.svg?branch=master)](https://travis-ci.org/emacs-china/packages)

Travis-CI builds and deploys the site daily by
using [Cron Jobs - Travis CI](https://docs.travis-ci.com/user/cron-jobs/). And
update on the master branch also triggers the update.

Thanks Travis-CI.
