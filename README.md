# DuskUE HTML5 Build

## 🚀 部署说明

### 当前问题
此项目已部署到 GitHub Pages，但由于 GitHub Pages **不支持 Git LFS**，大文件（压缩后的资源文件）无法正常提供。

### 替代部署方案

#### 方案 1: 使用 Netlify (推荐)
1. 访问 https://www.netlify.com
2. 使用 GitHub 账号登录
3. 选择此仓库并部署
4. Netlify 完全支持 Git LFS！

#### 方案 2: 使用 Vercel
1. 访问 https://vercel.com
2. 导入此仓库
3. 直接部署

#### 方案 3: 本地运行
1. 克隆仓库：`git clone https://github.com/AnshunAnson/DuskUE.git`
2. 确保已安装 Git LFS：`git lfs install`
3. 拉取 LFS 文件：`git lfs pull`
4. 在本地使用 HTTP 服务器运行

### 项目文件说明
- `index.html` / `DuskUE.html`: 主入口文件
- `DuskUE.UE4.js`: Unreal Engine 4 主脚本
- `DuskUE.data.gz`: 游戏数据（大文件）
- `DuskUE.wasm.gz`: WebAssembly 模块
