---
id: dictas
title: "DictAS: A Framework for Class-Generalizable Few-Shot Anomaly Segmentation via Dictionary Lookup"
title_en: "DictAS: A Framework for Class-Generalizable Few-Shot Anomaly Segmentation via Dictionary Lookup"
authors: ["屈震", "陶显","宫新一", "曲世辰", "张晓沛", "王欣刚", "沈飞", "张正涛", "Mukesh Prasad", "丁贵广"]
authors_en: ["Zhen Qu", "Xinyi Gong", "Shichen Qu", "Xiaopei Zhang", "Xingang Wang", "Fei Shen", "Zhengtao Zhang", "Mukesh Prasad", "Guiguang Ding"]
date: 2025-01-01
pub: ICCV
pub_zh: "International Conference on Computer Vision (ICCV 2025)"
pub_en: "International Conference on Computer Vision (ICCV 2025)"
pub_pre: "<strong class=\"text-danger\">人工智能Top会议</strong> · <strong class=\"text-primary\">CCF A类会议</strong> · "
pub_pre_en: "<strong class=\"text-danger\">Top AI Conference</strong> · <strong class=\"text-primary\">CCF A Conference</strong> · "
pub_post: ""
pub_post_en: ""
pub_last: " · <strong>第一作者</strong>"
pub_last_en: " · <strong>First Author</strong>"
selected: true
cover: /assets/images/covers/DictAS.png
abstract: "DictAS 是一种面向类别泛化少样本异常分割的字典查找框架，旨在仅利用少量正常参考图像，在无需目标类别重新训练的情况下检测未见类别中的异常。该方法通过字典构建模块建立正常特征字典，并利用稀疏查找策略判断查询区域是否能够从字典中被有效检索，从而将“查不到”的区域识别为异常。此外，引入查询判别正则化，通过对比约束和文本对齐进一步增强异常特征的可分性。实验结果表明，DictAS 在 7 个工业和医学数据集上均取得了优异的少样本异常分割性能。"
abstract_en: "DictAS is a dictionary lookup framework for class-generalizable few-shot anomaly segmentation, aiming to detect anomalies in unseen categories using only a few normal reference images without retraining on the target data. It constructs a dictionary from normal reference features and employs a sparse lookup strategy to determine whether queried regions can be effectively retrieved, treating unretrievable regions as anomalies. Query discrimination regularization, including contrastive query and text alignment constraints, is further introduced to enhance anomaly separability. Experiments on seven industrial and medical datasets demonstrate the strong few-shot anomaly segmentation performance of DictAS."
links:
  Paper: "https://openaccess.thecvf.com/content/ICCV2025/papers/Qu_DictAS_A_Framework_for_Class-Generalizable_Few-Shot_Anomaly_Segmentation_via_Dictionary_ICCV_2025_paper.pdf"
code: "https://github.com/xiaozhen228/DictAS"
---
