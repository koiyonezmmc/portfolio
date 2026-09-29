KY Portfolio - Semantic HTML Version

HTMLをセマンティック寄りに整理しています。

主な変更:
- 実績一覧: ul > li > article
- キャリア: ol > li
- スキル一覧: ul > li
- PERIOD / ROLE: dl / dt / dd
- 作品画像: figure / figcaption
- ページ見出し: header
- 戻る導線: nav
- 各コンテンツ: section / article

レイアウト用のdivは .container など必要な箇所だけ残しています。
divをゼロにすることより、内容の意味に合うHTML要素を使うことを優先しています。

assets/css/style.css には前回の横スクロール防止対策も含まれています。
