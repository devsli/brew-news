# brew-news

Software exploration tool for [brew](https://github.com/Homebrew/brew/).

When started, it run `brew update` and iterate over new or updated formulae.

## Install

```
$ brew tap devsli/news
```

## Usage

Just run `brew news` to update formulae and see, what was updated.

```
% brew news
[i] - show info; [s] - skip; [h] - visit homepage and continue
[   1 /   5 ] ammonite-repl
```

### Navigation

* Press `i` to show formulae info
* Press `h` to open formulae homepage and go next
* Press `s` to go to the next formulae

[![asciicast](https://asciinema.org/a/1dj119vinorgrbjuxsmvx4nfb.png)](https://asciinema.org/a/1dj119vinorgrbjuxsmvx4nfb)
