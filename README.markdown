 Spotify Now Playing Agent
====================================

This script utilizes Growl diagnostic messages to capture song change notifications and writes the new song metadata to a file in /tmp as well as setting iChat or Adium's status message if they are running.

Installation
-------------

1. Move com.spotify.NowPlayingAgent.plist to ~/Library/LaunchAgents
2. Copy SpotifyNowPlayingAgent to /usr/local/bin/
3. Open Terminal.app
4. Enter the following commands:

> chmod +x /usr/local/bin/SpotifyNowPlayingAgent
> launchctl load -w ~/Library/LaunchAgents/com.spotify.NowPlayingAgent.plist

Credits
---------

* Kaatje Galway
* Nicholas 'drudge' Penree
* [This snippet](http://codesnippets.joyent.com/posts/show/1954)

License
---------

(The MIT License)

Copyright (c) 2010 Nicholas Penree <drudge@conceited.net>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the 'Software'), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

	  