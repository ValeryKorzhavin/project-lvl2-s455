# Gendiff

[![Maintainability](https://api.codeclimate.com/v1/badges/ae8cd48fc9bd155c41f2/maintainability)](https://codeclimate.com/github/ValeryKorzhavin/project-lvl2-s455/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/ae8cd48fc9bd155c41f2/test_coverage)](https://codeclimate.com/github/ValeryKorzhavin/project-lvl2-s455/test_coverage)
[![Build Status](https://travis-ci.org/ValeryKorzhavin/project-lvl2-s455.svg?branch=master)](https://travis-ci.org/ValeryKorzhavin/project-lvl2-s455)
[![Issue Count](https://codeclimate.com/github/ValeryKorzhavin/project-lvl2-s455/badges/issue_count.svg)](https://codeclimate.com/github/ValeryKorzhavin/project-lvl2-s455)

### Installation
You can install gendiff with npm.
```
npm install --global korzhavin-gendiff
```

### Usage
```
gendiff --format plain before.json after.json
```
### Help
```
gendiff -h

  Usage: gendiff [options] <firstConfig> <secondConfig>

  Compares two configuration files and shows a difference.

  Options:

    -h, --help           output usage information
    -V, --version        output the version number
    -f, --format [type]  Output formats: pretty (by default), plain, json
```
### Expamples
#### Help
[![asciicast](https://asciinema.org/a/L1AeSck0SFxAb6WOCghzuBVVQ.svg)](https://asciinema.org/a/L1AeSck0SFxAb6WOCghzuBVVQ)
#### JSON files difference
[![asciicast](https://asciinema.org/a/iwwZy4V5LJ1hKj7VsAekMtUlL.svg)](https://asciinema.org/a/iwwZy4V5LJ1hKj7VsAekMtUlL)
#### Yaml files difference
[![asciicast](https://asciinema.org/a/Z7OpLg8CoEWHSdWd7CCCYBy9y.svg)](https://asciinema.org/a/Z7OpLg8CoEWHSdWd7CCCYBy9y)
#### Ini files difference
[![asciicast](https://asciinema.org/a/ZscVxdpzxMLt5phtUyA8hSoNS.svg)](https://asciinema.org/a/ZscVxdpzxMLt5phtUyA8hSoNS)
#### Nested  json files difference
[![asciicast](https://asciinema.org/a/EFSOwHey8fKNQaFr5gsMSkKKJ.svg)](https://asciinema.org/a/EFSOwHey8fKNQaFr5gsMSkKKJ)
#### Nested json files difference plain format
[![asciicast](https://asciinema.org/a/WbiwbuYFY9Wejm7T3NZ8SHIGG.svg)](https://asciinema.org/a/WbiwbuYFY9Wejm7T3NZ8SHIGG)
#### Nested json files difference json format
[![asciicast](https://asciinema.org/a/C0XPxujRIYllumbfMMlS8vwfX.svg)](https://asciinema.org/a/C0XPxujRIYllumbfMMlS8vwfX)