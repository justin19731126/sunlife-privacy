# sunlife-privacy

陽光健康生活（Sunlife）App 隱私權政策的公開頁面，給 Google Play／App Store 上架填寫用。

`index.html` 就是政策本文。發佈到 GitHub Pages 後網址為：

```
https://<你的GitHub帳號>.github.io/sunlife-privacy/
```

## 發佈步驟（GitHub Pages）

1. 在 GitHub 建一個 **public** 的空 repo，命名 `sunlife-privacy`（不要勾 README）。
2. 在本資料夾執行：

   ```powershell
   git init
   git add .
   git commit -m "Add Sunlife privacy policy"
   git branch -M main
   git remote add origin https://github.com/<你的帳號>/sunlife-privacy.git
   git push -u origin main
   ```

3. 到 repo → **Settings → Pages**，Source 選 **Deploy from a branch**，Branch 選 `main` / `/ (root)`，存檔。
4. 等 1～2 分鐘，上方會出現公開網址。打開確認頁面正常，這就是上架要填的隱私政策 URL。

## 更新政策

之後改 `index.html`（或從 `app/docs/privacy-policy.html` 重新複製過來）後，`git add . && git commit && git push`，Pages 會自動重新發佈。
