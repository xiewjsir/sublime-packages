# sublime-packages
sublime 安装的一些常用插件

插件安装方式一：直接安装：

   安装Sublime text 3插件很方便，可以直接下载安装包解压缩到Packages目录（菜单->preferences->packages）。

插件安装方式二：使用Package Control组件安装：

   按 Ctrl+` 调出console（注：安装有QQ输入法的这个快捷键会有冲突的，输入法属性设置-输入法管理-取消热键切换至QQ拼音）粘贴以下代码到底部命令行并回车：
   import urllib.request,os; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); open(os.path.join(ipp, pf), 'wb').write(urllib.request.urlopen( 'http://sublime.wbond.net/' + pf.replace(' ','%20')).read())

   重启Sublime Text 3。如果在Perferences->package settings中看到package control这一项，则安装成功。按下Ctrl+Shift+P调出命令面板输入install 调出 Install Package 选项并回车，然后在列表中选中要安装的插件。
