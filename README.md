# SAiDL Summer Assignment 2026

My attempt of the summer '26 [assignment](https://github.com/SforAiDl/SAiDL-Summer-2026-Induction-Assignment)

Chosen track (other than mandatory Core ML): Mechanistic Interpretability.

Refer to [`Report.pdf`](./Report.pdf) for analytical details; code is explained through in-line comments.

### Project structure

```
.
├── Core ML
│   ├── Data
│   │   ├── Attention Convolution Hybrids/
│   │   ├── Attention Variants/
│   │   └── Positional Embeddings/
│   └── Notebooks
│       ├── attention_variants.ipynb
│       ├── baseline.ipynb
│       ├── convolution_attention_hybrids.ipynb
│       └── positional_embeddings.ipynb
├── Mechanistic Interpretability
│   ├── Data
│   │   ├── m1024/
│   │   ├── m512/
│   │   └── normalizer.pt
│   ├── Notebook Logs
│   │   ├── m1024/
│   │   ├── m512/
│   │   └── pipeline-setup.log
│   └── Notebooks
│       ├── m1024/
│       ├── m512
│       │   ├── damage-robust-quantisation.ipynb
│       │   ├── quantisation-analysis.ipynb
│       │   └── sae-training-m512.ipynb
│       └── pipeline-setup.ipynb
└── Report.pdf
```