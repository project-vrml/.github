# Project VRML

<p align="center">
  <img src="https://github.com/project-vrml/vrml/raw/master/resources/logo.png" alt="VRML Logo" width="120">
</p>

<p align="center">
  <b>Multi-Language Application Runtime API Library</b>
</p>

<p align="center">
  <a href="https://github.com/project-vrml/vrml/stargazers"><img src="https://img.shields.io/github/stars/project-vrml/vrml?style=flat-square" alt="Stars"></a>
  <a href="https://github.com/project-vrml/vrml/network/members"><img src="https://img.shields.io/github/forks/project-vrml/vrml?style=flat-square" alt="Forks"></a>
  <a href="https://github.com/project-vrml/vrml/blob/master/LICENSE"><img src="https://img.shields.io/github/license/project-vrml/vrml?style=flat-square" alt="License"></a>
</p>

---

## 🌟 Vision

**VRML** (读作: [ver, mao]) 是一组高级抽象的应用运行时 API 库，旨在提供跨平台、跨框架的通用工具解决方案。

我们的目标是成为 [Cloud-Runtimes](https://github.com/capa-cloud/cloud-runtimes-jvm) 标准 API 的实现部分，为分布式应用运行时贡献功能。

## 🏗️ Architecture

<p align="center">
  <img src="https://github.com/project-vrml/vrml/raw/master/resources/vrml-architecture.png" alt="VRML Architecture" width="800">
</p>

## 📦 Ecosystem

### Core Libraries

| Project | Language | Description | Stars |
|---------|----------|-------------|-------|
| [**vrml**](https://github.com/project-vrml/vrml) | ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=java&logoColor=white) | Java 应用运行时 API 库 (Java 8+) | ![Stars](https://img.shields.io/github/stars/project-vrml/vrml?style=flat-square) |
| [**vrml-cloudruntimes**](https://github.com/project-vrml/vrml-cloudruntimes) | ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=java&logoColor=white) | Cloud-Runtimes 集成实现 | ![Stars](https://img.shields.io/github/stars/project-vrml/vrml-cloudruntimes?style=flat-square) |
| [**pyvrml**](https://github.com/project-vrml/pyvrml) | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) | Python 实用脚本工具库 | ![Stars](https://img.shields.io/github/stars/project-vrml/pyvrml?style=flat-square) |

### Multi-Language Implementations

| Language | Project | Status |
|----------|---------|--------|
| ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) | [gvrml](https://github.com/project-vrml/gvrml) | 🚧 Experimental |
| ![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white) | [ktvrml](https://github.com/project-vrml/ktvrml) | 🚧 Experimental |
| ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) | [jsvrml](https://github.com/project-vrml/jsvrml) | 🚧 Experimental |
| ![Lua](https://img.shields.io/badge/Lua-2C2D72?style=flat-square&logo=lua&logoColor=white) | [luvrml](https://github.com/project-vrml/luvrml) | 🚧 Experimental |
| ![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white) | [rsvrml](https://github.com/project-vrml/rsvrml) | 🚧 Experimental |
| ![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=c-sharp&logoColor=white) | [csvrml](https://github.com/project-vrml/csvrml) | 🚧 Experimental |
| ![Erlang](https://img.shields.io/badge/Erlang-A90533?style=flat-square&logo=erlang&logoColor=white) | [ervrml](https://github.com/project-vrml/ervrml) | 🚧 Experimental |
| ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white) | [cpvrml](https://github.com/project-vrml/cpvrml) | 🚧 Experimental |
| ![Scala](https://img.shields.io/badge/Scala-DC322F?style=flat-square&logo=scala&logoColor=white) | [scvrml](https://github.com/project-vrml/scvrml) | 🚧 Experimental |
| ![Haskell](https://img.shields.io/badge/Haskell-5D4F85?style=flat-square&logo=haskell&logoColor=white) | [hkvrml](https://github.com/project-vrml/hkvrml) | 🚧 Experimental |

### Proxy & API Server

| Project | Description |
|---------|-------------|
| [vrml-proxy](https://github.com/project-vrml/vrml-proxy) | VRML 代理服务 |
| [vrml-apiserver](https://github.com/project-vrml/vrml-apiserver) | VRML API 服务器 |
| [pyvrml-proxy](https://github.com/project-vrml/pyvrml-proxy) | Python 代理实现 |
| [jsvrml-proxy](https://github.com/project-vrml/jsvrml-proxy) | JavaScript 代理实现 |
| [gvrml-proxy](https://github.com/project-vrml/gvrml-proxy) | Go 代理实现 |

## 🔑 Key Features

### Core Concepts

- **面向接口编程** - 定义与框架/平台/实现无关的 API
- **模块化设计** - 按需引入，灵活组合
- **Cloud-Native** - 支持多种云运行时平台
- **多语言支持** - 跨语言生态覆盖

### VRML Java Modules

```
📊 Monitoring    : metric, log, alert, trace
💾 Data         : data, cache, error, resource
🌐 Network      : request, eventbus, netty, reactor
🔧 Utilities    : reflect, time, switch, compute, spi, ...
```

## 🚀 Quick Start

### Java

```xml
<dependency>
    <groupId>group.rxcloud</groupId>
    <artifactId>vrml</artifactId>
    <version>1.1.4</version>
    <type>pom</type>
    <scope>import</scope>
</dependency>
```

### Python

```bash
pip install pyvrml
```

## 🌐 Cloud-Runtimes Integration

VRML 支持多种 Cloud-Runtimes 平台：

- [CAPA](https://github.com/capa-cloud/capa)
- [Layotto](https://github.com/mosn/layotto)
- [Dapr](https://github.com/dapr/dapr)

## 📚 Documentation

- [VRML Wiki](https://github.com/project-vrml/vrml/wiki)
- [API Documentation](https://github.com/project-vrml/vrml/blob/master/README.md)
- [中文文档](https://github.com/project-vrml/vrml/blob/master/README_CN.md)

## 🤝 Contributing

我们欢迎各种形式的贡献！请查看我们的 [贡献指南](https://github.com/project-vrml/vrml/blob/master/CONTRIBUTING.md)。

## 📄 License

所有项目均采用 [Apache 2.0](https://github.com/project-vrml/vrml/blob/master/LICENSE) 许可证。

---

<p align="center">
  <b>Write Once, Run Anywhere</b>
</p>
