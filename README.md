# dajare-minigames

ダジャレのお題を数秒でこなすミニゲーム集のブラウザ版。遊ぶ: https://qorigame256.github.io/dajare-minigames/

- `app/` は Godot 4.7.1 の Web 書き出し（スレッドなし）で作ったもの。手で直さず、元のプロジェクトから書き出し直す。
- main に push すると `.github/workflows/pages.yml` が `app/` だけを GitHub Pages に公開する。
- 日本語の字体 Noto Sans JP（SIL Open Font License 1.1）を `app/index.pck` に同梱している。使用許諾は `LICENSE_font_NotoSansJP.txt`。
