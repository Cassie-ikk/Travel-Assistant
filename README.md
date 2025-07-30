# Travel-Assistant
A travel encyclopedia that helps users better plan their journeys.

# Thoughts Record
step1. llama3模型 + dolly-15k数据集训练——为了让模型从续写机器变成对话助手（v1）  
step2. 输入旅游数据，深入微调，使模型变成旅行专家（v2）  
step3. 输入gemini style数据，小而精的数据集，多轮epochs，使得模型以统一风格输出（v3）  
  
再用其他模型来跑一遍，做个对比  

新数据通过在dataset_info.json中添加配置信息，从而从hf上获取
