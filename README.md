Idle Master (Linux Python branch)
===========

This program will determine which of your Steam games still have Steam Trading Card drops remaining, and will go through each application to simulate you being “in-game” so that cards will drop. It will check periodically to see if the game you’re idling has card drops remaining. When only one drop remains, it will start checking more frequently. When the game you’re idling has no more cards, it’ll move on to the next game. When no more cards are available, the program will terminate.

Requirements
-------

This application requires Steam to be open and for you to be logged in.

The script needs these Python 2 packages to run:
- requests
- beautifulsoup4
- colorama
- gtk2
- notify

Examples for packages that meet the dependencies:
- Ubuntu: python-bs4 python-requests python-colorama python-gtk2 python-notify
- Arch Linux: python2-beautifulsoup4 python2-requests python2-colorama pygtk python2-notify

Run the Python script directly using the command "python2 start.py".

Setup
-------

Please read the included Setup Instructions.pdf file for detailed setup instructions and frequently asked questions.

Authors
-------

jshackles and Stumpokapow

License
-------

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation. A copy of the GNU General Public License can be found at http://www.gnu.org/licenses/. For your convenience, a copy of this license is included.
