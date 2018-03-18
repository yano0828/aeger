aeger  Copyright(C) Ken Yano	

≪著作権および免責事項≫

本ソフトはフリーソフトです．自由にご使用ください．なお，著作権は作者
である矢野　憲が保有しています．

このソフトウェアを使用したことによって生じたすべての障害・損害・不具
合等に関しては、私と私の関係者および私の所属するいかなる団体・組織とも、
一切の責任を負いません．各自の責任においてご使用ください．


■ はじめに
本ソフトウエアは，テキストから病名を抽出するコマンドラインツールです．


■ 動作環境
Windows 10
(Windows 10以外のWindows OSについては動作確認は行っていません）


■ インストール方法
MedInput.zip　を適当なフォルダに解凍してください．



■ 使用方法

aeger: A Japanese NLP tool to extract medical entity with its polarity judgement
Usage: aeger [options]
 -s, --standard name                    print suggested standard disease name.
 -c, --ICD10 code                       print corresponding ICD10 code.
 -h, --help                             show this help and exit.
 -v, --version                          show the version and exit.

At the prompt, enter input sentence. The 'return' is recognized as the end of sentence
The output is the input sentence with <P> and <N> tags
        <P> tag: Extracted medical entity whose polarity is judged as positive.
        <N> tag: Extracted medical entity whose polarity is judged as negative.


■ 関連論文

aeger の詳細な内容については，以下の論文を参照してください．

・矢野,伊藤，若宮，荒牧，”深層学習による医療テキストからの固有表現抽出器の開発とその性能評価”，人工知能学会，5月，2017
