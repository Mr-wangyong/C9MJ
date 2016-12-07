# C9MJ
该项目是本人为熟悉开发流程而设，不得用于商业用途。包含新闻浏览与视频直播（仍在开发中）

##基本架构
MVP+Glide+Retrofit+RxJava2
###本项目所用开源库如下
    compile 'com.android.support:appcompat-v7:25.0.0'
    compile 'com.android.support:support-v4:25.0.0'
    compile 'com.android.support:design:25.0.0'
    compile 'com.android.support:cardview-v7:25.0.0'
    compile 'com.android.support:recyclerview-v7:25.0.0'
    //butterknife
    compile 'com.jakewharton:butterknife:8.4.0'
    annotationProcessor 'com.jakewharton:butterknife-compiler:8.4.0'
    //glide
    compile 'com.github.bumptech.glide:glide:3.7.0'
    compile 'jp.wasabeef:glide-transformations:2.0.1'
    //RxJava2 + Retrofit
    compile 'com.google.code.gson:gson:2.7'
    compile 'com.squareup.retrofit2:retrofit:2.1.0'
    compile 'com.squareup.retrofit2:converter-gson:2.1.0'
    compile 'com.jakewharton.retrofit:retrofit2-rxjava2-adapter:1.0.0'
    compile 'io.reactivex.rxjava2:rxjava:2.0.2'
    compile 'io.reactivex.rxjava2:rxandroid:2.0.1'
    //Fragment库
    compile 'me.yokeyword:fragmentation:0.8.0'
    compile 'me.yokeyword:fragmentation-swipeback:0.7.9'
    //photoview
    compile 'com.github.chrisbanes:PhotoView:1.3.1'
    //RecyclerView Adapter库
    compile 'com.github.CymChad:BaseRecyclerViewAdapterHelper:2.4.7'
    //Tab指示器
    compile 'com.github.hackware1993:MagicIndicator:1.4.2'
    //工具类库
    compile 'joda-time:joda-time:2.3'
    compile 'com.orhanobut:logger:1.15'
    compile 'com.blankj:utilcode:1.3.0'
    //播放器库
    compile files('libs/pldroid-player-1.3.2.jar')
    compile 'com.qiniu:happy-dns:0.2.10'
    compile 'com.qiniu.pili:pili-android-qos:0.8.13'
    //弹幕烈焰使
    compile 'com.github.ctiao:DanmakuFlameMaster:0.5.4'
    //Appbar滑动动画
    compile 'com.github.todou:appbarspring:1.0.3'
    //内存泄漏
    debugCompile 'com.squareup.leakcanary:leakcanary-android:1.5'
    releaseCompile 'com.squareup.leakcanary:leakcanary-android-no-op:1.5'
    testCompile 'com.squareup.leakcanary:leakcanary-android-no-op:1.5'
##部分截图
<img src="https://github.com/452MJ/C9MJ/blob/master/screenshots/live_roomlist.jpg" width = "33%"/>
<img src="https://github.com/452MJ/C9MJ/blob/master/screenshots/user.jpg" width = "33%"/>
<img src="https://github.com/452MJ/C9MJ/blob/master/screenshots/live_play_portrait.jpg" width = "33%"/>
<br>
<img src="https://github.com/452MJ/C9MJ/blob/master/screenshots/live_play_landscape.jpg" width = "100%"/>
<img src="https://github.com/452MJ/C9MJ/blob/master/screenshots/live_play_landscape_with_controller.jpg" width = "100%"/>
<img src="https://github.com/452MJ/C9MJ/blob/master/screenshots/live_play_landscape_with_controller_2.jpg" width = "100%"/>

## 关于
本项目所有接口Api均利用Fiddler抓包分析所得，只用于分享、学习。
