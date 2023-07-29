
# 2023年度春学期「学問への扉：天文データ解析」講義資料

講義で使用したPythonプログラムとデータです。リンクから中身を参照できます。随時更新予定（最終更新：2023/7/10）

参考：[Pythonプログラミング入門のページ](https://utokyo-ipp.github.io)

## [lecture8_doppler](https://github.com/kemasuda/astrodata/tree/main/lecture8_doppler)
[ペガスス座51番星（51 Peg）](https://ja.wikipedia.org/wiki/ペガスス座51番星)の視線速度データにおける惑星シグナルの解析。
- [51Peg_rv.txt](https://github.com/kemasuda/astrodata/blob/main/lecture8_doppler/51Peg_rv.txt)：視線速度のデータ
- [lecture8-1.ipynb](https://github.com/kemasuda/astrodata/blob/main/lecture8_doppler/lecture8-1.ipynb)：教材ノートブック（NumPyの使用例, Matplotlibによるグラフ作成）
- [lecture8-2.ipynb](https://github.com/kemasuda/astrodata/blob/main/lecture8_doppler/lecture8-2.ipynb)：教材ノートブック（視線速度シグナルの解析）
- [lecture8-2_sol.ipynb](https://github.com/kemasuda/astrodata/blob/main/lecture8_doppler/lecture8-2_sol.ipynb)：演習の解説

## [lecture9_transit](https://github.com/kemasuda/astrodata/tree/main/lecture9_transit)
[Kepler探査機](https://ja.wikipedia.org/wiki/ケプラー_(探査機)) により得られた恒星 KOI-2（通称[HAT-P-7](https://exoplanetarchive.ipac.caltech.edu/overview/HAT-P-7)）の光度曲線データにおけるトランジットの解析。
- [koi2.txt](https://github.com/kemasuda/astrodata/blob/main/lecture9_transit/koi2.txt)：光度曲線のデータ
- [lecture9-1.ipynb](https://github.com/kemasuda/astrodata/blob/main/lecture9_transit/lecture9-1.ipynb)：教材ノートブック（トランジットの解析、トランジット外の光度変動）
- [lecture9-1_sol.ipynb](https://github.com/kemasuda/astrodata/blob/main/lecture9_transit/lecture9-1_sol.ipynb)：演習の解説

## [lecture10_mass-radius](https://github.com/kemasuda/astrodata/tree/main/lecture10_mass-radius)
太陽系外惑星の質量・半径の関係。
- [mass_radius.txt](https://github.com/kemasuda/astrodata/tree/main/lecture10_mass-radius/mass_radius.txt)：質量と半径の両方が測定された系外惑星のデータ
- [lecture10.ipynb](https://github.com/kemasuda/astrodata/tree/main/lecture10_mass-radius/lecture10.ipynb)：教材ノートブック（質量・半径のプロットと太陽系惑星との比較、惑星の平均密度）
- [lecture10_sol.ipynb](https://github.com/kemasuda/astrodata/tree/main/lecture10_mass-radius/lecture10_sol.ipynb)：演習の解説

## [lecture11_hr](https://github.com/kemasuda/astrodata/tree/main/lecture11_hr)
[Gaia衛星](https://ja.wikipedia.org/wiki/ガイア計画)のデータを用いた恒星の光度と有効温度の関係を示すプロット（[ヘルツシュプルング・ラッセル図; HR図](https://ja.wikipedia.org/wiki/ヘルツシュプルング・ラッセル図)）の作成。
- [gaia_data.csv](https://github.com/kemasuda/astrodata/tree/main/lecture11_hr/gaia_data.csv)：恒星の見かけの等級・年周視差・有効温度のデータ
- [lecture11.ipynb](https://github.com/kemasuda/astrodata/tree/main/lecture11_hr/lecture11.ipynb)：教材ノートブック（恒星の光度と有効温度の関係）
- [lecture11_sol.ipynb](https://github.com/kemasuda/astrodata/tree/main/lecture11_hr/lecture11_sol.ipynb)：演習の解説

## [lecture12_SgrA*](https://github.com/kemasuda/astrodata/blob/main/lecture12_sgrA*)
[いて座A*](https://ja.wikipedia.org/wiki/いて座A*)を公転する恒星[S2](https://ja.wikipedia.org/wiki/S2_(恒星))の軌道データを用いて、いて座A*に存在するブラックホールの質量を推定する。
- [S2.csv](https://github.com/kemasuda/astrodata/blob/main/lecture12_sgrA*/S2.csv)：恒星S2の軌道データ
- [lecture12.ipynb]()：教材ノートブック（S2の軌道長半径と公転周期の導出、ケプラーの第三法則の適用）[後日アップロード予定]
- [lecture12_sol.ipynb]()：演習の解説 [後日アップロード予定]

## [lecture13_hubble](https://github.com/kemasuda/astrodata/tree/main/lecture13_hubble)
[Calán/Tololo Supernova Survey](https://en.wikipedia.org/wiki/Calán/Tololo_Survey)による[Ia型超新星](https://ja.wikipedia.org/wiki/Ia型超新星)のデータを用いて[ハッブル-ルメートルの法則](https://ja.wikipedia.org/wiki/ハッブル–ルメートルの法則)を確認し、ハッブル定数を求める。
- [supernovae.txt](https://github.com/kemasuda/astrodata/tree/main/lecture13_hubble/supernovae.txt)：Ia型超新星の赤方偏移とピーク等級のデータ
- [lecture13.ipynb](https://github.com/kemasuda/astrodata/tree/main/lecture13_hubble/lecture13.ipynb)：教材ノートブック
- [lecture13_sol.ipynb](https://github.com/kemasuda/astrodata/tree/main/lecture13_hubble/lecture13_sol.ipynb)：演習の解説

