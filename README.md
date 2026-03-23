# MCP CN DevTools

MCP 服务器，连接 AI 编程助手（Cline、Cursor、Claude Code）与中国开发者平台。

## 功能

- 🔍 **跨平台搜索**：一键搜索稀土掘金、知乎、V2EX、开源中国等技术社区
- 📈 **热点追踪**：实时获取中文技术社区热门话题
- 📖 **文章获取**：自动抓取并整理文章全文内容
- 👤 **作者分析**：查看技术作者档案和其他作品

## 安装

```bash
npm install -g mcp-cn-devtools
```

或在你的 MCP 配置中添加：

```json
{
  "mcpServers": {
    "cn-devtools": {
      "command": "npx",
      "args": ["-y", "mcp-cn-devtools"]
    }
  }
}
```

## 使用示例

### 搜索技术文章

```
搜索 "MCP 协议" 在掘金平台的文章
```

### 获取热点话题

```
获取 AI 类别的热点话题
```

### 阅读文章

```
读取这篇文章的全文：https://juejin.cn/post/xxx
```

## 定价

### 免费版
- 每日 10 次搜索
- 基础热点查询
- 单篇文章获取

### 专业版 ¥29/月
- 无限搜索
- 高级过滤（时间、标签、作者）
- 保存搜索和订阅
- 批量文章导出
- 优先支持

## 购买专业版

访问 [爱发电](https://afdian.com/a/toyball/shop) 购买专业版兑换码。

## 开发

```bash
# 安装依赖
npm install

# 开发模式
npm run dev

# 构建
npm run build

# 测试
npm test
```

## 技术栈

- TypeScript
- @modelcontextprotocol/sdk
- Node.js 18+

## 许可证

MIT License

## 作者

Revenue Lobster (收益龙虾)

## 贡献

欢迎提交 Issue 和 Pull Request！

---

**注意**：本工具遵守各平台 robots.txt 和使用条款。请勿用于大规模爬取或商业用途。
