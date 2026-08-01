# 项目文档

[中文](README.md) | [English](README.en.md)

这里是项目文档总入口。第一次使用插件从“用户路径”开始；修改代码、排查运行链路或准备发布时进入“维护者路径”。

## 用户路径

1. [安装说明](../README-install.md)：一行安装、Release 包、Docker 与常见 Python 环境问题。
2. [详细使用手册](user-guide.md)：配置、CLI、多 bot、多 profile、升级和排障。
3. [迁移说明](migration.md)：旧版本配置与安装状态迁移。
4. [V4.1 安全控制与排障](wiki/v4.1-safety-controls.md)：按群原生投递、runtime readiness、strict repair 与服务管理。

## 维护者路径

1. [架构说明](architecture.md)：sidecar-only 结构和模块职责。
2. [事件协议](event-protocol.md)：Hermes 事件、卡片状态和终态交接。
3. [安装安全](installer-safety.md)：patch、恢复、完整性与失败边界。
4. [端到端验证](e2e-verification.md)：预览材料、mock E2E 与真实飞书验收边界。
5. [测试说明](testing.md)：聚焦测试、完整测试和发布门禁。
6. [维护 Wiki](wiki/README.md)：hot files、事件流、真实飞书验收和发布手册。

## 发布与历史

- [CHANGELOG](../CHANGELOG.md) 是版本变化的总索引；`release-notes-v*.md` 是各版本的公开说明。
- [发布准备说明](release-readiness.md) 保存跨版本的验证证据和未覆盖边界，不作为当前功能入口。
- [V3.6.0 roadmap](roadmap-v3.6.0.md) 与 `superpowers/plans/`、`superpowers/specs/` 是历史设计和实施记录。当前行为以 README、用户手册、维护 Wiki 和代码测试为准。
- `legacy/` 是 V2 归档，不属于 active runtime。

## 英文文档

主要用户文档均提供同目录 `.en.md` 版本；从 [English documentation index](README.en.md) 进入。
