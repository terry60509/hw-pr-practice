# PR Practice

這是一個練習 Git 分支開發與 GitHub Pull Request 流程的專案。

## 做了什麼

- 建立 GitHub repository
- 使用 feature branch 開發，新增 PROFILE.md 個人簡介頁面
- 透過 Pull Request 進行 code review 並合併到 main
- 使用 GitHub Issues 練習回報 bug 與提出功能建議

## 如何安裝

```bash
git clone git@github.com:terry60509/hw-pr-practice.git
cd hw-pr-practice
```

## 如何操作

1. 建立 feature branch：
   ```bash
   git checkout -b feature/your-feature
   ```

2. 修改檔案並 commit：
   ```bash
   git add .
   git commit -m "描述你的修改"
   ```

3. Push 到 GitHub 並建立 Pull Request：
   ```bash
   git push -u origin feature/your-feature
   ```
   然後到 GitHub 頁面點 **Compare & pull request** 建立 PR。

4. Review 後 merge，再回本地同步：
   ```bash
   git checkout main
   git pull origin main
   ```
