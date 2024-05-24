# KiCAD_FootPrint

## このリポジトリについて

このリポジトリは、[@Salicylic-acid3さん](https://github.com/Salicylic-acid3)が作成した[KiCAD用のフットプリントを管理するためのリポジトリ](https://github.com/Salicylic-acid3/KiCAD_FootPrint)のフォークです。

Choc v2のフットプリントをMXからコピーして追加しました。

## KiCadライブラリの管理

[このリポジトリ](https://github.com/njl7502l/njl7502l-kicad-library)を参考にKiCADライブラリをGitHubで管理する方法を検討しています。まだ試していません。

```console
# リポジトリをクローンする
git clone https://github.com/yourusername/your-kicad-project.git
cd your-kicad-project

# サブモジュールを追加する
git submodule add https://github.com/fu2hito/KiCAD_FootPrint.git kicad/footprint/submodule

# サブモジュールを初期化して更新する
git submodule update --init --recursive

# KiCadプロジェクトにPSLを設定
# ここではKiCadのGUIで行うため、具体的なコマンドはありませんが、以下の手順を実行します。
# 1. KiCadを開き、プロジェクトをロードします。
# 2. メニューバーから「Preferences」 > 「Manage Symbol Libraries」を選択します。
# 3. 「Project Specific Libraries」タブを選択し、「Add」ボタンをクリックします。
# 4. 先ほど追加したサブモジュールのパスを指定します。

# 設計を進めます
```

## ライセンス

* [MIT License](LICENSE)

フォーク元のライセンスは[Licence.txt](Licence.txt)を参照してください。
