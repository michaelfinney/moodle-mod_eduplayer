Moodle Eduplayer
================

Html5/flash player for both video and audio media with sharing and download capabilities

This module is based on T�nis Tartes's jplayer module
Most of the main fetaures in jplayer are on eduplayer aswell such as
- Html5 player with flash fallback
- Multiple file upload to ensure media compatibility with browsers ( for instance .mp4 files on Firefox/Chromium on Linux )
- Video playback (.mp4, .flv, .webm) 
- Support to Playlists from different sources ( Youtube, rss feed, etc)
- Url video playback ( Youtube, Vimeo )

New main features are 
- Support to audio playback ( mp3, m4a ) with dynamic player layout based on poster image presence
- Share via e-mail a instance-specific url setted by teacher/admins in the activity panel
- Ad instance customizable e-mail share message text with default message in labels
- Ajax email sending to prevent page reload and continue the media playback
- Enable/disable multimedia file download
- Enable/disable an optional disclaimer for copyright purposes triggered on e-mail sending or media download
- Ad instance player skin selector. Upload sikns in /eduplayer/skins/ as pacages or as xml file with base64 encoded images

As a course teacher, you can create, edit and delete eduplayer instances.
This module has been designed on Moodle 2.3.2 and tested on Moodle 2.4.5 and Moodle 2.5.1