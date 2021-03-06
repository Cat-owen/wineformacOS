# Wine for macOS

wine for macOS

## 简介

本仓库并非wine官方仓库，为为支持wine在macOS10.15以及更远的版本中使用，定期从wine官方源码包中编译打包

## 弊端

因为macOS在10.15后删除了一切对32位的支持，因此此wine完全由64位编辑，其弊端就是无法运行32位的Windows程序，如果需要，请使用虚拟机

## 使用条约

除了您需要遵守wine的全部条约外，您还需要注意，本软件仓库所有者不对本软件所造成的任何损害做任何责任承担，您在使用前必须了解不当操作甚至是遵守使用说明所导致的一切后果，并仓库所有者不负任何责任，但可以通过Issues进行报告，您在使用前请务必进行安全性检查，以保证该发布版本未被篡改，您使用本软件即代表您遵循本条约，并本条约应按照简体中文版本进行约束，其他语言版本仅供方便阅读

## 许可证

wine本体为自由软件，故本编译版本也为自由软件，本仓库所有者对仓库中的wine软件包不拥有任何所有权，一切软件包版权均应按照[wine官网的声明](https://wiki.winehq.org/Licensing)进行

## 使用

从本仓库发布的wine应当先自行对软件进行检查，并查看是否有病毒与软件中，因为虽然本软件编译者（即仓库拥有者）不会加入任何有害代码，但为了安全，请务必自行检查

### 自行编译

自行编译并不困难，但您需要：

1. gcc
2. macports（用于安装bison）

可选的：

1. bison（即使您不安装发布的处理程序也会自动安装）
2. wine的源码包（同上）

您需要sudo 并运行发布的处理程序，随后会自动完成编译并启动wine

### 使用发布的已编译版本

仅需将发布的软件包添加到path即可从终端启动
