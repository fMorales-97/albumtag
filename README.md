# Albumtag
A POSIX complaint shell script to write metadata to your albums.

## ¿How does it work?
First you have to obtain the album, to do this you have to use yt-dlp (or youtube-dl) and download a playlist. This reason to use a playlist of Youtube is because when an artist release an album, its record label distributes it in different platforms like Spotify, Itunes, Apple Music, etc. One of these platforms is Youtube and it uploads the album in the form of an auto-generated playlist, in other words, **you can find pretty much every album officially in youtube through playlists.**

After downloading the album the script orders the songs according to the track list of the album and renames each one to add a number prefix, then it gives a prompt to the user to write the metadata and applies it to the songs, in order to do this the songs have to have the opus format. This is already done when you use yt-dlp, but if you use youtube-dl you have to convert them to opus, the convertion process is handled by the script when you comment and uncomment some parts of the script which are mentioned in the script itself.

## Usage
You start by choosing the album, in this case it'll be Michael Jackson's Thriller.

![Michael Jackson's Thriller playlist] (https://imgur.com/a/1LirgQS)
If you want to make sure that you'll be downloading the official album, make sure you choose the playlist whose thumbnail has colored bars at the sides of the album cover.
