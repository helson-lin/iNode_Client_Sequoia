# iNode_Client_Sequoia

<p align="center">
<img style="width: 100px;" src="./imgs/icon.png"/>
</p>
<p align="center"><span><b>inodeClient Support Macos 15</b></span></p>


**该项目发行版不一定适用所有人，如果无法适用，请联系你们公司内部管理员，提供定制后的老版本客户端，然后自行按照教程来封包**

**Ps: 定制客户端封包：替换 inodeClient.app 和 lib 文件夹基本就可以了，如果发现还是无法使用，建议将 Library、custom、也替换掉**

**关于网络安全检查的Skip 问题，可以配合另一个软件使用[Sauter](https://github.com/helson-lin/Sauter)。**

> 如果打包过程提示.DS_store 问题，需要通过命令删除一下。.gitignore 我忘记忽略了

本项目为教程：二次封装 inodeClinet 支持Macos15.

当然同类型的 pkg的安装包（非 flat）可以通过相同方式二次封装。

程序目录对应原包内的目录地址：

| 程序目录 | 原包目录地址 |
| ----------- | ----------- |
| iNodeClient | iNodeClient.pkg/Contents/Archive.pax/Applications/iNodeClient |
| lib | iNodeClient.pkg/Contents/Archive.pax/usr/local/lib |
|  Library | iNodeClient.pkg/Contents/Archive.pax/Library |
|  inodesys.conf | iNodeClient.pkg/Contents/Archive.pax/etc/iNode/inodesys.conf |
|  custom | iNodeClient.pkg/Contents/Archive.pax/Applications/iNodeClient/custom |




## 📦 二次封装支持Macos15

首先需要下载[Packages](http://s.sudre.free.fr/Software/Packages/about.html)软件。

`git clone`本项目之后，双击`fkInode.pkproj`使用 Packages软件打开。

### 📄 关于配置说明

![配置 app](./imgs/CleanShot%202024-12-02%20at%2021.57.03@2x.png)

![配置脚本](./imgs/CleanShot%202024-12-02%20at%2021.58.54@2x.png)

### 🔨 编译 Pkg

![编译运行](./imgs/CleanShot%202024-12-02%20at%2022.06.27@2x.png)

窗口左上角，点击“Build”-"Build And Run"-安装。

### 🐛 安装调试

![安装调试](./imgs/CleanShot%202024-12-02%20at%2022.18.12@2x.png)

## 免责声明

使用本项目所产生的所有风险由用户自行承担。我们不对因使用本项目而导致的任何直接、间接、偶然、特殊或后果性的损害负责，包括但不限于利润损失、数据丢失或其他经济损失。 责任限制：在适用法律允许的最大范围内，项目作者及贡献者对因使用或无法使用本项目而导致的任何损失不承担责任。

## License

此项目采用MIT开源协议。详情请查阅LICENSE文件。
  

## 捐助和支持

![sponsors](https://pic.kblue.site//sponsors.png)
