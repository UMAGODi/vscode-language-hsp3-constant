# language-hsp3-constant for VSCode

現在公開されているlanguage-hsp3に、Win32API定数のシンタックスハイライトを追加するものです。
 
![image](https://raw.githubusercontent.com/UMAGODi/vscode-language-hsp3-constant/master/highlight.png)

## 注意点
Win32API定数の数が尋常ではないためファイルを開いた際に**エディタが重くなります。**  
もしフリーズしたり作業に支障がでるようでしたら無効化するかアンインストールしてください。

## インストール
必要なもの
* Visual Studio Code
* この拡張機能
* language-hsp3 (無くともハイライトは可能)
* language-hsp3-ex (無くともハイライトは可能)

手順
1. language-hsp3をインストールする
2. language-hsp3-exをインストールする
3. language-hsp3-constantをインストールする
4. 試しにHSPファイル(.hsp, .as)にalCreateImageやSetWindowLong等を書いてみて反映されていれば完了


## スコープ名詳細
色を好みのものに変更したいとき等に使用するスコープ名です。

`constant.win32api.hsp3`

### サンプル
_Win32API定数の色を赤に変更したい場合 (settings.json)_
```json
{
  "scope": "constant.win32api.hsp3",
  "settings": {
    "foreground": "#FF0000"
  }
}
```


## バージョン履歴

### v1.0.1 [2020/03/09]
* 初版