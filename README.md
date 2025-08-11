# 网站正在建设中 - Under Construction Page

一个优美的"网站正在建设中"HTML单页面，专为 golxc.com 域名设计。

## 🌟 项目特色

- **现代设计**：深蓝色渐变背景，简洁优雅的界面
- **动画效果**：CSS3 动画包括淡入效果、浮动元素、渐变背景动画
- **响应式设计**：完美适配桌面端和移动端设备
- **社群引导**：底部包含 Telegram 群组引导链接
- **SEO 优化**：包含适当的 meta 标签和语义化 HTML
- **快速加载**：纯 HTML/CSS 实现，无外部依赖

## 🎨 设计规范

### 色彩方案
- **主色调**：深蓝色 (#1a1a2e) 和渐变紫色 (#16213e)
- **辅助色**：亮蓝色 (#0f3460) 和白色 (#ffffff)
- **按钮样式**：圆角设计，悬停渐变效果

### 字体设计
- **主标题**：2.5rem，现代无衬线字体
- **副标题**：1.2rem，半透明白色
- **按钮文字**：0.9rem，加粗显示

## 🚀 快速开始

### 本地预览
1. 克隆或下载项目文件
2. 在浏览器中打开 `index.html` 文件
3. 即可预览效果

### 部署到 GitHub Pages

#### 步骤 1：创建 GitHub 仓库
1. 登录 [GitHub](https://github.com)
2. 创建新的公开仓库
3. 上传项目文件

#### 步骤 2：启用 GitHub Pages
1. 进入仓库 Settings > Pages
2. 选择 "Deploy from a branch"
3. 选择 "main" 分支和 "/" 根目录
4. 保存设置

#### 步骤 3：配置自定义域名
1. 在 GitHub Pages 设置中输入域名：`golxc.com`
2. 确保 CNAME 文件存在于仓库根目录
3. 配置域名 DNS 记录

## 🔧 DNS 配置

在您的域名注册商处添加以下 DNS 记录：

### 方法 A：CNAME 记录（推荐）
```
类型: CNAME
名称: @
值: 你的用户名.github.io
TTL: 3600
```

### 方法 B：A 记录
```
类型: A
名称: @
值: 185.199.108.153

类型: A
名称: @
值: 185.199.109.153

类型: A
名称: @
值: 185.199.110.153

类型: A
名称: @
值: 185.199.111.153
```

## 📁 文件结构

```
/
├── index.html          # 主页面文件
├── CNAME              # GitHub Pages 域名配置
├── README.md          # 项目说明文档
└── .trae/             # 项目文档目录
    └── documents/
        ├── 产品需求文档.md
        ├── 技术架构文档.md
        └── 使用文档.md
```

## 🎯 功能特性

### 动画效果
- **渐变背景动画**：8秒循环的背景色彩变化
- **文字淡入动画**：标题和副标题的渐进显示
- **加载动画**：旋转的加载指示器
- **浮动元素**：背景装饰圆圈的浮动效果
- **按钮交互**：悬停和点击的视觉反馈

### 响应式设计
- **桌面端**：完整的视觉效果和动画
- **平板端**：适配中等屏幕尺寸
- **移动端**：优化的布局和隐藏装饰元素
- **超小屏幕**：进一步优化的字体和间距

### 交互功能
- **社群链接**：点击跳转到 Telegram 群组
- **键盘快捷键**：按 'G' 键快速访问群组
- **右键保护**：禁用右键菜单（可选）

## 🔗 相关链接

- **网站地址**：[https://golxc.com](https://golxc.com)
- **Telegram 群组**：[https://t.me/lxcnatserver](https://t.me/lxcnatserver)
- **GitHub Pages 文档**：[docs.github.com/pages](https://docs.github.com/en/pages)

## 📱 浏览器兼容性

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ 移动端浏览器

## 🛠️ 技术栈

- **HTML5**：语义化标签和现代 HTML 特性
- **CSS3**：Flexbox、Grid、动画和渐变
- **JavaScript**：原生 JS，无外部依赖
- **GitHub Pages**：静态网站托管

## 📝 更新日志

### v1.0.0 (2024)
- ✨ 初始版本发布
- 🎨 实现深蓝色渐变设计
- 🎭 添加 CSS3 动画效果
- 📱 完成响应式设计
- 🔗 集成 Telegram 群组链接
- 🌐 配置 GitHub Pages 部署

## 🤝 贡献指南

欢迎提交 Issue 和 Pull Request 来改进这个项目！

1. Fork 本仓库
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启 Pull Request

## 📄 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情。

## 💬 技术支持

如果您在使用过程中遇到问题，可以：

1. 查看项目文档和 FAQ
2. 提交 GitHub Issue
3. 加入我们的 Telegram 群组：[t.me/lxcnatserver](https://t.me/lxcnatserver)

---

**Made with ❤️ for golxc.com**