# 横浜建設防火検査 非常用照明ページ（仮ページ / デモ）

実サイト（https://yokohamakensetsuboukakensa.jp/emergency-light/ ）で使用されている
動画・画像アセットを当てはめたデモ用の1ページサイトです。

## 収録アセット（assets/）
- yokohama.png … ロゴ
- site_video.mp4 … 停電・非常灯の解説動画（ヒーロー背景＋再生セクション）
- video_poster.jpg … 動画のポスター画像（動画から抽出）
- 23281619_s.jpg … 天井の非常用照明器具
- AdobeStock_1928064202.jpeg … 暗い通路（バンド背景）
- AdobeStock_457156842-768x512.jpeg … 担当者（シルエット）
- AdobeStock_1029135121-1-2.png … 小アイコン

## GitHubで公開する手順（GitHub Pages）
1. GitHub で新しいリポジトリを作成（例: `yokohama-emergency-light-demo`、Public）。
2. このフォルダの中身（index.html / assets/ / .nojekyll / README.md）をすべてアップロード
   （リポジトリ画面の「Add file」→「Upload files」でドラッグ＆ドロップでOK）。
3. リポジトリの Settings → Pages → Build and deployment の Source を
   「Deploy from a branch」、Branch を `main` / `/ (root)` に設定して Save。
4. 数十秒〜数分後、`https://<ユーザー名>.github.io/<リポジトリ名>/` で公開されます。

※ index.html には noindex を設定済み（検索エンジンにインデックスされません）。
※ アセットは実サイトのものです。公開範囲はご自身の権利範囲でご利用ください。
