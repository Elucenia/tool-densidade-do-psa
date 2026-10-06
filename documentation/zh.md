<!-- ELUCENIA technical documentation · densidade-do-psa · zh · no clinical/professional/rights approval -->

# PSA 密度

[条件、来源与许可](https://elucenia.org/zh/tools/densidade-do-psa)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 总 PSA

`psa`

ng/mL · 范围: 0.1–1000

### 前列腺体积（经直肠超声或 MRI）

`vol`

mL (cm³) · 范围: 5–400

## 方法版本

PSA密度/Benson 1992：PSA/体积，ng/mL/cm³；不假定通用阈值

## 已记录的公式

PSA密度（ng/mL/cm³）= 总PSA ÷ 前列腺体积。

如果仅有前列腺的三个径线，请先计算前列腺体积。

## 限制与适用人群

Benson 1992在男性中研究PSA密度，采用经直肠超声测量前列腺体积，以及Hybritech检测法测得的中间范围PSA值4.1–10 ng/mL。文章描述了风险列线图；单独的PSA/体积值不能构成诊断，也不能确立通用阈值。应考虑体积测量方法、PSA检测法和适用人群。

## 参考文献

- [Benson MC et al. The use of prostate specific antigen density to enhance the predictive value of intermediate levels of serum prostate specific antigen. J Urol, 1992.](https://doi.org/10.1016/S0022-5347(17)37394-9)

- [Nordström T et al. Prostate-specific antigen (PSA) density in the diagnostic algorithm of prostate cancer. Prostate Cancer Prostatic Dis, 2018.](https://doi.org/10.1038/s41391-017-0024-7)

## 复现技术测试

在此仓库的根目录中运行 node test.cjs，以重复已记录的合成案例。原始输入、预期结果和容差保持不变。技术测试不构成临床验证。

```sh
node test.cjs
```

tool.json 包含来源、版本和审查范围。examples.json 保留合成输入与预期结果；results.json 记录实际得到的结果。

[记录与参考文献](../tool.json) · [JavaScript代码](../calculator.js) · [参考案例](../examples.json) · [results.json](../results.json)

## 审查与使用条件

尚未开展独立临床审查。

此界面为自主编写的翻译，并非官方或认证版本。尚未完成独立临床审查、专业语言审查或工具权利授权。

公式或分类结果。解释、处理及适用性须结合专业评估和所选来源。

## 许可与署名

Apache-2.0 仅适用于 ELUCENIA 代码。工具、出版物、翻译和数据的权利仍归各自权利人所有。请保留 LICENSE 和 NOTICE。

ELUCENIA · Felipe Guedes · Copyright © 2026

## 已记录的结果

以下信息保留该方法对合成示例的输出，不构成独立的临床验证。

### 1

密度 < 0,10：临床显著性癌症的概率较低


### 2

密度在0,10和0,15之间：中间区间


### 3

密度 ≥ 0,15：高于经典阈值，有利于癌症检查

