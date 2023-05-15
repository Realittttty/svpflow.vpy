# svpflow.vpy
一个给mpv用的低配svpflow补帧脚本
### 特点：
1.自适应分辨率，超出显示器分辨率的视频会先缩放到合适的大小，然后再进行补帧，这样可以极大的减少播放高分辨率视频的性能开销
2.自适应倍帧，这部分代码极其的丑陋，但是因为据传倍帧比固定60帧要更流畅，所以我就这么写了
### 注意事项：
1.请将代码中的显示器分辨率（screen_width和screen_height）修改为你自己的显示器分辨率
2.如果你用的是linux，补帧没有生效，请尝试将代码中所有的gpu:1改为gpu:0
### 叠甲（废话）：
我不会python也没深究过mpv、vapoursynth、svpflow，也不会用git和github，是一个纯粹的电脑盲。这个脚本是我在查阅svpflow的官方文档的同时，用windows自带的文本文本写的。我写它的主要目的在于让我的土豆电脑能流畅的补帧，这花费了我不少时间，所以我将我的脚本发出来，希望能减少其它小白的学习成本
