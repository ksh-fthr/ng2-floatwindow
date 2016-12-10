はじめに
-------------------------------------------------------------
FloatWindow は動的にフロートウィンドウを生成するライブラリです.

機能
-------------------------------------------------------------
FloatWindow には以下の機能を設けています.

1. 表示 /　非表示の切り替え
2. 幅 / 高さを設定
3. 背景色の設定
4. 表示したフロートウィンドウのドラッグ＆ドロップ

使い方
-------------------------------------------------------------
sample.html をご参照ください.

API
-------------------------------------------------------------
## v0.0.3
現在、次のAPIを提供しています.

### setWidth()
* フロートウィンドウの幅を設定する.

### setHeight()
* フロートウィンドウの高さを設定する.

### setBgColor(headerBg, contentsBg, footerBg)
* フロートウィンドウのヘッダ、コンテンツ、フッタの各背景色を設定する.

### show()
* フロートウィンドウを表示する.

### hide()
* フロートウィンドウを非表示にする.

### isDraggable()
* フロートウィンドウに対してDrag & DropのON/OFFを設定する.
 * ONの場合, フロートウィンドウの移動ができる
 * OFFの場合, フロートウィンドウの移動ができない

### isRestrictMoveRange()
* フロートウィンドウの移動範囲に対する制限のON/OFFを設定する.
 * ONの場合, ブラウザの領域から外れてフロートウィンドウが隠れないよう制限する
 * OFFの場合, ブラウザの領域内から外れてフロートウィンドウが隠れても移動できる
