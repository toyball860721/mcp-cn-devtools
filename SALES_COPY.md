# MCP CN DevTools - 爱发电商品详情页文案

## 商品名称
MCP CN DevTools 专业版 - 中文开发者内容搜索工具

## 商品描述

### 🎯 这是什么？

MCP CN DevTools 是一个 Model Context Protocol (MCP) 服务器，专为使用 AI 编程助手（Cline、Cursor、Claude Code）的中国开发者设计。

它让你能够直接在 AI 编程助手中搜索和获取中文技术社区的最新内容，无需离开编辑器。

### ✨ 核心功能

**免费版功能：**
- 🔍 跨平台搜索（掘金、知乎、V2EX、开源中国等）
- 📈 热点话题查询
- 📖 单篇文章获取
- 每日 10 次搜索限制

**专业版功能（¥29/月）：**
- ✅ 无限搜索次数
- ✅ 高级搜索过滤（时间范围、标签、作者、点赞数）
- ✅ 保存搜索和自动订阅
- ✅ 批量文章导出（Markdown/PDF）
- ✅ 实时热点推送
- ✅ 优先技术支持

### 🛠️ 技术规格

- 支持平台：macOS, Linux, Windows
- Node.js 版本：18+
- 兼容 MCP 客户端：Cline, Cursor, Claude Code, 及其他支持 MCP 的 AI 助手

### 📦 交付方式

购买后你将获得：
1. 专业版激活码（通过爱发电私信发送）
2. 详细安装和配置指南
3. 使用示例和最佳实践文档

### 🚀 快速开始

```bash
# 安装
npm install -g mcp-cn-devtools

# 在 MCP 配置中添加
{
  "mcpServers": {
    "cn-devtools": {
      "command": "npx",
      "args": ["-y", "mcp-cn-devtools@latest"]
    }
  }
}

# 激活专业版（购买后获得激活码）
mcp-cn-devtools activate YOUR_LICENSE_KEY
```

### 💡 使用场景

1. **技术调研**：快速查找某个技术话题的中文讨论和最佳实践
2. **热点追踪**：了解中文技术社区正在讨论什么
3. **内容创作**：收集素材写技术文章
4. **学习提升**：跟随领域专家的学习路径

### ⚠️ 注意事项

- 本工具遵守各平台 robots.txt 和使用条款
- 请勿用于大规模爬取或商业数据采集
- 专业版订阅自动续费，可随时取消

### 📞 支持

- GitHub Issues: https://github.com/toyball860721/mcp-cn-devtools/issues
- 邮件：shentaobj@qq.com
- 爱发电私信

---

**开发者**：Revenue Lobster (收益龙虾)  
**许可证**：MIT (开源) + 专业版订阅  
**更新日期**：2026-03-24
