## 1.1.1

* Format file (to pass static analysis)

## 1.1.0

* Update ffmpeg_kit_flutter to 4.5.1-LTS
* Update other plugin versions
* Update Readme

## 1.0.0

* **BREAKING CHANGE:** Migrate to [FFmpegKit for Flutter](https://pub.dev/packages/ffmpeg_kit_flutter).
  `saveTrimmedVideo()` method is not async now, you'll need to use the callback `onSave: (outputPath) {}` to get the trimmed video output path.
* Add playback timestamp in the `showDuration`
* Simply configuration
* Update the plugin versions
* Update Docs

## 0.6.0

* Update the plugin versions
* Using flutter_lints

## 0.5.4

* Update Docs

## 0.5.3

* Add `borderWidth` and `scrubberWidth` properties under `TrimEditor` widget
* Fix padding and border decoration of `VideoViewer`
* Update the plugin versions

## 0.5.2

* Fix iOS error while loading thumbnails in `TrimEditor`
* Remove an unused dependency
* Update packages

## 0.5.1

* Update the example in Readme
* Update the plugin versions

## 0.5.0

* Global refactoring, example is now a standalone screen
* Fixed the staggering issue when dragging the frame
* The whole frame can now be dragged in addition to the sides
* Updated packages
* Updated the example

## 0.4.0

* Migrate to null safety
* Fix video thumbnail loading issues
* Bump up all dependencies
* Upgrade example

## 0.3.5

* Update example app (small bug fixes)
* Update to latest plugin versions

## 0.3.4

* Fixed the issue with video getting struck for a few initial frames during playback

## 0.3.3

* Updated plugin versions

## 0.3.2

* Minor changes

## 0.3.1

* Improve the file structure of the package
* Now, you just have to import one file for using the package

## 0.3.0

* Update the plugin versions
* Update example app (now includes how to retrieve the trimmed video)
* Update Readme
* Fixes some memory leak issues

## 0.2.7

* Add a new property called `maxVideoLength` for specifying the max length of the output video.
* Update Docs

## 0.2.6

* Add a new property called `fit` to `TrimEditor` widget which will let you specify the image fit type of each thumbnail image.
* Add a new property to `saveTrimmedVideo()` method called `applyVideoEncoding` which will let you specify whether to re-encode the trimmed video. 
  
  **NOTE:** Applying this will take significantly greater amount of time to process the output video.

* Improve Docs

## 0.2.5

* Update Docs
* Reverted the FFmpeg trimmed video start & end position to **milliseconds** (earlier it was changed to **seconds** in `v0.2.4` to fix video freezing, but after testing it was found that the issue still persists)

## 0.2.4

* Fix output video freezing during start and end
* Update the example app to use LTS version of FFmpeg (for wider device support)
* Update Readme

## 0.2.3

* Fix issue with path returned

## 0.2.2

* Change implementation of the `saveTrimmedVideo()` method
* `saveTrimmedVideo()` now returns the output video path
* Update Docs

## 0.2.1

* Fix over-scrolling && scroll-over issue

## 0.2.0

* BREAKING CHANGE: `loadVideo()` method implementation changed.
  Now, you can pass the video file to the method.
* Fix issue related to animation controller improperly disposing
* Update Docs

## 0.1.5

* Fix for paths having white spaces

## 0.1.4

* Smoothen the scrubber animation

## 0.1.3

* Code improvements
* Update Readme

## 0.1.2

* Changed `StorageDir` format naming
* Update documentation

## 0.1.1

* Correct documentation

## 0.1.0

* Initial Open Source release
