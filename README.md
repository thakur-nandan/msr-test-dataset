# msr-test-dataset

Copy of the [SWAG](https://rowanzellers.com/swag/) dataset CSVs from
[rowanz/swagaf](https://github.com/rowanz/swagaf/tree/master/data).

| File | Source |
|------|--------|
| `data/train.csv` | https://raw.githubusercontent.com/rowanz/swagaf/master/data/train.csv |
| `data/val.csv`   | https://raw.githubusercontent.com/rowanz/swagaf/master/data/val.csv |
| `data/test.csv`  | https://raw.githubusercontent.com/rowanz/swagaf/master/data/test.csv |

Columns: `'', video-id, fold-ind, startphrase, sent1, sent2, gold-source, ending0..ending3, label`
(`test.csv` has no `label`).

Licensed under the MIT License (see `LICENSE`), Copyright (c) 2018 Rowan Zellers.

> Zellers et al., *SWAG: A Large-Scale Adversarial Dataset for Grounded Commonsense Inference*, EMNLP 2018.
