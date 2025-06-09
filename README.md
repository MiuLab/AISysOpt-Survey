# AI System Optimization Survey

### 🏛️ Fixed Structure, NL Feedback

| Date |      Authors       |  Venue  | Paper                                                                                                                                  |
| :--: | :----------------: | :-----: | :------------------------------------------------------------------------------------------------------------------------------------- |
| 2406 | Yuksekgonul et al. | Nature  | [TextGrad: Automatic "Differentiation" via Text](https://arxiv.org/abs/2406.07496)                                                     |
| 2406 |    Cheng et al.    | NeurIPS | [Trace is the Next AutoDiff: Generative Optimization with Rich Feedback, Execution Traces, and LLMs](https://arxiv.org/abs/2406.16218) |
| 2410 |    Patel et al.    |  arXiv  | [AIME: AI System Optimization via Multiple LLM Evaluators](https://arxiv.org/abs/2410.03131)                                           |
| 2412 |    Zhang et al.    |  arXiv  | [Revolve: Optimizing AI Systems by Tracking Response Evolution in Textual Optimization](https://arxiv.org/abs/2412.03092)              |
| 2412 |    Wang et al.     |  arXiv  | [How to Correctly do Semantic Backpropagation on Language-based Agentic Systems](https://arxiv.org/abs/2412.03624)                     |
| 2501 |     Yin et al.     |  arXiv  | [LLM-AutoDiff: Auto-Differentiate Any LLM Workflow](https://arxiv.org/abs/2501.16673)                                                  |

### 📈 Fixed Structure, Numerical Signals

| Date |      Authors       | Venue | Paper                                                                                                                                        |
| :--: | :----------------: | :---: | :------------------------------------------------------------------------------------------------------------------------------------------- |
| 2310 |   Khattab et al.   | ICLR  | [DSPy: Compiling Declarative Language Model Calls into Self-Improving Pipelines](https://arxiv.org/abs/2310.03714)                           |
| 2406 | Opsahl-Ong et al.  | EMNLP | [Optimizing Instructions and Demonstrations for Multi-Stage Language Model Programs](https://arxiv.org/abs/2406.11695)                       |
| 2407 |    Soylu et al.    | EMNLP | [Fine-Tuning and Prompt Optimization: Two Great Steps that Work Better Together](https://arxiv.org/abs/2407.10930)                           |
| 2501 | Subramaniam et al. | ICLR  | [Multiagent Finetuning: Self Improvement with Diverse Reasoning Chains](https://arxiv.org/abs/2501.05707)                                    |
| 2502 |    Zhao et al.     | arXiv | [SiriuS: Self-improving Multi-agent Systems via Bootstrapped Reasoning](https://arxiv.org/abs/2502.04780)                                    |
| 2502 |    Park et al.     | arXiv | [MAPoRL: Multi-Agent Post-Co-Training for Collaborative Large Language Models with Reinforcement Learning](https://arxiv.org/abs/2502.18439) |
| 2502 |    Wang et al.     | AAAI  | [Aligning Compound AI Systems via System-level DPO](https://arxiv.org/abs/2502.17721)                                                        |

### 🧠 Flexible Structure, NL Feedback

| Date |   Authors    | Venue | Paper                                                                                                        |
| :--: | :----------: | :---: | :----------------------------------------------------------------------------------------------------------- |
| 2406 | Zhou et al.  | arXiv | [Symbolic Learning Enables Self-Evolving Agents](https://arxiv.org/abs/2406.18532)                           |
| 2408 |  Hu et al.   | ICLR  | [Automated Design of Agentic Systems](https://arxiv.org/abs/2408.08435)                                      |
| 2410 | Zhang et al. | ICLR  | [AFlow: Automating Agentic Workflow Generation](https://arxiv.org/abs/2410.10762)                            |
| 2502 | Zhou et al.  | arXiv | [Multi-Agent Design: Optimizing Agents with Better Prompts and Topologies](https://arxiv.org/abs/2502.02533) |
| 2503 |  Su et al.   | COLM  | [DebFlow: Automating Agent Creation via Agent Debate](https://arxiv.org/abs/2503.23781)                      |

### 🌐 Flexible Structure, Numerical Signals

| Date |   Authors    | Venue | Paper                                                                                                                |
| :--: | :----------: | :---: | :------------------------------------------------------------------------------------------------------------------- |
| 2310 |  Liu et al.  | COLM  | [A Dynamic LLM-Powered Agent Network for Task-Oriented Agent Collaboration](https://arxiv.org/abs/2310.02170)        |
| 2402 | Zhuge et al. | ICML  | [Language Agents as Optimizable Graphs](https://arxiv.org/abs/2402.16823)                                            |
| 2407 |  Li et al.   | arXiv | [AutoFlow: Automated Workflow Generation for Large Language Model Agents](https://arxiv.org/abs/2407.12821)          |
| 2502 | Wang et al.  | arXiv | [ScoreFlow: Mastering LLM Agent Workflows via Score-based Preference Optimization](https://arxiv.org/abs/2502.04306) |
| 2503 |  Ye et al.   | arXiv | [MAS-GPT: Training LLMs to Build LLM-based Multi-Agent Systems](https://arxiv.org/abs/2503.03686)                    |
| 2504 |  Nie et al.  | arXiv | [Weak-for-Strong: Training Weak Meta-Agent to Harness Strong Executors](https://arxiv.org/abs/2504.04785)            |

<!--

## Temporary Structure
[04/10 Slides](https://docs.google.com/presentation/d/12ZLgGgAG7FaFP4ddgcyc23e0TYXE0KsR3biGCRYFO84/edit?usp=sharing)


[Slides](https://docs.google.com/presentation/d/1voYwNgNOMGreKYnBLNKa4cvi9g2s3wIiXXpx_lFhaYA/edit?usp=sharing)

- AI system optimization problem
    - Definitions
        - [DSPy: Compiling Declarative Language Model Calls into Self-Improving Pipelines](https://arxiv.org/abs/2310.03714)
        - [A Review of Prominent Paradigms for LLM-Based Agents: Tool Use (Including RAG), Planning, and Feedback Learning](https://arxiv.org/html/2406.05804v6#bib.bib38)
            - 透過「任務類型」、「使用環境」、「LLM扮演的角色」，歸納各個 LLM-based agents 的工作流程，並比較不同 Agents 之間流程設計的關鍵，最後歸納當前的工作流程的侷限性：(1) A Unified Solution for Base Workflows and Autonomous Tool-Use Workflows、(2)Lack of Universal Tool-Use Workflow Design、(3)Formulating Language Tasks as Agentic Tasks
        - [AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversation](https://arxiv.org/abs/2308.08155)
            - 我們討論的分類型態，這篇的 framework 內幾乎都有涵蓋到
        - [LLM-based Optimization of Compound AI Systems: A Survey](https://arxiv.org/abs/2410.16392)
        - [A Survey on Large Language Model based Autonomous Agents](https://arxiv.org/abs/2308.11432)
        - [Multi-Modal and Multi-Agent Systems Meet Rationality: A Survey](https://arxiv.org/abs/2406.00252v1)
    - Fixed-structure optimization
        - Training-less methods (or non-numerical related method)
            - Natural Language Feedback (Textual gradient) Based Methods
                - Basic frameworks
                    - [Large Language Models as Optimizers](https://arxiv.org/pdf/2309.03409)
                    - [TextGrad: Automatic "Differentiation" via Text](https://arxiv.org/abs/2406.07496)
                    - [Trace is the Next AutoDiff: Generative Optimization with Rich Feedback, Execution Traces, and LLMs](https://arxiv.org/pdf/2406.16218)
                    - [CoMM: Collaborative Multi-Agent, Multi-Reasoning-Path Prompting for Complex Problem Solving](https://arxiv.org/pdf/2404.17729)
                - Advanced frameworks
                    - [How to Correctly do Semantic Backpropagation on Language-based Agentic Systems](https://arxiv.org/abs/2412.03624)
                    - [Revolve: Optimizing AI Systems by Tracking Response Evolution in Textual Optimization](https://arxiv.org/abs/2412.03092)
                    - [LLM-AutoDiff: Auto-Differentiate Any LLM Workflow](https://arxiv.org/abs/2501.16673)
            - Self-Improvement
                - [ReST meets ReAct: Self-Improvement for Multi-Step Reasoning LLM Agent](https://arxiv.org/abs/2312.10003)
                    - 基於改進這篇：[ReAct Meets ActRe: When Language Agents Enjoy Training Data Autonomy](https://arxiv.org/abs/2403.14589)
                - [ADaPT: As-Needed Decomposition and Planning with Language Models](https://arxiv.org/abs/2311.05772)
                - [Symbolic Learning Enables Self-Evolving Agents](https://arxiv.org/abs/2406.18532)
                - [Promptbreeder: Self-Referential Self-Improvement Via Prompt Evolution](https://arxiv.org/abs/2309.16797)
            - [A Declarative System for Optimizing AI Workloads](https://arxiv.org/abs/2405.14696)
            - Reasoning
                - [Chain-of-Planned-Behaviour Workflow Elicits Few-Shot Mobility Generation in LLMs](https://arxiv.org/abs/2402.09836)
                - [Combinatorial Reasoning: Selecting Reasons in Generative AI Pipelines via Combinatorial Optimization](https://arxiv.org/abs/2407.00071)
        - Methods with training/finetuning (or numerical methods) (e.g. RL, finetuning)
            - [From Novice to Expert: LLM Agent Policy Optimization via Step-wise Reinforcement Learning](https://arxiv.org/pdf/2411.03817)
            - [Mars-PO: Multi-Agent Reasoning System Preference Optimization](https://arxiv.org/pdf/2411.19039)
            - [MAPoRL: Multi-Agent Post-Co-Training for Collaborative Large Language Models with Reinforcement Learning](https://arxiv.org/abs/2502.18439)
            - [GReaTer: Gradients over Reasoning Makes Smaller Language Models Strong Prompt Optimizers](https://arxiv.org/abs/2412.09722)
            - [Aligning Compound AI Systems via System-level DPO](https://arxiv.org/pdf/2502.17721v1)
            - [SiriuS: Self-improving Multi-agent Systems via Bootstrapped Reasoning](https://arxiv.org/abs/2502.04780)
    - Structure optimization (e.g. how to build graph)
        - Graph
            - [Multi-Agent Design: Optimizing Agents with Better Prompts and Topologies](https://arxiv.org/pdf/2502.02533)
            - [A Versatile Graph Learning Approach through LLM-based Agent](https://arxiv.org/abs/2309.04565)
            - [Data Interpreter: An LLM Agent For Data Science](https://arxiv.org/abs/2402.18679)
            - [G-Designer: Architecting Multi-agent Communication Topologies via Graph Neural Networks](https://arxiv.org/abs/2410.11782)
            - [A Dynamic LLM-Powered Agent Network for Task-Oriented Agent Collaboration](https://arxiv.org/abs/2310.02170)
            - [GPTSwarm: Language Agents as Optimizable Graphs](https://arxiv.org/pdf/2402.16823)
        - Non-graph
            - Training-less methods
                - [AutoFlow: Automated Workflow Generation for Large Language Model Agents](https://arxiv.org/abs/2407.12821)
                - [AFlow: Automating Agentic Workflow Generation](https://arxiv.org/abs/2410.10762)
            - Methods with training/finetuning (or numerical methods)
                - [ScoreFlow: Mastering LLM Agent Workflows via Score-based Preference Optimization](https://arxiv.org/abs/2502.04306)
    - Advanced topics (applications)
        - [DSPy Assertions: Computational Constraints for Self-Refining Language Model Pipelines](https://arxiv.org/abs/2312.13382)
        - Evaluation
            - [An Agentic AI Workflow for Detecting Cognitive Concerns in Real-world Data](https://arxiv.org/abs/2502.01789)
        - autonomous Agent Operating System
            - [AutoAgent: A Fully-Automated and Zero-Code Framework for LLM Agents](https://arxiv.org/abs/2502.05957)
        - FL
            - [Can Textual Gradient Work in Federated Learning?](https://arxiv.org/abs/2502.19980)
        - Meta Learning
            - [metaTextGrad: Learning to learn with language models as optimizers](https://openreview.net/forum?id=yzieYIT9hu)

## Main idea
* 具體要比較的點是什麼？(待補充)
## Structure
1. Methods (keywords)
2. Cost ( paper/ 自行估算)
	1. times of LM calling (v)
		1. training time v.s. inference
3. Benchmark / Datasets
4. Initial LM
5. Evaluation LM
6. Others

分類 (methods)
1. 以 LM 進行優化 (3: 冠廷(1、2)、冠柏(3、4)、玫宜(Others))
	1. Backpropagation
	2. Gradients
	3. Texual Optimization
	4. Prompt opt
	5. comparing reasoning
	6. meta learning
2. 不侷限於 LM 進行優化 (2: 睿超 (1)、宇昂 (2) )
	1. RL
		1. Aligning Compound AI Systems via System-level DPO
	2. numerical
		1. [GReaTer: Gradients over Reasoning Makes Smaller Language Models Strong Prompt Optimizers](https://arxiv.org/abs/2412.09722)
		2. [ScoreFlow: Mastering LLM Agent Workflows via Score-based Preference Optimization](https://arxiv.org/abs/2502.04306)
## Paper

- [DSPy: Compiling Declarative Language Model Calls into Self-Improving Pipelines](https://arxiv.org/abs/2310.03714)
- [Large Language Models as Optimizers](https://arxiv.org/abs/2309.03409)
- [TextGrad: Automatic "Differentiation" via Text](https://arxiv.org/abs/2406.07496)
	- [AutoMedPrompt: A New Framework for Optimizing LLM Medical Prompts Using Textual Gradients](https://www.arxiv.org/abs/2502.15944)
- [Trace is the Next AutoDiff: Generative Optimization with Rich Feedback, Execution Traces, and LLMs](https://arxiv.org/abs/2406.16218)
- [GPTSwarm: Language Agents as Optimizable Graphs](https://arxiv.org/pdf/2402.16823)
- [Self-Supervised Prompt Optimization](https://arxiv.org/pdf/2502.06855)
- [PROMPTAGENT: STRATEGIC PLANNING WITH LANGUAGE MODELS ENABLES EXPERT-LEVEL PROMPT OPTIMIZATION](https://arxiv.org/pdf/2310.16427)

不是很確定有沒有直接相關
* [SGLang: Efficient Execution of Structured Language Model Programs](https://arxiv.org/abs/2312.07104)

### Prompt Optimization (not directly related to LLM systems)

- [Large Language Models are Human-Level Prompt Engineers](https://arxiv.org/pdf/2211.01910)
- [AUTOPROMPT: Eliciting Knowledge from Language Models with Automatically Generated Prompts](https://arxiv.org/pdf/2010.15980)
- [RLPROMPT: Optimizing Discrete Text Prompts with Reinforcement Learning](https://arxiv.org/pdf/2205.12548)
- [Prompt Optimization with Human Feedback](https://arxiv.org/pdf/2405.17346)

### Survey
- [LLM-based Optimization of Compound AI Systems: A Survey](https://arxiv.org/pdf/2410.16392#page=14&zoom=100,88,813)

## 20250306 討論摘要
1. 比較：
	1. benchmark
	2. DPO
	3. cost
		1. cost v.s. performance  (ref. [AIME: AI System Optimization via Multiple LLM Evaluators](https://arxiv.org/abs/2410.03131))
		2. [Self-Supervised Prompt Optimization](https://arxiv.org/abs/2502.06855)
	4. 初始的LM and evaluation LM

2. evaluate benchmark
	1. 補充每一篇 paper 的方法使用的 benchmark
	2. ex. 統一使用 gsm8k

3. DPO v.s. system opt. relation
	1. 比較 RL vs 剛剛提到的方法之間的效果有什麼不同/特色
4. cost (LM coding 的次數) 需不需納入考量
5. paper 有沒有提到 initial prompt, 對於 performance 有沒有影響？

 -->
