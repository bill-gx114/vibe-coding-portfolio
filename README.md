# Vibe Coding Portfolio

这是一个用于简历投递的静态作品集页面，展示 2024-2026 年的 AI / Vibe Coding 产品实践。页面口径强调：作者本职是 6 年搜推策略产品（5 年推荐、1 年搜索），这些作品是业余时间完成的 AI 产品实践。

## 本地预览

直接用浏览器打开 `index.html` 即可。也可以在当前目录启动一个本地静态服务：

```bash
python3 -m http.server 8000
```

然后访问：

```text
http://localhost:8000
```

## GitHub Pages 发布

1. 在 GitHub 新建一个仓库，例如 `vibe-coding-portfolio`。
2. 把当前目录里的文件推送到仓库。
3. 进入仓库的 `Settings` -> `Pages`。
4. 在 `Build and deployment` 里选择 `Deploy from a branch`。
5. Branch 选择 `main`，目录选择 `/root`。
6. 保存后等待 GitHub Pages 生成访问链接。

## 文件结构

```text
.
├── index.html
├── assets
│   ├── posters
│   └── videos
├── docs
│   └── superpowers
│       └── plans
└── README.md
```

## 发布注意

- `assets/videos/` 下的视频已经转为 H.264 MP4，适合网页播放。
- 单个视频文件已控制在 GitHub 的 100MB 推送限制以下。
- 根目录里的原始 `.mp4` 已通过 `.gitignore` 排除，发布时只需要提交 `assets/videos/` 下的网页版本。
- 已下线项目均为曾成功上线过的产品，页面以本地视频保留作品记录。
- 当前在线产品是小说伴读：<https://novel-companion-xi.vercel.app/> 和审美日课：<https://shenmei-rich.vercel.app/>
