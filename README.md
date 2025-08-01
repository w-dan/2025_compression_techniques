# Graphics Documentation

## Base Techniques vs Additional Techniques

Heatmap illustrating the co-occurrence between model compression techniques (rows) and additional techniques (columns).

![Base Techniques vs Additional Techniques](./graphics/non_exclusive_and_additional.png)

Quantization is the most widely adopted technique, with 14 standalone papers, while pruning and its combination with quantization show more moderate adoption with 11 and 9 papers respectively. The combination of multiple compression techniques is relatively rare, with quantization+pruning being the most popular hybrid approach.


---

## Additional Techniques vs Models


Heatmap showing the frequency of use of additional techniques (columns) across different NN models (rows), highlighting patterns of model-technique associations.

![Additional Techniques vs Models](./graphics/top_models.png)

ResNet-50 appears as the most popular model for evaluating additional compression techniques, especially with preprocessing methods. Context-dependent or more specialized techniques show limited adoption across different architectures, with hardware optimization being the second most explored approach.

---

## Co-application Heatmap

Heatmap depicting the frequency of co-application between exclusive model compression techniques (rows) and additional strategies (columns), indicating how often each additional technique is used in conjunction with a single compression method.

![Co-application Heatmap](./graphics/exclusive_and_additional.png)

Preprocessing techniques are most commonly applied in combination with quantization methods, appearing in 16 papers in total. Compact network design and hardware-based optimization demonstrate notable compatibility with quantization, pruning, and knowledge distillation techniques.

---

## Article Yearly Distribution

Annual distribution of published articles from 2017 to February 2025, showing the total number of publications per year (black line) and the yearly breakdown of articles employing specific model compression techniques (stacked bars).

![Article Yearly Distribution](./graphics/year.png)

Neural network compression research peaked in 2021-2022, showing sustained interest in the field. Quantization maintains consistent popularity throughout all years, while hybrid approaches like quantization+pruning emerge more prominently in recent years.

---
