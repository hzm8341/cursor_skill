# Cursor Skills Collection

这是一个 Cursor Skills 集合仓库，包含了多个实用的 skills，可以在 Cursor 中使用。

## 什么是 Skills？

Skills 是包含 `SKILL.md` 文件的目录，提供了特定任务的详细指导。Cursor 的 oh-my-opencode 插件可以自动发现并加载这些 skills。

## 使用方法

### 方法一：使用同步脚本（推荐）

1. 克隆此仓库：
```bash
git clone https://github.com/hzm8341/cursor_skill.git
cd cursor_skill
```

2. 使用 OpenCode 项目提供的同步脚本：
```bash
# 从 OpenCode 项目运行
cd /path/to/opencode
./scripts/sync-skills.sh sync /path/to/cursor_skill
```

### 方法二：手动创建符号链接

```bash
# 创建目标目录
mkdir -p ~/.config/opencode/skill

# 为每个 skill 创建符号链接
cd ~/.config/opencode/skill
ln -s /path/to/cursor_skill/algorithmic-art algorithmic-art
ln -s /path/to/cursor_skill/docx docx
# ... 其他 skills
```

### 方法三：复制到标准目录

```bash
cp -r cursor_skill/* ~/.config/opencode/skill/
```

## 包含的 Skills

本仓库包含以下 skills：

- **algorithmic-art** - 使用 p5.js 创建算法艺术
- **brand-guidelines** - 应用品牌颜色和排版指南
- **canvas-design** - 创建精美的视觉设计
- **doc-coauthoring** - 文档协作工作流
- **docx** - Word 文档创建、编辑和分析
- **frontend-design** - 创建高质量的前端界面
- **internal-comms** - 内部通信写作资源
- **mcp-builder** - 创建 MCP 服务器指南
- **pdf** - PDF 操作工具包
- **pptx** - PowerPoint 演示文稿处理
- **skill-creator** - 创建新 skills 的工具
- **slack-gif-creator** - 创建 Slack GIF
- **theme-factory** - 主题工厂
- **webapp-testing** - Web 应用测试
- **web-artifacts-builder** - Web 工件构建器
- **xlsx** - Excel 文件处理

## Skills 结构

每个 skill 目录包含：

- `SKILL.md` - Skill 定义文件（必需）
- `LICENSE.txt` - 许可证文件（可选）
- `scripts/` - 相关脚本（可选）
- 其他资源文件

## 跨设备同步

### 使用 Git

1. 在每台设备上克隆仓库
2. 运行同步脚本创建符号链接

### 使用云存储

将仓库放在云存储中（如 Dropbox、OneDrive），然后在每台设备上创建符号链接。

## 更多信息

详细使用指南请参考：[Cursor Skills 使用指南](https://github.com/hzm8341/opencode/blob/main/docs/Cursor_Skills_使用指南_v1.0_20250116_AI.md)

## 许可证

各个 skill 可能有不同的许可证，请查看每个 skill 目录中的 `LICENSE.txt` 文件。

## 贡献

欢迎提交 Issue 和 Pull Request！

---

**最后更新**: 2025-01-16

