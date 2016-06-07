# MusicPlayer

MusicPlayer is an open source music player for Windows.


## Features

##### Playlists
* Add songs to a playlist by:
  * Clicking the "Add Song to Playlist" button when a song is selected.
  * Dragging a song, artist, or album and dropping on the desired playlist to add the dragged contents to the playlist.
  * Selecting multiple songs using `CTRL` or `SHIFT` keys, then dragging & dropping on a playlist.

##### Automatic Music Library Updates
* The app's music library updates on startup if a song has been added or deleted from the user's music directory.


## Installation Instructions

1. Download the `MusicPlayer.jar` file from the `releases` directory in the repository.

2. Create a directory in your computer to store the JAR file. When the app runs for the first time, it will create an `img` directory and a `library.xml` file to store song data in the directory where the JAR is located.

3. Run the app by double-clicking the `MusicPlayer.jar` file.

(OPTIONAL)

4. Create a desktop shortcut for `MusicPlayer.jar`.

5. Download `MusicPlayer_Icon.png` from the `releases` directory and set it as the icon for the desktop shortcut.


## Supported File Types

MusicPlayer supports the following file types:
```java
// MP3
case "mp3":
// MP4
case "mp4":
case "m4a":
case "m4p":
case "m4b":
case "m4r":
case "m4v":
// OGG VORBIS
case "ogg":
case "oga":
case "ogx":
case "ogm":
case "spx":
case "opus":
// FLAC
case "flac":
// WAV
case "wav":
case "wave":
// WMA
case "wma":
// REAL
case "ra":
case "ram":
```


## Build

The project was built in eclipse with the following directory structure.

* `lib`: Contains jaudiotagger library

* `releases`: Contains the JAR file for the latest release

* `src`: Contains project source code

* `screenshots`: Contains screenshots used in the README
