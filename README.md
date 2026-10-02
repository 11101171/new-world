# 学习笔记

个人学习笔记汇总，以静态网页形式整理，通过 GitHub Pages 在线查看。

## 在线访问

部署后访问：

```
https://<你的用户名>.github.io/<仓库名>/
```

## 目录结构

```
.
├── index.html       # 导航首页，列出所有笔记页面
├── Go注意.html       # Go 语言注意事项汇总（并发、内存模型、channel 等）
└── README.md
```

## 如何新增一篇笔记

1. 把新的 `.html` 文件放到仓库根目录
2. 打开 `index.html`，复制其中的卡片代码块，改成新文件的标题、描述和链接

## 部署方式

仓库 **Settings → Pages**，Source 选择 `Deploy from a branch`，分支选 `main`，目录选 `/ (root)`，保存后等待 1~2 分钟自动生效。
