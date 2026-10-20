# 云野家具产品管理系统 V1.0

单文件静态网页产品档案工具。无需安装依赖。

## 本地使用
双击 `index.html`，在浏览器中打开。

## GitHub Pages 发布
1. 创建公开仓库 `yunye-product-manager`。
2. 上传 `index.html` 和 `README.md` 到仓库根目录。
3. Settings → Pages → Build and deployment → Deploy from a branch → main / (root) → Save。
4. 等待部署完成，访问 Pages 提供的网址。

## 注意
- 所有产品数据、图片只存放在当前浏览器 localStorage，不同步到 GitHub，也不会自动跨设备同步。
- 定期点击「备份 JSON」，备份文件中包含图片数据。导入会覆盖当前全部产品。
- CSV 仅含文本字段，不包含图片。
- 不要将客户机密、真实采购成本、报价备份上传到公开仓库。
- 本工具为试用原型，尚不适合多人协作或作为唯一的正式业务记录系统。
