# Python 求和方法知识库

一个全面收录 Python 中各种求和方法的静态知识库网站，专为 GitHub Pages 部署设计。

## 📚 收录的求和方法

1. **内置函数 sum()** - 最常用、最 Pythonic 的方式
2. **循环累加** - 基础灵活的方法
3. **推导式 + sum()** - 简洁优雅的 Python 风格
4. **functools.reduce()** - 函数式编程风格
5. **itertools.accumulate()** - 累积计算
6. **math.fsum()** - 高精度浮点数求和
7. **递归求和** - 教学用途
8. **NumPy 求和** - 科学计算和大规模数据
9. **Pandas 求和** - 数据分析
10. **并行分块求和** - 高性能计算

## 🚀 部署到 GitHub Pages

### 方法一：使用 GitHub Actions（推荐）

1. 将此仓库推送到你的 GitHub 仓库
2. GitHub Actions 会自动部署（见 `.github/workflows/deploy.yml`）
3. 访问 `https://yourusername.github.io/repository-name/`

### 方法二：手动部署

1. 在 GitHub 上创建新仓库
2. 推送所有文件到仓库
3. 进入 Settings → Pages
4. 选择 `main` 分支作为源
5. 保存后访问提供的 URL

## 📁 项目结构

```
.
├── index.html              # 主页面
├── static/
│   └── style.css          # 样式文件
├── .github/
│   └── workflows/
│       └── deploy.yml     # GitHub Actions 配置
└── README.md              # 说明文档
```

## 🎨 特性

- ✨ 现代化渐变背景和卡片设计
- 📱 完全响应式，支持移动端
- 🎯 粘性导航栏，快速跳转
- 🖨️ 支持打印优化
- 🚀 纯静态页面，无需服务器
- ⚡ 快速加载，无外部依赖

## 💻 本地预览

使用 Python 内置服务器：

```bash
# Python 3
python -m http.server 8000

# 访问 http://localhost:8000
```

或使用其他静态服务器：

```bash
# 使用 npx (Node.js)
npx serve .

# 使用 PHP
php -S localhost:8000
```

## 📝 使用示例

每种方法都包含：
- 适用情形说明
- 使用方法
- 完整代码示例
- 注意事项

访问网站后，点击导航栏即可快速跳转到对应方法。

## 🤝 贡献

欢迎提交 Issue 和 Pull Request 来改进这个知识库！

## 📄 许可证

MIT License

## 🔗 相关链接

- [Python 官方文档 - sum()](https://docs.python.org/3/library/functions.html#sum)
- [Python 官方文档 - math.fsum()](https://docs.python.org/3/library/math.html#math.fsum)
- [NumPy 文档](https://numpy.org/doc/)
- [Pandas 文档](https://pandas.pydata.org/docs/)

---

**Happy Coding! 🐍**
