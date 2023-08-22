# Desynced Japanese Language Mod
Stage Game Inc.によるゲーム[「Desynced」](https://store.steampowered.com/app/1450900/Desynced/)の日本語化Modです。

Stage Game Inc.のbeatwho氏によって原型が作られ、それを許諾を得た上で編集しています。

# 開発フロー
翻訳ファイルが1つのjsonであるため、conflictが多く発生する事が予想されます。そのため、masterブランチへの直接pushを禁止する設定にしています。
そのため、以下の様なフローで開発を進めてください。

1. ローカルでブランチを作成する
2. 編集する
3. 変更内容をcommit & pushする
4. 自身のブランチからmasterへのPull requestを作成する
5. Pull requestをmergeする

これにより、conflictが発生した際には可能な限り自動解決が行われ、不可能な場合は手動での解決を求められます。
また、ローカルのmasterブランチは新規ブランチ作成前に必ず更新(pull)してください。
