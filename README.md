# caj2pdf-add bookmark

[TOC]



# 1. 用途

此工具不能用于将caj格式文件转换为pdf文件，此工具正确用途为：**为处于文本可选择编辑模式的PDF文件（非图形模式的pdf）添加目录**。

如需将caj文件（如zhi wang）转换为pdf文件，可自行上网搜索转换软件。更推荐方法为：通过chrome插件“Tampermonkey”（俗称油猴）添加脚本实现（可通过脚本直接在例如zhi wang等页面直接添加pdf文件下载按钮从而下载文档的pdf格式）

（脚本选项之一：https://greasyfork.org/zh-CN/scripts/390733-%E7%9F%A5%E7%BD%91pdf%E4%B8%8B%E8%BD%BD%E5%8A%A9%E6%89%8B）

此软件为广大网友所提供，非常感谢！

# 2. 使用方法

**添加目录操作过程只需使用该可执行文件即可“FreePic2Pdf.1395217315.exe”**

## 2.1 word中生成可识别的目录格式

1. 新建word文档并打开
2. Alt+F11 调起“Microsoft Visual Basic for Applications”编辑器
3. 在左侧工程栏目，选择Normal，右键选择导入文件，选择“书签.bas”
4. Normal下出现模块选项，其中包含知网书签
5. 保存并退出visual basic编辑器
6. 在word内粘贴目录
7.  word中选择宏功能并点击，出现宏名“书签”，点击允许，书签格式自动调整成功

## 2.2 为pdf文件添加目录

**此操作成功的关键在于PDF需为文字版（可选择文字的状态），图片版（多为扫描）的无法成功提取文章中的目录标题文字**

1. 打开“FreePic2Pdf.1395217315.exe”

2. 操作过程如下图：

   ![1.png](https://github.com/Archie-King/images/blob/main/1.png?raw=true)

   ![2.png](https://github.com/Archie-King/images/blob/main/2.png?raw=true)
   
   

3. 然后将此前在word中生成的目录完整带格式的复制过来（CTRL+A)，粘贴后保存。

   ![3.png](https://github.com/Archie-King/images/blob/main/3.png?raw=true)

   ![4.png](https://github.com/Archie-King/images/blob/main/4.png?raw=true)

4. 成功