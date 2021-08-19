![](./docs/images/menu_logo_wecross.png)

# WeCross-Fabric2-Stub

[![CodeFactor](https://www.codefactor.io/repository/github/webankblockchain/WeCross-Fabric2-Stub/badge)](https://www.codefactor.io/repository/github/webankblockchain/WeCross-Fabric2-Stub) [![Build Status](https://travis-ci.org/WeBankBlockchain/WeCross-Fabric2-Stub.svg?branch=dev)](https://travis-ci.org/WeBankBlockchain/WeCross-Fabric2-Stub) [![Latest release](https://img.shields.io/github/release/WeBankBlockchain/WeCross-Fabric2-Stub.svg)](https://github.com/WeBankBlockchain/WeCross-Fabric2-Stub/releases/latest)
[![License](https://img.shields.io/github/license/WeBankBlockchain/WeCross-Fabric2-Stub)](https://www.apache.org/licenses/LICENSE-2.0) [![Language](https://img.shields.io/badge/Language-Java-blue.svg)](https://www.java.com)

WeCross Fabric2 Stub是[WeCross](https://github.com/WeBankBlockchain/WeCross)用于适配[Hyperledger Fabric 2](https://github.com/hyperledger/fabric/tree/release-2.0)及以上版本的插件。

## 关键特性

- Hyperledger Fabric配置加载
- Hyperledger Fabric账户生成
- Hyperledger Fabric链上资源访问
- Hyperledger Fabric交易签名与解析
- （适配中）通过WeCross部署链码

## 编译插件

**环境要求**:

  - [JDK8及以上](https://www.oracle.com/java/technologies/javase-downloads.html)
  - Gradle `5.0`及以上
  - golang `1.13.4`及以上（推荐采用国内源：`go env -w GOPROXY=https://goproxy.cn,direct`）

**编译命令**:

```shell
git clone https://github.com/WeBankBlockchain/WeCross-Fabric2-Stub.git
cd WeCross-Fabric2-Stub
./gradlew assemble
```

如果编译成功，将在当前目录的dist/apps目录下生成插件jar包。

## 插件使用

插件的详细使用方式请参阅[WeCross技术文档](https://wecross.readthedocs.io/zh_CN/latest/docs/stubs/fabric2.html)

## 项目贡献

欢迎参与WeCross社区的维护和建设：

- 提交代码(Pull requests)，可参考[代码贡献流程](CONTRIBUTING.md)以及[wiki指南](https://github.com/WeBankBlockchain/WeCross/wiki/%E8%B4%A1%E7%8C%AE%E4%BB%A3%E7%A0%81)
- [提问和提交BUG](https://github.com/WeBankBlockchain/WeCross/issues/new)

您将成为贡献者，感谢各位贡献者的付出：

<img src="https://contrib.rocks/image?repo=WeBankBlockchain/WeCross-Fabric2-Stub" alt="https://github.com/WeBankBlockchain/WeCross-Fabric2-Stub/graphs/contributors" style="zoom:100%;" />

## 开源社区

参与meetup：[活动日历](https://github.com/WeBankBlockchain/WeCross/wiki#%E6%B4%BB%E5%8A%A8%E6%97%A5%E5%8E%86)

学习知识、讨论方案、开发新特性：[联系微信小助手，加入跨链兴趣小组（CC-SIG）](https://wecross.readthedocs.io/zh_CN/latest/docs/community/cc-sig.html#id3)

## License

WeCross Fabric2 Stub的开源协议为Apache License 2.0，详情参考[LICENSE](./LICENSE)。

