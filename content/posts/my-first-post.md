+++
title = 'Embed audio Plyr in Hugo'
date = 2024-05-01T21:26:45+02:00
draft = false
+++

I recently found a [blog post](https://roneo.org/en/hugo-audio-player-embed-remote-media-files-plyr-shortcode/) which explains how to embed audio files with Plyr.io and a Shortcode in Hugo.

I implemented [hls.js](https://github.com/video-dev/hls.js/) on top of it. 

So here's the result: it plays the public german channel SWR3 using its HLS stream. You can rewind the live footage up to 2 hours.

{{< audio "https://swr3hlsaudio.akamaized.net/hls/live/2109007/swr3/master.m3u8" >}}
