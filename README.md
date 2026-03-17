# javazd

ZD 是一种类似 Python 的解释性脚本语言，使用 Java 实现，设计目标是简洁易用。
本仓库包含 ZD 解释器的 Java 实现、示例脚本以及构建配置。

## 快速开始

1. 构建项目（使用 Maven）：
   ```bash
   mvn clean package
   ```

2. 运行解释器（示例）：
   ```bash
   java -jar target/javazd-1.0-SNAPSHOT.jar examples/example.zd
   ```

## 项目结构

- src/main/java/... : Java 源码
- examples/ : ZD 示例脚本
- pom.xml : Maven 构建文件

## 贡献

欢迎提交 issue 与 pull request。详情见 CONTRIBUTING.md。
