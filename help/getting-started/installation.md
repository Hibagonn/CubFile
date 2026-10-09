# インストール

## この機能でできること

CubFile を Windows に置いて、起動できる状態にします。インストーラーでレジストリへ登録する方式ではありません。フォルダを展開して `CubFile.exe` を起動します。

## 操作前の準備

- Windows の PC を用意します。
- 配布物は [GitHub Releases](https://github.com/Hibagonn/CubFile/releases) または Vector から入手します。
- 新規導入用のファイルは `CubFile-<バージョン>-win64.zip` です。
- `CubFile-<バージョン>-Updater.exe` は、すでに入っている CubFile を更新するときに使います。
- GitHub が自動で付ける Source code の zip や tar.gz は、実行用の CubFile ではありません。

## 操作手順

1. `CubFile-<バージョン>-win64.zip` を、わかりやすいフォルダへ展開します。
2. 展開したフォルダの `CubFile.exe` をダブルクリックします。
3. 次回からすぐ開けるよう、ショートカットをデスクトップやスタートメニューへ作ってもかまいません。

## 操作中の画面

起動すると、フォルダを表示するパネルと、左側のサイドバーが出ます。画面の詳しい見方は [画面構成](screen-layout.md) です。

## 完了の確認方法

ウィンドウのタイトルに CubFile と出て、サイドバーからドライブやフォルダを開けることを確認します。

## 注意事項

- ZIP の中の `CubFileUpdater.exe` は、本体を更新するためのプログラムです。普段のファイル操作には `CubFile.exe` を使います。
- `.sha256` ファイルは、配布 ZIP の整合性を確認するためのものです。起動ファイルではありません。
- 設定は、通常 `%LOCALAPPDATA%\CubFile` に保存されます。エクスプローラーのアドレス欄に `%LOCALAPPDATA%\CubFile` と入力すると開けます。

## よくあるトラブル

起動しないときは [トラブルシューティング](../troubleshooting/index.md) を見てください。すでに CubFile が起動していると、新しいウィンドウは作られず、開いているウィンドウを前面に出します。

## 関連するヘルプページ

- [初回起動](first-launch.md)
- [手動更新](../updates/manual.md)
- [重複起動](../settings/single-instance.md)
