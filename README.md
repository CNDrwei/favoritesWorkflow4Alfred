# 充电器功率.alfredworkflow
展示当前充电器功率

# random_pic.alfredworkflow
根据尺寸 `宽x高` or `宽*高` 随机生成图片到桌面

# resetZoom.alfredworkflow
模拟鼠标操作关闭/打开双指缩放开关，从而在mac双指缩放失灵的时候达到快速修复的效果

# srt.alfredworkflow
个人用于解析提取剪映字幕的工具

# figma复制的svg处理.alfredworkflow
可以直接将figma（或其他地方）复制的svg内容替换掉fill后保存到当前Finder打开的目录中，或仅存到剪切板

# sequence.alfredworkflow
生成序列，多用于列编辑

# css.alfredworkflow
把写好的css【内联样式】和【内部样式之间】互相转换
* 内联->内部：复制内联样式（不包含style=""，仅复制里面的样式内容），alfred命令 `style`
* 内部->内联：复制内部样式（不包含&lt;style>&lt;/style>，仅复制里面的样式内容），alfred命令 `inline`


# frontiterm.alfredworkflow
全局快捷键 `` command + ` `` 打开/激活 iterm

# Len().alfredworkflow
复制一段文本，计算其长度

# Paste Markdown Pic.alfredworkflow
将 Markdown 图片链接由上面转换到下面的形式，便于控制图片的大小和是否居中
```
![名称](链接)

<div align="center">    
    <img src="链接" width="300" />
</div>
```

# GitClone.alfredworkflow
自动读取剪切板的git仓库地址，并clone到指定的目录

# MyWeekly.alfredworkflow
一款记录周报的小插件
> 为了方便大家使用，已经将node项目打包成可执行程序（使用时无需安装node环境），所以插件体积有点大（16.5M）

# jsonEditor
[一款chrome插件](https://github.com/sunzsh/chromeapp-jsonedit)的辅助工具，可以在chrome中快速打开json编辑器

# curl2local
可以将剪切板里的curl命令转换成请求本地127.0.0.1的命令


# NewPath
可以直接在最前面的Finder窗口内创建目录和文件：
> 建议安装后，分别将新建目录和文件的命令改为mkdir和touch，用起来会有在使用终端的错觉

<https://github.com/vitorgalvao/alfred-workflows/tree/master/NewPath>

# OpenItermInXcode
我自己写的可以直接在iterm里面打开最前面xcode窗口的项目地址
> 下载地址在上面

# Visual Studio Code plus
学习了 [alexchantastic/alfred-open-with-vscode-workflow](https://github.com/alexchantastic/alfred-open-with-vscode-workflow) 的代码后，增加了对st和idea的支持

# IP Address
可以直接获取本机ip和公网ip

<https://github.com/alexchantastic/alfred-ip-address-workflow/>

# TimeStamp Convert 
时间戳工具
> 依赖php环境，新版的MacOS需要自己安装配置php

<https://github.com/codezm/Alfred-codezm-workflows-timestamp-convert>

# Kill Process
根据名称kill进程，按住command同时杀掉所有同名进程
<https://github.com/nathangreenstein/alfred-process-killer>

# Audio Device
切换Mac音频 输入/输出源
> 重度使用场景：使用AirPods在笔记本和手机之间切换的时候，偶尔不那么灵敏，用这个插件可以快速的强制切换

* <https://michael.thegrebs.com/2013/01/18/alfred2-audio-device/>
* <https://github.com/sunzsh/favoritesWorkflow4Alfred/raw/main/Audio%20Device.alfredworkflow> 备用

# TerminalFinder
在Finder和终端（包括iterm）之间来回切换的组件

<https://github.com/LeEnno/alfred-terminalfinder>

# knm
我自己写的 海里<->公里 互转工具

# GitLab
配置好私服地址&token信息后，可以快速查找项目并进入项目的issues、overview等页面
> 非常好用

<https://github.com/lukewaite/alfred-gitlab>

# Youdao Translate
有道翻译
> 最新版已经不在依赖php

<https://github.com/wensonsmith/YoudaoTranslator>

# TimeStamp Convert Python.alfredworkflow
基于python版本的时间戳转换, 需要自己安装Python环境, 然后 pip install python-dateutil
### 时间戳转换工具, python 版本
默认快捷键 `ts`, 查看当前时间格式展示 
- 展示当天时间信息 `ts n` 或者 `t now`
    - 展示多久之前的时间
        - 支持的参数 h|hour|min|minutes|d|day|m|mon|month|y|year
        - 支持小时 分钟 天 月 年
        - `ts -2h` 2小时前 `ts -2min`2分钟前 支持小数 `ts -2.5h`
- 将时间戳转换成日期格式, 反之亦然 `t 1495276608` `t 2017-05-20 18:52:46`
  - 为了兼容复制的时候复制多了, 或者是时间戳被放大的情况, 只取前10位计算
- 选中某一项转换结果键入 `Enter` 即可复制
