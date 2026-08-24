# 手順
1. AがGitHub上にリモートリポジトリを用意し、（Helloと記述）をブランチにPushする。
<img width="1005" height="477" alt="スクリーンショット 2026-08-24 160526" src="https://github.com/user-attachments/assets/2583ec7b-cb9f-4655-ad86-d4c1f9e40eb4" />
2.Collaboratirsを追加する
<img width="1885" height="947" alt="スクリーンショット 2026-08-24 161635" src="https://github.com/user-attachments/assets/3c2661fe-9b63-46ba-82a1-bfb4e61037f1" />
3. Bがリポジトリをcloneし、作業ブランチを作成。を編集してPushし、Aへプルリクエストを出す。
4. AがBのプルリクエストをレビューし、ブランチにマージする。
5. Aがローカルのブランチを最新化（pull）し、作業ブランチを作成。を編集してPRを作成・マージする。
6. Bがローカルのブランチを最新化（pull）し、作業ブランチを作成。を追加してAへプルリクエストを出す。
7. AがBのプルリクエストをレビューし、ブランチにマージする。
