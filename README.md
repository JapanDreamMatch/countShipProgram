使い方について
使い方を画像付きで確認したい場合 "HowToUseCountProgram.pdf"を参照してください。
ただしpdfで記載されている内容は使い方のみであり、環境構築はREADME.mdのみに記載があります。

**プログラムを利用する前に**
count_groups.pyが存在するディレクトリにtest5.png, test6.pngという画像ファイル2つを準備してください。
この画像ファイルの名前はプログラムのl11で指定しています。変更したい場合はローカル環境で変更してください。
動作環境はpython3.10.8を想定しています。
またプログラム実行に必要な以下のパッケージをインストールしてください。
pip install pytesseract
pip install pillow
pip install openpyxl

次にOCRをインストールします。以下のURLにアクセスし
"The latest installer can be downloaded here:"
とあるものをダウンロードしてください。
https://github.com/UB-Mannheim/tesseract/wiki

パスの設定は各自で行ってください。

**プログラムの利用について**
これらが完了したらターミナル上で
python count_groups.py
によりプログラムを実行してください。

プログラムが正常に動作した場合、同ディレクトリにExcelファイルが保存されます(Excelは使える状態であってほしい...)

新しい画像データを読み込ませたい場合、一度Excelファイルを閉じてからプログラムを実行してください。
開いたままだと内容が更新されない場合があります。

**注意点**
日本語(特に漢字)の認識はできません。また読み取るアルファベットは全て大文字を想定しています。




