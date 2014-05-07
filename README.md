开源的Android视频播放器
之前尝试自己解码视频，然后播放显示，虽然音视频都可以播放，但是实现不了音视频的同步，所以使用第三方的视频库Vitamio来实现视频播放器功能，这样自己只需要实现播放解码的制作不不要关心底层解码和显示问题。是使用Vitamio 4.0，制作的视频播放器，后续会继续添加直播，网络播放功能。实现的主要功能：
1.搜索本地视频文件
2.使用ListView显示本地视频的缩略图，文件名称，播放时间
3.播放视频的格式可以支持大多数，Vitamio使用的解码库是ffmpeg，所以可以支持很多
4.支持手势调节声音，亮度(在左边上下滑动调节亮度，在右边滑动调节音量，主要扣取OPlayer里面的)
5.支持播放，暂停，快进和快退(界面也是扣取Oplayer里面的)
6.支持字母滑动搜索文件(主要扣取OPlayer里面的)
开源地址：https://github.com/jwzhangjie/JwZhangJie.git 自己克隆就可以了，不过要是用必须到官网下载Vitamio的自身的库，VitamioBundle，ZI，不然不能运行
