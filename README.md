
### What is Adversarial Transferability?
Adversarial Transferability refers to the ability of adversarial examples designed for one model to successfully deceive a different model.

### Reference
- This repo lists relevant papers summarized in our survey paper.
  
  **A Survey on Transferability of Adversarial Examples across Deep Neural Networks.**  *Jindong Gu, Xiaojun Jia, Pau de Jorge, Wenqain Yu, Xinwei Liu, Avery Ma, Yuan Xun, Anjun Hu, Ashkan Khakzar, Zhijiang Li, Xiaochun Cao, Philip Torr*. Preprint 2023. [[pdf]](http://arxiv.org/abs/2310.17626)

If you find our paper and repo helpful to your research, please cite the following paper:
```latex
@article{gu2023survey_atrans,
  title={A Survey on Transferability of Adversarial Examples across Deep Neural Networks},
  author={Gu, Jindong and Jia, Xiaojun and Pau de Jorge, and Yu, Wenqain and Liu, Xinwei and Ma, Avery and Xun, Yuan and Hu, Anjun and Khakzar, Ashkan and Li, Zhijiang and Cao, Xiaochun and Torr, Philip}
  journal={arXiv preprint arXiv:2310.17626},
  year={2023}
}
```
 
* Abbreviation tags, i.e., ![](https://img.shields.io/badge/data-4472C4) ![](https://img.shields.io/badge/model-7030A0) ![](https://img.shields.io/badge/loss-538C51) ![](https://img.shields.io/badge/optimization-D95E32) ![](https://img.shields.io/badge/generative-D94A70)
  Each paper will be marked with one or more tags, which mean the paper can be categorized into the corresponding category, e.g., optimization-based transferability-enhancing approach
### Papers
#### 2023
- ![](https://img.shields.io/badge/loss-538C51) Making Substitute Models More Bayesian Can Enhance Transferability of Adversarial Examples.
  [[pdf]](https://arxiv.org/pdf/2302.05086v3.pdf)
  [[code]](https://github.com/qizhangli/morebayesian-attack)<br />
  Qizhang Li, Yiwen Guo, Wangmeng Zuo, Hao Chen. arXiv, 2023.

- ![](https://img.shields.io/badge/generative-D94A70) Diffusion Models for Imperceptible and Transferable Adversarial Attack.
  [[pdf]](https://arxiv.org/pdf/2305.08192)
  [[code]](https://github.com/windvchen/diffattack)<br />
  Jianqi Chen, Hao Chen, Keyan Chen, Yilan Zhang, Zhengxia Zou, Zhenwei Shi. arXiv, 2023.

- ![](https://img.shields.io/badge/loss-538C51) An Adaptive Model Ensemble Adversarial Attack for Boosting Adversarial Transferability.
  [[pdf]](https://openaccess.thecvf.com/content/ICCV2023/papers/Chen_An_Adaptive_Model_Ensemble_Adversarial_Attack_for_Boosting_Adversarial_Transferability_ICCV_2023_paper.pdf)
  [[code]](https://github.com/CHENBIN99/AdaEA)
  Bin Chen, Jiali Yin, Shukai Chen, Bohao Chen, Ximeng Liu. **ICCV**, 2023.

- ![](https://img.shields.io/badge/model-7030A0) ![](https://img.shields.io/badge/data-4472C4) T-SEA: Transfer-Based Self-Ensemble Attack on Object Detection.
  [[pdf]](https://openaccess.thecvf.com/content/CVPR2023/papers/Huang_T-SEA_Transfer-Based_Self-Ensemble_Attack_on_Object_Detection_CVPR_2023_paper.pdf)
  [[code]](https://github.com/VDIGPKU/TSEA)
  Hao Huang, Ziyan Chen, Huanran Chen, Yongtao Wang, Kevin Zhang. **CVPR**, 2023.

- ![](https://img.shields.io/badge/optimization-D95E32) Transferable Adversarial Attack for Both Vision Transformers and Convolutional Networks via Momentum Integrated Gradients.
  [[pdf]](https://openaccess.thecvf.com/content/ICCV2023/papers/Ma_Transferable_Adversarial_Attack_for_Both_Vision_Transformers_and_Convolutional_Networks_ICCV_2023_paper.pdf)
  Wenshuo Ma, Yidong Li, Xiaofeng Jia, Wei Xu. **ICCV**, 2023.

- ![](https://img.shields.io/badge/loss-538C51) LEA2: A Lightweight Ensemble Adversarial Attack via Non-overlapping Vulnerable Frequency Regions.
  [[pdf]](https://openaccess.thecvf.com/content/ICCV2023/papers/Qian_LEA2_A_Lightweight_Ensemble_Adversarial_Attack_via_Non-overlapping_Vulnerable_Frequency_ICCV_2023_paper.pdf)
  Yaguan Qian, Shuke He, Chenyu Zhao, Jiaqiang Sha, Wei Wang, Bin Wang. **ICCV**, 2023.

- ![](https://img.shields.io/badge/optimization-D95E32) Boosting Adversarial Transferability via Gradient Relevance Attack.
  [[pdf]](https://openaccess.thecvf.com/content/ICCV2023/papers/Zhu_Boosting_Adversarial_Transferability_via_Gradient_Relevance_Attack_ICCV_2023_paper.pdf)
  [[code]](https://github.com/RYC-98/GRA)
  Hegui Zhu, Yuchen Ren, Xiaoyan Sui, Lianping Yang, Wuming Jiang. **ICCV**, 2023.
  
#### 2022
- ![](https://img.shields.io/badge/data-4472C4) Improving the Transferability of Targeted Adversarial Examples through Object-Based Diverse Input.
  [[pdf]](https://openaccess.thecvf.com/content/CVPR2022/papers/Byun_Improving_the_Transferability_of_Targeted_Adversarial_Examples_Through_Object-Based_Diverse_CVPR_2022_paper.pdf)
  [[code]](https://github.com/dreamflake/ODI)<br />
  Junyoung Byun, Seungju Cho, Myung-Joon Kwon, Hee-Seon Kim, Changick Kim. **CVPR**, 2022. 

- ![](https://img.shields.io/badge/loss-538C51) Investigating Top-k White-Box and Transferable Black-box Attack.
  [[pdf]](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhang_Investigating_Top-k_White-Box_and_Transferable_Black-Box_Attack_CVPR_2022_paper.pdf)
  [[code]](https://github.com/ChaoningZhang/Top-k-Transferable-Attack)<br />
  Chaoning Zhang, Philipp Benz, Adil Karjauv, Jae Won Cho, Kang Zhang, In So Kweon. **CVPR**, 2022. 
  
- ![](https://img.shields.io/badge/optimization-D95E32) Stochastic Variance Reduced Ensemble Adversarial Attack for Boosting the Adversarial Transferability.
  [[pdf]](https://openaccess.thecvf.com/content/CVPR2022/papers/Xiong_Stochastic_Variance_Reduced_Ensemble_Adversarial_Attack_for_Boosting_the_Adversarial_CVPR_2022_paper.pdf)
  [[code]](https://github.com/JHL-HUST/SVRE)<br />
  Yifeng Xiong, Jiadong Lin, Min Zhang, John E. Hopcroft, Kun He. **CVPR**, 2022. 
  
- ![](https://img.shields.io/badge/loss-538C51) Cross-Modal Transferable Adversarial Attacks from Images to Videos.
  [[pdf]](https://openaccess.thecvf.com/content/CVPR2022/papers/Wei_Cross-Modal_Transferable_Adversarial_Attacks_From_Images_to_Videos_CVPR_2022_paper.pdf)<br />
  Zhipeng Wei, Jingjing Chen, Zuxuan Wu, Yu-Gang Jiang. **CVPR**, 2022. 
  
- ![](https://img.shields.io/badge/loss-538C51) Improving Adversarial Transferability via Neuron Attribution-Based Attacks.
  [[pdf]](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhang_Improving_Adversarial_Transferability_via_Neuron_Attribution-Based_Attacks_CVPR_2022_paper.pdf)
  [[code]](https://github.com/jpzhang1810/NAA)<br />
  Jianping Zhang, Weibin Wu, Jen-tse Huang, Yizhan Huang, Wenxuan Wang, Yuxin Su, Michael R. Lyu. **CVPR**, 2022. 

- ![](https://img.shields.io/badge/data-4472C4) Boosting the Transferability of Video Adversarial Examples via Temporal Translation.
  [[pdf]](https://arxiv.org/pdf/2110.09075.pdf)
  [[code]](https://github.com/zhipeng-wei/TT)<br />
  Zhipeng Wei, Jingjing Chen, Zuxuan Wu, Yu-Gang Jiang. **AAAI**, 2022.

- ![](https://img.shields.io/badge/data-4472C4) Transferable Adversarial Attack based on Integrated Gradients.
  [[pdf]](https://arxiv.org/pdf/2205.13152.pdf)<br />
  Yi Huang, Adams Wai-Kin Kong. arXiv, 2022.

- ![](https://img.shields.io/badge/optimization-D95E32) Making Adversarial Examples More Transferable and Indistinguishable.
  [[pdf]](https://arxiv.org/pdf/2007.03838v2.pdf)
  [[code]](https://github.com/278287847/AI-FGTM)<br />
  Junhua Zou, Yexin Duan, Boyu Li, Wu Zhang, Yu Pan, Zhisong Pan. **AAAI**, 2022.

- ![](https://img.shields.io/badge/optimization-D95E32) Boosting the Transferability of Adversarial Attacks with Reverse Adversarial Perturbation.
  [[pdf]](https://proceedings.neurips.cc/paper_files/paper/2022/file/c0f9419caa85d7062c7e6d621a335726-Paper-Conference.pdf)
  [[code]](https://github.com/SCLBD/Transfer_attack_RAP)<br />
  Zeyu Qin, Yanbo Fan, Yi Liu, Li Shen, Yong Zhang, Jue Wang, Baoyuan Wu. **NIPS**, 2022.

- ![](https://img.shields.io/badge/loss-538C51) Learning to Learn Transferable Attack.
  [[pdf]](https://ojs.aaai.org/index.php/AAAI/article/view/19936/19695)<br />
  Shuman Fang, Jie Li, Xianming Lin, Rongrong Ji. **AAAI**, 2022.

- ![](https://img.shields.io/badge/loss-538C51) Adversarially Robust Models may not Transfer Better:<br />Sufficient Conditions for Domain Transferability from the View of Regularization.
  [[pdf]](https://proceedings.mlr.press/v162/xu22n/xu22n.pdf)<br />
  Xiaojun Xu, Jacky Y Zhang, Evelyn Ma, Hyun Ho Son, Sanmi Koyejo, Bo Li. **ICML**, 2022.

- ![](https://img.shields.io/badge/loss-538C51) Improving Adversarial Transferability via Neuron Attribution-Based Attacks.
  [[pdf]](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhang_Improving_Adversarial_Transferability_via_Neuron_Attribution-Based_Attacks_CVPR_2022_paper.pdf)
  [[code]](https://github.com/jpzhang1810/naa)<br />
  Jianping Zhang, Weibin Wu, Jen-tse Huang, Yizhan Huang, Wenxuan Wang, Yuxin Su, Michael R. Lyu. **CVPR**, 2022.

- ![](https://img.shields.io/badge/model-7030A0) On Improving Adversarial Transferability of Vision Transformers.
  [[pdf]](https://openreview.net/pdf?id=D6nH3719vZy)
  [[code]](https://github.com/Muzammal-Naseer/On-Improving-Adversarial-Transferability-of-Vision-Transformers)<br />
  Muzammal Naseer, Kanchana Ranasinghe, Salman Khan, Fahad Shahbaz Khan, Fatih Porikli. **ICLR**, 2022.

- ![](https://img.shields.io/badge/loss-538C51) LGV: Boosting Adversarial Example Transferability from Large Geometric Vicinity.
  [[pdf]](https://arxiv.org/pdf/2207.13129v1.pdf)
  [[code]](https://github.com/framartin/lgv-geometric-transferability)<br />
  Martin Gubri, Maxime Cordy, Mike Papadakis, Yves Le Traon, Koushik Sen. **ECCV**, 2022.

- ![](https://img.shields.io/badge/loss-538C51) Efficient and transferable adversarial examples from bayesian neural networks.
  [[pdf]](https://proceedings.mlr.press/v180/gubri22a/gubri22a.pdf)
  [[code]](https://github.com/framartin/transferable-bnn-adv-ex)<br />
  Martin Gubri, Maxime Cordy, Mike Papadakis, Yves Le Traon, Koushik Sen. **UAI**, 2022.

- ![](https://img.shields.io/badge/generative-D94A70) Boosting Transferability of Targeted Adversarial Examples via Hierarchical Generative Networks.
  [[pdf]](https://arxiv.org/pdf/2107.01809)
  [[code]](https://github.com/ShawnXYang/C-GSP)<br />
  Xiao Yang, Yinpeng Dong, Tianyu Pang, Hang Su, Jun Zhu. **ECCV**, 2022.

#### 2021
- ![](https://img.shields.io/badge/data-4472C4) Admix: Enhancing the Transferability of Adversarial Attacks.
  [[pdf]](https://openaccess.thecvf.com/content/ICCV2021/papers/Wang_Admix_Enhancing_the_Transferability_of_Adversarial_Attacks_ICCV_2021_paper.pdf)
  [[code]](https://github.com/JHL-HUST/Admix)<br />
  Xiaosen Wang, Xuanran He, Jingdong Wang, Kun He. **ICCV**, 2021. 
  
- ![](https://img.shields.io/badge/generative-D94A70) On Generating Transferable Targeted Perturbations.
  [[pdf]](https://openaccess.thecvf.com/content/ICCV2021/papers/Naseer_On_Generating_Transferable_Targeted_Perturbations_ICCV_2021_paper.pdf)
  [[code]](https://github.com/Muzammal-Naseer/TTP)<br />
  Muzammal Naseer, Salman Khan, Munawar Hayat, Fahad Shahbaz Khan, Fatih Porikli. **ICCV**, 2021. 
  
- ![](https://img.shields.io/badge/model-7030A0) Batch Normalization Increases Adversarial Vulnerability and Decreases Adversarial Transferability:  <br />A Non-Robust Feature Perspective.
  [[pdf]](https://openaccess.thecvf.com/content/ICCV2021/papers/Benz_Batch_Normalization_Increases_Adversarial_Vulnerability_and_Decreases_Adversarial_Transferability_A_ICCV_2021_paper.pdf) <br />
  Philipp Benz, Chaoning Zhang, In So Kweon. **ICCV**, 2021.

- ![](https://img.shields.io/badge/data-4472C4) Improving the Transferability of Adversarial Samples with Adversarial Transformations.
  [[pdf]](https://openaccess.thecvf.com/content/CVPR2021/papers/Wu_Improving_the_Transferability_of_Adversarial_Samples_With_Adversarial_Transformations_CVPR_2021_paper.pdf)<br />
  Weibin Wu, Yuxin Su, Michael R. Lyu, Irwin King. **CVPR**, 2021.

- ![](https://img.shields.io/badge/optimization-D95E32) Enhancing the Transferability of Adversarial Attacks Through Variance Tuning.
  [[pdf]](https://openaccess.thecvf.com/content/CVPR2021/papers/Wang_Enhancing_the_Transferability_of_Adversarial_Attacks_Through_Variance_Tuning_CVPR_2021_paper.pdf)
  [[code]](https://github.com/JHL-HUST/VT)<br />
  Xiaosen Wang, Kun He. **CVPR**, 2021.

- ![](https://img.shields.io/badge/loss-538C51) Improving Transferability of Adversarial Patches on Face Recognition With Generative Models.
  [[pdf]](https://openaccess.thecvf.com/content/CVPR2021/papers/Xiao_Improving_Transferability_of_Adversarial_Patches_on_Face_Recognition_With_Generative_CVPR_2021_paper.pdf)<br />
  Zihao Xiao, Xianfeng Gao, Chilin Fu, Yinpeng Dong, Wei Gao, Xiaolu Zhang, Jun Zhou, Jun Zhu. **CVPR**, 2021.

- ![](https://img.shields.io/badge/loss-538C51) On Success and Simplicity: A Second Look at Transferable Targeted Attacks.
  [[pdf]](https://proceedings.neurips.cc/paper_files/paper/2021/file/30d454f09b771b9f65e3eaf6e00fa7bd-Paper.pdf)
  [[code]](https://github.com/ZhengyuZhao/Targeted-Transfer)<br />
  Zhengyu Zhao, Zhuoran Liu, Martha Larson. **NIPS**, 2021.

- ![](https://img.shields.io/badge/loss-538C51) Learning Transferable Adversarial Perturbations.
  [[pdf]](https://proceedings.neurips.cc/paper_files/paper/2021/file/7486cef2522ee03547cfb970a404a874-Paper.pdf)<br />
  Krishna kanth Nakka, Mathieu Salzmann. **NIPS**, 2021.

- ![](https://img.shields.io/badge/loss-538C51) Feature Importance-Aware Transferable Adversarial Attacks.
  [[pdf]](https://openaccess.thecvf.com/content/ICCV2021/papers/Wang_Feature_Importance-Aware_Transferable_Adversarial_Attacks_ICCV_2021_paper.pdf)
  [[code]](https://github.com/hcguoO0/FIA)<br />
  Zhibo Wang, Hengchang Guo, Zhifei Zhang, Wenxin Liu, Zhan Qin, Kui Ren. **ICCV**, 2021.

- ![](https://img.shields.io/badge/loss-538C51) A Unified Approach to Interpreting and Boosting Adversarial Transferability.
  [[pdf]](https://arxiv.org/pdf/2010.04055v1.pdf)
  [[code]](https://github.com/xherdan76/A-Unified-Approach-to-Interpreting-and-Boosting-Adversarial-Transferability)<br />
  Xin Wang, Jie Ren, Shuyun Lin, Xiangming Zhu, Yisen Wang, Quanshi Zhang. **ICLR**, 2021. 

#### 2020
- ![](https://img.shields.io/badge/data-4472C4) Adversarial Examples on Segmentation Models Can be Easy to Transfer.
  [[pdf]](https://arxiv.org/pdf/2111.11368.pdf)
  [[code]](https://arxiv.org/pdf/2111.11368.pdf)<br />
  Jindong Gu, Hengshuang Zhao, Volker Tresp, Philip Torr. arXiv, 2020.

- ![](https://img.shields.io/badge/data-4472C4) Improving the Transferability of Adversarial Examples with Resized-Diverse-Inputs, Diversity-Ensemble and Region Fitting.
  [[pdf]](https://arxiv.org/pdf/2112.06011.pdf)
  [[code]](https://github.com/278287847/DEM)<br />
  Junhua Zou, Zhisong Pan, Junyang Qiu, Xin Liu, Ting Rui, Wei Li. **ECCV**, 2020.

- ![](https://img.shields.io/badge/data-4472C4) Regional Homogeneity: Towards Learning Transferable Universal Adversarial Perturbations Against Defenses.
  [[pdf]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123560766.pdf)
  [[code]](https://github.com/LiYingwei/Regional-Homogeneity)<br />
  Yingwei Li, Song Bai, Cihang Xie, Zhenyu Liao, Xiaohui Shen, Alan Yuille. **ECCV**, 2020.

- ![](https://img.shields.io/badge/loss-538C51) Towards Transferable Targeted Attack.
  [[pdf]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Li_Towards_Transferable_Targeted_Attack_CVPR_2020_paper.pdf)
  [[code]](https://github.com/TiJoy/Towards-Transferable-Targeted-Attack)<br />
  Maosen Li, Cheng Deng, Tengjiao Li, Junchi Yan, Xinbo Gao, Heng Huang. **CVPR**, 2020.

- ![](https://img.shields.io/badge/loss-538C51) Boosting the Transferability of Adversarial Samples via Attention.
  [[pdf]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Wu_Boosting_the_Transferability_of_Adversarial_Samples_via_Attention_CVPR_2020_paper.pdf)<br />
  Weibin Wu, Yuxin Su, Xixian Chen, Shenglin Zhao, Irwin King, Michael R. Lyu, Yu-Wing Tai. **CVPR**, 2020.

- ![](https://img.shields.io/badge/loss-538C51) Transferable Perturbations of Deep Feature Distributions.
  [[pdf]](https://arxiv.org/pdf/2004.12519)<br />
  Nathan Inkawhich, Kevin J Liang, Lawrence Carin, Yiran Chen. arXiv, 2020.

- ![](https://img.shields.io/badge/loss-538C51) Perturbing Across the Feature Hierarchy to Improve Standard and Strict Blackbox Attack Transferability.
  [[pdf]](https://proceedings.neurips.cc/paper_files/paper/2020/file/eefc7bfe8fd6e2c8c01aa6ca7b1aab1a-Paper.pdf)<br />
  Nathan Inkawhich, Kevin Liang, Binghui Wang, Matthew Inkawhich, Lawrence Carin, Yiran Chen. **NIPS**, 2020.

- ![](https://img.shields.io/badge/model-7030A0) Skip Connections Matter: On the Transferability of Adversarial Examples Generated with ResNets.
  [[pdf]](https://openreview.net/pdf?id=BJlRs34Fvr)
  [[code]](https://github.com/csdongxian/skip-connections-matter)<br />
  Dongxian Wu, Yisen Wang, Shu-Tao Xia, James Bailey, Xingjun Ma. **ICLR**, 2020.

- ![](https://img.shields.io/badge/model-7030A0) Backpropagating Linearly Improves Transferability of Adversarial Examples.
  [[pdf]](https://proceedings.neurips.cc/paper_files/paper/2020/file/00e26af6ac3b1c1c49d7c3d79c60d000-Paper.pdf)
  [[code]](https://github.com/qizhangli/linbp-attack)<br />
  Yiwen Guo, Qizhang Li, Hao Chen. **NIPS**, 2020.

- ![](https://img.shields.io/badge/generative-D94A70) CAG: A Real-Time Low-Cost Enhanced-Robustness High-Transferability Content-Aware Adversarial Attack Generator.
  [[pdf]](https://ojs.aaai.org/index.php/AAAI/article/view/5990/5846)<br />
  Huy Phan, Yi Xie, Siyu Liao, Jie Chen, Bo Yua. **AAAI**, 2020.

#### 2019
- ![](https://img.shields.io/badge/data-4472C4) Improving Transferability of Adversarial Examples with Input Diversity.
  [[pdf]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Xie_Improving_Transferability_of_Adversarial_Examples_With_Input_Diversity_CVPR_2019_paper.pdf)
  [[code]](https://github.com/cihangxie/DI-2-FGSM)<br />
  Cihang Xie, Zhishuai Zhang, Yuyin Zhou, Song Bai, Jianyu Wang, Zhou Ren, Alan L. Yuille. **CVPR**, 2019.

- ![](https://img.shields.io/badge/data-4472C4) Evading Defenses to Transferable Adversarial Examples by Translation-Invariant Attacks.
  [[pdf]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Dong_Evading_Defenses_to_Transferable_Adversarial_Examples_by_Translation-Invariant_Attacks_CVPR_2019_paper.pdf)
  [[code]](https://github.com/dongyp13/Translation-Invariant-Attacks)<br />
  Yinpeng Dong, Tianyu Pang, Hang Su, Jun Zhu. **CVPR**, 2019.

- ![](https://img.shields.io/badge/optimization-D95E32) ![](https://img.shields.io/badge/data-4472C4) Nesterov Accelerated Gradient and Scale Invariance for Adversarial Attacks.
  [[pdf]](https://arxiv.org/pdf/1908.06281.pdf)
  [[code]](https://github.com/JHL-HUST/SI-NI-FGSM)<br />
  Jiadong Lin, Chuanbiao Song, Kun He, Liwei Wang, John E. Hopcroft. arxiv, 2019.

- ![](https://img.shields.io/badge/loss-538C51) Enhancing Adversarial Example Transferability With an Intermediate Level Attack.
  [[pdf]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Huang_Enhancing_Adversarial_Example_Transferability_With_an_Intermediate_Level_Attack_ICCV_2019_paper.pdf)
  [[code]](https://github.com/CUAI/Intermediate-Level-Attack)<br />
  Qian Huang, Isay Katsman, Horace He, Zeqi Gu, Serge Belongie, Ser-Nam Lim. **ICCV**, 2019.

- ![](https://img.shields.io/badge/loss-538C51) FDA: Feature Disruptive Attack.
  [[pdf]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Ganeshan_FDA_Feature_Disruptive_Attack_ICCV_2019_paper.pdf)
  [[code]](https://github.com/BardOfCodes/fda)<br />
  Aditya Ganeshan, Vivek B.S., R. Venkatesh Babu. **ICCV**, 2019

- ![](https://img.shields.io/badge/loss-538C51) Feature Space Perturbations Yield More Transferable Adversarial Examples.
  [[pdf]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Inkawhich_Feature_Space_Perturbations_Yield_More_Transferable_Adversarial_Examples_CVPR_2019_paper.pdf)
  [[code]](https://github.com/Shall-Ven/Activation-Attack)<br />
  Nathan Inkawhich, Wei Wen, Hai (Helen) Li, Yiran Chen. **CVPR**, 2019.

- ![](https://img.shields.io/badge/generative-D94A70) Once a MAN: Towards Multi-Target Attack via Learning Multi-Target Adversarial Network Once.
  [[pdf]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Han_Once_a_MAN_Towards_Multi-Target_Attack_via_Learning_Multi-Target_Adversarial_ICCV_2019_paper.pdf)<br />
  Jiangfan Han, Xiaoyi Dong, Ruimao Zhang, Dongdong Chen, Weiming Zhang, Nenghai Yu, Ping Luo, Xiaogang Wang. **ICCV**, 2019.

- ![](https://img.shields.io/badge/generative-D94A70) Cross-Domain Transferability of Adversarial Perturbations.
  [[pdf]](https://proceedings.neurips.cc/paper_files/paper/2019/file/99cd3843754d20ec3c5885d805db8a32-Paper.pdf)
  [[code]](https://github.com/Muzammal-Naseer/Cross-domain-perturbations)<br />
  Muhammad Muzammal Naseer, Salman H. Khan, Muhammad Haris Khan, Fahad Shahbaz Khan, Fatih Porikli. **NIPS**, 2019.

#### 2018
- ![](https://img.shields.io/badge/loss-538C51) Task-generalizable Adversarial Attack based on Perceptual Metric.
  [[pdf]](https://arxiv.org/pdf/1811.09020.pdf)<br />
  Muzammal Naseer, Salman H. Khan, Shafin Rahman, Fatih Porikli. arxiv, 2018.

- ![](https://img.shields.io/badge/optimization-D95E32) Boosting Adversarial Attacks with Momentum.
  [[pdf]](https://openaccess.thecvf.com/content_cvpr_2018/papers/Dong_Boosting_Adversarial_Attacks_CVPR_2018_paper.pdf)
  [[code]](https://github.com/dongyp13/Non-Targeted-Adversarial-Attacks)<br />
  Yinpeng Dong, Fangzhou Liao, Tianyu Pang, Hang Su, Jun Zhu, Xiaolin Hu, Jianguo Li. **CVPR**, 2018.

- ![](https://img.shields.io/badge/loss-538C51) Transferable Adversarial Perturbations.
  [[pdf]](https://openaccess.thecvf.com/content_ECCV_2018/papers/Bruce_Hou_Transferable_Adversarial_Perturbations_ECCV_2018_paper.pdf)<br />
  Wen Zhou, Xin Hou, Yongjun Chen, Mengyun Tang, Xiangqi Huang, Xiang Gan, Yong Yang. **ECCV**, 2018.

- ![](https://img.shields.io/badge/model-7030A0) Transferable Adversarial Attacks for Image and Video Object Detection.
  [[pdf]](https://arxiv.org/pdf/1811.12641v5.pdf)
  [[code]](https://github.com/LiangSiyuan21/Adversarial-Attacks-for-Image-and-Video-Object-Detection/tree/master/img_attack_with_attention)<br />
  Xingxing Wei, Siyuan Liang, Ning Chen, Xiaochun Cao. arxiv, 2018.

- ![](https://img.shields.io/badge/generative-D94A70) Generative Adversarial Perturbations.
  [[pdf]](https://openaccess.thecvf.com/content_cvpr_2018/papers/Poursaeed_Generative_Adversarial_Perturbations_CVPR_2018_paper.pdf)
  [[code]](https://github.com/OmidPoursaeed/Generative_Adversarial_Perturbations)<br />
  Omid Poursaeed, Isay Katsman, Bicheng Gao, Serge Belongie. **CVPR**, 2018.

#### 2017
- ![](https://img.shields.io/badge/loss-538C51) LOTS about Attacking Deep Features.
  [[pdf]](https://arxiv.org/pdf/1611.06179)<br />
  Andras Rozsa, Manuel Günther, Terrance E. Boult. **IJCB**, 2017. 

- ![](https://img.shields.io/badge/model-7030A0) Delving into Transferable Adversarial Examples and Black-box Attacks.
  [[pdf]](https://openreview.net/pdf?id=Sys6GJqxl)
  [[code]](https://github.com/sunblaze-ucb/transferability-advdnn-pub)<br />
  Yanpei Liu, Xinyun Chen, Chang Liu, Dawn Song, **ICLR**, 2017


### Contact

Please contact us (jindong.gu@outlook.com) if 
- you would like to add your paper in this repo,
- you find any mistake in this repo, 
- you have any suggestion for this repo. 

