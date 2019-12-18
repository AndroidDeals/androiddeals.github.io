安装中文输入法（非必要）
同样的，使用adb命令搞定他。
先到当贝市场下载搜狗输入法tv版。
然后adb命令 adb shell ime list -a
之后会列出机子里面的输入法。如图所示
此时复制应用名称com.sohu.inputmethod.sogouoem/.SogouIME
先输入adb shell ime enable com.sohu.inputmethod.sogouoem/.SogouIME开启搜狗输入法
再输入adb shell ime set com.sohu.inputmethod.sogouoem/.SogouIME设置为默认。就可以使用了。