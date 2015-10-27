# video.js HLS Tech

## 构建
grunt build 取dist目录的文件

## Getting Started
Download [videojs-contrib-media-sources](https://github.com/videojs/videojs-contrib-media-sources/releases) and [videojs-contrib-hls](https://github.com/videojs/videojs-contrib-hls/releases). Include them both in your web page along with video.js:

```html
<video id=example-video width=600 height=300 class="video-js vjs-default-skin" controls>
  <source
     src="https://example.com/index.m3u8"
     type="application/x-mpegURL">
</video>
<script src="video.js"></script>
<script src="videojs-media-sources.js"></script>
<script src="videojs-hls.min.js"></script>
<script>
var player = videojs('example-video');
player.play();
</script>
```

Check out our [live example](http://videojs.github.io/videojs-contrib-hls/) if you're having trouble.

## Documentation
[full documentation](docs/) 