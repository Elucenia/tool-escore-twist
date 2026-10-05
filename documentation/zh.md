<!-- ELUCENIA technical documentation · escore-twist · zh · no clinical/professional/rights approval -->

# TWIST 评分（睾丸扭转）

[条件、来源与许可](https://elucenia.org/zh/tools/escore-twist)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 睾丸体积增大（水肿）

`edema`

### 睾丸变硬

`duro`

### 提睾反射消失

`cremaster`

### 恶心或呕吐

`nausea`

### 睾丸位置升高

`alto`

## 方法版本

TWIST/Barbosa 2013：5加权因素，总计0–7

## 已记录的公式

2分：睾丸肿胀；睾丸质硬。1分：提睾反射消失；恶心/呕吐；睾丸高位。总计0至7。

## 限制与适用人群

TWIST 2013最初在急性阴囊症状儿童中开发，由泌尿科医师检查，并对前瞻性队列中全部338名患者实施超声。阈值2和5还在回顾性分析中评估；作者仍要求进行前瞻性验证。这些结果不能保证某人不存在睾丸扭转，也不能代替对潜在外科急症的紧急评估。

## 参考文献

- [Barbosa JA et al. Development and initial validation of a scoring system to diagnose testicular torsion in children. J Urol, 2013.](https://doi.org/10.1016/j.juro.2012.10.056)

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
