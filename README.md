# Roformer

Reference paper: https://arxiv.org/pdf/2104.09864.pdf

Reimplementation of Table 1, which I've copied below:

| Model    | BLEU |
| -------- | ------- |
| Transformer-base Vaswani et al. [2017]  | 27.3    |
| RoFormer | **27.5**     |

---

My results (training and evaluating on the smaller Multi30k dataset):

**After 10 training epochs:**

| Model    | BLEU |
| -------- | ------- |
| Transformer-base Vaswani et al. [2017]  | 29.44    |
| RoFormer | **29.41**     |

**After 20 training epochs:**

| Model    | BLEU |
| -------- | ------- |
| Transformer-base Vaswani et al. [2017]  | 32.44    |
| RoFormer | **30.23**     |

This trend only continues as training progresses, so I was unsuccessful in replicating the paper's results. This could be attributed to the fact that I used a much smaller dataset
