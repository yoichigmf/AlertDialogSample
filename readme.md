# QGISアラートダイアログサンプル


QGISプラグインで目立つダイアログを作るときのサンプル



## AlertDialog_Dialog

QPropertyAnimationを利用してバックグランドカラーを変更する

```
    color1 = QColor(255, 0, 0)
    color2 = QColor(0, 255, 0)
    dlg = AlertDialog_Dialog(color1, color2)

    dlg.show()
```
コンストラクタで2色の色を指定する

## 音声ファイル

OtoLogic  https://otologic.jp/  CC BY 4.0で公開されている音声ファイルを利用