# GVM - Go Version Manager

[![Release](https://img.shields.io/github/tag/zmicro-design/plugin-gvm.svg?label=Release)](https://github.com/zmicro-design/plugin-gvm/tags)
[![Build Status](https://github.com/zmicro-design/plugin-gvm/actions/workflows/ci.yml/badge.svg?branch=master)](https://github.com/zmicro-design/plugin-gvm/actions/workflows/ci.yml)
[![GitHub issues](https://img.shields.io/github/issues/zmicro-design/plugin-gvm.svg)](https://github.com/zmicro-design/plugin-gvm/issues)


## Installation

```bash
# CURL
curl -o- https://raw.githubusercontent.com/zcorky/gvm/master/install | bash

# WGET
wget -qO- https://raw.githubusercontent.com/zcorky/gvm/master/install | bash
```

## Usage

```markdown
Go Version Manager (v1.3.7)

Go Version Manager is a tool for managing multiple Go versions.

Usage:
  gvm install <version>   - Install Go version
  gvm use <version>       - Use Go version
  gvm remove <version>    - Remove Go version
  gvm ls                  - List the Go versions installed
  gvm ls-remote           - List all Go versions from remote
  gvm current             - Show current Go version
  gvm exec                - Enter new shell with go version for tmp
  gvm help                - Show help

Example:
  gvm install v1.18
  gvm use v1.18
  gvm remove v1.18
  gvm ls
  gvm ls-remote
  gvm current
```

## FAQ
* 1. 问题：`zgvm: command not found`
  * 解决方案 1：`执行 source 重写加载环境变量`
  * 解决方案 2：`重启你的 terminal`
  * 解决方案 3：执行 `zmicro register` 重写注册环境，然后重新走解决方案 1 或 2

## License
ZMicro Design is released under the [MIT License](./LICENSE).
