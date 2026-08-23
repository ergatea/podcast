# Podcast

> 把复杂的世界，讲成可以一起思考的声音。

这是一个由 `ergatea` 管理的开放制作播客。首页用于发现内容，GitHub 用于留下制作过程：选题在 Issues，脚本和文稿在 Pull Requests，编辑规范在 Wiki，发布前检查交给 Actions。

## 入口

- [Podcast 首页](https://ergatea.github.io/podcast/)
- [Wiki：编辑手册](https://github.com/ergatea/podcast/wiki)
- [Issues：选题与听众反馈](https://github.com/ergatea/podcast/issues)
- [Pull requests：脚本与文稿审阅](https://github.com/ergatea/podcast/pulls)
- [Actions：自动检查与发布](https://github.com/ergatea/podcast/actions)

## 一期节目的最小流程

### EP.001：美债回购为何引爆金价

- [在线收听 / 下载音频](https://github.com/ergatea/podcast/releases/download/v0.1.0/default.m4a)
- [本期制作记录](https://github.com/ergatea/podcast/issues/1)

1. 用 `选题` Issue 描述问题、线索与希望回答的核心问题。
2. 讨论通过后，建立 `episode/NNN-topic` 分支。
3. 以 Pull Request 提交资料卡、节目提纲和文稿。
4. Actions 自动检查页面与链接；至少一位编辑审阅后合并。
5. 合并到 `main` 后自动部署 GitHub Pages。

## 本地预览

```bash
python3 -m http.server 4173
```

然后打开 <http://localhost:4173>。

更多规范见 [`docs/EDITORIAL.md`](docs/EDITORIAL.md) 与 [`wiki/Home.md`](wiki/Home.md)。
