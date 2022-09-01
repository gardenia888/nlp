[返回目录](../../readme.md)
## 注意力分数
###  加性注意力

将query和key合并起来进入一个单输出单隐藏层的MLP

$给定查询\mathbf{q} \in \mathbb{R}^q和键\mathbf{k} \in \mathbb{R}^k$,加性注意力（additive attention）的评分函数为
$a(\mathbf q, \mathbf k) = \mathbf w_v^\top \text{tanh}(\mathbf W_q\mathbf q + \mathbf W_k \mathbf k) \in \mathbb{R}$

其中可学参数为$w_v\in \mathbb{R}^h,\mathbf W_q \in\mathbb{R}^{h\times q},\mathbf W_k \in\mathbb{R}^{h\times k}$

### 缩放点积注意力



直接将query和key做内积，要求查询和键具有相同的长度d，

则缩放点积注意力（scaled dot-product attention）评分函数为:
$a(\mathbf q, \mathbf k) = \mathbf{q}^\top \mathbf{k}  /\sqrt{d}$

注意力池化：
$\mathrm{softmax}\left(\frac{\mathbf Q \mathbf K^\top }{\sqrt{d}}\right) \mathbf V \in \mathbb{R}^{n\times v}$

其中$\mathbf Q\in\mathbb R^{n\times d},\mathbf K\in\mathbb R^{m\times d},\mathbf V\in\mathbb R^{m\times v}$

注意力分数是query和key的相似度，注意力权重是分数的softmax结果