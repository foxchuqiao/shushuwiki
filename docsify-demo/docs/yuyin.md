------



# 1	发语音发不出来，显示CQ码或直接报错

安装ffmpeg:

在Windows上安装FFmpeg通常有几种方法，以下是简单易行的步骤，适用于大多数用户：

## 方法1：直接下载预编译的Windows二进制文件

1. **访问FFmpeg官方网站**：
   访问 [FFmpeg官方下载页面](https://ffmpeg.org/download.html)。

2. **下载Windows版本**：
   在页面中找到“Windows”部分，点击适合您系统的版本链接（例如，64-bit Static或Shared版本）。您也可以选择从第三方提供的稳定构建，如 [BtbN/FFmpeg-Builds](https://github.com/BtbN/FFmpeg-Builds/releases)。

3. **解压下载的文件**：
   将下载的.zip文件解压缩到您想要存放FFmpeg的目录，例如 `C:\ffmpeg`。

4. **配置环境变量**：
   - 右键点击“此电脑”或“计算机”，选择“属性”。
   - 点击“高级系统设置”。
   - 在“系统属性”窗口中点击“环境变量”按钮。
   - 在“系统变量”区域找到并选择“Path”，然后点击“编辑”。
   - 在编辑窗口点击“新建”，添加FFmpeg的`bin`目录路径（例如，`C:\ffmpeg\bin`）。
   - 确认所有窗口并关闭。

5. **验证安装**：
   打开命令提示符（按下Win+R，输入`cmd`，回车），输入 `ffmpeg -version`，如果看到FFmpeg的版本信息，表示安装成功。

## 方法2：使用Cygwin

如果您更倾向于使用Linux风格的环境，可以选择安装Cygwin：

1. **下载并安装Cygwin**：
   访问 [Cygwin官网](https://www.cygwin.com/)，下载安装程序，运行后选择合适的安装包，包括编译工具和FFmpeg相关组件。

2. **在Cygwin中编译FFmpeg**：
   打开Cygwin终端，使用Cygwin的包管理器安装必要的依赖，然后按照常规Linux环境下编译FFmpeg的步骤进行。

这种方法相对复杂，更适合那些需要定制编译选项或在Windows上使用Linux工具链的用户。
大多数用户会选择第一种方法，因为它更简便快捷。

2.如果还不行可能是网站暂时不稳定，稍后再试。

![](https://cn-sy1.rains3.com/jiaocheng/nb.gif)


