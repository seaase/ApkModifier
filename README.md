ApkModifier词典文件
==========================================================================================
[英汉词典](https://raw.githubusercontent.com/seaase/ApkModifier/master/EN-CN.db)


ApkModifier 使用中常见问题:
==========================================================================================
   1.修改后的Apk安装时出现解析包错误，请签名即可<br/>
   2.翻译出现问题，账户翻译字数已超限<br/>

特别提示
==========================================================================================
1.关于安卓7.0打开闪退问题，需要手动到系统设置中给软件权限，由于安卓7.0提高了安全，所以会自动禁用软件的权限<br/>
2.新版安装后崩溃，请清除软件数据，新版与旧版数据有冲突<br/>

使用教程
==========================================================================================
[教程视频](http://pan.baidu.com/s/1nvyhy7v)

更新历史:
==========================================================================================
[v1.0](http://pan.baidu.com/s/1dFgMzQD) <br/>
1.文件管理器功能(复制，剪切，粘贴，删除，重命名)<br/>
2.zip管理器，在打开的压缩包文件中，可以对内部的文件进行随意的移动，修改，并且没有确认是不会保存。<br/>
3.签名Apk<br/>
4.so库文件符号名编辑器(可以修改so中的符号名，但又能保证符号名的hash表被正确修复，如果要克隆一个apk，如果包中有so文件需要改包名，这就起到了作用)<br/> 
5.zipalign 压缩包字节对齐<br/>
6.apk共存<br/>
7.res资源文件混淆(是否查看过QQ安装包内部的文件，发现没有res文件夹，只有r文件夹，其实他用的就是类似的加密)<br/>
8.反编译和回编译Dex文件(手机端apktool也可以，但是安装包却很大)<br/>
9.apk文件以及图片能显示略缩图<br/>
10.arsc,dex,axml字符串常量编辑<br/>

[v1.1](http://pan.baidu.com/s/1hs7KBYW) <br/>
1.更换图标<br/>
2.支持安卓7.0<br/>

[v1.2](http://pan.baidu.com/s/1eSh026e) <br/>
1.更换图标<br/>
2.更换用户界面为安卓2.3风格(原谅作者对2.3觉得非常经典)<br/>
3.修复克隆部分apk时软件闪退<br/>
4.字符串常量池的color的常量支持颜色显示<br/>

[v1.3](https://pan.baidu.com/s/1dF5PafR) <br/>
1.文件管理支持多选操作<br/>
2.优化字符串常量池的搜索方法<br/>
3.设置添加主题选择，可以选择本机主题和怀旧主题<br/>
4.其他一些细小优化<br/>

[v1.4](http://pan.baidu.com/s/1o8M1LAa)(重大更新，下载过词典的请重新更新)<br/>
1.搜索方案优化<br/>
2.字符串常量池添加跳转功能<br/>
3.支持压缩文件(加密，注释)<br/>
4.修复7.0及以上保存arsc文件时的错误<br/>
5.修复7.0及以上无法用系统打开文件<br/>
6.7.0及以上的初始目录改为/mnt<br/>
7.增加词典管理，可以制作自己的词典以及编辑已有词典，支持翻译后的内容保存到词典<br/>
8.其他一些细小优化<br/>

[v1.4.2](http://pan.baidu.com/s/1dF7QZdv)<br/>
1.添加土耳其语言支持<br/>
2.修复res资源混淆时出现的错误<br/>

[v1.4.3](http://pan.baidu.com/s/1i5hu5sp)<br/>
1.添加俄语支持<br/>
2.修复一个小bug<br/>

[v1.4.4](http://pan.baidu.com/s/1ckW6Do)<br/>
1.添加波斯语支持<br/>
2.arsc解析速度提升30%左右<br/>

[v1.5](http://pan.baidu.com/s/1kVO9Xdl)(技术进步)<br/>
1.arsc的所有资源都支持修改，其中color资源还有颜色指示器和选择器<br/>
2.修复克隆时的一些崩溃<br/>
3.arsc解析速度提升<br/>
4.字符串常量池资源搜索支持按id搜索<br/>
5.其他一些细小优化<br/>

[1.5.2](http://pan.baidu.com/s/1dF9Tdct)<br/>
1.修复部分机型访问词典数据库时内存泄漏的问题<br/>
2.修复小bug<br/>

[v1.6](http://pan.baidu.com/s/1slMvOsd)<br/>
1.修复克隆时的一些崩溃<br/>
2.字符串常量池条目长按支持复制内容<br/>
3.翻译语言增加土耳其语言支持<br/>
4.听说安卓6.0不能访问sd卡，特地看了一下<br/>

[v1.6.2](http://pan.baidu.com/s/1hsp4tec)<br/>
1.添加谷歌(Google)翻译<br/>
2.添加维吾尔语言包<br/>

[v1.6.3](http://pan.baidu.com/s/1dFmmAnZ)<br/>
1.优化谷歌翻译速度<br/>
2.翻译支持的语言增加到35种<br/>
3.修复自定义翻译账号不能用的问题<br/>

[v1.6.4](http://pan.baidu.com/s/1bpEHceV)<br/>
1.压缩包浏览根据文件的前几个字节来判断是否是图片或xml,方便对付资源混淆后的软件<br/>

作者的其他作品
==========================================================
[ApkCrack](https://seaase.github.io/ApkCrack/)

关于作者
===========================================================
QQ:2801045898<br/>
E-Mail:2801045898@qq.com<br/>
HaGeSea@outlook.com<br/>

支持开发
============================================================
支付宝：13867750642<br/>
微信：18705874746<br/>
如果愿意，你可以对我捐赠，我也会更加有动力来开发和完善本软件。<br/>
如果没有这些，你可以下载[ApkModifier PRO ](http://pan.baidu.com/s/1eRFakvw)安装后打开，点击广告。以此来支持开发者<br/>

