# mdview
Script to quickly view local markdown files in a browser. With fallback to
other applications

When the script is run it

1. Generates an HTML from the markdown file
2. Opens the HTML in a browser

If any of those fail, some fallback program is called which displays the raw
file.

You can easily change what program is used to convert and display the file. I
use [mdconv](https://github.com/kevwan/mdconv) and
[surf](https://surf.suckless.org/)

# Usage
```
mdview <options> filename.md
```
Where options can be

* `-v`: Verbose
* `-h`: Help
