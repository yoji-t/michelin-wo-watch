# ミシュラン PCT国際公開ウォッチ

ミシュラン（出願人に Michelin を含むもの）のPCT国際公開を、WIPO PCT公報の週ごとにまとめた静的サイトです。
各週のレポートでは、発明の要約と国際調査報告（ISR）のX文献・その出願人を整理しています。

公開URL: https://yoji-t.github.io/michelin-wo-watch/

## 構成

- `index.html` … トップページ（週次レポートの一覧、新しい順）
- `weeks/YYYY-WW/index.html` … 各週のレポート（1ファイルで完結するHTML）
- `weeks.json` … 週次レポートの一覧データ
- `.nojekyll` … GitHub Pages で Jekyll の処理を無効にするための空ファイル

## 新しい週の追加方法

1. `weeks/YYYY-WW/index.html` にレポートを置く
2. `index.html` の `WEEKS-LIST` コメント内の `<ul>` の先頭に `<li>` を1行追加する
3. `weeks.json` の先頭に同じ週の項目を追加する

GitHub Pages は main ブランチのルートから配信しています。ビルド処理はありません。

## 注記

要約は公開文献に基づく参考情報です。法的な判断には公式の公開PDFを参照してください。
