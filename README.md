# urldencoder.py

URL Decoder/Encoder does the task as the name suggests

## Usage

    urldencoder -e "http://github.com/santosh"

will return `http%3A%2F%2Fgithub.com%2Fsantosh` and

    urldencoder -d "http%3A%2F%2Fgithub.com%2Fsantosh"

will return `http://github.com/santosh`

Multiple URLs can also be passed.