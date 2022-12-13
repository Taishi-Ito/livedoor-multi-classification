# livedoor-multi-classification

GoogleColabで文書を多値分類するモデルを作成しました。Pytorch-lightningとBERTを使用しています。
教師データはライブドアニュースコーパスを使用しています。そのまま使用するとout of memory になってしまうので、データ数、ラベル数共に削減しています。
このモデルは3値分類のモデルです。
