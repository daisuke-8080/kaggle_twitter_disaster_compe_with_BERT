# BERTをkaggleコンペで使ってみた
kaggleの「Natural Language Processing with Disaster Tweets」に自然言語処理アルゴリズムとして有名なBERTを使って参加しました。

BERTのアルゴリズムを勉強しているうちに実際に使ってみたくなったので、アウトプット代わりにこちらのコンペに参加しました。

方法としては、Pytorchのライブラリの一つであるtransformersから学習済みBERTをインポートしてファインチューニングしました。

結果：
約800チーム中188位でした。
「＜＞/ _ * # []」のような記号を取り除いてから識別モデルにかければさらにscoreが上がったかなと思いますが、ひとまずBERTの実践ができてよかったです。

<img width="1440" alt="my_socore" src="https://user-images.githubusercontent.com/102433704/196703901-4edd6b89-fb46-4792-8b54-1b60f3d2f713.png">
