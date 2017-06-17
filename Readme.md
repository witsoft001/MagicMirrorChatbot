# 树莓派聊天机器人
本程序基于Python，为树莓派魔镜项目的一部分。实现流程为利用百度语音识别API识别指令——返回文本——利用图灵机器人API实现聊天——返回文本——利用百度语音合成输出回答。

## 文件替换
使用时，请自行替换百度语音API及图灵API的key。
录音及播放程序可自行设定，注意树莓派用户不推荐使用omxplayer，会出现播放缺失头尾部的现象。

## 依赖
使用前请确保以安装python2,python3及urllib, urllib2。
建议使用pip install安装。
