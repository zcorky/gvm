# GVM - Go Version Manager

[![Release](https://img.shields.io/github/tag/zmicro-design/plugin-gvm.svg?label=Release)](https://github.com/zmicro-design/plugin-gvm/tags)
[![Build Status](https://github.com/zmicro-design/plugin-gvm/actions/workflows/ci.yml/badge.svg?branch=master)](https://github.com/zmicro-design/plugin-gvm/actions/workflows/ci.yml)
[![GitHub issues](https://img.shields.io/github/issues/zmicro-design/plugin-gvm.svg)](https://github.com/zmicro-design/plugin-gvm/issues)


## Installation

```bash
# CURL
curl -o- https://raw.githubusercontent.com/zcorky/zgvm/master/install | bash

# WGET
wget -qO- https://raw.githubusercontent.com/zcorky/zgvm/master/install | bash
```

## Usage

```markdown
Go Version Manager (v1.0.6)

Go Version Manager is a tool for managing multiple Go versions.

Usage:
  zgvm install <version>   - Install Go version
  zgvm use <version>       - Use Go version
  zgvm remove <version>    - Remove Go version
  zgvm ls                  - List all Go versions
  zgvm ls-remote           - Show current Go version
  zgvm current             - Show current Go version
  zgvm help                - Show help

Example:
  zgvm install v1.18
  zgvm use v1.18
  zgvm remove v1.18
  zgvm ls
  zgvm ls-remote
  zgvm current
```

## FAQ
* 1. 问题：`zgvm: command not found`
  * 解决方案 1：`执行 source 重写加载环境变量`
  * 解决方案 2：`重启你的 terminal`
  * 解决方案 3：执行 `zmicro register` 重写注册环境，然后重新走解决方案 1 或 2

## License
ZMicro Design is released under the [MIT License](./LICENSE).
