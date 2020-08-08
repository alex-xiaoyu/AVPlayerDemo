# AVPlayerDemo

#import "XYAVPlayerView.h"
XYAVPlayerView *playerView = [[XYAVPlayerView alloc] initWithFrame:CGRectMake(0, 100, self.view.bounds.size.width, self.view.bounds.size.width/7 *4)];

NSString *url = @"https://mp4.vjshi.com/2017-07-02/0cbbf21c6003f7936f4086dd10e7ebf5.mp4";

[playerView settingPlayerItemWithUrl:[NSURL URLWithString:url]];

三行代码即可使用
可自定义View
基本都有注释

基于AVPlayer的视频播放器
支持本地跟网络视频

本地视频暂时没有第一帧图片
目前只测试过MP4格式
进度条的滑动跟点击会有冲突



