
# nanoGPT

![nanoGPT](assets/nanogpt.jpg)

相比于 [nanoGPT](https://github.com/karpathy/nanoGPT) 替换了tokenizer为清华[GLM](https://github.com/THUDM/GLM)的,使得其容易支持中文

首先准备数据  `python prepare.py`

然后开始训练 `python train.py config/train_hongloumeng.py`

最后生成 `python sample.py --out_dir=out-hongloumeng`

