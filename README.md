[![Stand With Ukraine](https://raw.githubusercontent.com/vshymanskyy/StandWithUkraine/main/banner-direct-single.svg)](https://stand-with-ukraine.pp.ua)

# mdbooker

Converts your README.md into a documentation site (via mdbook)

## Demo

[README.md](https://github.com/xonixx/makesure) ➡ [makesure.dev](https://makesure.dev)

## Usage
  
```sh
REPO=username/reponame [BOOK=book_folder_path] awk -f mdbooker.awk README.md
```

then

```sh
mbdook build
```