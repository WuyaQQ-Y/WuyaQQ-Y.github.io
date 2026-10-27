# 作品集站点（GitHub Pages）

个人作品集，静态站。**线上地址：https://wuyaqq-y.github.io**（仓库 WuyaQQ-Y/WuyaQQ-Y.github.io，公开，Pages 已开）。页面不署名，只放作品。

## 结构

```
index.html              作品集主页（一页式：作品 / 在研 / 联系，不含自我介绍与经历）
shanwu/
  index.html            作品一：山雾茶事·茶空间品牌官网（概念设计 demo）
  assets/*.jpg          首页六张茶席图，已从 PNG 压到 JPEG（6.4MB → 0.54MB）
.nojekyll               让 GitHub Pages 跳过 Jekyll 处理
```

## 本地预览

```bash
cd D:/作品集站
python -m http.server 8899
# 浏览器打开 http://127.0.0.1:8899/
```

## 上线方式

1. GitHub 建公开仓库（个人站用 `<用户名>.github.io` 这个名字，网址就是根域名）
2. 本目录 git push 上去，或走网页版 Upload files 拖文件夹
3. 仓库 Settings → Pages → Source 选 `main` 分支 `/ (root)` → 保存
4. 等 1-2 分钟，访问 `https://<用户名>.github.io/`

## 红线（官方条款）

**GitHub Pages 不得用于以促成商业交易为目的的网站。**
- ✅ 放自己的作品展示 = 合规
- ❌ 甲方要我帮忙把他们的商用站挂在这里 = 不能接（商用站要另找正经主机）

## 待办

- [x] 联系邮箱：wuyaQQ-Y@qq.com（已填并上线）
- [x] 仓库已建：`WuyaQQ-Y.github.io`，Pages 已开（main / root）
- 更新方式：改完文件 `git add -A && git commit -m "..." && git push`，1 分钟内自动上线
- [ ] 第二批作品：展厅《中国计时历史馆》、升仙原型 v4、对弈、2048
- [ ] 渲染图（3d/餐饮空间）压缩后再传，单张压到 300KB 以内

_建档：小墨（桌面端），2026-09-24_
