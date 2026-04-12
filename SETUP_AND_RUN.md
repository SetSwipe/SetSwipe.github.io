# SetSwipe: What to Download and How to Run

This repository is a Jekyll site. To run it locally, you do **not** need Expo, Django, or watchOS source from this repo. Those are mentioned in the page copy, but the actual runnable project here is the website itself.

## What you need to download

### Required tools

- **Ruby** compatible with Jekyll 4.3.4
- **Bundler** version `2.5.7` or compatible

### Ruby gems installed by Bundler

These are the direct gems listed in [`Gemfile`](./Gemfile) and locked in [`Gemfile.lock`](./Gemfile.lock):

- `jekyll` `4.3.4`
- `minima` `2.5.2`
- `jekyll-feed` `0.17.0`
- `tzinfo` `2.0.6` on non-Windows platforms, plus `tzinfo-data` on Windows
- `http_parser.rb` `0.8.1` on JRuby only
- `wdm` `0.2.0` on Windows only

Bundler will also download the supporting Jekyll dependencies automatically, including:

- `addressable`
- `colorator`
- `concurrent-ruby`
- `em-websocket`
- `eventmachine`
- `i18n`
- `jekyll-sass-converter`
- `jekyll-watch`
- `kramdown`
- `kramdown-parser-gfm`
- `liquid`
- `listen`
- `mercenary`
- `pathutil`
- `public_suffix`
- `rake`
- `rb-fsevent`
- `rb-inotify`
- `rexml`
- `rouge`
- `safe_yaml`
- `sass-embedded`
- `terminal-table`
- `unicode-display_width`
- `webrick`

### Files already in this repo

You already have the project files needed to build the site:

- [`_config.yml`](./_config.yml)
- [`Gemfile`](./Gemfile)
- [`Gemfile.lock`](./Gemfile.lock)
- [`_layouts/default.html`](./_layouts/default.html)
- [`About.md`](./About.md)
- [`Download.md`](./Download.md)
- [`Team.md`](./Team.md)
- [`Tutorial.md`](./Tutorial.md)
- [`assets/css/style.css`](./assets/css/style.css)
- [`assets/images/setswipe-logo.png`](./assets/images/setswipe-logo.png)
- [`assets/images/setswipe-logo.svg`](./assets/images/setswipe-logo.svg)
- [`assets/images/team-pool.png`](./assets/images/team-pool.png)

## How to run locally

From the repository root:

```bash
bundle install
bundle exec jekyll serve
```

Then open:

```text
http://127.0.0.1:4000/
```

## Notes

- If `bundle install` fails because Ruby is missing, install Ruby first and then rerun it.
- If you want automatic browser refresh while editing, you can also use:

```bash
bundle exec jekyll serve --livereload
```

