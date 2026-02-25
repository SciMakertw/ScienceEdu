# Agent Login Notes

這份文件提供後續 agent 在此 repo 進行發佈時的登入與驗證流程。

## 目前 CLI 狀態
- GitHub host: `github.com`
- Active account: `git2scimaker-code`
- Git protocol: `https`
- Token scopes: `repo`, `read:org`, `gist`

## 驗證指令
```bash
gh auth status
gh api repos/SciMakertw/ScienceEdu --jq "{permissions: .permissions}"
```

## 發佈流程（建議）
```bash
git status
git add .
git commit -m "<message>"
git push -u origin main
```

## 權限不足時
若出現 `403` 或 `push:false`，代表目前帳號沒有寫入權限。可用以下替代流程：
1. `gh repo fork SciMakertw/ScienceEdu --remote=true --remote-name fork`
2. `git push -u fork <branch>`
3. `gh pr create --repo SciMakertw/ScienceEdu --base main --head git2scimaker-code:<branch> --title "..." --body "..."`

## 安全注意
- 不要把 Personal Access Token 明文寫進 repo。
- 不要把 `gh auth token` 輸出存到檔案。
- 若需要更換帳號，使用：
```bash
gh auth logout
gh auth login
```
