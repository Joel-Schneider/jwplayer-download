jwplayer-download
=================

Quick script written to download a JWPlayer's media to play locally

(C) Joel Schneider 17th November 2017

License
=======
ISC

How to use
==========

You obviously need permission to do this! Copyright etc.

How to find the URL
===================

1. Open the page in firefox
2. Right click->inspect (Q)
3. Find "Part x" where x is the number of this part, until you get
	a section with "<script> ... https://...m3u8... rtsp... etc.
4. Copy inner HTML to a blank document
5. Now copy the "URL" beginning https:// as $URL
6. $0 $URL [optional-save-location.mp4]

Notes
=====

NB you can use VLC to stream/convert/save, but it's quite a lot slower,
and uses more %CPU by far!
