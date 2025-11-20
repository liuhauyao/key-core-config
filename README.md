# Key Core Config

密枢（Key Core）项目的公开配置更新仓库。

## 关于密枢（Key Core）

密枢（Key Core）是一款 macOS 平台的 AI 密钥管理工具，主要功能包括：

- **密钥管理**: 安全存储和管理各种 AI 平台的 API 密钥
- **密钥模板**: 提供丰富的密钥模板，支持 ClaudeCode、Codex、Gemini 等 AI 工具
- **MCP 服务器配置**: 管理和配置 MCP（Model Context Protocol）服务器
- **多工具支持**: 支持 Cursor、ClaudeCode、Codex、Windsurf、Cline、Gemini 等 AI 开发工具

## 仓库说明

本仓库是密枢（Key Core）的配置更新仓库，用于存储和管理：

- 密钥模板配置（providers）
- MCP 服务器模板配置（mcpServerTemplates）
- Codex 认证配置规则（codexAuthConfig）

应用会自动从本仓库获取最新配置并更新到用户本地，无需重新安装应用即可获得最新的密钥模板和 MCP 服务器模板。

## 配置文件

- `app_config.json`: 主配置文件，包含所有密钥模板和 MCP 服务器模板配置

## 配置更新

配置文件更新后，密枢应用会在以下情况自动检查并更新：

- 应用启动时（异步检查，不阻塞启动）
- 距离上次检查超过 24 小时
- 手动触发更新检查

## 仓库地址

- **GitHub**: https://github.com/liuhuayao/key-core-config
- **Gitee**: https://gitee.com/liuhuayao/key-core-config（国内镜像）
