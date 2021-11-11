# Robust-Fixmatch
[FixMatch](https://arxiv.org/abs/2001.07685) with Robust loss functions ([published at KCC 2021](https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE10582840))
This code is a modified version of [FixMatch-pytorch](https://github.com/kekmodel/FixMatch-pytorch)



Exmaple:
```
python  ./train.py --dataset cifar10 --num-labeled 40 --arch wideresnet --batch-size 16 --lr 0.03 --wdecay 0.001 --expand-labels --seed 5 --out results/ --total-steps 1048576
```
