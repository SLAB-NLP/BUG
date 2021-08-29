# 🐞 BUG Dataset 
A Large-Scale Gender Bias Dataset for Coreference Resolution and Machine Translation, Levy et al., EMNLP 2021.


## 🪲 Gold BUG 

## 🐛 Balanced BUG


## Evaluations
See below instructions for reproducing our evaluations on BUG.

### Coreference
1. Download the Spanbert predictions from [this link](https://drive.google.com/file/d/1i24T1YT_0ByxttrCRR7qxEnt8UWyEJ7R/view?usp=sharing).
2. Unzip and put `coref_preds.jsonl` in in the `predictions/` folder.
3. From `src/evaluations/`, run `python evaluate_coref.py --in=../../predictions/coref_preds.jsonl --out=../../visualizations/delta_s_by_dist.png`.
4. This should reproduce the [coreference evaluation figure](visualizations/delta_s_by_dist.png)



## Citing


