# shirochizu-data

散歩アプリ「白地図さんぽ（仮）」が読む公開データ。GitHub Pages で配る。

## chome/v1

町丁目（町丁・字）の境界。市区町村ごとの GeoJSON（`<市区町村コード 5 けた>.json`）と、市区町村の一覧 `index.json`。

- 出典：政府統計の総合窓口(e-Stat)（https://www.e-stat.go.jp/）
  国勢調査 2020年 小地域（町丁・字等）境界データ を加工して作成
  （町丁・字だけを残し、KEY_CODE ごとにまとめ、形を軽くして市区町村ごとに分けた）
- 作り方：アプリのリポジトリの `tool/chome/build_chome.sh`
- 利用条件：政府標準利用規約（第 2.0 版）に準じる e-Stat の利用規約に従う
