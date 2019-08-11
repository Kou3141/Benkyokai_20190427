## ロリポップでdjangoを動かす方法

基本は　https://support.mc.lolipop.jp/hc/ja/articles/360011824713?utm_source=note.mu&utm_medium=referral&utm_campaign=python-release を参照

* 1,2,3はそのまま
(2で作成したsshの鍵は~/.sshに入れ、sshで入るときにオプションの-iでそのパスを指定する)

* 4のpyenvの部分は必要なし

* 5のpipenv〜の部分は必要なpythonのモジュールをpipでインストール
もし、次のエラーが出る場合は次の解決方法をとってください。

    OSError: [Errno 28] No space left on device

    https://qiita.com/kota9/items/2e4f8a0da20eb7df7d16

* 6,7,8もそのままでいける。

例：https://sentimentanalysis.lolipop.io/get/