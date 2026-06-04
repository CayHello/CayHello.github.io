# 个人主页

这是一个可直接部署到 GitHub Pages 的静态个人主页。

## 修改内容

- 在 `index.html` 中替换姓名、简介、项目、经历和联系方式。
- 在 `styles.css` 中调整颜色、间距和排版。

## 部署到 GitHub Pages

1. 在 GitHub 新建一个仓库，例如 `personal-homepage`。
2. 在本地执行：

   ```powershell
   git init
   git add .
   git commit -m "Create personal homepage"
   git branch -M main
   git remote add origin git@github.com:你的用户名/personal-homepage.git
   git push -u origin main
   ```

3. 进入 GitHub 仓库的 `Settings` -> `Pages`。
4. Source 选择 `Deploy from a branch`，Branch 选择 `main` 和 `/root`。
5. 保存后等待 GitHub 生成访问链接。
