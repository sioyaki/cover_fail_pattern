--概要
cover_fail_patternは、knewjadeさんが作成したsolution-finderの拡張機能のようなものです。
いままで少し出すのが面倒だったcoverコマンドのFail_pattern(すべての組み方が失敗するパターン)が簡単に出力できるようになります。
--準備
solution-finderのoutputディレクトリに"cover_fail_pattern.exe"を移動させておきます。
--実行
"cover_fail_pattern.exe"をダブルクリックで実行します。
実行に成功すると、outputディレクトリの中に"output_cover_fail.txt"が生成されます。
※元々ファイル内にあった"output_cover_fail.txt"は上書きされます。
※100000文字を超えるcsvファイルを読み込むと実行失敗するので、"cover.csv"のサイズによってはエラーが発生することがあります。エラーが発生したときは、"cover.csv"のサイズを確認して下さい。
--実行結果の見方
実行結果例:
Fail pattern
TIJSLZO
TIJSLOZ
TIJSZLO
TIJSZOL
TIJSOLZ
TIJSOZL
TIJZSLO
TIJZSOL
TISLJZO
TISLJOZ...
二行目以降に失敗パターンが並びます。
--使用したツール
-solution-finder(https://github.com/knewjade/solution-finder/releases/latest) テトリスの「パーフェクトクリア」「REN/Combo」「T-Spin」の手順などを探すためのツールです。このプログラムの実行に使います。
-EasyIDEC(https://9cguide.appspot.com/p_9cide.html) 学習用のC言語開発環境です。このプログラムの作成に使用しました。
