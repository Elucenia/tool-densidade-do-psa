<!-- ELUCENIA technical documentation · densidade-do-psa · ja · no clinical/professional/rights approval -->

# PSA密度

[条件・出典・許諾](https://elucenia.org/ja/tools/densidade-do-psa)

## 使い方

ポータルでツールを使用するか、ローカルHTTPサーバー経由でindex.htmlを開いてください。言語を選択し、項目を入力して計算してください。

## 入力項目と単位

### 総PSA

`psa`

ng/mL · 範囲: 0.1–1000

### 前立腺体積（経直腸超音波またはMRI）

`vol`

mL (cm³) · 範囲: 5–400

## 方法の版

PSA密度/Benson 1992：PSA/体積、ng/mL/cm³；普遍的な閾値を仮定しない

## 記載された計算式

PSA密度（ng/mL/cm³）= 総PSA ÷ 前立腺体積。

前立腺の3方向の測定値のみの場合は、まず前立腺体積を計算してください。

## 限界・対象集団

Benson 1992は、男性のPSA密度を、経直腸超音波による前立腺体積とHybritech測定法による中間域4.1–10 ng/mLのPSA値で研究しました。論文ではリスクのノモグラムを記述しています。PSA/体積という値だけでは診断にならず、普遍的な閾値も定まりません。体積測定法、PSA測定法、適用する集団を考慮する必要があります。

## 参考文献

- [Benson MC et al. The use of prostate specific antigen density to enhance the predictive value of intermediate levels of serum prostate specific antigen. J Urol, 1992.](https://doi.org/10.1016/S0022-5347(17)37394-9)

- [Nordström T et al. Prostate-specific antigen (PSA) density in the diagnostic algorithm of prostate cancer. Prostate Cancer Prostatic Dis, 2018.](https://doi.org/10.1038/s41391-017-0024-7)

## 技術テストの再現

このリポジトリのルートディレクトリでnode test.cjsを実行すると、記録された合成ケースを再実行できます。元の入力、期待結果、許容誤差は保持されています。技術テストは臨床的検証を意味しません。

```sh
node test.cjs
```

tool.jsonには出典、版、確認範囲が記録されています。examples.jsonには合成入力と期待結果が保持され、results.jsonには実際に得られた結果が記録されています。

[記録・参考文献](../tool.json) · [JavaScriptコード](../calculator.js) · [参照ケース](../examples.json) · [results.json](../results.json)

## 確認状況と使用条件

独立した臨床レビューは実施されていません。

このインターフェースは独自に作成した翻訳であり、公式版や認証済みの版ではありません。独立した臨床レビュー、専門家による言語レビュー、評価尺度等の権利許諾の確認は実施されていません。

式または分類の結果です。解釈、対応、適用可能性は専門家による評価と選択した出典に依存します。

## ライセンスと帰属表示

Apache-2.0はELUCENIAのコードにのみ適用されます。評価尺度等、出版物、翻訳、データの権利は、それぞれの権利者に帰属します。LICENSEとNOTICEを保持してください。

ELUCENIA · Felipe Guedes · Copyright © 2026

## 記録された結果

以下の情報は、合成例に対する手法の出力を保持したものです。独立した臨床的検証を示すものではありません。

### 1

密度 < 0,10：臨床的に重要ながんの可能性は低い


### 2

密度が0,10から0,15の間：中間域


### 3

密度 ≥ 0,15：従来の閾値を上回り、がんの精査を支持する

