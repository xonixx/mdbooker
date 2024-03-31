[![Stand With Ukraine](https://raw.githubusercontent.com/vshymanskyy/StandWithUkraine/main/banner-direct-single.svg)](https://stand-with-ukraine.pp.ua)

# mdbooker

Converts your README.md into a documentation site (via [mdBook](https://github.com/rust-lang/mdBook)).

It works by splitting README.md file into multiple .md documents based on title. 
It also generates the SUMMARY.md.

Article: [mdbooker – turn your README.md into a documentation site](https://maximullaris.com/mdbooker.html)

## Demo

[README.md](https://github.com/xonixx/makesure) ➡ [makesure.dev](https://makesure.dev)

## Usage
  
```sh
REPO=username/reponame [BOOK=book_folder_path] awk -f mdbooker.awk README.md
```

then

```sh
mdbook build
```