# 部署指南

## 🚀 部署步骤

### 步骤1：生成静态文件

在blog目录下运行：

```bash
cd /xxx/blog
npm run clean
npm run build
```

### 步骤2：本地预览（可选）

在部署前可以先本地预览：

```bash
npm run server
```

然后访问：http://localhost:4000

### 步骤3：部署到GitHub Pages

```bash
npm run deploy
```

## 🔄 如果需要更新

如果将来需要修改页面，只需：

```bash
cd /Users/prayfff/javaprojects/blog
# 编辑 source/_posts/蔬菜统计服务.md
npm run build
npm run deploy
```

