# Unichat-DeepSeek-R1-Safe

[//]: # (<p align="center" width="100%">)

[//]: # (  <img src="assets/logo.jpg" style="width: 20%; display: block; margin: auto;"></a>)

[//]: # (</p>)

<p align="center">
         <a href="https://www.modelscope.cn/models/UnicomAI/Unichat-llama3-Chinese">ModelScope</a>&nbsp&nbsp </a>
</p>


## 介绍
* 中国联通AI创新中心发布DeepSeek-R1系列中文微调版本安全强化模型，在中文环境下对安全和价值观进行改造，模型安全能力强化，对话模板为DeepSeekR1官方模板

### 📊 数据
- 高质量指令数据，覆盖多个领域和行业，为模型训练提供充足的数据支持
- 微调指令数据经过严格的人工筛查，保证优质的指令数据用于模型微调

## 能力评估结果
### Unichat-DeepSeek-R1-Safe模型：

![客观题](https://github.com/UnicomAI/DeepSeek-R1-Safe/blob/main/images/Objective_question.png)

在客观题方面，整体准确率（ACC-O）和五大安全子领域的准确率（ACC-i）多用于评估多项选择题（MCQ）的风险内容识别能力。图示呈现了六个 DeepSeek-R1 蒸馏模型在三个关键阶段——蒸馏前（pre-distillation）、蒸馏后（post-distillation）以及安全增强（safety-enhancement）的准确率表现，并对 DeepSeek-R1（671B）在安全增强前后的准确率进行了对比分析。实验结果从实证层面验证了安全增强在整个 DeepSeek-R1 系列中的有效性。

![主观题](https://github.com/UnicomAI/DeepSeek-R1-Safe/blob/main/images/Subjective_questions.png)

在主观题方面，上图系统地展示了所有七款 DeepSeek-R1 模型在“拒绝回答”子集上，于三个开发阶段——蒸馏前（pre-distillation）、蒸馏后（post-distillation）及安全增强（safety-enhancement）所获得的 RR-1、RR-2 和 HR 指标结果。需要指出的是，DeepSeek-R1（671B）在蒸馏前阶段并无对应的基础模型。

![推理性能](https://github.com/UnicomAI/DeepSeek-R1-Safe/blob/main/images/Subjective_questions.png)

上图展示了DeepSeek-R1 模型与安全增强模型在推理基准测试上的性能比较。








## 模型下载

### DeepSeek-R1-Safe安全增强模型
| 模型名称                     | 模型加载名称             | 下载地址                                                     |
|--------------------------| ------------------------- | --------------------- |
| Unichat-DeepSeek-R1-Distill-Qwen-1.5B-Safe | UnicomAI/Unichat-DeepSeek-R1-Distill-Qwen-1.5B-Safe-bf16 |  [ModelScope](https://www.modelscope.cn/models/UnicomAI/Unichat-DeepSeek-R1-Distill-Qwen-1.5B-Safe-bf16)|
| Unichat-DeepSeek-R1-Distill-Qwen-7B-Safe | UnicomAI/Unichat-DeepSeek-R1-Distill-Qwen-7B-Safe-bf16 |  [ModelScope](https://www.modelscope.cn/models/UnicomAI/Unichat-DeepSeek-R1-Distill-Qwen-7B-Safe-bf16)|
| Unichat-DeepSeek-R1-Distill-Qwen-14B-Safe | UnicomAI/Unichat-DeepSeek-R1-Distill-Qwen-14B-Safe-bf16  | [ModelScope](https://www.modelscope.cn/models/UnicomAI/Unichat-DeepSeek-R1-Distill-Qwen-14B-Safe-bf16) |
| Unichat-DeepSeek-R1-Distill-Qwen-32B-Safe | UnicomAI/Unichat-DeepSeek-R1-Distill-Qwen-32B-Safe-bf16  | [ModelScope](https://www.modelscope.cn/models/UnicomAI/Unichat-DeepSeek-R1-Distill-Qwen-32B-Safe-bf16) |
| Unichat-DeepSeek-R1-Distill-Llama-8B-Safe | UnicomAI/Unichat-DeepSeek-R1-Distill-Llama-8B-Safe-bf16 |  [ModelScope](https://www.modelscope.cn/models/UnicomAI/Unichat-DeepSeek-R1-Distill-Llama-8B-Safe-bf16)|
| Unichat-DeepSeek-R1-Distill-Llama-70B-Safe | UnicomAI/Unichat-DeepSeek-R1-Distill-Llama-70B-Safe-bf16  | [ModelScope](https://www.modelscope.cn/models/UnicomAI/Unichat-DeepSeek-R1-Distill-Llama-70B-Safe-bf16)|

## 引用
如果你觉得我们的研究对您的工作有帮助的话，请考虑引用下列论文
```
@article{zhang2025safety,
  title={Safety evaluation of deepseek models in chinese contexts},
  author={Zhang, Wenjing and Lei, Xuejiao and Liu, Zhaoxiang and Wang, Ning and Long, Zhenhong and Yang, Peijun and Zhao, Jiaojiao and Hua, Minjie and Ma, Chaoyang and Wang, Kai and others},
  journal={arXiv preprint arXiv:2502.11137},
  year={2025}
}


@article{zhang2025safety,
  title={Safety Evaluation and Enhancement of DeepSeek Models in Chinese Contexts},
  author={Zhang, Wenjing and Lei, Xuejiao and Liu, Zhaoxiang and Han, Limin and Zhao, Jiaojiao and Huang, Beibei and Long, Zhenhong and Guo, Junting and An, Meijuan and Du, Rongjia and others},
  journal={arXiv preprint arXiv:2503.16529},
  year={2025}
}
```