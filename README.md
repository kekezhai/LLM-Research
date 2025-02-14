# LLM-Research

## 介绍
**基于小型语言模型的后训练持续优化方法**

本文主要探索了小型语言模型的后训练持续优化方法，提出了一种针对小型语言模型的持续后训练对齐数据构建方法。该方法的核心是基于大模型的数据指导，优化了对齐数据的多样性和准确率，同时兼顾了模型的生成安全性。此外，为了验证本文方法的有效性，我们使用Qwen2-0.5B-Instruction作为SLM底座模型，并使用该方法构建的数据集进行了SFT后训练实验和KTO后训练实验，以及SFT-KTO两阶段实验和模型权重融合实验。最后，我们使用benchmark测试集对后训练模型进行了评估及分析，验证了持续后训练对于提升小型语言模型性能的效果。详见论文: [A Post-Training Enhanced Optimization Approach for Small Language Models](https://arxiv.org/abs/2411.02939)


**基于多维度攻击防御增强的大模型生成安全性方法**

当前大模型在面对复杂攻击指令时容易生成有害内容，从而使得大模型的防御能力显著下降，本文针对这个问题提出了一种基于多维度攻击防御对齐数据构建的方法来增强大模型的生成安全性。本文方法的核心是通过创新方法增加攻击指令维度多样性和生成安全回复的准确性来提升大模型安全对齐学习的效果。为了验证该方法的有效性，在已有的安全评测基准测试之外我们额外设计了新的安全评测基准测试，并使用Llama-3.2-1B-Instruct作为基线模型进行对照实验验证。最终实验效果证明了我们的方法可以显著提升大模型在复杂指令攻击下的生成安全性，同时兼顾模型通用能力的保持和提升。论文详见: [A Method for Enhancing the Safety of Large Model Generation Based on Multi-dimensional Attack and Defense](https://arxiv.org/abs/2501.00517)


## 模型地址
[Qwen2-0.5B-Instruct-S1](https://www.modelscope.cn/models/kkzhai/Qwen2-0.5B-Instruct-S1)

[Llama-3.2-1B-Instruct-ChineseSafety-Enhanced](https://modelscope.cn/models/kkzhai/Llama-3.2-1B-Instruct-ChineseSafety-Enhanced)



  





