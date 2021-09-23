# ANAGMA
This program has powered by IchigoJam BASIC.

※ファイル表記の説明※
1.0～3.0までは、暗号化プログラムが『ANAGMA[数字]』、復号化プログラムが『ANAGMA[数字]（）』という表記になっています。

4.0～6.0は１ファイル化された区別をするため、『ANAGMA[数字]＠』という表記になっています。


※基本操作説明：
ANAGMAをスタートさせると、画面中央に「 <<ANAGMA>> 」という文字が表示されます。
１＞画面上部に、「MODE　CHOICE」と表示されます。
「ENCODE：1」と、「DECODE：2」という文字が表示されます。
1を押すと『暗号化モード』になり、2を押すと『復号化モード』になります。
２＞画面上部に「PLEASE INPUT 12 DIGIT CODEKEY」と表示されて、
その下に「<4 DIGIT x3>」と表示されます。
そして、画面中央に「？」と、カーソルが表示されます。
そこに、あらかじめ決めておいた12桁のキーコード(0は使わないこと)を例のように入力します。入力したら、準備OKです。
　　　（例）「123456789123」の場合

　　　　　　　？1234
　　　　　　　？5678
　　　　　　　？9123

３＞画面上部に「INPUT:」、画面中央に「OUTPUT:」と表示されます。
『暗号化モード』のときに平文(読める文章)を入れると、「OUTPUT:」の下に暗号文が出てきます。
『復号化モード』のときに暗号文を入れると、「OUTPUT:」の下に平文が出てきます。
バックスペースを押すと、どちらのモードでも文字を消去することができます。
４＞使える文字・編集機能
使用できる文字は、大文字のアルファベットと数字と、キーボードに書いてある記号(＆、！等)、矢印記号(↑、↓、→、←)が、それぞれのキーを押すと表示されます。
スペースとバックスペースも使えます。
５＞その他
ちなみに、カタカナや小文字のアルファベット、イチゴジャムオリジナルのキャラクターは、暗号化するときに使うと、キーボードで入力できない記号が含まれている暗号文になってしまうので、入力できないようになっています。
ちなみに、ANAGMAでは「F10」キーを押すと、アンダーバー(_)を表示できるようにしました。
また「Delete」キーを押すと、ANAGMAが再起動します。
プログラムの400行目を少し変えると、暗号をさらに複雑にすることができます。

※復号してみて下さい
キーコード： 5264 6463 5322
暗号文　　： MGRPU%
 

※ANAGMA-B特殊操作説明
注意）必ず、I2CのEEPROM (AITENDOのCAT24M01)を差した状態で使ってください。
使い方の変更点は、
・Alt+C で暗号文の保存。Alt+V で暗号文の読み込み。
・最初の画面で、保存した暗号文の閲覧(REVIEW)を追加。
です。
