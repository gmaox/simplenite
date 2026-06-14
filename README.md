# Simplenite

<details>
<summary>
English README
</summary>

A clean yet feature-rich game launcher with simple configuration, low resource usage, and a Nintendo Switch-inspired interface.
https://discord.gg/ZZBwvfht3

<details>
<summary>
Xbox Full-Screen Experience Guide
</summary>

1. [Click here to install OmniConsole](https://8bit2qubit.github.io/omniconsole-site/zh-CN/download/)

2. After completing the basic full-screen setup by following the OmniConsole tutorial, refer to the image below and add Simplenite to the Custom section. You can then enjoy Simplenite in full-screen mode.

<img width="1920" height="1080" alt="IMG_20260612_224546" src="https://github.com/user-attachments/assets/6cf78028-99b2-43ec-b5b2-df07741e1022" />

</details>

<hr>

# Overview

**A lightweight Windows game launcher with a collection of built-in gaming utilities, making it easy to manage your gaming experience on Windows 10/11.**

<img width="1909" height="1080" alt="1000206717" src="https://github.com/user-attachments/assets/49a88ab2-aaba-4f84-ab6f-b066711f8a52" />

**⭐ Highlights**

**Minimalist Design**: No complicated settings menus. Manage your game library in full-screen mode for a truly immersive experience.

**Low Resource Usage**: Built on efficient Qt components, requiring only a few dozen megabytes of memory. Fast startup speed—go from picking up your controller to launching a game in as little as 3 seconds.

**Thoughtful Design**: Carefully arranged layouts, excellent touch support, and comprehensive controller compatibility (Xbox/DS4).

<img width="1911" height="1080" alt="1000206719" src="https://github.com/user-attachments/assets/ad85f498-e6d7-4548-966d-cea438b2ee72" />

**⭐ Features**

**Beyond game launching, the software also includes the following features:**

**Mouse Emulation**: Asymmetrical dual-stick controls for precise mouse movement. Includes a unique keyboard emulation system that is easy to learn, efficient to use, and can be activated on demand for emergency situations.

**Utility Hub**: A quick-launch menu for commonly used applications is available in the upper-left corner. Applications can be configured to launch alongside games, reducing the number of startup programs.

**Game Save Sync**: One-click cloud save synchronization via WebDAV.

**Game Screenshots**: Capture screenshots instantly with your controller and preserve your favorite gaming moments.

**Immersive Mode**: Hide desktop clutter and distractions to recreate a handheld-console-like experience.

I've personally found this launcher very comfortable to use, and you're welcome to give it a try. While many game frontend developers prioritize aesthetics over practicality, I focused on the user experience first. A significant amount of thought has gone into optimizing workflows and interaction logic to create a well-balanced game launcher. That said, my abilities are limited, and there may still be imperfections. Your understanding is appreciated.

<hr>

*This software shares its game library with Sunshine. It automatically detects whether Sunshine is installed, and if present, newly added games will be synchronized to Sunshine's game library automatically.*

<hr>

# Build

1. Download and install [Python 3.8.5 (64-bit)](https://www.python.org/ftp/python/3.8.5/python-3.8.5-amd64.exe) (make sure to enable **Add Python to PATH** during installation).

2. Download any IDE (for example, Visual Studio Code from the Microsoft Store).

3. Run the following command in a terminal to install the required dependencies:

`pip install PyQt5 pygame Pillow pywin32 psutil pyautogui icoextract -i https://pypi.tuna.tsinghua.edu.cn/simple`

4. Download the `.py` files from the `dev` branch and run them.

---

END

---

</details>

一个追求简洁全面的游戏启动器，配置简单占用低，仿Switch界面

[国内加速下载链接获取](http://gmaox.github.io/deskgamix)

<details>
<summary>
Xbox全屏体验指南
</summary>
1.[点击安装OmniConsole](https://8bit2qubit.github.io/omniconsole-site/zh-CN/download/)
  
2.按照OmniConsole教程完成全屏基础设置后，参考下图将Simplenite添加在自定义中即可在全屏模式下体验Simplenite
  
<img width="1920" height="1080" alt="IMG_20260612_224546" src="https://github.com/user-attachments/assets/6cf78028-99b2-43ec-b5b2-df07741e1022" />

</details>
  
<hr>

# 软件简介

**一款轻量级的Windows 游戏启动工具，内置多种游戏工具，轻松在Windows 10/11系统上掌控您的设备进行游戏**

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/2e8f4c26-88c4-43a0-8e25-7c64e4859530" />


**⭐功能亮点**

**极简设计**：没有繁琐的设置界面，全屏管理游戏库，沉浸式体验！

**低资源占用**：依赖高效的qt组件，只需几十 MB 内存，拉起速度快，从拿起手柄到进入游戏仅需3秒！

**设计合理**：精心排布的布局，良好的触摸体验，完善的手柄支持（Xbox/ds4）

![1000131675](https://github.com/user-attachments/assets/305dd201-c5b3-472b-a296-7506b650433f)

**⭐特色功能**

**除了游戏启动，该软件还有特色功能如下：**

**鼠标模拟**：左右非对称性摇杆，精确定位鼠标。特色键盘模拟，上手难度低效率高，主动式开启方便应急使用。

**工具合集**：左上角加入常用软件启动菜单，可设置游戏连携启动，减少开机启动项

**游戏存档**：一键同步云端存档，使用webdav。

**游戏截图**：手柄快速游戏截图，记录美好瞬间。

**沉浸模式**：隐藏繁杂桌面图标，回归掌机体验。

该软件我自用挺舒服的，欢迎体验。作为游戏前端，虽然一众开发者有美观>实用的开发理念，但我还是从体验入手，在该前端想了很多逻辑优化，呈现了一个较为合理的游戏启动器。但我个人能力终究有限，瑕疵之处还请谅解。

<hr>

*该软件和sunshine共享游戏库。软件会自动识别是否安装sunshine，若存在会在添加游戏时自动同步到sunshine的游戏库*

<hr>

# 构建

1.[下载python3.8.5-64bit](https://www.python.org/ftp/python/3.8.5/python-3.8.5-amd64.exe) 并安装（勾选PATH）

2.下载任意ide（如微软商店的vs code）

3.在终端输入如下指令安装依赖：

 ` pip install PyQt5 pygame Pillow pywin32 psutil pyautogui icoextract -i https://pypi.tuna.tsinghua.edu.cn/simple ` 

4.下载dev分支中的.py文件运行即可

<hr>

**旧版简介**

<details>
<summary>
--------------◇
</summary>

该前端的优势：
<p>1.依托qt5的自适应布局，界面布局简单舒适
<p>2.一键启动。playnite等一众前端启动游戏时更倾向于展示游戏介绍信息甚至启动影片，更倾向于电玩店，自用其实不太需要。从开启前端到进入游戏仅需3秒
<p>3.配置简单，更专注于游戏
<p>4.仿switch后台唤起，符合逻辑的关闭应用
<p>5.控件大小可调节，列数可编辑
<p>6.前端集成手柄模拟鼠标键盘，体验舒适
<p>7.无论你是客厅手柄还是掌机玩家，还是偶尔使用键盘鼠标的家用电脑玩家，你都能在这个软件获得较舒适的游戏体验
<p>0.依靠sunshine和qsaa管理游戏列表

  未来会加入的：

1.仿switch横向排列（已完成

2.对本次运行周期内从前端已经进入的无进程信息游戏，将收藏按钮改变为绑定进程信息。（不需要了）

3.改变触屏进入游戏逻辑（单击变为移动焦点，不确定更改是否合适，低优先级（已完成）

4.加入按键das和arr改善手感（低优先级

0.动画效果（不会做

最后放个抽象手稿：
![1000155737](https://github.com/user-attachments/assets/ff05e348-74b5-4cf4-82e0-e4489692044c)

</details>
