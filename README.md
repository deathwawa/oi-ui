<p align="right"> <a href="./README.md">🇺🇸 English</a> | <a href="./README_CN.md">🇨🇳 简体中文</a> </p> 



# Anomalous Matter - Interactive 3D Experience

A modern web application featuring interactive 3D generative art built with React, TypeScript, Vite, and Three.js.

## 🚀 Features

- **Interactive 3D Graphics**: Real-time WebGL rendering with Three.js
- **Generative Art**: Procedurally animated icosahedron with custom shaders
- **Mouse Interaction**: Dynamic lighting that responds to cursor movement
- **Modern Stack**: React 19, TypeScript, Vite, and Tailwind CSS
- **Responsive Design**: Full-screen experience with mobile optimization
- **Performance Optimized**: Uses Suspense and efficient rendering patterns

## 🛠️ Tech Stack

- **Frontend**: React 19, TypeScript
- **Build Tool**: Vite
- **3D Engine**: Three.js
- **Styling**: Tailwind CSS
- **Linting**: Oxlint
- **Package Manager**: npm

## 📦 Installation

1. Clone the repository:
`ash
git clone <repository-url>
cd test
`

2. Install dependencies:
`ash
npm install
`

3. Start the development server:
`ash
npm run dev
`

4. Open your browser and navigate to http://localhost:5173

## 🎯 Scripts

- 
pm run dev - Start development server with hot reload
- 
pm run build - Build for production
- 
pm run preview - Preview production build
- 
pm run lint - Run Oxlint for code quality

## 🎨 Project Structure

`
src/
├── components/
│   └── ui/
│       └── anomalous-matter-hero.tsx  # Main 3D hero component
├── assets/                           # Static assets (images, etc.)
├── App.tsx                           # Main application component
├── main.tsx                          # Entry point
└── index.css                         # Global styles
`

## 🎮 Interactive Features

The 3D scene includes:
- **Animated Geometry**: Icosahedron with Perlin noise displacement
- **Custom Shaders**: Vertex and fragment shaders for unique visual effects
- **Dynamic Lighting**: Point light that follows mouse cursor
- **Continuous Animation**: Smooth rotation and time-based effects

## 🎨 Styling

The project uses Tailwind CSS with a color scheme optimized for the 3D experience:
- Dark theme with subtle gradients
- Sky blue accent colors
- Responsive typography
- Full-screen layout

## 🚀 Deployment

Built with Vite for optimal performance:
- Fast development server
- Optimized production builds
- Automatic code splitting
- Asset optimization

## 📄 License

This project is licensed under the MIT License.

## 🔧 Configuration

- **TypeScript**: Strict type checking enabled
- **Oxlint**: Code linting with React and TypeScript rules
- **Tailwind CSS**: Custom configuration for project needs
- **Vite**: Optimized build configuration for React

## 🎯 Future Enhancements

- Additional 3D scenes and components
- Performance optimizations
- Accessibility improvements
- Mobile gesture support
- More interactive features

---

Built with ❤️ using modern web technologies
