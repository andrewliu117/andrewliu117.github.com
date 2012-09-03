---
layout: math_post
title: "使用BFGS实现最大熵模型"
description: ""
category: 
tags: [machine learning]
---
{% include JB/setup %}

### 最大熵模型BFGS
本文参考了李航的《统计学校方法》第6章P92

算法描述：
 输入：特征函数 \`f_1\` , \`f_{2}\` ,…\`f_{n}\`; 经验分布函数\`widetilde{P}(x,y)\`，目标函数\`f(w)\`，梯度函数\`g(x)=\bigtriangledown f(w)\`，精度要求\`\varepsilon \`;
