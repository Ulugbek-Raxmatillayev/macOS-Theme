本软件是免费开源软件 使用LGPLv3许可证
This software is free and open source software licensed under LGPLv3
https://github.com/Maplespe/ExplorerBlurMica

更新日志(update log)：

1.0.7 2023-8-11
增加新的配置文件选项:
- clearAddress : 清除地址栏背景颜色
(注意:如果你使用了StartAllBack 请将"右侧经典搜索栏"选项关掉 否则它会覆盖本程序的效果)
- clearBarBg : 清除滚动条背景颜色
(注意:由于系统滚动条本身不透明 因此为了去除背景色 滚动条是由本程序自绘的 它可能和系统样式有所差别)
- effect=3 : 将effect设置为3 则启用Blur(Clear)效果 这是一个没有任何着色的纯模糊效果#42

配置文件变更(系统颜色自适应支持#32):
原来的[blend]配置改为[light]和[dark]分别配置 请注意修改! 详情见config.ini

bug修复:
修复了Windows 11多标签页 打开新的标签页后 旧的标签页"showLine"效果失效
修复了DPI更改时和切换显示器时 丢失窗口效果的问题 #46
修复了文件资源管理器的"属性"页面和文件对话框的渲染问题 #35
修复了和优化了部分渲染问题

Add new feature settings:
- clearAddress : Clear the background of the address bar.
(Note: If you use StartAllBack, you must close the "Classic search box", otherwise it overrides the effect of this program).
- clearBarBg : Clear the background color of the scrollbar.
(Note: Since the system scrollbar itself has a background color that cannot be removed,
when this option is turned on, the scrollbar is drawn by the program and the style may be different from the system).
- effect=3 : Set effect to 3 to enable the Blur effect This is a pure blur effect without any coloring #42

Configuration file changes (system color adaptation support#32):
The original [blend] configuration has been changed to [light] and [dark] separately Please note the changes! See config.ini for details.

Bug fixes:
Fixed Windows 11 multi-tabbing issue where the "showLine" effect on old tabs is not working when opening new tabs.
Fixed missing window effects when changing DPI and switching monitors #46.
Fixed a rendering issue with the File Explorer Properties page and the File dialog #35.
Fixed and optimized some rendering issues.


--------------------------------------------------------------------------

1.0.6 2023-5-1
增加新的配置文件选项: 
- showLine : 该选项指定是否在主视图的TreeView和预览面板之间显示一条分隔线。 true或者false
- darkRibbon : Ribbon的文本颜色和背景在Windows 10 Light模式下呈现不正确, 这个选项允许你将Ribbon设置为Dark模式，以缓解这一问题。
详情请看ReadMe


修复了Windows 10 Acrylic效果超出窗口边框的问题 smallBorder选项现在默认false


Add new feature settings
- showLine : This option specifies whether to show a separator line between the TreeView and the preview panel in the main view.
- darkRibbon : Ribbon text colors and backgrounds are rendered incorrectly in Windows 10 Light mode.
This option allows you to set the ribbon to dark mode to alleviate this problem.
For more information, please see ReadMe.

Fixed Windows 10 Acrylic effect out of window border issue. smallBorder option now defaults to false

--------------------------------------------------------------------------

1.0.5 2023-4-29
修复了与StartAllBack等软件调节导航栏相关的功能的兼容性问题 #17
修复了控制面板的部分渲染问题和通过shell方式打开特定页面渲染效果异常的问题
优化了程序效率和代码

Fixed the compatibility issue with the function of modifying the navigation bar with software such as StartAllBack #17
Fixed some rendering issues in the control panel and the issue of rendering abnormalities when opening certain pages via shell.
Optimized program efficiency and code.

--------------------------------------------------------------------------

1.0.4 2023-1-12
修复了特定情况下可能出现背景渲染错误的问题 #10
修复了控制面板命令模块和导航栏渲染错误的问题 #9
修复了微软输入法文字颜色渲染错误的问题 #8

Fixed possible rendering errors in certain cases #10
Fixed control panel's command module and navbar rendering errors #9
Fixed Microsoft IME input text rendering error in edit box #8

--------------------------------------------------------------------------

1.0.3 2022-11-21
修复了win10 dark 主题颜色下地址栏不透明的问题 #7
修复了win10 配置文件 Blur效果和Acrylic效果参数ID相反的问题

Fixed the problem that the Win10 dark address bar was opaque #7
Fixed the problem that the Blur effect of the win10 configuration file was opposite to the Acrylic effect parameter ID.

--------------------------------------------------------------------------

1.0.2 2022-10-22
支持Windows 22H2系统 支持多标签页 #5
修复了Windows11 最左边有白色竖条的问题
修复了Windows11 暗色模式下地址栏不透明的问题
增强了程序稳定性
增加了Windows11的Acrylic支持 Mica效果现在为effect=2

Support Windows 22H2 system supports multiple tabs #5
Fixed the problem of white vertical bar on the left of WIndows11
Fixed the problem of opaque address bar in Windows 11 dark mode
The program stability is enhanced
Added Acrylic support for Windows 11, Mica effect is now effect=2

--------------------------------------------------------------------------

1.0.1 2022-8-27
Fixed the bug of opaque ribbon bar in Windows 10 English language system