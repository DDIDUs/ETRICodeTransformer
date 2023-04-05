# ETRICodeTransformer
This is PyTorch implementation of [Attention is All You Need](https://arxiv.org/abs/1706.03762) (NeurIPS 2017). 

## 1. Environment

- torch==1.7.1
- transformers=4.5.1

All dependencies are written in [requirements.txt](https://github.com/youngerous/transformer/blob/main/requirements.txt), and you can also access through [Dockerfile](https://github.com/youngerous/transformer/blob/main/Dockerfile).

## 2. How to Run

**Note**: In this implementation, ```[CLS]``` and ```[SEP]``` tokens mean ```<s>``` and ```</s>``` respectively.

### Train
```sh
sh run.sh
```

### Inference
```sh
python src/translate.py --source "TEXT_TO_SEARCH" --ckpt-path "CHECKPOINT_TO_LOAD"
```
