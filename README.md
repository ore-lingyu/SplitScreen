# SplitScreen
实现SplitScreen上下分屏拖动互换效果
1、有三个patch
StageCoordinator.patch    ---这个是实现上下分屏拖动互换核心部分
InputMonitorCompat.patch  ---这个是实现上下分屏Input监听
InputChannelCompat.patch  ---这个是实现上下分屏Input监听

2、打patch 在aosp版本 13分支
git apply StageCoordinator.patch
git apply InputMonitorCompat.patch
git apply InputChannelCompat.patch

3、SplitScreen相关知识
https://docs.qq.com/s/LpoRSeeieJcdzEU57-lHta
