これは、MUFG Data Science Competition Champion Ship部門 4位入賞した際のコードになります。

提出用.jpynbが、実際にtrainデータから、データ前処理・モデルの学習・モデルの出力から予測の作成までの一連の流れを実行するノートブックになっています。

構造の説明
・パスの定義（train、testデータの位置指定）
・モデル学習（CatBoost、XGBoost、LightGBM、ExtraTrees、線形SVM、ロジスティック回帰をそれぞれ学習し、予測結果を得る）
・アンサンブル（各モデルの学習の際に作ったoofファイルをもとにアンサンブル比率を決め、それをもとに最終予測）
