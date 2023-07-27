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
Augment_disease.ipynb
```
> You can download the [IU-Xray](https://www.kaggle.com/datasets/raddar/chest-xrays-indiana-university) any other datasets to perform a disease augmentation.
> Some analysis in our paper can be found, such as finding sentences w or w/o diseases, building disease pool/normal pool, and counting disease occurrences.

Note: The generation model used in our paper is from [R2Gen](https://github.com/cuhksz-nlp/R2Gen)


### Citation
If you find this paper, knowledge graph, or code useful for your research, please cite our paper:
```
@article{wang2023rethinking,
  title={Rethinking Medical Report Generation: Disease Revealing Enhancement with Knowledge Graph},
  author={Wang, Yixin and Lin, Zihao and Dong, Haoyu},
  journal={arXiv preprint arXiv:2307.12526},
  year={2023}
}
