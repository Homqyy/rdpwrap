# RDPWrap

## 说明

- 用途：提供Windows的远程桌面服务，主要是解决Windows家庭版本身不支持远程服务的问题

## 使用步骤

1. 安装：双击`install.bat`
2. 替换补丁文件：
    1. 在CMD终端中输入：`net stop termservice`
    2. 替换`C:\Program Files\RDP Wrapper`文件夹中的`rdpwrap.ini`
    3. 在CMD终端中输入：`net start termservice`
2. 启动配置管理程序：运行`RDPConf.exe`
3. 测试：`RDPCheck.exe`
