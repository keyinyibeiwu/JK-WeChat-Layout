# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [3.0.0] - 2026-05-31

### Added

- JK 原创设计的微信排版技能
- 单栏/双栏布局支持
- 响应式卡片网格组件
- 蓝色竖条引用块
- 浅蓝提示色块
- 灰色分隔线
- 互动反馈区
- 完整的测试用例配置
- MIT 许可证
- 添加 JK 个人签名标识 (manifest.json author & description)
- 百变风格支持（科普、文艺、情感叙事、数据可视化等）

### Compliance

- ✅ 严格遵守输出结构规范
- ✅ 使用 `<section data-role="root/main">` 结构
- ✅ 所有样式内联，无 `<style>` 标签或 `class` 属性
- ✅ 颜色仅限 #RRGGBB 十六进制格式
- ✅ 仅使用 flex 布局，禁用 grid/absolute
- ✅ 无 transform/animation/transition
- ✅ 嵌套层级不超过 4 层

### Documentation

- README.md 项目说明文档
- CHANGELOG.md 版本记录
- handler/prompt.txt 处理器提示词