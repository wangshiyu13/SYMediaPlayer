# SYMediaPlayer
[![@wangshiyu13 on weibo](https://img.shields.io/badge/weibo-%40wangshiyu13-blue.svg)](http://weibo.com/2096908353/)
[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg)](LICENSE.md)
[![Latest Stable Version](https://img.shields.io/badge/version-1.1-yellow.svg)](https://github.com/wangshiyu13/SYMediaPlayer/releases)
![Platform](https://img.shields.io/badge/platform-iOS%207%20and%20later-lightgrey.svg)
##### 使用MediaPlayer,AVPlayer制作的媒体播放器，目前已完成视频播放功能

## 使用方法
```
#import "SYVideoPlayer.h"

SYVideoPlayer *videoVC = [SYVideoPlayer player];

[videoVC playWithTarget:(当前视图控制器) viewRect:(视频视图大小) Title:@"视频标题" URL:[NSURL URLWithString:@"视频URL"] videoID:@"视频ID" shareURL:[NSURL URLWithString:@"视频URL"] isStreaming:(Bool值，是否为流媒体) playInFullScreen:(Bool值，默认是否全屏)];

```

###### 全屏
![fullView](https://github.com/wangshiyu13/SYMediaPlayer/blob/master/SYMeidaPlayer/fullView.jpg)
###### 默认
![defaultView](https://github.com/wangshiyu13/SYMediaPlayer/blob/master/SYMeidaPlayer/defaultView.jpg)
