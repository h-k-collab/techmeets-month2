# PRベースの開発フロー体験

## 概要
Issueを起点にしたPR開発フローをひととおり体験し、Issue作成→ブランチ作成→コード書いてcommitpush→request作成→mainにマージ→作業ブランチ削除の流れを理解する。

## 使用技術

## セットアップ手順
```
git checkout -b feature/add-readme
git add README.md
git commit -m "Add README"
git push origin feature/add-readme
git checkout main
git pull origin main
git branch -d feature/add-readme
```

## 機能一覧
- ブランチ作成
- commit・push
- マージ後にローカルのmainを更新し、作業ブランチを削除
