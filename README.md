# Spotify Application Client for MacOSX
Node Client for the Spotify App on Mac OSX

## Overview
Spotify built an [AppleScript API](https://developer.spotify.com/applescript-api/) that enables programmatic control of the player (on Mac OSX).

This client sits on top of this AppleScript API to provide a simple abstraction layer.

### API
All methods return a `Promise`

#### `isSpotifyRunning`
#### `getSongName`
#### `getAlbumName`
#### `getArtistName`
#### `getPlayerState`
#### `getPlayerPositionInSeconds`
#### `getTrackDurationInSeconds`
#### `turnOffRepeat`
#### `turnOnRepeat`
#### `isRepeating`
#### `toggleRepeat`
#### `turnOffShuffle`
#### `turnOnShuffle`
#### `isShuffling`
#### `toggleShuffle`
#### `togglePlayPause`
#### `play`
#### `pause`
#### `playNextTrack`
#### `playPreviousTrack`