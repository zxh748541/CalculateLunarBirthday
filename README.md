# 公历/农历生日接近计算器（可手机分享版）

## 你能得到什么
- 一个 **纯前端** 的小工具（HTML + JS），手机打开就能用
- 支持生成可分享链接（含参数），并支持 PWA（可“添加到主屏幕”）

## 如何本地打开
直接打开 `index.html` 即可（电脑/手机都行）。

## 如何变成“手机里可以直接分享的链接”
### 方案 A：GitHub Pages（推荐）
1. 新建仓库，把整个文件夹内容上传
2. 打开仓库 Settings → Pages → 选择从 main 分支部署
3. 得到一个 `https://xxx.github.io/yyy/` 的链接，发给朋友即可

### 方案 B：Vercel / Netlify
把这几个文件部署成静态站点即可（拖拽上传或连 GitHub）。

## 备注
- 使用 6tail 的 lunar-javascript 进行公历/农历换算（通过 jsDelivr CDN 加载）。
