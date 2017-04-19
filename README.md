# fromflux/favicon-generator
Bash script to generate range of favicon files from input image

## Installation
* Copy `favicon` to a `PATH` covered directory, for example `~/scripts` and `export PATH="$PATH:~/scripts"`
* Make `favicon` executable: `chmod +x favicon`


## Usage
```
favicon INPUT_IMAGE [OUTPUT_DIRECTORY]
```
`INPUT_IMAGE` The input image for the favicon. Should be a square image at least of size 144x144 pixels.

`OUTPUT_DIRECTORY` The output directory for the generated favicon files. If not provided, the current directory is used

## License
Copyright (c) 2017 Rod Melo

GPL-3.0 (https://opensource.org/licenses/GPL-3.0)
	