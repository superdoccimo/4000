# 東証上場株情報全取得VBAマクロ

このプロジェクトでは、Excel VBAを使用して、エクセルブック全体で全銘柄（4000銘柄以上）の株情報を取得することを可能にします。このVBAマクロは、日本証券取引所(JPX)から提供されるコード一覧ファイルを利用し、特定の株価情報を自動的に取得し、エクセルシートに挿入します。

## 機能

- **自動データ取得**: JPXから提供される銘柄コード一覧を使用して、現在値、銘柄名称、出来高などの情報を自動的に取得します。
- **非同期処理の最適化**: Excelの計算能力の制約を回避し、関数が非同期で動作するための適切なタイミングを設定します。
- **大量データの効率的処理**: 4000行以上のデータを効率的に処理するためのループ処理を実装します。

## 前提条件

- Microsoft Excelがインストールされていること。
- 楽天証券のマーケットスピード2にログインしていること。

## インストール方法

このプロジェクトのエクセルファイルには、必要なVBAマクロが既に組み込まれています。以下の手順に従ってファイルを使用してください：

1. このリポジトリからエクセルファイル（`4000over.zip`）をダウンロードして解凍します。
2. 解凍して現れたエクセルファイルを開きます。
3. セキュリティ警告が表示された場合は、「コンテンツの有効化」を選択してマクロを有効にします。

# 株情報取得VBAマクロについて

このプロジェクトでは、Excel VBAを使用して株情報を自動的に取得する方法を紹介しています。詳細な説明と使用方法は、以下のリソースを参照してください。

## 参考資料

- **ブログ記事**: [初回投稿：2023年6月23日](https://minokamo.tokyo/2023/06/23/5790/)
  - このブログ記事では、VBAマクロの作成過程と、その活用方法について詳しく解説しています。

- **YouTube動画**: [初回投稿：2023年6月22日](https://youtu.be/vlVsMPbc8S4)
  - YouTubeでの解説動画では、実際にこのマクロを使用して株情報を取得する様子を示しています。

## 著作権について

このVBAスクリプトとそれに関連するコンテンツは「美濃加茂の蝮」によって作成されました。無断での複製、配布、商用利用は禁じられています。

### 注意喚起

以下のリンクは、私の作成物を無断で使用し、自作のように振る舞っている例です。これらは著作権違反行為であり、公正な利用を阻害しています。

- 不正な動画、チャンネル: [著作権違反の例](https://www.youtube.com/@toushika_byun)

- 不正な動画、チャンネル: [著作権違反の例](https://www.youtube.com/@toushika_byun14)

- 不正な動画そのもの: [著作権違反動画](https://youtu.be/d_UyhCcYRVY)

- 不正な動画そのもの: [著作権違反動画](https://nextcloud.minokamo.xyz/index.php/s/s5my8CH6fkPWJM2)

これらの行為は、創作物の著作権を侵害するものであり、厳しく対処する必要があります。もし、これらの動画が不適切であると考える場合は、YouTubeの報告機能を使用してください。

- 証拠動画: [著作権違反に対する証拠動画](https://youtu.be/aiMoPjpAOXo)

## 貢献方法

このプロジェクトへの貢献や改善提案がある場合は、[Issueを作成](https://github.com/superdoccimo/4000/issues)するか、[Pull Request](https://github.com/superdoccimo/4000/pulls)を送ってください。

## ライセンス

このプロジェクトは[MIT License](https://github.com/superdoccimo/4000/blob/main/LICENSE)の下で公開されています。