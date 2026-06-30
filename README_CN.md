<p align="right"> <a href="./README.md">🇺🇸 English</a> | <a href="./README_CN.md">🇨🇳 简体中文</a> </p>  

# 异常物质 - 交互式3D体验应用

一个现代化的Web应用，使用React、TypeScript、Vite和Three.js构建，具有交互式3D生成艺术功能。

## 🚀 项目特性

- **交互式3D图形**：使用Three.js进行实时WebGL渲染
- **生成艺术**：具有自定义着色器的程序化动画二十面体
- **鼠标交互**：响应光标移动的动态光照系统
- **现代技术栈**：React 19、TypeScript、Vite和Tailwind CSS
- **响应式设计**：全屏体验，支持移动设备优化
- **性能优化**：使用Suspense和高效渲染模式

## 🛠️ 技术栈

- **前端**：React 19、TypeScript
- **构建工具**：Vite
- **3D引擎**：Three.js
- **样式**：Tailwind CSS
- **代码检查**：Oxlint
- **包管理器**：npm

## 📦 安装说明

1. 克隆仓库：
`bash
git clone git@github.com:deathwawa/oi-ui.git
cd oi-ui
`

2. 安装依赖：
`bash
npm install
`

3. 启动开发服务器：
`bash
npm run dev
`

4. 在浏览器中访问 http://localhost:5173

## 🎯 可用脚本

- 
pm run dev - 启动开发服务器，支持热重载
- 
pm run build - 构建生产版本
- 
pm run preview - 预览生产构建
- 
pm run lint - 运行Oxlint进行代码质量检查

## 🎨 项目结构

`
src/
├── components/
│   └── ui/
│       └── anomalous-matter-hero.tsx  # 主要3D英雄组件
├── assets/                           # 静态资源（图片等）
├── App.tsx                           # 主应用组件
├── main.tsx                          # 入口文件
└── index.css                         # 全局样式
`

## 🎮 交互功能

3D场景包含：
- **动画几何体**：具有Perlin噪声位移的二十面体
- **自定义着色器**：用于独特视觉效果的可编程着色器
- **动态光照**：跟随鼠标光标的光源
- **连续动画**：平滑旋转和时间基础效果

## 🎨 样式设计

项目使用Tailwind CSS，采用为3D体验优化的配色方案：
- 深色主题配合渐变效果
- 天蓝色强调色
- 响应式排版
- 全屏布局

## 🚀 部署说明

使用Vite构建，确保最佳性能：
- 快速开发服务器
- 优化的生产构建
- 自动代码分割
- 资源优化

## 📄 许可证

本项目采用MIT许可证。

## 🔧 配置详情

- **TypeScript**：启用严格类型检查
- **Oxlint**：React和TypeScript规则代码检查
- **Tailwind CSS**：项目定制配置
- **Vite**：针对React优化的构建配置

## 🎯 未来规划

- 更多3D场景和组件
- 性能优化改进
- 可访问性增强
- 移动端手势支持
- 更多交互功能

---

使用现代Web技术精心构建 ❤️
