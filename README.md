# whichtime

[![License: GPL-3.0](https://img.shields.io/github/license/teoc98/whichtime)](https://opensource.org/licenses/GPL-3.0)

A tool to open [whichtime.com](http://www.whichtime.com) calendars with a single command. Particularly useful on Linux and MacOS systems. 

## Installation

- Make sure [Python 3](https://www.python.org/) is installed
- Download (and if necessary decompress) the [Adobe Flash Player standalone player](https://www.adobe.com/support/flashplayer/debug_downloads.html)
- Symlink (or rename) the executable file to `flashplayer` and place it in a directory which is in your system `$PATH` 
- Clone with `git clone https://github.com/teoc98/whichtime`
- Install requirements with `pip3 install -r requirements.txt`; if `pip3` is not found, install with `python3 -m pip install -r requirements.txt`

### Dependencies

- [Adobe Flash Player standalone player](https://www.adobe.com/support/flashplayer/debug_downloads.html)
- [Python 3](https://www.python.org/)
- [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/)
- [lxml](https://lxml.de/)
- [Requests](https://docs.python-requests.org/)

## Usage

`./whichtime <USER> <PASSWORD>`

Alternatively, you can set user and password by setting the variables `USER` and `PASS` in the script. 

## License

Released under [GNU General Public License version 3](https://github.com/teoc98/whichtime/blob/master/LICENSE).
