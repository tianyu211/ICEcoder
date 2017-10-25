# ICEcoder

> 正式重做了下，更新了以前出现的问题，这次破解后的版本是 v6.0

## 这里是[破解过程](https://note.guotianyu.cn/Archive/ICEcoder.html) 

简单说下使用方法，直接把仓库克隆到本地，如果是Linux需要给整个文件夹权限
```
 chmod 777 -R ICEcoder
```
然后直接访问到你项目所在的路径就行，比如[我的demo在这里](http://118.89.224.172/ICEcoder/)

**第一次安装会要求你输入三次密码，前两次是注册，第三次是登录，所以不要以为是自己有问题**

#### 这个是基于官方破解版，可以无限试用，可以安装插件<br>[官网](https://www.icecoder.net)<br>[Demo](http://demo.icecoder.net/ICEcoder/)

### 以下是官方介绍
ICEcoder is a web IDE / browser based code editor, which allows you to develop websites directly within the web browser. It uses the brilliant CodeMirror for code highlighting & editing, with a slick IDE wrapped around it to make the whole thing work.

<img src="https://icecoder.net/images/icecoder-v5-7-browser-code-editor.png" alt="ICEcoder web IDE">

### Requirements
You can run ICEcoder either online or locally, on Linux, Windows or Mac based platforms. The only requirement is to have PHP 5 available (5.3 recommended). You can have this either as a vanilla installation or via a program such as WAMP or XAMPP (for Windows) or MAMP (for Mac).

###Installation

####Step 1: Get ICEcoder
Either download the zip or clone from Github using:

```
$ git clone git://github.com/mattpass/ICEcoder
```

####Step 2: Place in your document root (online or local)
* Put in a new sub-dir URL such as yourdomain.com/ICEcoder or localhost/ICEcoder
* Set write permissions (757 or 775 depending on your system) on the 'backups', 'lib', 'plugins', 'test' and 'tmp' folders

*(Note: A small number of web servers give an internal server error here, if you get this, try 755 instead)*

####Step 3: Start coding
* Visit the sub-dir URL in your browser and enter a password

**Now you're setup, auto-logged in and ready to code!**

Suitable for commercial & non-commercial projects, just let me know if it's useful to you and any cool customisations you make to it. I take no responsibility for anything, your usage is all down to you.

It's fully open source and MIT licensed. I'm happy for you to take it, make it your own and customise to your hearts content and/or contribute to this main repo! :)

Plenty of comments included in the code to assist with understanding, customising etc.

Comments, improvements & feedback welcomed!
