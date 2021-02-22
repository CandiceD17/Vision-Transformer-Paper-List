# Vision Transformer Paper List
A thorough paper list for the most recent progress in vision transformer. Mainly for image classification and object detection.

## Contents

- [Performance](https://github.com/CandiceD17/vision-transformer-paper-list#performance)
- Model
  - [Transformer in General](https://github.com/CandiceD17/vision-transformer-paper-list#transformer-in-general)
  - [Survey](https://github.com/CandiceD17/vision-transformer-paper-list#survey)
  - [Pure Attention Models](https://github.com/CandiceD17/vision-transformer-paper-list#pure-attention-models)
  - [Convolution + Attention Models](https://github.com/CandiceD17/vision-transformer-paper-list#convolution--attention-models)
    - [Transformer Blocks](https://github.com/CandiceD17/vision-transformer-paper-list#transformer-blocks)
    - [Non-Local Blocks](https://github.com/CandiceD17/vision-transformer-paper-list#non-local-blocks)
- [Blog](https://github.com/CandiceD17/vision-transformer-paper-list#%E7%9F%A5%E4%B9%8E%E5%8E%9F%E7%90%86%E8%AF%A6%E8%A7%A3)

## Performance

|      |      |      |
| ---- | ---- | ---- |
|      |      |      |
|      |      |      |
|      |      |      |



## Model

The model is listed using the taxonomy of self-attention architectures provided by in Google's paper [BoTNet](https://github.com/CandiceD17/vision-transformer-paper-list#transformer-blocks):

![taxonomy of self-attention architectures](https://github.com/CandiceD17/vision-transformer-paper-list/blob/master/assets/taxonomy.png)

### Transformer in General:

- **[Transformer]** Attention is All You Need | **[NeurIPS 2017]** | [`[PDF]`](https://arxiv.org/pdf/1706.03762v5.pdf) [`[official code - tensorflow]`](https://github.com/tensorflow/models/tree/master/official/nlp/transformer) [`[paper-with-code]`](https://paperswithcode.com/paper/attention-is-all-you-need)

### Survey:

- **[Survey]** Transformers in Vision: A Survey | **[Archive 2021]** | [`[PDF]`](https://arxiv.org/pdf/2101.01169.pdf) 
- **[Survey]** A Survey on Transformer | **[Archive 2021]** | [`[PDF]`](https://arxiv.org/abs/2012.12556.pdf) 
- **[Survey]** Efficient Transformers: A Survey | **[Archive 2020]** | [`[PDF]`](https://arxiv.org/pdf/2009.06732.pdf) 

### Pure Attention Models:

- **[LR-Net]** Local Relation Networks for Image Recognition | **[ICCV 2019]** | [`[PDF]`](https://arxiv.org/pdf/1904.11491.pdf) [`[unofficial code - torch]`](https://github.com/gan3sh500/local-relational-nets) [`[paper-with-code]`](https://paperswithcode.com/paper/190411491#code)
- **[SASA]** Stand-Alone Self-Attention in Vision Models | **[NeurIPS 2019]** | [`[PDF]`](https://arxiv.org/pdf/1904.11491.pdf) [`[unofficial code - torch]`](https://github.com/leaderj1001/Stand-Alone-Self-Attention) [`[paper-with-code]`](https://paperswithcode.com/paper/stand-alone-self-attention-in-vision-models)
- **[SANet]** Exploring Self-attention for Image Recognition | **[CVPR 2020]** | [`[PDF]`](https://arxiv.org/abs/2004.13621.pdf) [`[official code - tensorflow]`](https://github.com/hszhao/SAN) [`[paper-with-code]`](https://paperswithcode.com/paper/exploring-self-attention-for-image)
- **[ViT]** An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale | **[ICLR 2021]** | [`[PDF]`](https://arxiv.org/pdf/1904.11491.pdf) [`[official code - jax]`](https://github.com/google-research/vision_transformer) [`[paper-with-code]`](https://paperswithcode.com/paper/an-image-is-worth-16x16-words-transformers-1)
- **[T2T-ViT]** Tokens-to-Token ViT: Training Vision Transformers from Scratch on ImageNet | **[Archive 2021]** | [`[PDF]`](https://arxiv.org/pdf/1904.11491.pdf) [`[official code - torch]`](https://github.com/yitu-opensource/T2T-ViT) [`[paper-with-code]`](https://paperswithcode.com/paper/tokens-to-token-vit-training-vision)

### Convolution + Attention Models:

#### Transformer Blocks:

- **[DETR]** End-to-End Object Detection with Transformers | **[ECCV 2020]** | [`[PDF]`](https://arxiv.org/pdf/2005.12872.pdf) [`[official code - torch]`](https://github.com/facebookresearch/detr) [`[paper-with-code]`](https://paperswithcode.com/paper/end-to-end-object-detection-with-transformers)
- **[DeiT]** Training data-efficient image transformers & distillation through attention | **[Archive 2021]** | [`[PDF]`](https://arxiv.org/abs/2012.12877.pdf) [`[official code - torch]`](https://github.com/facebookresearch/deit) [`[paper-with-code]`](https://paperswithcode.com/paper/training-data-efficient-image-transformers)
- **[BoTNet]** Bottleneck Transformers for Visual Recognition  | **[Archive 2021]** | [`[PDF]`](https://arxiv.org/abs/2101.11605.pdf) [`[unofficial code - torch]`](https://github.com/lucidrains/bottleneck-transformer-pytorch) [`[paper-with-code]`](https://paperswithcode.com/paper/bottleneck-transformers-for-visual)

#### Non-Local Blocks:

- **[NL-ConvNet]** Non-local Neural Networks | **[CVPR 2018]** | [`[PDF]`](https://arxiv.org/pdf/1711.07971.pdf) [`[official code - caffe]`](https://github.com/facebookresearch/video-nonlocal-net) [`[paper-with-code]`](https://paperswithcode.com/paper/non-local-neural-networks)



### 知乎原理详解：

- 解释Transformer Attention机制 (Attention is All You Need)，详细清晰，原理和训练场景图文并茂 [链接](https://zhuanlan.zhihu.com/p/48508221)
- Transformer原理+两个视觉transformer(ViT & DETR) 的机制和重要源码解读，源码备注很详细 [链接](https://zhuanlan.zhihu.com/p/308301901)
- Non-Local blocks的原理解释，读完可以区分它和上面Transformer的设计区别 [链接](https://zhuanlan.zhihu.com/p/33345791)

