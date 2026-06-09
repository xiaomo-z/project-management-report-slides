# 项目管理课程报告网页幻灯片（可部署版）

这是 reveal.js 网页幻灯片的静态部署版本，不依赖 node_modules，也不需要 npm install。

## 本地预览

```bash
cd /home/hermes/presentations/project-management-report-deploy
python3 -m http.server 8080
```

浏览器打开：

```text
http://127.0.0.1:8080
```

## 最推荐发布方式：Netlify Drop

1. 打开 https://app.netlify.com/drop
2. 登录或注册 Netlify
3. 把整个 `project-management-report-deploy` 文件夹拖进去
4. 等待上传完成，Netlify 会给你一个公开网址
5. 把网址发给老师/同学即可

## 也可以用 Vercel

1. 新建 GitHub 仓库
2. 上传本文件夹里的所有内容
3. 在 https://vercel.com/new 导入仓库
4. Framework Preset 选择 Other / Static
5. Build Command 留空
6. Output Directory 留空或填 `.`
7. Deploy

## 操作说明

- 方向键 / 空格：翻页
- F：全屏
- S：演讲者视图
- Esc：总览

## 导出 PDF

部署后访问：

```text
你的网址/?print-pdf
```

然后浏览器打印为 PDF。
