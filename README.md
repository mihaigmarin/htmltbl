# htmltbl
A html table parser for the terminal.

## Installation
### From source
With go install(Go 1.18 or higher required):

    go install github.com/mihaigmarin/htmltbl@latest

Or building from repository:

    git clone http://github.com/mihaigmarin/htmltbl
    cd htmltbl
    go build

## Usage
You must specify a http link and optionally the format(table, json)

    htmltbl --format table <url>
    htmltbl --format json <url>
    htmltbl --format json-indent <url>

To use simulate GET method created by a real browser run with:

    htmltbl --simulate-browser <url>
    htmltbl --format json --simulate-browser <url>
    htmltbl --format json-indent --simulate-browser <url>

## License
[MIT](https://github.com/mihaigmarin/htmltbl/raw/main/LICENSE)
