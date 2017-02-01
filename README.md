## boosta

#### Easy bookmark management with rofi

### Features

- Browser independent
- Store your bookmarks in a simple textfile, which can be easily tracked with git
- Use rofi as a convenient interface to search, open and manage bookmarks
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

Run *boosta*, then you can switch between the following modes:

* `Alt+o` **open bookmark** (default mode)
  * start to type a tag, a title or an url and press `Enter` when you found the bookmark to open.
* `Alt+n` **add bookmark**
  * You need to provide tag(s), title and url for a new bookmark.
  * For each of tags, title and url, you can also select from the existing ones.
  * The title of the previous window (probably the browser window) is inserted as the default value for the title.
  * You might want to copy the url to the clipboard before running boosta and insert it then with `Shift+Insert`.
  * Press `Ctrl+Enter` to use the entered text and not the selected entry as input.

### License

This software is released under the terms of the
GNU General Public License v2:

[http://www.gnu.org/licenses/old-licenses/gpl-2.0.txt](http://www.gnu.org/licenses/old-licenses/gpl-2.0.txt)

### TODO
- change delimiter
- edit and delete bookmark
- generate a html file of the bookmarks
