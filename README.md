# item_modifier-copy_custom_data
item_modifierの1項目であるcopy_custom_dataのサンプルになります。

~詳しくはブログ記事『[]()』を参考にしてください。~<br>
現在執筆中

<h3>概要</h3>
custom_dataをブロック、エンティティ、storageなどからコピーします。

<h3>使い方</h3>

データパック導入後、ワールドに入り```/reload```と入力し実行してください。

ダイヤモンドが付与されるほか、sample:storageというstorageのex001に1というデータが保存されます。

ダイヤモンドを手に持った状態で以下のコマンドを実行することで、そのダイヤモンドにstorageに保存されたデータを適用させることが出来ます。

```copy
/item modify entity @s weapon.mainhand sample:copy_custom_data
```

データがコピーされているかどうかは、確認したいアイテムをに手に持った状態で以下のコマンドを実行します。

```copy
/data get entity @s SelectedItem
```
