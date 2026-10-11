# 开源项目许可门槛

本项目借鉴或集成外部开源项目时，首选明确允许商业使用且尽量免署名的许可证：CC0-1.0、Unlicense、0BSD；次选 MIT、Apache-2.0、BSD-2-Clause、BSD-3-Clause、ISC、MPL-2.0（逐项审查）。

默认排除：未声明许可证、仅 source-available、非商业条款、个人使用条款、SSPL、Commons Clause，以及 AGPL/GPL 项目。GPL/AGPL 只有在明确评估其分发、网络服务和源码公开义务后，并得到用户明确选择，才可使用。

每个候选项目必须核对仓库中的 LICENSE、版权声明、第三方依赖许可证和当前版本；README 的描述不能替代许可证文本。借鉴设计思想不等于复制代码；复制代码必须保留适用的版权和许可证通知，并记录来源。

当前确认可作为研究候选：
- Little Lantern：CC0-1.0，项目声明可直接商用、修改和再发布，无需许可或署名；仅借鉴其本地数据和记忆界面设计。
- person-memory：MIT，可商用，但复制代码仍需保留版权和许可证声明。
- AliceMemory：MIT，可商用，但复制代码仍需保留版权和许可证声明。
- PersonalClaw：MIT，可商用，但不符合“完全不用引用”的最高标准。

当前排除：
- personal-ai-agent：AGPL-3.0-only，另有商业许可入口；除非取得适用商业许可，否则不纳入实现依赖。
- nanoMuse：GPL-3.0-or-later，不纳入实现依赖。
- Serenity、Layla：非商业或 source-available 条款，不纳入实现依赖。

注意：即使主项目使用 CC0/Unlicense，复制代码时仍需核查第三方依赖、模型、字体、图标和素材的许可证；“无需署名”不能自动覆盖依赖。