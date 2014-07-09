2048x
=====

2048游戏学习版


- 1.创建工程

cocos new "2048" -p com.sinory.x2048x -l cpp -d /Users/sinory/Documents/Android 



FAQ：
- 1.expected class name 
include 的.h不对
- 2.libpng warning: iCCP: known incorrect sRGB profile
http://stackoverflow.com/questions/20139335/cocos2d-x-background-image-is-not-displaying-properly
- 3.ipone中横竖屏问题
http://my.oschina.net/minglic/blog/151914
- 4.cocos run -p android  ——ANT_ROOT not defined. Please define it in your environment
http://www.cocos2d-x.org/docs/manual/framework/html5/v2/cocos-console/en

安卓环境配置：http://stackoverflow.com/questions/23675436/set-ndk-module-path-for-cocos2d-x
- 5.cocos2d undefined reference to 'AppDelegate::AppDelegate()  cocos run -p android
在proj.android/jni/Anroid.mk 中添加需要编译的cpp
