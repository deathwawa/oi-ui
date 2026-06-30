# 异常物质 - 交互式 3D 体验

一个基于 React、TypeScript、Vite 和 Three.js 构建的现代 Web 应用，提供交互式 3D 生成艺术体验。

## 🚀 特性

- **交互式 3D 图形**：基于 Three.js 的实时 WebGL 渲染
- **生成艺术**：使用自定义着色器实现程序化动画二十面体
- **鼠标交互**：动态光照跟随光标移动
- **现代技术栈**：React 19、TypeScript、Vite 和 Tailwind CSS
- **响应式设计**：全屏体验，针对移动端优化
- **性能优化**：使用 Suspense 和高效渲染模式

## 🛠️ 技术栈

- **前端**：React 19、TypeScript
- **构建工具**：Vite
- **3D 引擎**：Three.js
- **样式**：Tailwind CSS
- **代码检查**：Oxlint
- **包管理器**：npm

## 📦 安装

1. 克隆仓库：
   ```bash
   git clone <repository-url>
   cd test
   ```

2. 安装依赖：
   ```bash
   npm install
   ```

3. 启动开发服务器：
   ```bash
   npm run dev
   ```

4. 在浏览器中打开 http://localhost:5173

## 🎯 脚本命令

- `npm run dev` - 启动开发服务器（支持热重载）
- `npm run build` - 构建生产版本
- `npm run preview` - 预览生产构建
- `npm run lint` - 运行 Oxlint 代码质量检查

## 🎨 项目结构

```
src/
├── components/
│   └── ui/
│       └── anomalous-matter-hero.tsx  # 主 3D Hero 组件
├── assets/                           # 静态资源（图片等）
├── App.tsx                           # 主应用组件
├── main.tsx                          # 入口文件
└── index.css                         # 全局样式
```

## 🎮 交互功能

3D 场景包含：

- **动画几何体**：带有柏林噪声位移的二十面体
- **自定义着色器**：顶点和片元着色器，实现独特视觉效果
- **动态光照**：点光源跟随鼠标光标移动
- **持续动画**：平滑旋转和基于时间的动态效果

## 🎨 样式设计

项目使用 Tailwind CSS，配色方案专为 3D 体验优化：

- 深色主题搭配柔和渐变
- 天蓝色强调色
- 响应式排版
- 全屏布局

## 🚀 部署

基于 Vite 构建，以获得最佳性能：

- 快速的开发服务器
- 优化的生产构建
- 自动代码分割
- 资源优化

## 📄 许可证

本项目基于 MIT 许可证开源。

## 🔧 配置

- **TypeScript**：启用严格类型检查
- **Oxlint**：使用 React 和 TypeScript 规则进行代码检查
- **Tailwind CSS**：针对项目需求的自定义配置
- **Vite**：针对 React 的优化构建配置

## 🎯 未来增强

- 更多 3D 场景和组件
- 性能优化
- 无障碍访问改进
- 移动端手势支持
- 更多交互功能

---

用 ❤️ 和现代 Web 技术构建
