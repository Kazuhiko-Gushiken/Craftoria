---
navigation:
  title: "エリアウィジェット"
  icon: "pneumaticcraft:textures/progwidgets/area_piece.png"
  parent: pneumaticcraft:widget_other.md
---

# エリアウィジェット

*エリア*ウィジェットは他のウィジェットのパラメータとしてのみ使用され、ウィジェットに適用するエリア(単一のブロックの場合もあります)を指定します。このウィジェットを使用するには[GPSツール](../tools/gps_tool.md)および/または[GPSエリアツール](../tools/gps_area_tool.md)が必要です。

エリアウィジェットを設定する一般的な方法は3つあります:

1. [プログラマー](./programmer.md)GUIでエリアウィジェットを*右クリック*して設定GUIを開いてそこで設定します。2つの*GPS*ボタン(クリックすると別のGUIが開き、インベントリから[GPSツール](../tools/gps_tool.md)を選択)を使用してエリアの範囲を設定し、その下のラジオボタンを使用して*エリアタイプ*と関連するパラメータを選択します。

2. ワールド内で[GPSツール](../tools/gps_tool.md)または[GPSエリアツール](../tools/gps_area_tool.md)を設定します。 [プログラマー](./programmer.md)GUIでは、次の操作を実行できます。
- 既存の*エリア*ウィジェットで*GPS(エリア)ツール*を*左クリック*してツールの設定をウィジェットにコピーします。
- 空のプログラミング領域で*GPSツール*を*左クリック*して、新しい[座標](./coordinate.md)ウィジェットを作成します。
- 空のプログラミング領域で*GPSツール*を*Shiftキーを押しながら左クリック*して、新しい*エリア*ウィジェットを作成します。
- 空のプログラミング領域で*GPSエリアツール*を*左クリック*して、新しい*エリア*ウィジェットを作成します。

3. 高度なオプション: [座標演算](./coordinate_operator.md)ウィジェットによって作成された*変数*を使用できます。変数を使用するには[プログラマー](./programmer.md)が*高度*モードになっている必要があります。GPSボタンの横にドロップダウン選択フィールドも表示されます。そこで既知の変数名を選択するとこのエリアの対応するコーナーでその変数の位置が使用されます。

*エリアウィジェット*

![](area_piece.png)

