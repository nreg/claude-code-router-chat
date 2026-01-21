# 🚀 Claude Code Router Chat

[![VS Code Extension](https://img.shields.io/badge/VS%20Code-Extension-blue?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=andrepimenta.claude-code-chat)
[![Claude Code](https://img.shields.io/badge/Powered%20by-Claude%20Code-orange?style=for-the-badge)](https://claude.ai/code)
[![TypeScript](https://img.shields.io/badge/Built%20with-TypeScript-3178C6?style=for-the-badge&logo=typescript)](https://www.typescriptlang.org/)

> **不再需要终端命令。通过一个美丽直观的界面，在VS Code内部直接与Claude Code聊天。**

告别命令行，体验前所未有的Claude Code。此扩展程序将令人惊叹的聊天界面直接带入您的编辑器，使AI辅助变得触手可及、可视化且愉快。

🤖 **由Claude Code为Claude Code打造** - 此扩展完全使用Claude Code本身开发。Claude Code创建了自己的聊天界面！

---

## ✨ **为什么选择Claude Code Router Chat？**

🖥️ **无需终端** - 美观的聊天界面替代命令行交互

⏪ **恢复检查点** - 撤销更改并恢复到任何先前状态

🔌 **MCP Server支持** - 完整的Model Context Protocol服务器管理

💾 **对话历史** - 自动对话历史记录和会话管理

🎨 **VS Code原生** - Claude Code直接集成到VS Code中，具有原生主题和侧边栏支持

🧠 **计划和思维模式** - 计划优先和可配置的思维模式以获得更好的结果

⚡ **智能文件/图像上下文和自定义命令** - 引用任何文件，粘贴图片或屏幕截图并创建自定义命令

🤖 **模型选择** - 根据您的需求在Opus、Sonnet或默认模型之间选择

🐧 **Windows/WSL支持** - 完整的原生Windows和WSL支持

---

## 🌟 **核心功能**

### 💬 **美丽的聊天图形界面**
- 无需终端 - 所有操作通过UI完成
- 实时流式响应和打字指示器
- 一键消息复制并显示视觉反馈
- 增强的markdown支持和语法高亮
- 自适应输入框，根据内容自动调整大小
- 代码块复制到剪贴板

### ⏪ **检查点和会话管理**
- **恢复检查点** - 立即撤销更改并恢复到任何先前状态
- 基于Git的自动备份系统以确保安全实验
- 浏览并从任何对话检查点恢复
- 自动对话保存和恢复
- 实时成本和令牌跟踪
- 会话统计和性能指标

### 📝 **内联Diff查看器** ⭐ **V1.1新增**
- **完整Diff显示** - 在编辑、多编辑和写入消息中直接查看完整文件更改
- **在VS Code Diff中打开** - 一键按钮打开VS Code的原生并排diff编辑器
- **智能截断** - 长diff被截断并带有展开按钮以提高可读性
- **语法高亮** - diff视图中的正确代码高亮
- **视觉变更指示器** - 清晰的绿色/红色高亮显示添加和删除

### 🔌 **MCP服务器管理** ⭐ **V1.0新增**
- **流行服务器库** - 一键安装常见的MCP服务器
- **自定义服务器创建** - 构建和配置自己的MCP服务器
- **服务器管理** - 通过UI编辑、删除、启用/禁用服务器
- **自动集成** - 无缝权限和工具集成
- **跨平台支持** - 完整的WSL兼容性与路径转换

### 🔒 **高级权限系统** ⭐ **V1.0新增**
- **交互式权限对话框** - 详细的工具信息和命令预览
- **始终允许功能** - 智能命令模式匹配常见工具（npm、git、docker）
- **YOLO模式** - 跳过所有权限检查以供高级用户使用
- **工作区权限** - 对什么工具可以执行的细粒度控制
- **实时权限管理** - 通过直观的UI添加/删除权限

### 🖼️ **图像和剪贴板支持** ⭐ **V1.0新增**
- **拖放图像** - 直接将图像拖入聊天
- **剪贴板粘贴** - 按Ctrl+V粘贴屏幕截图和复制的图像
- **多图像选择** - 通过VS Code的文件选择器选择多个图像
- **组织存储** - 自动在`.claude/claude-code-router-chat-images/`中组织
- **格式支持** - PNG、JPG、JPEG、GIF、SVG、WebP、BMP格式

### 📱 **侧边栏集成** ⭐ **V1.0新增**
- **原生VS Code侧边栏** - 侧边栏面板中的完整聊天功能
- **智能面板管理** - 在主视图和侧边栏视图间自动切换
- **持久会话** - 面板切换时保持状态
- **活动栏集成** - 通过VS Code的活动栏快速访问

### 📁 **智能文件集成**
- 输入`@`即可即时搜索和引用工作区文件
- 通过文件浏览器和复制粘贴屏幕截图附加图像
- 跨整个项目的闪电般快速文件搜索
- 多文件讨论中无缝保持上下文

### 🛠️ **工具管理**
- 可视化仪表板显示所有可用的Claude Code工具
- 实时工具执行和格式化结果
- 进程控制 - 启动、停止和监控操作
- 智能权限系统用于安全工具执行

### 🎨 **VS Code集成**
- 匹配您编辑器的原生主题
- 状态栏集成连接状态
- 活动栏面板快速访问
- 响应式设计适用于任何屏幕尺寸

### 🤖 **模型选择**
- **Opus** - 最强大的模型，适合需要深度推理的复杂任务
- **Sonnet** - 平衡模型，为大多数用例提供出色性能
- **默认** - 使用您配置的模型设置
- 模型偏好在会话间保持并自动保存
- 通过聊天界面中的下拉选择器轻松切换
- 切换模型时的视觉确认
- 通过集成终端一键模型配置

### ⚡ **斜杠命令集成**
- **斜杠命令模态框** - 输入"/"即可访问所有Claude Code命令
- **23+内置命令** - /agents、/cost、/config、/memory、/review等
- **自定义命令支持** - 在会话上下文中执行任何Claude Code命令
- **会话感知执行** - 所有命令都在当前对话上下文中运行
- **终端集成** - 命令直接在VS Code终端中打开，支持WSL

### 🧠 **高级AI模式**
- **计划优先模式** - 切换以使Claude在实施更改前先计划
- **思维模式** - 可配置的强度级别（Think、Think Hard、Think Harder、Ultrathink）
- **模式切换** - 文本输入区域上方的简单开关
- **智能提示** - 根据选定的思维强度级别使用不同提示
- **令牌意识** - 更高的思维级别消耗更多令牌但提供更深层的推理

---

## 🚀 **入门指南**

### 先决条件
- **VS Code 1.80+** - 推荐最新版本
- **Claude Code Router CLI** - [从Claude Code Router安装](https://github.com/musistudio/claude-code-router)
- **活跃的Claude API或订阅** - API或Pro/Max计划
```
   npm install -g @musistudio/claude-code-router --registry=https://registry.npmmirror.com
   ccr ui
```
### 安装

1. **从VS Code市场安装**
   ```
   ext install claude-code-router-chat
   ```

2. **或手动安装**
   - 从发布页面下载`.vsix`文件
   - 运行`code --install-extension claude-code-router-chat-x.x.x.vsix`

3. **打开Claude Code Router Chat**
   - 按`Ctrl+Shift+C`（Mac上按`Cmd+Shift+C`）
   - 或点击状态栏中的Claude图标
   - 或使用命令面板：`Claude Code: Open Chat`

---

## 💡 **使用示例**

### 🔥 **代码审查和重构**
```
You: @src/components/UserProfile.tsx 你能审查这个组件并提出改进建议吗？

Claude: 我将分析您的UserProfile组件。查看代码，这里有我的建议：

1. **性能优化**：添加React.memo()以防止不必要的重新渲染
2. **TypeScript增强**：props接口可以更加具体
3. **可访问性**：缺少屏幕阅读器的ARIA标签

[详细的分析和代码示例...]
```

### 📊 **项目分析**
```
You: 分析我的项目的整体架构并识别潜在问题

Claude: 我将检查您的项目结构并识别改进区域：

🏗️ **架构概述**
- 使用TypeScript的React前端
- 使用Express的Node.js后端
- MongoDB数据库层

⚠️ **已识别问题**
- React组件中缺少错误边界
- 数据库查询缺少适当的索引
- API路由缺少输入验证

[详细建议和实施示例...]
```

### 🐛 **调试助手**
```
You: 我的API出现了奇怪的错误。这是堆栈跟踪：[粘贴错误]

Claude: 看起来这个堆栈跟踪显示的是您的异步中间件中的竞态条件。发生的情况是：

1. **根本原因**：多个请求正在修改共享状态
2. **解决方案**：实现正确的请求隔离
3. **预防措施**：添加全面的错误处理

[逐步调试指南...]
```

### ⏪ **使用检查点的安全实验**
```
You: 你能将这个完整的组件重构为使用hooks而不是类组件吗？

Claude: 我将重构您的组件以使用React hooks。不用担心 - 我会先创建一个检查点，这样您就可以轻松恢复。

[自动创建检查点]

这里是使用hooks重构的组件：
[显示新的实现]

如果您想恢复这些更改，只需点击"恢复检查点"即可立即回到原始代码。
```

---

## ⚙️ **配置**

### 键盘快捷键
| 快捷键 | 动作 |
|----------|--------|
| `Ctrl+Shift+C` | 打开Claude Code Router Chat |
| `Enter` | 发送消息 |
| `@` | 打开文件选择器 |
| `/` | 打开斜杠命令模态框 |

### WSL配置（Windows用户）
如果您通过WSL（Windows子系统Linux）使用Claude Code，可以配置扩展程序使用WSL：

1. 打开VS Code设置（`Ctrl+,`或`Cmd+,`）
2. 搜索"Claude Code Router Chat"
3. 配置这些设置：
   - **Claude Code Router Chat: WSL Enabled** - 启用WSL集成
   - **Claude Code Router Chat: WSL Distro** - 您的WSL发行版名称（例如`Ubuntu`、`Debian`）
   - **Claude Code Router Chat: WSL Node Path** - WSL中的Node.js路径（默认：`/usr/bin/node`）
   - **Claude Code Router Chat: WSL Claude Path** - WSL中的Claude路径（默认：`ccr code`）

`settings.json`中的示例配置：
```json
{
"claudeCodeChat.wsl.enabled": true,
"claudeCodeChat.wsl.distro": "Ubuntu",
"claudeCodeChat.wsl.nodePath": "/usr/bin/node",
"claudeCodeChat.wsl.claudePath": "ccr code"
}
```

---

## 🎯 **专业提示和技巧**

### 🔥 **文件上下文魔法**
- 输入`@`后跟搜索词可快速引用文件
- 使用`@src/`缩小到特定目录
- 在一条消息中引用多个文件进行跨文件分析
- **新增**：直接将图像复制粘贴到聊天中以获得视觉上下文
- **新增**：使用Ctrl+V粘贴屏幕截图以实现即时视觉通信

### ⚡ **生产力提升器**
- **在更改前自动创建检查点**以进行安全实验
- **如果更改不符合预期可立即恢复**
- **新增**：权限系统防止意外工具执行
- **新增**：YOLO模式供希望速度超过安全性的高级用户
- 使用停止按钮取消长时间运行的操作
- 复制消息内容以重复使用Claude的响应
- 打开历史面板以参考之前的对话
- **新增**：侧边栏集成以实现多面板工作流程

### 🎨 **界面定制**
- UI会自动适应您的VS Code主题
- 消息颜色编码：绿色代表您，蓝色代表Claude
- 鼠标悬停在消息上显示复制按钮
- **新增**：增强的代码块渲染和语法高亮
- **新增**：代码块的复制到剪贴板功能

---

## 🔧 **高级功能**

### 🛠️ **工具集成**
Claude Code Router Chat提供对所有Claude Code工具的安全访问：
- **Bash** - 执行shell命令并进行权限控制
- **文件操作** - 读取、写入和编辑文件
- **搜索** - 在工作区中进行grep和glob模式匹配
- **Web** - 获取和搜索网络内容
- **多编辑** - 批量文件修改
- **MCP服务器** - 通过Model Context Protocol服务器扩展功能
- **权限系统** - 细粒度控制工具执行以确保安全

### 📊 **分析和监控**
- **实时成本追踪** - 监控API使用情况
- **令牌消耗** - 查看输入/输出令牌数量
- **响应时间** - 跟踪性能指标
- **会话统计** - 全面的使用分析

### ⏪ **检查点系统**
- **即时恢复** - 一键恢复到任何先前状态
- **对话检查点** - 每个更改都创建一个恢复点
- **视觉时间线** - 查看并导航所有项目状态

### 🔄 **对话历史**
- **自动保存** - 每个对话都被保存
- **智能恢复** - 在您离开的地方继续
- **在聊天间切换** - 轻松查看和切换到之前的对话

---

## 🤝 **贡献**

我们欢迎贡献！以下是您可以帮助的方式：

1. **🐛 报告Bug** - 使用我们的问题跟踪器
2. **💡 提出功能建议** - 分享您的想法
3. **🔧 提交PR** - 帮助我们改进代码库
4. **📚 改进文档** - 让文档变得更好

### 开发设置
```bash
git clone https://github.com/nreg/claude-code-router-chat
cd claude-code-router-chat
npm install

点击"F5"运行扩展或在VSCode中访问"Run and Debug"部分
```

---

## 📝 **许可证**

详情见[LICENSE](LICENSE)文件。

---

## 🙏 **致谢**

- **Anthropic** - 为创建出色的Claude AI以及特别是Claude Code SDK
- **VS Code团队** - 为令人难以置信的扩展平台
- **[Claude Code Router](https://github.com/musistudio/claude-code-router)** 团队 - 为开源精神
- **[Claude Code Chat](https://github.com/andrepimenta/claude-code-chat)** 团队 - 为开源精神
- **我们的社区** - 为反馈、建议和贡献

