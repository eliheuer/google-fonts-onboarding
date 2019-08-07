# Google Fonts Onboarding Manual
This repository contains the source files for the
[Google Fonts Onboarding Manual](https://elih.blog/google-fonts-onboarding).

## Using this Repository
Each section of this manual is a markdownfile in the `src` directory.
The site is built with [mdbook](https://rust-lang-nursery.github.io/mdBook/).

First install `mdbook`:
```
brew install mdbook
```
or
```
cargo install mdbook
```
then from the root directory of this repo run:
```
mdbook build
cp -r book/ docs
```
Then, to view the site locally, run:
```
mdbook serve
```
This serves a book at `http://localhost:3000`, and rebuilds it on changes.

