experimental_dem
================
国土地理院ベクトルタイル提供実験（基盤地図情報（数値標高モデル））
# 数値標高モデルの GeoJSON タイル
国土地理院ベクトルタイル提供実験の対象地区（第一次地域区画 5439, 5440, 5638, 5639）について、
基盤地図情報（数値標高モデル）の5mメッシュ（航空レーザ測量）及び10mメッシュ（地形図の等高線）を
ズームレベル 18 の GeoJSON タイルに変換したものを提供実験いたします。それぞれのデータの
仕様は次のとおりです。

## 基盤地図情報（数値標高モデル）5mメッシュ（航空レーザ測量）（DEM5A、高さ精度0.3m）
テンプレート URL: http://cyberjapandata.gsi.go.jp/xyz/experimental_dem5a/{z}/{x}/{y}.geojson

サンプル：http://cyberjapandata.gsi.go.jp/xyz/experimental_dem5a/18/233094/102736.geojson

## 基盤地図情報（数値標高モデル）10mメッシュ（地形図の等高線）（DEM10B、高さ精度5m）
テンプレートURL：http://cyberjapandata.gsi.go.jp/xyz/experimental_dem10b/{z}/{x}/{y}.geojson

サンプル：http://cyberjapandata.gsi.go.jp/xyz/experimental_dem10b/18/233094/102736.geojson

# データ内容の詳細について
データの内容の詳細については、
基盤地図情報（数値標高モデル）の種類と概要（http://fgd.gsi.go.jp/download/DEMkind.htm ）や基盤地図情報 ダウンロードデータ　ファイル仕様書4.0　(1,138KB　PDFファイル)（http://fgd.gsi.go.jp/otherdata/spec/2014/FGD_DLFileSpecV4.0.pdf ）をご覧ください。

# デモサイトについて
デモサイトを次の場所に用意しております。
http://gsi-cyberjapan.github.io/experimental_dem/

ズームレベル18以上でDEM10Bのデータを赤文字で、ズームレベル19以上でDEM5Aデータを
青文字で表示します。文字列の中央がメッシュ中心点（サンプリング点）となります。
小さいズームレベルでは、提供実験の範囲をポリゴンで表示します。

# 提供の位置づけ
国土地理院ベクトルタイル提供実験におけるデータの提供の位置づけは次のとおりです。
- 本提供実験は、ベクトルタイル提供における技術的・施策的課題を国土地理院が把握するとともに、外部からの技術的な提案を受け取り、外部との技術的な議論を通じてベクトルタイルの適切な提供方法を研究開発することを目的とするものです。
- 本提供実験の期間は、2014年8月1日から本提供実験終了までとなります。
- 本提供実験は、予告なく内容変更したり提供停止したりする場合があります。
- 本提供実験のベクトルタイルは基本測量成果と位置付けているものではありませんが、基本測量成果としての提供を検討するにあたって、提供を行うものです。
- 本提供実験の利用により生じた損失及び損害等について、国土地理院はいかなる責任も負わないものとします。

# 履歴
2014-10-31 基盤地図情報（数値標高モデル）の提供実験を開始
