# 小红书购物人格 DNA 测试 - GitHub 轻量部署包

这是经过资源去重的单层 GitHub Pages 静态部署包。

## 部署方法

1. 解压完整 ZIP。
2. 将解压后的全部文件上传到 GitHub 仓库根目录，不要上传 ZIP 本身。
3. 不要重命名文件，也不要建立子文件夹。
4. 在仓库 `Settings` → `Pages` 中选择 `Deploy from a branch`。
5. 选择对应分支和 `/ (root)` 后保存。

## 文件说明

- `index.html`：页面入口。
- `app.js`：交互逻辑。
- `styles.css`：样式和动画。
- `.nojekyll`：GitHub Pages 静态部署标记。
- `*.svg`：页面视觉素材。
- `img-*.png`、`img-*.jpg`：从 SVG 中提取并按内容哈希去重的位图素材。

所有文件都必须保持在同一级，SVG 会通过相对路径加载对应的图片文件。
