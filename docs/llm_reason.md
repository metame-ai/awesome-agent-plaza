# LLM Reasoning

- [LLM Reasoning](#llm-reasoning) 
	- [Survey](#survey)
	- [LLM Reasoning](#llm-reasoning-1)
	- [Reinforcement Learning](#reinforcement-learning)
	- [RLVR](#rlvr)
	- [Test Time Scaling](#test-time-scaling)
	- [Latent Reasoning](#latent-reasoning)
	- [Data](#data)
	- [Toolkits](#toolkits)
	- [Misc](#misc)


## Survey


## LLM Reasoning

- **Learning to Self-Verify Makes Language Models Better Reasoners**, `arXiv, 2602.07594`, [arxiv](https://arxiv.org/abs/2602.07594v1), [pdf](https://arxiv.org/pdf/2602.07594v1.pdf), cication: [**-1**](None) 

	 *Yuxin Chen, Yu Wang, Yi Zhang, ..., An Zhang, Tat-Seng Chua*
- **Weak-Driven Learning: How Weak Agents make Strong Agents Stronger**, `arXiv, 2602.08222`, [arxiv](https://arxiv.org/abs/2602.08222v1), [pdf](https://arxiv.org/pdf/2602.08222v1.pdf), cication: [**-1**](None) 

	 *Zehao Chen, Gongxun Li, Tianxiang Ai, ..., Deqing Wang, Yikun Ban*
- **Learning beyond Teacher: Generalized On-Policy Distillation with Reward Extrapolation**, `arXiv, 2602.12125`, [arxiv](https://arxiv.org/abs/2602.12125v1), [pdf](https://arxiv.org/pdf/2602.12125v1.pdf), cication: [**-1**](None) 

	 *Wenkai Yang, Weijie Liu, Ruobing Xie, ..., Saiyong Yang, Yankai Lin*
- **Can LLMs Predict Their Own Failures? Self-Awareness via Internal Circuits**, `arXiv, 2512.20578`, [arxiv](https://arxiv.org/abs/2512.20578v2), [pdf](https://arxiv.org/pdf/2512.20578v2.pdf), cication: [**-1**](None) 

	 *Amirhosein Ghasemabadi, Di Niu*
- [**PaCoRe**](https://github.com/stepfun-ai/PaCoRe) - stepfun-ai ![Star](https://img.shields.io/github/stars/stepfun-ai/PaCoRe.svg?style=social&label=Star) 

	 *Learning to Scale Test-Time Compute with Parallel Coordinated Reasoning*
- **P1: Mastering Physics Olympiads with Reinforcement Learning**, `arXiv, 2511.13612`, [arxiv](https://arxiv.org/abs/2511.13612v1), [pdf](https://arxiv.org/pdf/2511.13612v1.pdf), cication: [**-1**](None) 

	 *Jiacheng Chen, Qianjia Cheng, Fangchen Yu, ..., Peng Ye, Ganqu Cui*
- 🌟 **DeepSeekMath-V2: Towards Self-Verifiable Mathematical Reasoning**, `arXiv, 2511.22570`, [arxiv](https://arxiv.org/abs/2511.22570v1), [pdf](https://arxiv.org/pdf/2511.22570v1.pdf), cication: [**-1**](None) 

	 *Zhihong Shao, Yuxiang Luo, Chengda Lu, ..., Shirong Ma, Xiaokang Zhang*
- **Native Parallel Reasoner: Reasoning in Parallelism via Self-Distilled Reinforcement Learning**, `arXiv, 2512.07461`, [arxiv](https://arxiv.org/abs/2512.07461v2), [pdf](https://arxiv.org/pdf/2512.07461v2.pdf), cication: [**-1**](None) 

	 *Tong Wu, Yang Liu, Jun Bai, ..., Song-Chun Zhu, Zilong Zheng*
- **Bottom-up Policy Optimization: Your Language Model Policy Secretly Contains Internal Policies**, `arXiv, 2512.19673`, [arxiv](https://arxiv.org/abs/2512.19673v1), [pdf](https://arxiv.org/pdf/2512.19673v1.pdf), cication: [**-1**](None) 

	 *Yuqiao Tan, Minzheng Wang, Shizhu He, ..., Jun Zhao, Kang Liu*
- **When Reasoning Meets Its Laws**, `arXiv, 2512.17901`, [arxiv](https://arxiv.org/abs/2512.17901v1), [pdf](https://arxiv.org/pdf/2512.17901v1.pdf), cication: [**-1**](None) 

	 *Junyu Zhang, Yifan Sun, Tianang Leng, ..., Paul Pu Liang, Huan Zhang*
- **Natural Language Actor-Critic: Scalable Off-Policy Learning in Language Space**, `arXiv, 2512.04601`, [arxiv](https://arxiv.org/abs/2512.04601v1), [pdf](https://arxiv.org/pdf/2512.04601v1.pdf), cication: [**-1**](None) 

	 *Joey Hong, Kang Liu, Zhan Ling, ..., Jiecao Chen, Sergey Levine*
- 🌟 [**DeepSeek-Math-V2**](https://github.com/deepseek-ai/DeepSeek-Math-V2) - deepseek-ai ![Star](https://img.shields.io/github/stars/deepseek-ai/DeepSeek-Math-V2.svg?style=social&label=Star) 

	 *Towards Self-Verifiable Mathematical Reasoning*
  and Depth?**, `arXiv, 2510.08189`, [arxiv](http://arxiv.org/abs/2510.08189v2), [pdf](http://arxiv.org/pdf/2510.08189v2.pdf), cication: [**-1**](None) 

	 *Yi Lu, Jianing Wang, Linsen Guo, ..., Wei Wang, Xunliang Cai* · ([reasoning-horizon.github](https://reasoning-horizon.github.io/))
- **Reasoning with Sampling: Your Base Model is Smarter Than You Think**, `arXiv, 2510.14901`, [arxiv](http://arxiv.org/abs/2510.14901v1), [pdf](http://arxiv.org/pdf/2510.14901v1.pdf), cication: [**-1**](None) 

	 *Aayush Karan, Yilun Du*
- **QeRL: Beyond Efficiency -- Quantization-enhanced Reinforcement Learning 
  for LLMs**, `arXiv, 2510.11696`, [arxiv](http://arxiv.org/abs/2510.11696v1), [pdf](http://arxiv.org/pdf/2510.11696v1.pdf), cication: [**-1**](None) 

	 *Wei Huang, Yi Ge, Shuai Yang, ..., Song Han, Yukang Chen*

## Reinforcement Learning

- **Composition-RL: Compose Your Verifiable Prompts for Reinforcement Learning of Large Language Models**, `arXiv, 2602.12036`, [arxiv](https://arxiv.org/abs/2602.12036v1), [pdf](https://arxiv.org/pdf/2602.12036v1.pdf), cication: [**-1**](None) 

	 *Xin Xu, Clive Bai, Kai Yang, ..., Saiyong Yang, Can Yang*
- **iGRPO: Self-Feedback-Driven LLM Reasoning**, `arXiv, 2602.09000`, [arxiv](https://arxiv.org/abs/2602.09000v1), [pdf](https://arxiv.org/pdf/2602.09000v1.pdf), cication: [**-1**](None) 

	 *Ali Hatamizadeh, Shrimai Prabhumoye, Igor Gitman, ..., Yejin Choi, Jan Kautz*
- **Rewarding the Rare: Uniqueness-Aware RL for Creative Problem Solving in LLMs**, `arXiv, 2601.08763`, [arxiv](https://arxiv.org/abs/2601.08763v2), [pdf](https://arxiv.org/pdf/2601.08763v2.pdf), cication: [**-1**](None) 

	 *Zhiyuan Hu, Yucheng Wang, Yufei He, ..., Hae Won Park, Bryan Hooi*
- **Your Group-Relative Advantage Is Biased**, `arXiv, 2601.08521`, [arxiv](https://arxiv.org/abs/2601.08521v2), [pdf](https://arxiv.org/pdf/2601.08521v2.pdf), cication: [**-1**](None) 

	 *Fengkai Yang, Zherui Chen, Xiaohan Wang, ..., Jianxin Li, Yikun Ban*
- **Reinforcement Learning via Self-Distillation**, `arXiv, 2601.20802`, [arxiv](https://arxiv.org/abs/2601.20802v1), [pdf](https://arxiv.org/pdf/2601.20802v1.pdf), cication: [**-1**](None) 

	 *Jonas Hübotter, Frederike Lübeck, Lejs Behric, ..., Carlos Guestrin, Andreas Krause*
- **Golden Goose: A Simple Trick to Synthesize Unlimited RLVR Tasks from Unverifiable Internet Text**, `arXiv, 2601.22975`, [arxiv](https://arxiv.org/abs/2601.22975v2), [pdf](https://arxiv.org/pdf/2601.22975v2.pdf), cication: [**-1**](None) 

	 *Ximing Lu, David Acuna, Jaehun Jung, ..., Yi Dong, Yejin Choi*
- **F-GRPO: Don't Let Your Policy Learn the Obvious and Forget the Rare**, `arXiv, 2602.06717`, [arxiv](https://arxiv.org/abs/2602.06717v1), [pdf](https://arxiv.org/pdf/2602.06717v1.pdf), cication: [**-1**](None) 

	 *Daniil Plyusov, Alexey Gorbatovski, Boris Shaposhnikov, ..., Alexey Malakhov, Daniil Gavrilov*
- **Self-Distilled Reasoner: On-Policy Self-Distillation for Large Language Models**, `arXiv, 2601.18734`, [arxiv](https://arxiv.org/abs/2601.18734v1), [pdf](https://arxiv.org/pdf/2601.18734v1.pdf), cication: [**-1**](None) 

	 *Siyan Zhao, Zhihui Xie, Mengchen Liu, ..., Feiyu Chen, Aditya Grover*
- **GDPO: Group reward-Decoupled Normalization Policy Optimization for Multi-reward RL Optimization**, `arXiv, 2601.05242`, [arxiv](https://arxiv.org/abs/2601.05242v1), [pdf](https://arxiv.org/pdf/2601.05242v1.pdf), cication: [**-1**](None) 

	 *Shih-Yang Liu, Xin Dong, Ximing Lu, ..., Jan Kautz, Pavlo Molchanov*
- [How to Explore to Scale RL Training of LLMs on Hard Problems?](https://blog.ml.cmu.edu/2025/11/26/how-to-explore-to-scale-rl-training-of-llms-on-hard-problems/) 

	 · ([𝕏](https://x.com/aviral_kumar2/status/2001855734485582239))
- **Soft Adaptive Policy Optimization**, `arXiv, 2511.20347`, [arxiv](https://arxiv.org/abs/2511.20347v2), [pdf](https://arxiv.org/pdf/2511.20347v2.pdf), cication: [**-1**](None) 

	 *Chang Gao, Chujie Zheng, Xiong-Hui Chen, ..., Jingren Zhou, Junyang Lin*
- **The Path Not Taken: RLVR Provably Learns Off the Principals**, `arXiv, 2511.08567`, [arxiv](https://arxiv.org/abs/2511.08567v1), [pdf](https://arxiv.org/pdf/2511.08567v1.pdf), cication: [**-1**](None) 

	 *Hanqing Zhu, Zhenyu Zhang, Hanxian Huang, ..., Yuandong Tian, Kai Sheng Tai*
- **HiPO: Hybrid Policy Optimization for Dynamic Reasoning in LLMs**, `arXiv, 2509.23967`, [arxiv](http://arxiv.org/abs/2509.23967v2), [pdf](http://arxiv.org/pdf/2509.23967v2.pdf), cication: [**-1**](None) 

	 *Ken Deng, Zizheng Zhan, Wen Xiang, ..., Bin Chen, Jiaheng Liu*
  Reasoning**, `arXiv, 2510.25992`, [arxiv](http://arxiv.org/abs/2510.25992v1), [pdf](http://arxiv.org/pdf/2510.25992v1.pdf), cication: [**-1**](None) 

	 *Yihe Deng, I-Hung Hsu, Jun Yan, ..., Tomas Pfister, Chen-Yu Lee* · ([𝕏](https://x.com/IHung_Hsu/status/1984077573383712934))
- **The Art of Scaling Reinforcement Learning Compute for LLMs**, `arXiv, 2510.13786`, [arxiv](http://arxiv.org/abs/2510.13786v1), [pdf](http://arxiv.org/pdf/2510.13786v1.pdf), cication: [**-1**](None) 

	 *Devvrit Khatri, Lovish Madaan, Rishabh Tiwari, ..., David Brandfonbrener, Rishabh Agarwal*
- **SPICE: Self-Play In Corpus Environments Improves Reasoning**, `arXiv, 2510.24684`, [arxiv](http://arxiv.org/abs/2510.24684v1), [pdf](http://arxiv.org/pdf/2510.24684v1.pdf), cication: [**-1**](None) 

	 *Bo Liu, Chuanyang Jin, Seungone Kim, ..., Jack Lanchantin, Jason Weston*
- **ASPO: Asymmetric Importance Sampling Policy Optimization**, `arXiv, 2510.06062`, [arxiv](http://arxiv.org/abs/2510.06062v1), [pdf](http://arxiv.org/pdf/2510.06062v1.pdf), cication: [**-1**](None) 

	 *Jiakang Wang, Runze Liu, Lei Lin, ..., Guorui Zhou, Kun Gai* · ([Archer2.0](https://github.com/wizard-III/Archer2.0) - wizard-III) ![Star](https://img.shields.io/github/stars/wizard-III/Archer2.0.svg?style=social&label=Star) · ([huggingface](https://huggingface.co/collections/Fate-Zero/archer20-68b945c878768a27941fd7b6)) · ([zhuanlan.zhihu](https://zhuanlan.zhihu.com/p/1950985242098799047))
- **BAPO: Stabilizing Off-Policy Reinforcement Learning for LLMs via 
  Balanced Policy Optimization with Adaptive Clipping**, `arXiv, 2510.18927`, [arxiv](http://arxiv.org/abs/2510.18927v1), [pdf](http://arxiv.org/pdf/2510.18927v1.pdf), cication: [**-1**](None) 

	 *Zhiheng Xi, Xin Guo, Yang Nan, ..., Qi Zhang, Xuanjing Huang*
- **Every Step Evolves: Scaling Reinforcement Learning for Trillion-Scale 
  Thinking Model**, `arXiv, 2510.18855`, [arxiv](http://arxiv.org/abs/2510.18855v2), [pdf](http://arxiv.org/pdf/2510.18855v2.pdf), cication: [**-1**](None) 

	 *Ling Team, Anqi Shen, Baihui Li, ..., Zihao Wang, Zujie Wen*
- **Agentic Entropy-Balanced Policy Optimization**, `arXiv, 2510.14545`, [arxiv](http://arxiv.org/abs/2510.14545v1), [pdf](http://arxiv.org/pdf/2510.14545v1.pdf), cication: [**-1**](None) 

	 *Guanting Dong, Licheng Bao, Zhongyuan Wang, ..., Ji-Rong Wen, Zhicheng Dou*
- **VCRL: Variance-based Curriculum Reinforcement Learning for Large 
  Language Models**, `arXiv, 2509.19803`, [arxiv](http://arxiv.org/abs/2509.19803v1), [pdf](http://arxiv.org/pdf/2509.19803v1.pdf), cication: [**-1**](None) 

	 *Guochao Jiang, Wenfeng Feng, Guofeng Quan, ..., Guohua Liu, Hao Wang*

## RLVR

- **Rethinking the Trust Region in LLM Reinforcement Learning**, `arXiv, 2602.04879`, [arxiv](https://arxiv.org/abs/2602.04879v1), [pdf](https://arxiv.org/pdf/2602.04879v1.pdf), cication: [**-1**](None) 

	 *Penghui Qi, Xiangxin Zhou, Zichen Liu, ..., Min Lin, Wee Sun Lee* · ([𝕏](https://x.com/TheTuringPost/status/2022326245745377562))
- **SimKO: Simple Pass@K Policy Optimization**, `arXiv, 2510.14807`, [arxiv](https://arxiv.org/abs/2510.14807v2), [pdf](https://arxiv.org/pdf/2510.14807v2.pdf), cication: [**-1**](None) 

	 *Ruotian Peng, Yi Ren, Zhouliang Yu, ..., Weiyang Liu, Yandong Wen*

	 *Ruotian Peng, Yi Ren, Zhouliang Yu, ..., Weiyang Liu, Yandong Wen* · ([SimKO](https://github.com/CLR-Lab/SimKO) - CLR-Lab) ![Star](https://img.shields.io/github/stars/CLR-Lab/SimKO.svg?style=social&label=Star) · ([spherelab](https://spherelab.ai/simko/)))


## Test Time Scaling
- [Recursive Language Models](https://alexzhang13.github.io/blog/2025/rlm/) 

	 · ([𝕏](https://x.com/a1zhang/status/1978469116542337259))
- **Rethinking Thinking Tokens: LLMs as Improvement Operators**, `arXiv, 2510.01123`, [arxiv](http://arxiv.org/abs/2510.01123v1), [pdf](http://arxiv.org/pdf/2510.01123v1.pdf), cication: [**-1**](None) 

	 *Lovish Madaan, Aniket Didolkar, Suchin Gururangan, ..., Sanjeev Arora, Anirudh Goyal*
- **A Theoretical Study on Bridging Internal Probability and 
  Self-Consistency for LLM Reasoning**, `arXiv, 2510.15444`, [arxiv](http://arxiv.org/abs/2510.15444v1), [pdf](http://arxiv.org/pdf/2510.15444v1.pdf), cication: [**-1**](None) 

	 *Zhi Zhou, Yuhao Tan, Zenan Li, ..., Yu-Feng Li, Xiaoxing Ma*


## Latent Reasoning

- **Dynamic Large Concept Models: Latent Reasoning in an Adaptive Semantic Space**, `arXiv, 2512.24617`, [arxiv](https://arxiv.org/abs/2512.24617v2), [pdf](https://arxiv.org/pdf/2512.24617v2.pdf), cication: [**-1**](None) 

	 *Xingwei Qu, Shaowen Wang, Zihao Huang, ..., Ge Zhang, Wenhao Huang*
- **Think-at-Hard: Selective Latent Iterations to Improve Reasoning Language Models**, `arXiv, 2511.08577`, [arxiv](https://arxiv.org/abs/2511.08577v1), [pdf](https://arxiv.org/pdf/2511.08577v1.pdf), cication: [**-1**](None) 

	 *Tianyu Fu, Yichen You, Zekai Chen, ..., Huazhong Yang, Yu Wang*
- **Scaling Latent Reasoning via Looped Language Models**, `arXiv, 2510.25741`, [arxiv](https://arxiv.org/abs/2510.25741v4), [pdf](https://arxiv.org/pdf/2510.25741v4.pdf), cication: [**-1**](None) 

	 *Rui-Jie Zhu, Zixuan Wang, Kai Hua, ..., Yoshua Bengio, Jason Eshraghian*

## Data


## Toolkits


## Misc
## Misc
- [random improvement property of RLVR disappears with proper data decontamination](https://x.com/cwolferesearch/status/1998289169052045516)  𝕏 