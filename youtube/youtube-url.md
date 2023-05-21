# YouTube URL Regex

## About
The following regex expression will identify the current YouTube url formats, including the video id. The regex expression will identify all current YouTube URLs.

## Use Cases
  1. Validating that a url is a YouTube url
  2. Finding a YouTube url in a string so the video ID can be extracted from it.

## Regex Code
/https?:\/\/.*?((m\.)|(www\.))?((youtube(\-nocookie)?\.com)|(youtu\.be))\/((.*watch%3Fv%3D)|(((watch\?.*v(=|%3D))|((e\/)|(v\/)))?|(embed\/)))[a-zA-Z0-9_\-]{11}/

## Current YouTube URL Formats Identified
http://www.youtube.com/watch?v=NSU23_C3fiw

http://www.youtube.com/watch?v=NSU23_C3fiw&feature=em-uploademail

http://www.youtube.com/watch?v=NSU23_C3fiw&feature=feedrec_grec_index

http://www.youtube.com/watch?v=NSU23_C3fiw#t=0m10s

http://www.youtube.com/watch?v=NSU23_C3fiw&feature=channel

http://www.youtube.com/watch?v=NSU23_C3fiw&playnext_from=TL&videos=osPknwzXEas&feature=sub

http://www.youtube.com/watch?v=NSU23_C3fiw&feature=youtu.be

http://www.youtube.com/watch?v=NSU23_C3fiw&feature=youtube_gdata_player

http://www.youtube.com/watch?v=NSU23_C3fiw&list=PLGup6kBfcU7Le5laEaCLgTKtlDcxMqGxZ&index=106&shuffle=2655

http://www.youtube.com/watch?feature=player_embedded&v=NSU23_C3fiw

http://www.youtube.com/watch?app=desktop&v=NSU23_C3fiw

http://www.youtube.com/v/NSU23_C3fiw

http://www.youtube.com/v/NSU23_C3fiw?version=3&autohide=1

http://www.youtube.com/v/NSU23_C3fiw?fs=1&hl=en_US&rel=0

http://www.youtube.com/v/NSU23_C3fiw?feature=youtube_gdata_player

http://youtu.be/NSU23_C3fiw

http://youtu.be/NSU23_C3fiw?feature=youtube_gdata_player

http://youtu.be/NSU23_C3fiw?list=PLToa5JuFMsXTNkrLJbRlB--76IAOjRM9b

http://youtu.be/NSU23_C3fiw&feature=channel

http://youtu.be/NSU23_C3fiw?t=1

http://www.youtube.com/oembed?url=http%3A//www.youtube.com/watch?v%3DNSU23_C3fiw&format=json

http://www.youtube.com/attribution_link?a=JdfC0C9V6ZI&u=%2Fwatch%3Fv%3DNSU23_C3fiw%26feature%3Dshare

http://www.youtube.com/attribution_link?a=8g8kPrPIi-ecwIsS&u=/watch%3Fv%3DNSU23_C3fiw%26feature%3Dem-uploademail

http://www.youtube.com/embed/NSU23_C3fiw

http://www.youtube.com/embed/NSU23_C3fiw?rel=0

http://www.youtube-nocookie.com/embed/NSU23_C3fiw?rel=0

http://www.youtube.com/e/NSU23_C3fiw
