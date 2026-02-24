# Lua Snippets for Stormworks　について

このリポジトリはゲーム「[Stormworks: Build and Rescue](https://store.steampowered.com/app/573090/Stormworks_Build_and_Rescue/)」で使用するLuaスクリプトをVSCodeで記述する際に、ゲーム内に用意されている関数を簡単に書けるようにするための設定ファイル群である。

## 使用手順

前提として下記の拡張機能を事前にインストールしておくことをお勧めする。

[LuaHelper Guide (ID: yinfei.luahelper)](https://marketplace.visualstudio.com/items?itemName=yinfei.luahelper)

上記以外の拡張機能でも大体可能だが、stormworks内の文字数制限などを考慮した LuaHelper Guide 用の設定ファイルが存在しているため、LuaHelper Guide を導入することをお勧めする。

### git clone　する場合

1. このリポジトリを `git clone` する
2. クローンしたプロジェクトの配下でLuaスクリプトを記述する

### コピー&ペーストする場合

1. VSCodeで任意のワークスペースを用意する
2. ワークスペースのルートに本リポジトリの `.vscode/` のディレクトリを配下ごとコピーして貼り付ける
3. ワークスペースの配下でLuaスクリプトを記述する

## 注意事項

本プロジェクトはあくまでスニペットを提供するだけであり、コード補完やフォーマットなどの機能は提供していません。それらの機能が欲しい場合は前述の [使用手順](#使用手順) に記した拡張機能やそれらに準ずるものをVSCodeに別途導入してください。

また、StormworksにおけるLuaスクリプト関連で何かしらの更新があった場合はこのリポジトリをメンテンスする予定ですが、それ以外に私自身が更新した方が良いなと感じたタイミングや、強い要望があった際には適宜メンテナンスを行う予定です。
