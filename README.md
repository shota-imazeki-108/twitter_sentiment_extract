# [Tweet Sentiment Extraction](https://www.kaggle.com/c/tweet-sentiment-extraction)
## Extract support phrases for sentiment labels
---
## これは何か
- Tweet Sentiment Extractionにて使用したコード類をまとめました。
- 社内勉強会にて振り返りをしました。詳細は `./notebooks/振り返り会資料.ipynb` にて確認いただければと思います。

## コンペ概要
- tweet文とそれにラベル付けされたsentiment(positive, negative, neutral)のデータをもとに感情を表す文を抜き出す。

## 使用したノートブック
- ./notebook/tweet_sentiment.ipynb
- colabで動かす前提のノートブックのため、序盤にgoogle drive マウントの処理が記載されています。

## データ
- [こちらから](https://www.kaggle.com/c/tweet-sentiment-extraction/data)
- 規約に同意する必要あり

## モデル
- BERT: [こちらから](https://www.kaggle.com/abhishek/data)ダウンロードしてください。
- RoBERTa: [こちらから](https://www.kaggle.com/abhishek/roberta-base)ダウンロードしてください。

## 結果
- 上位12%であったもののメダル獲得ならず...(10%以上がメダル)

## おまけ
- 本コンペとは直接関係ないが、BERTのattention headの可視化をしてみた。
- 目的は、deep learning モデルの解釈性を高めるため。
- コードは、 `./research/bert/` にある。