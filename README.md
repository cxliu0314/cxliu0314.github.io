# cxliu0314.github.io

一个可直接部署到 GitHub Pages 的静态个人主页，结构参考 `https://rui-ye.github.io/` 的学术主页信息组织方式。

当前已根据 Changxing Liu 的 Google Scholar profile 补充姓名、单位、研究兴趣、发表列表和引用信息：
`https://scholar.google.com.hk/citations?user=MpUEflgAAAAJ&hl=zh-CN`

部署地址：
`https://cxliu0314.github.io/`

## 文件

- `index.html`：主页内容，包含简介、论文、项目、教育经历。
- `style.css`：页面样式和移动端适配。
- `assets/avatar-placeholder.svg`：占位头像，可替换为个人照片。

## 本地预览

```powershell
cd D:\Workspace\personal_homepage
python -m http.server 8000
```

然后打开 `http://localhost:8000`。

## 部署到 GitHub Pages

1. 新建仓库，推荐命名为 `你的GitHub用户名.github.io`。
2. 将本目录内容提交到仓库根目录。
3. 在仓库 Settings -> Pages 中选择从主分支部署。

## 下一步需要替换

- 邮箱、GitHub、CV 链接。
- 头像文件，建议放在 `assets/` 目录。
- 更完整的教育经历、荣誉和项目链接。
