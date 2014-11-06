bookmarker-json
===============

# Nifty tool that converts Chrome-exported bookmarks to a JSON file

## Basic usage:

```
$ ./node bookmarker.js -f bookmarks.html -o output.json
```

## Alternatively use STDIN and STDOUT to parse data:
```
$ cat bookmarks.html | node ./bookmarker.js > output.json
```
