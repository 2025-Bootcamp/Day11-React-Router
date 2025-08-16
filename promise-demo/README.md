# Promise 学习项目

一个完整的 JavaScript Promise 学习项目，从基础概念到高级应用，包含练习题、测试框架和实际示例。

## 📚 项目概述

本项目旨在帮助开发者系统性地学习 JavaScript Promise，通过渐进式的练习和完整的测试覆盖，掌握异步编程的核心概念。

## 🏗️ 项目结构

```
promise-demo/
├── 01-basic-promise.js          # 基础 Promise 封装练习
├── 02-promise-then-catch.js     # Promise 链式调用练习
├── 03-async-await.js            # async/await 语法练习
├── 04-promise-error-handling.js # Promise 错误处理练习
├── 05-promise-all.js            # Promise.all() 方法练习
├── test-framework.js             # 自定义测试框架
├── test/                         # 测试文件目录
│   ├── test-01.js               # 基础 Promise 测试
│   ├── test-02.js               # 链式调用测试
│   ├── test-03.js               # async/await 测试
│   ├── test-04.js               # 错误处理测试
│   └── test-05.js               # Promise.all 测试
├── package.json                  # 项目配置
└── README.md                     # 项目说明文档
```

## 🎯 学习目标

### 1. 基础 Promise 封装 (01-basic-promise.js)
- 理解 Promise 的基本概念
- 学会将回调函数封装成 Promise
- 掌握 Promise 的状态管理

**练习内容：**
- 将 `setTimeout` 包装成 Promise
- 实现 `delay(ms)` 函数

### 2. Promise 链式调用 (02-promise-then-catch.js)
- 掌握 `then()` 方法的使用
- 掌握 `catch()` 方法的使用
- 学会处理成功和失败的情况

**练习内容：**
- 实现数据处理的 Promise 链
- 错误处理和异常捕获

### 3. async/await 语法 (03-async-await.js)
- 掌握 async/await 的基本语法
- 理解 async/await 与 Promise 的关系
- 学会使用 async/await 简化异步代码

**练习内容：**
- 将函数改为 async 函数
- 使用 await 等待 Promise 完成

### 4. Promise 错误处理 (04-promise-error-handling.js)
- 掌握 Promise 错误处理的最佳实践
- 学会使用 try-catch 处理异步错误
- 理解错误传播机制

**练习内容：**
- 在 async 函数中捕获异常
- 处理网络请求和 JSON 解析错误

### 5. Promise.all() 方法 (05-promise-all.js)
- 掌握 `Promise.all()` 的用法和特点
- 理解并行执行的概念
- 学会处理多个异步操作的场景

**练习内容：**
- 使用 `Promise.all()` 等待多个 Promise 完成
- 理解并行执行的时间特性

## 🧪 测试框架

项目包含一个自定义的测试框架 (`test-framework.js`)，提供以下功能：

### 测试工具函数
- `test(name, testFunction)` - 同步测试
- `asyncTest(name, testFunction)` - 异步测试
- `assert(condition, message)` - 断言函数
- `assertEqual(actual, expected, message)` - 相等断言
- `assertDeepEqual(actual, expected, message)` - 深度相等断言

### 测试结果统计
- 总测试数统计
- 通过/失败数量
- 成功率计算
- 详细测试结果

## 🚀 使用方法

### 安装依赖
```bash
npm install
```

### 运行所有测试
```bash
npm test
```

### 运行特定练习的测试
```bash
# 运行基础 Promise 测试
npm run test:01

# 运行链式调用测试
npm run test:02

# 运行 async/await 测试
npm run test:03

# 运行错误处理测试
npm run test:04

# 运行 Promise.all 测试
npm run test:05
```

### 直接运行练习文件
```bash
# 运行基础 Promise 练习
node 01-basic-promise.js

# 运行链式调用练习
node 02-promise-then-catch.js

# 运行 async/await 练习
node 03-async-await.js

# 运行错误处理练习
node 04-promise-error-handling.js

# 运行 Promise.all 练习
node 05-promise-all.js
```

## 📝 练习说明

每个练习文件都包含：
- 清晰的学习目标说明
- 具体的练习要求
- TODO 注释标记需要完成的部分
- 示例代码和预期输出
- 导出函数供测试使用

## 🔧 开发环境

- **Node.js**: 建议使用 16.0+ 版本
- **模块系统**: ES6 模块 (ESM)
- **测试框架**: 自定义测试框架
- **开发工具**: 支持 nodemon 热重载

## 📖 学习建议

1. **按顺序学习**: 从 01 开始，逐步完成每个练习
2. **理解概念**: 不要只关注代码实现，要理解背后的概念
3. **运行测试**: 完成练习后及时运行测试验证
4. **查看错误**: 测试失败时仔细阅读错误信息
5. **实践应用**: 尝试在实际项目中使用学到的知识

## 🤝 贡献

欢迎提交 Issue 和 Pull Request 来改进这个学习项目！

## 📄 许可证

MIT License

---

**Happy Learning! 🎉**
