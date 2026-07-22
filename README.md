# Backend Dev Guide — 后端高级开发工程师方案产出指南

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-1.0.0-green.svg)](SKILL.md)

一个面向 AI 编程助手的 **后端开发工程师 Skill**，将后端工程方法论转化为可执行工作流。自动识别 5 类场景（0→1 新后端服务 / 模块开发 / Bug修复 / 架构重构 / 预研），按对应清单产出系统架构、API设计、数据库Schema、缓存策略、安全方案、灾备方案等完整技术文档。

## 适用场景

| 场景 | 示例 | 产出量 |
|------|------|:---:|
| 0→1 新后端服务 | 全新微服务搭建 | 10-12类 |
| 中大型功能/模块 | CRM 新增订单核心API模块 | 6-8类 |
| 小优化/Bug修复 | 慢查询优化 | 2-3类 |
| 大版本重构/升级 | 单体拆微服务 | 8-10类 |
| 技术预研/选型 | 新语言/框架评估 PoC | 3-4类 |

## 触发热词

后端开发、后端架构、API设计、数据库设计、系统架构、微服务、后端技术选型、缓存方案、消息队列、后端方案

---

## 安装

本 Skill 遵循 **Open Agent Skills 标准**（SKILL.md 格式），兼容以下工具：

### WorkBuddy / CodeBuddy

**方式一：克隆到 skills 目录**
```bash
# 克隆到 workbuddy skill 目录（全局可用）
git clone https://github.com/genapohub/backend-dev-guide.git ~/.workbuddy/skills/backend-dev-guide
```

**方式二：ZIP导入**
```bash
# 先下载并打包
git clone https://github.com/genapohub/backend-dev-guide.git
zip -r backend-dev-guide.zip backend-dev-guide/
```
然后在 WorkBuddy 桌面端 → **技能市场** → **添加技能/上传技能** → **点击"跳过检测，直接安装"**。

### Trae

**ZIP 导入**
```bash
# 先下载并打包
git clone https://github.com/genapohub/backend-dev-guide.git
```
然后在 Trae → **设置** → **Rules & Skills** → **创建** → 上传 `backend-dev-guide.zip`。

### Codex

```bash
# 克隆到 skills 目录
git clone https://github.com/genapohub/backend-dev-guide.git ~/.codex/skills/backend-dev-guide

# 或使用 cc switch (推荐)
git clone https://github.com/genapohub/backend-dev-guide.git ~/.cc-switch/skills/backend-dev-guide
```

重启 CC Switch客户端/Codex客户端 后自动发现。也可以在对话中输入 `$backend-dev-guide` 手动调用。

### Cursor
```bash
# 克隆到 skills 目录
git clone https://github.com/genapohub/backend-dev-guide.git ~/.cursor/skills-cursor/backend-dev-guide
```

重启 Cursor客户端 后自动发现。也可以在对话中输入 `$backend-dev-guide` 手动调用。

---

## 使用

```
帮我设计一个新订单系统的后端架构
用户中心的 API 模块方案怎么出
这个慢查询怎么优化
从单体迁移到微服务，出个架构升级方案
```

---

## 目录结构

```
backend-dev-guide/
├── SKILL.md                  # 主指令
├── README.md
├── LICENSE
├── .gitignore
└── references/
    └── 后端开发方法论.md       # 详细方法论
```

## 许可

[MIT](LICENSE) © zhangmengbo
