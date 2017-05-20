YOURLS Ver 1.7.2 简体中文语言包
==========================

本语言包是根据 YOURLS 官方翻译模版 修改的简体中文语言包。提供给 YOURLS 1.7.2 以上版本使用。

## 语言包使用方法

1. 访问 [YOURLS 官方网站](http://yourls.org "YOURLS 官方网站")或者此项目的 [Github源](https://github.com/YOURLS/YOURLS/releases "Github源") 下载最新版本的YOURLS程序。
2. 下载本简体中文语言包，将 `zh_CN.po` 和 `zh_CN.mo` 两个文件复制到 YOURLS 安装路径下的 `user/languages` 文件夹中。
3. 修改 `user/config.php` 文件，在文件中找到以下代码：
    define( 'YOURLS_LANG', '' ); 
将其修改为：
    define( 'YOURLS_LANG', 'zh_CN' );
记住保存哦！
> 如果没有该文件，请将 `user/config-sample.php` 另存为该文件名即可。
4. 按照官方的 [安装向导](http://yourls.org/#Install "安装向导") 对其他的设置进行修改。
> 当然也可以将服务器上已经配置好的 `user/config.php` 文件下载到本地进行修改。
5. 完成后，将 YOURLS 安装路径中的所有文件上传到你的服务器空间中。
> 如果你不是全新安装或者升级的话，可以只上传新增的语言包和修改的 `user/config.php` 文件。
6. 打开浏览器访问 `http://_YOURSITE_/admin/` ，就这样！你就可以看到简体中文版的 YOURLS 应用程序了。

## 反馈错误

如果你发现语言包里面的内容有错误，你可以将出现错误的截图等信息提交到本项目的 [Issues](https://github.com/shileiye/YOURLS-zh-CN.pot/issues "Issues") 中，我会尽快进行修改。
