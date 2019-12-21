change all `CRLF` to `LF`:

find . -type f -exec dos2unix {} \;
