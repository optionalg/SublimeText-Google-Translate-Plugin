Sublime Text Google Translate Plugin
===============================

For SublimeText 2 & 3, support proxy `PROXY_TYPE_SOCKS5` `PROXY_TYPE_SOCKS4` `PROXY_TYPE_HTTP`

**Version:** 2.0.0

![Sublime Text Google Translate Plugin](/GoogleTranslate.gif)
------------------

Install:
=======

**Without Git:** Download the latest source from [GitHub](https://github.com/MtimerCMS/SublimeText-Google-Translate-Plugin) and copy the GoogleTranslate folder to your Sublime Text "Packages" directory.

**With Git:** Clone the repository in your Sublime Text "Packages" directory:

    git clone https://github.com/MtimerCMS/SublimeText-Google-Translate-Plugin GoogleTranslate

Folder name must be **GoogleTranslate** !!

The "Packages" directory is located at:

* OS X:

        ST2: ~/Library/Application Support/Sublime Text 2/Packages/
        ST3: ~/Library/Application Support/Sublime Text 3/Packages/

* Linux:

        ST2: ~/.config/sublime-text-2/Packages/
        ST3: ~/.config/sublime-text-3/Packages/

* Windows:

        ST2: %APPDATA%/Sublime Text 2/Packages/
        ST3: %APPDATA%/Sublime Text 3/Packages/

Configure:
=========

Set Target Language AND Source Language [default is auto detect] in user settings:


    {     
		"source_language": "en", // default is 'auto'
    	"target_language": "zh-CN", // must be specified
    	"target_type": "html",	// or plain or html
    	"proxy_enable": "yes",	// enable or disable proxy
    	"proxy_type": "socks5",	// socks4 or socks5 or http
    	"proxy_host": "127.0.0.1",	// eg. 127.0.0.1
    	"proxy_port": "9050"	// eg. 9050
    }


Usage:
=====

Select text:

* press `ctrl+alt+g` or select `Google Translate seclected text` in context menu

Tips:
====

Overview your language code:

* press `Google Translate Print the available translate variants` in context menu

Features:
=======

* Support proxy! F*K GFW !
* 80 languages support!
* SublimeText 2 & 3 support!
* Autodetect source language!
* Ability to specify source language & target language!
* Ability to choose the target language in context menu
* Ability to choose output type, 'plain' or 'html'
* Ability to specify proxy type, proxy host, proxy port
* Fixed Google Translate output errors
* Implemented translation of multiple selection **`[Ctrl]`**!

Credits:
=======

* [PySocks](https://github.com/Anorov/PySocks)
* [MTimer](http://www.mtimer.cn)

License:
=======

MIT



------------------



Sublime Text Google 翻译插件
==========================

SublimeText Google 翻译插件 支持 ST 2 和 3，支持各种代理！**GFW** 你逼我的！

@更多优秀项目 [下载插件中文版](http://dev.mtimecms.com)

**当前版本:** 2.0.0

------------------

安装:
====

**不用 Git:** 从 [GitHub](https://github.com/MtimerCMS/SublimeText-Google-Translate-Plugin) 下载 GoogleTranslate 文件复制到 Sublime Text "程序包" 目录。

**用 Git:** 克隆岛 Sublime Text "程序包" 目录:

    git clone https://github.com/MtimerCMS/SublimeText-Google-Translate-Plugin GoogleTranslate

目录名必须为 **GoogleTranslate** !!

插件将位于 "程序包" 目录:

* OS X:

        ST2: ~/Library/Application Support/Sublime Text 2/Packages/
        ST3: ~/Library/Application Support/Sublime Text 3/Packages/

* Linux:

        ST2: ~/.config/sublime-text-2/Packages/
        ST3: ~/.config/sublime-text-3/Packages/

* Windows:

        ST2: %APPDATA%/Sublime Text 2/Packages/
        ST3: %APPDATA%/Sublime Text 3/Packages/

设置:
====

从 source_language 翻译到 target_language，你可以在 ST 中设置:


    {     
		"source_language": "en", // 默认是 'auto'
    	"target_language": "zh-CN", // 必需填写
    	"target_type": "html",	// 输出格式，plain 或者 html 格式
    	"proxy_enable": "yes",	// 开启或关闭代理
    	"proxy_type": "socks5",	// socks4 或者 socks5 或者 http
    	"proxy_host": "127.0.0.1",	// 比如 127.0.0.1
    	"proxy_port": "9050"	// 比如 9050
    }


用法:
====

鼠标划选需要翻译的内容，可以多选:

* 按 `ctrl+alt+g` 或者右键面板中选择 `Google Translate seclected text`

技巧:
====

查看你的语言代码:

* 在邮件面板中点击 `Google Translate Print the available translate variants`

功能:
====

* 支持各种代理! F*K GFW !
* 支持 80 种语言互相转换翻译!
* 支持 SublimeText 2 & 3!
* 自动监测 source language!
* 可以指定 source language & target language!
* 可以右键选择需要翻译成的语言
* 可以设置代理服务器类型、地址、端口
* 可以选择输出类型, 'plain' 或 'html'
* 修复 Google 输出的 html 标签错误
* 可以多划选翻译 **`[Ctrl]`**!

感谢:
====

* [PySocks](https://github.com/Anorov/PySocks)
* [MTimer](http://www.mtimer.cn)

版权:
===

MIT