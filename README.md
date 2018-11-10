# modelvision

**一些神经网络组件**:

- 完整的神经网络模型 --- complete NN models
- 特殊层 ----  special layers
- 优化器 ----  optimizers
- 回调器 -----callbacks 
- 其它函数 --- functions

此外, 还包括一些**竞赛和项目的解决方案**.

**有几个目的:**

- 记录
- 提供实用工具，有助于快速开始做某事
- 实现一些论文

---

到目前为止，已经实现了以下组件：

- Callback
    - [Snapshot Ensembles](https://arxiv.org/abs/1704.00109) at `callbacks.snapshot`
- Model
    - [DenseNet](https://arxiv.org/abs/1608.06993) at `models.densenet`
    - [Densely Interactive Inference Network(DIIN)](https://openreview.net/forum?id=r1dHXnH6-&noteId=r1dHXnH6-) at `models.diin`
    - [Transformer](https://arxiv.org/abs/1706.03762) at `models.tansformer`
- Layer
    - DecayingDropout at `layers.dropout`
    - [Transformer](https://arxiv.org/abs/1706.03762) at `layers.tansformer`
- Loss
    - [Focal loss](https://arxiv.org/abs/1708.02002) at `losses.classify.focal_loss`
    - [Robust category cross entropy](https://kexue.fm/archives/4493) at `losses.classify.robust_cross_entropy`
- NLP method
    - [Subword](http://arxiv.org/abs/1508.07909) at `utils.subword`