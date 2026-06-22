<div align="center">
  <h1>Beyond NL2Code: A Structured Survey of Multimodal Code Intelligence</h1>
  <a href="https://awesome.re">
    <img src="https://awesome.re/badge.svg" alt="Awesome">
  </a>
  <a href="https://img.shields.io/badge/PRs-Welcome-red">
    <img src="https://img.shields.io/badge/PRs-Welcome-red" alt="PRs Welcome">
  </a>
  <a href="https://img.shields.io/github/last-commit/xxlllz/Awesome-Multimodal-LLM-for-Code?color=green">
    <img src="https://img.shields.io/github/last-commit/xxlllz/Awesome-Multimodal-LLM-for-Code?color=green" alt="Last Commit">
  </a>
</div>

<p align="center">
  <img src="assets/figures/overview.png" alt="Survey overview" width="95%">
</p>

This repository tracks papers, benchmarks, datasets, and systems for **Multimodal Code Intelligence**, aligned with the survey paper **Beyond NL2Code: A Structured Survey of Multimodal Code Intelligence**.

The survey organizes the field by the role code plays when visual information is part of the programming task:
- **Graphical User Interface:** web and mobile UI generation, editing, refinement, interaction, and repair.
- **Scientific Visualization:** chart, document, slide, poster, and scientific-demonstration code that should preserve data, structure, equations, argument flow, and domain constraints.
- **Structured Graphics:** SVG, diagrams, CAD, and 3D shape programs where generated code should remain symbolic, editable, and structurally valid.
- **Frontier Tasks and Frameworks:** code as a visual-reasoning tool trace, software-repair interface, temporal procedure, embodied policy, game artifact, or unified multimodal-code interface.

<p align="center">
  <img src="assets/figures/publication_trend.png" alt="Publication trend" width="95%">
</p>

# Content

