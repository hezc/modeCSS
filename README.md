# CSS mode for Sublime Text #

样式模块管理工具，模块化样式的更快处理、优化。

## 功能 ##
### 样式压缩 ###

*  "ctrl+shift+m"：默认压缩光标所在样式规则。
* "ctrl+shift+alt+m"：压缩整个文档中的样式规则。

### 图片转BASE64编码 ###

* “ctrl+shift+e”：将光标所在位置的图片转换为BASE64编码。CSS为光标规则中的图片；HTML中光标所在的img标签。
* “ctrl+shift+alt+[”：折叠编辑器中的Base64代码。
* “ctrl+shift+e”：展开编辑器中的Base64代码。

## TODO LIST ##

* 检查图片是否存在
* 格式化
* 属性排序
* 导入外部文件
* 更新相关文件
* 检查模块样式依赖性、完整性

## DONE LIST ##
### 功能 ###

#### 2015-03-23 更新

* 图片转换功能优化
* 图片转换base64编码后将代码折叠
* base64代码折叠、展开

#### 2015-01-07 更新

* 图片转换功能支持Sublime Text 3
* 代码优化

已知道问题

* 图片转换功能

#### 2013-01-14 更新

* 压缩样式
* 区分CSS和HTML文件（HTML只处理STYLE标签的部分）
* 图片添加、更新、删除时间缀
* 图片时间缀支持IE滤镜中的图片
* 将图片转换为BASE64编码（只支持光标所在区域：样式定义或img标签）

### 设置 ###
* 压缩成一行（设置）
* 压缩成多行（设置）
* 删除最后一个分号（设置）
* 压缩时保留注释（设置）
* 更新图片时间缀（设置）
* 版本标识（设置）
* 定义时间缀后缀字符（设置）
* 使用base64代码折叠（设置）