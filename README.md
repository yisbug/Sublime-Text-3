# sublime text 3 插件和快捷键

包括：
* sublime text3常用的插件
* 尽可能兼容windows和mac的快捷键

### 已安装插件和简介

#### JsFormat
格式化js代码
#### git
#### LiveReload
#### AutoFileName
自动补全文件路径
#### Markdown



### 快捷键设置

快捷键设置原则

* 参考部分`Emacs`快捷键
* 不影响系统常用快捷键，如windows下的ctrl+c/v/x/z/f，mac os中的ctrl+a/e/n/p等

#### 光标移动 `ctrl`系列

* `ctrl+p` 上一行
* `ctrl+n` 下一行
* `ctrl+b` 前一个字符
* `ctrl+f` 后一个字符，和windows下查找快捷键冲突，查找替换为`ctrl+y`
* `ctrl+a` 移动到行首，和windows下全选快捷键冲突，全选替换为`ctrl+q`
* `ctrl+e` 移动到行尾。

#### 光标移动 `alt`系列

* `alt+p` 上一屏幕
* `alt+n` 下一屏幕
* `alt+b` 前一个单词
* `alt+f` 后一个单词
* `alt+a` 文件头部
* `alt+e` 文件尾部

> 光标移动的同时按住`shift`则选择文本。
 

#### 基本命令

* `ctrl+q` 全选
* `ctrl+c` 复制
* `ctrl+x` 剪切
* `ctrl+v` 粘贴
* `ctrl+z` 撤销
* `ctrl+shift+z` 重做
* `ctrl+,` 删除左边一个字符
* `ctrl+.` 删除右边一个字符
* `alt+v` 从历史记录中粘贴

#### 文件操作

* `ctrl+t` 新建文件
* `ctrl+s` 保存文件
* `ctrl+w` 关闭文件
* `ctrl+o` 打开文件
* `ctrl+shift+t` 在新窗口新建文件 
* `ctrl+shift+w` 关闭窗口
* `ctrl+shift+s` 另存为
* `ctrl+alt+t` 撤销上一次关闭的文件

#### 查找和替换

* `ctrl+d` 选中下一个单词
* `ctrl+k,ctrl+d` 在`ctrl+d`模式中跳过当前内容
* `ctrl+h` 替换
* `ctrl+y` 查找

#### 查找和替换模式
使用`ctrl+y`或`ctrl+h`打开查找面板后
* `ctrl+enter` 可输入多行查找的字符
* `alt+r` 切换正则模式
* `alt+c` 切换大小写匹配
* `alt+w` 切换匹配整个单词
* `enter` 查找下一个
* `shift+enter` 查找上一个
* `alt+enter` 查找所有
* `ctrl+alt+enter` 替换所有
* `ctrl+shift+h` 替换一次

#### 分组和文件移动

* `alt+shift+1` 分为1列，一个分组
* `alt+shift+2` 分为2列，两个分组
* `alt+shift+3` 分为3列，三个分组
* `ctrl+alt+1` 将焦点文件移动到分组一
* `ctrl+alt+2` 将焦点文件移动到分组二
* `ctrl+alt+3` 将焦点文件移动到分组三

#### 焦点和窗口移动

* `ctrl+2` 向左切换一个文件到焦点
* `ctrl+3` 向右切换一个文件到焦点
* `alt+0` 切换焦点到侧边栏
* `alt+1` 切换焦点到分组1
* `alt+2` 切换焦点到分组2
* `alt+3` 切换焦点到分组3
* `ctrl+alt+p` 屏幕向上滚动一行
* `ctrl+alt+n` 屏幕向下滚动一行


#### 其他系统命令

* `ctrl+\` 切换文件
* `ctrl+shift+\`,`ctrl+shift+p` 打开命令输入
* `ctrl+alt+\` 切换项目
* `ctrl+r` 跳转到函数，或者`ctrl+\`后加`@`操作符
* `ctrl+g` 跳转到行，或者`ctrl+\`后加`:`操作符
* `ctrl+;` 跳转到定义，或者`ctrl+\`后加`#`操作符
* `ctrl+u` 编译，sublime默认为`ctrl+b`
* `ctrl+shift+u` Run
* `alt+shift+f` 全屏
* `alt+shift+g` 无干扰模式
* `ctrl+/` 注释
* `ctrl+[` 取消缩进
* `ctrl+]` 缩进
* `ctrl+l` 选择行
* `ctrl+shift+l` 分隔光标到选择的每一行
* `ctrl+m` 区域首尾跳转


#### 插件命令

* `ctrl+alt+f` 格式化js代码
* `ctrl+alt+w` 在项目根目录路径打开terminal
* `ctrl+alt+shift+w` 在文件路径打开terminal