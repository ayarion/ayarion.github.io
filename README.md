# 作り場

つくったものを置いておく場所。 https://tsukuriba.org/

個人開発したアプリをここにまとめている。各アプリは独立したリポジトリで管理し、このページから辿れるようにしている。

## 置いてあるもの

- **[トガメ](https://github.com/ayarion/togame)** — SNSを開いた瞬間に「なんで開いたの？」と問い返すアプリ（[公開ページ](https://tsukuriba.org/togame/)）
- **[Kinto-Log](https://github.com/ayarion/kinto-log)** — かわいく続ける、筋トレ記録アプリ（[公開ページ](https://tsukuriba.org/kinto-log/)）
- **[OjiMate](https://github.com/ayarion/OjiMate)** — 集中すれば働き、サボれば一緒にサボる、表裏一体のおじさんと暮らす集中アプリ（[公開ページ](https://tsukuriba.org/OjiMate/)）

## 技術

- HTML / CSS / JavaScript（このトップページはビルド不要の単一ファイル）
- ヒーローはガラスのチェーンを WebGL で生成して軸回転させている（three.js r152 を `assets/vendor` に同梱、CDN 非依存）
- チェーンの奥に置いた PORTFOLIO の文字をガラスが屈折させる
- スクロールするとアプリのスクリーンショットが 3 列で流れ続けるショーケースが立ち上がる（CSS アニメーション）
- フォントは Google Fonts（Inter Tight）
- ショーケース用の画像は `assets/stream` に webp で配置
- GitHub Pages + カスタムドメイン
