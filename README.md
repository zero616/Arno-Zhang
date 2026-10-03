# Arno Zhang 网站发布说明

这是最新版静态网站，包含电脑版和手机版布局。

## 上传 GitHub
1. 新建 Public 仓库，名称可用 arnozhang。
2. 解压这个 ZIP。上传 index.html、style.css、app.js、content.js，以及 .nojekyll（如系统可见），放在仓库根目录。
3. 不要只上传 ZIP，也不要把文件放在额外的一层文件夹里。
4. 提交文件后，在仓库 Settings → Pages 中，选择 Deploy from a branch。
5. Branch 选择 main，文件夹选择 / (root)，点击 Save。
6. 等待发布完成，Pages 页面将显示真正的网站网址。复制该网址分享即可。

## 文件说明
- index.html：页面结构
- style.css：配色、排版及手机适配
- app.js：筛选、分页、轮播及页面交互
- content.js：教学路径和博客内容
- .nojekyll：静态发布标记

## 当前 Demo 状态
咨询表单仅展示信息预览，不会发送或保存咨询信息。
教学路径为示例说明，不是真实学生成绩或效果承诺。
国内访问情况需要用实际网络测试。

## 本地预览
解压后双击 index.html 即可打开。