- [1. Graphical User Interface](#1-graphical-user-interface)
  - [1.1 Website Application](#11-website-application)
  - [1.2 Mobile Application](#12-mobile-application)
- [2. Scientific Visualization](#2-scientific-visualization)
  - [2.1 Statistical Charts](#21-statistical-charts)
  - [2.2 Structured Document](#22-structured-document)
  - [2.3 Academic Presentations](#23-academic-presentations)
  - [2.4 Scientific Demonstration](#24-scientific-demonstration)
- [3. Structured Graphics](#3-structured-graphics)
  - [3.1 Scalable Vector Graphics (SVG)](#31-scalable-vector-graphics-svg)
  - [3.2 Diagram](#32-diagram)
  - [3.3 Computer-Aided Design (CAD)](#33-computer-aided-design-cad)
- [4. Frontier Tasks and Frameworks](#4-frontier-tasks-and-frameworks)
  - [4.1 Programmatic Visual Manipulation](#41-programmatic-visual-manipulation)
  - [4.2 Video Code Generation](#42-video-code-generation)
  - [4.3 Embodied Control](#43-embodied-control)
  - [4.4 Visually Grounded Programming](#44-visually-grounded-programming)
  - [4.5 Unified Multimodal Code Generation](#45-unified-multimodal-code-generation)
- [Contributing](#contributing)

---

# 📜 Papers

> You can directly click on a paper title to jump to its PDF, project page, or official source when a link is available.

## 1. Graphical User Interface

<p align="center">
  <img src="assets/figures/gui_task.png" alt="GUI code generation tasks" width="90%">
</p>

### 1.1 Website Application

1. [**Unlocking the conversion of Web Screenshots into HTML Code with the WebSight Dataset**](https://arxiv.org/abs/2403.09029) *Hugo Laurençon, Léo Tronchon, Victor Sanh.* 📄 (arXiv 2024).

2. [**Web2Code: A Large-scale Webpage-to-Code Dataset and Evaluation Framework for Multimodal LLMs**](https://arxiv.org/abs/2406.20098) *Sukmin Yun, Haokun Lin, Rusiru Thushara, Mohammad Qazim Bhat, Yongxin Wang, Zutao Jiang, Mingkai Deng, Jinhong Wang, Tianhua Tao, Junbo Li, Haonan Li, Preslav Nakov, Timothy Baldwin, Zhengzhong Liu, Eric P. Xing, Xiaodan Liang, Zhiqiang Shen.* 🏛️ (NeurIPS 2024 Datasets and Benchmarks). &nbsp;&nbsp; [GitHub](https://github.com/MBZUAI-LLM/web2code)

3. [**Design2Code: Benchmarking Multimodal Code Generation for Automated Front-End Engineering**](https://arxiv.org/abs/2403.03163) *Chenglei Si, Yanzhe Zhang, Ryan Li, Zhengyuan Yang, Ruibo Liu, Diyi Yang.* 🏛️ (NAACL 2025). &nbsp;&nbsp; [GitHub](https://github.com/NoviScl/Design2Code)

4. [**WebCode2M: A Real-World Dataset for Code Generation from Webpage Designs**](https://arxiv.org/abs/2404.06369) *Yi Gui, Zhen Li, Yao Wan, Yemin Shi, Hongyu Zhang, Yi Su, Bohua Chen, Dongping Chen, Siyuan Wu, Xing Zhou, Wenbin Jiang, Hai Jin, Xiangliang Zhang.* 📄 (arXiv 2024).

5. [**WebCode2M: A Real-World Dataset for Code Generation from Webpage Designs**](https://openreview.net/pdf?id=aeP5nmlw5B) *Yi Gui, Zhen Li, Yao Wan, Yemin Shi, Hongyu Zhang, Yi Su, Bohua Chen, Dongping Chen, Siyuan Wu, Xing Zhou, Wenbin Jiang, Hai Jin, Xiangliang Zhang.* 🏛️ (WWW 2025 Oral). &nbsp;&nbsp; [GitHub](https://github.com/CGCL-codes/naturalcc/tree/main/examples/webcode2m)

6. [**IW-Bench: Evaluating Large Multimodal Models for Converting Image-to-Web**](https://arxiv.org/abs/2409.18980) *Hongcheng Guo, Wei Zhang, Junhao Chen, Yaonan Gu, Jian Yang, Junjia Du, Shaosheng Cao, Binyuan Hui, Tianyu Liu, Jianxin Ma, Chang Zhou, Zhoujun Li.* 🏛️ (ACL 2025 Findings). &nbsp;&nbsp; [GitHub](https://github.com/HC-Guo/IWBench)

7. [**WebRenderBench: Enhancing Web Interface Generation through Layout-Style Consistency and Reinforcement Learning**](https://arxiv.org/abs/2510.04097) *Peichao Lai, Jinhui Zhuang, Kexuan Zhang, Ningchang Xiong, Shengjie Wang, Yanwei Xu, Chong Chen, Yilei Wang, Bin Cui.* 📄 (arXiv 2025).

8. [**WebGen-V Bench: Structured Representation for Enhancing Visual Design in LLM-based Web Generation and Evaluation**](https://arxiv.org/abs/2510.15306) *Kuang-Da Wang, Zhao Wang, Yotaro Shimose, Wei-Yao Wang, Shingo Takamatsu.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/sony/web_gen_v_bench)

9. [**DesignBench: A Comprehensive Benchmark for MLLM-based Front-end Code Generation**](https://arxiv.org/abs/2506.06251) *Jingyu Xiao, Ming Wang, Man Ho Lam, Yuxuan Wan, Junliang Liu, Yintong Huo, Michael R. Lyu.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/WebPAI/DesignBench)

10. [**WebUIBench: A Comprehensive Benchmark for Evaluating Multimodal Large Language Models in WebUI-to-Code**](https://arxiv.org/abs/2506.07818) *Zhiyu Lin, Zhengda Zhou, Zhiyuan Zhao, Tianrui Wan, Yilun Ma, Junyu Gao, Xuelong Li.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/MAIL-Tele-AI/WebUIBench)

11. [**FullFront: Benchmarking MLLMs Across the Full Front-End Engineering Workflow**](https://arxiv.org/abs/2505.17399) *Haoyu Sun, Huichen Will Wang, Jiawei Gu, Linjie Li, Yu Cheng.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/Mikivishy/FullFront)

12. [**Interaction2Code: Benchmarking MLLM-based Interactive Webpage Code Generation from Interactive Prototyping**](https://arxiv.org/abs/2411.03292) *Jingyu Xiao, Yuxuan Wan, Yintong Huo, Zixin Wang, Xinyi Xu, Wenxuan Wang, Zhiyao Xu, Yuhang Wang, Michael R. Lyu.* 🏛️ (ASE 2025). &nbsp;&nbsp; [GitHub](https://github.com/WebPAI/Interaction2Code)

13. [**MRWeb: An Exploration of Generating Multi-Page Resource-Aware Web Code from UI Designs**](https://arxiv.org/abs/2412.15310) *Yuxuan Wan, Yi Dong, Jingyu Xiao, Yintong Huo, Wenxuan Wang, Michael R. Lyu.* 📄 (arXiv 2024). &nbsp;&nbsp; [GitHub](https://github.com/WebPAI/MRWeb)

14. [**Web-Bench: A LLM Code Benchmark Based on Web Standards and Frameworks**](https://arxiv.org/abs/2505.07473) *Kai Xu, YiWei Mao, XinYi Guan, ZiLong Feng.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/bytedance/web-bench)

15. [**IWR-Bench: Can LVLMs reconstruct interactive webpage from a user interaction video?**](https://arxiv.org/abs/2509.24709) *Yang Chen, Minghao Liu, Yufan Shen, Yunwen Li, Tianyuan Huang, Xinyu Fang, Tianyu Zheng, Wenxuan Huang, Cheng Yang, Daocheng Fu, Jianbiao Mei, Rong Wu, Yunfei Zhao, Licheng Wen, Xuemeng Yang, Song Mao, Qunshu Lin, Zhi Yu, Yongliang Shen, Yu Qiao, Botian Shi.* 🏛️ (ICLR 2026).

16. [**WebGen-Bench: Evaluating LLMs on Generating Interactive and Functional Websites from Scratch**](https://arxiv.org/abs/2505.03733) *Zimu Lu, Yunqiao Yang, Houxing Ren, Haotian Hou, Han Xiao, Ke Wang, Weikang Shi, Aojun Zhou, Mingjie Zhan, Hongsheng Li.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/mnluzimu/WebGen-Bench)

17. [**EfficientUICoder: Efficient MLLM-based UI Code Generation via Input and Output Token Compression**](https://arxiv.org/abs/2509.12159) *Jingyu Xiao, Zhongyi Zhang, Yuxuan Wan, Yintong Huo, Yang Liu, Michael R. Lyu.* 🏛️ (FSE 2026). &nbsp;&nbsp; [GitHub](https://github.com/WebPAI/EfficientUICoder)

18. [**ScreenCoder: Advancing Visual-to-Code Generation for Front-End Automation via Modular Multimodal Agents**](https://arxiv.org/abs/2507.22827) *Yilei Jiang, Yaozhi Zheng, Yuxuan Wan, Jiaming Han, Qunzhong Wang, Michael R. Lyu, Xiangyu Yue.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/leigest519/ScreenCoder)

19. [**Frontend Diffusion: Empowering Self-Representation of Junior Researchers and Designers Through Multi-agent System**](https://arxiv.org/abs/2502.03788) *Zijian Ding, Qinshi Zhang, Mohan Chi, Ziyi Wang.* 📄 (arXiv 2025).

20. [**Automatically Generating Web Applications from Requirements Via Multi-Agent Test-Driven Development**](https://arxiv.org/abs/2509.25297) *Yuxuan Wan, Tingshuo Liang, Jiakai Xu, Jingyu Xiao, Yintong Huo, Michael R. Lyu.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/yxwan123/TDDev)

21. [**ComUICoder: Component-based Reusable UI Code Generation for Complex Websites via Semantic Segmentation and Element-wise Feedback**](https://arxiv.org/abs/2602.19276) *Jingyu Xiao, Jiantong Qin, Shuoqi Li, Man Ho Lam, Yuxuan Wan, Jen-tse Huang, Yintong Huo, Michael R. Lyu.* 🏛️ (KDD 2026). &nbsp;&nbsp; [GitHub](https://github.com/WebPAI/ComUICoder)

22. [**UI2Code^N: UI-to-Code Generation as Interactive Visual Optimization**](https://arxiv.org/abs/2511.08195) *Zhen Yang, Wenyi Hong, Mingde Xu, Xinyue Fan, Weihan Wang, Jiale Cheng, Xiaotao Gu, Jie Tang.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/zai-org/UI2Code_N)

23. [**ReLook: Vision-Grounded RL with a Multimodal LLM Critic for Agentic Web Coding**](https://arxiv.org/abs/2510.11498) *Yuhang Li, Chenchen Zhang, Ruilin Lv, Ao Liu, Ken Deng, Yuanxing Zhang, Jiaheng Liu, Wiggin Zhou, Bo Zhou.* 📄 (arXiv 2025).

24. [**Computer-Use Agents as Judges for Generative User Interface**](https://arxiv.org/abs/2511.15567) *Kevin Qinghong Lin, Siyuan Hu, Linjie Li, Zhengyuan Yang, Lijuan Wang, Philip Torr, Mike Zheng Shou.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/showlab/AUI)

25. [**UIClip: A Data-driven Model for Assessing User Interface Design**](https://dl.acm.org/doi/10.1145/3654777.3676408) *Jason Wu, Yi-Hao Peng, Xin Yue Amanda Li, Amanda Swearngin, Jeffrey P Bigham, Jeffrey Nichols.* 🏛️ (UIST 2024).

26. [**WebVIA: A Web-based Vision-Language Agentic Framework for Interactive and Verifiable UI-to-Code Generation**](https://arxiv.org/abs/2511.06251) *Mingde Xu, Zhen Yang, Wenyi Hong, Lihang Pan, Xinyue Fan, Yan Wang, Xiaotao Gu, Bin Xu, Jie Tang.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/zheny2751-dotcom/WebVIA)

27. [**NLDesign: A UI Design Tool for Natural Language Interfaces**](https://dl.acm.org/doi/10.1145/3674399.3674455) *Tianhao Zhang, Fu Peiguo, Jie Liu, Yihe Zhang, Xingmei Chen.* 🏛️ (ACM-TURC 2024).

28. [**Automatically Generating UI Code from Screenshot: A Divide-and-Conquer-Based Approach**](https://arxiv.org/abs/2406.16386) *Yuxuan Wan, Chaozheng Wang, Yi Dong, Wenxuan Wang, Shuqing Li, Yintong Huo, Michael R. Lyu.* 🏛️ (FSE 2025). &nbsp;&nbsp; [GitHub](https://github.com/WebPAI/DCGen)

29. [**Prototype2Code: End-to-end Front-end Code Generation from UI Design Prototypes**](https://arxiv.org/abs/2405.04975) *Shuhong Xiao, Yunnong Chen, Jiazhi Li, Liuqing Chen, Lingyun Sun, Tingting Zhou.* 📄 (arXiv 2024).

30. [**Bridging Design and Development with Automated Declarative UI Code Generation**](https://arxiv.org/abs/2409.11667) *Ting Zhou, Yanjie Zhao, Xinyi Hou, Xiaoyu Sun, Kai Chen, Haoyu Wang.* 🏛️ (FSE 2025).

31. [**Sketch2Code: Evaluating Vision-Language Models for Interactive Web Design Prototyping**](https://arxiv.org/abs/2410.16232) *Ryan Li, Yanzhe Zhang, Diyi Yang.* 📄 (arXiv 2024). &nbsp;&nbsp; [GitHub](https://github.com/SALT-NLP/Sketch2Code)

32. [**WAFFLE: Finetuning Multi-Modal Models for Automated Front-End Development**](https://arxiv.org/abs/2410.18362) *Shanchao Liang, Nan Jiang, Shangshu Qian, Lin Tan.* 🏛️ (ACL 2025 Main). &nbsp;&nbsp; [GitHub](https://github.com/lt-asset/Waffle)

33. [**UICopilot: Automating UI Synthesis via Hierarchical Code Generation from Webpage Designs**](https://openreview.net/pdf?id=faMbH0wkye) *Yi Gui, Yao Wan, Zhen Li, Zhongyi Zhang, Dongping Chen, Hongyu Zhang, Yi Su, Bohua Chen, Xing Zhou, Wenbin Jiang, Xiangliang Zhang.* 🏛️ (WWW 2025 Oral).

34. [**Zero-Shot Prompting Approaches for LLM-based Graphical User Interface Generation**](https://arxiv.org/abs/2412.11328) *Kristian Kolthoff, Felix Kretzer, Lennart Fiebig, Christian Bartelt, Alexander Maedche, Simone Paolo Ponzetto.* 📄 (arXiv 2024).

35. [**Towards Human-AI Synergy in UI Design: Supporting Iterative Generation with LLMs**](https://arxiv.org/abs/2412.20071) *Mingyue Yuan, Jieshan Chen, Yongquan Hu, Sidong Feng, Mulong Xie, Gelareh Mohammadi, Zhenchang Xing, Aaron Quigley.* 📄 (arXiv 2024).

36. [**UICrit: Enhancing Automated Design Evaluation with a UICritique Dataset**](https://arxiv.org/abs/2407.08850) *Peitong Duan, Chin-yi Chen, Gang Li, Bjoern Hartmann, Yang Li.* 🏛️ (UIST 2024). &nbsp;&nbsp; [GitHub](https://github.com/google-research-datasets/uicrit)

37. [**Advancing vision-language models in front-end development via data synthesis**](https://arxiv.org/abs/2503.01619) *Tong Ge, Yashu Liu, Jieping Ye, Tianyi Li, Chao Wang.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/Flame-Code-VLM/Flame-Code-VLM)

38. [**Multimodal graph representation learning for website generation based on visual sketch**](https://arxiv.org/abs/2504.18729) *Tung D. Vu, Chung Hoang, Truong-Son Hy.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/HySonLab/Design2Code)

39. [**MLLM-Based UI2Code Automation Guided by UI Layout Information**](https://arxiv.org/abs/2506.10376) *Fan Wu, Cuiyun Gao, Shuqing Li, Xin-Cheng Wen, Qing Liao.* 🏛️ (ISSTA 2025). &nbsp;&nbsp; [GitHub](https://github.com/ay7u1009/LayoutCoder/)

40. [**DesignCoder: Hierarchy-Aware and Self-Correcting UI Code Generation with Large Language Models**](https://arxiv.org/abs/2506.13663) *Yunnong Chen, Shixian Ding, YingYing Zhang, Wenkai Chen, Jinzhou Du, Lingyun Sun, Liuqing Chen.* 📄 (arXiv 2025).

41. [**FrontendBench: A Benchmark for Evaluating LLMs on Front-End Development via Automatic Evaluation**](https://arxiv.org/abs/2506.13832) *Hongda Zhu, Yiwen Zhang, Bing Zhao, Jingzhe Ding, Siyao Liu, Tong Liu, Dandan Wang, Yanan Liu, Zhaojian Li.* 📄 (arXiv 2025).

42. [**Generative Interfaces for Language Models**](https://arxiv.org/abs/2508.19227) *Jiaqi Chen, Yanzhe Zhang, Yutong Zhang, Yijia Shao, Diyi Yang.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/SALT-NLP/GenUI)

43. [**UI-Bench: A Benchmark for Evaluating Design Capabilities of AI Text-to-App Tools**](https://arxiv.org/abs/2508.20410) *Sam Jung, Agustin Garcinuno, Spencer Mateega.* 📄 (arXiv 2025).

44. [**WebGen-Agent: Enhancing Interactive Website Generation with Multi-Level Feedback and Step-Level Reinforcement Learning**](https://arxiv.org/abs/2509.22644) *Zimu Lu, Houxing Ren, Yunqiao Yang, Ke Wang, Zhuofan Zong, Junting Pan, Mingjie Zhan, Hongsheng Li.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/mnluzimu/WebGen-Agent)

45. [**UI-UG: A Unified MLLM for UI Understanding and Generation**](https://arxiv.org/abs/2509.24361) *Hao Yang, Weijie Qiu, Ru Zhang, Zhou Fang, Ruichao Mao, Xiaoyu Lin, Maji Huang, Zhaosong Huang, Teng Guo, Shuoyang Liu, Hai Rao.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/afx-team/UI-UG)

46. [**UIOrchestra: Generating High-Fidelity Code from UI Designs with a Multi-agent System**](https://aclanthology.org/2025.findings-emnlp.150/) *Chuhuai Yue, Jiajun Chai, Yufei Zhang, Zixiang Ding, Xihao Liang, Peixin Wang, Shihai Chen, Wang Yixuan, Wangyanping, Guojun Yin, Wei Lin.* 📄 (arXiv 2025).

47. [**CANVAS: A Benchmark for Vision-Language Models on Tool-Based User Interface Design**](https://arxiv.org/abs/2511.20737) *Daeheon Jeong, Seoyeon Byun, Kihoon Son, Dae Hyun Kim, Juho Kim.* 🏛️ (AAAI 2026). &nbsp;&nbsp; [GitHub](https://github.com/kixlab/CANVAS)

48. [**Beyond Prototyping: Autonomous, Enterprise-Grade Frontend Development from Pixel to Production via a Specialized Multi-Agent Framework**](https://arxiv.org/abs/2512.06046) *Ramprasath Ganesaraja, Swathika N, Saravanan AP, Kamalkumar Rathinasamy, Chetana Amancharla, Rahul Das, Sahil Dilip Panse, Aditya Batwe, Dileep Vijayan, Veena Ashok, Thanushree A P, Kausthubh J Rao, Alden Olivero, Roshan, Rajeshwar Reddy Manthena, Asmitha Yuga Sre A, Harsh Tripathi, Suganya Selvaraj, Vito Chin, Kasthuri Rangan Bhaskar, Kasthuri Rangan Bhaskar, Venkatraman R, Sajit Vijayakumar.* 📄 (arXiv 2025).

49. [**FronTalk: Benchmarking Front-End Development as Conversational Code Generation with Multi-Modal Feedback**](https://arxiv.org/abs/2601.04203) *Xueqing Wu, Zihan Xue, Da Yin, Shuyan Zhou, Kai-Wei Chang, Nanyun Peng, Yeming Wen.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/shirley-wu/frontalk)

50. [**Widget2Code: From Visual Widgets to UI Code via Multimodal LLMs**](https://arxiv.org/abs/2512.19918) *Houston H. Zhang, Tao Zhang, Baoze Lin, Yuanqi Xue, Yincheng Zhu, Huan Liu, Li Gu, Linfeng Ye, Ziqiang Wang, Xinxin Zuo, Yang Wang, Yuanhao Yu, Zhixiang Chi.* 🏛️ (CVPR 2026). &nbsp;&nbsp; [GitHub](https://github.com/Djanghao/widget2code)

51. [**WebCoderBench: Benchmarking Web Application Generation with Comprehensive and Interpretable Evaluation Metrics**](https://arxiv.org/abs/2601.02430) *Chenxu Liu, Yingjie Fu, Wei Yang, Ying Zhang, Tao Xie.* 📄 (arXiv 2026).

52. [**FullStack-Agent: Enhancing Agentic Full-Stack Web Coding via Development-Oriented Testing and Repository Back-Translation**](https://arxiv.org/abs/2602.03798) *Zimu Lu, Houxing Ren, Yunqiao Yang, Ke Wang, Zhuofan Zong, Mingjie Zhan, Hongsheng Li.* 📄 (arXiv 2026). &nbsp;&nbsp; [GitHub](https://github.com/mnluzimu/FullStack-Agent)

53. [**VisRefiner: Learning from Visual Differences for Screenshot-to-Code Generation**](https://arxiv.org/abs/2602.05998) *Jie Deng, Kaichun Yao, Libo Zhang.* 📄 (arXiv 2026).

54. [**Bridging Design and Implementation: A Study of Multi-Agent LLM Architectures for Automated Front-End Generation**](https://das.encs.concordia.ca/pdf/rizk_MSR2026.pdf) *Caren Rizk, SayedHassan Khatoonabadi, Emad Shihab.* 🏛️ (MSR 2026).

55. [**SWE-Bench Mobile: Can Large Language Model Agents Develop Industry-Level Mobile Applications?**](https://arxiv.org/abs/2602.09540) *Muxin Tian, Zhe Wang, Blair Yang, Zhenwei Tang, Kunlun Zhu, Honghua Dong, Hanchen Li, Xinni Xie, Guangjing Wang, Jiaxuan You.* 📄 (arXiv 2026).

56. [**1D-Bench: A Benchmark for Iterative UI Code Generation with Visual Feedback in Real-World**](https://arxiv.org/abs/2602.18548) *Qiao Xu, Yipeng Yu, Chengxiao Feng, Xu Liu.* 📄 (arXiv 2026).

57. [**LikeThis! Empowering App Users to Submit UI Improvement Suggestions Instead of Complaints**](https://arxiv.org/abs/2603.04245) *Jialiang Wei, Ali Ebrahimi Pourasad, Walid Maalej.* 📄 (arXiv 2026).

58. [**No Code, No Cloud: On-Device Mockup-to-Code withLightweight Vision-Language AI**](https://dl.acm.org/doi/full/10.1145/3742413.3789144) *Abinas Kuganathan, Mitra Purandare, Markus Stolze.* 🏛️ (IUI 2026).

59. [**AutoStructGUI: Bridging Design and Implementation of GUI through Structured Layout Generation**](https://dl.acm.org/doi/full/10.1145/3742413.3789058) *Junquan Ren, Pengfei Xu.* 🏛️ (IUI 2026).

60. [**Vision2Web: A Hierarchical Benchmark for Visual Website Development with Agent Verification**](https://arxiv.org/abs/2603.26648) *Zehai He, Wenyi Hong, Zhen Yang, Ziyang Pan, Mingdao Liu, Xiaotao Gu, Jie Tang.* 📄 (arXiv 2026). &nbsp;&nbsp; [GitHub](https://github.com/zai-org/Vision2Web)

61. [**MM-WebAgent: A Hierarchical Multimodal Web Agent for Webpage Generation**](https://arxiv.org/abs/2604.15309) *Yan Li, Zezi Zeng, Yifan Yang, Yuqing Yang, Ning Liao, Weiwei Guo, Lili Qiu, Mingxi Cheng, Qi Dai, Zhendong Wang, Zhengyuan Yang, Xue Yang, Ji Li, Lijuan Wang, Chong Luo.* 📄 (arXiv 2026). &nbsp;&nbsp; [GitHub](https://github.com/microsoft/MM-WebAgent)

62. [**WebCompass: Towards Multimodal Web Coding Evaluation for Code Language Models**](https://arxiv.org/abs/2604.18224) *Xinping Lei, Xinyu Che, Junqi Xiong, Chenchen Zhang, Yukai Huang, Chenyu Zhou, Haoyang Huang, Minghao Liu, Letian Zhu, Hongyi Ye, Jinhua Hao, Ken Deng, Zizheng Zhan, Han Li, Dailin Li, Yifan Yao, Ming Sun, Zhaoxiang Zhang, Jiaheng Liu.* 📄 (arXiv 2026). &nbsp;&nbsp; [GitHub](https://github.com/NJU-LINK/WebCompass)

63. [**Benchmarking Multimodal LLMs on Code Generation for Complex Interactive Webpages**](https://arxiv.org/abs/2606.00154) *Fan Wu, Lishuai Dong, Cuiyun Gao, Yujia Chen, Yiming Huang, Yang Xiao, Qing Liao.* 📄 (arXiv 2026).

64. [**I-WebGenBench: Evaluating Interactivity in LLM-Generated Scientific Web Applications**](https://arxiv.org/abs/2606.00750) *Dasen Dai, Biao Wu, Meng Fang, Shuoqi Li, Wenhao Wang.* 📄 (arXiv 2026).

65. [**ProductWebGen: Benchmarking Multimodal Product Webpage Generation**](https://arxiv.org/abs/2606.01022) *Zhihong Liu, Siqi Kou, Zheng Li, Ye Ma, Quan Chen, Peng Jiang, Kai Yu, Zhijie Deng.* 🏛️ (KDD 2026). &nbsp;&nbsp; [GitHub](https://github.com/SJTU-DENG-Lab/ProductWebGen)

### 1.2 Mobile Application

1. [**UIOrchestra: Generating High-Fidelity Code from UI Designs with a Multi-agent System**](https://aclanthology.org/2025.findings-emnlp.150/) *Chuhuai Yue, Jiajun Chai, Yufei Zhang, Zixiang Ding, Xihao Liang, Peixin Wang, Shihai Chen, Wang Yixuan, Wangyanping, Guojun Yin, Wei Lin.* 🏛️ (EMNLP 2025 Findings).

2. [**CANVAS: A Benchmark for Vision-Language Models on Tool-Based User Interface Design**](https://arxiv.org/abs/2511.20737) *Daeheon Jeong, Seoyeon Byun, Kihoon Son, Dae Hyun Kim, Juho Kim.* 🏛️ (AAAI 2026). &nbsp;&nbsp; [GitHub](https://github.com/kixlab/CANVAS)

3. [**UICrit: Enhancing Automated Design Evaluation with a UICritique Dataset**](https://arxiv.org/abs/2407.08850) *Peitong Duan, Chin-yi Chen, Gang Li, Bjoern Hartmann, Yang Li.* 🏛️ (UIST 2024). &nbsp;&nbsp; [GitHub](https://github.com/google-research-datasets/uicrit)

4. [**UIClip: A Data-Driven Model for Assessing User Interface Design**](https://dl.acm.org/doi/10.1145/3654777.3676408) *Jason Wu, Yi-Hao Peng, Xin Yue Amanda Li, Amanda Swearngin, Jeffrey P Bigham, Jeffrey Nichols.* 🏛️ (UIST 2024).

5. [**Bridging Design and Development with Automated Declarative UI Code Generation**](https://arxiv.org/abs/2409.11667) *Ting Zhou, Yanjie Zhao, Xinyi Hou, Xiaoyu Sun, Kai Chen, Haoyu Wang.* 🏛️ (FSE 2025).

6. [**DesignCoder: Hierarchy-Aware and Self-Correcting UI Code Generation with Large Language Models**](https://arxiv.org/abs/2506.13663) *Yunnong Chen, Shixian Ding, YingYing Zhang, Wenkai Chen, Jinzhou Du, Lingyun Sun, Liuqing Chen.* 📄 (arXiv 2025).

7. [**Zero-Shot Prompting Approaches for LLM-based Graphical User Interface Generation**](https://arxiv.org/abs/2412.11328) *Kristian Kolthoff, Felix Kretzer, Lennart Fiebig, Christian Bartelt, Alexander Maedche, Simone Paolo Ponzetto.* 📄 (arXiv 2024). &nbsp;&nbsp; [GitHub](https://github.com/ZSPromptingGUIGeneration/ZS-Prompting-Approaches-GUI-Generation)

8. [**Rico: A Mobile App Dataset for Building Data-Driven Design Applications**](https://dl.acm.org/doi/10.1145/3126594.3126651) *Biplab Deka, Zifeng Huang, Chad Franzen, Joshua Hibschman, Daniel Afergan, Yang Li, Jeffrey Nichols, Ranjitha Kumar.* 🏛️ (UIST 2017).

9. [**UI-UG: A Unified MLLM for UI Understanding and Generation**](https://arxiv.org/abs/2509.24361) *Hao Yang, Weijie Qiu, Ru Zhang, Zhou Fang, Ruichao Mao, Xiaoyu Lin, Maji Huang, Zhaosong Huang, Teng Guo, Shuoyang Liu, Hai Rao.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/afx-team/UI-UG)

10. [**Towards Human-AI Synergy in UI Design: Supporting Iterative Generation with LLMs**](https://arxiv.org/abs/2412.20071) *Mingyue Yuan, Jieshan Chen, Yongquan Hu, Sidong Feng, Mulong Xie, Gelareh Mohammadi, Zhenchang Xing, Aaron Quigley.* 📄 (arXiv 2024).

11. [**Generative Interfaces for Language Models**](https://arxiv.org/abs/2508.19227) *Jiaqi Chen, Yanzhe Zhang, Yutong Zhang, Yijia Shao, Diyi Yang.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/SALT-NLP/GenUI)

## 2. Scientific Visualization

<p align="center">
  <img src="assets/figures/scientific_visualizations.png" alt="Scientific visualization code generation tasks" width="90%">
</p>

### 2.1 Statistical Charts

1. [**nvBench: A Large-Scale Synthesized Dataset for Cross-Domain Natural Language to Visualization Task**](https://arxiv.org/abs/2112.12926) *Yuyu Luo, Jiawei Tang, Guoliang Li.* 📄 (arXiv 2021).

2. [**VisEval: A Benchmark for Data Visualization in the Era of Large Language Models**](https://arxiv.org/abs/2407.00981) *Nan Chen, Yuge Zhang, Jiahang Xu, Kan Ren, Yuqing Yang.* 📄 (arXiv 2024).

3. [**MatPlotAgent: Method and Evaluation for LLM-Based Agentic Scientific Data Visualization**](https://arxiv.org/abs/2402.11453) *Zhiyu Yang, Zihan Zhou, Shuo Wang, Xin Cong, Xu Han, Yukun Yan, Zhenghao Liu, Zhixing Tan, Pengyuan Liu, Dong Yu, Zhiyuan Liu, Xiaodong Shi, Maosong Sun.* 📄 (arXiv 2024). &nbsp;&nbsp; [GitHub](https://github.com/thunlp/MatPlotAgent)

4. [**Drawing Pandas: A Benchmark for LLMs in Generating Plotting Code**](https://arxiv.org/abs/2412.02764) *Timur Galimzyanov, Sergey Titov, Yaroslav Golubev, Egor Bogomolov.* 📄 (arXiv 2025).

5. [**Text2Vis: A Challenging and Diverse Benchmark for Generating Multimodal Visualizations from Text**](https://arxiv.org/abs/2507.19969) *Mizanur Rahman, Md Tahmid Rahman Laskar, Shafiq Joty, Enamul Hoque.* 📄 (arXiv 2025).

6. [**nvBench 2.0: Resolving Ambiguity in Text-to-Visualization through Stepwise Reasoning**](https://arxiv.org/abs/2503.12880) *Tianqi Luo, Chuhan Huang, Leixian Shen, Boyan Li, Shuyu Shen, Wei Zeng, Nan Tang, Yuyu Luo.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/HKUSTDial/nvBench-2.0)

7. [**PlotCraft: Pushing the Limits of LLMs for Complex and Interactive Data Visualization**](https://arxiv.org/abs/2511.00010) *Jiajun Zhang, Jianke Zhang, Zeyu Cui, Jiaxi Yang, Lei Zhang, Binyuan Hui, Qiang Liu, Zilei Wang, Liang Wang, Junyang Lin.* 📄 (arXiv 2025).

8. [**ChartX & ChartVLM: A Versatile Benchmark and Foundation Model for Complicated Chart Reasoning**](https://arxiv.org/abs/2402.12185) *Renqiu Xia, Bo Zhang, Hancheng Ye, Xiangchao Yan, Qi Liu, Hongbin Zhou, Zijun Chen, Peng Ye, Min Dou, Botian Shi, Junchi Yan, Yu Qiao.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/InternScience/ChartVLM)

9. [**Plot2Code: A Comprehensive Benchmark for Evaluating Multi-modal Large Language Models in Code Generation from Scientific Plots**](https://arxiv.org/abs/2405.07990) *Chengyue Wu, Yixiao Ge, Qiushan Guo, Jiahao Wang, Zhixuan Liang, Zeyu Lu, Ying Shan, Ping Luo.* 🏛️ (NAACL 2025 Findings). &nbsp;&nbsp; [GitHub](https://github.com/TencentARC/Plot2Code)

10. [**ChartMimic: Evaluating LMM's Cross-Modal Reasoning Capability via Chart-to-Code Generation**](https://arxiv.org/abs/2406.09961) *Cheng Yang, Chufan Shi, Yaxin Liu, Bo Shui, Junjie Wang, Mohan Jing, Linran Xu, Xinyu Zhu, Siheng Li, Yuxiang Zhang, Gongye Liu, Xiaomei Nie, Deng Cai, Yujiu Yang.* 📄 (arXiv 2024). &nbsp;&nbsp; [GitHub](https://github.com/ChartMimic/ChartMimic)

11. [**ChartEdit: How Far Are MLLMs From Automating Chart Analysis? Evaluating MLLMs' Capability via Chart Editing**](https://arxiv.org/abs/2505.11935) *Xuanle Zhao, Xuexin Liu, Haoyue Yang, Xianzhen Luo, Fanhu Zeng, Jianling Li, Qi Shi, Chi Chen.* 🏛️ (ACL 2025 Findings). &nbsp;&nbsp; [GitHub](https://github.com/xxlllz/ChartEdit)

12. [**ChartM$^3$: Benchmarking Chart Editing with Multimodal Instructions**](https://arxiv.org/abs/2507.21167) *Donglu Yang, Liang Zhang, Zihao Yue, Liangyu Chen, Yichen Xu, Wenxuan Wang, Qin Jin.* 📄 (arXiv 2025).

13. [**ChartEditor: A Reinforcement Learning Framework for Robust Chart Editing**](https://arxiv.org/abs/2511.15266) *Liangyu Chen, Yichen Xu, Jianzhe Ma, Yuqi Liu, Donglu Yang, Liang Zhang, Wenxuan Wang, Qin Jin.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/CleyLyChen/ChartEditor)

14. [**ChartGalaxy: A Dataset for Infographic Chart Understanding and Generation**](https://arxiv.org/abs/2505.18668) *Zhen Li, Duan Li, Yukai Guo, Xinyuan Guo, Bowen Li, Lanxi Xiao, Shenyu Qiao, Jiashu Chen, Zijian Wu, Hui Zhang, Xinhuan Shu, Shixia Liu.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/ChartGalaxy/ChartGalaxy)

15. [**From Charts to Code: A Hierarchical Benchmark for Multimodal Models**](https://arxiv.org/abs/2510.17932) *Jiahao Tang, Henry Hengyuan Zhao, Lijian Wu, Zijian Zhang, Yifei Tao, Dongxing Mao, Yang Wan, Jingru Tan, Min Zeng, Min Li, Alex Jinpeng Wang.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/CSU-JPG/Chart2Code)

16. [**Automated Visualization Code Synthesis via Multi-Path Reasoning and Feedback-Driven Optimization**](https://arxiv.org/abs/2502.11140) *Wonduk Seo, Daye Kang, Hyunjin An, Taehan Kim, Soohyuk Cho, Seungyong Lee, Minhyeong Yu, Jian Park, Yi Bu, Seunghyun Lee.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/leesy7197/vispath)

17. [**nvAgent: Automated Data Visualization from Natural Language via Collaborative Agent Workflow**](https://arxiv.org/abs/2502.05036) *Geliang Ouyang, Jingyao Chen, Zhihe Nie, Yi Gui, Yao Wan, Hongyu Zhang, Dongping Chen.* 🏛️ (ACL 2025 Main). &nbsp;&nbsp; [GitHub](https://github.com/geliang0114/nvAgent)

18. [**AMACE: Automatic Multi-Agent Chart Evolution for Iteratively Tailored Chart Generation**](https://doi.org/10.18653/v1/2025.emnlp-main.1089) *Hyuk Namgoong, Jeesu Jung, Hyeonseok Kang, Yohan Lee, Sangkeun Jung.* 🏛️ (EMNLP 2025).

19. [**Doc2Chart: Intent-Driven Zero-Shot Chart Generation from Documents**](https://arxiv.org/abs/2507.14819) *Akriti Jain, Pritika Ramu, Aparna Garimella, Apoorv Saxena.* 📄 (arXiv 2025).

20. [**Text2Chart31: Instruction Tuning for Chart Generation with Automatic Feedback**](https://arxiv.org/abs/2410.04064) *Fatemeh Pesaran Zadeh, Juyeon Kim, Jin-Hwa Kim, Gunhee Kim.* 📄 (arXiv 2024). &nbsp;&nbsp; [GitHub](https://github.com/fatemehpesaran310/Text2Chart31)

21. [**VisCoder: Fine-Tuning LLMs for Executable Python Visualization Code Generation**](https://arxiv.org/abs/2506.03930) *Yuansheng Ni, Ping Nie, Kai Zou, Xiang Yue, Wenhu Chen.* 🏛️ (EMNLP 2025 Findings). &nbsp;&nbsp; [GitHub](https://github.com/TIGER-AI-Lab/VisCoder)

22. [**ChartLlama: A Multimodal LLM for Chart Understanding and Generation**](https://arxiv.org/abs/2311.16483) *Yucheng Han, Chi Zhang, Xin Chen, Xu Yang, Zhibin Wang, Gang Yu, Bin Fu, Hanwang Zhang.* 📄 (arXiv 2023). &nbsp;&nbsp; [GitHub](https://github.com/tingxueronghua/ChartLlama-code)

23. [**ChartMoE: Mixture of Diversely Aligned Expert Connector for Chart Understanding**](https://arxiv.org/abs/2409.03277) *Zhengzhuo Xu, Bowen Qu, Yiyan Qi, Sinan Du, Chengjin Xu, Chun Yuan, Jian Guo.* 🏛️ (ICLR 2025 Oral). &nbsp;&nbsp; [GitHub](https://github.com/DataArcTech/ChartMoE)

24. [**ChartCoder: Advancing Multimodal Large Language Model for Chart-to-Code Generation**](https://arxiv.org/abs/2501.06598) *Xuanle Zhao, Xianzhen Luo, Qi Shi, Chi Chen, Shuo Wang, Zhiyuan Liu, Maosong Sun.* 🏛️ (ACL 2025 Main). &nbsp;&nbsp; [GitHub](https://github.com/thunlp/ChartCoder)

25. [**Chart2Code53: A Large-Scale Diverse and Complex Dataset for Enhancing Chart-to-Code Generation**](https://aclanthology.org/2025.emnlp-main.799/) *Tianhao Niu, Yiming Cui, Baoxin Wang, Xiao Xu, Xin Yao, Qingfu Zhu, Dayong Wu, Shijin Wang, Wanxiang Che.* 🏛️ (EMNLP 2025). &nbsp;&nbsp; [GitHub](https://github.com/nth2000/Chart2Code53)

26. [**ChartGen-Agent: A Three-Stage Framework for Automated High-Quality Chart Generation**](https://doi.org/10.1007/978-981-95-3462-3_2) *Rui Jiang, Shenrong Wu, Zhehao Wu, Zhenjie Han, Jiang Zhong.* 🏛️ (ADMA 2025).

27. [**METAL: A Multi-Agent Framework for Chart Generation with Test-Time Scaling**](https://arxiv.org/abs/2502.17651) *Bingxuan Li, Yiwei Wang, Jiuxiang Gu, Kai-Wei Chang, Nanyun Peng.* 🏛️ (ACL 2025 Main). &nbsp;&nbsp; [GitHub](https://github.com/metal-chart-generation/metal)

28. [**Boosting Chart-to-Code Generation in MLLM via Dual Preference-Guided Refinement**](https://arxiv.org/abs/2504.02906) *Zhihan Zhang, Yixin Cao, Lizi Liao.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/Zhihan72/Chart2Code)

29. [**Breaking the SFT Plateau: Multimodal Structured Reinforcement Learning for Chart-to-Code Generation**](https://arxiv.org/abs/2508.13587) *Lei Chen, Xuanle Zhao, Zhixiong Zeng, Jing Huang, Liming Zheng, Yufeng Zhong, Lin Ma.* 🏛️ (ICLR 2026). &nbsp;&nbsp; [GitHub](https://github.com/DocTron-hub/MSRL)

30. [**ChartMaster: Advancing Chart-to-Code Generation with Real-World Charts and Chart Similarity Reinforcement Learning**](https://arxiv.org/abs/2508.17608) *Wentao Tan, Qiong Cao, Chao Xue, Yibing Zhan, Changxing Ding, Xiaodong He.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/WentaoTan/ChartMaster)

31. [**ChartReformer: Natural Language-Driven Chart Image Editing**](https://arxiv.org/abs/2403.00209) *Pengyu Yan, Mahesh Bhosale, Jay Lal, Bikhyat Adhikari, David Doermann.* 📄 (arXiv 2024).

32. [**Effective Training Data Synthesis for Improving MLLM Chart Understanding**](https://arxiv.org/abs/2508.06492) *Yuwei Yang, Zeyu Zhang, Yunzhong Hou, Zhuowan Li, Gaowen Liu, Ali Payani, Yuan-Sen Ting, Liang Zheng.* 🏛️ (ICCV 2025). &nbsp;&nbsp; [GitHub](https://github.com/yuweiyang-anu/ECD)

33. [**Chart-R1: Chain-of-Thought Supervision and Reinforcement for Advanced Chart Reasoner**](https://arxiv.org/abs/2507.15509) *Lei Chen, Xuanle Zhao, Zhixiong Zeng, Jing Huang, Yufeng Zhong, Lin Ma.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/DocTron-hub/Chart-R1)

34. [**ChartReasoner: Code-Driven Modality Bridging for Long-Chain Reasoning in Chart Question Answering**](https://arxiv.org/abs/2506.10116) *Caijun Jia, Nan Xu, Jingxuan Wei, Qingli Wang, Lei Wang, Bihui Yu, Junnan Zhu.* 📄 (arXiv 2025).

35. [**From Words to Structured Visuals: A Benchmark and Framework for Text-to-Diagram Generation and Editing**](https://arxiv.org/abs/2411.11916) *Jingxuan Wei, Cheng Tan, Qi Chen, Gaowei Wu, Siyuan Li, Zhangyang Gao, Linzhuang Sun, Bihui Yu, Ruifeng Guo.* 📄 (arXiv 2024). &nbsp;&nbsp; [GitHub](https://github.com/DiagramAgent/DiagramAgent_official)

36. [**Is GPT-4V (ision) All You Need for Automating Academic Data Visualization? Exploring Vision-Language Models’ Capability in Reproducing Academic Charts**](https://aclanthology.org/2024.findings-emnlp.485/) *Zhehao Zhang, Weicheng Ma, Soroush Vosoughi.* 🏛️ (EMNLP 2024 Findings). &nbsp;&nbsp; [GitHub](https://github.com/zzh-SJTU/AcademiaChart)

37. [**Chain of Functions: A Programmatic Pipeline for Fine-Grained Chart Reasoning Data**](https://arxiv.org/abs/2503.16260) *Zijian Li, Jingjing Fu, Lei Song, Jiang Bian, Jun Zhang, Rui Wang.* 📄 (arXiv 2025).

38. [**Draw with Thought: Unleashing Multimodal Reasoning for Scientific Diagram Generation**](https://arxiv.org/abs/2504.09479) *Zhiqing Cui, Jiahao Yuan, Hanqing Wang, Yanshu Li, Chenxu Du, Zhenglong Ding.* 📄 (arXiv 2025).

39. [**ChartMuseum: Testing Visual Reasoning Capabilities of Large Vision-Language Models**](https://arxiv.org/abs/2505.13444) *Liyan Tang, Grace Kim, Xinyu Zhao, Thom Lake, Wenxuan Ding, Fangcong Yin, Prasann Singhal, Manya Wadhwa, Zeyu Leo Liu, Zayne Sprague, Ramya Namuduri, Bodun Hu, Juan Diego Rodriguez, Puyuan Peng, Greg Durrett.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/Liyan06/ChartMuseum)

40. [**ChartCards: A Chart-Metadata Generation Framework for Multi-Task Chart Understanding**](https://arxiv.org/abs/2505.15046) *Yifan Wu, Lutao Yan, Leixian Shen, Yinan Mei, Jiannan Wang, Yuyu Luo.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/Evanwu1125/ChartCards)

41. [**Multimodal DeepResearcher: Generating Text-Chart Interleaved Reports From Scratch with Agentic Framework**](https://arxiv.org/abs/2506.02454) *Zhaorui Yang, Bo Pan, Han Wang, Yiyao Wang, Xingyu Liu, Luoxuan Weng, Yingchaojie Feng, Haozhe Feng, Minfeng Zhu, Bo Zhang, Wei Chen.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/rickyang1114/multimodal-deepresearcher)

42. [**Generating Pedagogically Meaningful Visuals for Math Word Problems: A New Benchmark and Analysis of Text-to-Image Models**](https://arxiv.org/abs/2506.03735) *Junling Wang, Anna Rutkiewicz, April Yi Wang, Mrinmaya Sachan.* 🏛️ (ACL 2025 Findings). &nbsp;&nbsp; [GitHub](https://github.com/eth-lre/math2visual)

43. [**OpusAnimation: Code-Based Dynamic Chart Generation**](https://arxiv.org/abs/2510.03341) *Bozheng Li, Miao Yang, Zhenhan Chen, Jiawang Cao, Mushui Liu, Yi Lu, Yongliang Wu, Bin Zhang, Yangguang Ji, Licheng Tang, Jay Wu, Wenbo Zhu.* 📄 (arXiv 2025).

44. [**InteractScience: Programmatic and Visually-Grounded Evaluation of Interactive Scientific Demonstration Code Generation**](https://arxiv.org/abs/2510.09724) *Qiaosheng Chen, Yang Liu, Lei Li, Kai Chen, Qipeng Guo, Gong Cheng, Fei Yuan.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/open-compass/InteractScience)

45. [**ChartEditBench: Evaluating Grounded Multi-Turn Chart Editing in Multimodal Language Models**](https://arxiv.org/abs/2602.15758) *Manav Nitin Kapadnis, Lawanya Baghel, Atharva Naik, Carolyn Rosé.* 📄 (arXiv 2026).

46. [**MM-ReCoder: Advancing Chart-to-Code Generation with Reinforcement Learning and Self-Correction**](https://arxiv.org/abs/2604.01600) *Zitian Tang, Xu Zhang, Jianbo Yuan, Yang Zou, Varad Gunjal, Songyao Jiang, Davide Modolo.* 🏛️ (CVPR 2026). &nbsp;&nbsp; [GitHub](https://github.com/ZitianTang/MM-ReCoder)

### 2.2 Structured Document

1. [**OmniDocBench: Benchmarking Diverse PDF Document Parsing with Comprehensive Annotations**](https://arxiv.org/abs/2412.07626) *Linke Ouyang, Yuan Qu, Hongbin Zhou, Jiawei Zhu, Rui Zhang, Qunshu Lin, Bin Wang, Zhiyuan Zhao, Man Jiang, Xiaomeng Zhao, Jin Shi, Fan Wu, Pei Chu, Minghao Liu, Zhenxiang Li, Chao Xu, Bo Zhang, Botian Shi, Zhongying Tu, Conghui He.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/opendatalab/OmniDocBench)

2. [**olmOCR: Unlocking Trillions of Tokens in PDFs with Vision Language Models**](https://arxiv.org/abs/2502.18443) *Jake Poznanski, Aman Rangapur, Jon Borchardt, Jason Dunkelberger, Regan Huff, Daniel Lin, Aman Rangapur, Christopher Wilhelm, Kyle Lo, Luca Soldaini.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/allenai/olmocr)

3. [**READoc: A Unified Benchmark for Realistic Document Structured Extraction**](https://arxiv.org/abs/2409.05137) *Zichao Li, Aizier Abulaiti, Yaojie Lu, Xuanang Chen, Jia Zheng, Hongyu Lin, Xianpei Han, Le Sun.* 🏛️ (ACL 2025 Findings).

4. [**Image-based table recognition: data, model, and evaluation**](https://arxiv.org/abs/1911.10683) *Xu Zhong, Elaheh ShafieiBavani, Antonio Jimeno Yepes.* 📄 (arXiv 2020).

5. [**Global Table Extractor (GTE): A Framework for Joint Table Identification and Cell Structure Recognition Using Visual Context**](https://arxiv.org/abs/2005.00589) *Xinyi Zheng, Doug Burdick, Lucian Popa, Xu Zhong, Nancy Xin Ru Wang.* 📄 (arXiv 2021).

6. [**UniMERNet: A Universal Network for Real-World Mathematical Expression Recognition**](https://arxiv.org/abs/2404.15254) *Bin Wang, Zhuangcheng Gu, Guang Liang, Chao Xu, Bo Zhang, Botian Shi, Conghui He.* 📄 (arXiv 2024). &nbsp;&nbsp; [GitHub](https://github.com/opendatalab/UniMERNet)

7. [**DocTron-Formula: Generalized Formula Recognition in Complex and Structured Scenarios**](https://arxiv.org/abs/2508.00311) *Yufeng Zhong, Zhixiong Zeng, Lei Chen, Longrong Yang, Liming Zheng, Jing Huang, Siqi Yang, Lin Ma.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/DocTron-hub/DocTron-Formula)

8. [**OCRBench v2: An Improved Benchmark for Evaluating Large Multimodal Models on Visual Text Localization and Reasoning**](https://arxiv.org/abs/2501.00321) *Ling Fu, Zhebin Kuang, Jiajun Song, Mingxin Huang, Biao Yang, Yuzhe Li, Linghao Zhu, Qidi Luo, Xinyu Wang, Hao Lu, Zhang Li, Guozhi Tang, Bin Shan, Chunhui Lin, Qi Liu, Binghong Wu, Hao Feng, Hao Liu, Can Huang, Jingqun Tang, Wei Chen, Lianwen Jin, Yuliang Liu, Xiang Bai.* 📄 (arXiv 2025).

9. [**KITAB-Bench: A Comprehensive Multi-Domain Benchmark for Arabic OCR and Document Understanding**](https://arxiv.org/abs/2502.14949) *Ahmed Heakl, Abdullah Sohail, Mukul Ranjan, Rania Hossam, Ghazi Shazan Ahmad, Mohamed El-Geish, Omar Maher, Zhiqiang Shen, Fahad Khan, Salman Khan.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/mbzuai-oryx/KITAB-Bench)

10. [**Ocean-OCR: Towards General OCR Application via a Vision-Language Model**](https://arxiv.org/abs/2501.15558) *Song Chen, Xinyu Guo, Yadong Li, Tao Zhang, Mingan Lin, Dongdong Kuang, Youwei Zhang, Lingfeng Ming, Fengyu Zhang, Yuran Wang, Jianhua Xu, Zenan Zhou, Weipeng Chen.* 📄 (arXiv 2025).

11. [**LATTE: Improving Latex Recognition for Tables and Formulae with Iterative Refinement**](https://arxiv.org/abs/2409.14201) *Nan Jiang, Shanchao Liang, Chengxiao Wang, Jiannan Wang, Lin Tan.* 🏛️ (AAAI 2025). &nbsp;&nbsp; [GitHub](https://github.com/lt-asset/Latte)

12. [**MinerU: An Open-Source Solution for Precise Document Content Extraction**](https://arxiv.org/abs/2409.18839) *Bin Wang, Chao Xu, Xiaomeng Zhao, Linke Ouyang, Fan Wu, Zhiyuan Zhao, Rui Xu, Kaiwen Liu, Yuan Qu, Fukai Shang, Bo Zhang, Liqun Wei, Zhihao Sui, Wei Li, Botian Shi, Yu Qiao, Dahua Lin, Conghui He.* 📄 (arXiv 2024). &nbsp;&nbsp; [GitHub](https://github.com/opendatalab/MinerU)

13. [**PaddleOCR 3.0 Technical Report**](https://arxiv.org/abs/2507.05595) *Cheng Cui, Ting Sun, Manhui Lin, Tingquan Gao, Yubo Zhang, Jiaxuan Liu, Xueqing Wang, Zelun Zhang, Changda Zhou, Hongen Liu, Yue Zhang, Wenyu Lv, Kui Huang, Yichao Zhang, Jing Zhang, Jun Zhang, Yi Liu, Dianhai Yu, Yanjun Ma.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/PaddlePaddle/PaddleOCR)

14. [**Marker: Fast and Accurate PDF to Markdown Converter**](https://github.com/datalab-to/marker) *Vik Paruchuri.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/datalab-to/marker)

15. [**PDF-Extract-Kit**](https://github.com/opendatalab/PDF-Extract-Kit) *Bin Wang, Chao Xu, Xiaomeng Zhao, Linke Ouyang, Fan Wu, Zhiyuan Zhao, Rui Xu, Kaiwen Liu, Yuan Qu, Fukai Shang, Bo Zhang, Liqun Wei, Zhihao Sui, Wei Li, Botian Shi, Yu Qiao, Dahua Lin, Conghui He.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/opendatalab/PDF-Extract-Kit)

16. [**Dolphin: Document Image Parsing via Heterogeneous Anchor Prompting**](https://arxiv.org/abs/2505.14059) *Hao Feng, Shu Wei, Xiang Fei, Wei Shi, Yingdong Han, Lei Liao, Jinghui Lu, Binghong Wu, Qi Liu, Chunhui Lin, Jingqun Tang, Hao Liu, Can Huang.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/bytedance/Dolphin)

17. [**MonkeyOCR: Document Parsing with a Structure-Recognition-Relation Triplet Paradigm**](https://arxiv.org/abs/2506.05218) *Zhang Li, Yuliang Liu, Qiang Liu, Zhiyin Ma, Ziyang Zhang, Shuo Zhang, Biao Yang, Zidun Guo, Jiarui Zhang, Xinyu Wang, Xiang Bai.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/Yuliang-Liu/MonkeyOCR)

18. [**PaddleOCR-VL: Boosting Multilingual Document Parsing via a 0.9B Ultra-Compact Vision-Language Model**](https://arxiv.org/abs/2510.14528) *Cheng Cui, Ting Sun, Suyin Liang, Tingquan Gao, Zelun Zhang, Jiaxuan Liu, Xueqing Wang, Changda Zhou, Hongen Liu, Manhui Lin, Yue Zhang, Yubo Zhang, Handong Zheng, Jing Zhang, Jun Zhang, Yi Liu, Dianhai Yu, Yanjun Ma.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/PaddlePaddle/PaddleOCR)

19. [**POINTS-Reader: Distillation-Free Adaptation of Vision-Language Models for Document Conversion**](https://arxiv.org/abs/2509.01215) *Yuan Liu, Zhongyin Zhao, Le Tian, Haicheng Wang, Xubing Ye, Yangxiu You, Zilin Yu, Chuhan Wu, Xiao Zhou, Yang Yu, Jie Zhou.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/Tencent/POINTS-Reader)

20. [**DeepSeek-OCR: Contexts Optical Compression**](https://arxiv.org/abs/2510.18234) *Haoran Wei, Yaofeng Sun, Yukun Li.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/deepseek-ai/DeepSeek-OCR)

21. [**dots.ocr: Multilingual Document Layout Parsing in a Single Vision-Language Model**](https://arxiv.org/abs/2512.02498) *Yumeng Li, Guang Yang, Hao Liu, Bowen Wang, Colin Zhang.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/rednote-hilab/dots.ocr)

22. [**Infinity Parser: Layout Aware Reinforcement Learning for Scanned Document Parsing**](https://arxiv.org/abs/2506.03197) *Baode Wang, Biao Wu, Weizhen Li, Meng Fang, Zuming Huang, Jun Huang, Haozhe Wang, Yanjie Liang, Ling Chen, Wei Chu, Yuan Qi.* 📄 (arXiv 2025).

23. [**Logics-Parsing Technical Report**](https://arxiv.org/abs/2509.19760) *Xiangyang Chen, Shuzhao Li, Xiuwen Zhu, Yongfan Chen, Fan Yang, Cheng Fang, Lin Qu, Xiaoxiao Xu, Hu Wei, Minggang Wu.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/alibaba/Logics-Parsing)

24. [**olmOCR 2: Unit Test Rewards for Document OCR**](https://arxiv.org/abs/2510.19817) *Jake Poznanski, Luca Soldaini, Kyle Lo.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/allenai/olmocr)

25. [**Reading or Reasoning? Format Decoupled Reinforcement Learning for Document OCR**](https://arxiv.org/abs/2601.08834) *Yufeng Zhong, Lei Chen, Zhixiong Zeng, Xuanle Zhao, Deyang Jiang, Liming Zheng, Jing Huang, Haibo Qiu, Peng Shi, Siqi Yang, Lin Ma.* 📄 (arXiv 2025).

26. [**TableFormer: Table Structure Understanding with Transformers**](https://arxiv.org/abs/2203.01017) *Ahmed Nassar, Nikolaos Livathinos, Maksym Lysak, Peter Staar.* 📄 (arXiv 2022).

27. [**UniTable: Towards a Unified Framework for Table Recognition via Self-Supervised Pretraining**](https://arxiv.org/abs/2403.04822) *ShengYun Peng, Aishwarya Chakravarthy, Seongmin Lee, Xiaojing Wang, Rajarajeswari Balasubramaniyan, Duen Horng Chau.* 📄 (arXiv 2024).

28. [**Latexnet: A specialized model for converting visual tables and equations to latex code**](https://doi.org/10.1109/icassp49660.2025.10887698) *Renqiu Xia, Hongbin Zhou, Ziming Feng, Huanxi Liu, Boan Chen, Bo Zhang, Junchi Yan.* 🏛️ (ICASSP 2025).

29. [**OmniCaptioner: One Captioner to Rule Them All**](https://arxiv.org/abs/2504.07089) *Yiting Lu, Jiakang Yuan, Zhen Li, Shitian Zhao, Qi Qin, Xinyue Li, Le Zhuo, Licheng Wen, Dongyang Liu, Yuewen Cao, Xiangchao Yan, Xin Li, Tianshuo Peng, Shufei Zhang, Botian Shi, Tao Chen, Zhibo Chen, Lei Bai, Peng Gao, Bo Zhang.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/InternScience/OmniCaptioner)

30. [**pix2tex - LaTeX OCR**](https://github.com/lukas-blecher/LaTeX-OCR) *Lukas Blecher.* 📄 (arXiv 2022). &nbsp;&nbsp; [GitHub](https://github.com/lukas-blecher/LaTeX-OCR)

31. [**Texify**](https://github.com/VikParuchuri/texify) *Vik Paruchuri.* 📄 (arXiv 2023). &nbsp;&nbsp; [GitHub](https://github.com/VikParuchuri/texify)

32. [**PosFormer: Recognizing Complex Handwritten Mathematical Expression with Position Forest Transformer**](https://arxiv.org/abs/2407.07764) *Tongkun Guan, Chengyu Lin, Wei Shen, Xiaokang Yang.* 📄 (arXiv 2024). &nbsp;&nbsp; [GitHub](https://github.com/SJTU-DeepVisionLab/PosFormer)

33. [**PP-FormulaNet: Bridging Accuracy and Efficiency in Advanced Formula Recognition**](https://arxiv.org/abs/2503.18382) *Hongen Liu, Cheng Cui, Yuning Du, Yi Liu, Gang Pan.* 📄 (arXiv 2025).

34. [**DocFusion: A Unified Framework for Document Parsing Tasks**](https://arxiv.org/abs/2412.12505) *Mingxu Chai, Ziyu Shen, Chong Zhang, Yue Zhang, Xiao Wang, Shihan Dou, Jihua Kang, Jiazheng Zhang, Qi Zhang.* 🏛️ (ACL 2025 Findings). &nbsp;&nbsp; [GitHub](https://github.com/SII-sc22mc/DocFusion)

35. [**BigDocs: An Open Dataset for Training Multimodal Models on Document and Code Tasks**](https://arxiv.org/abs/2412.04626) *Juan Rodriguez, Xiangru Jian, Siba Smarak Panigrahi, Tianyu Zhang, Aarash Feizi, Abhay Puri, Akshay Kalkunte, François Savard, Ahmed Masry, Shravan Nayak, Rabiul Awal, Mahsa Massoud, Amirhossein Abaskohi, Zichao Li, Suyuchen Wang, Pierre-André Noël, Mats Leon Richter, Saverio Vadacchino, Shubham Agarwal, Sanket Biswas, Sara Shanian, Ying Zhang, Noah Bolger, Kurt MacDonald, Simon Fauvel, Sathwik Tejaswi, Srinivas Sunkara, Joao Monteiro, Krishnamurthy DJ Dvijotham, Torsten Scholak, Nicolas Chapados, Sepideh Kharagani, Sean Hughes, M. Özsu, Siva Reddy, Marco Pedersoli, Yoshua Bengio, Christopher Pal, Issam Laradji, Spandana Gella, Perouz Taslakian, David Vazquez, Sai Rajeswar.* 🏛️ (ICLR 2025).

36. [**Multimodal DeepResearcher: Generating Text-Chart Interleaved Reports From Scratch with Agentic Framework**](https://arxiv.org/abs/2506.02454) *Zhaorui Yang, Bo Pan, Han Wang, Yiyao Wang, Xingyu Liu, Luoxuan Weng, Yingchaojie Feng, Haozhe Feng, Minfeng Zhu, Bo Zhang, Wei Chen.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/rickyang1114/multimodal-deepresearcher)

37. [**TableBank: A Benchmark Dataset for Table Detection and Recognition**](https://arxiv.org/abs/1903.01949) *Minghao Li, Lei Cui, Shaohan Huang, Furu Wei, Ming Zhou, Zhoujun Li.* 📄 (arXiv 2020). &nbsp;&nbsp; [GitHub](https://github.com/doc-analysis/TableBank)

### 2.3 Academic Presentations

1. [**AutoPresent: Designing Structured Visuals from Scratch**](https://arxiv.org/abs/2501.00912) *Jiaxin Ge, Zora Zhiruo Wang, Xuhui Zhou, Yi-Hao Peng, Sanjay Subramanian, Qinyue Tan, Maarten Sap, Alane Suhr, Daniel Fried, Graham Neubig, Trevor Darrell.* 🏛️ (CVPR 2025). &nbsp;&nbsp; [GitHub](https://github.com/para-lost/AutoPresent)

2. [**PPTAgent: Generating and Evaluating Presentations Beyond Text-to-Slides**](https://arxiv.org/abs/2501.03936) *Hao Zheng, Xinyan Guan, Hao Kong, Jia Zheng, Weixiang Zhou, Hongyu Lin, Yaojie Lu, Ben He, Xianpei Han, Le Sun.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/icip-cas/PPTAgent)

3. [**Talk to Your Slides: High-Efficiency Slide Editing via Language-Driven Structured Data Manipulation**](https://arxiv.org/abs/2505.11604) *Kyudan Jung, Hojun Cho, Jooyeol Yun, Soyoung Yang, Jaehyeok Jang, Jaegul Choo.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/KyuDan1/Talk-to-Your-Slides)

4. [**SlideCoder: Layout-aware RAG-enhanced Hierarchical Slide Generation from Design**](https://arxiv.org/abs/2506.07964) *Wenxin Tang, Jingyu Xiao, Wenxuan Jiang, Xi Xiao, Yuhang Wang, Xuxin Tang, Qing Li, Yuehe Ma, Junliang Liu, Shisong Tang, Michael R. Lyu.* 🏛️ (EMNLP 2025 Main). &nbsp;&nbsp; [GitHub](https://github.com/vinsontang1/SlideCoder)

5. [**PresentAgent: Multimodal Agent for Presentation Video Generation**](https://arxiv.org/abs/2507.04036) *Jingwei Shi, Zeyu Zhang, Biao Wu, Yanjie Liang, Meng Fang, Ling Chen, Yang Zhao.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/AIGeeksGroup/PresentAgent)

6. [**Paper2Poster: Towards Multimodal Poster Automation from Scientific Papers**](https://arxiv.org/abs/2505.21497) *Wei Pang, Kevin Qinghong Lin, Xiangru Jian, Xi He, Philip Torr.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/Paper2Poster/Paper2Poster)

7. [**P2P: Automated Paper-to-Poster Generation and Fine-Grained Benchmark**](https://arxiv.org/abs/2505.17104) *Tao Sun, Enhao Pan, Zhengkai Yang, Kaixin Sui, Jiajun Shi, Xianfu Cheng, Tongliang Li, Wenhao Huang, Ge Zhang, Jian Yang, Zhoujun Li.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/multimodal-art-projection/P2P)

8. [**PreGenie: An Agentic Framework for High-quality Visual Presentation Generation**](https://arxiv.org/abs/2505.21660) *Xiaojie Xu, Xinli Xu, Sirui Chen, Haoyu Chen, Fan Zhang, Ying-Cong Chen.* 📄 (arXiv 2025).

9. [**Presenting a Paper is an Art: Self-Improvement Aesthetic Agents for Academic Presentations**](https://arxiv.org/abs/2510.05571) *Chengzhi Liu, Yuzhe Yang, Kaiwen Zhou, Zhen Zhang, Yue Fan, Yanan Xie, Peng Qi, Xin Eric Wang.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/UCSB-AI/EvoPresent)

10. [**PosterGen: Aesthetic-Aware Multi-Modal Paper-to-Poster Generation via Multi-Agent LLMs**](https://arxiv.org/abs/2508.17188) *Zhilin Zhang, Xiang Zhang, Jiaqi Wei, Yiwei Xu, Chenyu You.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/Y-Research-SBU/PosterGen)

11. [**EfficientPosterGen: Semantic-aware Efficient Poster Generation via Token Compression and Accurate Violation Detection**](https://arxiv.org/abs/2603.00155) *Wenxin Tang, Jingyu Xiao, Yanpei Gong, Fengyuan Ran, Tongchuan Xia, Junliang Liu, Man Ho Lam, Wenxuan Wang, Michael R. Lyu.* 📄 (arXiv 2026). &nbsp;&nbsp; [GitHub](https://github.com/vinsontang1/EfficientPosterGen-Code)

12. [**Code2Video: A Code-centric Paradigm for Educational Video Generation**](https://arxiv.org/abs/2510.01174) *Yanzhe Chen, Kevin Qinghong Lin, Mike Zheng Shou.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/showlab/Code2Video)

13. [**Paper2Video: Automatic Video Generation from Scientific Papers**](https://arxiv.org/abs/2510.05096) *Zeyu Zhu, Kevin Qinghong Lin, Mike Zheng Shou.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/showlab/Paper2Video)

14. [**Paper2Web: Let's Make Your Paper Alive!**](https://arxiv.org/abs/2510.15842) *Yuhang Chen, Tianpeng Lv, Siyi Zhang, Yixiang Yin, Yao Wan, Philip S. Yu, Dongping Chen.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/YuhangChen1/Paper2All)

15. [**Human-Agent Collaborative Paper-to-Page Crafting for Under $0.1**](https://arxiv.org/abs/2510.19600) *Qianli Ma, Siyu Wang, Yilin Chen, Yinhao Tang, Yixiang Yang, Chang Guo, Bingjie Gao, Zhening Xing, Yanan Sun, Zhipeng Zhang.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/AutoLab-SAI-SJTU/AutoPage)

16. [**PPTBench: Towards Holistic Evaluation of Large Language Models for PowerPoint Layout and Design Understanding**](https://arxiv.org/abs/2512.02624) *Zheng Huang, Xukai Liu, Tianyu Hu, Kai Zhang, Ye Liu.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/Gastronomicluna/PPTBench-Eval)

17. [**SlideGen: Collaborative Multimodal Agents for Scientific Slide Generation**](https://arxiv.org/abs/2512.04529) *Xin Liang, Xiang Zhang, Yiwei Xu, Siqi Sun, Chenyu You.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/Y-Research-SBU/SlideGen)

18. [**SlideTailor: Personalized Presentation Slide Generation for Scientific Papers**](https://arxiv.org/abs/2512.20292) *Wenzheng Zeng, Mingyu Ouyang, Langyuan Cui, Hwee Tou Ng.* 🏛️ (AAAI 2026). &nbsp;&nbsp; [GitHub](https://github.com/nusnlp/SlideTailor)

### 2.4 Scientific Demonstration

1. [**ScienceAgentBench: Toward Rigorous Assessment of Language Agents for Data-Driven Scientific Discovery**](https://arxiv.org/abs/2410.05080) *Ziru Chen, Shijie Chen, Yuting Ning, Qianheng Zhang, Boshi Wang, Botao Yu, Yifei Li, Zeyi Liao, Chen Wei, Zitong Lu, Vishal Dey, Mingyi Xue, Frazier N. Baker, Benjamin Burns, Daniel Adu-Ampratwum, Xuhui Huang, Xia Ning, Song Gao, Yu Su, Huan Sun.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/OSU-NLP-Group/ScienceAgentBench)

2. [**ScienceBoard: Evaluating Multimodal Autonomous Agents in Realistic Scientific Workflows**](https://arxiv.org/abs/2505.19897) *Qiushi Sun, Zhoumianze Liu, Chang Ma, Zichen Ding, Fangzhi Xu, Zhangyue Yin, Haiteng Zhao, Zhenyu Wu, Kanzhi Cheng, Zhaoyang Liu, Jianing Wang, Qintong Li, Xiangru Tang, Tianbao Xie, Xiachong Feng, Xiang Li, Ben Kao, Wenhai Wang, Biqing Qi, Lingpeng Kong, Zhiyong Wu.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/OS-Copilot/ScienceBoard)

3. [**From EduVisBench to EduVisAgent: A Benchmark and Multi-Agent Framework for Reasoning-Driven Pedagogical Visualization**](https://arxiv.org/abs/2505.16832) *Haonian Ji, Shi Qiu, Siyang Xin, Siwei Han, Zhaorun Chen, Dake Zhang, Hongyi Wang, Huaxiu Yao.* 🏛️ (NeurIPS 2025).

4. [**TheoremExplainAgent: Towards Video-based Multimodal Explanations for LLM Theorem Understanding**](https://aclanthology.org/2025.acl-long.332/) *Max Ku, Cheuk Hei Chong, Jonathan Leung, Krish Shah, Alvin Yu, Wenhu Chen.* 🏛️ (ACL 2025). &nbsp;&nbsp; [GitHub](https://github.com/TIGER-AI-Lab/TheoremExplainAgent)

5. [**Toward Automated and Trustworthy Scientific Analysis and Visualization with LLM-Generated Code**](https://arxiv.org/abs/2511.21920) *Apu Kumar Chakroborti, Yi Ding, Lipeng Wan.* 📄 (arXiv 2025).

6. [**Scaling Text-Rich Image Understanding via Code-Guided Synthetic Multimodal Data Generation**](https://arxiv.org/abs/2502.14846) *Yue Yang, Ajay Patel, Matt Deitke, Tanmay Gupta, Luca Weihs, Andrew Head, Mark Yatskar, Chris Callison-Burch, Ranjay Krishna, Aniruddha Kembhavi, Christopher Clark.* 🏛️ (ACL 2025).

7. [**TinyChemVL: Advancing Chemical Vision-Language Models via Efficient Visual Token Reduction and Complex Reaction Tasks**](https://arxiv.org/abs/2511.06283) *Xuanle Zhao, Shuxin Zeng, Xinyuan Cai, Xiang Cheng, Duzhen Zhang, Xiuyi Chen, Bo Xu.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/xxlllz/TinyChemVL)

8. [**AutomaTikZ: Text-Guided Synthesis of Scientific Vector Graphics with TikZ**](https://arxiv.org/abs/2310.00367) *Jonas Belouadi, Anne Lauscher, Steffen Eger.* 📄 (arXiv 2023).

## 3. Structured Graphics

<p align="center">
  <img src="assets/figures/structured_graphics.png" alt="Structured graphics generation tasks" width="90%">
</p>

### 3.1 Scalable Vector Graphics (SVG)

1. [**IconShop: Text-Guided Vector Icon Synthesis with Autoregressive Transformers**](https://arxiv.org/abs/2304.14400) *Ronghuan Wu, Wanchao Su, Kede Ma, Jing Liao.* 📄 (arXiv 2023).

2. [**SVGFusion: A VAE-Diffusion Transformer for Vector Graphic Generation**](https://arxiv.org/abs/2412.10437) *Ximing Xing, Juncheng Hu, Ziteng Xue, Jing Zhang, Buyu Li, Sheng Wang, Dong Xu, Qian Yu.* 📄 (arXiv 2024). &nbsp;&nbsp; [GitHub](https://github.com/ximinng/SVGFusion)

3. [**Empowering LLMs to Understand and Generate Complex Vector Graphics**](https://arxiv.org/abs/2412.11102) *Ximing Xing, Juncheng Hu, Guotao Liang, Jing Zhang, Dong Xu, Qian Yu.* 🏛️ (CVPR 2025). &nbsp;&nbsp; [GitHub](https://github.com/ximinng/LLM4SVG)

4. [**VGBench: Evaluating Large Language Models on Vector Graphics Understanding and Generation**](https://arxiv.org/abs/2407.10972) *Bocheng Zou, Mu Cai, Jianrui Zhang, Yong Jae Lee.* 📄 (arXiv 2024).

5. [**Reason-SVG: Enhancing Structured Reasoning for Vector Graphics Generation with Reinforcement Learning**](https://arxiv.org/abs/2505.24499) *Ximing Xing, Ziteng Xue, Yandong Guan, Jing Zhang, Dong Xu, Qian Yu.* 🏛️ (CVPR 2026).

6. [**UniSVG: A Unified Dataset for Vector Graphic Understanding and Generation with Multimodal Large Language Models**](https://arxiv.org/abs/2508.07766) *Jinke Li, Jiarui Yu, Chenxing Wei, Hande Dong, Qiang Lin, Liangjing Yang, Zhicai Wang, Yanbin Hao.* 📄 (arXiv 2025).

7. [**SVGenius: Benchmarking LLMs in SVG Understanding, Editing and Generation**](https://arxiv.org/abs/2506.03139) *Siqi Chen, Xinyu Dong, Haolei Xu, Xingyu Wu, Fei Tang, Hang Zhang, Yuchen Yan, Linjuan Wu, Wenqi Zhang, Guiyang Hou, Yongliang Shen, Weiming Lu, Yueting Zhuang.* 🏛️ (MM 2025). &nbsp;&nbsp; [GitHub](https://github.com/ZJU-REAL/SVGenius)

8. [**DeepSVG: A Hierarchical Generative Network for Vector Graphics Animation**](https://arxiv.org/abs/2007.11301) *Alexandre Carlier, Martin Danelljan, Alexandre Alahi, Radu Timofte.* 📄 (arXiv 2020). &nbsp;&nbsp; [GitHub](https://github.com/alexandre01/deepsvg)

9. [**StarVector: Generating Scalable Vector Graphics Code from Images and Text**](https://arxiv.org/abs/2312.11556) *Juan A. Rodriguez, Abhay Puri, Shubham Agarwal, Issam H. Laradji, Pau Rodriguez, Sai Rajeswar, David Vazquez, Christopher Pal, Marco Pedersoli.* 🏛️ (CVPR 2025).

10. [**OmniSVG: A Unified Scalable Vector Graphics Generation Model**](https://arxiv.org/abs/2504.06263) *Yiying Yang, Wei Cheng, Sijin Chen, Xianfang Zeng, Fukun Yin, Jiaxu Zhang, Liao Wang, Gang Yu, Xingjun Ma, Yu-Gang Jiang.* 🏛️ (NeurIPS 2025). &nbsp;&nbsp; [GitHub](https://github.com/OmniSVG/OmniSVG)

11. [**Rendering-Aware Reinforcement Learning for Vector Graphics Generation**](https://arxiv.org/abs/2505.20793) *Juan A. Rodriguez, Haotian Zhang, Abhay Puri, Aarash Feizi, Rishav Pramanik, Pascal Wichmann, Arnab Mondal, Mohammad Reza Samsami, Rabiul Awal, Perouz Taslakian, Spandana Gella, Sai Rajeswar, David Vazquez, Christopher Pal, Marco Pedersoli.* 📄 (arXiv 2025).

12. [**VCode: a Multimodal Coding Benchmark with SVG as Symbolic Visual Representation**](https://arxiv.org/abs/2511.02778) *Kevin Qinghong Lin, Yuhao Zheng, Hangyu Ran, Dantong Zhu, Dongxing Mao, Linjie Li, Philip Torr, Alex Jinpeng Wang.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/CSU-JPG/VCode)

13. [**RoboSVG: A Unified Framework for Interactive SVG Generation with Multi-modal Guidance**](https://arxiv.org/abs/2510.22684) *Jiuniu Wang, Gongjie Zhang, Quanhao Qian, Junlong Gao, Deli Zhao, Ran Xu.* 📄 (arXiv 2025).

14. [**Differentiable vector graphics rasterization for editing and learning**](https://people.csail.mit.edu/tzumao/diffvg/) *Tzu-Mao Li, Michal Luk\'ac, Micha\"el Gharbi, Jonathan Ragan-Kelley.* 🏛️ (TOG 2020).

15. [**Towards Layer-wise Image Vectorization**](https://arxiv.org/abs/2206.04655) *Xu Ma, Yuqian Zhou, Xingqian Xu, Bin Sun, Valerii Filev, Nikita Orlov, Yun Fu, Humphrey Shi.* 📄 (arXiv 2022).

16. [**VectorFusion: Text-to-SVG by Abstracting Pixel-Based Diffusion Models**](https://arxiv.org/abs/2211.11319) *Ajay Jain, Amber Xie, Pieter Abbeel.* 📄 (arXiv 2023).

17. [**SVGDreamer: Text Guided SVG Generation with Diffusion Model**](https://arxiv.org/abs/2312.16476) *Ximing Xing, Haitao Zhou, Chuang Wang, Jing Zhang, Dong Xu, Qian Yu.* 📄 (arXiv 2024). &nbsp;&nbsp; [GitHub](https://github.com/ximinng/SVGDreamer)

18. [**SAMVG: A Multi-stage Image Vectorization Model with the Segment-Anything Model**](https://arxiv.org/abs/2311.05276) *Haokun Zhu, Juang Ian Chong, Teng Hu, Ran Yi, Yu-Kun Lai, Paul L. Rosin.* 🏛️ (ICASSP 2024).

19. [**NeuralSVG: An Implicit Representation for Text-to-Vector Generation**](https://arxiv.org/abs/2501.03992) *Sagi Polaczek, Yuval Alaluf, Elad Richardson, Yael Vinker, Daniel Cohen-Or.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/SagiPolaczek/NeuralSVG)

20. [**Im2Vec: Synthesizing Vector Graphics without Vector Supervision**](https://arxiv.org/abs/2102.02798) *Pradyumna Reddy, Michael Gharbi, Michal Lukac, Niloy J. Mitra.* 📄 (arXiv 2021).

21. [**SuperSVG: Superpixel-based Scalable Vector Graphics Synthesis**](https://arxiv.org/abs/2406.09794) *Teng Hu, Ran Yi, Baihong Qian, Jiangning Zhang, Paul L. Rosin, Yu-Kun Lai.* 📄 (arXiv 2024).

22. [**SVGBuilder: Component-Based Colored SVG Generation with Text-Guided Autoregressive Transformers**](https://arxiv.org/abs/2412.10488) *Zehao Chen, Rong Pan.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/amcghm/ColorSVG-100K)

23. [**SVGThinker: Instruction-Aligned and Reasoning-Driven Text-to-SVG Generation**](https://arxiv.org/abs/2509.24299) *Hanqi Chen, Zhongyin Zhao, Ye Chen, Zhujin Liang, Bingbing Ni.* 📄 (arXiv 2025).

24. [**SVGen: Interpretable Vector Graphics Generation with Large Language Models**](https://arxiv.org/abs/2508.09168) *Feiyu Wang, Zhiyuan Zhao, Yuandong Liu, Da Zhang, Junyu Gao, Hao Sun, Xuelong Li.* 📄 (arXiv 2025).

25. [**Chat2SVG: Vector Graphics Generation with Large Language Models and Image Diffusion Models**](https://arxiv.org/abs/2411.16602) *Ronghuan Wu, Wanchao Su, Jing Liao.* 🏛️ (CVPR 2025). &nbsp;&nbsp; [GitHub](https://github.com/kingnobro/chat2svg)

26. [**LogoMotion: Visually-Grounded Code Synthesis for Creating and Editing Animation**](https://arxiv.org/abs/2405.07065) *Vivian Liu, Rubaiat Habib Kazi, Li-Yi Wei, Matthew Fisher, Timothy Langlois, Seth Walker, Lydia Chilton.* 🏛️ (CHI 2025).

27. [**SVGEditBench: A Benchmark Dataset for Quantitative Assessment of LLM's SVG Editing Capabilities**](https://arxiv.org/abs/2404.13710) *Kunato Nishina, Yusuke Matsui.* 🏛️ (CVPR 2024). &nbsp;&nbsp; [GitHub](https://github.com/mti-lab/SVGEditBench)

28. [**Can Large Language Models Understand Symbolic Graphics Programs?**](https://arxiv.org/abs/2408.08313) *Zeju Qiu, Weiyang Liu, Haiwen Feng, Zhen Liu, Tim Z. Xiao, Katherine M. Collins, Joshua B. Tenenbaum, Adrian Weller, Michael J. Black, Bernhard Schölkopf.* 🏛️ (ICLR 2025 Spotlight). &nbsp;&nbsp; [GitHub](https://github.com/sgp-bench/sgp-bench)

29. [**See it. Say it. Sorted: Agentic System for Compositional Diagram Generation**](https://arxiv.org/abs/2508.15222) *Hantao Zhang, Jingyang Liu, Ed Li.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/hantaoZhangrichard/see_it_say_it_sorted)

30. [**DuetSVG: Unified Multimodal SVG Generation with Internal Visual Guidance**](https://arxiv.org/abs/2512.10894) *Peiying Zhang, Nanxuan Zhao, Matthew Fisher, Yiran Xu, Jing Liao, Difan Liu.* 📄 (arXiv 2025).

31. [**Vector Prism: Animating Vector Graphics by Stratifying Semantic Structure**](https://arxiv.org/abs/2512.14336) *Jooyeol Yun, Jaegul Choo.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/YeolJ00/vector-prism)

32. [**Reliable Reasoning in SVG-LLMs via Multi-Task Multi-Reward Reinforcement Learning**](https://arxiv.org/abs/2603.16189) *Haomin Wang, Qi Wei, Qianli Ma, Shengyuan Ding, Jinhui Yin, Kai Chen, Hongjie Zhang.* 📄 (arXiv 2026). &nbsp;&nbsp; [GitHub](https://github.com/hmwang2002/CTRL-S)

### 3.2 Diagram

1. [**Code generation from flowcharts with texts: A benchmark dataset and an approach**](https://doi.org/10.18653/v1/2022.findings-emnlp.449) *Zejie Liu, Xiaoyu Hu, Deyu Zhou, Lin Li, Xu Zhang, Yanzheng Xiang.* 🏛️ (EMNLP 2022 Findings).

2. [**Flow2Code: Evaluating Large Language Models for Flowchart-based Code Generation Capability**](https://arxiv.org/abs/2506.02073) *Mengliang He, Jiayi Zeng, Yankai Jiang, Wei Zhang, Zeming Liu, Xiaoming Shi, Aimin Zhou.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/hml-github/Flow2Code)

3. [**StarFlow: Generating Structured Workflow Outputs From Sketch Images**](https://arxiv.org/abs/2503.21889) *Patrice Bechard, Chao Wang, Amirhossein Abaskohi, Juan Rodriguez, Christopher Pal, David Vazquez, Spandana Gella, Sai Rajeswar, Perouz Taslakian.* 📄 (arXiv 2025).

4. [**Unified Modeling Language Code Generation from Diagram Images Using Multimodal Large Language Models**](https://arxiv.org/abs/2503.12293) *Averi Bates, Ryan Vavricka, Shane Carleton, Ruosi Shao, Chongle Pan.* 📄 (arXiv 2025).

5. [**Natural language is not enough: Benchmarking multi-modal generative AI for Verilog generation**](https://arxiv.org/abs/2407.08473) *Kaiyan Chang, Zhirong Chen, Yunhao Zhou, Wenlong Zhu, kun wang, Haobo Xu, Cangyuan Li, Mengdi Wang, Shengwen Liang, Huawei Li, Yinhe Han, Ying Wang.* 📄 (arXiv 2024).

6. [**OmniDiagram: Advancing Unified Diagram Code Generation via Visual Interrogation Reward**](https://arxiv.org/abs/2604.05514) *Haoyue Yang, Xuanle Zhao, Xuexin Liu, Feibang Jiang, Yao Zhu.* 📄 (arXiv 2026). &nbsp;&nbsp; [GitHub](https://github.com/Haoyue-Yang/OmniDiagram)

7. [**FlowVQA: Mapping Multimodal Logic in Visual Question Answering with Flowcharts**](https://arxiv.org/abs/2406.19237) *Shubhankar Singh, Purvi Chaurasia, Yerram Varun, Pranshu Pandya, Vatsal Gupta, Vivek Gupta, Dan Roth.* 📄 (arXiv 2024). &nbsp;&nbsp; [GitHub](https://github.com/flowvqa/flowvqa)

8. [**From Image to UML: First Results of Image Based UML Diagram Generation Using LLMs**](https://arxiv.org/abs/2404.11376) *Aaron Conrardy, Jordi Cabot.* 🏛️ (LLM4MDE 2024).

### 3.3 Computer-Aided Design (CAD)

1. [**DeepCAD: A Deep Generative Network for Computer-Aided Design Models**](https://arxiv.org/abs/2105.09492) *Rundi Wu, Chang Xiao, Changxi Zheng.* 📄 (arXiv 2021). &nbsp;&nbsp; [GitHub](https://github.com/rundiwu/DeepCAD)

2. [**Fusion 360 Gallery: A Dataset and Environment for Programmatic CAD Construction from Human Design Sequences**](https://arxiv.org/abs/2010.02392) *Karl D. D. Willis, Yewen Pu, Jieliang Luo, Hang Chu, Tao Du, Joseph G. Lambourne, Armando Solar-Lezama, Wojciech Matusik.* 📄 (arXiv 2021).

3. [**Text2CAD: Generating Sequential CAD Models from Beginner-to-Expert Level Text Prompts**](https://arxiv.org/abs/2409.17106) *Mohammad Sadil Khan, Sankalp Sinha, Talha Uddin Sheikh, Didier Stricker, Sk Aziz Ali, Muhammad Zeshan Afzal.* 📄 (arXiv 2024). &nbsp;&nbsp; [GitHub](https://github.com/SadilKhan/Text2CAD)

4. [**CADTalk: An Algorithm and Benchmark for Semantic Commenting of CAD Programs**](https://arxiv.org/abs/2311.16703) *Haocheng Yuan, Jing Xu, Hao Pan, Adrien Bousseau, Niloy J. Mitra, Changjian Li.* 📄 (arXiv 2024).

5. [**CADReview: Automatically Reviewing CAD Programs with Error Detection and Correction**](https://arxiv.org/abs/2505.22304) *Jiali Chen, Xusen Hei, HongFei Liu, Yuancheng Wei, Zikun Deng, Jiayuan Xie, Yi Cai, Li Qing.* 🏛️ (ACL 2025 Main Oral). &nbsp;&nbsp; [GitHub](https://github.com/Gary-code/CADReview)

6. [**From Intent to Execution: Multimodal Chain-of-Thought Reinforcement Learning for Precise CAD Code Generation**](https://arxiv.org/abs/2508.10118) *Ke Niu, Haiyang Yu, Zhuofan Chen, Mengyang Zhao, Teng Fu, Bin Li, Xiangyang Xue.* 📄 (arXiv 2025).

7. [**CME-CAD: Heterogeneous Collaborative Multi-Expert Reinforcement Learning for CAD Code Generation**](https://arxiv.org/abs/2512.23333) *Ke Niu, Haiyang Yu, Zhuofan Chen, Zhengtao Yao, Weitao Jia, Xiaodong Ge, Jingqun Tang, Benlei Cui, Bin Li, Xiangyang Xue.* 📄 (arXiv 2025).

8. [**Cad translator: An effective drive for text to 3d parametric computer-aided design generative modeling**](https://openreview.net/forum?id=DN3722rnLd) *Xueyang Li, Yu Song, Yunzhong Lou, Xiangdong Zhou.* 🏛️ (ACM MM 2024).

9. [**CAD-Llama: Leveraging Large Language Models for Computer-Aided Design Parametric 3D Model Generation**](https://arxiv.org/abs/2505.04481) *Jiahao Li, Weijian Ma, Xueyang Li, Yunzhong Lou, Guichun Zhou, Xiangdong Zhou.* 📄 (arXiv 2025).

10. [**Query2CAD: Generating CAD models using natural language queries**](https://arxiv.org/abs/2406.00144) *Akshay Badagabettu, Sai Sravan Yarlagadda, Amir Barati Farimani.* 📄 (arXiv 2024). &nbsp;&nbsp; [GitHub](https://github.com/akshay140601/Query2CAD)

11. [**CAD-Coder: Text-to-CAD Generation with Chain-of-Thought and Geometric Reward**](https://arxiv.org/abs/2505.19713) *Yandong Guan, Xilin Wang, Ximing Xing, Jing Zhang, Dong Xu, Qian Yu.* 🏛️ (NeurIPS 2025). &nbsp;&nbsp; [GitHub](https://github.com/gudo7208/CAD-Coder)

12. [**CAD-Recode: Reverse Engineering CAD Code from Point Clouds**](https://arxiv.org/abs/2412.14042) *Danila Rukhovich, Elona Dupont, Dimitrios Mallis, Kseniya Cherenkova, Anis Kacem, Djamila Aouada.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/filaPro/cad-recode)

13. [**CAD-SIGNet: CAD Language Inference from Point Clouds using Layer-wise Sketch Instance Guided Attention**](https://arxiv.org/abs/2402.17678) *Mohammad Sadil Khan, Elona Dupont, Sk Aziz Ali, Kseniya Cherenkova, Anis Kacem, Djamila Aouada.* 📄 (arXiv 2024).

14. [**Img2CAD: Conditioned 3-D CAD Model Generation From Single Image With Structured Visual Geometry**](https://doi.org/10.1109/tii.2025.3584476) *Tianrun Chen, Chunan Yu, Yuanqi Hu, Jing Li, Tao Xu, Runlong Cao, Lanyun Zhu, Ying Zang, Yong Zhang, Zejian Li, Lingyun Sun.* 🏛️ (TII 2025).

15. [**CAD-MLLM: Unifying Multimodality-Conditioned CAD Generation With MLLM**](https://arxiv.org/abs/2411.04954) *Jingwei Xu, Chenyu Wang, Zibo Zhao, Wen Liu, Yi Ma, Shenghua Gao.* 📄 (arXiv 2024). &nbsp;&nbsp; [GitHub](https://github.com/CAD-MLLM/CAD-MLLM)

16. [**CAD-Assistant: Tool-Augmented VLLMs as Generic CAD Task Solvers**](https://arxiv.org/abs/2412.13810) *Dimitrios Mallis, Ahmet Serdar Karadeniz, Sebastian Cavada, Danila Rukhovich, Niki Foteinopoulou, Kseniya Cherenkova, Anis Kacem, Djamila Aouada.* 📄 (arXiv 2025).

17. [**ReCAD: Reinforcement Learning Enhanced Parametric CAD Model Generation with Vision-Language Models**](https://arxiv.org/abs/2512.06328) *Jiahao Li, Yusheng Luo, Yunzhong Lou, Xiangdong Zhou.* 📄 (arXiv 2025).

18. [**CAD-Judge: Toward Efficient Morphological Grading and Verification for Text-to-CAD Generation**](https://arxiv.org/abs/2508.04002) *Zheyuan Zhou, Jiayi Han, Liang Du, Naiyu Fang, Lemiao Qiu, Shuyou Zhang.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/zhouzheyuan/cad-judge)

19. [**ShapeCoder: Discovering Abstractions for Visual Programs from Unstructured Primitives**](https://arxiv.org/abs/2305.05661) *R. Kenny Jones, Paul Guerrero, Niloy J. Mitra, Daniel Ritchie.* 📄 (arXiv 2023). &nbsp;&nbsp; [GitHub](https://github.com/rkjones4/ShapeCoder)

20. [**Real2Code: Reconstruct Articulated Objects via Code Generation**](https://arxiv.org/abs/2406.08474) *Zhao Mandi, Yijia Weng, Dominik Bauer, Shuran Song.* 📄 (arXiv 2024). &nbsp;&nbsp; [GitHub](https://github.com/MandiZhao/real2code)

21. [**MeshCoder: LLM-Powered Structured Mesh Code Generation from Point Clouds**](https://arxiv.org/abs/2508.14879) *Bingquan Dai, Li Ray Luo, Qihong Tang, Jie Wang, Xinyu Lian, Hao Xu, Minghan Qin, Xudong Xu, Bo Dai, Haoqian Wang, Zhaoyang Lyu, Jiangmiao Pang.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/InternRobotics/MeshCoder)

22. [**mrCAD: Multimodal Refinement of Computer-aided Designs**](https://arxiv.org/abs/2504.20294) *William P. McCarthy, Saujas Vaduguru, Karl D. D. Willis, Justin Matejka, Judith E. Fan, Daniel Fried, Yewen Pu.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/AutodeskAILab/mrCAD)

23. [**DreamCoder: Growing generalizable, interpretable knowledge with wake-sleep Bayesian program learning**](https://arxiv.org/abs/2006.08381) *Kevin Ellis, Catherine Wong, Maxwell Nye, Mathias Sable-Meyer, Luc Cary, Lucas Morales, Luke Hewitt, Armando Solar-Lezama, Joshua B. Tenenbaum.* 📄 (arXiv 2021).

24. [**WorldCoder-Bench: Benchmarking Physically Grounded 3D World Synthesis**](https://arxiv.org/abs/2606.01869) *Shuo Lu, Yinuo Xu, Kecheng Yu, Siru Jiang, Yongcan Yu, Yubin Wang, Haitao Yang, Yuxiang Zhang, Bin Wang, Ran He, Jian Liang.* 📄 (arXiv 2026).

## 4. Frontier Tasks and Frameworks

<p align="center">
  <img src="assets/figures/frontier_tasks.png" alt="Frontier multimodal code tasks" width="90%">
</p>

### 4.1 Programmatic Visual Manipulation

1. [**MM-REACT: Prompting ChatGPT for Multimodal Reasoning and Action**](https://arxiv.org/abs/2303.11381) *Zhengyuan Yang, Linjie Li, Jianfeng Wang, Kevin Lin, Ehsan Azarnasab, Faisal Ahmed, Zicheng Liu, Ce Liu, Michael Zeng, Lijuan Wang.* 📄 (arXiv 2023).

2. [**VipAct: Visual-Perception Enhancement via Specialized VLM Agent Collaboration and Tool-use**](https://arxiv.org/abs/2410.16400) *Zhehao Zhang, Ryan Rossi, Tong Yu, Franck Dernoncourt, Ruiyi Zhang, Jiuxiang Gu, Sungchul Kim, Xiang Chen, Zichao Wang, Nedim Lipka.* 📄 (arXiv 2024).

3. [**HYDRA: A Hyper Agent for Dynamic Compositional Visual Reasoning**](https://arxiv.org/abs/2403.12884) *Fucai Ke, Zhixi Cai, Simindokht Jahangard, Weiqing Wang, Pari Delir Haghighi, Hamid Rezatofighi.* 📄 (arXiv 2024). &nbsp;&nbsp; [GitHub](https://github.com/ControlNet/HYDRA)

4. [**DoraemonGPT: Toward Understanding Dynamic Scenes with Large Language Models (Exemplified as A Video Agent)**](https://arxiv.org/abs/2401.08392) *Zongxin Yang, Guikun Chen, Xiaodi Li, Wenguan Wang, Yi Yang.* 📄 (arXiv 2024). &nbsp;&nbsp; [GitHub](https://github.com/z-x-yang/DoraemonGPT)

5. [**TraveLER: A Modular Multi-LMM Agent Framework for Video Question-Answering**](https://arxiv.org/abs/2404.01476) *Chuyi Shang, Amos You, Sanjay Subramanian, Trevor Darrell, Roei Herzig.* 📄 (arXiv 2024). &nbsp;&nbsp; [GitHub](https://github.com/traveler-framework/TraveLER)

6. [**MoReVQA: Exploring Modular Reasoning Models for Video Question Answering**](https://arxiv.org/abs/2404.06511) *Juhong Min, Shyamal Buch, Arsha Nagrani, Minsu Cho, Cordelia Schmid.* 📄 (arXiv 2024).

7. [**VideoAgent: A Memory-augmented Multimodal Agent for Video Understanding**](https://arxiv.org/abs/2403.11481) *Yue Fan, Xiaojian Ma, Rujie Wu, Yuntao Du, Jiaqi Li, Zhi Gao, Qing Li.* 📄 (arXiv 2024). &nbsp;&nbsp; [GitHub](https://github.com/YueFan1014/VideoAgent)

8. [**VideoAgent: Long-form Video Understanding with Large Language Model as Agent**](https://arxiv.org/abs/2403.10517) *Xiaohan Wang, Yuhui Zhang, Orr Zohar, Serena Yeung-Levy.* 📄 (arXiv 2024).

9. [**VTimeCoT: Thinking by Drawing for Video Temporal Grounding and Reasoning**](https://arxiv.org/abs/2510.14672) *Jinglei Zhang, Yuanfan Guo, Rolandos Alexandros Potamias, Jiankang Deng, Hang Xu, Chao Ma.* 📄 (arXiv 2025).

10. [**MLLM-Tool: A Multimodal Large Language Model For Tool Agent Learning**](https://arxiv.org/abs/2401.10727) *Chenyu Wang, Weixin Luo, Sixun Dong, Xiaohua Xuan, Zhengxin Li, Lin Ma, Shenghua Gao.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/Chenyu-Wang567/MLLM-Tool)

11. [**CogCoM: A Visual Language Model with Chain-of-Manipulations Reasoning**](https://arxiv.org/abs/2402.04236) *Ji Qi, Ming Ding, Weihan Wang, Yushi Bai, Qingsong Lv, Wenyi Hong, Bin Xu, Lei Hou, Juanzi Li, Yuxiao Dong, Jie Tang.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/zai-org/CogCoM)

12. [**Pixel Reasoner: Incentivizing Pixel-Space Reasoning with Curiosity-Driven Reinforcement Learning**](https://arxiv.org/abs/2505.15966) *Haozhe Wang, Alex Su, Weiming Ren, Fangzhen Lin, Wenhu Chen.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/TIGER-AI-Lab/Pixel-Reasoner)

13. [**Scaling Agentic Reinforcement Learning for Tool-Integrated Reasoning in VLMs**](https://arxiv.org/abs/2511.19773) *Meng Lu, Ran Xu, Yi Fang, Wenxuan Zhang, Yue Yu, Gaurav Srivastava, Yuchen Zhuang, Mohamed Elhoseiny, Charles Fleming, Carl Yang, Zhengzhong Tu, Yang Xie, Guanghua Xiao, Hanrui Wang, Di Jin, Wenqi Shi, Xuan Wang.* 📄 (arXiv 2025).

14. [**Visual Programming: Compositional visual reasoning without training**](https://arxiv.org/abs/2211.11559) *Tanmay Gupta, Aniruddha Kembhavi.* 📄 (arXiv 2023).

15. [**ViperGPT: Visual Inference via Python Execution for Reasoning**](https://arxiv.org/abs/2303.08128) *Dídac Surís, Sachit Menon, Carl Vondrick.* 📄 (arXiv 2023). &nbsp;&nbsp; [GitHub](https://github.com/cvlab-columbia/viper)

16. [**Modular Visual Question Answering via Code Generation**](https://arxiv.org/abs/2306.05392) *Sanjay Subramanian, Medhini Narasimhan, Kushal Khangaonkar, Kevin Yang, Arsha Nagrani, Cordelia Schmid, Andy Zeng, Trevor Darrell, Dan Klein.* 📄 (arXiv 2023).

17. [**Visual Program Distillation: Distilling Tools and Programmatic Reasoning into Vision-Language Models**](https://arxiv.org/abs/2312.03052) *Yushi Hu, Otilia Stretcu, Chun-Ta Lu, Krishnamurthy Viswanathan, Kenji Hata, Enming Luo, Ranjay Krishna, Ariel Fuxman.* 📄 (arXiv 2024).

18. [**Reinforcing Spatial Reasoning in Vision-Language Models with Interwoven Thinking and Visual Drawing**](https://arxiv.org/abs/2506.09965) *Junfei Wu, Jian Guan, Kaituo Feng, Qiang Liu, Shu Wu, Liang Wang, Wei Wu, Tieniu Tan.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/AntResearchNLP/ViLaSR)

19. [**PyVision: Agentic Vision with Dynamic Tooling**](https://arxiv.org/abs/2507.07998) *Shitian Zhao, Haoquan Zhang, Shaoheng Lin, Ming Li, Qilong Wu, Kaipeng Zhang, Chen Wei.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/agents-x-project/PyVision)

20. [**ReFocus: Visual Editing as a Chain of Thought for Structured Image Understanding**](https://arxiv.org/abs/2501.05452) *Xingyu Fu, Minqian Liu, Zhengyuan Yang, John Corring, Yijuan Lu, Jianwei Yang, Dan Roth, Dinei Florencio, Cha Zhang.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/zeyofu/ReFocus_Code)

21. [**Skywork-R1V4: Toward Agentic Multimodal Intelligence through Interleaved Thinking with Images and DeepResearch**](https://arxiv.org/abs/2512.02395) *Yifan Zhang, Liang Hu, Haofeng Sun, Peiyu Wang, Yichen Wei, Shukang Yin, Jiangbo Pei, Wei Shen, Peng Xia, Yi Peng, Tianyidan Xie, Eric Li, Yang Liu, Xuchen Song, Yahui Zhou.* 📄 (arXiv 2025).

22. [**Visual Agentic Reinforcement Fine-Tuning**](https://arxiv.org/abs/2505.14246) *Ziyu Liu, Yuhang Zang, Yushan Zou, Zijian Liang, Xiaoyi Dong, Yuhang Cao, Haodong Duan, Dahua Lin, Jiaqi Wang.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/Liuziyu77/Visual-RFT)

23. [**Thyme: Think Beyond Images**](https://arxiv.org/abs/2508.11630) *Yi-Fan Zhang, Xingyu Lu, Shukang Yin, Chaoyou Fu, Wei Chen, Xiao Hu, Bin Wen, Kaiyu Jiang, Changyi Liu, Tianke Zhang, Haonan Fan, Kaibing Chen, Jiankang Chen, Haojie Ding, Kaiyu Tang, Zhang Zhang, Liang Wang, Fan Yang, Tingting Gao, Guorui Zhou.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/yfzhang114/Thyme)

24. [**Thinking with Programming Vision: Towards a Unified View for Thinking with Images**](https://arxiv.org/abs/2512.03746) *Zirun Guo, Minjie Hong, Feng Zhang, Kai Jia, Tao Jin.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/ByteDance-BandAI/CodeVision)

25. [**CodeV: Code with Images for Faithful Visual Reasoning via Tool-Aware Policy Optimization**](https://arxiv.org/abs/2511.19661) *Xinhai Hou, Shaoyuan Xu, Manan Biyani, Moyan Li, Jia Liu, Todd C. Hollon, Bryan Wang.* 📄 (arXiv 2025).

26. [**DeepSketcher: Internalizing Visual Manipulation for Multimodal Reasoning**](https://arxiv.org/abs/2509.25866) *Chi Zhang, Haibo Qiu, Qiming Zhang, Zhixiong Zeng, Lin Ma, Jing Zhang.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/MiliLab/DeepSketcher)

27. [**CodePlot-CoT: Mathematical Visual Reasoning by Thinking with Code-Driven Images**](https://arxiv.org/abs/2510.11718) *Chengqi Duan, Kaiyue Sun, Rongyao Fang, Manyuan Zhang, Yan Feng, Ying Luo, Yufang Liu, Ke Wang, Peng Pei, Xunliang Cai, Hongsheng Li, Yi Ma, Xihui Liu.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/HKU-MMLab/Math-VR-CodePlot-CoT)

28. [**Geoint-R1: Formalizing Multimodal Geometric Reasoning with Dynamic Auxiliary Constructions**](https://arxiv.org/abs/2508.03173) *Jingxuan Wei, Caijun Jia, Qi Chen, Honghao He, Linzhuang Sun, Conghui He, Lijun Wu, Bihui Yu, Cheng Tan.* 📄 (arXiv 2025).

29. [**VCode: a Multimodal Coding Benchmark with SVG as Symbolic Visual Representation**](https://arxiv.org/abs/2511.02778) *Kevin Qinghong Lin, Yuhao Zheng, Hangyu Ran, Dantong Zhu, Dongxing Mao, Linjie Li, Philip Torr, Alex Jinpeng Wang.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/CSU-JPG/VCode)

### 4.2 Video Code Generation

1. [**Neural Program Synthesis from Diverse Demonstration Videos**](https://proceedings.mlr.press/v80/sun18a.html) *Shao-Hua Sun, Hyeonwoo Noh, Sriram Somasundaram, Joseph Lim.* 🏛️ (ICML 2018). &nbsp;&nbsp; [GitHub](https://github.com/shaohua0116/demo2program)

2. [**Robotic Programmer: Video Instructed Policy Code Generation for Robotic Manipulation**](https://arxiv.org/abs/2501.04268) *Senwei Xie, Hongyu Wang, Zhanqi Xiao, Ruiping Wang, Xilin Chen.* 📄 (arXiv 2025).

3. [**Theoremexplainagent: Towards video-based multimodal explanations for llm theorem understanding**](https://aclanthology.org/2025.acl-long.332/) *Max Ku, Cheuk Hei Chong, Jonathan Leung, Krish Shah, Alvin Yu, Wenhu Chen.* 🏛️ (ACL 2025). &nbsp;&nbsp; [GitHub](https://github.com/TIGER-AI-Lab/TheoremExplainAgent)

### 4.3 Embodied Control

1. [**VirtualHome: Simulating Household Activities via Programs**](https://arxiv.org/abs/1806.07011) *Xavier Puig, Kevin Ra, Marko Boben, Jiaman Li, Tingwu Wang, Sanja Fidler, Antonio Torralba.* 📄 (arXiv 2018). &nbsp;&nbsp; [GitHub](https://github.com/xavierpuigf/virtualhome)

2. [**Code as Policies: Language Model Programs for Embodied Control**](https://arxiv.org/abs/2209.07753) *Jacky Liang, Wenlong Huang, Fei Xia, Peng Xu, Karol Hausman, Brian Ichter, Pete Florence, Andy Zeng.* 📄 (arXiv 2022).

3. [**Octopus: Embodied Vision-Language Programmer from Environmental Feedback**](https://arxiv.org/abs/2310.08588) *Jingkang Yang, Yuhao Dong, Shuai Liu, Bo Li, Ziyue Wang, Chencheng Jiang, Haoran Tan, Jiamu Kang, Yuanhan Zhang, Kaiyang Zhou, Ziwei Liu.* 📄 (arXiv 2024).

4. [**See and Think: Embodied Agent in Virtual Environment**](https://arxiv.org/abs/2311.15209) *Zhonghan Zhao, Wenhao Chai, Xuan Wang, Li Boyi, Shengyu Hao, Shidong Cao, Tian Ye, Gaoang Wang.* 📄 (arXiv 2024). &nbsp;&nbsp; [GitHub](https://github.com/wenhaochai/STEVE)

5. [**ProgPrompt: Program Generation for Situated Robot Task Planning Using Large Language Models**](https://doi.org/10.1007/s10514-023-10135-3) *Ishika Singh, Valts Blukis, Arsalan Mousavian, Ankit Goyal, Danfei Xu, Jonathan Tremblay, Dieter Fox, Jesse Thomason, Animesh Garg.* 🏛️ (Autonomous Robots 2023). &nbsp;&nbsp; [GitHub](https://github.com/NVlabs/progprompt-vh)

6. [**RoboScript: Code Generation for Free-Form Manipulation Tasks across Real and Simulation**](https://arxiv.org/abs/2402.14623) *Junting Chen, Yao Mu, Qiaojun Yu, Tianming Wei, Silang Wu, Zhecheng Yuan, Zhixuan Liang, Chao Yang, Kaipeng Zhang, Wenqi Shao, Yu Qiao, Huazhe Xu, Mingyu Ding, Ping Luo.* 📄 (arXiv 2024).

7. [**Code as Reward: Empowering Reinforcement Learning with VLMs**](https://arxiv.org/abs/2402.04764) *David Venuto, Sami Nur Islam, Martin Klissarov, Doina Precup, Sherry Yang, Ankit Anand.* 📄 (arXiv 2024).

8. [**Is Imitation All You Need? Generalized Decision-Making with Dual-Phase Training**](https://arxiv.org/abs/2307.07909) *Yao Wei, Yanchao Sun, Ruijie Zheng, Sai Vemprala, Rogerio Bonatti, Shuhang Chen, Ratnesh Madaan, Zhongjie Ba, Ashish Kapoor, Shuang Ma.* 📄 (arXiv 2023).

9. [**RoboCodeX: Multimodal Code Generation for Robotic Behavior Synthesis**](https://arxiv.org/abs/2402.16117) *Yao Mu, Junting Chen, Qinglong Zhang, Shoufa Chen, Qiaojun Yu, Chongjian Ge, Runjian Chen, Zhixuan Liang, Mengkang Hu, Chaofan Tao, Peize Sun, Haibao Yu, Chao Yang, Wenqi Shao, Wenhai Wang, Jifeng Dai, Yu Qiao, Mingyu Ding, Ping Luo.* 📄 (arXiv 2024).

10. [**Robotic Programmer: Video Instructed Policy Code Generation for Robotic Manipulation**](https://arxiv.org/abs/2501.04268) *Senwei Xie, Hongyu Wang, Zhanqi Xiao, Ruiping Wang, Xilin Chen.* 📄 (arXiv 2025).

### 4.4 Visually Grounded Programming

1. [**MMCode: Benchmarking Multimodal Large Language Models for Code Generation with Visually Rich Programming Problems**](https://arxiv.org/abs/2404.09486) *Kaixin Li, Yuchen Tian, Qisheng Hu, Ziyang Luo, Zhiyong Huang, Jing Ma.* 📄 (arXiv 2024). &nbsp;&nbsp; [GitHub](https://github.com/likaixin2000/MMCode)

2. [**ScratchEval: Are GPT-4o Smarter than My Child? Evaluating Large Multimodal Models with Visual Programming Challenges**](https://arxiv.org/abs/2411.18932) *Rao Fu, Ziyang Luo, Hongzhan Lin, Zhen Ye, Jing Ma.* 📄 (arXiv 2024). &nbsp;&nbsp; [GitHub](https://github.com/HKBUNLP/ScratchEval)

3. [**TurtleBench: A Visual Programming Benchmark in Turtle Geometry**](https://arxiv.org/abs/2411.00264) *Sina Rismanchian, Yasaman Razeghi, Sameer Singh, Shayan Doroudi.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/sinaris76/TurtleBench)

4. [**Code-Vision: Evaluating Multimodal LLMs Logic Understanding and Code Generation Capabilities**](https://arxiv.org/abs/2502.11829) *Hanbin Wang, Xiaoxuan Zhou, Zhipeng Xu, Keyuan Cheng, Yuxin Zuo, Kai Tian, Jingwei Song, Junting Lu, Wenhui Hu, Xueyang Liu.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/wanghanbinpanda/CodeVision)

5. [**OmniGIRL: A Multilingual and Multimodal Benchmark for GitHub Issue Resolution**](https://arxiv.org/abs/2505.04606) *Lianghong Guo, Wei Tao, Runhan Jiang, Yanlin Wang, Jiachi Chen, Xilin Liu, Yuchi Ma, Mingzhi Mao, Hongyu Zhang, Zibin Zheng.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/DeepSoftwareAnalytics/OmniGIRL)

6. [**CodeV: Issue Resolving with Visual Data**](https://arxiv.org/abs/2412.17315) *Linhao Zhang, Daoguang Zan, Quanshun Yang, Zhirong Huang, Dong Chen, Bo Shen, Tianyu Liu, Yongshun Gong, Pengjie Huang, Xudong Lu, Guangtai Liang, Lizhen Cui, Qianxiang Wang.* 📄 (arXiv 2024). &nbsp;&nbsp; [GitHub](https://github.com/luolin101/CodeV)

7. [**SWE-bench Multimodal: Do AI Systems Generalize to Visual Software Domains?**](https://arxiv.org/abs/2410.03859) *John Yang, Carlos E. Jimenez, Alex L. Zhang, Kilian Lieret, Joyce Yang, Xindi Wu, Ori Press, Niklas Muennighoff, Gabriel Synnaeve, Karthik R. Narasimhan, Diyi Yang, Sida I. Wang, Ofir Press.* 🏛️ (ICLR 2025).

8. [**Seeing is Fixing: Cross-Modal Reasoning with Multimodal LLMs for Visual Software Issue Fixing**](https://arxiv.org/abs/2506.16136) *Kai Huang, Jian Zhang, Xiaofei Xie, Chunyang Chen.* 🏛️ (ASE 2025).

9. [**HumanEval-V: Benchmarking High-Level Visual Reasoning with Complex Diagrams in Coding Tasks**](https://arxiv.org/abs/2410.12381) *Fengji Zhang, Linquan Wu, Huiyu Bai, Guancheng Lin, Xiao Li, Xiao Yu, Yue Wang, Bei Chen, Jacky Keung.* 📄 (arXiv 2024). &nbsp;&nbsp; [GitHub](https://github.com/HumanEval-V/HumanEval-V-Benchmark)

10. [**DynEx: Dynamic Code Synthesis with Structured Design Exploration for Accelerated Exploratory Programming**](https://arxiv.org/abs/2410.00400) *Jenny Ma, Karthik Sreedhar, Vivian Liu, Pedro Alejandro Perez, Sitong Wang, Riya Sahni, Lydia B. Chilton.* 📄 (arXiv 2024).

11. [**MathCoder-VL: Bridging Vision and Code for Enhanced Multimodal Mathematical Reasoning**](https://arxiv.org/abs/2505.10557) *Ke Wang, Junting Pan, Linda Wei, Aojun Zhou, Weikang Shi, Zimu Lu, Han Xiao, Yunqiao Yang, Houxing Ren, Mingjie Zhan, Hongsheng Li.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/mathllm/MathCoder)

12. [**DesignRepair: Dual-Stream Design Guideline-Aware Frontend Repair with Large Language Models**](https://arxiv.org/abs/2411.01606) *Mingyue Yuan, Jieshan Chen, Zhenchang Xing, Aaron Quigley, Yuyu Luo, Tianqi Luo, Gelareh Mohammadi, Qinghua Lu, Liming Zhu.* 🏛️ (ICSE 2025). &nbsp;&nbsp; [GitHub](https://github.com/UGAIForge/DesignRepair)

13. [**SVRepair: Structured Visual Reasoning for Automated Program Repair**](https://arxiv.org/abs/2602.06090) *Xiaoxuan Tang, Jincheng Wang, Liwei Luo, Jingxuan Xu, Sheng Zhou, Dajun Chen, Wei Jiang, Yong Li.* 📄 (arXiv 2026). &nbsp;&nbsp; [GitHub](https://github.com/codefuse-ai/CodeFuse-SVR)

### 4.5 Unified Multimodal Code Generation

1. [**Image2Struct: Benchmarking Structure Extraction for Vision-Language Models**](https://arxiv.org/abs/2410.22456) *Josselin Somerville Roberts, Tony Lee, Chi Heem Wong, Michihiro Yasunaga, Yifan Mai, Percy Liang.* 🏛️ (NeurIPS 2024 Datasets and Benchmarks).

2. [**Scaling Text-Rich Image Understanding via Code-Guided Synthetic Multimodal Data Generation**](https://arxiv.org/abs/2502.14846) *Yue Yang, Ajay Patel, Matt Deitke, Tanmay Gupta, Luca Weihs, Andrew Head, Mark Yatskar, Chris Callison-Burch, Ranjay Krishna, Aniruddha Kembhavi, Christopher Clark.* 🏛️ (ACL 2025).

3. [**ArtifactsBench: Bridging the Visual-Interactive Gap in LLM Code Generation Evaluation**](https://arxiv.org/abs/2507.04952) *Chenchen Zhang, Yuhang Li, Can Xu, Jiaheng Liu, Ao Liu, Changzhi Zhou, Ken Deng, Dengpeng Wu, Guanhua Huang, Kejiao Li, Qi Yi, Ruibin Xiong, Shihui Hu, Yue Zhang, Yuhao Jiang, Zenan Xu, Yuanxing Zhang, Wiggin Zhou, Chayse Zhou, Fengzong Lian.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/Tencent-Hunyuan/ArtifactsBenchmark)

4. [**VisCodex: Unified Multimodal Code Generation via Merging Vision and Coding Models**](https://arxiv.org/abs/2508.09945) *Lingjie Jiang, Shaohan Huang, Xun Wu, Yixia Li, Dongdong Zhang, Furu Wei.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/JackLingjie/VisCodex)

5. [**VisCoder2: Building Multi-Language Visualization Coding Agents**](https://arxiv.org/abs/2510.23642) *Yuansheng Ni, Songcheng Cai, Xiangchao Chen, Jiarong Liang, Zhiheng Lyu, Jiaqi Deng, Kai Zou, Ping Nie, Fei Yuan, Xiang Yue, Wenhu Chen.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/TIGER-AI-Lab/VisCoder2)

6. [**General OCR Theory: Towards OCR-2.0 via a Unified End-to-end Model**](https://arxiv.org/abs/2409.01704) *Haoran Wei, Chenglong Liu, Jinyue Chen, Jia Wang, Lingyu Kong, Yanming Xu, Zheng Ge, Liang Zhao, Jianjian Sun, Yuang Peng, Chunrui Han, Xiangyu Zhang.* 📄 (arXiv 2024). &nbsp;&nbsp; [GitHub](https://github.com/Ucas-HaoranWei/GOT-OCR2.0)

7. [**JanusCoder: Towards a Foundational Visual-Programmatic Interface for Code Intelligence**](https://arxiv.org/abs/2510.23538) *Qiushi Sun, Jingyang Gong, Yang Liu, Qiaosheng Chen, Lei Li, Kai Chen, Qipeng Guo, Ben Kao, Fei Yuan.* 🏛️ (ICLR 2026). &nbsp;&nbsp; [GitHub](https://github.com/InternLM/JanusCoder)

8. [**VinciCoder: Unifying Multimodal Code Generation via Coarse-to-fine Visual Reinforcement Learning**](https://arxiv.org/abs/2511.00391) *Xuanle Zhao, Deyang Jiang, Zhixiong Zeng, Lei Chen, Haibo Qiu, Jing Huang, Yufeng Zhong, Liming Zheng, Yilin Cao, Lin Ma.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/DocTron-hub/VinciCoder)

9. [**OCRVerse: Towards Holistic OCR in End-to-End Vision-Language Models**](https://arxiv.org/abs/2601.21639) *Yufeng Zhong, Lei Chen, Xuanle Zhao, Wenkang Han, Liming Zheng, Jing Huang, Deyang Jiang, Yilin Cao, Lin Ma, Zhixiong Zeng.* 📄 (arXiv 2026). &nbsp;&nbsp; [GitHub](https://github.com/DocTron-hub/OCRVerse)

10. [**FullStack Bench: Evaluating LLMs as Full Stack Coders**](https://arxiv.org/abs/2412.00535) *Yao Cheng, Jianfeng Chen, Jie Chen, Li Chen, Liyu Chen, Wentao Chen, Zhengyu Chen, Shijie Geng, Aoyan Li, Bo Li, Bowen Li, Linyi Li, Boyi Liu, Jiaheng Liu, Kaibo Liu, Qi Liu, Shukai Liu, Siyao Liu, Tianyi Liu, Tingkai Liu, Yongfei Liu, Rui Long, Jing Mai, Guanghan Ning, Z. Y. Peng, Kai Shen, Jiahao Su, Jing Su, Tao Sun, Yifan Sun, Yunzhe Tao, Guoyin Wang, Siwei Wang, Xuwu Wang, Yite Wang, Zihan Wang, Jinxiang Xia, Liang Xiang, Xia Xiao, Yongsheng Xiao, Chenguang Xi, Shulin Xin, Jingjing Xu, Shikun Xu, Hongxia Yang, Jack Yang, Yingxiang Yang, Jianbo Yuan, Jun Zhang, Yufeng Zhang, Yuyu Zhang, Shen Zheng, He Zhu, Ming Zhu.* 📄 (arXiv 2024). &nbsp;&nbsp; [GitHub](https://github.com/bytedance/FullStackBench)

11. [**Empowering Agile-Based Generative Software Development through Human-AI Teamwork**](https://arxiv.org/abs/2407.15568) *Sai Zhang, Zhenchang Xing, Ronghui Guo, Fangzhou Xu, Lei Chen, Zhaoyuan Zhang, Xiaowang Zhang, Zhiyong Feng, Zhiqiang Zhuang.* 🏛️ (TOSEM 2024). &nbsp;&nbsp; [GitHub](https://github.com/UGAIForge/AgileGen)

12. [**Automated LaTeX Code Generation from Handwritten Math Expressions Using Vision Transformer**](https://arxiv.org/abs/2412.03853) *Jayaprakash Sundararaj, Akhil Vyas, Benjamin Gonzalez-Maldonado.* 📄 (arXiv 2024).

13. [**Multilingual Multimodal Software Developer for Code Generation**](https://arxiv.org/abs/2507.08719) *Linzheng Chai, Jian Yang, Shukai Liu, Wei Zhang, Liran Wang, Ke Jin, Tao Sun, Congnan Liu, Chenchen Zhang, Hualei Zhu, Jiaheng Liu, Xianjie Wu, Ge Zhang, Tianyu Liu, Zhoujun Li.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/MCEVAL/MMCoder)

14. [**Table2LaTeX-RL: High-Fidelity LaTeX Code Generation from Table Images via Reinforced Multimodal Language Models**](https://arxiv.org/abs/2509.17589) *Jun Ling, Yao Qi, Tao Huang, Shibo Zhou, Yanqin Huang, Jiang Yang, Ziqi Song, Ying Zhou, Yang Yang, Heng Tao Shen, Peng Wang.* 🏛️ (NeurIPS 2025). &nbsp;&nbsp; [GitHub](https://github.com/newLLing/Table2LaTeX-RL)

15. [**EmbodiedCoder: Parameterized Embodied Mobile Manipulation via Modern Coding Model**](https://arxiv.org/abs/2510.06207) *Zefu Lin, Rongxu Cui, Chen Hanning, Xiangyu Wang, Junjia Xu, Xiaojuan Jin, Chen Wenbo, Hui Zhou, Lue Fan, Wenling Li, Zhaoxiang Zhang.* 📄 (arXiv 2025).

16. [**Visual-ERM: Reward Modeling for Visual Equivalence**](https://arxiv.org/abs/2603.13224) *Ziyu Liu, Shengyuan Ding, Xinyu Fang, Xuanlang Dai, Penghui Yang, Jianze Liang, Jiaqi Wang, Kai Chen, Dahua Lin, Yuhang Zang.* 📄 (arXiv 2026). &nbsp;&nbsp; [GitHub](https://github.com/InternLM/Visual-ERM)

17. [**Vision2Code: A Multi-Domain Benchmark for Evaluating Image-to-Code Generation**](https://arxiv.org/abs/2605.11307) *Ajay Vikram Periasami, Junlin Wang, Bhuwan Dhingra.* 📄 (arXiv 2026). &nbsp;&nbsp; [GitHub](https://github.com/image2code/vision2code)

18. [**Self-Distillation Policy Optimization via Visual Feedback: Bridging Code and Visual Artifacts**](https://arxiv.org/abs/2606.10334) *Haoyu Dong.* 📄 (arXiv 2026).

19. [**V-GameGym: Visual Game Generation for Code Large Language Models**](https://arxiv.org/abs/2509.20136) *Wei Zhang, Jack Yang, Renshuai Tao, Lingzheng Chai, Shawn Guo, Jiajun Wu, Xiaoming Chen, Ganqu Cui, Ning Ding, Xander Xu, Hu Wei, Bowen Zhou.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/alibaba/SKYLENAGE-GameCodeGym)

20. [**90% Faster, 100% Code-Free: MLLM-Driven Zero-Code 3D Game Development**](https://arxiv.org/abs/2509.26161) *Runxin Yang, Yuxuan Wan, Shuqing Li, Michael R. Lyu.* 📄 (arXiv 2025). &nbsp;&nbsp; [GitHub](https://github.com/yxwan123/UniGen)

21. [**GameUIAgent: An LLM-Powered Framework for Automated Game UI Design with Structured Intermediate Representation**](https://arxiv.org/abs/2603.14724) *Wei Zeng, Fengwei An, Zhen Liu, Jian Zhao.* 📄 (arXiv 2026). &nbsp;&nbsp; [GitHub](https://github.com/zengwei-code/GameUIAgent)

22. [**OpenGame: Open Agentic Coding for Games**](https://arxiv.org/abs/2604.18394) *Yilei Jiang, Jinyuan Hu, Qianyin Xiao, Yaozhi Zheng, Ruize Ma, Kaituo Feng, Jiaming Han, Tianshuo Peng, Kaixuan Fan, Manyuan Zhang, Xiangyu Yue.* 📄 (arXiv 2026). &nbsp;&nbsp; [GitHub](https://github.com/leigest519/OpenGame)

23. [**PlayCoder: Making LLM-Generated GUI Code Playable**](https://arxiv.org/abs/2604.19742) *Zhiyuan Peng, Wei Tao, Xin Yin, Chenhao Ying, Yuan Luo, Yiwen Guo.* 📄 (arXiv 2026). &nbsp;&nbsp; [GitHub](https://github.com/Tencent/PlayCoder)

# 🔥Contributing
This is an active repository and your contributions are always welcome! Before you add papers/tools into the awesome list, please make sure that:
- First, think about which category the work should belong to.
- The paper or tools is related to Multimodal Large Language Models (MLLMs) for code generation.
- The paper should be inserted in the correct position in chronological order (publication/arxiv release time).
- The link to paper should be the arxiv page, not the pdf page if this is a paper posted on arxiv.
- If the paper is accpeted, please use the correct publication venue instead of arxiv.
