## 欢迎使用Altman网站管理工具##
`免责申明：本程序仅供学习和研究！
请使用者遵守国家相关法律法规！
由于使用不当造成的后果本人不承担任何责任！`

### 为什么要写它###
针对现有的网站管理工具，本人对这类软件进行了分析，研究和改进，写出了本工具。

本人旨在对互联网安全技术的发展做出一点贡献，同是为传播开源精神出一点力。

### 它能做什么 ###
**Altman** 是一款网站管理工具。

截至目前，它可以：

- 自定义代理
- 自定义HttpHeader
- 自定义脚本类型和脚本功能
- 自定义加密/编码
- 自定义插件
- Shell管理插件
- 命令执行插件
- 文件管理插件
- 数据库管理插件
- 插件管理中心

目前支持的脚本类型有：asp、aspx、php、jspFull、python

### 如何运行它 ###
**Altman** 基于.Net4.0，兼容Mono，可以运行在windows、linux、mac（不推荐）等平台。

在`Windows`下，需要安装.Net4.0，点击`Altman.exe`即可运行。

在`Linux`下，需要安装Mono(>=3.2.8)以及libgdiplus，在终端输入命令`mono Altman.exe`即可运行。

在`Mac`下，需要安装Mono和MonoDevelop，在终端输入命令`mono Altman.exe`即可运行。

### 如何扩展它的功能 ###
**Altman**采用了mef插件架构，脚本类型（.type）、脚本功能(.func)也是以文件形式保存。

你可以：

- 添加或修改脚本类型，使它支持更多脚本类型（asp、aspx、php、jsp、python等）
- 扩展插件，只需要引用特定接口dll
- xxxxx(某些高级功能可能会被人恶意使用，故不详细说明)

### 是否使用、修改它的代码 ###
本程序使用的是GPL协议，具体细节请参照根目录下的`LICENSE`文件，谢谢。

### 如何联系我 ###
我的邮箱keepwn#gmail.com

- 如果你有任何问题
- 如果你有任何建议
- 如果你实现了新插件或者新的脚本类型，或者对程序有帮助的地方

欢迎来信。

技术讨论群:331451473
