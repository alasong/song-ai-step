
# Transformer & attention

## 1. 简介

Transformer 是一种基于自注意力机制的神经网络模型，它在自然语言处理任务中取得了显著的成果。Transformer 模型通过将输入序列中的每个单词与其他单词进行比较，从而学习到单词之间的关系，从而实现了对输入序列的建模。

## 2. attention
- [注意力机制到底在做什么，Q/K/V怎么来的？](https://www.zhihu.com/tardis/zm/art/414084879?source_id=1005)
- Self-Attention（自注意力机制）是一种用于捕捉序列数据中元素之间关系的机制。优点包括：
  - 捕捉长期依赖关系：自注意力机制可以捕捉序列中元素之间的长期依赖关系，这对于处理长序列数据非常有用。
  - 并行计算：自注意力机制可以并行计算，这使得它在处理大规模序列数据时非常高效。
  - 模型复杂度低：自注意力机制的模型复杂度较低，这使得它在处理大规模序列数据时非常高效。
  - 可解释性强：自注意力机制的可解释性强，这使得它在处理大规模序列数据时非常高效。
  - 灵活性高：自注意力机制的灵活性高，这使得它在处理大规模序列数据时非常高效。
  - 易于实现：自注意力机制的易于实现，这使得它在处理大规模序列数据时非常高效。
  - 易于扩展：自注意力机制的易于扩展，这使得它在处理大规模序列数据时非常高效。
- Attention里面的QKV的意思：
  - Q: Query，查询向量，用于表示当前输入的信息。attention关注的特征。
  - K: Key，键向量，用于表示输入序列中的每个元素的信息。QK的匹配度。
  - V: Value，值向量，用于表示输入序列中的每个元素的信息。信息本身。
- multi-head attention: 多组qkv，每个qkv都有一组attention，最后concat起来。
- [Q、K、V 与 Multi-Head Attention 多头注意力机制](https://zhuanlan.zhihu.com/p/669027091)
  - 最棒的解释
  - 8套qkv，就是8套attention，每个qkv都有一套attention，最后concat起来。


## 3. transformer
- 一文了解Transformer全貌（图解Transformer）

- 为什么需要多个encoder层？
  - 多个encoder层可以让模型更好地捕捉输入序列中的复杂关系。