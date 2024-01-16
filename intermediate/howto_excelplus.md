---
layout: default
title: プラグインの使い方 - ExcelPlus
parent: Grasshopper中級への道
nav_order: 4
---

# プラグインの使い方 - ExcelPlus

**ExcelPlus**は、GH内の値をexcelファイルとして保存する、既存のexcelファイル内のデータをGHへ読み込むためのプラグインです。<br>
GHプログラム内部の値を、excelファイルとして保存するGHサンプルを組んだので参照してください。

<a href="../assets/excelPlusTest.zip">ExcelPlusサンプルファイル</a>

### ファイルの保存先の設定方法
上記GHサンプルには、"セーブするフォルダの場所"と説明されたパネルが内蔵されています。<br>
その名の通り、ここを変更するとexcelが書き出されるフォルダが変更されます。

<img src="../assets/excelplus_01.jpg" alt="hi" class="inline"/>

まず、windowsエクスプロ―ラーを開き、excelファイルを保存したいフォルダまで移動します。<br>
保存先のフォルダを開いた状態で、エクスプロ―ラー上部のパスをクリックし、コピーします。

<img src="../assets/excelplus_02.jpg" alt="hi" class="inline"/>

コピーした文字列を先程のパネルにペーストして、フォルダのパスを上書きすれば保存場所の変更は完了です。<br>
セーブ実行ボタンをおせば、excelファイルを書き出します。

