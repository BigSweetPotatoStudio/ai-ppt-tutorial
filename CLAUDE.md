# 🎨 Reveal.js 双主题演示系统

## 📊 项目概述
- **框架**: Reveal.js 5.2.1 
- **主题系统**: 双主题架构 (🌞 白色商务 + 🌙 黑色极客)
- **语言**: 中文
- **设计理念**: 内容优先、场景适配、视觉震撼、专业呈现

## 🎯 主题选择系统

### 🌞 白色商务主题
- **适用场景**: 商务演示、学术演讲、培训教学、投影环境
- **设计特色**: 毛玻璃效果、语义化色彩、专业正式
- **详细规范**: 查看 `themes/white-theme.md`

### 🌙 黑色极客主题  
- **适用场景**: 技术分享、产品发布、创意展示、暗场环境
- **设计特色**: 霓虹发光、赛博网格、炫酷特效
- **详细规范**: 查看 `themes/dark-theme.md`

### 📋 主题选择建议
```
商务演示 → 选择白色主题 → 专业权威
技术分享 → 选择黑色主题 → 科技炫酷
品牌适配 → 根据VI选择 → 场景匹配
```

## 🚨 核心约束原则

### 1. **768px黄金法则** ⭐ 最重要设计约束
- **绝对高度限制**: 所有内容必须在768px内完整显示
- **一页一主题**: 每页只传达一个核心概念  
- **3-7信息法则**: 每页3-7个要点，理想为3-5个
- **即开即用**: 零配置，直接打开HTML预览

### 2. 技术栈配置
- **CDN**: jsDelivr (reveal.js@5.2.1 + 字体资源)
- **字体**: Inter + JetBrains Mono
- **动画**: 禁用fragment，采用自动动画
- **兼容**: Chrome 80+、Safari 13+、Firefox 75+

## 🎨 通用设计规范

### 1. 主题系统
- **默认主题**: 白色商务主题 (兼容性最佳)
- **主题文档**: 详细规范请查看 `themes/` 文件夹

### 2. 颜色语义系统 (双主题共享)
- **keyword-highlight**: 关键词和重要概念
- **success-highlight**: 成功状态和积极概念  
- **info-highlight**: 信息和技术术语
- **warning-highlight**: 警告和注意事项
- **number-highlight**: 数字和统计数据

### 3. 字体层级系统 (768px优化)
- **H1**: 2.0em (主标题) 
- **H2**: 1.6em (页面标题) - 渐变动画，居中显示
- **H3**: 1.2em (区块标题)
- **H4**: 1.0em (卡片标题) 
- **正文**: 0.85em (内容文字)
- **代码**: 0.8em (JetBrains Mono)
- **表格**: 0.8em (数据展示)

### 4. 布局设计令牌
- **间距**: xs(4px) | sm(8px) | md(12px) | lg(16px) | xl(20px)
- **圆角**: 12px(标准) | 16px(大卡片) | 20px(强调框)
- **阴影**: elevation-1~5 (2px~32px渐进)

## 🎭 动画效果系统

### 1. 双主题特色效果
- **🌞 白色主题**: Shimmer扫光、渐变文字、粒子浮动、毛玻璃
- **🌙 黑色主题**: 霓虹扫光、故障效果、赛博网格、发光动画

### 2. 通用动画时序
- **fadeInUp**: 0.5s, 延迟0.1s递增
- **slideInLeft**: 0.4s, 延迟0.1s递增  
- **zoomIn**: 0.5s, 延迟0.6s起步
- **过渡动画**: 0.25-0.3s cubic-bezier
- **禁用旋转css** rotate

## 📝 内容规划法则

### 1. 页面类型模板
- **标题页**: 主标题 + 副标题 + 描述 (≤3行)
- **内容页**: H2标题 + 3-5要点 + 小结
- **对比页**: 2列对比布局  
- **数据页**: stats-grid + 数字强调
- **总结页**: 核心要点 + CTA

### 2. 组件选择器
```html
<div class="features-grid">      <!-- 2列特性 -->
<div class="tech-grid">          <!-- 3列技术 -->
<div class="stats-grid">         <!-- 4列数据 -->
<div class="highlight-box">      <!-- 重点强调 -->
<div class="code-block">         <!-- 代码展示 -->
```

### 3. 动画应用
- **auto-animate**: 淡入上升
- **stagger-animation**: 交错左滑
- **zoom-in-animation**: 缩放淡入

## ⚙️ Reveal.js 5.2.1 配置

### 标准配置
```javascript
Reveal.initialize({
    view: 'scroll',              // 现代滚动模式
    width: 1024, height: 768,    // 固定尺寸
    margin: 0.05,                // 边距
    autoAnimateEasing: 'ease-in-out',
    autoAnimateDuration: 1.0,
    controls: true,
    progress: true,
    plugins: [RevealHighlight, RevealMarkdown, RevealNotes]
});
```

## 🔧 快速使用指南

### 1. 语义化颜色
```html
<span class="keyword-highlight">关键概念</span>
<span class="success-highlight">积极结果</span>
<span class="info-highlight">技术术语</span>
<span class="warning-highlight">注意事项</span>
<span class="number-highlight">70%</span>
```

### 2. 页面结构示例
```html
<section>
    <h2>页面标题</h2>
    <div class="features-grid auto-animate">
        <div class="feature-card">内容卡片</div>
    </div>
    <div class="highlight-box zoom-in-animation">重点强调</div>
</section>
```

## ✅ 质量检查要点

### 核心检查
- [ ] **768px限制**: 内容完整显示，无滚动条
- [ ] **动画流畅**: 特效运行正常，无卡顿
- [ ] **投影兼容**: 1024x768分辨率完整显示

## 📚 总结

双主题演示系统为不同场景提供专业解决方案：
- **🌞 白色主题**: 商务正式，投影兼容
- **🌙 黑色主题**: 技术炫酷，视觉震撼
- **详细规范**: 查看 `themes/` 文件夹获取完整指南

---

*基于claude-code-demo.html成功实践，专为多场景演示设计的现代化主题系统。*