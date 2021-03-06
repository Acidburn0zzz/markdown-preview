# Markdown Preview Plus

Automatically parses markdown files (.md) into HTML. This is useful
if you're writing markdown (ultimately targeting HTML) and want a quick
preview.

[Get it for Chrome][webstore]

Features
--------

1. Support auto reload.
1. Support external css file.
1. You can change theme for each single md file.
1. Support github flavored markdown.

Usage
--------

1. Install extension from [webstore][] (creates no new UI)
2. Check "Allow access to file URLs" in `chrome://extensions` listing: ![fileurls](http://i.imgur.com/qth3K.png)
3. Open local or remote .md file in Chrome.
4. See nicely formatted HTML!

Release Notes
-----------------

### 0.3.4

* H2 and HR tag styles update, to be more close to current github styles. Thanks Lukas238. See #13.
* Add an option for custom reload time interval. see #12.

### 0.3.2/0.3.3

* Fix Github theme.

### 0.3.1

* Fixed a bug for code highlight.

### 0.3

* Support github flavored markdown.
* Change the markdown parser from showdown to [marked][marked].

### Changelog

* 0.2.7 Fix a bug for "Export Html".
* 0.2.6 Support code hightlight. Fix a bug for auto reload.
* 0.2.5 Fix a bug when add new css.
* 0.2.4 Add .mkd extension.
* 0.2.3 New button for export html file.
* 0.2.2 
    Add a list of the supported file extensions in the options page.
    Support new file extension .txt
* 0.2.1 
    Add browser icon.
    You can change theme for each single md file.
* 0.2 
     New UI for options page.
     You can upload custom css files.
* 0.1.1 Do not render if file's Content-Type is 'text/html'. 
* 0.1
     Support auto reload. 
     Support external css file.

Thanks
-------

Thanks to Kevin Burke for his [markdown-friendly stylesheet][style],
to John Fraser for his [JavaScript markdown processor][showdown],
to Boris Smus for his [Markdown Preview][mp] and to
Swartz and Gruber for [Markdown][md].

[webstore]: https://chrome.google.com/webstore/detail/markdown-preview-plus/febilkbfcbhebfnokafefeacimjdckgl
[style]: http://kevinburke.bitbucket.org/markdowncss
[marked]: https://github.com/chjj/marked
[md]: http://en.wikipedia.org/wiki/Markdown
[mp]: https://github.com/borismus/markdown-preview


