## boosta

#### Easy bookmark management

### Features

- Browser independent
- Store your bookmarks in a simple textfile
- Manage your bookmarks with a simple script
- Use rofi to search and open bookmarks in your browser
- Convert your bookmarks.html file exported from Firefox to a boosta bookmarks file

### Requirements

boosta has the following requirements:

- Python 2 or 3 (for the convertFirefox2Boosta script)
- rofi

### Usage

To convert your *bookmarks.html* file exported from Firefox to a boosta
bookmarks file, run:

    convertFirefox2Boosta

The boosta bookmarks file will be created as *bookmarks*. Copy it to *$HOME/.config/boosta/bookmarks* to use it with boosta.

Copy the *config.sample* file to *$HOME/.config/boosta/config* and customize it as you like.

To select a bookmark and open it in your browser, run:

    boosta

### License

This software is released under the terms of the
GNU General Public License v2:

[http://www.gnu.org/licenses/old-licenses/gpl-2.0.txt](http://www.gnu.org/licenses/old-licenses/gpl-2.0.txt)

### TODO
- change delimiter
- add, edit and delete bookmark
- generate a html file of the bookmarks
