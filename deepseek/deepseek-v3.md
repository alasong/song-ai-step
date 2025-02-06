# deepseek-v3

## key info

- [DeepSeek-V3 Technical Report](https://arxiv.org/pdf/2412.19437)
- 架构
  - 采用多头潜在注意力 （MLA） 进行高效推理。
  - 采用 DeepSeekMoE 进行经济高效的训练。
  - 优点：在V2中验证，模型稳定性
  - 两个额外的策略来进一步增强模型功能。
    - 用于负载均衡的辅助无损策略，旨在最大限度地减少鼓励负载均衡对模型性能的不利影响。
    - 多标记预测训练目标，我们观察到该目标可以提高评估基准的整体性能。
    - 
## 各api接口及价格
- [deepseek官方api](https://platform.deepseek.com/usage)
- 硅基流动
- [百度千帆大模型平台](https://cloud.baidu.com/product-s/qianfan_home) --> 最便宜，有大量学习资源
- 阿里云
- 腾讯云 --> 未公布

## 复刻deepseek v3
