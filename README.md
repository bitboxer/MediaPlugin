# MediaPlugin

This plugin controls your player using the
[MPRIS](https://specifications.freedesktop.org/mpris-spec/latest/) interface.
It will let you play/pause the current playing item and start the previous/next
track using the [StreamController](https://github.com/StreamController/StreamController).

This is a fork of [MediaPlugin](https://github.com/StreamController/MediaPlugin).

## Actions

- **Play** - Starts media playback if the player is not currently playing.
- **Pause** - Pauses media playback if the player is currently playing.
- **PlayPause** - Toggles between play and pause states based on the current
  playback status.
- **Next** - Skips to the next track in the media queue.
- **Previous** - Returns to the previous track in the media queue.
- **Info** - Displays the current media title and artist information with and
  optional separator.
- **ThumbnailBackground** - Sets the current media thumbnail as the deck
  background image.

## Installation

- Open Settings
- Navigate to "Store"
- Enable "Custom Plugins"
- Add `https://github.com/bitboxer/MediaPlugin` as Repository URL and `main` as branch
- Open Store
- Search for "MediaEnhanced"
- Install
- Enjoy

## FAQ

### The album artwork is not on the play/pause button

- If you add the play/pause as action on a button, you also need to allow it
  to control the media. In the "Actions" you see 3 Buttons area before the
  `Play/Pause`. The first one is an image. Activate it.
- If you installed the app inside of FlatPack, you might need to increase the
  permission of the app using [FlatSeal](https://flathub.org/en/apps/com.github.tchx84.Flatseal).
  Open it there and add the folder `~/.var/app/` under "Filesystem".
  Now it should be able to load the images of other applications.
