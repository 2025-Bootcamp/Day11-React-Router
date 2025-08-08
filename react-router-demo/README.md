# React Router Demo

这是一个使用React Router构建的示例项目，展示了推荐的React项目目录结构。

## 项目结构

```
src/
├── components/         # 可复用组件
│   ├── layout/        # 布局组件
│   │   └── Header.jsx # 页面头部导航
│   └── ProductCard.jsx # 产品卡片组件
├── pages/             # 页面组件
│   ├── Home.jsx       # 首页
│   ├── Products.jsx   # 产品列表页
│   └── About.jsx      # 关于页面
├── hooks/             # 自定义Hooks
├── utils/             # 工具函数
│   └── constants.js   # 常量定义
├── styles/            # 样式文件
│   └── global.css     # 全局样式
├── assets/            # 静态资源
├── App.jsx            # 主应用组件（路由配置）
└── main.jsx           # 应用入口
```

## 特性

- ✅ React Router 路由管理
- ✅ 推荐的目录结构
- ✅ 组件化开发
- ✅ 产品列表页面（搜索、筛选功能）
- ✅ 响应式设计
- ✅ 全局样式管理
- ✅ 常量管理
- ✅ 代码格式化配置

## 开发环境配置

### 编辑器配置

项目包含以下配置文件以确保代码格式一致性：

- `.editorconfig` - 编辑器基础配置
- `.prettierrc` - Prettier 代码格式化规则
- `.vscode/settings.json` - VS Code 工作区设置
- `.vscode/extensions.json` - 推荐的 VS Code 扩展

### 推荐的 VS Code 扩展

- Prettier - 代码格式化
- ESLint - 代码检查
- Auto Rename Tag - 自动重命名标签
- Path Intellisense - 路径智能提示
- Emmet - 代码片段

### 代码格式化

项目使用 Prettier 进行代码格式化，配置了以下规则：

- 使用单引号
- 行尾分号
- 2空格缩进
- 最大行长度 100 字符
- 尾随逗号（ES5 兼容）

## 开发

```bash
# 安装依赖
npm install

# 启动开发服务器
npm run dev

# 构建生产版本
npm run build

# 代码检查
npm run lint
```

## 路由

- `/` - 首页
- `/products` - 产品列表页
- `/about` - 关于页面

## 产品页面功能

- 🔍 产品搜索（按名称和描述）
- 🏷️ 分类筛选
- 📱 响应式网格布局
- 🎨 悬停动画效果
- 📊 产品统计显示

## 技术栈

- React 19
- React Router
- Vite
- ESLint
- Prettier
- EditorConfig
