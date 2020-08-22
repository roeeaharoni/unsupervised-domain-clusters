# unsupervised-domain-clusters
This repository contains code and data accompanying our ACL 2020 paper, ["Unsupervised Domain Clusters in Pretrained Language Models"](https://arxiv.org/pdf/2004.02105.pdf). 

## data
The multi-domain German-English parallel data we used in the paper is available [here](https://drive.google.com/file/d/1yvB-pvlojtT2UpOX1JvwtD6rw9joQ49A/view?usp=sharing) (626MB). It is a new data split we created that avoids duplicate examples and leakage from the train split to the dev/test splits. The original multi-domain data first appeared in [Koehn and Knowles (2017)](https://www.aclweb.org/anthology/W17-3204/) and consists of five datasets available in the [Opus website](http://opus.nlpl.eu/). 

## code
Available in a notebook in the src directory. 
Please contact me in roee.aharoni@gmail.com for any questions.

## bibtex
If you find this useful for your work, please use the following citation:
```
@inproceedings{aharoni2020unsupervised,
  title={Unsupervised domain clusters in pretrained language models},
  author={Aharoni, Roee and Goldberg, Yoav},
  booktitle = "Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)",
  year={2020},
  url={https://arxiv.org/abs/2004.02105},
  publisher = "Association for Computational Linguistics"
}
```

