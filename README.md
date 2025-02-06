<hr>
<p align="center"><img src="assets/logo.png" width="346"></p> 
<h2 align="center"><b>PipePipe</b></h2>
<h4 align="center">
NewPipe, reimagined: faster, more stable, and packed with more features.</h4>
<p align="center"><a href="https://f-droid.org/packages/InfinityLoop1309.NewPipeEnhanced/"><img src="https://fdroid.gitlab.io/artwork/badge/get-it-on.png" alt="Get it on F-Droid" height=80/></a>
<a href="https://apt.izzysoft.de/fdroid/index/apk/InfinityLoop1309.NewPipeEnhanced"><img src="assets/IzzyOnDroid.png" alt="Get it on IzzyOnDroid" height=80/></a></p>
<hr>

## Features

### Beyond NewPipe

* SponsorBlock (YouTube & BiliBili)
* ReturnYouTubeDislike
* Bullet comments / Live Chats
* Search filters
* Search & sort in local playlists
* Filter out unwanted items by keywords/channels/...
* Music player mode & Background playing
* Sleep timer
* Fullscreen gestures
* Login to watch restricted / premium contents
* ... and many minor improvements

### Origin

* Watch videos at resolutions up to 8K
* Listen to audio in the background, only loading the audio stream to save data
* Popup mode (floating player, aka Picture-in-Picture)
* Watch live streams
* Show/hide subtitles/closed captions
* Search videos and audios (on YouTube, you can specify the content language as well)
* Enqueue videos (and optionally save them as local playlists)
* Show/hide general information about videos (such as description and tags)
* Show/hide next/related videos
* Show/hide comments
* Search videos, audios, channels, playlists and albums
* Browse videos and audios within a channel
* Subscribe to channels (yes, without logging into any account!)
* Get notifications about new videos from channels you're subscribed to
* Create and edit channel groups (for easier browsing and management)
* Browse video feeds generated from your channel groups
* View and search your watch history
* Search and watch playlists (these are remote playlists, which means they're fetched from the service you're browsing)
* Create and edit local playlists (these are created and saved within the app, and have nothing to do with any service)
* Download videos/audios/subtitles (closed captions)

## Screenshots

[<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/00-v2.png" width=640>](fastlane/metadata/android/en-US/images/phoneScreenshots/00-v1.png)

[<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/01-v3.png" width=160>](fastlane/metadata/android/en-US/images/phoneScreenshots/01-v3.png)
[<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/02-v3.png" width=160>](fastlane/metadata/android/en-US/images/phoneScreenshots/02-v3.png)
[<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/03-v3.png" width=160>](fastlane/metadata/android/en-US/images/phoneScreenshots/03-v3.png)
[<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/04-v3.png" width=160>](fastlane/metadata/android/en-US/images/phoneScreenshots/04-v3.png)
<br/>
[<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/05-v3.png" width=160>](fastlane/metadata/android/en-US/images/phoneScreenshots/05-v3.png)
[<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/06-v3.png" width=160>](fastlane/metadata/android/en-US/images/phoneScreenshots/06-v3.png)
[<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/07-v3.png" width=160>](fastlane/metadata/android/en-US/images/phoneScreenshots/07-v3.png)
[<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/08-v3.png" width=160>](fastlane/metadata/android/en-US/images/phoneScreenshots/08-v3.png)
<br/>
[<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/09-v3.png" width=160>](fastlane/metadata/android/en-US/images/phoneScreenshots/09-v3.png)
[<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/10-v3.png" width=160>](fastlane/metadata/android/en-US/images/phoneScreenshots/10-v3.png)
[<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/11-v3.png" width=160>](fastlane/metadata/android/en-US/images/phoneScreenshots/11-v3.png)
[<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/12-v3.png" width=160>](fastlane/metadata/android/en-US/images/phoneScreenshots/12-v3.png)


## About this fork

Due to differences in development philosophy, I forked NewPipe in early 2022 and began independent development based on it.

This means that PipePipe neither receives updates from NewPipe nor pushes updates to NewPipe. They have become two separate projects. Issues that occur in NewPipe don't necessarily happen in PipePipe, and changes made in NewPipe may not be adopted by PipePipe. In contrast, forks like Tubular track the latest version of NewPipe and develop based on it.

Making a hard fork allows us to effectively address issues with quick fixes and maintain frequent feature updates.

## About sign in

PipePipe will ONLY use the login cookie for the specified scenarios you set. You can configure it in "Cookie Functions."

For YouTube, the cookie will only be used when retrieving playback streams.

## Contribute

Issues and PRs are welcomed. Please note that I will **NOT** accept service requests. 

Anyone interested in creating their own service is encouraged to fork this repository.

## About Latest Build

Sometimes, for a known issue, PipePipe may already have a fix in place, but a new version has not yet been officially released. In such cases, you can check the continuous integration (CI) system to obtain the latest build. This allows you to access the most recent updates and fixes before they are included in the next official release. 

Check https://github.com/InfinityLoop1308/PipePipe/actions/workflows/ci.yml , select the latest, and download the debug apk.


## Donation

If you find PipePipe useful, please consider becoming a supporter on Ko-Fi. Your support is important to me and helps me add more exciting new features. Every bit counts! 😇

Liberapay: https://liberapay.com/PipePipe

Ko-fi: https://ko-fi.com/pipepipe

## Special Thanks

[SocialSisterYi/bilibili-API-collect](https://github.com/SocialSisterYi/bilibili-API-collect) for providing some BiliBili API lists.

[AioiLight](https://github.com/AioiLight) for providing some code of NicoNico service.
