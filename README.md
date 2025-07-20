# 🎨 Reveal.js 双主题演示系统

<div align="center">

**🌞 白色商务 + 🌙 黑色极客 | 专为不同场景设计的现代化演示系统**

[![Reveal.js](https://img.shields.io/badge/Reveal.js-5.2.1-ff6b6b?style=for-the-badge&logo=reveal.js)](https://revealjs.com/)
[![主题系统](https://img.shields.io/badge/双主题系统-Ready-4ECDC4?style=for-the-badge&logo=palette)](./themes/)
[![Demo](https://img.shields.io/badge/Live_Demo-在线演示-27ae60?style=for-the-badge&logo=googlechrome)](https://bigsweetpotatostudio.github.io/ai-ppt-tutorial/)

*一套代码，双重体验 | 商务演示与技术分享的完美解决方案*

</div>

---

## 🎯 主题选择系统

<table>
<tr>
<td width="50%" align="center">

### 🌞 **白色商务主题**

**适用场景**
- 商务演示、学术演讲
- 培训教学、投影环境
- 正式会议、客户汇报

**设计特色**
- 毛玻璃效果、专业正式
- 语义化色彩、投影兼容
- Shimmer扫光、粒子浮动

[📖 详细规范](./themes/white-theme.md)

</td>
<td width="50%" align="center">

### 🌙 **黑色极客主题**

**适用场景**
- 技术分享、产品发布
- 创意展示、暗场环境
- 开发者大会、科技产品

**设计特色**
- 霓虹发光、赛博网格
- 故障效果、终端风格
- 量子浮动、扫描线

[📖 详细规范](./themes/dark-theme.md)

</td>
</tr>
</table>

### 📋 **智能主题选择**

```
商务演示 → 🌞 白色主题 → 专业权威
技术分享 → 🌙 黑色主题 → 科技炫酷
通用场景 → 🔄 主题切换 → 用户自选
品牌适配 → 📊 VI匹配 → 场景定制
```

---

## 🚀 系统亮点

<table>
<tr>
<td width="50%">

### ⚡ **双主题架构**
- **模块化设计**: 独立主题文档管理
- **一键切换**: 无缝主题切换体验
- **场景适配**: 精准匹配不同演示环境
- **易于扩展**: 支持自定义主题开发

### 🎯 **专业品质**
- **768px黄金法则**: 确保投影设备完美显示
- **语义化色彩**: 双主题共享的色彩系统
- **响应式设计**: 完美适配各种设备尺寸
- **性能优化**: 60fps流畅动画体验

</td>
<td width="50%">

### 🎭 **视觉震撼**
- **🌞 白色特效**: Shimmer扫光、毛玻璃、粒子浮动
- **🌙 黑色特效**: 霓虹发光、赛博网格、故障动画
- **3D交互**: 鼠标视差、量子浮动、终端光标
- **高级动画**: 渐变文字、扫描线、发光脉冲

### 🔧 **技术先进**
- **Reveal.js 5.2.1**: 最新版本演示框架
- **现代CSS3**: backdrop-filter、clip-path特效
- **jsDelivr CDN**: 国内访问优化加载
- **组件化系统**: 标准化布局和交互组件

</td>
</tr>
</table>

---

## 📁 项目结构

```
ai-ppt-tutorial/
├── 📄 CLAUDE.md           # 主配置文件和使用指南
├── 📁 themes/             # 主题规范文档
│   ├── 🌞 white-theme.md  # 白色商务主题详细规范
│   └── 🌙 dark-theme.md   # 黑色极客主题详细规范
├── 📁 examples/           # 演示文稿实例
│   ├── claude-code-demo.html    # Claude Code功能演示
│   ├── deepseek-intro.html      # 技术产品介绍案例
│   └── reveal-demo.html         # 框架特性展示
├── 🌞 index.html          # 白色主题演示文稿
├── 🌙 index.dark.html     # 黑色主题演示文稿
└── 📖 README.md           # 项目说明文档
```

---

## 🛠️ 快速开始

### 1️⃣ **选择主题**

根据你的演示场景选择合适的主题：

- **商务正式** → 查看 [`themes/white-theme.md`](./themes/white-theme.md)
- **技术炫酷** → 查看 [`themes/dark-theme.md`](./themes/dark-theme.md)
- **混合使用** → 查看主配置 [`CLAUDE.md`](./CLAUDE.md)

### 2️⃣ **在线预览**

**🌐 GitHub Pages 在线演示**
- **[🌞 白色商务主题](https://bigsweetpotatostudio.github.io/ai-ppt-tutorial/index.html)** - 专业商务演示
- **[🌙 黑色极客主题](https://bigsweetpotatostudio.github.io/ai-ppt-tutorial/index.dark.html)** - 炫酷技术分享  
- **[🎨 Claude Code演示](https://bigsweetpotatostudio.github.io/ai-ppt-tutorial/examples/claude-code-demo.html)** - AI编程功能展示

**💻 本地预览**
```bash
# 克隆项目
git clone https://github.com/BigSweetPotatoStudio/ai-ppt-tutorial.git
cd ai-ppt-tutorial

# 直接打开HTML文件即可预览
open index.html
```

### 3️⃣ **开始创建**

使用主题规范创建你的演示文稿：

```html
<!-- 白色主题基础模板 -->
<html class="white-theme">
<section>
    <h2>页面标题</h2>
    <div class="features-grid auto-animate">
        <div class="feature-card">
            <h4><span class="keyword-highlight">重点内容</span></h4>
            <p>详细说明文字</p>
        </div>
    </div>
</section>
</html>
```

---

## 🎨 核心设计理念

### 💡 **为什么选择双主题系统？**

1. **🎯 场景适配**: 不同环境需要不同的视觉风格
2. **👥 受众偏好**: 商务场合 vs 技术场合的审美差异  
3. **🌓 环境友好**: 明亮环境 vs 暗场环境的最佳体验
4. **🎨 品牌灵活**: 支持企业根据VI选择主题风格

### 📐 **768px黄金法则**

> **为什么是768px？**
> 
> ✅ **投影兼容**: 确保在主流投影仪(1024x768)完整显示  
> ✅ **注意力管理**: 限制内容量，强迫精简信息  
> ✅ **演示流畅**: 避免滚动操作干扰演示节奏  
> ✅ **标准统一**: 建立一致的设计约束体系

### 🌈 **颜色语义系统**

| 颜色类型 | 🌞 白色主题 | 🌙 黑色主题 | 使用场景 |
|---------|------------|------------|----------|
| `keyword-highlight` | #e74c3c 红色 | #ff2d92 霓虹粉 | 关键词、重要概念 |
| `success-highlight` | #27ae60 绿色 | #00ff88 霓虹绿 | 成功状态、积极概念 |
| `info-highlight` | #3498db 蓝色 | #00d4ff 霓虹青 | 信息、技术术语 |
| `warning-highlight` | #e67e22 橙色 | #ff8c00 霓虹橙 | 警告、注意事项 |
| `number-highlight` | #f39c12 黄色 | #ffff00 霓虹黄 | 数字、统计数据 |

---

## 🧩 组件系统

### 📊 **布局组件**

| 组件名称 | 列数 | 适用场景 | 主题支持 |
|---------|------|----------|----------|
| `features-grid` | 2列 | 特性对比、优劣分析 | 🌞🌙 双主题 |
| `tech-grid` | 3列 | 技术栈、工具展示 | 🌞🌙 双主题 |
| `stats-grid` | 4列 | 数据统计、KPI展示 | 🌞🌙 双主题 |
| `highlight-box` | 全宽 | 重点强调、核心观点 | 🌞🌙 双主题 |
| `code-block` | 全宽 | 代码示例、配置展示 | 🌞🌙 双主题 |

### 🎭 **动画组件**

| 动画类型 | 🌞 白色效果 | 🌙 黑色效果 | 触发方式 |
|---------|------------|------------|----------|
| `auto-animate` | 淡入上升 | 淡入上升 | 页面加载 |
| `stagger-animation` | 交错左滑 | 交错左滑 | 列表展示 |
| `zoom-in-animation` | 缩放淡入 | 缩放淡入 | 重点强调 |
| 悬停特效 | Shimmer扫光 | 霓虹扫光 | 鼠标悬停 |

---

## 📚 学习资源

### 📖 **核心文档**

- **[主配置指南](./CLAUDE.md)** - 系统概述和快速上手
- **[白色主题规范](./themes/white-theme.md)** - 商务演示完整指南  
- **[黑色主题规范](./themes/dark-theme.md)** - 技术分享完整指南

### 🎯 **实战案例** 

1. **[🎨 Claude Code演示](https://bigsweetpotatostudio.github.io/ai-ppt-tutorial/examples/claude-code-demo.html)** - AI编程助手功能展示
2. **[🌞 白色商务主题](https://bigsweetpotatostudio.github.io/ai-ppt-tutorial/index.html)** - 商务演示模板案例
3. **[🌙 黑色极客主题](https://bigsweetpotatostudio.github.io/ai-ppt-tutorial/index.dark.html)** - 技术分享模板案例

### 🎬 **主题切换演示**

```html
<!-- 主题切换按钮 -->
<div class="theme-switcher">
    <button onclick="switchTheme('white-theme')">🌞 商务白</button>
    <button onclick="switchTheme('dark-theme')">🌙 极客黑</button>
</div>
```

---

## ✅ 质量保证

### 🔍 **检查清单**

- [ ] **768px限制**: 内容完整显示，无滚动条
- [ ] **主题适配**: 白色/黑色主题正常切换  
- [ ] **动画流畅**: 特效运行正常，无卡顿
- [ ] **投影兼容**: 1024x768分辨率完整显示
- [ ] **语义色彩**: 正确使用highlight色彩系统
- [ ] **响应式**: 移动设备正常显示和交互

### 🎯 **最佳实践**

1. **内容密度**: 每页3-7个要点，避免信息过载
2. **主题选择**: 根据演示场景选择合适主题
3. **色彩使用**: 合理使用语义化强调色彩
4. **动画适度**: 保证视觉效果不干扰内容传达

---

## 🤝 贡献指南

### 🎨 **如何贡献**

1. **Fork项目** - 创建你的功能分支
2. **选择方向**:
   - 🌈 **新主题开发**: 添加新的主题风格
   - 🧩 **组件扩展**: 开发新的布局组件
   - 📖 **文档改进**: 完善主题规范文档
   - 🎭 **特效创新**: 创建新的视觉效果

3. **提交规范**:
   ```
   🎨 feat(theme): 添加紫色创意主题
   📝 docs(white): 完善商务主题组件说明  
   🐛 fix(dark): 修复霓虹扫光动画问题
   ⚡ perf(core): 优化主题切换性能
   ```

### 🌟 **贡献方向**

- **🎨 新主题**: 深蓝科技、橙色创意、绿色自然
- **📱 移动优化**: 改进小屏设备体验
- **🌐 国际化**: 多语言主题模板
- **📊 数据可视化**: 图表组件集成

---

## 🔗 相关链接

- [Reveal.js官方文档](https://revealjs.com/) - 了解更多框架特性
- [CSS backdrop-filter](https://developer.mozilla.org/en-US/docs/Web/CSS/backdrop-filter) - 毛玻璃效果技术
- [jsDelivr CDN](https://www.jsdelivr.com/) - 了解资源加载优化

---

## 📄 开源协议

本项目采用 [MIT License](LICENSE) 开源协议。

---

<div align="center">

### 🚀 开始你的双主题演示之旅

**🌞 商务专业 | 🌙 技术炫酷 | 🔄 一键切换**

[![🌞 白色主题](https://img.shields.io/badge/🌞_白色主题-商务演示-667eea?style=for-the-badge)](./themes/white-theme.md)
[![🌙 黑色主题](https://img.shields.io/badge/🌙_黑色主题-技术分享-00ff88?style=for-the-badge)](./themes/dark-theme.md)
[![📖 查看文档](https://img.shields.io/badge/📖_查看文档-使用指南-27ae60?style=for-the-badge)](./CLAUDE.md)

---

*🎨 让每个演示都能精准匹配场景，创造最佳视觉体验*

**基于 claude-code-demo.html 成功实践 | 专为多场景演示设计的现代化主题系统**

</div>