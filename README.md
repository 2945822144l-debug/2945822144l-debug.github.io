# 测测你是什么小狗

一份 25 题的犬种鉴定小测试。单文件网页，零依赖、零构建，直接用浏览器打开 `index.html` 就能玩。

## 内容

- 25 个生活化场景题，每题 3 个选项
- 8 种常规犬种 + 1 个隐藏人格
- 结果页含八维性格条、最搭犬种、小狗图鉴
- 内置一个隐藏彩蛋：按特定顺序作答才会出现

## 本地运行

```bash
# 直接双击 index.html 即可，或起一个静态服务
python -m http.server 8000
```

## 部署

纯静态，任何静态托管都能跑：GitHub Pages / Vercel / Netlify / 对象存储。

GitHub Pages：仓库 Settings → Pages → Source 选 `main` 分支根目录，稍等片刻访问 `https://<用户名>.github.io/<仓库名>/`。
