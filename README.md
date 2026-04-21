# jygame
这是《金庸群侠传X0.6》的opensilver 版本

### 软件架构
软件架构说明 使用opensilver框架

### 开发环境安装教程
操作系统：win10

下载按照开发环境 VS2026

安装OpenSilver_SDK_v3.3.3.0.vsix 下载地址：https://opensilver.net/

编译整个解决方案，启动JyGame.Browser 项目即可

### 部署到IIS

1、发布JyGame.Browser 后，部署到IIS 2、iis映射到wwwroot目录下，应用程序池设置为无托管模式即可 输入图片说明 输入图片说明


### 部署常见问题

1、如果部署到iis后页面打不开，可以看是哪个文件没加载，检查iis网站的MIME类型里面是否包含该文件类型，如果没有，加上即可


2、如果IIS部署后，还是打不开，安装一下这个工具：https://download.microsoft.com/download/1/2/8/128E2E22-C1B9-44A4-BE2A-5859ED1D4592/rewrite_amd64_zh-CN.msi
