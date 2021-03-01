# PLAsTiCC
kaggleのPLAsTiCCコンペで書いたコード。
モデル構築部分のコードのみ。
特徴量作成部分はGCPとか色々なところに色々なコードが散らばっていてまとめるのに時間かかりそうだったので勘弁してください…。

```
lightgbm_binary_logloss_oof.ipynb：各クラスに属するか否かの2値分類
lightgbm_multiclass_model.ipynb:binary_oofの結果も入れて多値分類
lightgbm_specz.ipynb:speczカラムを入れた多値分類
MLP.ipynb：MLP
score_merge_and_post_process.ipynb:lgbとmlp重み付け
```

