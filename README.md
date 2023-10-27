# MRG-KG
> This repo holds code for [Rethinking Medical Report Generation: Disease Revealing Enhancement with Knowledge Graph](). (ICML IMLH 2023 Accepted)

<!--![](https://github.com/dbader/readme-template/raw/master/header.png)-->

## Knowledge graph
```
KG.json
```
You can download our Disease Knowledge Graph in JSON format.

## Disease augmentation
```
Aug_and_Eval.ipynb
```
> You can download the [IU-Xray](https://www.kaggle.com/datasets/raddar/chest-xrays-indiana-university) any other datasets to perform a disease augmentation.

> To augment your dataset, please refer to [augmentation_to_count_sent()](https://github.com/Wangyixinxin/MRG-KG/blob/bdbd78b115b75f86b99ff97c8ca61faa07a5295f/Aug_and_Eval.ipynb#L1982) function.

> Some analysis in our paper can be found, such as finding sentences w or w/o diseases, building disease pool/normal pool, and counting disease occurrences.


## DOR and DS evaluation scores
```
Aug_and_Eval.ipynb
```
> The proposed DS and DOR scores can be found in the [Evaluation](https://github.com/Wangyixinxin/MRG-KG/blob/21253cea19d9b6d0630b80091b91d4994a10d86a/Aug_and_Eval.ipynb#L2489) section.

> Codes to generate Figure 1 (disease and sentence statistics) are also included.


Note: The generation model used in our paper is from [R2Gen](https://github.com/cuhksz-nlp/R2Gen). Feel free to train it on the augmented dataset and evaluate the results using new scores.

**Update: We updated the implementation of DOR to avoid divide-by-zero issue.

### Citation
If you find this paper, knowledge graph, or code useful for your research, please cite our paper:
```
@article{wang2023rethinking,
  title={Rethinking Medical Report Generation: Disease Revealing Enhancement with Knowledge Graph},
  author={Wang, Yixin and Lin, Zihao and Dong, Haoyu},
  journal={arXiv preprint arXiv:2307.12526},
  year={2023}
}
