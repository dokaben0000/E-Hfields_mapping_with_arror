# E-Hfields_mapping_with_arror
電場分布と磁場分布をヒートマップ化し、かつ電磁場ベクトルを表現する

作成された画像サンプルは[Issue]に載せている。

●データ詳細

・データ点の座標
・電場intensityの絶対値|x| ----(1)
・電場intensityの絶対値|y| ----(2)
(磁場も同様)

(1)と(2)からベクトルの角度成分をsin,cosで計算。
全ての点を矢印化するとヒートマップが汚くなるので、特定のデータだけピックアップして画像化している。
