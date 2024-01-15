# Furigana

网易云音乐插件：给日文歌词的汉字标注假名
使用了kuromoji的在线API

## Version 0.2.2

1. （测试）将“词”“编”这样的汉字转换为繁体，以便正确注音
2. （测试）将“一人”“二人”这样的词语手动标注为“ひとり”“ふたり”而非机器注音的“いちにん”“ににん”
3. 修复了因代码问题导致的句首汉字注音不准确的问题

## Version 0.2.1

发现插件不再兼容新版Apple Music-like lyrics，即“类苹果歌词”，故在设置界面做出提示。

## Version 0.2.0

1. 由于kuroshiro在线API不可用，将在线API换为kuromoji
2. 对于已经注音过的歌词会进行缓存，以加快再次注音的速度
3. 设置页面的小更改

## Version 0.1.1

测试出Apple Music-like lyrics开启逐词歌词后，使用本插件的部分功能会产生问题。故在设置界面做出提示。

## Version 0.1.0

1. 修复了一些小bug
2. 部分兼容了网易云音乐2.x版本
3. 兼容了Apple Music-like lyrics
