# Lilja Custom Project Window

[![license](https://img.shields.io/badge/LICENSE-MIT-green.svg)](LICENSE)
![unity-version](https://img.shields.io/badge/unity-6000.0+-blue.svg)

Unity のアセットを任意のグループやフォルダ参照で整理できるエディター拡張です。

## インストール

Package Manager の **Add package from git URL...** に以下を入力します。

```text
https://github.com/kamahir0-lilja/CustomProjectWindow.git?path=/Packages/com.kamahir0.custom-project-window
```

または `Packages/manifest.json` の `dependencies` に追加します。

```json
"com.kamahir0.custom-project-window": "https://github.com/kamahir0-lilja/CustomProjectWindow.git?path=/Packages/com.kamahir0.custom-project-window"
```

EditorEx 版と同じアセンブリを含むため、移行時は EditorEx 版を取り除いてからインストールしてください。

## 使い方

Unity のメニュー **Lilja > EditorEx > Custom Project Window > Open Window** から開きます。グループを作成し、Project ウィンドウからアセットやフォルダをドラッグして整理できます。保存先は同メニューの **Save Mode** で選択できます。既定ではプロジェクトの `UserSettings/CustomProjectWindowSettings.json` に保存します。

## 開発

リポジトリのルートを Unity プロジェクトとして開きます。パッケージ本体は `Packages/com.kamahir0.custom-project-window/`、開発用アセットは `Assets/Development/` にあります。

## ライセンス

[MIT License](LICENSE)
