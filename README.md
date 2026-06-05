# GreenCross 地図パスデータ

OpenStreetMap から地図データを取得し、Illustrator編集用のSVGを生成するWebツールです。

🔗 **公開URL**: https://snowdrop-lab.github.io/[repo-name]/

## できること

- 座標（緯度・経度）と半径を指定して地図SVGを生成
- レイヤー分けされたSVG出力（建物・道路・鉄道・水域・土地利用）
- ブラウザだけで完結（インストール不要）
- Mac/Windows/iPad など全環境で動作

## 使い方

1. 上記URLにブラウザでアクセス
2. 座標と半径を入力
3. 「OSMデータを取得」をクリック
4. 取得後に「⬇ SVGをダウンロード」
5. SVGをIllustratorで開く

詳しい手順はサイト内「📖 簡単な使い方」セクションを参照。

## 初回セットアップ

レイヤー昇格スクリプト `promote_groups_to_layers.jsx` をIllustratorの
スクリプトフォルダに配置すると、開いた後ワンクリックでグループがレイヤーに昇格します。

サイト内「📦 初回セットアップ」セクションから JSX をダウンロードして手順に従ってください。

## クレジット・ライセンス

- 地図データ: © OpenStreetMap contributors ([ODbL](https://opendatacommons.org/licenses/odbl/))
- 生成SVGの左下に **「© OpenStreetMap contributors」** の表記が自動で入ります。
  この表記は**削除しないでください**（OSMライセンス要件）。

## 作者

GreenCross-YAMAGATA+S
