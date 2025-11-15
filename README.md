# 卒論解析用のプログラムやデータを保存するリポジトリ
# EGG data
mat_to_csvフォルダは、SSSEP~.mat(生データ)から、各端子のPLIを算出したcsvファイルの出し方。
実行結果は、PLI_0_kumakura_rest.csv,concentration_1_kumakura_practice.csvが出力される。場所は、csv->0_kumakura->PLIdata
現在、yamashita_overloadだけがエラーでてうまくいっていないけど

PLI_Analysis.ipynbはmat_to_csvで作成したcsvファイルを使って一秒ごとのPLIを算出して描画するプログラム。
PLI_Analysisいじった2.ipynbはpracticeしか成功してない😭その理由はpractice以外のcsvファイルは7端子の列まで表示しているから。

# ECG data
mat_to_csvフォルダは、SSSEP~.mat(生データ)から、心電図を算出したcsvファイルの出し方。
実行結果は、ECG_kumakura_boredom.csvが出力される。場所は、csv->0_kumakura->ECG


constants.pyはpath_to_matlab_repository_folder = "/content/soturon"を変更
