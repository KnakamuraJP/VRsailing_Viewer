# VRsailing Viewer

このリポジトリは、VR Sailing の 360° スナップショットを GitHub Pages で公開するための静的サイトです。

各 `*.html` は 1 枚の 360° パノラマ画像を埋め込んだ単体ビューアで、ブラウザだけでそのまま閲覧できます。追加のアプリやサーバーは不要です。

## これは何のページか

- セーリング中の視点を 360° で見渡せるスナップショットページです
- `gh-pages` ブランチの内容が、そのまま GitHub Pages として公開されます
- 各 HTML は独立していて、URL を直接共有すればそのまま閲覧できます

## 公開ページ

- ギャラリートップ: https://knakamurajp.github.io/VRsailing_viewer/
- Port view: https://knakamurajp.github.io/VRsailing_viewer/portview_upwinndsailing_snap_0m19s_1.html
- Starboard view: https://knakamurajp.github.io/VRsailing_viewer/starboradview_upwindsailing_snap_0m49s.html

## 使い方

1. 上の公開 URL をブラウザで開きます
2. 画面をドラッグ、またはスワイプして視点を動かします
3. マウスホイール、トラックパッド、またはピンチ操作でズームします
4. 右上の `Fullscreen` ボタンで全画面表示に切り替えられます
5. 右下の `FOV` スライダーで視野角を調整できます

## ファイル構成

- `index.html`: GitHub Pages のトップページ
- `portview_upwinndsailing_snap_0m19s_1.html`: ポート側視点の 360° スナップショット
- `starboradview_upwindsailing_snap_0m49s.html`: スターボード側視点の 360° スナップショット

## 技術メモ

- ビューアは `three.js` を CDN から読み込んで描画しています
- 画像データは各 HTML に埋め込み済みです
- そのため、単一 HTML ファイルだけでも閲覧できます

## 運用メモ

- ページを追加する場合は、新しいスナップショット HTML を `gh-pages` に追加します
- ページを削除または差し替える場合は、対象 HTML を削除し、必要に応じてこの README のリンクも更新します
- 旧ページ `portview_upwinndsailing_snap_0m19s.html` は削除済みです
