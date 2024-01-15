---
layout: main
title: 貢献する
category: About
menu: menu_ja
toc:
    - title: 貢献する
      url: "#貢献する"
      active: true
    - title: 何に取り組むべきか
      url: "#何に取り組むべきか"
    - title: 貢献のための一般的なガイドライン
      url: "#貢献のための一般的なガイドライン"
    - title: プルリクエストを送る
      url: "#プルリクエストを送る"
    - title: コミットメッセージのフォーマット
      url: "#コミットメッセージのフォーマット"
      subitem: true
---
# 貢献する

貢献のご検討ありがとうございます！支援にはたくさんの方法があります。

## 何に取り組むべきか

Screwdriver の全ての issue は、[screwdriver repo][api-issues-url] にあります。私達が現在何に取り組んでいるかは、[Screwdriver API repo][api-repo] の Projects にある [digital scrum board](https://github.com/screwdriver-cd/screwdriver/projects/4) をチェックしてください。どのリポジトリを変更すればよいか分からなければ、[どこに貢献するか](./where-to-contribute)のドキュメントを参照してください。開発の指針に関しては、[開発を開始する](./development)のドキュメントを確認してください。

## 貢献のための一般的なガイドライン

以下のようにお願いします。
* 取り組んでいる [issues](./issues) を更新してください
* issue の番号と feature をチャンネルのタイトルにして (例: `#911-subdirectory-support`) Slack のチャンネルを作成し、そこで議論してください
* 該当する場合は、[design doc](https://github.com/screwdriver-cd/screwdriver/tree/master/design) も追加してください

## プルリクエストを送る

バグ修正、機能追加、改善のパッチはプルリクエストとして受け付けています。以下は貢献する際の参考です。

* わかりやすいコミットメッセージを現在形で(Added XではなくAdd Xのように)書いてください！タイトルは短くし、本文には必要に応じて空行や箇条書きを使ってください。タイトルと箇条書きの先頭文字は大文字にしてください。タイトルに句読点は不要です。
* コードはリンターとスタイルチェックをパスする必要があります。
* すべての手順は文書化されている必要があります。READMEやこの[ガイド][guide-repo]に説明を追加してください。
* コードカバレッジを上げバグの発生や再発を防ぐためにテストコードを含めてください。
* 機能追加/バグ修正ごとに変更をひとつのコミットにまとめてください。どのようにまとめればよいかわからないときはお問い合わせください。
* 可能であれば、プルリクエストに適切な Github のラベルを付けてください。

大掛かりな改善に取り組むときは、それがプロジェクトの目標に沿うものか確認するために事前にお声掛けください。

[api-issues-url]: https://github.com/screwdriver-cd/screwdriver/issues
[api-repo]: https://github.com/screwdriver-cd/screwdriver
[guide-repo]: https://github.com/screwdriver-cd/guide