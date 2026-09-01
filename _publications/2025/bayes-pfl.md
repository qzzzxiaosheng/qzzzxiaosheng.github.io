---
id: bayes-pfl
title: "Bayesian Prompt Flow Learning for Zero-Shot Anomaly Detection"
title_en: "Bayesian Prompt Flow Learning for Zero-Shot Anomaly Detection"
authors: ["屈震", "陶显", "宫新一", "曲世辰", "陈麒宇", "张正涛", "王欣刚", "丁贵广"]
authors_en: ["Zhen Qu", "Xian Tao", "Xinyi Gong", "Shichen Qu", "Qiyu Chen", "Zhengtao Zhang", "Xingang Wang", "Guiguang Ding"]
date: 2025-01-01
pub: CVPR
pub_zh: "Computer Vision and Pattern Recognition Conference (CVPR 2025)"
pub_en: "Computer Vision and Pattern Recognition Conference (CVPR 2025)"
pub_pre: "<strong class=\"text-danger\">人工智能Top会议</strong> · <strong class=\"text-primary\">CCF A类会议</strong> · "
pub_pre_en: "<strong class=\"text-danger\">Top AI Conference</strong> · <strong class=\"text-primary\">CCF A Conference</strong> · "
pub_post: ""
pub_post_en: ""
pub_last: " · <strong>第一作者</strong>"
pub_last_en: " · <strong>First Author</strong>"
selected: true
cover: /assets/images/covers/Bayes.png
abstract: "Bayes-PFL 是一种面向零样本异常检测的贝叶斯提示流学习方法，旨在提升 CLIP 对未见类别异常的泛化能力。该方法从贝叶斯视角将提示空间建模为可学习的概率分布，并通过 Prompt Flow 同时学习图像相关与图像无关的提示分布，从中采样生成多样化的文本提示。此外，引入残差跨模态注意力（RCA）模块，以增强动态文本表示与细粒度视觉特征之间的对齐。实验结果表明，Bayes-PFL 在 15 个工业和医学异常检测数据集上取得了优异的零样本异常检测性能。"
abstract_en: "Bayes-PFL is a Bayesian prompt flow learning framework for zero-shot anomaly detection, aiming to improve CLIP’s generalization to anomalies from unseen categories. It models the prompt space as a learnable probability distribution and employs Prompt Flow to jointly learn image-specific and image-agnostic prompt distributions, from which diverse text prompts are sampled. A residual cross-modal attention (RCA) module is further introduced to enhance the alignment between dynamic text representations and fine-grained visual features. Experiments on 15 industrial and medical anomaly detection datasets demonstrate the strong zero-shot performance of Bayes-PFL."
links:
  Paper: "https://openaccess.thecvf.com/content/CVPR2025/papers/Qu_Bayesian_Prompt_Flow_Learning_for_Zero-Shot_Anomaly_Detection_CVPR_2025_paper.pdf"
code: "https://github.com/xiaozhen228/Bayes-PFL"
---
