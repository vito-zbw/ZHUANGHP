---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
$^\dagger$: Corresponding author.

**[2022]**
===
**Huiping Zhuang**, Zhenyu Weng, Hongxin Wei, Renchunzi Xie, Kar-Ann Toh, Zhiping Lin"ACIL: Analytic Class-Incremental Learning with Absolute Memorization and Privacy Protection", Thirty-Sixth Conference on Neural Information Processing Systems (NeurIPS) 2022.

Weng, Zhenyu, **Huiping Zhuang**, Haizhou Li, Balakrishnan Ramalingam, Rajesh Elara Mohan, and Zhiping Lin. "Online Multi-Face Tracking With Multi-Modality Cascaded Matching." IEEE Transactions on Circuits and Systems for Video Technology (2022).

Man, Siu Shing, Yingqian Guo, Alan Hoi Shou Chan, and **Huiping Zhuang$^\dagger$**. "Acceptance of Online Mapping Technology among Older Adults: Technology Acceptance Model with Facilitating Condition, Compatibility, and Self-Satisfaction." ISPRS International Journal of Geo-Information 11, no. 11 (2022): 558.

Li, Hanhui, Xinggan Peng, **Huiping Zhuang$^\dagger$**, and Zhiping Lin. "Multiple Temporal Context Embedding Networks for Unsupervised time Series Anomaly Detection." In ICASSP 2022-2022 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), pp. 3438-3442. IEEE, 2022.

[2021]
===

**Huiping Zhuang**, Yi Wang, Qinglai Liu, and Zhiping Lin. "Fully Decoupled Neural Network Learning Using Delayed Gradients," in IEEE Transactions on Neural Networks and Learning Systems, doi: 10.1109/TNNLS.2021.3069883. 

**Huiping Zhuang**, Zhiping Lin, and Kar-Ann Toh. "Blockwise Recursive Moore-Penrose Inverse for Network Learning," in IEEE Transactions on Systems, Man, and Cybernetics: Systems, doi: 10.1109/TSMC.2021.3064241.

**Huiping Zhuang**, Zhenyu Weng, Fulin Luo, Kar-Ann Toh, Haizhou Li, Zhiping Lin. "Accumulated Decoupled Learning with Gradient Staleness Mitigation for Convolutional Neural Networks” International Conference of Machine Learning 2021 (spotlight).

**Huiping Zhuang**, Zhiping Lin, and Kar-Ann Toh. "Correlation Projection for Analytic Learning of a Classification Network," Neural Process Lett (2021). https://doi.org/10.1007/s11063-021-10570-2.

**Huiping Zhuang**, Zhiping Lin, and Kar-Ann Toh. "Training Multilayer Neural Networks Analytically Using Kernel Projection,” 2021 IEEE International Symposium on Circuits and Systems.

[2020]
===

**Huiping Zhuang**, Zhiping Lin, and Kar-Ann Toh. "Training a multilayer network with low-memory kernel-and-range projection." Journal of the Franklin Institute 357.1 (2020): 522-550.

Xinggan Peng, **Huiping Zhuang**, Guang-Bin Huang, Haizhou Li and Zhiping Lin. "Robust Real-time Face Tracking with or without Face Masks." 2020 16th International Conference on Control, Automation, Robotics and Vision (ICARV). IEEE, 2020.

[2019]
===
**Huiping Zhuang**, Zhiping Lin, and Kar-Ann Toh. "A Low-Memory Learning Formulation for a Kernel-and-Range Network." 2019 International Joint Conference on Neural Networks (IJCNN). IEEE, 2019.

Oh, B. S., **Zhuang, H**., Toh, K. A., & Lin, Z. (2019). Augmented EMD for complex-valued univariate signals. IET Signal Processing, 13(4), 424-433.

[2016-2018]
===
**Huiping Zhuang**, Beom-Seok Oh, Dongyun Lin, Kar-Ann Toh, and Zhiping Lin. "Multicomponent Signal Decomposition Using Morphological Operations." In 2018 IEEE 23rd International Conference on Digital Signal Processing (DSP), pp. 1-5. IEEE, 2018.

Su, Wendan, **Huiping Zhuang**, and Xiaohong Qiu. "Moving targets detection and tracking based on improved codebook algorithm and Kalman filtering." 2017 36th Chinese Control Conference (CCC). IEEE, 2017.

**Huiping Zhuang**, Jieying Lu, and Junhui Li. "Joint estimation of state and parameter with maximum likelihood method." 2017 36th Chinese Control Conference (CCC). IEEE, 2017.

**Huiping Zhuang**, and Junhui Li. "Robust two-stage Kalman filtering in presence of autoregressive input." 2016 14th International Conference on Control, Automation, Robotics and Vision (ICARV). IEEE, 2016. 

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
