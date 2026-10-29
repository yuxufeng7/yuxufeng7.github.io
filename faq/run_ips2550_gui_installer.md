# 如何安装 IPS2550 GUI 软件

## 问题

解压安装包后，看到以下两个文件：
- `IPS2550STKIT Application Setup.msi`
- `setup.exe`
应该双击运行哪个文件完成安装？

![安装包内容示例](resouce/img/ips2550_gui_install_files.png)

## 答案

**推荐优先运行 `setup.exe`。**
这是标准安装入口，安装程序会自动检查系统环境并调用 MSI 安装包完成安装。
相比直接运行 `.msi` 文件，使用 `setup.exe` 可以：
- 自动检查安装依赖项
- 自动安装缺失的运行库
- 完成安装前的环境配置

**推荐安装流程如下：**
```text
解压安装包
    ↓
运行 setup.exe
    ↓
完成安装向导
    ↓
启动 IPS2550 GUI
```
