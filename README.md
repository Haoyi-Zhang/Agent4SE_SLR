# Agent4SE: Systematic Literature Review on Intelligent Agents for Software Engineering

## 📖 Overview

Intelligent Agents have rapidly moved from concept to practice in software engineering (SE), catalyzed by advances in large language models (LLMs), multi-agent coordination, and tool-augmented automation. Beyond single-turn assistance, contemporary agents can perceive heterogeneous SE artifacts, reason over long horizons, act on development environments, and refine their behavior from feedback. This paradigm promises end-to-end support across the software development lifecycle (SDLC)—from requirements and design to coding, testing, deployment, and evolution—while also raising urgent questions of definition, architecture, evaluation fidelity, safety, and integration at scale.

Despite the intense activity, the landscape remains fragmented along three dimensions:  
- **Conceptually**, the notion of “agent” spans from chat-style copilots to autonomous, tool-operating systems, with implicit or inconsistent boundaries.  
- **Technically**, implementations reuse similar building blocks (planning/orchestration, knowledge grounding, deep tool integration), yet descriptions and interfaces remain heterogeneous, hindering replication and transfer.  
- **Empirically**, reported results are short-horizon and task-specific, with limited attention to multi-agent coordination, repository-scale validation, human–AI interaction quality, and transparent cost/latency reporting.  

To address these gaps, we conducted a **Systematic Literature Review (SLR)** of **215 peer-reviewed studies** published between April 2023 and July 2025. Our SLR introduces a comprehensive classification framework, synthesizes conceptual and technological landscapes, and develops a challenges-to-directions roadmap for advancing Intelligent Agents in SE.

---

## 🔍 Research Questions

We address three research questions:

1. **RQ1: How are Intelligent Agents conceptualized and what is the scope of their current applications in software engineering contexts?**  
   This foundational research question systematically addresses the conceptual landscape of Intelligent Agents within software engineering domains, examining both theoretical frameworks and practical implementation patterns. The investigation encompasses systematic analysis of definitional approaches, taxonomic classifications, and architectural paradigms employed across the literature, including agent taxonomy development, application domain mapping across software engineering lifecycle phases, and capability boundary analysis examining human–AI collaboration patterns.

2. **RQ2: What technological architectures and implementation approaches enable Intelligent Agent deployment in software engineering applications?**  
   This technically focused research question systematically examines the technological substrates, architectural patterns, and implementation methodologies that enable Intelligent Agent capabilities in software engineering contexts. The investigation encompasses comprehensive analysis of AI/ML foundations, system architectural approaches, learning mechanisms, and development tool ecosystems, including foundation technologies, system architecture patterns, learning mechanism analysis, and development tool examination.

3. **RQ3: What are the primary barriers to Intelligent Agent adoption in software engineering, and what opportunities exist for future development and research?**  
   This forward-looking research question systematically analyzes current limitations, deployment challenges, and evolutionary opportunities that will shape the future development of Intelligent Agents in software engineering. The investigation encompasses systematic analysis of current barriers, emerging opportunities, evaluation challenges, and future research directions, providing strategic insights for both researchers and practitioners.


## 🗂Table of Contents

- [Software Development Lifecycle Management](#software-development-lifecycle-management)  
  - [Requirements Engineering and Analysis](#requirements-engineering-and-analysis)  
  - [Software Design and Architecture](#software-design-and-architecture)  
  - [Code Generation and Implementation](#code-generation-and-implementation)  
  - [Testing and Quality Assurance](#testing-and-quality-assurance)  
  - [Maintenance and Evolution](#maintenance-and-evolution)  

- [Multi-Agent Systems and Collaboration](#multi-agent-systems-and-collaboration)  
  - [Agent Architecture and Framework Design](#agent-architecture-and-framework-design)  
  - [Multi-Agent Coordination and Communication](#multi-agent-coordination-and-communication)  
  - [Agent Specialization and Role Assignment](#agent-specialization-and-role-assignment)  
  - [Collaborative Problem Solving](#collaborative-problem-solving)  

- [Code Analysis and Quality Assurance](#code-analysis-and-quality-assurance)  
  - [Static Code Analysis and Bug Detection](#static-code-analysis-and-bug-detection)  
  - [Code Review Automation](#code-review-automation)  
  - [Software Quality Assessment](#software-quality-assessment)  
  - [Security and Vulnerability Analysis](#security-and-vulnerability-analysis)  

- [Automated Testing and Validation](#automated-testing-and-validation)  
  - [API Testing and Service Validation](#api-testing-and-service-validation)  
  - [Unit Testing and Test Generation](#unit-testing-and-test-generation)  
  - [System Testing and Integration](#system-testing-and-integration)  
  - [Multi-User Interactive Testing](#multi-user-interactive-testing)  

- [Industrial Applications and Domain-Specific Solutions](#industrial-applications-and-domain-specific-solutions)  
  - [Smart Manufacturing and Industrial Automation](#smart-manufacturing-and-industrial-automation)  
  - [Cloud Systems and Infrastructure Management](#cloud-systems-and-infrastructure-management)  
  - [Network Configuration and Management](#network-configuration-and-management)  
  - [Electronic Design Automation](#electronic-design-automation)  
  - [Policy as Code and Compliance Automation](#policy-as-code-and-compliance-automation)  

- [Educational and Research Applications](#educational-and-research-applications)  
  - [Programming Education and Learning Support](#programming-education-and-learning-support)  
  - [Research Methodology and Literature Analysis](#research-methodology-and-literature-analysis)  
  - [Agent-Based Modeling and Simulation](#agent-based-modeling-and-simulation)  
  - [Evaluation and Benchmarking Systems](#evaluation-and-benchmarking-systems)  

- [Development Process Automation](#development-process-automation)  
  - [Agile Development Support](#agile-development-support)  
  - [DevOps and Continuous Integration](#devops-and-continuous-integration)  
  - [Project Management and Planning](#project-management-and-planning)  
  - [Issue Resolution and Bug Fixing](#issue-resolution-and-bug-fixing)  

- [Human-AI Interaction and Collaboration](#human-ai-interaction-and-collaboration)  
  - [Conversational Programming Interfaces](#conversational-programming-interfaces)  
  - [AI-Assisted Development Tools](#ai-assisted-development-tools)  
  - [Human-in-the-Loop Systems](#human-in-the-loop-systems)  
  - [Context-Aware Assistance](#context-aware-assistance)  

- [System Integration and Tool Development](#system-integration-and-tool-development)  
  - [API Integration and Service Orchestration](#api-integration-and-service-orchestration)  
  - [Development Environment Integration](#development-environment-integration)  
  - [Tool Chain Automation](#tool-chain-automation)  

- [Legacy System Modernization and Documentation](#legacy-system-modernization-and-documentation)  
  - [Legacy Code Analysis and Understanding](#legacy-code-analysis-and-understanding)  
  - [Code Documentation Generation](#code-documentation-generation)  
  - [System Migration and Transformation](#system-migration-and-transformation)  
  - [Knowledge Extraction and Preservation](#knowledge-extraction-and-preservation)  


## Software Development Lifecycle Management
### Requirements Engineering and Analysis
- **Title**: Autonomous Agents in Software Development: A Vision Paper
  - **Authors**: Zeeshan Rasheed, Muhammad Waseem, Kai-Kristian Kemell, Wang Xiaofeng, Anh Nguyen Duc, Kari Systä, Pekka Abrahamsson
  - **Published**: 2023-11-30
  - **Link**: http://arxiv.org/abs/2311.18440v1
  
  
- **Title**: CodePori: Large-Scale System for Autonomous Software Development Using Multi-Agent Technology
  - **Authors**: Zeeshan Rasheed, Malik Abdul Sami, Kai-Kristian Kemell, Muhammad Waseem, Mika Saari, Kari Systä, Pekka Abrahamsson
  - **Published**: 2024-02-02
  - **Link**: http://arxiv.org/abs/2402.01411v2
  
  
- **Title**: LLM-based agents for automating the enhancement of user story quality: An early report
  - **Authors**: Zheying Zhang, Maruf Rayhan, Tomas Herda, Manuel Goisauf, Pekka Abrahamsson
  - **Published**: 2024-03-14
  - **Link**: http://arxiv.org/abs/2403.09442v1
  
  
- **Title**: MARE: Multi-Agents Collaboration Framework for Requirements Engineering
  - **Authors**: Dongming Jin, Zhi Jin, Xiaohong Chen, Chunhui Wang
  - **Published**: 2024-05-06
  - **Link**: http://arxiv.org/abs/2405.03256v1
  
  
- **Title**: Experimenting with Multi-Agent Software Development: Towards a Unified Platform
  - **Authors**: Malik Abdul Sami, Muhammad Waseem, Zeeshan Rasheed, Mika Saari, Kari Systä, Pekka Abrahamsson
  - **Published**: 2024-06-08
  - **Link**: http://arxiv.org/abs/2406.05381v1
  
  
- **Title**: MAO: A Framework for Process Model Generation with Multi-Agent Orchestration
  - **Authors**: Leilei Lin, Yumeng Jin, Yingming Zhou, Wenlong Chen, Chen Qian
  - **Published**: 2024-08-04
  - **Link**: http://arxiv.org/abs/2408.01916v2
  
  
- **Title**: From LLMs to LLM-based Agents for Software Engineering: A Survey of Current, Challenges and Future
  - **Authors**: Haolin Jin, Linghan Huang, Haipeng Cai, Jun Yan, Bo Li, Huaming Chen
  - **Published**: 2024-08-05
  - **Link**: http://arxiv.org/abs/2408.02479v2
  
  
- **Title**: Agents in Software Engineering: Survey, Landscape, and Vision
  - **Authors**: Yanlin Wang, Wanjun Zhong, Yanxian Huang, Ensheng Shi, Min Yang, Jiachi Chen, Hui Li, Yuchi Ma, Qianxiang Wang, Zibin Zheng
  - **Published**: 2024-09-13
  - **Link**: http://arxiv.org/abs/2409.09030v2
  
  
- **Title**: Improving Performance of Commercially Available AI Products in a Multi-Agent Configuration
  - **Authors**: Cory Hymel, Sida Peng, Kevin Xu, Charath Ranganathan
  - **Published**: 2024-10-29
  - **Link**: http://arxiv.org/abs/2410.22129v1
  
  
- **Title**: Goal2Story: A Multi-Agent Fleet based on Privately Enabled sLLMs for Impacting Mapping on Requirements Elicitation
  - **Authors**: Xinkai Zou, Yan Liu, Xiongbo Shi, Chen Yang
  - **Published**: 2025-03-17
  - **Link**: http://arxiv.org/abs/2503.13279v1
  
  
- **Title**: Software Development Life Cycle Perspective: A Survey of Benchmarks for Code Large Language Models and Agents
  - **Authors**: Kaixin Wang, Tianlin Li, Xiaoyu Zhang, Chong Wang, Weisong Sun, Yang Liu, Bin Shi
  - **Published**: 2025-05-08
  - **Link**: http://arxiv.org/abs/2505.05283v2
  
  
- **Title**: Unified Software Engineering agent as AI Software Engineer
  - **Authors**: Leonhard Applis, Yuntong Zhang, Shanchao Liang, Nan Jiang, Lin Tan, Abhik Roychoudhury
  - **Published**: 2025-06-17
  - **Link**: http://arxiv.org/abs/2506.14683v1
  
  
- **Title**: Knowledge-Guided Multi-Agent Framework for Automated Requirements Development: A Vision
  - **Authors**: Jiangping Huang, Dongming Jin, Weisong Sun, Yang Liu, Zhi Jin
  - **Published**: 2025-06-27
  - **Link**: http://arxiv.org/abs/2506.22656v1
  
  
- **Title**: Multi-Agent Debate Strategies to Enhance Requirements Engineering with Large Language Models
  - **Authors**: Marc Oriol, Quim Motger, Jordi Marco, Xavier Franch
  - **Published**: 2025-07-08
  - **Link**: http://arxiv.org/abs/2507.05981v1
  
  
### Software Design and Architecture
- **Title**: ChatDev: Communicative Agents for Software Development
  - **Authors**: Chen Qian, Wei Liu, Hongzhang Liu, Nuo Chen, Yufan Dang, Jiahao Li, Cheng Yang, Weize Chen, Yusheng Su, Xin Cong, Juyuan Xu, Dahai Li, Zhiyuan Liu, Maosong Sun
  - **Published**: 2023-07-16
  - **Link**: http://arxiv.org/abs/2307.07924v5
  
  
- **Title**: Autonomous Agents in Software Development: A Vision Paper
  - **Authors**: Zeeshan Rasheed, Muhammad Waseem, Kai-Kristian Kemell, Wang Xiaofeng, Anh Nguyen Duc, Kari Systä, Pekka Abrahamsson
  - **Published**: 2023-11-30
  - **Link**: http://arxiv.org/abs/2311.18440v1
  
  
- **Title**: Experimenting with Multi-Agent Software Development: Towards a Unified Platform
  - **Authors**: Malik Abdul Sami, Muhammad Waseem, Zeeshan Rasheed, Mika Saari, Kari Systä, Pekka Abrahamsson
  - **Published**: 2024-06-08
  - **Link**: http://arxiv.org/abs/2406.05381v1
  
  
- **Title**: From LLMs to LLM-based Agents for Software Engineering: A Survey of Current, Challenges and Future
  - **Authors**: Haolin Jin, Linghan Huang, Haipeng Cai, Jun Yan, Bo Li, Huaming Chen
  - **Published**: 2024-08-05
  - **Link**: http://arxiv.org/abs/2408.02479v2
  
  
- **Title**: Agents in Software Engineering: Survey, Landscape, and Vision
  - **Authors**: Yanlin Wang, Wanjun Zhong, Yanxian Huang, Ensheng Shi, Min Yang, Jiachi Chen, Hui Li, Yuchi Ma, Qianxiang Wang, Zibin Zheng
  - **Published**: 2024-09-13
  - **Link**: http://arxiv.org/abs/2409.09030v2
  
  
- **Title**: Knowledge-Based Multi-Agent Framework for Automated Software Architecture Design
  - **Authors**: Yiran Zhang, Ruiyin Li, Peng Liang, Weisong Sun, Yang Liu
  - **Published**: 2025-03-26
  - **Link**: http://arxiv.org/abs/2503.20536v1
  
  
- **Title**: Software Development Life Cycle Perspective: A Survey of Benchmarks for Code Large Language Models and Agents
  - **Authors**: Kaixin Wang, Tianlin Li, Xiaoyu Zhang, Chong Wang, Weisong Sun, Yang Liu, Bin Shi
  - **Published**: 2025-05-08
  - **Link**: http://arxiv.org/abs/2505.05283v2
  
  
- **Title**: Unified Software Engineering agent as AI Software Engineer
  - **Authors**: Leonhard Applis, Yuntong Zhang, Shanchao Liang, Nan Jiang, Lin Tan, Abhik Roychoudhury
  - **Published**: 2025-06-17
  - **Link**: http://arxiv.org/abs/2506.14683v1
  
  
### Code Generation and Implementation
- **Title**: ChatDev: Communicative Agents for Software Development
  - **Authors**: Chen Qian, Wei Liu, Hongzhang Liu, Nuo Chen, Yufan Dang, Jiahao Li, Cheng Yang, Weize Chen, Yusheng Su, Xin Cong, Juyuan Xu, Dahai Li, Zhiyuan Liu, Maosong Sun
  - **Published**: 2023-07-16
  - **Link**: http://arxiv.org/abs/2307.07924v5
  
  
- **Title**: Autonomous Agents in Software Development: A Vision Paper
  - **Authors**: Zeeshan Rasheed, Muhammad Waseem, Kai-Kristian Kemell, Wang Xiaofeng, Anh Nguyen Duc, Kari Systä, Pekka Abrahamsson
  - **Published**: 2023-11-30
  - **Link**: http://arxiv.org/abs/2311.18440v1
  
  
- **Title**: CodeAgent: Enhancing Code Generation with Tool-Integrated Agent Systems for Real-World Repo-level Coding Challenges
  - **Authors**: Kechi Zhang, Jia Li, Ge Li, Xianjie Shi, Zhi Jin
  - **Published**: 2024-01-14
  - **Link**: http://arxiv.org/abs/2401.07339v2
  
  
- **Title**: CodePori: Large-Scale System for Autonomous Software Development Using Multi-Agent Technology
  - **Authors**: Zeeshan Rasheed, Malik Abdul Sami, Kai-Kristian Kemell, Muhammad Waseem, Mika Saari, Kari Systä, Pekka Abrahamsson
  - **Published**: 2024-02-02
  - **Link**: http://arxiv.org/abs/2402.01411v2
  
  
- **Title**: SOEN-101: Code Generation by Emulating Software Process Models Using Large Language Model Agents
  - **Authors**: Feng Lin, Dong Jae Kim, Tse-Husn, Chen
  - **Published**: 2024-03-23
  - **Link**: http://arxiv.org/abs/2403.15852v2
  
  
- **Title**: Large Language Model Evaluation Via Multi AI Agents: Preliminary results
  - **Authors**: Zeeshan Rasheed, Muhammad Waseem, Kari Systä, Pekka Abrahamsson
  - **Published**: 2024-04-01
  - **Link**: http://arxiv.org/abs/2404.01023v1
  
  
- **Title**: Self-Organized Agents: A LLM Multi-Agent Framework toward Ultra Large-Scale Code Generation and Optimization
  - **Authors**: Yoichi Ishibashi, Yoshimasa Nishimura
  - **Published**: 2024-04-02
  - **Link**: http://arxiv.org/abs/2404.02183v1
  
  
- **Title**: HumanEvalComm: Benchmarking the Communication Competence of Code Generation for LLMs and LLM Agent
  - **Authors**: Jie JW Wu, Fatemeh H Fard
  - **Published**: 2024-05-31
  - **Link**: http://arxiv.org/abs/2406.00215v3
  
  
- **Title**: Experimenting with Multi-Agent Software Development: Towards a Unified Platform
  - **Authors**: Malik Abdul Sami, Muhammad Waseem, Zeeshan Rasheed, Mika Saari, Kari Systä, Pekka Abrahamsson
  - **Published**: 2024-06-08
  - **Link**: http://arxiv.org/abs/2406.05381v1
  
  
- **Title**: CoSQA+: Pioneering the Multi-Choice Code Search Benchmark with Test-Driven Agents
  - **Authors**: Jing Gong, Yanghui Wu, Linxi Liang, Yanlin Wang, Jiachi Chen, Mingwei Liu, Zibin Zheng
  - **Published**: 2024-06-17
  - **Link**: http://arxiv.org/abs/2406.11589v5
  
  
- **Title**: CodeNav: Beyond tool-use to using real-world codebases with LLM agents
  - **Authors**: Tanmay Gupta, Luca Weihs, Aniruddha Kembhavi
  - **Published**: 2024-06-18
  - **Link**: http://arxiv.org/abs/2406.12276v1
  
  
- **Title**: Agent-Driven Automatic Software Improvement
  - **Authors**: Fernando Vallecillos Ruiz
  - **Published**: 2024-06-24
  - **Link**: http://arxiv.org/abs/2406.16739v1
  
  
- **Title**: Agentless: Demystifying LLM-based Software Engineering Agents
  - **Authors**: Chunqiu Steven Xia, Yinlin Deng, Soren Dunn, Lingming Zhang
  - **Published**: 2024-07-01
  - **Link**: http://arxiv.org/abs/2407.01489v2
  
  
- **Title**: PyBench: Evaluating LLM Agent on various real-world coding tasks
  - **Authors**: Yaolun Zhang, Yinxu Pan, Yudong Wang, Jie Cai
  - **Published**: 2024-07-23
  - **Link**: http://arxiv.org/abs/2407.16732v2
  
  
- **Title**: OpenHands: An Open Platform for AI Software Developers as Generalist Agents
  - **Authors**: Xingyao Wang, Boxuan Li, Yufan Song, Frank F. Xu, Xiangru Tang, Mingchen Zhuge, Jiayi Pan, Yueqi Song, Bowen Li, Jaskirat Singh, Hoang H. Tran, Fuqiang Li, Ren Ma, Mingzhang Zheng, Bill Qian, Yanjun Shao, Niklas Muennighoff, Yizhe Zhang, Binyuan Hui, Junyang Lin, Robert Brennan, Hao Peng, Heng Ji, Graham Neubig
  - **Published**: 2024-07-23
  - **Link**: http://arxiv.org/abs/2407.16741v3
  
  
- **Title**: LAMBDA: A Large Model Based Data Agent
  - **Authors**: Maojun Sun, Ruijian Han, Binyan Jiang, Houduo Qi, Defeng Sun, Yancheng Yuan, Jian Huang
  - **Published**: 2024-07-24
  - **Link**: http://arxiv.org/abs/2407.17535v3
  
  
- **Title**: AppWorld: A Controllable World of Apps and People for Benchmarking Interactive Coding Agents
  - **Authors**: Harsh Trivedi, Tushar Khot, Mareike Hartmann, Ruskin Manku, Vinty Dong, Edward Li, Shashank Gupta, Ashish Sabharwal, Niranjan Balasubramanian
  - **Published**: 2024-07-26
  - **Link**: http://arxiv.org/abs/2407.18901v1
  
  
- **Title**: From LLMs to LLM-based Agents for Software Engineering: A Survey of Current, Challenges and Future
  - **Authors**: Haolin Jin, Linghan Huang, Haipeng Cai, Jun Yan, Bo Li, Huaming Chen
  - **Published**: 2024-08-05
  - **Link**: http://arxiv.org/abs/2408.02479v2
  
  
- **Title**: Text2BIM: Generating Building Models Using a Large Language Model-based Multi-Agent Framework
  - **Authors**: Changyu Du, Sebastian Esser, Stavros Nousias, André Borrmann
  - **Published**: 2024-08-15
  - **Link**: http://arxiv.org/abs/2408.08054v2
  
  
- **Title**: HyperAgent: Generalist Software Engineering Agents to Solve Coding Tasks at Scale
  - **Authors**: Huy Nhat Phan, Tien N. Nguyen, Phong X. Nguyen, Nghi D. Q. Bui
  - **Published**: 2024-09-09
  - **Link**: http://arxiv.org/abs/2409.16299v2
  
  
- **Title**: Agents in Software Engineering: Survey, Landscape, and Vision
  - **Authors**: Yanlin Wang, Wanjun Zhong, Yanxian Huang, Ensheng Shi, Min Yang, Jiachi Chen, Hui Li, Yuchi Ma, Qianxiang Wang, Zibin Zheng
  - **Published**: 2024-09-13
  - **Link**: http://arxiv.org/abs/2409.09030v2
  
  
- **Title**: AutoSafeCoder: A Multi-Agent Framework for Securing LLM Code Generation through Static Analysis and Fuzz Testing
  - **Authors**: Ana Nunez, Nafis Tanveer Islam, Sumit Kumar Jha, Peyman Najafirad
  - **Published**: 2024-09-16
  - **Link**: http://arxiv.org/abs/2409.10737v2
  
  
- **Title**: MOSS: Enabling Code-Driven Evolution and Context Management for AI Agents
  - **Authors**: Ming Zhu, Yi Zhou
  - **Published**: 2024-09-24
  - **Link**: http://arxiv.org/abs/2409.16120v1
  
  
- **Title**: TRANSAGENT: An LLM-Based Multi-Agent System for Code Translation
  - **Authors**: Zhiqiang Yuan, Weitong Chen, Hanlin Wang, Kai Yu, Xin Peng, Yiling Lou
  - **Published**: 2024-09-30
  - **Link**: http://arxiv.org/abs/2409.19894v2
  
  
- **Title**: RGD: Multi-LLM Based Agent Debugger via Refinement and Generation Guidance
  - **Authors**: Haolin Jin, Zechao Sun, Huaming Chen
  - **Published**: 2024-10-02
  - **Link**: http://arxiv.org/abs/2410.01242v2
  
  
- **Title**: Towards Exception Safety Code Generation with Intermediate Representation Agents Framework
  - **Authors**: Xuanming Zhang, Yuxuan Chen, Yuan Yuan, Minlie Huang
  - **Published**: 2024-10-09
  - **Link**: http://arxiv.org/abs/2410.06949v3
  
  
- **Title**: Agents4PLC: Automating Closed-loop PLC Code Generation and Verification in Industrial Control Systems using LLM-based Agents
  - **Authors**: Zihan Liu, Ruinan Zeng, Dongxia Wang, Gengyun Peng, Jingyi Wang, Qiang Liu, Peiyu Liu, Wenhai Wang
  - **Published**: 2024-10-18
  - **Link**: http://arxiv.org/abs/2410.14209v2
  
  
- **Title**: Self-Evolving Multi-Agent Collaboration Networks for Software Development
  - **Authors**: Yue Hu, Yuzhu Cai, Yaxin Du, Xinyu Zhu, Xiangrui Liu, Zijie Yu, Yuchen Hou, Shuo Tang, Siheng Chen
  - **Published**: 2024-10-22
  - **Link**: http://arxiv.org/abs/2410.16946v1
  
  
- **Title**: SELA: Tree-Search Enhanced LLM Agents for Automated Machine Learning
  - **Authors**: Yizhou Chi, Yizhang Lin, Sirui Hong, Duyi Pan, Yaying Fei, Guanghao Mei, Bangbang Liu, Tianqi Pang, Jacky Kwok, Ceyao Zhang, Bang Liu, Chenglin Wu
  - **Published**: 2024-10-22
  - **Link**: http://arxiv.org/abs/2410.17238v1
  
  
- **Title**: MaCTG: Multi-Agent Collaborative Thought Graph for Automatic Programming
  - **Authors**: Zixiao Zhao, Jing Sun, Zhe Hou, Zhiyuan Wei, Cheng-Hao Cai, Miao Qiao, Jin Song Dong
  - **Published**: 2024-10-25
  - **Link**: http://arxiv.org/abs/2410.19245v2
  
  
- **Title**: SceneGenAgent: Precise Industrial Scene Generation with Coding Agent
  - **Authors**: Xiao Xia, Dan Zhang, Zibo Liao, Zhenyu Hou, Tianrui Sun, Jing Li, Ling Fu, Yuxiao Dong
  - **Published**: 2024-10-29
  - **Link**: http://arxiv.org/abs/2410.21909v3
  
  
- **Title**: GIS Copilot: Towards an Autonomous GIS Agent for Spatial Analysis
  - **Authors**: Temitope Akinboyewa, Zhenlong Li, Huan Ning, M. Naser Lessani
  - **Published**: 2024-11-05
  - **Link**: http://arxiv.org/abs/2411.03205v4
  
  
- **Title**: Human-In-the-Loop Software Development Agents
  - **Authors**: Wannita Takerngsaksiri, Jirat Pasuksmit, Patanamon Thongtanunam, Chakkrit Tantithamthavorn, Ruixiong Zhang, Fan Jiang, Jing Li, Evan Cook, Kun Chen, Ming Wu
  - **Published**: 2024-11-19
  - **Link**: http://arxiv.org/abs/2411.12924v2
  
  
- **Title**: Beyond pip install: Evaluating LLM Agents for the Automated Installation of Python Projects
  - **Authors**: Louis Milliken, Sungmin Kang, Shin Yoo
  - **Published**: 2024-12-09
  - **Link**: http://arxiv.org/abs/2412.06294v1
  
  
- **Title**: CoopetitiveV: Leveraging LLM-powered Coopetitive Multi-Agent Prompting for High-quality Verilog Generation
  - **Authors**: Zhendong Mi, Renming Zheng, Haowen Zhong, Yue Sun, Seth Kneeland, Sayan Moitra, Ken Kutzer, Zhaozhuo Xu Shaoyi Huang
  - **Published**: 2024-12-15
  - **Link**: http://arxiv.org/abs/2412.11014v2
  
  
- **Title**: Seeker: Towards Exception Safety Code Generation with Intermediate Language Agents Framework
  - **Authors**: Xuanming Zhang, Yuxuan Chen, Yiming Zheng, Zhexin Zhang, Yuan Yuan, Minlie Huang
  - **Published**: 2024-12-16
  - **Link**: http://arxiv.org/abs/2412.11713v1
  
  
- **Title**: CodeCoR: An LLM-Based Self-Reflective Multi-Agent Framework for Code Generation
  - **Authors**: Ruwei Pan, Hongyu Zhang, Chao Liu
  - **Published**: 2025-01-14
  - **Link**: http://arxiv.org/abs/2501.07811v1
  
  
- **Title**: QualityFlow: An Agentic Workflow for Program Synthesis Controlled by LLM Quality Checks
  - **Authors**: Yaojie Hu, Qiang Zhou, Qihong Chen, Xiaopeng Li, Linbo Liu, Dejiao Zhang, Amit Kachroo, Talha Oz, Omer Tripp
  - **Published**: 2025-01-20
  - **Link**: http://arxiv.org/abs/2501.17167v2
  
  
- **Title**: Autonomous Legacy Web Application Upgrades Using a Multi-Agent System
  - **Authors**: Valtteri Ala-Salmi, Zeeshan Rasheed, Abdul Malik Sami, Zheying Zhang, Kai-Kristian Kemell, Jussi Rasku, Shahbaz Siddeeq, Mika Saari, Pekka Abrahamsson
  - **Published**: 2025-01-31
  - **Link**: http://arxiv.org/abs/2501.19204v1
  
  
- **Title**: Agentic Bug Reproduction for Effective Automated Program Repair at Google
  - **Authors**: Runxiang Cheng, Michele Tufano, Jürgen Cito, José Cambronero, Pat Rondon, Renyao Wei, Aaron Sun, Satish Chandra
  - **Published**: 2025-02-03
  - **Link**: http://arxiv.org/abs/2502.01821v2
  
  
- **Title**: Every Software as an Agent: Blueprint and Case Study
  - **Authors**: Mengwei Xu
  - **Published**: 2025-02-07
  - **Link**: http://arxiv.org/abs/2502.04747v1
  
  
- **Title**: CSR-Bench: Benchmarking LLM Agents in Deployment of Computer Science Research Repositories
  - **Authors**: Yijia Xiao, Runhui Wang, Luyang Kong, Davor Golac, Wei Wang
  - **Published**: 2025-02-10
  - **Link**: http://arxiv.org/abs/2502.06111v2
  
  
- **Title**: Agentic AI Software Engineers: Programming with Trust
  - **Authors**: Abhik Roychoudhury, Corina Pasareanu, Michael Pradel, Baishakhi Ray
  - **Published**: 2025-02-19
  - **Link**: http://arxiv.org/abs/2502.13767v3
  
  
- **Title**: Nexus: A Lightweight and Scalable Multi-Agent Framework for Complex Tasks Automation
  - **Authors**: Humza Sami, Mubashir ul Islam, Samy Charas, Asav Gandhi, Pierre-Emmanuel Gaillardon, Valerio Tenace
  - **Published**: 2025-02-26
  - **Link**: http://arxiv.org/abs/2502.19091v1
  
  
- **Title**: Fully Autonomous Programming using Iterative Multi-Agent Debugging with Large Language Models
  - **Authors**: Anastasiia Grishina, Vadim Liventsev, Aki Härmä, Leon Moonen
  - **Published**: 2025-03-10
  - **Link**: http://arxiv.org/abs/2503.07693v1
  
  
- **Title**: DARS: Dynamic Action Re-Sampling to Enhance Coding Agent Performance by Adaptive Tree Traversal
  - **Authors**: Vaibhav Aggarwal, Ojasv Kamal, Abhinav Japesh, Zhijing Jin, Bernhard Schölkopf
  - **Published**: 2025-03-18
  - **Link**: http://arxiv.org/abs/2503.14269v1
  
  
- **Title**: MANTRA: Enhancing Automated Method-Level Refactoring with Contextual RAG and Multi-Agent LLM Collaboration
  - **Authors**: Yisen Xu, Feng Lin, Jinqiu Yang, Tse-Hsun, Chen, Nikolaos Tsantalis
  - **Published**: 2025-03-18
  - **Link**: http://arxiv.org/abs/2503.14340v2
  
  
- **Title**: Unlocking LLM Repair Capabilities in Low-Resource Programming Languages Through Cross-Language Translation and Multi-Agent Refinement
  - **Authors**: Wenqiang Luo, Jacky Wai Keung, Boyang Yang, Jacques Klein, Tegawende F. Bissyande, Haoye Tian, Bach Le
  - **Published**: 2025-03-28
  - **Link**: http://arxiv.org/abs/2503.22512v3
  
  
- **Title**: Thinking Longer, Not Larger: Enhancing Software Engineering Agents via Scaling Test-Time Compute
  - **Authors**: Yingwei Ma, Yongbin Li, Yihong Dong, Xue Jiang, Rongyu Cao, Jue Chen, Fei Huang, Binhua Li
  - **Published**: 2025-03-31
  - **Link**: http://arxiv.org/abs/2503.23803v2
  
  
- **Title**: SciReplicate-Bench: Benchmarking LLMs in Agent-driven Algorithmic Reproduction from Research Papers
  - **Authors**: Yanzheng Xiang, Hanqi Yan, Shuyin Ouyang, Lin Gui, Yulan He
  - **Published**: 2025-03-31
  - **Link**: http://arxiv.org/abs/2504.00255v1
  
  
- **Title**: AdaCoder: An Adaptive Planning and Multi-Agent Framework for Function-Level Code Generation
  - **Authors**: Yueheng Zhu, Chao Liu, Xuan He, Xiaoxue Ren, Zhongxin Liu, Ruwei Pan, Hongyu Zhang
  - **Published**: 2025-04-05
  - **Link**: http://arxiv.org/abs/2504.04220v1
  
  
- **Title**: CodeVisionary: An Agent-based Framework for Evaluating Large Language Models in Code Generation
  - **Authors**: Xinchen Wang, Pengfei Gao, Chao Peng, Ruida Hu, Cuiyun Gao
  - **Published**: 2025-04-18
  - **Link**: http://arxiv.org/abs/2504.13472v1
  
  
- **Title**: Human-In-The-Loop Software Development Agents: Challenges and Future Directions
  - **Authors**: Jirat Pasuksmit, Wannita Takerngsaksiri, Patanamon Thongtanunam, Chakkrit Tantithamthavorn, Ruixiong Zhang, Shiyan Wang, Fan Jiang, Jing Li, Evan Cook, Kun Chen, Ming Wu
  - **Published**: 2025-04-25
  - **Link**: http://arxiv.org/abs/2506.11009v1
  
  
- **Title**: AutoP2C: An LLM-Based Agent Framework for Code Repository Generation from Multimodal Content in Academic Papers
  - **Authors**: Zijie Lin, Yiqing Shen, Qilin Cai, He Sun, Jinrui Zhou, Mingjun Xiao
  - **Published**: 2025-04-28
  - **Link**: http://arxiv.org/abs/2504.20115v2
  
  
- **Title**: ResearchCodeAgent: An LLM Multi-Agent System for Automated Codification of Research Methodologies
  - **Authors**: Shubham Gandhi, Dhruv Shah, Manasi Patwardhan, Lovekesh Vig, Gautam Shroff
  - **Published**: 2025-04-28
  - **Link**: http://arxiv.org/abs/2504.20117v2
  
  
- **Title**: Enhancing LLM Code Generation: A Systematic Evaluation of Multi-Agent Collaboration and Runtime Debugging for Improved Accuracy, Reliability, and Latency
  - **Authors**: Nazmus Ashrafi, Salah Bouktif, Mohammed Mediani
  - **Published**: 2025-05-04
  - **Link**: http://arxiv.org/abs/2505.02133v1
  
  
- **Title**: MARCO: Multi-Agent Code Optimization with Real-Time Knowledge Integration for High-Performance Computing
  - **Authors**: Asif Rahman, Veljko Cvetkovic, Kathleen Reece, Aidan Walters, Yasir Hassan, Aneesh Tummeti, Bryan Torres, Denise Cooney, Margaret Ellis, Dimitrios S. Nikolopoulos
  - **Published**: 2025-05-06
  - **Link**: http://arxiv.org/abs/2505.03906v3
  
  
- **Title**: CompileAgent: Automated Real-World Repo-Level Compilation with Tool-Integrated LLM-based Agent System
  - **Authors**: Li Hu, Guoqiang Chen, Xiuwei Shang, Shaoyin Cheng, Benlong Wu, Gangyang Li, Xu Zhu, Weiming Zhang, Nenghai Yu
  - **Published**: 2025-05-07
  - **Link**: http://arxiv.org/abs/2505.04254v1
  
  
- **Title**: Software Development Life Cycle Perspective: A Survey of Benchmarks for Code Large Language Models and Agents
  - **Authors**: Kaixin Wang, Tianlin Li, Xiaoyu Zhang, Chong Wang, Weisong Sun, Yang Liu, Bin Shi
  - **Published**: 2025-05-08
  - **Link**: http://arxiv.org/abs/2505.05283v2
  
  
- **Title**: Guided Search Strategies in Non-Serializable Environments with Applications to Software Engineering Agents
  - **Authors**: Karina Zainullina, Alexander Golubev, Maria Trofimova, Sergei Polezhaev, Ibragim Badertdinov, Daria Litvintseva, Simon Karasik, Filipp Fisin, Sergei Skvortsov, Maksim Nekrashevich, Anton Shevtsov, Boris Yangel
  - **Published**: 2025-05-19
  - **Link**: http://arxiv.org/abs/2505.13652v1
  
  
- **Title**: Large Language Model-Powered Agent for C to Rust Code Translation
  - **Authors**: HoHyun Sim, Hyeonjoong Cho, Yeonghyeon Go, Zhoulai Fu, Ali Shokri, Binoy Ravindran
  - **Published**: 2025-05-21
  - **Link**: http://arxiv.org/abs/2505.15858v2
  
  
- **Title**: SEW: Self-Evolving Agentic Workflows for Automated Code Generation
  - **Authors**: Siwei Liu, Jinyuan Fang, Han Zhou, Yingxu Wang, Zaiqiao Meng
  - **Published**: 2025-05-24
  - **Link**: http://arxiv.org/abs/2505.18646v1
  
  
- **Title**: Vibe Coding vs. Agentic Coding: Fundamentals and Practical Implications of Agentic AI
  - **Authors**: Ranjan Sapkota, Konstantinos I. Roumeliotis, Manoj Karkee
  - **Published**: 2025-05-26
  - **Link**: http://arxiv.org/abs/2505.19443v1
  
  
- **Title**: CXXCrafter: An LLM-Based Agent for Automated C/C++ Open Source Software Building
  - **Authors**: Zhengmin Yu, Yuan Zhang, Ming Wen, Yinan Nie, Wenhui Zhang, Min Yang
  - **Published**: 2025-05-27
  - **Link**: http://arxiv.org/abs/2505.21069v1
  
  
- **Title**: GUARD:Dual-Agent based Backdoor Defense on Chain-of-Thought in Neural Code Generation
  - **Authors**: Naizhu Jin, Zhong Li, Tian Zhang, Qingkai Zeng
  - **Published**: 2025-05-27
  - **Link**: http://arxiv.org/abs/2505.21425v2
  
  
- **Title**: Co-Saving: Resource Aware Multi-Agent Collaboration for Software Development
  - **Authors**: Rennai Qiu, Chen Qian, Ran Li, Yufan Dang, Weize Chen, Cheng Yang, Yingli Zhang, Ye Tian, Xuantang Xiong, Lei Han, Zhiyuan Liu, Maosong Sun
  - **Published**: 2025-05-28
  - **Link**: http://arxiv.org/abs/2505.21898v1
  
  
- **Title**: Lessons Learned: A Multi-Agent Framework for Code LLMs to Learn and Improve
  - **Authors**: Yuanzhe Liu, Ryan Deng, Tim Kaler, Xuhao Chen, Charles E. Leiserson, Yao Ma, Jie Chen
  - **Published**: 2025-05-29
  - **Link**: http://arxiv.org/abs/2505.23946v1
  
  
- **Title**: Understanding Software Engineering Agents Through the Lens of Traceability: An Empirical Study
  - **Authors**: Ira Ceka, Saurabh Pujar, Shyam Ramji, Luca Buratti, Gail Kaiser, Baishakhi Ray
  - **Published**: 2025-06-10
  - **Link**: http://arxiv.org/abs/2506.08311v1
  
  
- **Title**: ReVeal: Self-Evolving Code Agents via Iterative Generation-Verification
  - **Authors**: Yiyang Jin, Kunzhao Xu, Hang Li, Xueting Han, Yanmin Zhou, Cheng Li, Jing Bai
  - **Published**: 2025-06-13
  - **Link**: http://arxiv.org/abs/2506.11442v1
  
  
- **Title**: SWE-Bench-CL: Continual Learning for Coding Agents
  - **Authors**: Thomas Joshi, Shayan Chowdhury, Fatih Uysal
  - **Published**: 2025-06-13
  - **Link**: http://arxiv.org/abs/2507.00014v1
  
  
- **Title**: Unified Software Engineering agent as AI Software Engineer
  - **Authors**: Leonhard Applis, Yuntong Zhang, Shanchao Liang, Nan Jiang, Lin Tan, Abhik Roychoudhury
  - **Published**: 2025-06-17
  - **Link**: http://arxiv.org/abs/2506.14683v1
  
  
- **Title**: LMR-BENCH: Evaluating LLM Agent's Ability on Reproducing Language Modeling Research
  - **Authors**: Shuo Yan, Ruochen Li, Ziming Luo, Zimu Wang, Daoyang Li, Liqiang Jing, Kaiyu He, Peilin Wu, George Michalopoulos, Yue Zhang, Ziyang Zhang, Mian Zhang, Zhiyu Chen, Xinya Du
  - **Published**: 2025-06-19
  - **Link**: http://arxiv.org/abs/2506.17335v1
  
  
- **Title**: LLM-based Multi-Agent System for Intelligent Refactoring of Haskell Code
  - **Authors**: Shahbaz Siddeeq, Muhammad Waseem, Zeeshan Rasheed, Md Mahade Hasan, Jussi Rasku, Mika Saari, Henri Terho, Kalle Makela, Kai-Kristian Kemell, Pekka Abrahamsson
  - **Published**: 2025-06-24
  - **Link**: http://arxiv.org/abs/2506.19481v1
  
  
- **Title**: Context-Aware Code Wiring Recommendation with LLM-based Agent
  - **Authors**: Taiming Wang, Yanjie Jiang, Chunhao Dong, Yuxia Zhang, Hui Liu
  - **Published**: 2025-07-02
  - **Link**: http://arxiv.org/abs/2507.01315v1
  
  
### Testing and Quality Assurance
- **Title**: ChatDev: Communicative Agents for Software Development
  - **Authors**: Chen Qian, Wei Liu, Hongzhang Liu, Nuo Chen, Yufan Dang, Jiahao Li, Cheng Yang, Weize Chen, Yusheng Su, Xin Cong, Juyuan Xu, Dahai Li, Zhiyuan Liu, Maosong Sun
  - **Published**: 2023-07-16
  - **Link**: http://arxiv.org/abs/2307.07924v5
  
  
- **Title**: Experimenting with Multi-Agent Software Development: Towards a Unified Platform
  - **Authors**: Malik Abdul Sami, Muhammad Waseem, Zeeshan Rasheed, Mika Saari, Kari Systä, Pekka Abrahamsson
  - **Published**: 2024-06-08
  - **Link**: http://arxiv.org/abs/2406.05381v1
  
  
- **Title**: Agents in Software Engineering: Survey, Landscape, and Vision
  - **Authors**: Yanlin Wang, Wanjun Zhong, Yanxian Huang, Ensheng Shi, Min Yang, Jiachi Chen, Hui Li, Yuchi Ma, Qianxiang Wang, Zibin Zheng
  - **Published**: 2024-09-13
  - **Link**: http://arxiv.org/abs/2409.09030v2
  
  
- **Title**: Evaluating Software Development Agents: Patch Patterns, Code Quality, and Issue Complexity in Real-World GitHub Scenarios
  - **Authors**: Zhi Chen, Lingxiao Jiang
  - **Published**: 2024-10-16
  - **Link**: http://arxiv.org/abs/2410.12468v2
  
  
- **Title**: Agents4PLC: Automating Closed-loop PLC Code Generation and Verification in Industrial Control Systems using LLM-based Agents
  - **Authors**: Zihan Liu, Ruinan Zeng, Dongxia Wang, Gengyun Peng, Jingyi Wang, Qiang Liu, Peiyu Liu, Wenhai Wang
  - **Published**: 2024-10-18
  - **Link**: http://arxiv.org/abs/2410.14209v2
  
  
- **Title**: Watson: A Cognitive Observability Framework for the Reasoning of LLM-Powered Agents
  - **Authors**: Benjamin Rombaut, Sogol Masoumzadeh, Kirill Vasilevski, Dayi Lin, Ahmed E. Hassan
  - **Published**: 2024-11-05
  - **Link**: http://arxiv.org/abs/2411.03455v2
  
  
- **Title**: QualityFlow: An Agentic Workflow for Program Synthesis Controlled by LLM Quality Checks
  - **Authors**: Yaojie Hu, Qiang Zhou, Qihong Chen, Xiaopeng Li, Linbo Liu, Dejiao Zhang, Amit Kachroo, Talha Oz, Omer Tripp
  - **Published**: 2025-01-20
  - **Link**: http://arxiv.org/abs/2501.17167v2
  
  
- **Title**: Software Development Life Cycle Perspective: A Survey of Benchmarks for Code Large Language Models and Agents
  - **Authors**: Kaixin Wang, Tianlin Li, Xiaoyu Zhang, Chong Wang, Weisong Sun, Yang Liu, Bin Shi
  - **Published**: 2025-05-08
  - **Link**: http://arxiv.org/abs/2505.05283v2
  
  
- **Title**: Understanding Software Engineering Agents Through the Lens of Traceability: An Empirical Study
  - **Authors**: Ira Ceka, Saurabh Pujar, Shyam Ramji, Luca Buratti, Gail Kaiser, Baishakhi Ray
  - **Published**: 2025-06-10
  - **Link**: http://arxiv.org/abs/2506.08311v1
  
  
- **Title**: ReVeal: Self-Evolving Code Agents via Iterative Generation-Verification
  - **Authors**: Yiyang Jin, Kunzhao Xu, Hang Li, Xueting Han, Yanmin Zhou, Cheng Li, Jing Bai
  - **Published**: 2025-06-13
  - **Link**: http://arxiv.org/abs/2506.11442v1
  
  
- **Title**: Unified Software Engineering agent as AI Software Engineer
  - **Authors**: Leonhard Applis, Yuntong Zhang, Shanchao Liang, Nan Jiang, Lin Tan, Abhik Roychoudhury
  - **Published**: 2025-06-17
  - **Link**: http://arxiv.org/abs/2506.14683v1
  
  
### Maintenance and Evolution

- **Title**: Autonomous Agents in Software Development: A Vision Paper
  - **Authors**: Zeeshan Rasheed, Muhammad Waseem, Kai-Kristian Kemell, Wang Xiaofeng, Anh Nguyen Duc, Kari Systä, Pekka Abrahamsson
  - **Published**: 2023-11-30
  - **Link**: http://arxiv.org/abs/2311.18440v1
  
  
- **Title**: Exploring LLM-based Agents for Root Cause Analysis
  - **Authors**: Devjeet Roy, Xuchao Zhang, Rashi Bhave, Chetan Bansal, Pedro Las-Casas, Rodrigo Fonseca, Saravan Rajmohan
  - **Published**: 2024-03-07
  - **Link**: http://arxiv.org/abs/2403.04123v1
  
  
- **Title**: RepairAgent: An Autonomous, LLM-Based Agent for Program Repair
  - **Authors**: Islem Bouzenia, Premkumar Devanbu, Michael Pradel
  - **Published**: 2024-03-25
  - **Link**: http://arxiv.org/abs/2403.17134v2
  
  
- **Title**: Agent-Driven Automatic Software Improvement
  - **Authors**: Fernando Vallecillos Ruiz
  - **Published**: 2024-06-24
  - **Link**: http://arxiv.org/abs/2406.16739v1
  
  
- **Title**: From LLMs to LLM-based Agents for Software Engineering: A Survey of Current, Challenges and Future
  - **Authors**: Haolin Jin, Linghan Huang, Haipeng Cai, Jun Yan, Bo Li, Huaming Chen
  - **Published**: 2024-08-05
  - **Link**: http://arxiv.org/abs/2408.02479v2
  
  
- **Title**: Agents in Software Engineering: Survey, Landscape, and Vision
  - **Authors**: Yanlin Wang, Wanjun Zhong, Yanxian Huang, Ensheng Shi, Min Yang, Jiachi Chen, Hui Li, Yuchi Ma, Qianxiang Wang, Zibin Zheng
  - **Published**: 2024-09-13
  - **Link**: http://arxiv.org/abs/2409.09030v2
  
  
- **Title**: Distributed Approach to Haskell Based Applications Refactoring with LLMs Based Multi-Agent Systems
  - **Authors**: Shahbaz Siddeeq, Zeeshan Rasheed, Malik Abdul Sami, Mahade Hasan, Muhammad Waseem, Jussi Rasku, Mika Saari, Kai-Kristian Kemell, Pekka Abrahamsson
  - **Published**: 2025-02-11
  - **Link**: http://arxiv.org/abs/2502.07928v1
  
  
- **Title**: Software Development Life Cycle Perspective: A Survey of Benchmarks for Code Large Language Models and Agents
  - **Authors**: Kaixin Wang, Tianlin Li, Xiaoyu Zhang, Chong Wang, Weisong Sun, Yang Liu, Bin Shi
  - **Published**: 2025-05-08
  - **Link**: http://arxiv.org/abs/2505.05283v2
  
  
- **Title**: Unified Software Engineering agent as AI Software Engineer
  - **Authors**: Leonhard Applis, Yuntong Zhang, Shanchao Liang, Nan Jiang, Lin Tan, Abhik Roychoudhury
  - **Published**: 2025-06-17
  - **Link**: http://arxiv.org/abs/2506.14683v1
  
  
- **Title**: LLM-based Multi-Agent System for Intelligent Refactoring of Haskell Code
  - **Authors**: Shahbaz Siddeeq, Muhammad Waseem, Zeeshan Rasheed, Md Mahade Hasan, Jussi Rasku, Mika Saari, Henri Terho, Kalle Makela, Kai-Kristian Kemell, Pekka Abrahamsson
  - **Published**: 2025-06-24
  - **Link**: http://arxiv.org/abs/2506.19481v1
  
  
## Multi-Agent Systems and Collaboration
### Agent Architecture and Framework Design
- **Title**: Towards Autonomous Testing Agents via Conversational Large Language Models
  - **Authors**: Robert Feldt, Sungmin Kang, Juyeon Yoon, Shin Yoo
  - **Published**: 2023-06-08
  - **Link**: http://arxiv.org/abs/2306.05152v2
  
  
- **Title**: ChatDev: Communicative Agents for Software Development
  - **Authors**: Chen Qian, Wei Liu, Hongzhang Liu, Nuo Chen, Yufan Dang, Jiahao Li, Cheng Yang, Weize Chen, Yusheng Su, Xin Cong, Juyuan Xu, Dahai Li, Zhiyuan Liu, Maosong Sun
  - **Published**: 2023-07-16
  - **Link**: http://arxiv.org/abs/2307.07924v5
  
  
- **Title**: Balancing Autonomy and Alignment: A Multi-Dimensional Taxonomy for Autonomous LLM-powered Multi-Agent Architectures
  - **Authors**: Thorsten Händler
  - **Published**: 2023-10-05
  - **Link**: http://arxiv.org/abs/2310.03659v1
  
  
- **Title**: Towards Responsible Generative AI: A Reference Architecture for Designing Foundation Model based Agents
  - **Authors**: Qinghua Lu, Liming Zhu, Xiwei Xu, Zhenchang Xing, Stefan Harrer, Jon Whittle
  - **Published**: 2023-11-22
  - **Link**: http://arxiv.org/abs/2311.13148v3
  
  
- **Title**: Experiential Co-Learning of Software-Developing Agents
  - **Authors**: Chen Qian, Yufan Dang, Jiahao Li, Wei Liu, Zihao Xie, Yifei Wang, Weize Chen, Cheng Yang, Xin Cong, Xiaoyin Che, Zhiyuan Liu, Maosong Sun
  - **Published**: 2023-12-28
  - **Link**: http://arxiv.org/abs/2312.17025v3
  
  
- **Title**: CodeAgent: Enhancing Code Generation with Tool-Integrated Agent Systems for Real-World Repo-level Coding Challenges
  - **Authors**: Kechi Zhang, Jia Li, Ge Li, Xianjie Shi, Zhi Jin
  - **Published**: 2024-01-14
  - **Link**: http://arxiv.org/abs/2401.07339v2
  
  
- **Title**: CodePori: Large-Scale System for Autonomous Software Development Using Multi-Agent Technology
  - **Authors**: Zeeshan Rasheed, Malik Abdul Sami, Kai-Kristian Kemell, Muhammad Waseem, Mika Saari, Kari Systä, Pekka Abrahamsson
  - **Published**: 2024-02-02
  - **Link**: http://arxiv.org/abs/2402.01411v2
  
  
- **Title**: CodeAgent: Autonomous Communicative Agents for Code Review
  - **Authors**: Xunzhu Tang, Kisub Kim, Yewei Song, Cedric Lothritz, Bei Li, Saad Ezzini, Haoye Tian, Jacques Klein, Tegawende F. Bissyande
  - **Published**: 2024-02-03
  - **Link**: http://arxiv.org/abs/2402.02172v5
  
  
- **Title**: LLM-based agents for automating the enhancement of user story quality: An early report
  - **Authors**: Zheying Zhang, Maruf Rayhan, Tomas Herda, Manuel Goisauf, Pekka Abrahamsson
  - **Published**: 2024-03-14
  - **Link**: http://arxiv.org/abs/2403.09442v1
  
  
- **Title**: SOEN-101: Code Generation by Emulating Software Process Models Using Large Language Model Agents
  - **Authors**: Feng Lin, Dong Jae Kim, Tse-Husn, Chen
  - **Published**: 2024-03-23
  - **Link**: http://arxiv.org/abs/2403.15852v2
  
  
- **Title**: RepairAgent: An Autonomous, LLM-Based Agent for Program Repair
  - **Authors**: Islem Bouzenia, Premkumar Devanbu, Michael Pradel
  - **Published**: 2024-03-25
  - **Link**: http://arxiv.org/abs/2403.17134v2
  
  
- **Title**: MAGIS: LLM-Based Multi-Agent Framework for GitHub Issue Resolution
  - **Authors**: Wei Tao, Yucheng Zhou, Yanlin Wang, Wenqiang Zhang, Hongyu Zhang, Yu Cheng
  - **Published**: 2024-03-26
  - **Link**: http://arxiv.org/abs/2403.17927v2
  
  
- **Title**: Large Language Model Evaluation Via Multi AI Agents: Preliminary results
  - **Authors**: Zeeshan Rasheed, Muhammad Waseem, Kari Systä, Pekka Abrahamsson
  - **Published**: 2024-04-01
  - **Link**: http://arxiv.org/abs/2404.01023v1
  
  
- **Title**: Self-Organized Agents: A LLM Multi-Agent Framework toward Ultra Large-Scale Code Generation and Optimization
  - **Authors**: Yoichi Ishibashi, Yoshimasa Nishimura
  - **Published**: 2024-04-02
  - **Link**: http://arxiv.org/abs/2404.02183v1
  
  
- **Title**: Concept-Guided LLM Agents for Human-AI Safety Codesign
  - **Authors**: Florian Geissler, Karsten Roscher, Mario Trapp
  - **Published**: 2024-04-03
  - **Link**: http://arxiv.org/abs/2404.15317v1
  
  
- **Title**: LLM-Based Multi-Agent Systems for Software Engineering: Literature Review, Vision and the Road Ahead
  - **Authors**: Junda He, Christoph Treude, David Lo
  - **Published**: 2024-04-07
  - **Link**: http://arxiv.org/abs/2404.04834v3
  
  
- **Title**: AI2Apps: A Visual IDE for Building LLM-based AI Agent Applications
  - **Authors**: Xin Pang, Zhucong Li, Jiaxiang Chen, Yuan Cheng, Yinghui Xu, Yuan Qi
  - **Published**: 2024-04-07
  - **Link**: http://arxiv.org/abs/2404.04902v1
  
  
- **Title**: A Unified Debugging Approach via LLM-Based Multi-Agent Synergy
  - **Authors**: Cheryl Lee, Chunqiu Steven Xia, Longji Yang, Jen-tse Huang, Zhouruixin Zhu, Lingming Zhang, Michael R. Lyu
  - **Published**: 2024-04-26
  - **Link**: http://arxiv.org/abs/2404.17153v2
  
  
- **Title**: MARE: Multi-Agents Collaboration Framework for Requirements Engineering
  - **Authors**: Dongming Jin, Zhi Jin, Xiaohong Chen, Chunhui Wang
  - **Published**: 2024-05-06
  - **Link**: http://arxiv.org/abs/2405.03256v1
  
  
- **Title**: Iterative Experience Refinement of Software-Developing Agents
  - **Authors**: Chen Qian, Jiahao Li, Yufan Dang, Wei Liu, YiFei Wang, Zihao Xie, Weize Chen, Cheng Yang, Yingli Zhang, Zhiyuan Liu, Maosong Sun
  - **Published**: 2024-05-07
  - **Link**: http://arxiv.org/abs/2405.04219v1
  
  
- **Title**: DepsRAG: Towards Agentic Reasoning and Planning for Software Dependency Management
  - **Authors**: Mohannad Alhanahnah, Yazan Boshmaf
  - **Published**: 2024-05-30
  - **Link**: http://arxiv.org/abs/2405.20455v5
  
  
- **Title**: HumanEvalComm: Benchmarking the Communication Competence of Code Generation for LLMs and LLM Agent
  - **Authors**: Jie JW Wu, Fatemeh H Fard
  - **Published**: 2024-05-31
  - **Link**: http://arxiv.org/abs/2406.00215v3
  
  
- **Title**: Experimenting with Multi-Agent Software Development: Towards a Unified Platform
  - **Authors**: Malik Abdul Sami, Muhammad Waseem, Zeeshan Rasheed, Mika Saari, Kari Systä, Pekka Abrahamsson
  - **Published**: 2024-06-08
  - **Link**: http://arxiv.org/abs/2406.05381v1
  
  
- **Title**: Multi-Agent Collaboration via Cross-Team Orchestration
  - **Authors**: Zhuoyun Du, Chen Qian, Wei Liu, Zihao Xie, YiFei Wang, Rennai Qiu, Yufan Dang, Weize Chen, Cheng Yang, Ye Tian, Xuantang Xiong, Lei Han
  - **Published**: 2024-06-13
  - **Link**: http://arxiv.org/abs/2406.08979v2
  
  
- **Title**: MASAI: Modular Architecture for Software-engineering AI Agents
  - **Authors**: Daman Arora, Atharv Sonwane, Nalin Wadhwa, Abhav Mehrotra, Saiteja Utpala, Ramakrishna Bairi, Aditya Kanade, Nagarajan Natarajan
  - **Published**: 2024-06-17
  - **Link**: http://arxiv.org/abs/2406.11638v1
  
  
- **Title**: OpenHands: An Open Platform for AI Software Developers as Generalist Agents
  - **Authors**: Xingyao Wang, Boxuan Li, Yufan Song, Frank F. Xu, Xiangru Tang, Mingchen Zhuge, Jiayi Pan, Yueqi Song, Bowen Li, Jaskirat Singh, Hoang H. Tran, Fuqiang Li, Ren Ma, Mingzhang Zheng, Bill Qian, Yanjun Shao, Niklas Muennighoff, Yizhe Zhang, Binyuan Hui, Junyang Lin, Robert Brennan, Hao Peng, Heng Ji, Graham Neubig
  - **Published**: 2024-07-23
  - **Link**: http://arxiv.org/abs/2407.16741v3
  
  
- **Title**: Building Living Software Systems with Generative & Agentic AI
  - **Authors**: Jules White
  - **Published**: 2024-08-03
  - **Link**: http://arxiv.org/abs/2408.01768v1
  
  
- **Title**: ReDel: A Toolkit for LLM-Powered Recursive Multi-Agent Systems
  - **Authors**: Andrew Zhu, Liam Dugan, Chris Callison-Burch
  - **Published**: 2024-08-05
  - **Link**: http://arxiv.org/abs/2408.02248v2
  
  
- **Title**: AutoGen Studio: A No-Code Developer Tool for Building and Debugging Multi-Agent Systems
  - **Authors**: Victor Dibia, Jingya Chen, Gagan Bansal, Suff Syed, Adam Fourney, Erkang Zhu, Chi Wang, Saleema Amershi
  - **Published**: 2024-08-09
  - **Link**: http://arxiv.org/abs/2408.15247v1
  
  
- **Title**: HyperAgent: Generalist Software Engineering Agents to Solve Coding Tasks at Scale
  - **Authors**: Huy Nhat Phan, Tien N. Nguyen, Phong X. Nguyen, Nghi D. Q. Bui
  - **Published**: 2024-09-09
  - **Link**: http://arxiv.org/abs/2409.16299v2
  
  
- **Title**: Think-on-Process: Dynamic Process Generation for Collaborative Development of Multi-Agent System
  - **Authors**: Leilei Lin, Yingming Zhou, Wenlong Chen, Chen Qian
  - **Published**: 2024-09-10
  - **Link**: http://arxiv.org/abs/2409.06568v1
  
  
- **Title**: Agents in Software Engineering: Survey, Landscape, and Vision
  - **Authors**: Yanlin Wang, Wanjun Zhong, Yanxian Huang, Ensheng Shi, Min Yang, Jiachi Chen, Hui Li, Yuchi Ma, Qianxiang Wang, Zibin Zheng
  - **Published**: 2024-09-13
  - **Link**: http://arxiv.org/abs/2409.09030v2
  
  
- **Title**: LLM-Agent-UMF: LLM-based Agent Unified Modeling Framework for Seamless Integration of Multi Active/Passive Core-Agents
  - **Authors**: Amine Ben Hassouna, Hana Chaari, Ines Belhaj
  - **Published**: 2024-09-17
  - **Link**: http://arxiv.org/abs/2409.11393v2
  
  
- **Title**: MOSS: Enabling Code-Driven Evolution and Context Management for AI Agents
  - **Authors**: Ming Zhu, Yi Zhou
  - **Published**: 2024-09-24
  - **Link**: http://arxiv.org/abs/2409.16120v1
  
  
- **Title**: TRANSAGENT: An LLM-Based Multi-Agent System for Code Translation
  - **Authors**: Zhiqiang Yuan, Weitong Chen, Hanlin Wang, Kai Yu, Xin Peng, Yiling Lou
  - **Published**: 2024-09-30
  - **Link**: http://arxiv.org/abs/2409.19894v2
  
  
- **Title**: Towards Exception Safety Code Generation with Intermediate Representation Agents Framework
  - **Authors**: Xuanming Zhang, Yuxuan Chen, Yuan Yuan, Minlie Huang
  - **Published**: 2024-10-09
  - **Link**: http://arxiv.org/abs/2410.06949v3
  
  
- **Title**: AFlow: Automating Agentic Workflow Generation
  - **Authors**: Jiayi Zhang, Jinyu Xiang, Zhaoyang Yu, Fengwei Teng, Xionghui Chen, Jiaqi Chen, Mingchen Zhuge, Xin Cheng, Sirui Hong, Jinlin Wang, Bingnan Zheng, Bang Liu, Yuyu Luo, Chenglin Wu
  - **Published**: 2024-10-14
  - **Link**: http://arxiv.org/abs/2410.10762v4
  
  
- **Title**: Self-Evolving Multi-Agent Collaboration Networks for Software Development
  - **Authors**: Yue Hu, Yuzhu Cai, Yaxin Du, Xinyu Zhu, Xiangrui Liu, Zijie Yu, Yuchen Hou, Shuo Tang, Siheng Chen
  - **Published**: 2024-10-22
  - **Link**: http://arxiv.org/abs/2410.16946v1
  
  
- **Title**: MaCTG: Multi-Agent Collaborative Thought Graph for Automatic Programming
  - **Authors**: Zixiao Zhao, Jing Sun, Zhe Hou, Zhiyuan Wei, Cheng-Hao Cai, Miao Qiao, Jin Song Dong
  - **Published**: 2024-10-25
  - **Link**: http://arxiv.org/abs/2410.19245v2
  
  
- **Title**: The BrowserGym Ecosystem for Web Agent Research
  - **Authors**: Thibault Le Sellier De Chezelles, Maxime Gasse, Alexandre Drouin, Massimo Caccia, Léo Boisvert, Megh Thakkar, Tom Marty, Rim Assouel, Sahar Omidi Shayegan, Lawrence Keunho Jang, Xing Han Lù, Ori Yoran, Dehan Kong, Frank F. Xu, Siva Reddy, Quentin Cappart, Graham Neubig, Ruslan Salakhutdinov, Nicolas Chapados, Alexandre Lacoste
  - **Published**: 2024-12-06
  - **Link**: http://arxiv.org/abs/2412.05467v4
  
  
- **Title**: Towards Modeling Human-Agentic Collaborative Workflows: A BPMN Extension
  - **Authors**: Adem Ait, Javier Luis Cánovas Izquierdo, Jordi Cabot
  - **Published**: 2024-12-08
  - **Link**: http://arxiv.org/abs/2412.05958v3
  
  
- **Title**: CoopetitiveV: Leveraging LLM-powered Coopetitive Multi-Agent Prompting for High-quality Verilog Generation
  - **Authors**: Zhendong Mi, Renming Zheng, Haowen Zhong, Yue Sun, Seth Kneeland, Sayan Moitra, Ken Kutzer, Zhaozhuo Xu Shaoyi Huang
  - **Published**: 2024-12-15
  - **Link**: http://arxiv.org/abs/2412.11014v2
  
  
- **Title**: CodeCoR: An LLM-Based Self-Reflective Multi-Agent Framework for Code Generation
  - **Authors**: Ruwei Pan, Hongyu Zhang, Chao Liu
  - **Published**: 2025-01-14
  - **Link**: http://arxiv.org/abs/2501.07811v1
  
  
- **Title**: Every Software as an Agent: Blueprint and Case Study
  - **Authors**: Mengwei Xu
  - **Published**: 2025-02-07
  - **Link**: http://arxiv.org/abs/2502.04747v1
  
  
- **Title**: Distributed Approach to Haskell Based Applications Refactoring with LLMs Based Multi-Agent Systems
  - **Authors**: Shahbaz Siddeeq, Zeeshan Rasheed, Malik Abdul Sami, Mahade Hasan, Muhammad Waseem, Jussi Rasku, Mika Saari, Kai-Kristian Kemell, Pekka Abrahamsson
  - **Published**: 2025-02-11
  - **Link**: http://arxiv.org/abs/2502.07928v1
  
  
- **Title**: The Ann Arbor Architecture for Agent-Oriented Programming
  - **Authors**: Wei Dong
  - **Published**: 2025-02-14
  - **Link**: http://arxiv.org/abs/2502.09903v1
  
  
- **Title**: Nexus: A Lightweight and Scalable Multi-Agent Framework for Complex Tasks Automation
  - **Authors**: Humza Sami, Mubashir ul Islam, Samy Charas, Asav Gandhi, Pierre-Emmanuel Gaillardon, Valerio Tenace
  - **Published**: 2025-02-26
  - **Link**: http://arxiv.org/abs/2502.19091v1
  
  
- **Title**: AgentDroid: A Multi-Agent Framework for Detecting Fraudulent Android Applications
  - **Authors**: Ruwei Pan, Hongyu Zhang, Zhonghao Jiang, Ran Hou
  - **Published**: 2025-03-15
  - **Link**: http://arxiv.org/abs/2503.12163v1
  
  
- **Title**: MooseAgent: A LLM Based Multi-agent Framework for Automating Moose Simulation
  - **Authors**: Tao Zhang, Zhenhai Liu, Yong Xin, Yongjun Jiao
  - **Published**: 2025-04-11
  - **Link**: http://arxiv.org/abs/2504.08621v1
  
  
- **Title**: Agent for User: Testing Multi-User Interactive Features in TikTok
  - **Authors**: Sidong Feng, Changhao Du, Huaxiao Liu, Qingnan Wang, Zhengwei Lv, Gang Huo, Xu Yang, Chunyang Chen
  - **Published**: 2025-04-21
  - **Link**: http://arxiv.org/abs/2504.15474v1
  
  
- **Title**: Assessing and Enhancing the Robustness of LLM-based Multi-Agent Systems Through Chaos Engineering
  - **Authors**: Joshua Owotogbe
  - **Published**: 2025-05-06
  - **Link**: http://arxiv.org/abs/2505.03096v1
  
  
- **Title**: Large Language Model-Powered Agent for C to Rust Code Translation
  - **Authors**: HoHyun Sim, Hyeonjoong Cho, Yeonghyeon Go, Zhoulai Fu, Ali Shokri, Binoy Ravindran
  - **Published**: 2025-05-21
  - **Link**: http://arxiv.org/abs/2505.15858v2
  
  
- **Title**: SEW: Self-Evolving Agentic Workflows for Automated Code Generation
  - **Authors**: Siwei Liu, Jinyuan Fang, Han Zhou, Yingxu Wang, Zaiqiao Meng
  - **Published**: 2025-05-24
  - **Link**: http://arxiv.org/abs/2505.18646v1
  
  
- **Title**: Vibe Coding vs. Agentic Coding: Fundamentals and Practical Implications of Agentic AI
  - **Authors**: Ranjan Sapkota, Konstantinos I. Roumeliotis, Manoj Karkee
  - **Published**: 2025-05-26
  - **Link**: http://arxiv.org/abs/2505.19443v1
  
  
- **Title**: Survey of LLM Agent Communication with MCP: A Software Design Pattern Centric Review
  - **Authors**: Anjana Sarkar, Soumyendu Sarkar
  - **Published**: 2025-05-26
  - **Link**: http://arxiv.org/abs/2506.05364v1
  
  
- **Title**: Understanding Software Engineering Agents Through the Lens of Traceability: An Empirical Study
  - **Authors**: Ira Ceka, Saurabh Pujar, Shyam Ramji, Luca Buratti, Gail Kaiser, Baishakhi Ray
  - **Published**: 2025-06-10
  - **Link**: http://arxiv.org/abs/2506.08311v1
  
  
- **Title**: Querying Large Automotive Software Models: Agentic vs. Direct LLM Approaches
  - **Authors**: Lukasz Mazur, Nenad Petrovic, James Pontes Miranda, Ansgar Radermacher, Robert Rasche, Alois Knoll
  - **Published**: 2025-06-16
  - **Link**: http://arxiv.org/abs/2506.13171v1
  
  
- **Title**: Unified Software Engineering agent as AI Software Engineer
  - **Authors**: Leonhard Applis, Yuntong Zhang, Shanchao Liang, Nan Jiang, Lin Tan, Abhik Roychoudhury
  - **Published**: 2025-06-17
  - **Link**: http://arxiv.org/abs/2506.14683v1
  
  
- **Title**: Knowledge-Guided Multi-Agent Framework for Automated Requirements Development: A Vision
  - **Authors**: Jiangping Huang, Dongming Jin, Weisong Sun, Yang Liu, Zhi Jin
  - **Published**: 2025-06-27
  - **Link**: http://arxiv.org/abs/2506.22656v1
  
  
### Multi-Agent Coordination and Communication
- **Title**: ChatDev: Communicative Agents for Software Development
  - **Authors**: Chen Qian, Wei Liu, Hongzhang Liu, Nuo Chen, Yufan Dang, Jiahao Li, Cheng Yang, Weize Chen, Yusheng Su, Xin Cong, Juyuan Xu, Dahai Li, Zhiyuan Liu, Maosong Sun
  - **Published**: 2023-07-16
  - **Link**: http://arxiv.org/abs/2307.07924v5
  
  
- **Title**: Balancing Autonomy and Alignment: A Multi-Dimensional Taxonomy for Autonomous LLM-powered Multi-Agent Architectures
  - **Authors**: Thorsten Händler
  - **Published**: 2023-10-05
  - **Link**: http://arxiv.org/abs/2310.03659v1
  
  
- **Title**: Autonomous Agents in Software Development: A Vision Paper
  - **Authors**: Zeeshan Rasheed, Muhammad Waseem, Kai-Kristian Kemell, Wang Xiaofeng, Anh Nguyen Duc, Kari Systä, Pekka Abrahamsson
  - **Published**: 2023-11-30
  - **Link**: http://arxiv.org/abs/2311.18440v1
  
  
- **Title**: Experiential Co-Learning of Software-Developing Agents
  - **Authors**: Chen Qian, Yufan Dang, Jiahao Li, Wei Liu, Zihao Xie, Yifei Wang, Weize Chen, Cheng Yang, Xin Cong, Xiaoyin Che, Zhiyuan Liu, Maosong Sun
  - **Published**: 2023-12-28
  - **Link**: http://arxiv.org/abs/2312.17025v3
  
  
- **Title**: CodePori: Large-Scale System for Autonomous Software Development Using Multi-Agent Technology
  - **Authors**: Zeeshan Rasheed, Malik Abdul Sami, Kai-Kristian Kemell, Muhammad Waseem, Mika Saari, Kari Systä, Pekka Abrahamsson
  - **Published**: 2024-02-02
  - **Link**: http://arxiv.org/abs/2402.01411v2
  
  
- **Title**: CodeAgent: Autonomous Communicative Agents for Code Review
  - **Authors**: Xunzhu Tang, Kisub Kim, Yewei Song, Cedric Lothritz, Bei Li, Saad Ezzini, Haoye Tian, Jacques Klein, Tegawende F. Bissyande
  - **Published**: 2024-02-03
  - **Link**: http://arxiv.org/abs/2402.02172v5
  
  
- **Title**: SOEN-101: Code Generation by Emulating Software Process Models Using Large Language Model Agents
  - **Authors**: Feng Lin, Dong Jae Kim, Tse-Husn, Chen
  - **Published**: 2024-03-23
  - **Link**: http://arxiv.org/abs/2403.15852v2
  
  
- **Title**: MAGIS: LLM-Based Multi-Agent Framework for GitHub Issue Resolution
  - **Authors**: Wei Tao, Yucheng Zhou, Yanlin Wang, Wenqiang Zhang, Hongyu Zhang, Yu Cheng
  - **Published**: 2024-03-26
  - **Link**: http://arxiv.org/abs/2403.17927v2
  
  
- **Title**: Large Language Model Evaluation Via Multi AI Agents: Preliminary results
  - **Authors**: Zeeshan Rasheed, Muhammad Waseem, Kari Systä, Pekka Abrahamsson
  - **Published**: 2024-04-01
  - **Link**: http://arxiv.org/abs/2404.01023v1
  
  
- **Title**: Self-Organized Agents: A LLM Multi-Agent Framework toward Ultra Large-Scale Code Generation and Optimization
  - **Authors**: Yoichi Ishibashi, Yoshimasa Nishimura
  - **Published**: 2024-04-02
  - **Link**: http://arxiv.org/abs/2404.02183v1
  
  
- **Title**: LLM-Based Multi-Agent Systems for Software Engineering: Literature Review, Vision and the Road Ahead
  - **Authors**: Junda He, Christoph Treude, David Lo
  - **Published**: 2024-04-07
  - **Link**: http://arxiv.org/abs/2404.04834v3
  
  
- **Title**: A Unified Debugging Approach via LLM-Based Multi-Agent Synergy
  - **Authors**: Cheryl Lee, Chunqiu Steven Xia, Longji Yang, Jen-tse Huang, Zhouruixin Zhu, Lingming Zhang, Michael R. Lyu
  - **Published**: 2024-04-26
  - **Link**: http://arxiv.org/abs/2404.17153v2
  
  
- **Title**: MARE: Multi-Agents Collaboration Framework for Requirements Engineering
  - **Authors**: Dongming Jin, Zhi Jin, Xiaohong Chen, Chunhui Wang
  - **Published**: 2024-05-06
  - **Link**: http://arxiv.org/abs/2405.03256v1
  
  
- **Title**: Experimenting with Multi-Agent Software Development: Towards a Unified Platform
  - **Authors**: Malik Abdul Sami, Muhammad Waseem, Zeeshan Rasheed, Mika Saari, Kari Systä, Pekka Abrahamsson
  - **Published**: 2024-06-08
  - **Link**: http://arxiv.org/abs/2406.05381v1
  
  
- **Title**: Multi-Agent Collaboration via Cross-Team Orchestration
  - **Authors**: Zhuoyun Du, Chen Qian, Wei Liu, Zihao Xie, YiFei Wang, Rennai Qiu, Yufan Dang, Weize Chen, Cheng Yang, Ye Tian, Xuantang Xiong, Lei Han
  - **Published**: 2024-06-13
  - **Link**: http://arxiv.org/abs/2406.08979v2
  
  
- **Title**: MASAI: Modular Architecture for Software-engineering AI Agents
  - **Authors**: Daman Arora, Atharv Sonwane, Nalin Wadhwa, Abhav Mehrotra, Saiteja Utpala, Ramakrishna Bairi, Aditya Kanade, Nagarajan Natarajan
  - **Published**: 2024-06-17
  - **Link**: http://arxiv.org/abs/2406.11638v1
  
  
- **Title**: Agent-Driven Automatic Software Improvement
  - **Authors**: Fernando Vallecillos Ruiz
  - **Published**: 2024-06-24
  - **Link**: http://arxiv.org/abs/2406.16739v1
  
  
- **Title**: LAMBDA: A Large Model Based Data Agent
  - **Authors**: Maojun Sun, Ruijian Han, Binyan Jiang, Houduo Qi, Defeng Sun, Yancheng Yuan, Jian Huang
  - **Published**: 2024-07-24
  - **Link**: http://arxiv.org/abs/2407.17535v3
  
  
- **Title**: MAO: A Framework for Process Model Generation with Multi-Agent Orchestration
  - **Authors**: Leilei Lin, Yumeng Jin, Yingming Zhou, Wenlong Chen, Chen Qian
  - **Published**: 2024-08-04
  - **Link**: http://arxiv.org/abs/2408.01916v2
  
  
- **Title**: AutoGen Studio: A No-Code Developer Tool for Building and Debugging Multi-Agent Systems
  - **Authors**: Victor Dibia, Jingya Chen, Gagan Bansal, Suff Syed, Adam Fourney, Erkang Zhu, Chi Wang, Saleema Amershi
  - **Published**: 2024-08-09
  - **Link**: http://arxiv.org/abs/2408.15247v1
  
  
- **Title**: COAST: Enhancing the Code Debugging Ability of LLMs through Communicative Agent Based Data Synthesis
  - **Authors**: Weiqing Yang, Hanbin Wang, Zhenghao Liu, Xinze Li, Yukun Yan, Shuo Wang, Yu Gu, Minghe Yu, Zhiyuan Liu, Ge Yu
  - **Published**: 2024-08-09
  - **Link**: http://arxiv.org/abs/2408.05006v3
  
  
- **Title**: Diversity Empowers Intelligence: Integrating Expertise of Software Engineering Agents
  - **Authors**: Kexun Zhang, Weiran Yao, Zuxin Liu, Yihao Feng, Zhiwei Liu, Rithesh Murthy, Tian Lan, Lei Li, Renze Lou, Jiacheng Xu, Bo Pang, Yingbo Zhou, Shelby Heinecke, Silvio Savarese, Huan Wang, Caiming Xiong
  - **Published**: 2024-08-13
  - **Link**: http://arxiv.org/abs/2408.07060v1
  
  
- **Title**: Text2BIM: Generating Building Models Using a Large Language Model-based Multi-Agent Framework
  - **Authors**: Changyu Du, Sebastian Esser, Stavros Nousias, André Borrmann
  - **Published**: 2024-08-15
  - **Link**: http://arxiv.org/abs/2408.08054v2
  
  
- **Title**: GoNoGo: An Efficient LLM-based Multi-Agent System for Streamlining Automotive Software Release Decision-Making
  - **Authors**: Arsham Gholamzadeh Khoee, Yinan Yu, Robert Feldt, Andris Freimanis, Patrick Andersson Rhodin, Dhasarathy Parthasarathy
  - **Published**: 2024-08-19
  - **Link**: http://arxiv.org/abs/2408.09785v2
  
  
- **Title**: Co-Learning: Code Learning for Multi-Agent Reinforcement Collaborative Framework with Conversational Natural Language Interfaces
  - **Authors**: Jiapeng Yu, Yuqian Wu, Yajing Zhan, Wenhao Guo, Zhou Xu, Raymond Lee
  - **Published**: 2024-09-02
  - **Link**: http://arxiv.org/abs/2409.00985v1
  
  
- **Title**: HyperAgent: Generalist Software Engineering Agents to Solve Coding Tasks at Scale
  - **Authors**: Huy Nhat Phan, Tien N. Nguyen, Phong X. Nguyen, Nghi D. Q. Bui
  - **Published**: 2024-09-09
  - **Link**: http://arxiv.org/abs/2409.16299v2
  
  
- **Title**: Think-on-Process: Dynamic Process Generation for Collaborative Development of Multi-Agent System
  - **Authors**: Leilei Lin, Yingming Zhou, Wenlong Chen, Chen Qian
  - **Published**: 2024-09-10
  - **Link**: http://arxiv.org/abs/2409.06568v1
  
  
- **Title**: Agents in Software Engineering: Survey, Landscape, and Vision
  - **Authors**: Yanlin Wang, Wanjun Zhong, Yanxian Huang, Ensheng Shi, Min Yang, Jiachi Chen, Hui Li, Yuchi Ma, Qianxiang Wang, Zibin Zheng
  - **Published**: 2024-09-13
  - **Link**: http://arxiv.org/abs/2409.09030v2
  
  
- **Title**: AutoSafeCoder: A Multi-Agent Framework for Securing LLM Code Generation through Static Analysis and Fuzz Testing
  - **Authors**: Ana Nunez, Nafis Tanveer Islam, Sumit Kumar Jha, Peyman Najafirad
  - **Published**: 2024-09-16
  - **Link**: http://arxiv.org/abs/2409.10737v2
  
  
- **Title**: LLM-Agent-UMF: LLM-based Agent Unified Modeling Framework for Seamless Integration of Multi Active/Passive Core-Agents
  - **Authors**: Amine Ben Hassouna, Hana Chaari, Ines Belhaj
  - **Published**: 2024-09-17
  - **Link**: http://arxiv.org/abs/2409.11393v2
  
  
- **Title**: TRANSAGENT: An LLM-Based Multi-Agent System for Code Translation
  - **Authors**: Zhiqiang Yuan, Weitong Chen, Hanlin Wang, Kai Yu, Xin Peng, Yiling Lou
  - **Published**: 2024-09-30
  - **Link**: http://arxiv.org/abs/2409.19894v2
  
  
- **Title**: RGD: Multi-LLM Based Agent Debugger via Refinement and Generation Guidance
  - **Authors**: Haolin Jin, Zechao Sun, Huaming Chen
  - **Published**: 2024-10-02
  - **Link**: http://arxiv.org/abs/2410.01242v2
  
  
- **Title**: Towards Exception Safety Code Generation with Intermediate Representation Agents Framework
  - **Authors**: Xuanming Zhang, Yuxuan Chen, Yuan Yuan, Minlie Huang
  - **Published**: 2024-10-09
  - **Link**: http://arxiv.org/abs/2410.06949v3
  
  
- **Title**: Self-Evolving Multi-Agent Collaboration Networks for Software Development
  - **Authors**: Yue Hu, Yuzhu Cai, Yaxin Du, Xinyu Zhu, Xiangrui Liu, Zijie Yu, Yuchen Hou, Shuo Tang, Siheng Chen
  - **Published**: 2024-10-22
  - **Link**: http://arxiv.org/abs/2410.16946v1
  
  
- **Title**: MaCTG: Multi-Agent Collaborative Thought Graph for Automatic Programming
  - **Authors**: Zixiao Zhao, Jing Sun, Zhe Hou, Zhiyuan Wei, Cheng-Hao Cai, Miao Qiao, Jin Song Dong
  - **Published**: 2024-10-25
  - **Link**: http://arxiv.org/abs/2410.19245v2
  
  
- **Title**: Improving Performance of Commercially Available AI Products in a Multi-Agent Configuration
  - **Authors**: Cory Hymel, Sida Peng, Kevin Xu, Charath Ranganathan
  - **Published**: 2024-10-29
  - **Link**: http://arxiv.org/abs/2410.22129v1
  
  
- **Title**: Human-In-the-Loop Software Development Agents
  - **Authors**: Wannita Takerngsaksiri, Jirat Pasuksmit, Patanamon Thongtanunam, Chakkrit Tantithamthavorn, Ruixiong Zhang, Fan Jiang, Jing Li, Evan Cook, Kun Chen, Ming Wu
  - **Published**: 2024-11-19
  - **Link**: http://arxiv.org/abs/2411.12924v2
  
  
- **Title**: SLA Management in Reconfigurable Multi-Agent RAG: A Systems Approach to Question Answering
  - **Authors**: Michael Iannelli, Sneha Kuchipudi, Vera Dvorak
  - **Published**: 2024-12-07
  - **Link**: http://arxiv.org/abs/2412.06832v2
  
  
- **Title**: Towards Modeling Human-Agentic Collaborative Workflows: A BPMN Extension
  - **Authors**: Adem Ait, Javier Luis Cánovas Izquierdo, Jordi Cabot
  - **Published**: 2024-12-08
  - **Link**: http://arxiv.org/abs/2412.05958v3
  
  
- **Title**: CoopetitiveV: Leveraging LLM-powered Coopetitive Multi-Agent Prompting for High-quality Verilog Generation
  - **Authors**: Zhendong Mi, Renming Zheng, Haowen Zhong, Yue Sun, Seth Kneeland, Sayan Moitra, Ken Kutzer, Zhaozhuo Xu Shaoyi Huang
  - **Published**: 2024-12-15
  - **Link**: http://arxiv.org/abs/2412.11014v2
  
  
- **Title**: Seeker: Towards Exception Safety Code Generation with Intermediate Language Agents Framework
  - **Authors**: Xuanming Zhang, Yuxuan Chen, Yiming Zheng, Zhexin Zhang, Yuan Yuan, Minlie Huang
  - **Published**: 2024-12-16
  - **Link**: http://arxiv.org/abs/2412.11713v1
  
  
- **Title**: RTLSquad: Multi-Agent Based Interpretable RTL Design
  - **Authors**: Bowei Wang, Qi Xiong, Zeqing Xiang, Lei Wang, Renzhi Chen
  - **Published**: 2025-01-06
  - **Link**: http://arxiv.org/abs/2501.05470v1
  
  
- **Title**: CodeCoR: An LLM-Based Self-Reflective Multi-Agent Framework for Code Generation
  - **Authors**: Ruwei Pan, Hongyu Zhang, Chao Liu
  - **Published**: 2025-01-14
  - **Link**: http://arxiv.org/abs/2501.07811v1
  
  
- **Title**: QualityFlow: An Agentic Workflow for Program Synthesis Controlled by LLM Quality Checks
  - **Authors**: Yaojie Hu, Qiang Zhou, Qihong Chen, Xiaopeng Li, Linbo Liu, Dejiao Zhang, Amit Kachroo, Talha Oz, Omer Tripp
  - **Published**: 2025-01-20
  - **Link**: http://arxiv.org/abs/2501.17167v2
  
  
- **Title**: VulnBot: Autonomous Penetration Testing for A Multi-Agent Collaborative Framework
  - **Authors**: He Kong, Die Hu, Jingguo Ge, Liangxiong Li, Tong Li, Bingzhen Wu
  - **Published**: 2025-01-23
  - **Link**: http://arxiv.org/abs/2501.13411v1
  
  
- **Title**: Autonomous Legacy Web Application Upgrades Using a Multi-Agent System
  - **Authors**: Valtteri Ala-Salmi, Zeeshan Rasheed, Abdul Malik Sami, Zheying Zhang, Kai-Kristian Kemell, Jussi Rasku, Shahbaz Siddeeq, Mika Saari, Pekka Abrahamsson
  - **Published**: 2025-01-31
  - **Link**: http://arxiv.org/abs/2501.19204v1
  
  
- **Title**: SyncMind: Measuring Agent Out-of-Sync Recovery in Collaborative Software Engineering
  - **Authors**: Xuehang Guo, Xingyao Wang, Yangyi Chen, Sha Li, Chi Han, Manling Li, Heng Ji
  - **Published**: 2025-02-10
  - **Link**: http://arxiv.org/abs/2502.06994v2
  
  
- **Title**: Distributed Approach to Haskell Based Applications Refactoring with LLMs Based Multi-Agent Systems
  - **Authors**: Shahbaz Siddeeq, Zeeshan Rasheed, Malik Abdul Sami, Mahade Hasan, Muhammad Waseem, Jussi Rasku, Mika Saari, Kai-Kristian Kemell, Pekka Abrahamsson
  - **Published**: 2025-02-11
  - **Link**: http://arxiv.org/abs/2502.07928v1
  
  
- **Title**: Flow-of-Action: SOP Enhanced LLM-Based Multi-Agent System for Root Cause Analysis
  - **Authors**: Changhua Pei, Zexin Wang, Fengrui Liu, Zeyan Li, Yang Liu, Xiao He, Rong Kang, Tieying Zhang, Jianjun Chen, Jianhui Li, Gaogang Xie, Dan Pei
  - **Published**: 2025-02-12
  - **Link**: http://arxiv.org/abs/2502.08224v1
  
  
- **Title**: A Multi-Agent Framework for Automated Vulnerability Detection and Repair in Solidity and Move Smart Contracts
  - **Authors**: Rabimba Karanjai, Sam Blackshear, Lei Xu, Weidong Shi
  - **Published**: 2025-02-22
  - **Link**: http://arxiv.org/abs/2502.18515v1
  
  
- **Title**: Nexus: A Lightweight and Scalable Multi-Agent Framework for Complex Tasks Automation
  - **Authors**: Humza Sami, Mubashir ul Islam, Samy Charas, Asav Gandhi, Pierre-Emmanuel Gaillardon, Valerio Tenace
  - **Published**: 2025-02-26
  - **Link**: http://arxiv.org/abs/2502.19091v1
  
  
- **Title**: Fully Autonomous Programming using Iterative Multi-Agent Debugging with Large Language Models
  - **Authors**: Anastasiia Grishina, Vadim Liventsev, Aki Härmä, Leon Moonen
  - **Published**: 2025-03-10
  - **Link**: http://arxiv.org/abs/2503.07693v1
  
  
- **Title**: Teamwork makes the dream work: LLMs-Based Agents for GitHub README.MD Summarization
  - **Authors**: Duc S. H. Nguyen, Bach G. Truong, Phuong T. Nguyen, Juri Di Rocco, Davide Di Ruscio
  - **Published**: 2025-03-13
  - **Link**: http://arxiv.org/abs/2503.10876v1
  
  
- **Title**: Is Multi-Agent Debate (MAD) the Silver Bullet? An Empirical Analysis of MAD in Code Summarization and Translation
  - **Authors**: Jina Chun, Qihong Chen, Jiawei Li, Iftekhar Ahmed
  - **Published**: 2025-03-15
  - **Link**: http://arxiv.org/abs/2503.12029v1
  
  
- **Title**: AgentDroid: A Multi-Agent Framework for Detecting Fraudulent Android Applications
  - **Authors**: Ruwei Pan, Hongyu Zhang, Zhonghao Jiang, Ran Hou
  - **Published**: 2025-03-15
  - **Link**: http://arxiv.org/abs/2503.12163v1
  
  
- **Title**: MANTRA: Enhancing Automated Method-Level Refactoring with Contextual RAG and Multi-Agent LLM Collaboration
  - **Authors**: Yisen Xu, Feng Lin, Jinqiu Yang, Tse-Hsun, Chen, Nikolaos Tsantalis
  - **Published**: 2025-03-18
  - **Link**: http://arxiv.org/abs/2503.14340v2
  
  
- **Title**: Knowledge-Based Multi-Agent Framework for Automated Software Architecture Design
  - **Authors**: Yiran Zhang, Ruiyin Li, Peng Liang, Weisong Sun, Yang Liu
  - **Published**: 2025-03-26
  - **Link**: http://arxiv.org/abs/2503.20536v1
  
  
- **Title**: Unlocking LLM Repair Capabilities in Low-Resource Programming Languages Through Cross-Language Translation and Multi-Agent Refinement
  - **Authors**: Wenqiang Luo, Jacky Wai Keung, Boyang Yang, Jacques Klein, Tegawende F. Bissyande, Haoye Tian, Bach Le
  - **Published**: 2025-03-28
  - **Link**: http://arxiv.org/abs/2503.22512v3
  
  
- **Title**: SciReplicate-Bench: Benchmarking LLMs in Agent-driven Algorithmic Reproduction from Research Papers
  - **Authors**: Yanzheng Xiang, Hanqi Yan, Shuyin Ouyang, Lin Gui, Yulan He
  - **Published**: 2025-03-31
  - **Link**: http://arxiv.org/abs/2504.00255v1
  
  
- **Title**: AdaCoder: An Adaptive Planning and Multi-Agent Framework for Function-Level Code Generation
  - **Authors**: Yueheng Zhu, Chao Liu, Xuan He, Xiaoxue Ren, Zhongxin Liu, Ruwei Pan, Hongyu Zhang
  - **Published**: 2025-04-05
  - **Link**: http://arxiv.org/abs/2504.04220v1
  
  
- **Title**: AgentFM: Role-Aware Failure Management for Distributed Databases with LLM-Driven Multi-Agents
  - **Authors**: Lingzhe Zhang, Yunpeng Zhai, Tong Jia, Xiaosong Huang, Chiming Duan, Ying Li
  - **Published**: 2025-04-09
  - **Link**: http://arxiv.org/abs/2504.06614v1
  
  
- **Title**: MooseAgent: A LLM Based Multi-agent Framework for Automating Moose Simulation
  - **Authors**: Tao Zhang, Zhenhai Liu, Yong Xin, Yongjun Jiao
  - **Published**: 2025-04-11
  - **Link**: http://arxiv.org/abs/2504.08621v1
  
  
- **Title**: Agent for User: Testing Multi-User Interactive Features in TikTok
  - **Authors**: Sidong Feng, Changhao Du, Huaxiao Liu, Qingnan Wang, Zhengwei Lv, Gang Huo, Xu Yang, Chunyang Chen
  - **Published**: 2025-04-21
  - **Link**: http://arxiv.org/abs/2504.15474v1
  
  
- **Title**: Human-In-The-Loop Software Development Agents: Challenges and Future Directions
  - **Authors**: Jirat Pasuksmit, Wannita Takerngsaksiri, Patanamon Thongtanunam, Chakkrit Tantithamthavorn, Ruixiong Zhang, Shiyan Wang, Fan Jiang, Jing Li, Evan Cook, Kun Chen, Ming Wu
  - **Published**: 2025-04-25
  - **Link**: http://arxiv.org/abs/2506.11009v1
  
  
- **Title**: AutoP2C: An LLM-Based Agent Framework for Code Repository Generation from Multimodal Content in Academic Papers
  - **Authors**: Zijie Lin, Yiqing Shen, Qilin Cai, He Sun, Jinrui Zhou, Mingjun Xiao
  - **Published**: 2025-04-28
  - **Link**: http://arxiv.org/abs/2504.20115v2
  
  
- **Title**: ResearchCodeAgent: An LLM Multi-Agent System for Automated Codification of Research Methodologies
  - **Authors**: Shubham Gandhi, Dhruv Shah, Manasi Patwardhan, Lovekesh Vig, Gautam Shroff
  - **Published**: 2025-04-28
  - **Link**: http://arxiv.org/abs/2504.20117v2
  
  
- **Title**: Enhancing LLM Code Generation: A Systematic Evaluation of Multi-Agent Collaboration and Runtime Debugging for Improved Accuracy, Reliability, and Latency
  - **Authors**: Nazmus Ashrafi, Salah Bouktif, Mohammed Mediani
  - **Published**: 2025-05-04
  - **Link**: http://arxiv.org/abs/2505.02133v1
  
  
- **Title**: Assessing and Enhancing the Robustness of LLM-based Multi-Agent Systems Through Chaos Engineering
  - **Authors**: Joshua Owotogbe
  - **Published**: 2025-05-06
  - **Link**: http://arxiv.org/abs/2505.03096v1
  
  
- **Title**: MARCO: Multi-Agent Code Optimization with Real-Time Knowledge Integration for High-Performance Computing
  - **Authors**: Asif Rahman, Veljko Cvetkovic, Kathleen Reece, Aidan Walters, Yasir Hassan, Aneesh Tummeti, Bryan Torres, Denise Cooney, Margaret Ellis, Dimitrios S. Nikolopoulos
  - **Published**: 2025-05-06
  - **Link**: http://arxiv.org/abs/2505.03906v3
  
  
- **Title**: Facilitating Trustworthy Human-Agent Collaboration in LLM-based Multi-Agent System oriented Software Engineering
  - **Authors**: Krishna Ronanki
  - **Published**: 2025-05-07
  - **Link**: http://arxiv.org/abs/2505.04251v1
  
  
- **Title**: SEW: Self-Evolving Agentic Workflows for Automated Code Generation
  - **Authors**: Siwei Liu, Jinyuan Fang, Han Zhou, Yingxu Wang, Zaiqiao Meng
  - **Published**: 2025-05-24
  - **Link**: http://arxiv.org/abs/2505.18646v1
  
  
- **Title**: Survey of LLM Agent Communication with MCP: A Software Design Pattern Centric Review
  - **Authors**: Anjana Sarkar, Soumyendu Sarkar
  - **Published**: 2025-05-26
  - **Link**: http://arxiv.org/abs/2506.05364v1
  
  
- **Title**: Co-Saving: Resource Aware Multi-Agent Collaboration for Software Development
  - **Authors**: Rennai Qiu, Chen Qian, Ran Li, Yufan Dang, Weize Chen, Cheng Yang, Yingli Zhang, Ye Tian, Xuantang Xiong, Lei Han, Zhiyuan Liu, Maosong Sun
  - **Published**: 2025-05-28
  - **Link**: http://arxiv.org/abs/2505.21898v1
  
  
- **Title**: Lessons Learned: A Multi-Agent Framework for Code LLMs to Learn and Improve
  - **Authors**: Yuanzhe Liu, Ryan Deng, Tim Kaler, Xuhao Chen, Charles E. Leiserson, Yao Ma, Jie Chen
  - **Published**: 2025-05-29
  - **Link**: http://arxiv.org/abs/2505.23946v1
  
  
- **Title**: Temac: Multi-Agent Collaboration for Automated Web GUI Testing
  - **Authors**: Chenxu Liu, Zhiyu Gu, Guoquan Wu, Ying Zhang, Jun Wei, Tao Xie
  - **Published**: 2025-05-31
  - **Link**: http://arxiv.org/abs/2506.00520v1
  
  
- **Title**: Hallucination to Consensus: Multi-Agent LLMs for End-to-End Test Generation with Accurate Oracles
  - **Authors**: Qinghua Xu, Guancheng Wang, Lionel Briand, Kui Liu
  - **Published**: 2025-06-03
  - **Link**: http://arxiv.org/abs/2506.02943v4
  
  
- **Title**: Unified Software Engineering agent as AI Software Engineer
  - **Authors**: Leonhard Applis, Yuntong Zhang, Shanchao Liang, Nan Jiang, Lin Tan, Abhik Roychoudhury
  - **Published**: 2025-06-17
  - **Link**: http://arxiv.org/abs/2506.14683v1
  
  
- **Title**: Breaking Single-Tester Limits: Multi-Agent LLMs for Multi-User Feature Testing
  - **Authors**: Sidong Feng, Changhao Du, Huaxiao Liu, Qingnan Wang, Zhengwei Lv, Mengfei Wang, Chunyang Chen
  - **Published**: 2025-06-21
  - **Link**: http://arxiv.org/abs/2506.17539v2
  
  
- **Title**: LLM-based Multi-Agent System for Intelligent Refactoring of Haskell Code
  - **Authors**: Shahbaz Siddeeq, Muhammad Waseem, Zeeshan Rasheed, Md Mahade Hasan, Jussi Rasku, Mika Saari, Henri Terho, Kalle Makela, Kai-Kristian Kemell, Pekka Abrahamsson
  - **Published**: 2025-06-24
  - **Link**: http://arxiv.org/abs/2506.19481v1
  
  
- **Title**: Knowledge-Guided Multi-Agent Framework for Automated Requirements Development: A Vision
  - **Authors**: Jiangping Huang, Dongming Jin, Weisong Sun, Yang Liu, Zhi Jin
  - **Published**: 2025-06-27
  - **Link**: http://arxiv.org/abs/2506.22656v1
  
  
- **Title**: Multi-Agent Debate Strategies to Enhance Requirements Engineering with Large Language Models
  - **Authors**: Marc Oriol, Quim Motger, Jordi Marco, Xavier Franch
  - **Published**: 2025-07-08
  - **Link**: http://arxiv.org/abs/2507.05981v1
  
  
- **Title**: An Empirical Study of Multi-Agent RAG for Real-World University Admissions Counseling
  - **Authors**: Anh Nguyen-Duc, Chien Vu Manh, Bao Anh Tran, Viet Phuong Ngo, Luan Le Chi, Anh Quang Nguyen
  - **Published**: 2025-07-15
  - **Link**: http://arxiv.org/abs/2507.11272v1
  
  
### Agent Specialization and Role Assignment
- **Title**: ChatDev: Communicative Agents for Software Development
  - **Authors**: Chen Qian, Wei Liu, Hongzhang Liu, Nuo Chen, Yufan Dang, Jiahao Li, Cheng Yang, Weize Chen, Yusheng Su, Xin Cong, Juyuan Xu, Dahai Li, Zhiyuan Liu, Maosong Sun
  - **Published**: 2023-07-16
  - **Link**: http://arxiv.org/abs/2307.07924v5
  
  
- **Title**: Balancing Autonomy and Alignment: A Multi-Dimensional Taxonomy for Autonomous LLM-powered Multi-Agent Architectures
  - **Authors**: Thorsten Händler
  - **Published**: 2023-10-05
  - **Link**: http://arxiv.org/abs/2310.03659v1
  
  
- **Title**: How to Teach Programming in the AI Era? Using LLMs as a Teachable Agent for Debugging
  - **Authors**: Qianou Ma, Hua Shen, Kenneth Koedinger, Tongshuang Wu
  - **Published**: 2023-10-08
  - **Link**: http://arxiv.org/abs/2310.05292v5
  
  
- **Title**: Experiential Co-Learning of Software-Developing Agents
  - **Authors**: Chen Qian, Yufan Dang, Jiahao Li, Wei Liu, Zihao Xie, Yifei Wang, Weize Chen, Cheng Yang, Xin Cong, Xiaoyin Che, Zhiyuan Liu, Maosong Sun
  - **Published**: 2023-12-28
  - **Link**: http://arxiv.org/abs/2312.17025v3
  
  
- **Title**: Can Large Language Models Serve as Data Analysts? A Multi-Agent Assisted Approach for Qualitative Data Analysis
  - **Authors**: Zeeshan Rasheed, Muhammad Waseem, Aakash Ahmad, Kai-Kristian Kemell, Wang Xiaofeng, Anh Nguyen Duc, Pekka Abrahamsson
  - **Published**: 2024-02-02
  - **Link**: http://arxiv.org/abs/2402.01386v1
  
  
- **Title**: SOEN-101: Code Generation by Emulating Software Process Models Using Large Language Model Agents
  - **Authors**: Feng Lin, Dong Jae Kim, Tse-Husn, Chen
  - **Published**: 2024-03-23
  - **Link**: http://arxiv.org/abs/2403.15852v2
  
  
- **Title**: Combining Fine-Tuning and LLM-based Agents for Intuitive Smart Contract Auditing with Justifications
  - **Authors**: Wei Ma, Daoyuan Wu, Yuqiang Sun, Tianwen Wang, Shangqing Liu, Jian Zhang, Yue Xue, Yang Liu
  - **Published**: 2024-03-24
  - **Link**: http://arxiv.org/abs/2403.16073v3
  
  
- **Title**: MAGIS: LLM-Based Multi-Agent Framework for GitHub Issue Resolution
  - **Authors**: Wei Tao, Yucheng Zhou, Yanlin Wang, Wenqiang Zhang, Hongyu Zhang, Yu Cheng
  - **Published**: 2024-03-26
  - **Link**: http://arxiv.org/abs/2403.17927v2
  
  
- **Title**: Large Language Model Evaluation Via Multi AI Agents: Preliminary results
  - **Authors**: Zeeshan Rasheed, Muhammad Waseem, Kari Systä, Pekka Abrahamsson
  - **Published**: 2024-04-01
  - **Link**: http://arxiv.org/abs/2404.01023v1
  
  
- **Title**: LLM-Based Multi-Agent Systems for Software Engineering: Literature Review, Vision and the Road Ahead
  - **Authors**: Junda He, Christoph Treude, David Lo
  - **Published**: 2024-04-07
  - **Link**: http://arxiv.org/abs/2404.04834v3
  
  
- **Title**: A Unified Debugging Approach via LLM-Based Multi-Agent Synergy
  - **Authors**: Cheryl Lee, Chunqiu Steven Xia, Longji Yang, Jen-tse Huang, Zhouruixin Zhu, Lingming Zhang, Michael R. Lyu
  - **Published**: 2024-04-26
  - **Link**: http://arxiv.org/abs/2404.17153v2
  
  
- **Title**: MARE: Multi-Agents Collaboration Framework for Requirements Engineering
  - **Authors**: Dongming Jin, Zhi Jin, Xiaohong Chen, Chunhui Wang
  - **Published**: 2024-05-06
  - **Link**: http://arxiv.org/abs/2405.03256v1
  
  
- **Title**: DepsRAG: Towards Agentic Reasoning and Planning for Software Dependency Management
  - **Authors**: Mohannad Alhanahnah, Yazan Boshmaf
  - **Published**: 2024-05-30
  - **Link**: http://arxiv.org/abs/2405.20455v5
  
  
- **Title**: Experimenting with Multi-Agent Software Development: Towards a Unified Platform
  - **Authors**: Malik Abdul Sami, Muhammad Waseem, Zeeshan Rasheed, Mika Saari, Kari Systä, Pekka Abrahamsson
  - **Published**: 2024-06-08
  - **Link**: http://arxiv.org/abs/2406.05381v1
  
  
- **Title**: MASAI: Modular Architecture for Software-engineering AI Agents
  - **Authors**: Daman Arora, Atharv Sonwane, Nalin Wadhwa, Abhav Mehrotra, Saiteja Utpala, Ramakrishna Bairi, Aditya Kanade, Nagarajan Natarajan
  - **Published**: 2024-06-17
  - **Link**: http://arxiv.org/abs/2406.11638v1
  
  
- **Title**: LAMBDA: A Large Model Based Data Agent
  - **Authors**: Maojun Sun, Ruijian Han, Binyan Jiang, Houduo Qi, Defeng Sun, Yancheng Yuan, Jian Huang
  - **Published**: 2024-07-24
  - **Link**: http://arxiv.org/abs/2407.17535v3
  
  
- **Title**: MAO: A Framework for Process Model Generation with Multi-Agent Orchestration
  - **Authors**: Leilei Lin, Yumeng Jin, Yingming Zhou, Wenlong Chen, Chen Qian
  - **Published**: 2024-08-04
  - **Link**: http://arxiv.org/abs/2408.01916v2
  
  
- **Title**: Co-Learning: Code Learning for Multi-Agent Reinforcement Collaborative Framework with Conversational Natural Language Interfaces
  - **Authors**: Jiapeng Yu, Yuqian Wu, Yajing Zhan, Wenhao Guo, Zhou Xu, Raymond Lee
  - **Published**: 2024-09-02
  - **Link**: http://arxiv.org/abs/2409.00985v1
  
  
- **Title**: HyperAgent: Generalist Software Engineering Agents to Solve Coding Tasks at Scale
  - **Authors**: Huy Nhat Phan, Tien N. Nguyen, Phong X. Nguyen, Nghi D. Q. Bui
  - **Published**: 2024-09-09
  - **Link**: http://arxiv.org/abs/2409.16299v2
  
  
- **Title**: Agents in Software Engineering: Survey, Landscape, and Vision
  - **Authors**: Yanlin Wang, Wanjun Zhong, Yanxian Huang, Ensheng Shi, Min Yang, Jiachi Chen, Hui Li, Yuchi Ma, Qianxiang Wang, Zibin Zheng
  - **Published**: 2024-09-13
  - **Link**: http://arxiv.org/abs/2409.09030v2
  
  
- **Title**: LLM-Agent-UMF: LLM-based Agent Unified Modeling Framework for Seamless Integration of Multi Active/Passive Core-Agents
  - **Authors**: Amine Ben Hassouna, Hana Chaari, Ines Belhaj
  - **Published**: 2024-09-17
  - **Link**: http://arxiv.org/abs/2409.11393v2
  
  
- **Title**: TRANSAGENT: An LLM-Based Multi-Agent System for Code Translation
  - **Authors**: Zhiqiang Yuan, Weitong Chen, Hanlin Wang, Kai Yu, Xin Peng, Yiling Lou
  - **Published**: 2024-09-30
  - **Link**: http://arxiv.org/abs/2409.19894v2
  
  
- **Title**: Towards Exception Safety Code Generation with Intermediate Representation Agents Framework
  - **Authors**: Xuanming Zhang, Yuxuan Chen, Yuan Yuan, Minlie Huang
  - **Published**: 2024-10-09
  - **Link**: http://arxiv.org/abs/2410.06949v3
  
  
- **Title**: MaCTG: Multi-Agent Collaborative Thought Graph for Automatic Programming
  - **Authors**: Zixiao Zhao, Jing Sun, Zhe Hou, Zhiyuan Wei, Cheng-Hao Cai, Miao Qiao, Jin Song Dong
  - **Published**: 2024-10-25
  - **Link**: http://arxiv.org/abs/2410.19245v2
  
  
- **Title**: SLA Management in Reconfigurable Multi-Agent RAG: A Systems Approach to Question Answering
  - **Authors**: Michael Iannelli, Sneha Kuchipudi, Vera Dvorak
  - **Published**: 2024-12-07
  - **Link**: http://arxiv.org/abs/2412.06832v2
  
  
- **Title**: Seeker: Towards Exception Safety Code Generation with Intermediate Language Agents Framework
  - **Authors**: Xuanming Zhang, Yuxuan Chen, Yiming Zheng, Zhexin Zhang, Yuan Yuan, Minlie Huang
  - **Published**: 2024-12-16
  - **Link**: http://arxiv.org/abs/2412.11713v1
  
  
- **Title**: RTLSquad: Multi-Agent Based Interpretable RTL Design
  - **Authors**: Bowei Wang, Qi Xiong, Zeqing Xiang, Lei Wang, Renzhi Chen
  - **Published**: 2025-01-06
  - **Link**: http://arxiv.org/abs/2501.05470v1
  
  
- **Title**: QualityFlow: An Agentic Workflow for Program Synthesis Controlled by LLM Quality Checks
  - **Authors**: Yaojie Hu, Qiang Zhou, Qihong Chen, Xiaopeng Li, Linbo Liu, Dejiao Zhang, Amit Kachroo, Talha Oz, Omer Tripp
  - **Published**: 2025-01-20
  - **Link**: http://arxiv.org/abs/2501.17167v2
  
  
- **Title**: VulnBot: Autonomous Penetration Testing for A Multi-Agent Collaborative Framework
  - **Authors**: He Kong, Die Hu, Jingguo Ge, Liangxiong Li, Tong Li, Bingzhen Wu
  - **Published**: 2025-01-23
  - **Link**: http://arxiv.org/abs/2501.13411v1
  
  
- **Title**: Distributed Approach to Haskell Based Applications Refactoring with LLMs Based Multi-Agent Systems
  - **Authors**: Shahbaz Siddeeq, Zeeshan Rasheed, Malik Abdul Sami, Mahade Hasan, Muhammad Waseem, Jussi Rasku, Mika Saari, Kai-Kristian Kemell, Pekka Abrahamsson
  - **Published**: 2025-02-11
  - **Link**: http://arxiv.org/abs/2502.07928v1
  
  
- **Title**: Flow-of-Action: SOP Enhanced LLM-Based Multi-Agent System for Root Cause Analysis
  - **Authors**: Changhua Pei, Zexin Wang, Fengrui Liu, Zeyan Li, Yang Liu, Xiao He, Rong Kang, Tieying Zhang, Jianjun Chen, Jianhui Li, Gaogang Xie, Dan Pei
  - **Published**: 2025-02-12
  - **Link**: http://arxiv.org/abs/2502.08224v1
  
  
- **Title**: A Multi-Agent Framework for Automated Vulnerability Detection and Repair in Solidity and Move Smart Contracts
  - **Authors**: Rabimba Karanjai, Sam Blackshear, Lei Xu, Weidong Shi
  - **Published**: 2025-02-22
  - **Link**: http://arxiv.org/abs/2502.18515v1
  
  
- **Title**: Fully Autonomous Programming using Iterative Multi-Agent Debugging with Large Language Models
  - **Authors**: Anastasiia Grishina, Vadim Liventsev, Aki Härmä, Leon Moonen
  - **Published**: 2025-03-10
  - **Link**: http://arxiv.org/abs/2503.07693v1
  
  
- **Title**: Teamwork makes the dream work: LLMs-Based Agents for GitHub README.MD Summarization
  - **Authors**: Duc S. H. Nguyen, Bach G. Truong, Phuong T. Nguyen, Juri Di Rocco, Davide Di Ruscio
  - **Published**: 2025-03-13
  - **Link**: http://arxiv.org/abs/2503.10876v1
  
  
- **Title**: AgentDroid: A Multi-Agent Framework for Detecting Fraudulent Android Applications
  - **Authors**: Ruwei Pan, Hongyu Zhang, Zhonghao Jiang, Ran Hou
  - **Published**: 2025-03-15
  - **Link**: http://arxiv.org/abs/2503.12163v1
  
  
- **Title**: Knowledge-Based Multi-Agent Framework for Automated Software Architecture Design
  - **Authors**: Yiran Zhang, Ruiyin Li, Peng Liang, Weisong Sun, Yang Liu
  - **Published**: 2025-03-26
  - **Link**: http://arxiv.org/abs/2503.20536v1
  
  
- **Title**: SciReplicate-Bench: Benchmarking LLMs in Agent-driven Algorithmic Reproduction from Research Papers
  - **Authors**: Yanzheng Xiang, Hanqi Yan, Shuyin Ouyang, Lin Gui, Yulan He
  - **Published**: 2025-03-31
  - **Link**: http://arxiv.org/abs/2504.00255v1
  
  
- **Title**: AdaCoder: An Adaptive Planning and Multi-Agent Framework for Function-Level Code Generation
  - **Authors**: Yueheng Zhu, Chao Liu, Xuan He, Xiaoxue Ren, Zhongxin Liu, Ruwei Pan, Hongyu Zhang
  - **Published**: 2025-04-05
  - **Link**: http://arxiv.org/abs/2504.04220v1
  
  
- **Title**: MooseAgent: A LLM Based Multi-agent Framework for Automating Moose Simulation
  - **Authors**: Tao Zhang, Zhenhai Liu, Yong Xin, Yongjun Jiao
  - **Published**: 2025-04-11
  - **Link**: http://arxiv.org/abs/2504.08621v1
  
  
- **Title**: AutoP2C: An LLM-Based Agent Framework for Code Repository Generation from Multimodal Content in Academic Papers
  - **Authors**: Zijie Lin, Yiqing Shen, Qilin Cai, He Sun, Jinrui Zhou, Mingjun Xiao
  - **Published**: 2025-04-28
  - **Link**: http://arxiv.org/abs/2504.20115v2
  
  
- **Title**: ResearchCodeAgent: An LLM Multi-Agent System for Automated Codification of Research Methodologies
  - **Authors**: Shubham Gandhi, Dhruv Shah, Manasi Patwardhan, Lovekesh Vig, Gautam Shroff
  - **Published**: 2025-04-28
  - **Link**: http://arxiv.org/abs/2504.20117v2
  
  
- **Title**: MARCO: Multi-Agent Code Optimization with Real-Time Knowledge Integration for High-Performance Computing
  - **Authors**: Asif Rahman, Veljko Cvetkovic, Kathleen Reece, Aidan Walters, Yasir Hassan, Aneesh Tummeti, Bryan Torres, Denise Cooney, Margaret Ellis, Dimitrios S. Nikolopoulos
  - **Published**: 2025-05-06
  - **Link**: http://arxiv.org/abs/2505.03906v3
  
  
- **Title**: Facilitating Trustworthy Human-Agent Collaboration in LLM-based Multi-Agent System oriented Software Engineering
  - **Authors**: Krishna Ronanki
  - **Published**: 2025-05-07
  - **Link**: http://arxiv.org/abs/2505.04251v1
  
  
- **Title**: SEW: Self-Evolving Agentic Workflows for Automated Code Generation
  - **Authors**: Siwei Liu, Jinyuan Fang, Han Zhou, Yingxu Wang, Zaiqiao Meng
  - **Published**: 2025-05-24
  - **Link**: http://arxiv.org/abs/2505.18646v1
  
  
- **Title**: Co-Saving: Resource Aware Multi-Agent Collaboration for Software Development
  - **Authors**: Rennai Qiu, Chen Qian, Ran Li, Yufan Dang, Weize Chen, Cheng Yang, Yingli Zhang, Ye Tian, Xuantang Xiong, Lei Han, Zhiyuan Liu, Maosong Sun
  - **Published**: 2025-05-28
  - **Link**: http://arxiv.org/abs/2505.21898v1
  
  
- **Title**: Breaking Single-Tester Limits: Multi-Agent LLMs for Multi-User Feature Testing
  - **Authors**: Sidong Feng, Changhao Du, Huaxiao Liu, Qingnan Wang, Zhengwei Lv, Mengfei Wang, Chunyang Chen
  - **Published**: 2025-06-21
  - **Link**: http://arxiv.org/abs/2506.17539v2
  
  
- **Title**: LLM-based Multi-Agent System for Intelligent Refactoring of Haskell Code
  - **Authors**: Shahbaz Siddeeq, Muhammad Waseem, Zeeshan Rasheed, Md Mahade Hasan, Jussi Rasku, Mika Saari, Henri Terho, Kalle Makela, Kai-Kristian Kemell, Pekka Abrahamsson
  - **Published**: 2025-06-24
  - **Link**: http://arxiv.org/abs/2506.19481v1
  
  
- **Title**: Knowledge-Guided Multi-Agent Framework for Automated Requirements Development: A Vision
  - **Authors**: Jiangping Huang, Dongming Jin, Weisong Sun, Yang Liu, Zhi Jin
  - **Published**: 2025-06-27
  - **Link**: http://arxiv.org/abs/2506.22656v1
  
  
- **Title**: An Empirical Study of Multi-Agent RAG for Real-World University Admissions Counseling
  - **Authors**: Anh Nguyen-Duc, Chien Vu Manh, Bao Anh Tran, Viet Phuong Ngo, Luan Le Chi, Anh Quang Nguyen
  - **Published**: 2025-07-15
  - **Link**: http://arxiv.org/abs/2507.11272v1
  
  
### Collaborative Problem Solving

- **Title**: ChatDev: Communicative Agents for Software Development
  - **Authors**: Chen Qian, Wei Liu, Hongzhang Liu, Nuo Chen, Yufan Dang, Jiahao Li, Cheng Yang, Weize Chen, Yusheng Su, Xin Cong, Juyuan Xu, Dahai Li, Zhiyuan Liu, Maosong Sun
  - **Published**: 2023-07-16
  - **Link**: http://arxiv.org/abs/2307.07924v5
  
  
- **Title**: Balancing Autonomy and Alignment: A Multi-Dimensional Taxonomy for Autonomous LLM-powered Multi-Agent Architectures
  - **Authors**: Thorsten Händler
  - **Published**: 2023-10-05
  - **Link**: http://arxiv.org/abs/2310.03659v1
  
  
- **Title**: How to Teach Programming in the AI Era? Using LLMs as a Teachable Agent for Debugging
  - **Authors**: Qianou Ma, Hua Shen, Kenneth Koedinger, Tongshuang Wu
  - **Published**: 2023-10-08
  - **Link**: http://arxiv.org/abs/2310.05292v5
  
  
- **Title**: Autonomous Agents in Software Development: A Vision Paper
  - **Authors**: Zeeshan Rasheed, Muhammad Waseem, Kai-Kristian Kemell, Wang Xiaofeng, Anh Nguyen Duc, Kari Systä, Pekka Abrahamsson
  - **Published**: 2023-11-30
  - **Link**: http://arxiv.org/abs/2311.18440v1
  
  
- **Title**: Experiential Co-Learning of Software-Developing Agents
  - **Authors**: Chen Qian, Yufan Dang, Jiahao Li, Wei Liu, Zihao Xie, Yifei Wang, Weize Chen, Cheng Yang, Xin Cong, Xiaoyin Che, Zhiyuan Liu, Maosong Sun
  - **Published**: 2023-12-28
  - **Link**: http://arxiv.org/abs/2312.17025v3
  
  
- **Title**: CodePori: Large-Scale System for Autonomous Software Development Using Multi-Agent Technology
  - **Authors**: Zeeshan Rasheed, Malik Abdul Sami, Kai-Kristian Kemell, Muhammad Waseem, Mika Saari, Kari Systä, Pekka Abrahamsson
  - **Published**: 2024-02-02
  - **Link**: http://arxiv.org/abs/2402.01411v2
  
  
- **Title**: SOEN-101: Code Generation by Emulating Software Process Models Using Large Language Model Agents
  - **Authors**: Feng Lin, Dong Jae Kim, Tse-Husn, Chen
  - **Published**: 2024-03-23
  - **Link**: http://arxiv.org/abs/2403.15852v2
  
  
- **Title**: MAGIS: LLM-Based Multi-Agent Framework for GitHub Issue Resolution
  - **Authors**: Wei Tao, Yucheng Zhou, Yanlin Wang, Wenqiang Zhang, Hongyu Zhang, Yu Cheng
  - **Published**: 2024-03-26
  - **Link**: http://arxiv.org/abs/2403.17927v2
  
  
- **Title**: Self-Organized Agents: A LLM Multi-Agent Framework toward Ultra Large-Scale Code Generation and Optimization
  - **Authors**: Yoichi Ishibashi, Yoshimasa Nishimura
  - **Published**: 2024-04-02
  - **Link**: http://arxiv.org/abs/2404.02183v1
  
  
- **Title**: LLM-Based Multi-Agent Systems for Software Engineering: Literature Review, Vision and the Road Ahead
  - **Authors**: Junda He, Christoph Treude, David Lo
  - **Published**: 2024-04-07
  - **Link**: http://arxiv.org/abs/2404.04834v3
  
  
- **Title**: A Unified Debugging Approach via LLM-Based Multi-Agent Synergy
  - **Authors**: Cheryl Lee, Chunqiu Steven Xia, Longji Yang, Jen-tse Huang, Zhouruixin Zhu, Lingming Zhang, Michael R. Lyu
  - **Published**: 2024-04-26
  - **Link**: http://arxiv.org/abs/2404.17153v2
  
  
- **Title**: MARE: Multi-Agents Collaboration Framework for Requirements Engineering
  - **Authors**: Dongming Jin, Zhi Jin, Xiaohong Chen, Chunhui Wang
  - **Published**: 2024-05-06
  - **Link**: http://arxiv.org/abs/2405.03256v1
  
  
- **Title**: DepsRAG: Towards Agentic Reasoning and Planning for Software Dependency Management
  - **Authors**: Mohannad Alhanahnah, Yazan Boshmaf
  - **Published**: 2024-05-30
  - **Link**: http://arxiv.org/abs/2405.20455v5
  
  
- **Title**: Experimenting with Multi-Agent Software Development: Towards a Unified Platform
  - **Authors**: Malik Abdul Sami, Muhammad Waseem, Zeeshan Rasheed, Mika Saari, Kari Systä, Pekka Abrahamsson
  - **Published**: 2024-06-08
  - **Link**: http://arxiv.org/abs/2406.05381v1
  
  
- **Title**: Multi-Agent Collaboration via Cross-Team Orchestration
  - **Authors**: Zhuoyun Du, Chen Qian, Wei Liu, Zihao Xie, YiFei Wang, Rennai Qiu, Yufan Dang, Weize Chen, Cheng Yang, Ye Tian, Xuantang Xiong, Lei Han
  - **Published**: 2024-06-13
  - **Link**: http://arxiv.org/abs/2406.08979v2
  
  
- **Title**: Agent-Driven Automatic Software Improvement
  - **Authors**: Fernando Vallecillos Ruiz
  - **Published**: 2024-06-24
  - **Link**: http://arxiv.org/abs/2406.16739v1
  
  
- **Title**: LAMBDA: A Large Model Based Data Agent
  - **Authors**: Maojun Sun, Ruijian Han, Binyan Jiang, Houduo Qi, Defeng Sun, Yancheng Yuan, Jian Huang
  - **Published**: 2024-07-24
  - **Link**: http://arxiv.org/abs/2407.17535v3
  
  
- **Title**: MAO: A Framework for Process Model Generation with Multi-Agent Orchestration
  - **Authors**: Leilei Lin, Yumeng Jin, Yingming Zhou, Wenlong Chen, Chen Qian
  - **Published**: 2024-08-04
  - **Link**: http://arxiv.org/abs/2408.01916v2
  
  
- **Title**: Diversity Empowers Intelligence: Integrating Expertise of Software Engineering Agents
  - **Authors**: Kexun Zhang, Weiran Yao, Zuxin Liu, Yihao Feng, Zhiwei Liu, Rithesh Murthy, Tian Lan, Lei Li, Renze Lou, Jiacheng Xu, Bo Pang, Yingbo Zhou, Shelby Heinecke, Silvio Savarese, Huan Wang, Caiming Xiong
  - **Published**: 2024-08-13
  - **Link**: http://arxiv.org/abs/2408.07060v1
  
  
- **Title**: Think-on-Process: Dynamic Process Generation for Collaborative Development of Multi-Agent System
  - **Authors**: Leilei Lin, Yingming Zhou, Wenlong Chen, Chen Qian
  - **Published**: 2024-09-10
  - **Link**: http://arxiv.org/abs/2409.06568v1
  
  
- **Title**: Agents in Software Engineering: Survey, Landscape, and Vision
  - **Authors**: Yanlin Wang, Wanjun Zhong, Yanxian Huang, Ensheng Shi, Min Yang, Jiachi Chen, Hui Li, Yuchi Ma, Qianxiang Wang, Zibin Zheng
  - **Published**: 2024-09-13
  - **Link**: http://arxiv.org/abs/2409.09030v2
  
  
- **Title**: MaCTG: Multi-Agent Collaborative Thought Graph for Automatic Programming
  - **Authors**: Zixiao Zhao, Jing Sun, Zhe Hou, Zhiyuan Wei, Cheng-Hao Cai, Miao Qiao, Jin Song Dong
  - **Published**: 2024-10-25
  - **Link**: http://arxiv.org/abs/2410.19245v2
  
  
- **Title**: RTLSquad: Multi-Agent Based Interpretable RTL Design
  - **Authors**: Bowei Wang, Qi Xiong, Zeqing Xiang, Lei Wang, Renzhi Chen
  - **Published**: 2025-01-06
  - **Link**: http://arxiv.org/abs/2501.05470v1
  
  
- **Title**: VulnBot: Autonomous Penetration Testing for A Multi-Agent Collaborative Framework
  - **Authors**: He Kong, Die Hu, Jingguo Ge, Liangxiong Li, Tong Li, Bingzhen Wu
  - **Published**: 2025-01-23
  - **Link**: http://arxiv.org/abs/2501.13411v1
  
  
- **Title**: SyncMind: Measuring Agent Out-of-Sync Recovery in Collaborative Software Engineering
  - **Authors**: Xuehang Guo, Xingyao Wang, Yangyi Chen, Sha Li, Chi Han, Manling Li, Heng Ji
  - **Published**: 2025-02-10
  - **Link**: http://arxiv.org/abs/2502.06994v2
  
  
- **Title**: Flow-of-Action: SOP Enhanced LLM-Based Multi-Agent System for Root Cause Analysis
  - **Authors**: Changhua Pei, Zexin Wang, Fengrui Liu, Zeyan Li, Yang Liu, Xiao He, Rong Kang, Tieying Zhang, Jianjun Chen, Jianhui Li, Gaogang Xie, Dan Pei
  - **Published**: 2025-02-12
  - **Link**: http://arxiv.org/abs/2502.08224v1
  
  
- **Title**: Teamwork makes the dream work: LLMs-Based Agents for GitHub README.MD Summarization
  - **Authors**: Duc S. H. Nguyen, Bach G. Truong, Phuong T. Nguyen, Juri Di Rocco, Davide Di Ruscio
  - **Published**: 2025-03-13
  - **Link**: http://arxiv.org/abs/2503.10876v1
  
  
- **Title**: Is Multi-Agent Debate (MAD) the Silver Bullet? An Empirical Analysis of MAD in Code Summarization and Translation
  - **Authors**: Jina Chun, Qihong Chen, Jiawei Li, Iftekhar Ahmed
  - **Published**: 2025-03-15
  - **Link**: http://arxiv.org/abs/2503.12029v1
  
  
- **Title**: AgentDroid: A Multi-Agent Framework for Detecting Fraudulent Android Applications
  - **Authors**: Ruwei Pan, Hongyu Zhang, Zhonghao Jiang, Ran Hou
  - **Published**: 2025-03-15
  - **Link**: http://arxiv.org/abs/2503.12163v1
  
  
- **Title**: Knowledge-Based Multi-Agent Framework for Automated Software Architecture Design
  - **Authors**: Yiran Zhang, Ruiyin Li, Peng Liang, Weisong Sun, Yang Liu
  - **Published**: 2025-03-26
  - **Link**: http://arxiv.org/abs/2503.20536v1
  
  
- **Title**: MooseAgent: A LLM Based Multi-agent Framework for Automating Moose Simulation
  - **Authors**: Tao Zhang, Zhenhai Liu, Yong Xin, Yongjun Jiao
  - **Published**: 2025-04-11
  - **Link**: http://arxiv.org/abs/2504.08621v1
  
  
- **Title**: Enhancing LLM Code Generation: A Systematic Evaluation of Multi-Agent Collaboration and Runtime Debugging for Improved Accuracy, Reliability, and Latency
  - **Authors**: Nazmus Ashrafi, Salah Bouktif, Mohammed Mediani
  - **Published**: 2025-05-04
  - **Link**: http://arxiv.org/abs/2505.02133v1
  
  
- **Title**: MARCO: Multi-Agent Code Optimization with Real-Time Knowledge Integration for High-Performance Computing
  - **Authors**: Asif Rahman, Veljko Cvetkovic, Kathleen Reece, Aidan Walters, Yasir Hassan, Aneesh Tummeti, Bryan Torres, Denise Cooney, Margaret Ellis, Dimitrios S. Nikolopoulos
  - **Published**: 2025-05-06
  - **Link**: http://arxiv.org/abs/2505.03906v3
  
  
- **Title**: Facilitating Trustworthy Human-Agent Collaboration in LLM-based Multi-Agent System oriented Software Engineering
  - **Authors**: Krishna Ronanki
  - **Published**: 2025-05-07
  - **Link**: http://arxiv.org/abs/2505.04251v1
  
  
- **Title**: Vibe Coding vs. Agentic Coding: Fundamentals and Practical Implications of Agentic AI
  - **Authors**: Ranjan Sapkota, Konstantinos I. Roumeliotis, Manoj Karkee
  - **Published**: 2025-05-26
  - **Link**: http://arxiv.org/abs/2505.19443v1
  
  
- **Title**: Co-Saving: Resource Aware Multi-Agent Collaboration for Software Development
  - **Authors**: Rennai Qiu, Chen Qian, Ran Li, Yufan Dang, Weize Chen, Cheng Yang, Yingli Zhang, Ye Tian, Xuantang Xiong, Lei Han, Zhiyuan Liu, Maosong Sun
  - **Published**: 2025-05-28
  - **Link**: http://arxiv.org/abs/2505.21898v1
  
  
- **Title**: Lessons Learned: A Multi-Agent Framework for Code LLMs to Learn and Improve
  - **Authors**: Yuanzhe Liu, Ryan Deng, Tim Kaler, Xuhao Chen, Charles E. Leiserson, Yao Ma, Jie Chen
  - **Published**: 2025-05-29
  - **Link**: http://arxiv.org/abs/2505.23946v1
  
  
- **Title**: Hallucination to Consensus: Multi-Agent LLMs for End-to-End Test Generation with Accurate Oracles
  - **Authors**: Qinghua Xu, Guancheng Wang, Lionel Briand, Kui Liu
  - **Published**: 2025-06-03
  - **Link**: http://arxiv.org/abs/2506.02943v4
  
  
- **Title**: Unified Software Engineering agent as AI Software Engineer
  - **Authors**: Leonhard Applis, Yuntong Zhang, Shanchao Liang, Nan Jiang, Lin Tan, Abhik Roychoudhury
  - **Published**: 2025-06-17
  - **Link**: http://arxiv.org/abs/2506.14683v1
  
  
- **Title**: LLM-based Multi-Agent System for Intelligent Refactoring of Haskell Code
  - **Authors**: Shahbaz Siddeeq, Muhammad Waseem, Zeeshan Rasheed, Md Mahade Hasan, Jussi Rasku, Mika Saari, Henri Terho, Kalle Makela, Kai-Kristian Kemell, Pekka Abrahamsson
  - **Published**: 2025-06-24
  - **Link**: http://arxiv.org/abs/2506.19481v1
  
  
- **Title**: Knowledge-Guided Multi-Agent Framework for Automated Requirements Development: A Vision
  - **Authors**: Jiangping Huang, Dongming Jin, Weisong Sun, Yang Liu, Zhi Jin
  - **Published**: 2025-06-27
  - **Link**: http://arxiv.org/abs/2506.22656v1
  
  
- **Title**: Multi-Agent Debate Strategies to Enhance Requirements Engineering with Large Language Models
  - **Authors**: Marc Oriol, Quim Motger, Jordi Marco, Xavier Franch
  - **Published**: 2025-07-08
  - **Link**: http://arxiv.org/abs/2507.05981v1
  
  
## Code Analysis and Quality Assurance
### Static Code Analysis and Bug Detection
- **Title**: How to Teach Programming in the AI Era? Using LLMs as a Teachable Agent for Debugging
  - **Authors**: Qianou Ma, Hua Shen, Kenneth Koedinger, Tongshuang Wu
  - **Published**: 2023-10-08
  - **Link**: http://arxiv.org/abs/2310.05292v5
  
  
- **Title**: Static Code Analysis in the AI Era: An In-depth Exploration of the Concept, Function, and Potential of Intelligent Code Analysis Agents
  - **Authors**: Gang Fan, Xiaoheng Xie, Xunjin Zheng, Yinan Liang, Peng Di
  - **Published**: 2023-10-13
  - **Link**: http://arxiv.org/abs/2310.08837v1
  
  
- **Title**: Identifying Performance-Sensitive Configurations in Software Systems through Code Analysis with LLM Agents
  - **Authors**: Zehao Wang, Dong Jae Kim, Tse-Hsun Chen
  - **Published**: 2024-06-18
  - **Link**: http://arxiv.org/abs/2406.12806v1
  
  
- **Title**: HyperAgent: Generalist Software Engineering Agents to Solve Coding Tasks at Scale
  - **Authors**: Huy Nhat Phan, Tien N. Nguyen, Phong X. Nguyen, Nghi D. Q. Bui
  - **Published**: 2024-09-09
  - **Link**: http://arxiv.org/abs/2409.16299v2
  
  
- **Title**: Agents in Software Engineering: Survey, Landscape, and Vision
  - **Authors**: Yanlin Wang, Wanjun Zhong, Yanxian Huang, Ensheng Shi, Min Yang, Jiachi Chen, Hui Li, Yuchi Ma, Qianxiang Wang, Zibin Zheng
  - **Published**: 2024-09-13
  - **Link**: http://arxiv.org/abs/2409.09030v2
  
  
- **Title**: AutoSafeCoder: A Multi-Agent Framework for Securing LLM Code Generation through Static Analysis and Fuzz Testing
  - **Authors**: Ana Nunez, Nafis Tanveer Islam, Sumit Kumar Jha, Peyman Najafirad
  - **Published**: 2024-09-16
  - **Link**: http://arxiv.org/abs/2409.10737v2
  
  
- **Title**: REDO: Execution-Free Runtime Error Detection for COding Agents
  - **Authors**: Shou Li, Andrey Kan, Laurent Callot, Bhavana Bhasker, Muhammad Shihab Rashid, Timothy B Esler
  - **Published**: 2024-10-10
  - **Link**: http://arxiv.org/abs/2410.09117v1
  
  
- **Title**: Seeker: Towards Exception Safety Code Generation with Intermediate Language Agents Framework
  - **Authors**: Xuanming Zhang, Yuxuan Chen, Yiming Zheng, Zhexin Zhang, Yuan Yuan, Minlie Huang
  - **Published**: 2024-12-16
  - **Link**: http://arxiv.org/abs/2412.11713v1
  
  
- **Title**: Defining and Detecting the Defects of the Large Language Model-based Autonomous Agents
  - **Authors**: Kaiwen Ning, Jiachi Chen, Jingwen Zhang, Wei Li, Zexu Wang, Yuming Feng, Weizhe Zhang, Zibin Zheng
  - **Published**: 2024-12-24
  - **Link**: http://arxiv.org/abs/2412.18371v2
  
  
- **Title**: RepoAudit: An Autonomous LLM-Agent for Repository-Level Code Auditing
  - **Authors**: Jinyao Guo, Chengpeng Wang, Xiangzhe Xu, Zian Su, Xiangyu Zhang
  - **Published**: 2025-01-30
  - **Link**: http://arxiv.org/abs/2501.18160v3
  
  
- **Title**: Benchmarking and Enhancing LLM Agents in Localizing Linux Kernel Bugs
  - **Authors**: Zhenhao Zhou, Zhuochen Huang, Yike He, Chong Wang, Jiajun Wang, Yijian Wu, Xin Peng, Yiling Lou
  - **Published**: 2025-05-26
  - **Link**: http://arxiv.org/abs/2505.19489v1
  
  
- **Title**: Code Researcher: Deep Research Agent for Large Systems Code and Commit History
  - **Authors**: Ramneet Singh, Sathvik Joel, Abhav Mehrotra, Nalin Wadhwa, Ramakrishna B Bairi, Aditya Kanade, Nagarajan Natarajan
  - **Published**: 2025-05-27
  - **Link**: http://arxiv.org/abs/2506.11060v1
  
  
- **Title**: An LLM Agent for Functional Bug Detection in Network Protocols
  - **Authors**: Mingwei Zheng, Chengpeng Wang, Xuwei Liu, Jinyao Guo, Shiwei Feng, Xiangyu Zhang
  - **Published**: 2025-05-31
  - **Link**: http://arxiv.org/abs/2506.00714v1
  
  
- **Title**: PAGENT: Learning to Patch Software Engineering Agents
  - **Authors**: Haoran Xue, Gias Uddin, Song Wang
  - **Published**: 2025-06-21
  - **Link**: http://arxiv.org/abs/2506.17772v1
  
  
- **Title**: LLM-based Multi-Agent System for Intelligent Refactoring of Haskell Code
  - **Authors**: Shahbaz Siddeeq, Muhammad Waseem, Zeeshan Rasheed, Md Mahade Hasan, Jussi Rasku, Mika Saari, Henri Terho, Kalle Makela, Kai-Kristian Kemell, Pekka Abrahamsson
  - **Published**: 2025-06-24
  - **Link**: http://arxiv.org/abs/2506.19481v1
  
  
### Code Review Automation
- **Title**: CodeAgent: Autonomous Communicative Agents for Code Review
  - **Authors**: Xunzhu Tang, Kisub Kim, Yewei Song, Cedric Lothritz, Bei Li, Saad Ezzini, Haoye Tian, Jacques Klein, Tegawende F. Bissyande
  - **Published**: 2024-02-03
  - **Link**: http://arxiv.org/abs/2402.02172v5
  
  
- **Title**: COAST: Enhancing the Code Debugging Ability of LLMs through Communicative Agent Based Data Synthesis
  - **Authors**: Weiqing Yang, Hanbin Wang, Zhenghao Liu, Xinze Li, Yukun Yan, Shuo Wang, Yu Gu, Minghe Yu, Zhiyuan Liu, Ge Yu
  - **Published**: 2024-08-09
  - **Link**: http://arxiv.org/abs/2408.05006v3
  
  
- **Title**: Agents in Software Engineering: Survey, Landscape, and Vision
  - **Authors**: Yanlin Wang, Wanjun Zhong, Yanxian Huang, Ensheng Shi, Min Yang, Jiachi Chen, Hui Li, Yuchi Ma, Qianxiang Wang, Zibin Zheng
  - **Published**: 2024-09-13
  - **Link**: http://arxiv.org/abs/2409.09030v2
  
  
- **Title**: Evaluating Software Development Agents: Patch Patterns, Code Quality, and Issue Complexity in Real-World GitHub Scenarios
  - **Authors**: Zhi Chen, Lingxiao Jiang
  - **Published**: 2024-10-16
  - **Link**: http://arxiv.org/abs/2410.12468v2
  
  
### Software Quality Assessment
- **Title**: CodeAgent: Autonomous Communicative Agents for Code Review
  - **Authors**: Xunzhu Tang, Kisub Kim, Yewei Song, Cedric Lothritz, Bei Li, Saad Ezzini, Haoye Tian, Jacques Klein, Tegawende F. Bissyande
  - **Published**: 2024-02-03
  - **Link**: http://arxiv.org/abs/2402.02172v5
  
  
- **Title**: Concept-Guided LLM Agents for Human-AI Safety Codesign
  - **Authors**: Florian Geissler, Karsten Roscher, Mario Trapp
  - **Published**: 2024-04-03
  - **Link**: http://arxiv.org/abs/2404.15317v1
  
  
- **Title**: GoNoGo: An Efficient LLM-based Multi-Agent System for Streamlining Automotive Software Release Decision-Making
  - **Authors**: Arsham Gholamzadeh Khoee, Yinan Yu, Robert Feldt, Andris Freimanis, Patrick Andersson Rhodin, Dhasarathy Parthasarathy
  - **Published**: 2024-08-19
  - **Link**: http://arxiv.org/abs/2408.09785v2
  
  
- **Title**: Agents in Software Engineering: Survey, Landscape, and Vision
  - **Authors**: Yanlin Wang, Wanjun Zhong, Yanxian Huang, Ensheng Shi, Min Yang, Jiachi Chen, Hui Li, Yuchi Ma, Qianxiang Wang, Zibin Zheng
  - **Published**: 2024-09-13
  - **Link**: http://arxiv.org/abs/2409.09030v2
  
  
- **Title**: Evaluating Software Development Agents: Patch Patterns, Code Quality, and Issue Complexity in Real-World GitHub Scenarios
  - **Authors**: Zhi Chen, Lingxiao Jiang
  - **Published**: 2024-10-16
  - **Link**: http://arxiv.org/abs/2410.12468v2
  
  
- **Title**: Seeker: Towards Exception Safety Code Generation with Intermediate Language Agents Framework
  - **Authors**: Xuanming Zhang, Yuxuan Chen, Yiming Zheng, Zhexin Zhang, Yuan Yuan, Minlie Huang
  - **Published**: 2024-12-16
  - **Link**: http://arxiv.org/abs/2412.11713v1
  
  
- **Title**: Defining and Detecting the Defects of the Large Language Model-based Autonomous Agents
  - **Authors**: Kaiwen Ning, Jiachi Chen, Jingwen Zhang, Wei Li, Zexu Wang, Yuming Feng, Weizhe Zhang, Zibin Zheng
  - **Published**: 2024-12-24
  - **Link**: http://arxiv.org/abs/2412.18371v2
  
  
- **Title**: Agentic AI Software Engineers: Programming with Trust
  - **Authors**: Abhik Roychoudhury, Corina Pasareanu, Michael Pradel, Baishakhi Ray
  - **Published**: 2025-02-19
  - **Link**: http://arxiv.org/abs/2502.13767v3
  
  
- **Title**: Human-In-The-Loop Software Development Agents: Challenges and Future Directions
  - **Authors**: Jirat Pasuksmit, Wannita Takerngsaksiri, Patanamon Thongtanunam, Chakkrit Tantithamthavorn, Ruixiong Zhang, Shiyan Wang, Fan Jiang, Jing Li, Evan Cook, Kun Chen, Ming Wu
  - **Published**: 2025-04-25
  - **Link**: http://arxiv.org/abs/2506.11009v1
  
  
- **Title**: OSS-UAgent: An Agent-based Usability Evaluation Framework for Open Source Software
  - **Authors**: Lingkai Meng, Yu Shao, Long Yuan, Longbin Lai, Peng Cheng, Wenyuan Yu, Wenjie Zhang, Xuemin Lin, Jingren Zhou
  - **Published**: 2025-05-29
  - **Link**: http://arxiv.org/abs/2505.23239v1
  
  
### Security and Vulnerability Analysis

- **Title**: CodeAgent: Autonomous Communicative Agents for Code Review
  - **Authors**: Xunzhu Tang, Kisub Kim, Yewei Song, Cedric Lothritz, Bei Li, Saad Ezzini, Haoye Tian, Jacques Klein, Tegawende F. Bissyande
  - **Published**: 2024-02-03
  - **Link**: http://arxiv.org/abs/2402.02172v5
  
  
- **Title**: Combining Fine-Tuning and LLM-based Agents for Intuitive Smart Contract Auditing with Justifications
  - **Authors**: Wei Ma, Daoyuan Wu, Yuqiang Sun, Tianwen Wang, Shangqing Liu, Jian Zhang, Yue Xue, Yang Liu
  - **Published**: 2024-03-24
  - **Link**: http://arxiv.org/abs/2403.16073v3
  
  
- **Title**: DepsRAG: Towards Agentic Reasoning and Planning for Software Dependency Management
  - **Authors**: Mohannad Alhanahnah, Yazan Boshmaf
  - **Published**: 2024-05-30
  - **Link**: http://arxiv.org/abs/2405.20455v5
  
  
- **Title**: Experimenting with Multi-Agent Software Development: Towards a Unified Platform
  - **Authors**: Malik Abdul Sami, Muhammad Waseem, Zeeshan Rasheed, Mika Saari, Kari Systä, Pekka Abrahamsson
  - **Published**: 2024-06-08
  - **Link**: http://arxiv.org/abs/2406.05381v1
  
  
- **Title**: Agents in Software Engineering: Survey, Landscape, and Vision
  - **Authors**: Yanlin Wang, Wanjun Zhong, Yanxian Huang, Ensheng Shi, Min Yang, Jiachi Chen, Hui Li, Yuchi Ma, Qianxiang Wang, Zibin Zheng
  - **Published**: 2024-09-13
  - **Link**: http://arxiv.org/abs/2409.09030v2
  
  
- **Title**: AutoSafeCoder: A Multi-Agent Framework for Securing LLM Code Generation through Static Analysis and Fuzz Testing
  - **Authors**: Ana Nunez, Nafis Tanveer Islam, Sumit Kumar Jha, Peyman Najafirad
  - **Published**: 2024-09-16
  - **Link**: http://arxiv.org/abs/2409.10737v2
  
  
- **Title**: RedCode: Risky Code Execution and Generation Benchmark for Code Agents
  - **Authors**: Chengquan Guo, Xun Liu, Chulin Xie, Andy Zhou, Yi Zeng, Zinan Lin, Dawn Song, Bo Li
  - **Published**: 2024-11-12
  - **Link**: http://arxiv.org/abs/2411.07781v1
  
  
- **Title**: EvalSVA: Multi-Agent Evaluators for Next-Gen Software Vulnerability Assessment
  - **Authors**: Xin-Cheng Wen, Jiaxin Ye, Cuiyun Gao, Lianwei Wu, Qing Liao
  - **Published**: 2024-12-11
  - **Link**: http://arxiv.org/abs/2501.14737v1
  
  
- **Title**: VulnBot: Autonomous Penetration Testing for A Multi-Agent Collaborative Framework
  - **Authors**: He Kong, Die Hu, Jingguo Ge, Liangxiong Li, Tong Li, Bingzhen Wu
  - **Published**: 2025-01-23
  - **Link**: http://arxiv.org/abs/2501.13411v1
  
  
- **Title**: A Multi-Agent Framework for Automated Vulnerability Detection and Repair in Solidity and Move Smart Contracts
  - **Authors**: Rabimba Karanjai, Sam Blackshear, Lei Xu, Weidong Shi
  - **Published**: 2025-02-22
  - **Link**: http://arxiv.org/abs/2502.18515v1
  
  
- **Title**: AgentDroid: A Multi-Agent Framework for Detecting Fraudulent Android Applications
  - **Authors**: Ruwei Pan, Hongyu Zhang, Zhonghao Jiang, Ran Hou
  - **Published**: 2025-03-15
  - **Link**: http://arxiv.org/abs/2503.12163v1
  
  
- **Title**: Agent That Debugs: Dynamic State-Guided Vulnerability Repair
  - **Authors**: Zhengyao Liu, Yunlong Ma, Jingxuan Xu, Junchen Ai, Xiang Gao, Hailong Sun, Abhik Roychoudhury
  - **Published**: 2025-04-10
  - **Link**: http://arxiv.org/abs/2504.07634v1
  
  
- **Title**: A Survey on the Safety and Security Threats of Computer-Using Agents: JARVIS or Ultron?
  - **Authors**: Ada Chen, Yongjiang Wu, Junyuan Zhang, Jingyu Xiao, Shu Yang, Jen-tse Huang, Kun Wang, Wenxuan Wang, Shuai Wang
  - **Published**: 2025-05-16
  - **Link**: http://arxiv.org/abs/2505.10924v2
  
  
- **Title**: GUARD:Dual-Agent based Backdoor Defense on Chain-of-Thought in Neural Code Generation
  - **Authors**: Naizhu Jin, Zhong Li, Tian Zhang, Qingkai Zeng
  - **Published**: 2025-05-27
  - **Link**: http://arxiv.org/abs/2505.21425v2
  
  
- **Title**: An LLM Agent for Functional Bug Detection in Network Protocols
  - **Authors**: Mingwei Zheng, Chengpeng Wang, Xuwei Liu, Jinyao Guo, Shiwei Feng, Xiangyu Zhang
  - **Published**: 2025-05-31
  - **Link**: http://arxiv.org/abs/2506.00714v1
  
  
- **Title**: OS-Harm: A Benchmark for Measuring Safety of Computer Use Agents
  - **Authors**: Thomas Kuntz, Agatha Duzan, Hao Zhao, Francesco Croce, Zico Kolter, Nicolas Flammarion, Maksym Andriushchenko
  - **Published**: 2025-06-17
  - **Link**: http://arxiv.org/abs/2506.14866v1
  
  
- **Title**: Are AI-Generated Fixes Secure? Analyzing LLM and Agent Patches on SWE-bench
  - **Authors**: Amirali Sajadi, Kostadin Damevski, Preetha Chatterjee
  - **Published**: 2025-06-30
  - **Link**: http://arxiv.org/abs/2507.02976v1
  
  
## Automated Testing and Validation
### API Testing and Service Validation
- **Title**: Experimenting with Multi-Agent Software Development: Towards a Unified Platform
  - **Authors**: Malik Abdul Sami, Muhammad Waseem, Zeeshan Rasheed, Mika Saari, Kari Systä, Pekka Abrahamsson
  - **Published**: 2024-06-08
  - **Link**: http://arxiv.org/abs/2406.05381v1
  
  
- **Title**: ShortcutsBench: A Large-Scale Real-world Benchmark for API-based Agents
  - **Authors**: Haiyang Shen, Yue Li, Desong Meng, Dongqi Cai, Sheng Qi, Li Zhang, Mengwei Xu, Yun Ma
  - **Published**: 2024-06-28
  - **Link**: http://arxiv.org/abs/2407.00132v3
  
  
- **Title**: Agents in Software Engineering: Survey, Landscape, and Vision
  - **Authors**: Yanlin Wang, Wanjun Zhong, Yanxian Huang, Ensheng Shi, Min Yang, Jiachi Chen, Hui Li, Yuchi Ma, Qianxiang Wang, Zibin Zheng
  - **Published**: 2024-09-13
  - **Link**: http://arxiv.org/abs/2409.09030v2
  
  
- **Title**: A Multi-Agent Approach for REST API Testing with Semantic Graphs and LLM-Driven Inputs
  - **Authors**: Myeongsoo Kim, Tyler Stennett, Saurabh Sinha, Alessandro Orso
  - **Published**: 2024-11-11
  - **Link**: http://arxiv.org/abs/2411.07098v2
  
  
- **Title**: LogiAgent: Automated Logical Testing for REST Systems with LLM-Based Multi-Agents
  - **Authors**: Ke Zhang, Chenxi Zhang, Chong Wang, Chi Zhang, YaChen Wu, Zhenchang Xing, Yang Liu, Qingshan Li, Xin Peng
  - **Published**: 2025-03-19
  - **Link**: http://arxiv.org/abs/2503.15079v1
  
  
- **Title**: Are Autonomous Web Agents Good Testers?
  - **Authors**: Antoine Chevrot, Alexandre Vernotte, Jean-Rémy Falleri, Xavier Blanc, Bruno Legeard
  - **Published**: 2025-04-02
  - **Link**: http://arxiv.org/abs/2504.01495v1
  
  
- **Title**: Test Amplification for REST APIs via Single and Multi-Agent LLM Systems
  - **Authors**: Robbe Nooyens, Tolgahan Bardakci, Mutlu Beyazit, Serge Demeyer
  - **Published**: 2025-04-10
  - **Link**: http://arxiv.org/abs/2504.08113v1
  
  
- **Title**: IEA-Plugin: An AI Agent Reasoner for Test Data Analytics
  - **Authors**: Seoyeon Kim, Yu Su, Li-C. Wang
  - **Published**: 2025-04-14
  - **Link**: http://arxiv.org/abs/2504.11496v1
  
  
- **Title**: IntenTest: Stress Testing for Intent Integrity in API-Calling LLM Agents
  - **Authors**: Shiwei Feng, Xiangzhe Xu, Xuan Chen, Kaiyuan Zhang, Syed Yusuf Ahmed, Zian Su, Mingwei Zheng, Xiangyu Zhang
  - **Published**: 2025-06-09
  - **Link**: http://arxiv.org/abs/2506.07524v1
  
  
### Unit Testing and Test Generation
- **Title**: Large Language Model Evaluation Via Multi AI Agents: Preliminary results
  - **Authors**: Zeeshan Rasheed, Muhammad Waseem, Kari Systä, Pekka Abrahamsson
  - **Published**: 2024-04-01
  - **Link**: http://arxiv.org/abs/2404.01023v1
  
  
- **Title**: Experimenting with Multi-Agent Software Development: Towards a Unified Platform
  - **Authors**: Malik Abdul Sami, Muhammad Waseem, Zeeshan Rasheed, Mika Saari, Kari Systä, Pekka Abrahamsson
  - **Published**: 2024-06-08
  - **Link**: http://arxiv.org/abs/2406.05381v1
  
  
- **Title**: SWT-Bench: Testing and Validating Real-World Bug-Fixes with Code Agents
  - **Authors**: Niels Mündler, Mark Niklas Müller, Jingxuan He, Martin Vechev
  - **Published**: 2024-06-18
  - **Link**: http://arxiv.org/abs/2406.12952v3
  
  
- **Title**: From LLMs to LLM-based Agents for Software Engineering: A Survey of Current, Challenges and Future
  - **Authors**: Haolin Jin, Linghan Huang, Haipeng Cai, Jun Yan, Bo Li, Huaming Chen
  - **Published**: 2024-08-05
  - **Link**: http://arxiv.org/abs/2408.02479v2
  
  
- **Title**: Agents in Software Engineering: Survey, Landscape, and Vision
  - **Authors**: Yanlin Wang, Wanjun Zhong, Yanxian Huang, Ensheng Shi, Min Yang, Jiachi Chen, Hui Li, Yuchi Ma, Qianxiang Wang, Zibin Zheng
  - **Published**: 2024-09-13
  - **Link**: http://arxiv.org/abs/2409.09030v2
  
  
- **Title**: RedCode: Risky Code Execution and Generation Benchmark for Code Agents
  - **Authors**: Chengquan Guo, Xun Liu, Chulin Xie, Andy Zhou, Yi Zeng, Zinan Lin, Dawn Song, Bo Li
  - **Published**: 2024-11-12
  - **Link**: http://arxiv.org/abs/2411.07781v1
  
  
- **Title**: You Name It, I Run It: An LLM Agent to Execute Tests of Arbitrary Projects
  - **Authors**: Islem Bouzenia, Michael Pradel
  - **Published**: 2024-12-13
  - **Link**: http://arxiv.org/abs/2412.10133v2
  
  
- **Title**: CodeCoR: An LLM-Based Self-Reflective Multi-Agent Framework for Code Generation
  - **Authors**: Ruwei Pan, Hongyu Zhang, Chao Liu
  - **Published**: 2025-01-14
  - **Link**: http://arxiv.org/abs/2501.07811v1
  
  
- **Title**: ToolFuzz -- Automated Agent Tool Testing
  - **Authors**: Ivan Milev, Mislav Balunović, Maximilian Baader, Martin Vechev
  - **Published**: 2025-03-06
  - **Link**: http://arxiv.org/abs/2503.04479v3
  
  
- **Title**: Fully Autonomous Programming using Iterative Multi-Agent Debugging with Large Language Models
  - **Authors**: Anastasiia Grishina, Vadim Liventsev, Aki Härmä, Leon Moonen
  - **Published**: 2025-03-10
  - **Link**: http://arxiv.org/abs/2503.07693v1
  
  
- **Title**: TestForge: Feedback-Driven, Agentic Test Suite Generation
  - **Authors**: Kush Jain, Claire Le Goues
  - **Published**: 2025-03-18
  - **Link**: http://arxiv.org/abs/2503.14713v1
  
  
- **Title**: AdaCoder: An Adaptive Planning and Multi-Agent Framework for Function-Level Code Generation
  - **Authors**: Yueheng Zhu, Chao Liu, Xuan He, Xiaoxue Ren, Zhongxin Liu, Ruwei Pan, Hongyu Zhang
  - **Published**: 2025-04-05
  - **Link**: http://arxiv.org/abs/2504.04220v1
  
  
- **Title**: Hallucination to Consensus: Multi-Agent LLMs for End-to-End Test Generation with Accurate Oracles
  - **Authors**: Qinghua Xu, Guancheng Wang, Lionel Briand, Kui Liu
  - **Published**: 2025-06-03
  - **Link**: http://arxiv.org/abs/2506.02943v4
  
  
- **Title**: UTBoost: Rigorous Evaluation of Coding Agents on SWE-Bench
  - **Authors**: Boxi Yu, Yuxuan Zhu, Pinjia He, Daniel Kang
  - **Published**: 2025-06-10
  - **Link**: http://arxiv.org/abs/2506.09289v1
  
  
### System Testing and Integration
- **Title**: Autonomous Large Language Model Agents Enabling Intent-Driven Mobile GUI Testing
  - **Authors**: Juyeon Yoon, Robert Feldt, Shin Yoo
  - **Published**: 2023-11-15
  - **Link**: http://arxiv.org/abs/2311.08649v1
  
  
- **Title**: Experimenting with Multi-Agent Software Development: Towards a Unified Platform
  - **Authors**: Malik Abdul Sami, Muhammad Waseem, Zeeshan Rasheed, Mika Saari, Kari Systä, Pekka Abrahamsson
  - **Published**: 2024-06-08
  - **Link**: http://arxiv.org/abs/2406.05381v1
  
  
- **Title**: Agents in Software Engineering: Survey, Landscape, and Vision
  - **Authors**: Yanlin Wang, Wanjun Zhong, Yanxian Huang, Ensheng Shi, Min Yang, Jiachi Chen, Hui Li, Yuchi Ma, Qianxiang Wang, Zibin Zheng
  - **Published**: 2024-09-13
  - **Link**: http://arxiv.org/abs/2409.09030v2
  
  
- **Title**: SLA Management in Reconfigurable Multi-Agent RAG: A Systems Approach to Question Answering
  - **Authors**: Michael Iannelli, Sneha Kuchipudi, Vera Dvorak
  - **Published**: 2024-12-07
  - **Link**: http://arxiv.org/abs/2412.06832v2
  
  
- **Title**: You Name It, I Run It: An LLM Agent to Execute Tests of Arbitrary Projects
  - **Authors**: Islem Bouzenia, Michael Pradel
  - **Published**: 2024-12-13
  - **Link**: http://arxiv.org/abs/2412.10133v2
  
  
- **Title**: LLM-Agents Driven Automated Simulation Testing and Analysis of small Uncrewed Aerial Systems
  - **Authors**: Venkata Sai Aswath Duvvuru, Bohan Zhang, Michael Vierhauser, Ankit Agrawal
  - **Published**: 2025-01-21
  - **Link**: http://arxiv.org/abs/2501.11864v1
  
  
- **Title**: Are Autonomous Web Agents Good Testers?
  - **Authors**: Antoine Chevrot, Alexandre Vernotte, Jean-Rémy Falleri, Xavier Blanc, Bruno Legeard
  - **Published**: 2025-04-02
  - **Link**: http://arxiv.org/abs/2504.01495v1
  
  
- **Title**: Temac: Multi-Agent Collaboration for Automated Web GUI Testing
  - **Authors**: Chenxu Liu, Zhiyu Gu, Guoquan Wu, Ying Zhang, Jun Wei, Tao Xie
  - **Published**: 2025-05-31
  - **Link**: http://arxiv.org/abs/2506.00520v1
  
  
### Multi-User Interactive Testing

- **Title**: Agent for User: Testing Multi-User Interactive Features in TikTok
  - **Authors**: Sidong Feng, Changhao Du, Huaxiao Liu, Qingnan Wang, Zhengwei Lv, Gang Huo, Xu Yang, Chunyang Chen
  - **Published**: 2025-04-21
  - **Link**: http://arxiv.org/abs/2504.15474v1
  
  
- **Title**: Temac: Multi-Agent Collaboration for Automated Web GUI Testing
  - **Authors**: Chenxu Liu, Zhiyu Gu, Guoquan Wu, Ying Zhang, Jun Wei, Tao Xie
  - **Published**: 2025-05-31
  - **Link**: http://arxiv.org/abs/2506.00520v1
  
  
- **Title**: Breaking Single-Tester Limits: Multi-Agent LLMs for Multi-User Feature Testing
  - **Authors**: Sidong Feng, Changhao Du, Huaxiao Liu, Qingnan Wang, Zhengwei Lv, Mengfei Wang, Chunyang Chen
  - **Published**: 2025-06-21
  - **Link**: http://arxiv.org/abs/2506.17539v2
  
  
## Industrial Applications and Domain-Specific Solutions
### Smart Manufacturing and Industrial Automation
- **Title**: Towards autonomous system: flexible modular production system enhanced with large language model agents
  - **Authors**: Yuchen Xia, Manthan Shenoy, Nasser Jazdi, Michael Weyrich
  - **Published**: 2023-04-28
  - **Link**: http://arxiv.org/abs/2304.14721v4
  
  
- **Title**: Agents4PLC: Automating Closed-loop PLC Code Generation and Verification in Industrial Control Systems using LLM-based Agents
  - **Authors**: Zihan Liu, Ruinan Zeng, Dongxia Wang, Gengyun Peng, Jingyi Wang, Qiang Liu, Peiyu Liu, Wenhai Wang
  - **Published**: 2024-10-18
  - **Link**: http://arxiv.org/abs/2410.14209v2
  
  
- **Title**: SceneGenAgent: Precise Industrial Scene Generation with Coding Agent
  - **Authors**: Xiao Xia, Dan Zhang, Zibo Liao, Zhenyu Hou, Tianrui Sun, Jing Li, Ling Fu, Yuxiao Dong
  - **Published**: 2024-10-29
  - **Link**: http://arxiv.org/abs/2410.21909v3
  
  
### Cloud Systems and Infrastructure Management
- **Title**: RCAgent: Cloud Root Cause Analysis by Autonomous Agents with Tool-Augmented Large Language Models
  - **Authors**: Zefan Wang, Zichuan Liu, Yingying Zhang, Aoxiao Zhong, Jihong Wang, Fengbin Yin, Lunting Fan, Lingfei Wu, Qingsong Wen
  - **Published**: 2023-10-25
  - **Link**: http://arxiv.org/abs/2310.16340v3
  
  
- **Title**: Exploring LLM-based Agents for Root Cause Analysis
  - **Authors**: Devjeet Roy, Xuchao Zhang, Rashi Bhave, Chetan Bansal, Pedro Las-Casas, Rodrigo Fonseca, Saravan Rajmohan
  - **Published**: 2024-03-07
  - **Link**: http://arxiv.org/abs/2403.04123v1
  
  
- **Title**: Building AI Agents for Autonomous Clouds: Challenges and Design Principles
  - **Authors**: Manish Shetty, Yinfang Chen, Gagan Somashekar, Minghua Ma, Yogesh Simmhan, Xuchao Zhang, Jonathan Mace, Dax Vandevoorde, Pedro Las-Casas, Shachee Mishra Gupta, Suman Nath, Chetan Bansal, Saravan Rajmohan
  - **Published**: 2024-07-16
  - **Link**: http://arxiv.org/abs/2407.12165v2
  
  
- **Title**: SLA Management in Reconfigurable Multi-Agent RAG: A Systems Approach to Question Answering
  - **Authors**: Michael Iannelli, Sneha Kuchipudi, Vera Dvorak
  - **Published**: 2024-12-07
  - **Link**: http://arxiv.org/abs/2412.06832v2
  
  
- **Title**: AIOpsLab: A Holistic Framework to Evaluate AI Agents for Enabling Autonomous Clouds
  - **Authors**: Yinfang Chen, Manish Shetty, Gagan Somashekar, Minghua Ma, Yogesh Simmhan, Jonathan Mace, Chetan Bansal, Rujia Wang, Saravan Rajmohan
  - **Published**: 2025-01-12
  - **Link**: http://arxiv.org/abs/2501.06706v1
  
  
- **Title**: Enabling Autonomic Microservice Management through Self-Learning Agents
  - **Authors**: Fenglin Yu, Fangkai Yang, Xiaoting Qin, Zhiyang Zhang, Jue Zhang, Qingwei Lin, Hongyu Zhang, Yingnong Dang, Saravan Rajmohan, Dongmei Zhang, Qi Zhang
  - **Published**: 2025-01-31
  - **Link**: http://arxiv.org/abs/2501.19056v1
  
  
- **Title**: AgentFM: Role-Aware Failure Management for Distributed Databases with LLM-Driven Multi-Agents
  - **Authors**: Lingzhe Zhang, Yunpeng Zhai, Tong Jia, Xiaosong Huang, Chiming Duan, Ying Li
  - **Published**: 2025-04-09
  - **Link**: http://arxiv.org/abs/2504.06614v1
  
  
### Network Configuration and Management
- **Title**: Leveraging LLM Agents for Translating Network Configurations
  - **Authors**: Yunze Wei, Xiaohui Xie, Yiwei Zuo, Tianshuo Hu, Xinyi Chen, Kaiwen Chi, Yong Cui
  - **Published**: 2025-01-15
  - **Link**: http://arxiv.org/abs/2501.08760v1
  
  
- **Title**: KP-A: A Unified Network Knowledge Plane for Catalyzing Agentic Network Intelligence
  - **Authors**: Yun Tang, Mengbang Zou, Zeinab Nezami, Syed Ali Raza Zaidi, Weisi Guo
  - **Published**: 2025-07-10
  - **Link**: http://arxiv.org/abs/2507.08164v1
  
  
### Electronic Design Automation
- **Title**: CoopetitiveV: Leveraging LLM-powered Coopetitive Multi-Agent Prompting for High-quality Verilog Generation
  - **Authors**: Zhendong Mi, Renming Zheng, Haowen Zhong, Yue Sun, Seth Kneeland, Sayan Moitra, Ken Kutzer, Zhaozhuo Xu Shaoyi Huang
  - **Published**: 2024-12-15
  - **Link**: http://arxiv.org/abs/2412.11014v2
  
  
- **Title**: RTLSquad: Multi-Agent Based Interpretable RTL Design
  - **Authors**: Bowei Wang, Qi Xiong, Zeqing Xiang, Lei Wang, Renzhi Chen
  - **Published**: 2025-01-06
  - **Link**: http://arxiv.org/abs/2501.05470v1
  
  
- **Title**: Nexus: A Lightweight and Scalable Multi-Agent Framework for Complex Tasks Automation
  - **Authors**: Humza Sami, Mubashir ul Islam, Samy Charas, Asav Gandhi, Pierre-Emmanuel Gaillardon, Valerio Tenace
  - **Published**: 2025-02-26
  - **Link**: http://arxiv.org/abs/2502.19091v1
  
  
- **Title**: Timing Analysis Agent: Autonomous Multi-Corner Multi-Mode (MCMM) Timing Debugging with Timing Debug Relation Graph
  - **Authors**: Jatin Nainani, Chia-Tung Ho, Anirudh Dhurka, Haoxing Ren
  - **Published**: 2025-04-15
  - **Link**: http://arxiv.org/abs/2504.11502v1
  
  
- **Title**: JARVIS: A Multi-Agent Code Assistant for High-Quality EDA Script Generation
  - **Authors**: Ghasem Pasandi, Kishor Kunal, Varun Tej, Kunjal Shan, Hanfei Sun, Sumit Jain, Chunhui Li, Chenhui Deng, Teodor-Dumitru Ene, Haoxing Ren, Sreedhar Pratty
  - **Published**: 2025-05-20
  - **Link**: http://arxiv.org/abs/2505.14978v1
  
  
- **Title**: BugGen: A Self-Correcting Multi-Agent LLM Pipeline for Realistic RTL Bug Synthesis
  - **Authors**: Surya Jasper, Minh Luu, Evan Pan, Aakash Tyagi, Michael Quinn, Jiang Hu, David Kebo Houngninou
  - **Published**: 2025-06-12
  - **Link**: http://arxiv.org/abs/2506.10501v2
  
  
### Policy as Code and Compliance Automation

- **Title**: Representing Prompting Patterns with PDL: Compliance Agent Case Study
  - **Authors**: Mandana Vaziri, Louis Mandel, Yuji Watanabe, Hirokuni Kitahara, Martin Hirzel, Anca Sailer
  - **Published**: 2025-07-08
  - **Link**: http://arxiv.org/abs/2507.06396v1
  
  
- **Title**: ARPaCCino: An Agentic-RAG for Policy as Code Compliance
  - **Authors**: Francesco Romeo, Luigi Arena, Francesco Blefari, Francesco Aurelio Pironti, Matteo Lupinacci, Angelo Furfaro
  - **Published**: 2025-07-11
  - **Link**: http://arxiv.org/abs/2507.10584v1
  
  
## Educational and Research Applications
### Programming Education and Learning Support
- **Title**: ChatLogo: A Large Language Model-Driven Hybrid Natural-Programming Language Interface for Agent-based Modeling and Programming
  - **Authors**: John Chen, Uri Wilensky
  - **Published**: 2023-08-16
  - **Link**: http://arxiv.org/abs/2308.08102v1
  
  
- **Title**: How to Teach Programming in the AI Era? Using LLMs as a Teachable Agent for Debugging
  - **Authors**: Qianou Ma, Hua Shen, Kenneth Koedinger, Tongshuang Wu
  - **Published**: 2023-10-08
  - **Link**: http://arxiv.org/abs/2310.05292v5
  
  
- **Title**: Co-Learning: Code Learning for Multi-Agent Reinforcement Collaborative Framework with Conversational Natural Language Interfaces
  - **Authors**: Jiapeng Yu, Yuqian Wu, Yajing Zhan, Wenhao Guo, Zhou Xu, Raymond Lee
  - **Published**: 2024-09-02
  - **Link**: http://arxiv.org/abs/2409.00985v1
  
  
- **Title**: Agents in Software Engineering: Survey, Landscape, and Vision
  - **Authors**: Yanlin Wang, Wanjun Zhong, Yanxian Huang, Ensheng Shi, Min Yang, Jiachi Chen, Hui Li, Yuchi Ma, Qianxiang Wang, Zibin Zheng
  - **Published**: 2024-09-13
  - **Link**: http://arxiv.org/abs/2409.09030v2
  
  
- **Title**: VTutor: An Open-Source SDK for Generative AI-Powered Animated Pedagogical Agents with Multi-Media Output
  - **Authors**: Eason Chen, Chenyu Lin, Xinyi Tang, Aprille Xi, Canwen Wang, Jionghao Lin, Kenneth R Koedinger
  - **Published**: 2025-02-06
  - **Link**: http://arxiv.org/abs/2502.04103v2
  
  
- **Title**: An Empirical Study of Multi-Agent RAG for Real-World University Admissions Counseling
  - **Authors**: Anh Nguyen-Duc, Chien Vu Manh, Bao Anh Tran, Viet Phuong Ngo, Luan Le Chi, Anh Quang Nguyen
  - **Published**: 2025-07-15
  - **Link**: http://arxiv.org/abs/2507.11272v1
  
  
### Research Methodology and Literature Analysis
- **Title**: Can Large Language Models Serve as Data Analysts? A Multi-Agent Assisted Approach for Qualitative Data Analysis
  - **Authors**: Zeeshan Rasheed, Muhammad Waseem, Aakash Ahmad, Kai-Kristian Kemell, Wang Xiaofeng, Anh Nguyen Duc, Pekka Abrahamsson
  - **Published**: 2024-02-02
  - **Link**: http://arxiv.org/abs/2402.01386v1
  
  
- **Title**: System for systematic literature review using multiple AI agents: Concept and an empirical evaluation
  - **Authors**: Abdul Malik Sami, Zeeshan Rasheed, Kai-Kristian Kemell, Muhammad Waseem, Terhi Kilamo, Mika Saari, Anh Nguyen Duc, Kari Systä, Pekka Abrahamsson
  - **Published**: 2024-03-13
  - **Link**: http://arxiv.org/abs/2403.08399v1
  
  
- **Title**: LLM-Based Multi-Agent Systems for Software Engineering: Literature Review, Vision and the Road Ahead
  - **Authors**: Junda He, Christoph Treude, David Lo
  - **Published**: 2024-04-07
  - **Link**: http://arxiv.org/abs/2404.04834v3
  
  
- **Title**: A Review of Prominent Paradigms for LLM-Based Agents: Tool Use (Including RAG), Planning, and Feedback Learning
  - **Authors**: Xinzhe Li
  - **Published**: 2024-06-09
  - **Link**: http://arxiv.org/abs/2406.05804v6
  
  
- **Title**: Large Language Model-Based Agents for Software Engineering: A Survey
  - **Authors**: Junwei Liu, Kaixin Wang, Yixuan Chen, Xin Peng, Zhenpeng Chen, Lingming Zhang, Yiling Lou
  - **Published**: 2024-09-04
  - **Link**: http://arxiv.org/abs/2409.02977v1
  
  
- **Title**: Agents in Software Engineering: Survey, Landscape, and Vision
  - **Authors**: Yanlin Wang, Wanjun Zhong, Yanxian Huang, Ensheng Shi, Min Yang, Jiachi Chen, Hui Li, Yuchi Ma, Qianxiang Wang, Zibin Zheng
  - **Published**: 2024-09-13
  - **Link**: http://arxiv.org/abs/2409.09030v2
  
  
- **Title**: ResearchCodeAgent: An LLM Multi-Agent System for Automated Codification of Research Methodologies
  - **Authors**: Shubham Gandhi, Dhruv Shah, Manasi Patwardhan, Lovekesh Vig, Gautam Shroff
  - **Published**: 2025-04-28
  - **Link**: http://arxiv.org/abs/2504.20117v2
  
  
- **Title**: LMR-BENCH: Evaluating LLM Agent's Ability on Reproducing Language Modeling Research
  - **Authors**: Shuo Yan, Ruochen Li, Ziming Luo, Zimu Wang, Daoyang Li, Liqiang Jing, Kaiyu He, Peilin Wu, George Michalopoulos, Yue Zhang, Ziyang Zhang, Mian Zhang, Zhiyu Chen, Xinya Du
  - **Published**: 2025-06-19
  - **Link**: http://arxiv.org/abs/2506.17335v1
  
  
### Agent-Based Modeling and Simulation
- **Title**: ChatLogo: A Large Language Model-Driven Hybrid Natural-Programming Language Interface for Agent-based Modeling and Programming
  - **Authors**: John Chen, Uri Wilensky
  - **Published**: 2023-08-16
  - **Link**: http://arxiv.org/abs/2308.08102v1
  
  
- **Title**: SWE-rebench: An Automated Pipeline for Task Collection and Decontaminated Evaluation of Software Engineering Agents
  - **Authors**: Ibragim Badertdinov, Alexander Golubev, Maksim Nekrashevich, Anton Shevtsov, Simon Karasik, Andrei Andriushchenko, Maria Trofimova, Daria Litvintseva, Boris Yangel
  - **Published**: 2025-05-26
  - **Link**: http://arxiv.org/abs/2505.20411v1
  
  
- **Title**: OSS-UAgent: An Agent-based Usability Evaluation Framework for Open Source Software
  - **Authors**: Lingkai Meng, Yu Shao, Long Yuan, Longbin Lai, Peng Cheng, Wenyuan Yu, Wenjie Zhang, Xuemin Lin, Jingren Zhou
  - **Published**: 2025-05-29
  - **Link**: http://arxiv.org/abs/2505.23239v1
  
  
### Evaluation and Benchmarking Systems

- **Title**: Autonomous Agents in Software Development: A Vision Paper
  - **Authors**: Zeeshan Rasheed, Muhammad Waseem, Kai-Kristian Kemell, Wang Xiaofeng, Anh Nguyen Duc, Kari Systä, Pekka Abrahamsson
  - **Published**: 2023-11-30
  - **Link**: http://arxiv.org/abs/2311.18440v1
  
  
- **Title**: CodeAgent: Enhancing Code Generation with Tool-Integrated Agent Systems for Real-World Repo-level Coding Challenges
  - **Authors**: Kechi Zhang, Jia Li, Ge Li, Xianjie Shi, Zhi Jin
  - **Published**: 2024-01-14
  - **Link**: http://arxiv.org/abs/2401.07339v2
  
  
- **Title**: Understanding the Weakness of Large Language Model Agents within a Complex Android Environment
  - **Authors**: Mingzhe Xing, Rongkai Zhang, Hui Xue, Qi Chen, Fan Yang, Zhen Xiao
  - **Published**: 2024-02-09
  - **Link**: http://arxiv.org/abs/2402.06596v1
  
  
- **Title**: SOEN-101: Code Generation by Emulating Software Process Models Using Large Language Model Agents
  - **Authors**: Feng Lin, Dong Jae Kim, Tse-Husn, Chen
  - **Published**: 2024-03-23
  - **Link**: http://arxiv.org/abs/2403.15852v2
  
  
- **Title**: Large Language Model Evaluation Via Multi AI Agents: Preliminary results
  - **Authors**: Zeeshan Rasheed, Muhammad Waseem, Kari Systä, Pekka Abrahamsson
  - **Published**: 2024-04-01
  - **Link**: http://arxiv.org/abs/2404.01023v1
  
  
- **Title**: HumanEvalComm: Benchmarking the Communication Competence of Code Generation for LLMs and LLM Agent
  - **Authors**: Jie JW Wu, Fatemeh H Fard
  - **Published**: 2024-05-31
  - **Link**: http://arxiv.org/abs/2406.00215v3
  
  
- **Title**: CoSQA+: Pioneering the Multi-Choice Code Search Benchmark with Test-Driven Agents
  - **Authors**: Jing Gong, Yanghui Wu, Linxi Liang, Yanlin Wang, Jiachi Chen, Mingwei Liu, Zibin Zheng
  - **Published**: 2024-06-17
  - **Link**: http://arxiv.org/abs/2406.11589v5
  
  
- **Title**: ShortcutsBench: A Large-Scale Real-world Benchmark for API-based Agents
  - **Authors**: Haiyang Shen, Yue Li, Desong Meng, Dongqi Cai, Sheng Qi, Li Zhang, Mengwei Xu, Yun Ma
  - **Published**: 2024-06-28
  - **Link**: http://arxiv.org/abs/2407.00132v3
  
  
- **Title**: Agentless: Demystifying LLM-based Software Engineering Agents
  - **Authors**: Chunqiu Steven Xia, Yinlin Deng, Soren Dunn, Lingming Zhang
  - **Published**: 2024-07-01
  - **Link**: http://arxiv.org/abs/2407.01489v2
  
  
- **Title**: PyBench: Evaluating LLM Agent on various real-world coding tasks
  - **Authors**: Yaolun Zhang, Yinxu Pan, Yudong Wang, Jie Cai
  - **Published**: 2024-07-23
  - **Link**: http://arxiv.org/abs/2407.16732v2
  
  
- **Title**: AppWorld: A Controllable World of Apps and People for Benchmarking Interactive Coding Agents
  - **Authors**: Harsh Trivedi, Tushar Khot, Mareike Hartmann, Ruskin Manku, Vinty Dong, Edward Li, Shashank Gupta, Ashish Sabharwal, Niranjan Balasubramanian
  - **Published**: 2024-07-26
  - **Link**: http://arxiv.org/abs/2407.18901v1
  
  
- **Title**: Agents in Software Engineering: Survey, Landscape, and Vision
  - **Authors**: Yanlin Wang, Wanjun Zhong, Yanxian Huang, Ensheng Shi, Min Yang, Jiachi Chen, Hui Li, Yuchi Ma, Qianxiang Wang, Zibin Zheng
  - **Published**: 2024-09-13
  - **Link**: http://arxiv.org/abs/2409.09030v2
  
  
- **Title**: Evaluating Software Development Agents: Patch Patterns, Code Quality, and Issue Complexity in Real-World GitHub Scenarios
  - **Authors**: Zhi Chen, Lingxiao Jiang
  - **Published**: 2024-10-16
  - **Link**: http://arxiv.org/abs/2410.12468v2
  
  
- **Title**: Self-Evolving Multi-Agent Collaboration Networks for Software Development
  - **Authors**: Yue Hu, Yuzhu Cai, Yaxin Du, Xinyu Zhu, Xiangrui Liu, Zijie Yu, Yuchen Hou, Shuo Tang, Siheng Chen
  - **Published**: 2024-10-22
  - **Link**: http://arxiv.org/abs/2410.16946v1
  
  
- **Title**: RedCode: Risky Code Execution and Generation Benchmark for Code Agents
  - **Authors**: Chengquan Guo, Xun Liu, Chulin Xie, Andy Zhou, Yi Zeng, Zinan Lin, Dawn Song, Bo Li
  - **Published**: 2024-11-12
  - **Link**: http://arxiv.org/abs/2411.07781v1
  
  
- **Title**: Evaluation-Driven Development of LLM Agents: A Process Model and Reference Architecture
  - **Authors**: Boming Xia, Qinghua Lu, Liming Zhu, Zhenchang Xing, Dehai Zhao, Hao Zhang
  - **Published**: 2024-11-21
  - **Link**: http://arxiv.org/abs/2411.13768v2
  
  
- **Title**: The BrowserGym Ecosystem for Web Agent Research
  - **Authors**: Thibault Le Sellier De Chezelles, Maxime Gasse, Alexandre Drouin, Massimo Caccia, Léo Boisvert, Megh Thakkar, Tom Marty, Rim Assouel, Sahar Omidi Shayegan, Lawrence Keunho Jang, Xing Han Lù, Ori Yoran, Dehan Kong, Frank F. Xu, Siva Reddy, Quentin Cappart, Graham Neubig, Ruslan Salakhutdinov, Nicolas Chapados, Alexandre Lacoste
  - **Published**: 2024-12-06
  - **Link**: http://arxiv.org/abs/2412.05467v4
  
  
- **Title**: AIOpsLab: A Holistic Framework to Evaluate AI Agents for Enabling Autonomous Clouds
  - **Authors**: Yinfang Chen, Manish Shetty, Gagan Somashekar, Minghua Ma, Yogesh Simmhan, Jonathan Mace, Chetan Bansal, Rujia Wang, Saravan Rajmohan
  - **Published**: 2025-01-12
  - **Link**: http://arxiv.org/abs/2501.06706v1
  
  
- **Title**: SyncMind: Measuring Agent Out-of-Sync Recovery in Collaborative Software Engineering
  - **Authors**: Xuehang Guo, Xingyao Wang, Yangyi Chen, Sha Li, Chi Han, Manling Li, Heng Ji
  - **Published**: 2025-02-10
  - **Link**: http://arxiv.org/abs/2502.06994v2
  
  
- **Title**: ProjectEval: A Benchmark for Programming Agents Automated Evaluation on Project-Level Code Generation
  - **Authors**: Kaiyuan Liu, Youcheng Pan, Yang Xiang, Daojing He, Jing Li, Yexing Du, Tianrun Gao
  - **Published**: 2025-03-10
  - **Link**: http://arxiv.org/abs/2503.07010v2
  
  
- **Title**: SciReplicate-Bench: Benchmarking LLMs in Agent-driven Algorithmic Reproduction from Research Papers
  - **Authors**: Yanzheng Xiang, Hanqi Yan, Shuyin Ouyang, Lin Gui, Yulan He
  - **Published**: 2025-03-31
  - **Link**: http://arxiv.org/abs/2504.00255v1
  
  
- **Title**: SeaView: Software Engineering Agent Visual Interface for Enhanced Workflow
  - **Authors**: Timothy Bula, Saurabh Pujar, Luca Buratti, Mihaela Bornea, Avirup Sil
  - **Published**: 2025-04-11
  - **Link**: http://arxiv.org/abs/2504.08696v2
  
  
- **Title**: SWE-PolyBench: A multi-language benchmark for repository level evaluation of coding agents
  - **Authors**: Muhammad Shihab Rashid, Christian Bock, Yuan Zhuang, Alexander Buchholz, Tim Esler, Simon Valentin, Luca Franceschi, Martin Wistuba, Prabhu Teja Sivaprasad, Woo Jung Kim, Anoop Deoras, Giovanni Zappella, Laurent Callot
  - **Published**: 2025-04-11
  - **Link**: http://arxiv.org/abs/2504.08703v3
  
  
- **Title**: CodeVisionary: An Agent-based Framework for Evaluating Large Language Models in Code Generation
  - **Authors**: Xinchen Wang, Pengfei Gao, Chao Peng, Ruida Hu, Cuiyun Gao
  - **Published**: 2025-04-18
  - **Link**: http://arxiv.org/abs/2504.13472v1
  
  
- **Title**: Software Development Life Cycle Perspective: A Survey of Benchmarks for Code Large Language Models and Agents
  - **Authors**: Kaixin Wang, Tianlin Li, Xiaoyu Zhang, Chong Wang, Weisong Sun, Yang Liu, Bin Shi
  - **Published**: 2025-05-08
  - **Link**: http://arxiv.org/abs/2505.05283v2
  
  
- **Title**: Benchmarking and Enhancing LLM Agents in Localizing Linux Kernel Bugs
  - **Authors**: Zhenhao Zhou, Zhuochen Huang, Yike He, Chong Wang, Jiajun Wang, Yijian Wu, Xin Peng, Yiling Lou
  - **Published**: 2025-05-26
  - **Link**: http://arxiv.org/abs/2505.19489v1
  
  
- **Title**: SWE-rebench: An Automated Pipeline for Task Collection and Decontaminated Evaluation of Software Engineering Agents
  - **Authors**: Ibragim Badertdinov, Alexander Golubev, Maksim Nekrashevich, Anton Shevtsov, Simon Karasik, Andrei Andriushchenko, Maria Trofimova, Daria Litvintseva, Boris Yangel
  - **Published**: 2025-05-26
  - **Link**: http://arxiv.org/abs/2505.20411v1
  
  
- **Title**: Can Agents Fix Agent Issues?
  - **Authors**: Alfin Wijaya Rahardja, Junwei Liu, Weitong Chen, Zhenpeng Chen, Yiling Lou
  - **Published**: 2025-05-27
  - **Link**: http://arxiv.org/abs/2505.20749v1
  
  
- **Title**: UTBoost: Rigorous Evaluation of Coding Agents on SWE-Bench
  - **Authors**: Boxi Yu, Yuxuan Zhu, Pinjia He, Daniel Kang
  - **Published**: 2025-06-10
  - **Link**: http://arxiv.org/abs/2506.09289v1
  
  
- **Title**: SWE-Bench-CL: Continual Learning for Coding Agents
  - **Authors**: Thomas Joshi, Shayan Chowdhury, Fatih Uysal
  - **Published**: 2025-06-13
  - **Link**: http://arxiv.org/abs/2507.00014v1
  
  
- **Title**: Unified Software Engineering agent as AI Software Engineer
  - **Authors**: Leonhard Applis, Yuntong Zhang, Shanchao Liang, Nan Jiang, Lin Tan, Abhik Roychoudhury
  - **Published**: 2025-06-17
  - **Link**: http://arxiv.org/abs/2506.14683v1
  
  
- **Title**: OS-Harm: A Benchmark for Measuring Safety of Computer Use Agents
  - **Authors**: Thomas Kuntz, Agatha Duzan, Hao Zhao, Francesco Croce, Zico Kolter, Nicolas Flammarion, Maksym Andriushchenko
  - **Published**: 2025-06-17
  - **Link**: http://arxiv.org/abs/2506.14866v1
  
  
- **Title**: LMR-BENCH: Evaluating LLM Agent's Ability on Reproducing Language Modeling Research
  - **Authors**: Shuo Yan, Ruochen Li, Ziming Luo, Zimu Wang, Daoyang Li, Liqiang Jing, Kaiyu He, Peilin Wu, George Michalopoulos, Yue Zhang, Ziyang Zhang, Mian Zhang, Zhiyu Chen, Xinya Du
  - **Published**: 2025-06-19
  - **Link**: http://arxiv.org/abs/2506.17335v1
  
  
- **Title**: Understanding Software Engineering Agents: A Study of Thought-Action-Result Trajectories
  - **Authors**: Islem Bouzenia, Michael Pradel
  - **Published**: 2025-06-23
  - **Link**: http://arxiv.org/abs/2506.18824v1
  
  
- **Title**: SetupBench: Assessing Software Engineering Agents' Ability to Bootstrap Development Environments
  - **Authors**: Avi Arora, Jinu Jang, Roshanak Zilouchian Moghaddam
  - **Published**: 2025-07-11
  - **Link**: http://arxiv.org/abs/2507.09063v1
  
  
## Development Process Automation
### Agile Development Support
- **Title**: LLM-based agents for automating the enhancement of user story quality: An early report
  - **Authors**: Zheying Zhang, Maruf Rayhan, Tomas Herda, Manuel Goisauf, Pekka Abrahamsson
  - **Published**: 2024-03-14
  - **Link**: http://arxiv.org/abs/2403.09442v1
  
  
- **Title**: SOEN-101: Code Generation by Emulating Software Process Models Using Large Language Model Agents
  - **Authors**: Feng Lin, Dong Jae Kim, Tse-Husn, Chen
  - **Published**: 2024-03-23
  - **Link**: http://arxiv.org/abs/2403.15852v2
  
  
- **Title**: Experimenting with Multi-Agent Software Development: Towards a Unified Platform
  - **Authors**: Malik Abdul Sami, Muhammad Waseem, Zeeshan Rasheed, Mika Saari, Kari Systä, Pekka Abrahamsson
  - **Published**: 2024-06-08
  - **Link**: http://arxiv.org/abs/2406.05381v1
  
  
- **Title**: Agents in Software Engineering: Survey, Landscape, and Vision
  - **Authors**: Yanlin Wang, Wanjun Zhong, Yanxian Huang, Ensheng Shi, Min Yang, Jiachi Chen, Hui Li, Yuchi Ma, Qianxiang Wang, Zibin Zheng
  - **Published**: 2024-09-13
  - **Link**: http://arxiv.org/abs/2409.09030v2
  
  
- **Title**: Evaluation-Driven Development of LLM Agents: A Process Model and Reference Architecture
  - **Authors**: Boming Xia, Qinghua Lu, Liming Zhu, Zhenchang Xing, Dehai Zhao, Hao Zhang
  - **Published**: 2024-11-21
  - **Link**: http://arxiv.org/abs/2411.13768v2
  
  
### DevOps and Continuous Integration
- **Title**: Experimenting with Multi-Agent Software Development: Towards a Unified Platform
  - **Authors**: Malik Abdul Sami, Muhammad Waseem, Zeeshan Rasheed, Mika Saari, Kari Systä, Pekka Abrahamsson
  - **Published**: 2024-06-08
  - **Link**: http://arxiv.org/abs/2406.05381v1
  
  
- **Title**: Agents in Software Engineering: Survey, Landscape, and Vision
  - **Authors**: Yanlin Wang, Wanjun Zhong, Yanxian Huang, Ensheng Shi, Min Yang, Jiachi Chen, Hui Li, Yuchi Ma, Qianxiang Wang, Zibin Zheng
  - **Published**: 2024-09-13
  - **Link**: http://arxiv.org/abs/2409.09030v2
  
  
- **Title**: AgentOps: Enabling Observability of LLM Agents
  - **Authors**: Liming Dong, Qinghua Lu, Liming Zhu
  - **Published**: 2024-11-08
  - **Link**: http://arxiv.org/abs/2411.05285v2
  
  
- **Title**: Vibe Coding vs. Agentic Coding: Fundamentals and Practical Implications of Agentic AI
  - **Authors**: Ranjan Sapkota, Konstantinos I. Roumeliotis, Manoj Karkee
  - **Published**: 2025-05-26
  - **Link**: http://arxiv.org/abs/2505.19443v1
  
  
### Project Management and Planning
- **Title**: Autonomous Agents in Software Development: A Vision Paper
  - **Authors**: Zeeshan Rasheed, Muhammad Waseem, Kai-Kristian Kemell, Wang Xiaofeng, Anh Nguyen Duc, Kari Systä, Pekka Abrahamsson
  - **Published**: 2023-11-30
  - **Link**: http://arxiv.org/abs/2311.18440v1
  
  
- **Title**: Experimenting with Multi-Agent Software Development: Towards a Unified Platform
  - **Authors**: Malik Abdul Sami, Muhammad Waseem, Zeeshan Rasheed, Mika Saari, Kari Systä, Pekka Abrahamsson
  - **Published**: 2024-06-08
  - **Link**: http://arxiv.org/abs/2406.05381v1
  
  
- **Title**: GoNoGo: An Efficient LLM-based Multi-Agent System for Streamlining Automotive Software Release Decision-Making
  - **Authors**: Arsham Gholamzadeh Khoee, Yinan Yu, Robert Feldt, Andris Freimanis, Patrick Andersson Rhodin, Dhasarathy Parthasarathy
  - **Published**: 2024-08-19
  - **Link**: http://arxiv.org/abs/2408.09785v2
  
  
- **Title**: Think-on-Process: Dynamic Process Generation for Collaborative Development of Multi-Agent System
  - **Authors**: Leilei Lin, Yingming Zhou, Wenlong Chen, Chen Qian
  - **Published**: 2024-09-10
  - **Link**: http://arxiv.org/abs/2409.06568v1
  
  
- **Title**: Agents in Software Engineering: Survey, Landscape, and Vision
  - **Authors**: Yanlin Wang, Wanjun Zhong, Yanxian Huang, Ensheng Shi, Min Yang, Jiachi Chen, Hui Li, Yuchi Ma, Qianxiang Wang, Zibin Zheng
  - **Published**: 2024-09-13
  - **Link**: http://arxiv.org/abs/2409.09030v2
  
  
### Issue Resolution and Bug Fixing

- **Title**: RCAgent: Cloud Root Cause Analysis by Autonomous Agents with Tool-Augmented Large Language Models
  - **Authors**: Zefan Wang, Zichuan Liu, Yingying Zhang, Aoxiao Zhong, Jihong Wang, Fengbin Yin, Lunting Fan, Lingfei Wu, Qingsong Wen
  - **Published**: 2023-10-25
  - **Link**: http://arxiv.org/abs/2310.16340v3
  
  
- **Title**: Exploring LLM-based Agents for Root Cause Analysis
  - **Authors**: Devjeet Roy, Xuchao Zhang, Rashi Bhave, Chetan Bansal, Pedro Las-Casas, Rodrigo Fonseca, Saravan Rajmohan
  - **Published**: 2024-03-07
  - **Link**: http://arxiv.org/abs/2403.04123v1
  
  
- **Title**: RepairAgent: An Autonomous, LLM-Based Agent for Program Repair
  - **Authors**: Islem Bouzenia, Premkumar Devanbu, Michael Pradel
  - **Published**: 2024-03-25
  - **Link**: http://arxiv.org/abs/2403.17134v2
  
  
- **Title**: MAGIS: LLM-Based Multi-Agent Framework for GitHub Issue Resolution
  - **Authors**: Wei Tao, Yucheng Zhou, Yanlin Wang, Wenqiang Zhang, Hongyu Zhang, Yu Cheng
  - **Published**: 2024-03-26
  - **Link**: http://arxiv.org/abs/2403.17927v2
  
  
- **Title**: A Unified Debugging Approach via LLM-Based Multi-Agent Synergy
  - **Authors**: Cheryl Lee, Chunqiu Steven Xia, Longji Yang, Jen-tse Huang, Zhouruixin Zhu, Lingming Zhang, Michael R. Lyu
  - **Published**: 2024-04-26
  - **Link**: http://arxiv.org/abs/2404.17153v2
  
  
- **Title**: MASAI: Modular Architecture for Software-engineering AI Agents
  - **Authors**: Daman Arora, Atharv Sonwane, Nalin Wadhwa, Abhav Mehrotra, Saiteja Utpala, Ramakrishna Bairi, Aditya Kanade, Nagarajan Natarajan
  - **Published**: 2024-06-17
  - **Link**: http://arxiv.org/abs/2406.11638v1
  
  
- **Title**: SWT-Bench: Testing and Validating Real-World Bug-Fixes with Code Agents
  - **Authors**: Niels Mündler, Mark Niklas Müller, Jingxuan He, Martin Vechev
  - **Published**: 2024-06-18
  - **Link**: http://arxiv.org/abs/2406.12952v3
  
  
- **Title**: Agentless: Demystifying LLM-based Software Engineering Agents
  - **Authors**: Chunqiu Steven Xia, Yinlin Deng, Soren Dunn, Lingming Zhang
  - **Published**: 2024-07-01
  - **Link**: http://arxiv.org/abs/2407.01489v2
  
  
- **Title**: Building AI Agents for Autonomous Clouds: Challenges and Design Principles
  - **Authors**: Manish Shetty, Yinfang Chen, Gagan Somashekar, Minghua Ma, Yogesh Simmhan, Xuchao Zhang, Jonathan Mace, Dax Vandevoorde, Pedro Las-Casas, Shachee Mishra Gupta, Suman Nath, Chetan Bansal, Saravan Rajmohan
  - **Published**: 2024-07-16
  - **Link**: http://arxiv.org/abs/2407.12165v2
  
  
- **Title**: Diversity Empowers Intelligence: Integrating Expertise of Software Engineering Agents
  - **Authors**: Kexun Zhang, Weiran Yao, Zuxin Liu, Yihao Feng, Zhiwei Liu, Rithesh Murthy, Tian Lan, Lei Li, Renze Lou, Jiacheng Xu, Bo Pang, Yingbo Zhou, Shelby Heinecke, Silvio Savarese, Huan Wang, Caiming Xiong
  - **Published**: 2024-08-13
  - **Link**: http://arxiv.org/abs/2408.07060v1
  
  
- **Title**: MarsCode Agent: AI-native Automated Bug Fixing
  - **Authors**: Yizhou Liu, Pengfei Gao, Xinchen Wang, Jie Liu, Yexuan Shi, Zhao Zhang, Chao Peng
  - **Published**: 2024-09-02
  - **Link**: http://arxiv.org/abs/2409.00899v2
  
  
- **Title**: Co-Learning: Code Learning for Multi-Agent Reinforcement Collaborative Framework with Conversational Natural Language Interfaces
  - **Authors**: Jiapeng Yu, Yuqian Wu, Yajing Zhan, Wenhao Guo, Zhou Xu, Raymond Lee
  - **Published**: 2024-09-02
  - **Link**: http://arxiv.org/abs/2409.00985v1
  
  
- **Title**: HyperAgent: Generalist Software Engineering Agents to Solve Coding Tasks at Scale
  - **Authors**: Huy Nhat Phan, Tien N. Nguyen, Phong X. Nguyen, Nghi D. Q. Bui
  - **Published**: 2024-09-09
  - **Link**: http://arxiv.org/abs/2409.16299v2
  
  
- **Title**: Agents in Software Engineering: Survey, Landscape, and Vision
  - **Authors**: Yanlin Wang, Wanjun Zhong, Yanxian Huang, Ensheng Shi, Min Yang, Jiachi Chen, Hui Li, Yuchi Ma, Qianxiang Wang, Zibin Zheng
  - **Published**: 2024-09-13
  - **Link**: http://arxiv.org/abs/2409.09030v2
  
  
- **Title**: A Multi-Agent Approach to Fault Localization via Graph-Based Retrieval and Reflexion
  - **Authors**: Md Nakhla Rafi, Dong Jae Kim, Tse-Hsun Chen, Shaowei Wang
  - **Published**: 2024-09-20
  - **Link**: http://arxiv.org/abs/2409.13642v2
  
  
- **Title**: TRANSAGENT: An LLM-Based Multi-Agent System for Code Translation
  - **Authors**: Zhiqiang Yuan, Weitong Chen, Hanlin Wang, Kai Yu, Xin Peng, Yiling Lou
  - **Published**: 2024-09-30
  - **Link**: http://arxiv.org/abs/2409.19894v2
  
  
- **Title**: RGD: Multi-LLM Based Agent Debugger via Refinement and Generation Guidance
  - **Authors**: Haolin Jin, Zechao Sun, Huaming Chen
  - **Published**: 2024-10-02
  - **Link**: http://arxiv.org/abs/2410.01242v2
  
  
- **Title**: Watson: A Cognitive Observability Framework for the Reasoning of LLM-Powered Agents
  - **Authors**: Benjamin Rombaut, Sogol Masoumzadeh, Kirill Vasilevski, Dayi Lin, Ahmed E. Hassan
  - **Published**: 2024-11-05
  - **Link**: http://arxiv.org/abs/2411.03455v2
  
  
- **Title**: An Empirical Study on LLM-based Agents for Automated Bug Fixing
  - **Authors**: Xiangxin Meng, Zexiong Ma, Pengfei Gao, Chao Peng
  - **Published**: 2024-11-15
  - **Link**: http://arxiv.org/abs/2411.10213v1
  
  
- **Title**: Evaluating Agent-based Program Repair at Google
  - **Authors**: Pat Rondon, Renyao Wei, José Cambronero, Jürgen Cito, Aaron Sun, Siddhant Sanyam, Michele Tufano, Satish Chandra
  - **Published**: 2025-01-13
  - **Link**: http://arxiv.org/abs/2501.07531v1
  
  
- **Title**: Empirical Research on Utilizing LLM-based Agents for Automated Bug Fixing via LangGraph
  - **Authors**: Jialin Wang, Zhihua Duan
  - **Published**: 2025-01-29
  - **Link**: http://arxiv.org/abs/2502.18465v1
  
  
- **Title**: OrcaLoca: An LLM Agent Framework for Software Issue Localization
  - **Authors**: Zhongming Yu, Hejia Zhang, Yujie Zhao, Hanxian Huang, Matrix Yao, Ke Ding, Jishen Zhao
  - **Published**: 2025-02-01
  - **Link**: http://arxiv.org/abs/2502.00350v1
  
  
- **Title**: Agentic Bug Reproduction for Effective Automated Program Repair at Google
  - **Authors**: Runxiang Cheng, Michele Tufano, Jürgen Cito, José Cambronero, Pat Rondon, Renyao Wei, Aaron Sun, Satish Chandra
  - **Published**: 2025-02-03
  - **Link**: http://arxiv.org/abs/2502.01821v2
  
  
- **Title**: Flow-of-Action: SOP Enhanced LLM-Based Multi-Agent System for Root Cause Analysis
  - **Authors**: Changhua Pei, Zexin Wang, Fengrui Liu, Zeyan Li, Yang Liu, Xiao He, Rong Kang, Tieying Zhang, Jianjun Chen, Jianhui Li, Gaogang Xie, Dan Pei
  - **Published**: 2025-02-12
  - **Link**: http://arxiv.org/abs/2502.08224v1
  
  
- **Title**: Fully Autonomous Programming using Iterative Multi-Agent Debugging with Large Language Models
  - **Authors**: Anastasiia Grishina, Vadim Liventsev, Aki Härmä, Leon Moonen
  - **Published**: 2025-03-10
  - **Link**: http://arxiv.org/abs/2503.07693v1
  
  
- **Title**: LocAgent: Graph-Guided LLM Agents for Code Localization
  - **Authors**: Zhaoling Chen, Xiangru Tang, Gangda Deng, Fang Wu, Jialong Wu, Zhiwei Jiang, Viktor Prasanna, Arman Cohan, Xingyao Wang
  - **Published**: 2025-03-12
  - **Link**: http://arxiv.org/abs/2503.09089v2
  
  
- **Title**: Unveiling Pitfalls: Understanding Why AI-driven Code Agents Fail at GitHub Issue Resolution
  - **Authors**: Zhi Chen, Wei Ma, Lingxiao Jiang
  - **Published**: 2025-03-16
  - **Link**: http://arxiv.org/abs/2503.12374v2
  
  
- **Title**: BugCraft: End-to-End Crash Bug Reproduction Using LLM Agents in Minecraft
  - **Authors**: Eray Yapağcı, Yavuz Alp Sencer Öztürk, Eray Tüzün
  - **Published**: 2025-03-25
  - **Link**: http://arxiv.org/abs/2503.20036v1
  
  
- **Title**: Unlocking LLM Repair Capabilities in Low-Resource Programming Languages Through Cross-Language Translation and Multi-Agent Refinement
  - **Authors**: Wenqiang Luo, Jacky Wai Keung, Boyang Yang, Jacques Klein, Tegawende F. Bissyande, Haoye Tian, Bach Le
  - **Published**: 2025-03-28
  - **Link**: http://arxiv.org/abs/2503.22512v3
  
  
- **Title**: Thinking Longer, Not Larger: Enhancing Software Engineering Agents via Scaling Test-Time Compute
  - **Authors**: Yingwei Ma, Yongbin Li, Yihong Dong, Xue Jiang, Rongyu Cao, Jue Chen, Fei Huang, Binhua Li
  - **Published**: 2025-03-31
  - **Link**: http://arxiv.org/abs/2503.23803v2
  
  
- **Title**: AdaCoder: An Adaptive Planning and Multi-Agent Framework for Function-Level Code Generation
  - **Authors**: Yueheng Zhu, Chao Liu, Xuan He, Xiaoxue Ren, Zhongxin Liu, Ruwei Pan, Hongyu Zhang
  - **Published**: 2025-04-05
  - **Link**: http://arxiv.org/abs/2504.04220v1
  
  
- **Title**: Agent That Debugs: Dynamic State-Guided Vulnerability Repair
  - **Authors**: Zhengyao Liu, Yunlong Ma, Jingxuan Xu, Junchen Ai, Xiang Gao, Hailong Sun, Abhik Roychoudhury
  - **Published**: 2025-04-10
  - **Link**: http://arxiv.org/abs/2504.07634v1
  
  
- **Title**: Towards Adaptive Software Agents for Debugging
  - **Authors**: Yacine Majdoub, Eya Ben Charrada, Haifa Touati
  - **Published**: 2025-04-25
  - **Link**: http://arxiv.org/abs/2504.18316v1
  
  
- **Title**: CrashFixer: A crash resolution agent for the Linux kernel
  - **Authors**: Alex Mathai, Chenxi Huang, Suwei Ma, Jihwan Kim, Hailie Mitchell, Aleksandr Nogikh, Petros Maniatis, Franjo Ivančić, Junfeng Yang, Baishakhi Ray
  - **Published**: 2025-04-29
  - **Link**: http://arxiv.org/abs/2504.20412v2
  
  
- **Title**: CompileAgent: Automated Real-World Repo-Level Compilation with Tool-Integrated LLM-based Agent System
  - **Authors**: Li Hu, Guoqiang Chen, Xiuwei Shang, Shaoyin Cheng, Benlong Wu, Gangyang Li, Xu Zhu, Weiming Zhang, Nenghai Yu
  - **Published**: 2025-05-07
  - **Link**: http://arxiv.org/abs/2505.04254v1
  
  
- **Title**: Guided Search Strategies in Non-Serializable Environments with Applications to Software Engineering Agents
  - **Authors**: Karina Zainullina, Alexander Golubev, Maria Trofimova, Sergei Polezhaev, Ibragim Badertdinov, Daria Litvintseva, Simon Karasik, Filipp Fisin, Sergei Skvortsov, Maksim Nekrashevich, Anton Shevtsov, Boris Yangel
  - **Published**: 2025-05-19
  - **Link**: http://arxiv.org/abs/2505.13652v1
  
  
- **Title**: Benchmarking and Enhancing LLM Agents in Localizing Linux Kernel Bugs
  - **Authors**: Zhenhao Zhou, Zhuochen Huang, Yike He, Chong Wang, Jiajun Wang, Yijian Wu, Xin Peng, Yiling Lou
  - **Published**: 2025-05-26
  - **Link**: http://arxiv.org/abs/2505.19489v1
  
  
- **Title**: Code Researcher: Deep Research Agent for Large Systems Code and Commit History
  - **Authors**: Ramneet Singh, Sathvik Joel, Abhav Mehrotra, Nalin Wadhwa, Ramakrishna B Bairi, Aditya Kanade, Nagarajan Natarajan
  - **Published**: 2025-05-27
  - **Link**: http://arxiv.org/abs/2506.11060v1
  
  
- **Title**: Can Agents Fix Agent Issues?
  - **Authors**: Alfin Wijaya Rahardja, Junwei Liu, Weitong Chen, Zhenpeng Chen, Yiling Lou
  - **Published**: 2025-05-27
  - **Link**: http://arxiv.org/abs/2505.20749v1
  
  
- **Title**: Unified Software Engineering agent as AI Software Engineer
  - **Authors**: Leonhard Applis, Yuntong Zhang, Shanchao Liang, Nan Jiang, Lin Tan, Abhik Roychoudhury
  - **Published**: 2025-06-17
  - **Link**: http://arxiv.org/abs/2506.14683v1
  
  
- **Title**: SemAgent: A Semantics Aware Program Repair Agent
  - **Authors**: Anvith Pabba, Alex Mathai, Anindya Chakraborty, Baishakhi Ray
  - **Published**: 2025-06-19
  - **Link**: http://arxiv.org/abs/2506.16650v1
  
  
- **Title**: Dissecting the SWE-Bench Leaderboards: Profiling Submitters and Architectures of LLM- and Agent-Based Repair Systems
  - **Authors**: Matias Martinez, Xavier Franch
  - **Published**: 2025-06-20
  - **Link**: http://arxiv.org/abs/2506.17208v1
  
  
- **Title**: PAGENT: Learning to Patch Software Engineering Agents
  - **Authors**: Haoran Xue, Gias Uddin, Song Wang
  - **Published**: 2025-06-21
  - **Link**: http://arxiv.org/abs/2506.17772v1
  
  
- **Title**: Understanding Software Engineering Agents: A Study of Thought-Action-Result Trajectories
  - **Authors**: Islem Bouzenia, Michael Pradel
  - **Published**: 2025-06-23
  - **Link**: http://arxiv.org/abs/2506.18824v1
  
  
- **Title**: Are AI-Generated Fixes Secure? Analyzing LLM and Agent Patches on SWE-bench
  - **Authors**: Amirali Sajadi, Kostadin Damevski, Preetha Chatterjee
  - **Published**: 2025-06-30
  - **Link**: http://arxiv.org/abs/2507.02976v1
  
  
## Human-AI Interaction and Collaboration
### Conversational Programming Interfaces
- **Title**: Towards Autonomous Testing Agents via Conversational Large Language Models
  - **Authors**: Robert Feldt, Sungmin Kang, Juyeon Yoon, Shin Yoo
  - **Published**: 2023-06-08
  - **Link**: http://arxiv.org/abs/2306.05152v2
  
  
- **Title**: ChatDev: Communicative Agents for Software Development
  - **Authors**: Chen Qian, Wei Liu, Hongzhang Liu, Nuo Chen, Yufan Dang, Jiahao Li, Cheng Yang, Weize Chen, Yusheng Su, Xin Cong, Juyuan Xu, Dahai Li, Zhiyuan Liu, Maosong Sun
  - **Published**: 2023-07-16
  - **Link**: http://arxiv.org/abs/2307.07924v5
  
  
- **Title**: ChatLogo: A Large Language Model-Driven Hybrid Natural-Programming Language Interface for Agent-based Modeling and Programming
  - **Authors**: John Chen, Uri Wilensky
  - **Published**: 2023-08-16
  - **Link**: http://arxiv.org/abs/2308.08102v1
  
  
- **Title**: DepsRAG: Towards Agentic Reasoning and Planning for Software Dependency Management
  - **Authors**: Mohannad Alhanahnah, Yazan Boshmaf
  - **Published**: 2024-05-30
  - **Link**: http://arxiv.org/abs/2405.20455v5
  
  
- **Title**: HumanEvalComm: Benchmarking the Communication Competence of Code Generation for LLMs and LLM Agent
  - **Authors**: Jie JW Wu, Fatemeh H Fard
  - **Published**: 2024-05-31
  - **Link**: http://arxiv.org/abs/2406.00215v3
  
  
- **Title**: Text2BIM: Generating Building Models Using a Large Language Model-based Multi-Agent Framework
  - **Authors**: Changyu Du, Sebastian Esser, Stavros Nousias, André Borrmann
  - **Published**: 2024-08-15
  - **Link**: http://arxiv.org/abs/2408.08054v2
  
  
- **Title**: Co-Learning: Code Learning for Multi-Agent Reinforcement Collaborative Framework with Conversational Natural Language Interfaces
  - **Authors**: Jiapeng Yu, Yuqian Wu, Yajing Zhan, Wenhao Guo, Zhou Xu, Raymond Lee
  - **Published**: 2024-09-02
  - **Link**: http://arxiv.org/abs/2409.00985v1
  
  
- **Title**: Agents in Software Engineering: Survey, Landscape, and Vision
  - **Authors**: Yanlin Wang, Wanjun Zhong, Yanxian Huang, Ensheng Shi, Min Yang, Jiachi Chen, Hui Li, Yuchi Ma, Qianxiang Wang, Zibin Zheng
  - **Published**: 2024-09-13
  - **Link**: http://arxiv.org/abs/2409.09030v2
  
  
- **Title**: Motivations, Challenges, Best Practices, and Benefits for Bots and Conversational Agents in Software Engineering: A Multivocal Literature Review
  - **Authors**: Stefano Lambiase, Gemma Catolino, Fabio Palomba, Filomena Ferrucci
  - **Published**: 2024-09-18
  - **Link**: http://arxiv.org/abs/2409.11864v2
  
  
- **Title**: GIS Copilot: Towards an Autonomous GIS Agent for Spatial Analysis
  - **Authors**: Temitope Akinboyewa, Zhenlong Li, Huan Ning, M. Naser Lessani
  - **Published**: 2024-11-05
  - **Link**: http://arxiv.org/abs/2411.03205v4
  
  
- **Title**: TableTalk: Scaffolding Spreadsheet Development with a Language Agent
  - **Authors**: Jenny T. Liang, Aayush Kumar, Yasharth Bajpai, Sumit Gulwani, Vu Le, Chris Parnin, Arjun Radhakrishna, Ashish Tiwari, Emerson Murphy-Hill, Guastavo Soares
  - **Published**: 2025-02-13
  - **Link**: http://arxiv.org/abs/2502.09787v1
  
  
- **Title**: MooseAgent: A LLM Based Multi-agent Framework for Automating Moose Simulation
  - **Authors**: Tao Zhang, Zhenhai Liu, Yong Xin, Yongjun Jiao
  - **Published**: 2025-04-11
  - **Link**: http://arxiv.org/abs/2504.08621v1
  
  
- **Title**: Enhancing Software Development with Context-Aware Conversational Agents: A User Study on Developer Interactions with Chatbots
  - **Authors**: Glaucia Melo, Paulo Alencar, Donald Cowan
  - **Published**: 2025-05-13
  - **Link**: http://arxiv.org/abs/2505.08648v1
  
  
- **Title**: Vibe Coding vs. Agentic Coding: Fundamentals and Practical Implications of Agentic AI
  - **Authors**: Ranjan Sapkota, Konstantinos I. Roumeliotis, Manoj Karkee
  - **Published**: 2025-05-26
  - **Link**: http://arxiv.org/abs/2505.19443v1
  
  
### AI-Assisted Development Tools
- **Title**: Towards Autonomous Testing Agents via Conversational Large Language Models
  - **Authors**: Robert Feldt, Sungmin Kang, Juyeon Yoon, Shin Yoo
  - **Published**: 2023-06-08
  - **Link**: http://arxiv.org/abs/2306.05152v2
  
  
- **Title**: ChatDev: Communicative Agents for Software Development
  - **Authors**: Chen Qian, Wei Liu, Hongzhang Liu, Nuo Chen, Yufan Dang, Jiahao Li, Cheng Yang, Weize Chen, Yusheng Su, Xin Cong, Juyuan Xu, Dahai Li, Zhiyuan Liu, Maosong Sun
  - **Published**: 2023-07-16
  - **Link**: http://arxiv.org/abs/2307.07924v5
  
  
- **Title**: Static Code Analysis in the AI Era: An In-depth Exploration of the Concept, Function, and Potential of Intelligent Code Analysis Agents
  - **Authors**: Gang Fan, Xiaoheng Xie, Xunjin Zheng, Yinan Liang, Peng Di
  - **Published**: 2023-10-13
  - **Link**: http://arxiv.org/abs/2310.08837v1
  
  
- **Title**: Autonomous Large Language Model Agents Enabling Intent-Driven Mobile GUI Testing
  - **Authors**: Juyeon Yoon, Robert Feldt, Shin Yoo
  - **Published**: 2023-11-15
  - **Link**: http://arxiv.org/abs/2311.08649v1
  
  
- **Title**: CodeAgent: Enhancing Code Generation with Tool-Integrated Agent Systems for Real-World Repo-level Coding Challenges
  - **Authors**: Kechi Zhang, Jia Li, Ge Li, Xianjie Shi, Zhi Jin
  - **Published**: 2024-01-14
  - **Link**: http://arxiv.org/abs/2401.07339v2
  
  
- **Title**: Exploring LLM-based Agents for Root Cause Analysis
  - **Authors**: Devjeet Roy, Xuchao Zhang, Rashi Bhave, Chetan Bansal, Pedro Las-Casas, Rodrigo Fonseca, Saravan Rajmohan
  - **Published**: 2024-03-07
  - **Link**: http://arxiv.org/abs/2403.04123v1
  
  
- **Title**: LLM-based agents for automating the enhancement of user story quality: An early report
  - **Authors**: Zheying Zhang, Maruf Rayhan, Tomas Herda, Manuel Goisauf, Pekka Abrahamsson
  - **Published**: 2024-03-14
  - **Link**: http://arxiv.org/abs/2403.09442v1
  
  
- **Title**: RepairAgent: An Autonomous, LLM-Based Agent for Program Repair
  - **Authors**: Islem Bouzenia, Premkumar Devanbu, Michael Pradel
  - **Published**: 2024-03-25
  - **Link**: http://arxiv.org/abs/2403.17134v2
  
  
- **Title**: AI2Apps: A Visual IDE for Building LLM-based AI Agent Applications
  - **Authors**: Xin Pang, Zhucong Li, Jiaxiang Chen, Yuan Cheng, Yinghui Xu, Yuan Qi
  - **Published**: 2024-04-07
  - **Link**: http://arxiv.org/abs/2404.04902v1
  
  
- **Title**: Iterative Experience Refinement of Software-Developing Agents
  - **Authors**: Chen Qian, Jiahao Li, Yufan Dang, Wei Liu, YiFei Wang, Zihao Xie, Weize Chen, Cheng Yang, Yingli Zhang, Zhiyuan Liu, Maosong Sun
  - **Published**: 2024-05-07
  - **Link**: http://arxiv.org/abs/2405.04219v1
  
  
- **Title**: DepsRAG: Towards Agentic Reasoning and Planning for Software Dependency Management
  - **Authors**: Mohannad Alhanahnah, Yazan Boshmaf
  - **Published**: 2024-05-30
  - **Link**: http://arxiv.org/abs/2405.20455v5
  
  
- **Title**: Experimenting with Multi-Agent Software Development: Towards a Unified Platform
  - **Authors**: Malik Abdul Sami, Muhammad Waseem, Zeeshan Rasheed, Mika Saari, Kari Systä, Pekka Abrahamsson
  - **Published**: 2024-06-08
  - **Link**: http://arxiv.org/abs/2406.05381v1
  
  
- **Title**: CodeNav: Beyond tool-use to using real-world codebases with LLM agents
  - **Authors**: Tanmay Gupta, Luca Weihs, Aniruddha Kembhavi
  - **Published**: 2024-06-18
  - **Link**: http://arxiv.org/abs/2406.12276v1
  
  
- **Title**: PyBench: Evaluating LLM Agent on various real-world coding tasks
  - **Authors**: Yaolun Zhang, Yinxu Pan, Yudong Wang, Jie Cai
  - **Published**: 2024-07-23
  - **Link**: http://arxiv.org/abs/2407.16732v2
  
  
- **Title**: OpenHands: An Open Platform for AI Software Developers as Generalist Agents
  - **Authors**: Xingyao Wang, Boxuan Li, Yufan Song, Frank F. Xu, Xiangru Tang, Mingchen Zhuge, Jiayi Pan, Yueqi Song, Bowen Li, Jaskirat Singh, Hoang H. Tran, Fuqiang Li, Ren Ma, Mingzhang Zheng, Bill Qian, Yanjun Shao, Niklas Muennighoff, Yizhe Zhang, Binyuan Hui, Junyang Lin, Robert Brennan, Hao Peng, Heng Ji, Graham Neubig
  - **Published**: 2024-07-23
  - **Link**: http://arxiv.org/abs/2407.16741v3
  
  
- **Title**: Building Living Software Systems with Generative & Agentic AI
  - **Authors**: Jules White
  - **Published**: 2024-08-03
  - **Link**: http://arxiv.org/abs/2408.01768v1
  
  
- **Title**: LLM Agents Improve Semantic Code Search
  - **Authors**: Sarthak Jain, Aditya Dora, Ka Seng Sam, Prabhat Singh
  - **Published**: 2024-08-05
  - **Link**: http://arxiv.org/abs/2408.11058v1
  
  
- **Title**: AutoGen Studio: A No-Code Developer Tool for Building and Debugging Multi-Agent Systems
  - **Authors**: Victor Dibia, Jingya Chen, Gagan Bansal, Suff Syed, Adam Fourney, Erkang Zhu, Chi Wang, Saleema Amershi
  - **Published**: 2024-08-09
  - **Link**: http://arxiv.org/abs/2408.15247v1
  
  
- **Title**: COAST: Enhancing the Code Debugging Ability of LLMs through Communicative Agent Based Data Synthesis
  - **Authors**: Weiqing Yang, Hanbin Wang, Zhenghao Liu, Xinze Li, Yukun Yan, Shuo Wang, Yu Gu, Minghe Yu, Zhiyuan Liu, Ge Yu
  - **Published**: 2024-08-09
  - **Link**: http://arxiv.org/abs/2408.05006v3
  
  
- **Title**: GoNoGo: An Efficient LLM-based Multi-Agent System for Streamlining Automotive Software Release Decision-Making
  - **Authors**: Arsham Gholamzadeh Khoee, Yinan Yu, Robert Feldt, Andris Freimanis, Patrick Andersson Rhodin, Dhasarathy Parthasarathy
  - **Published**: 2024-08-19
  - **Link**: http://arxiv.org/abs/2408.09785v2
  
  
- **Title**: Agents in Software Engineering: Survey, Landscape, and Vision
  - **Authors**: Yanlin Wang, Wanjun Zhong, Yanxian Huang, Ensheng Shi, Min Yang, Jiachi Chen, Hui Li, Yuchi Ma, Qianxiang Wang, Zibin Zheng
  - **Published**: 2024-09-13
  - **Link**: http://arxiv.org/abs/2409.09030v2
  
  
- **Title**: Motivations, Challenges, Best Practices, and Benefits for Bots and Conversational Agents in Software Engineering: A Multivocal Literature Review
  - **Authors**: Stefano Lambiase, Gemma Catolino, Fabio Palomba, Filomena Ferrucci
  - **Published**: 2024-09-18
  - **Link**: http://arxiv.org/abs/2409.11864v2
  
  
- **Title**: REDO: Execution-Free Runtime Error Detection for COding Agents
  - **Authors**: Shou Li, Andrey Kan, Laurent Callot, Bhavana Bhasker, Muhammad Shihab Rashid, Timothy B Esler
  - **Published**: 2024-10-10
  - **Link**: http://arxiv.org/abs/2410.09117v1
  
  
- **Title**: Improving Performance of Commercially Available AI Products in a Multi-Agent Configuration
  - **Authors**: Cory Hymel, Sida Peng, Kevin Xu, Charath Ranganathan
  - **Published**: 2024-10-29
  - **Link**: http://arxiv.org/abs/2410.22129v1
  
  
- **Title**: GIS Copilot: Towards an Autonomous GIS Agent for Spatial Analysis
  - **Authors**: Temitope Akinboyewa, Zhenlong Li, Huan Ning, M. Naser Lessani
  - **Published**: 2024-11-05
  - **Link**: http://arxiv.org/abs/2411.03205v4
  
  
- **Title**: Watson: A Cognitive Observability Framework for the Reasoning of LLM-Powered Agents
  - **Authors**: Benjamin Rombaut, Sogol Masoumzadeh, Kirill Vasilevski, Dayi Lin, Ahmed E. Hassan
  - **Published**: 2024-11-05
  - **Link**: http://arxiv.org/abs/2411.03455v2
  
  
- **Title**: Evaluation-Driven Development of LLM Agents: A Process Model and Reference Architecture
  - **Authors**: Boming Xia, Qinghua Lu, Liming Zhu, Zhenchang Xing, Dehai Zhao, Hao Zhang
  - **Published**: 2024-11-21
  - **Link**: http://arxiv.org/abs/2411.13768v2
  
  
- **Title**: Agentic Bug Reproduction for Effective Automated Program Repair at Google
  - **Authors**: Runxiang Cheng, Michele Tufano, Jürgen Cito, José Cambronero, Pat Rondon, Renyao Wei, Aaron Sun, Satish Chandra
  - **Published**: 2025-02-03
  - **Link**: http://arxiv.org/abs/2502.01821v2
  
  
- **Title**: Every Software as an Agent: Blueprint and Case Study
  - **Authors**: Mengwei Xu
  - **Published**: 2025-02-07
  - **Link**: http://arxiv.org/abs/2502.04747v1
  
  
- **Title**: TableTalk: Scaffolding Spreadsheet Development with a Language Agent
  - **Authors**: Jenny T. Liang, Aayush Kumar, Yasharth Bajpai, Sumit Gulwani, Vu Le, Chris Parnin, Arjun Radhakrishna, Ashish Tiwari, Emerson Murphy-Hill, Guastavo Soares
  - **Published**: 2025-02-13
  - **Link**: http://arxiv.org/abs/2502.09787v1
  
  
- **Title**: Agentic AI Software Engineers: Programming with Trust
  - **Authors**: Abhik Roychoudhury, Corina Pasareanu, Michael Pradel, Baishakhi Ray
  - **Published**: 2025-02-19
  - **Link**: http://arxiv.org/abs/2502.13767v3
  
  
- **Title**: DARS: Dynamic Action Re-Sampling to Enhance Coding Agent Performance by Adaptive Tree Traversal
  - **Authors**: Vaibhav Aggarwal, Ojasv Kamal, Abhinav Japesh, Zhijing Jin, Bernhard Schölkopf
  - **Published**: 2025-03-18
  - **Link**: http://arxiv.org/abs/2503.14269v1
  
  
- **Title**: MANTRA: Enhancing Automated Method-Level Refactoring with Contextual RAG and Multi-Agent LLM Collaboration
  - **Authors**: Yisen Xu, Feng Lin, Jinqiu Yang, Tse-Hsun, Chen, Nikolaos Tsantalis
  - **Published**: 2025-03-18
  - **Link**: http://arxiv.org/abs/2503.14340v2
  
  
- **Title**: A Multi-agent Onboarding Assistant based on Large Language Models, Retrieval Augmented Generation, and Chain-of-Thought
  - **Authors**: Andrei Cristian Ionescu, Sergey Titov, Maliheh Izadi
  - **Published**: 2025-03-30
  - **Link**: http://arxiv.org/abs/2503.23421v1
  
  
- **Title**: Thinking Longer, Not Larger: Enhancing Software Engineering Agents via Scaling Test-Time Compute
  - **Authors**: Yingwei Ma, Yongbin Li, Yihong Dong, Xue Jiang, Rongyu Cao, Jue Chen, Fei Huang, Binhua Li
  - **Published**: 2025-03-31
  - **Link**: http://arxiv.org/abs/2503.23803v2
  
  
- **Title**: MooseAgent: A LLM Based Multi-agent Framework for Automating Moose Simulation
  - **Authors**: Tao Zhang, Zhenhai Liu, Yong Xin, Yongjun Jiao
  - **Published**: 2025-04-11
  - **Link**: http://arxiv.org/abs/2504.08621v1
  
  
- **Title**: SeaView: Software Engineering Agent Visual Interface for Enhanced Workflow
  - **Authors**: Timothy Bula, Saurabh Pujar, Luca Buratti, Mihaela Bornea, Avirup Sil
  - **Published**: 2025-04-11
  - **Link**: http://arxiv.org/abs/2504.08696v2
  
  
- **Title**: IEA-Plugin: An AI Agent Reasoner for Test Data Analytics
  - **Authors**: Seoyeon Kim, Yu Su, Li-C. Wang
  - **Published**: 2025-04-14
  - **Link**: http://arxiv.org/abs/2504.11496v1
  
  
- **Title**: AutoP2C: An LLM-Based Agent Framework for Code Repository Generation from Multimodal Content in Academic Papers
  - **Authors**: Zijie Lin, Yiqing Shen, Qilin Cai, He Sun, Jinrui Zhou, Mingjun Xiao
  - **Published**: 2025-04-28
  - **Link**: http://arxiv.org/abs/2504.20115v2
  
  
- **Title**: Enhancing Software Development with Context-Aware Conversational Agents: A User Study on Developer Interactions with Chatbots
  - **Authors**: Glaucia Melo, Paulo Alencar, Donald Cowan
  - **Published**: 2025-05-13
  - **Link**: http://arxiv.org/abs/2505.08648v1
  
  
- **Title**: Vibe Coding vs. Agentic Coding: Fundamentals and Practical Implications of Agentic AI
  - **Authors**: Ranjan Sapkota, Konstantinos I. Roumeliotis, Manoj Karkee
  - **Published**: 2025-05-26
  - **Link**: http://arxiv.org/abs/2505.19443v1
  
  
- **Title**: OSS-UAgent: An Agent-based Usability Evaluation Framework for Open Source Software
  - **Authors**: Lingkai Meng, Yu Shao, Long Yuan, Longbin Lai, Peng Cheng, Wenyuan Yu, Wenjie Zhang, Xuemin Lin, Jingren Zhou
  - **Published**: 2025-05-29
  - **Link**: http://arxiv.org/abs/2505.23239v1
  
  
- **Title**: MCP-Zero: Active Tool Discovery for Autonomous LLM Agents
  - **Authors**: Xiang Fei, Xiawu Zheng, Hao Feng
  - **Published**: 2025-06-01
  - **Link**: http://arxiv.org/abs/2506.01056v4
  
  
- **Title**: ReVeal: Self-Evolving Code Agents via Iterative Generation-Verification
  - **Authors**: Yiyang Jin, Kunzhao Xu, Hang Li, Xueting Han, Yanmin Zhou, Cheng Li, Jing Bai
  - **Published**: 2025-06-13
  - **Link**: http://arxiv.org/abs/2506.11442v1
  
  
- **Title**: SWE-Bench-CL: Continual Learning for Coding Agents
  - **Authors**: Thomas Joshi, Shayan Chowdhury, Fatih Uysal
  - **Published**: 2025-06-13
  - **Link**: http://arxiv.org/abs/2507.00014v1
  
  
- **Title**: Querying Large Automotive Software Models: Agentic vs. Direct LLM Approaches
  - **Authors**: Lukasz Mazur, Nenad Petrovic, James Pontes Miranda, Ansgar Radermacher, Robert Rasche, Alois Knoll
  - **Published**: 2025-06-16
  - **Link**: http://arxiv.org/abs/2506.13171v1
  
  
- **Title**: Unified Software Engineering agent as AI Software Engineer
  - **Authors**: Leonhard Applis, Yuntong Zhang, Shanchao Liang, Nan Jiang, Lin Tan, Abhik Roychoudhury
  - **Published**: 2025-06-17
  - **Link**: http://arxiv.org/abs/2506.14683v1
  
  
- **Title**: PAGENT: Learning to Patch Software Engineering Agents
  - **Authors**: Haoran Xue, Gias Uddin, Song Wang
  - **Published**: 2025-06-21
  - **Link**: http://arxiv.org/abs/2506.17772v1
  
  
- **Title**: Understanding Software Engineering Agents: A Study of Thought-Action-Result Trajectories
  - **Authors**: Islem Bouzenia, Michael Pradel
  - **Published**: 2025-06-23
  - **Link**: http://arxiv.org/abs/2506.18824v1
  
  
- **Title**: Context-Aware Code Wiring Recommendation with LLM-based Agent
  - **Authors**: Taiming Wang, Yanjie Jiang, Chunhao Dong, Yuxia Zhang, Hui Liu
  - **Published**: 2025-07-02
  - **Link**: http://arxiv.org/abs/2507.01315v1
  
  
- **Title**: Representing Prompting Patterns with PDL: Compliance Agent Case Study
  - **Authors**: Mandana Vaziri, Louis Mandel, Yuji Watanabe, Hirokuni Kitahara, Martin Hirzel, Anca Sailer
  - **Published**: 2025-07-08
  - **Link**: http://arxiv.org/abs/2507.06396v1
  
  
### Human-in-the-Loop Systems
- **Title**: How to Teach Programming in the AI Era? Using LLMs as a Teachable Agent for Debugging
  - **Authors**: Qianou Ma, Hua Shen, Kenneth Koedinger, Tongshuang Wu
  - **Published**: 2023-10-08
  - **Link**: http://arxiv.org/abs/2310.05292v5
  
  
- **Title**: Can Large Language Models Serve as Data Analysts? A Multi-Agent Assisted Approach for Qualitative Data Analysis
  - **Authors**: Zeeshan Rasheed, Muhammad Waseem, Aakash Ahmad, Kai-Kristian Kemell, Wang Xiaofeng, Anh Nguyen Duc, Pekka Abrahamsson
  - **Published**: 2024-02-02
  - **Link**: http://arxiv.org/abs/2402.01386v1
  
  
- **Title**: Concept-Guided LLM Agents for Human-AI Safety Codesign
  - **Authors**: Florian Geissler, Karsten Roscher, Mario Trapp
  - **Published**: 2024-04-03
  - **Link**: http://arxiv.org/abs/2404.15317v1
  
  
- **Title**: Experimenting with Multi-Agent Software Development: Towards a Unified Platform
  - **Authors**: Malik Abdul Sami, Muhammad Waseem, Zeeshan Rasheed, Mika Saari, Kari Systä, Pekka Abrahamsson
  - **Published**: 2024-06-08
  - **Link**: http://arxiv.org/abs/2406.05381v1
  
  
- **Title**: Agents in Software Engineering: Survey, Landscape, and Vision
  - **Authors**: Yanlin Wang, Wanjun Zhong, Yanxian Huang, Ensheng Shi, Min Yang, Jiachi Chen, Hui Li, Yuchi Ma, Qianxiang Wang, Zibin Zheng
  - **Published**: 2024-09-13
  - **Link**: http://arxiv.org/abs/2409.09030v2
  
  
- **Title**: Human-In-the-Loop Software Development Agents
  - **Authors**: Wannita Takerngsaksiri, Jirat Pasuksmit, Patanamon Thongtanunam, Chakkrit Tantithamthavorn, Ruixiong Zhang, Fan Jiang, Jing Li, Evan Cook, Kun Chen, Ming Wu
  - **Published**: 2024-11-19
  - **Link**: http://arxiv.org/abs/2411.12924v2
  
  
- **Title**: Towards Modeling Human-Agentic Collaborative Workflows: A BPMN Extension
  - **Authors**: Adem Ait, Javier Luis Cánovas Izquierdo, Jordi Cabot
  - **Published**: 2024-12-08
  - **Link**: http://arxiv.org/abs/2412.05958v3
  
  
- **Title**: VTutor: An Open-Source SDK for Generative AI-Powered Animated Pedagogical Agents with Multi-Media Output
  - **Authors**: Eason Chen, Chenyu Lin, Xinyi Tang, Aprille Xi, Canwen Wang, Jionghao Lin, Kenneth R Koedinger
  - **Published**: 2025-02-06
  - **Link**: http://arxiv.org/abs/2502.04103v2
  
  
- **Title**: TableTalk: Scaffolding Spreadsheet Development with a Language Agent
  - **Authors**: Jenny T. Liang, Aayush Kumar, Yasharth Bajpai, Sumit Gulwani, Vu Le, Chris Parnin, Arjun Radhakrishna, Ashish Tiwari, Emerson Murphy-Hill, Guastavo Soares
  - **Published**: 2025-02-13
  - **Link**: http://arxiv.org/abs/2502.09787v1
  
  
- **Title**: Human-In-The-Loop Software Development Agents: Challenges and Future Directions
  - **Authors**: Jirat Pasuksmit, Wannita Takerngsaksiri, Patanamon Thongtanunam, Chakkrit Tantithamthavorn, Ruixiong Zhang, Shiyan Wang, Fan Jiang, Jing Li, Evan Cook, Kun Chen, Ming Wu
  - **Published**: 2025-04-25
  - **Link**: http://arxiv.org/abs/2506.11009v1
  
  
- **Title**: Facilitating Trustworthy Human-Agent Collaboration in LLM-based Multi-Agent System oriented Software Engineering
  - **Authors**: Krishna Ronanki
  - **Published**: 2025-05-07
  - **Link**: http://arxiv.org/abs/2505.04251v1
  
  
- **Title**: Vibe Coding vs. Agentic Coding: Fundamentals and Practical Implications of Agentic AI
  - **Authors**: Ranjan Sapkota, Konstantinos I. Roumeliotis, Manoj Karkee
  - **Published**: 2025-05-26
  - **Link**: http://arxiv.org/abs/2505.19443v1
  
  
- **Title**: Unified Software Engineering agent as AI Software Engineer
  - **Authors**: Leonhard Applis, Yuntong Zhang, Shanchao Liang, Nan Jiang, Lin Tan, Abhik Roychoudhury
  - **Published**: 2025-06-17
  - **Link**: http://arxiv.org/abs/2506.14683v1
  
  
### Context-Aware Assistance

- **Title**: Building Living Software Systems with Generative & Agentic AI
  - **Authors**: Jules White
  - **Published**: 2024-08-03
  - **Link**: http://arxiv.org/abs/2408.01768v1
  
  
- **Title**: Agents in Software Engineering: Survey, Landscape, and Vision
  - **Authors**: Yanlin Wang, Wanjun Zhong, Yanxian Huang, Ensheng Shi, Min Yang, Jiachi Chen, Hui Li, Yuchi Ma, Qianxiang Wang, Zibin Zheng
  - **Published**: 2024-09-13
  - **Link**: http://arxiv.org/abs/2409.09030v2
  
  
- **Title**: MOSS: Enabling Code-Driven Evolution and Context Management for AI Agents
  - **Authors**: Ming Zhu, Yi Zhou
  - **Published**: 2024-09-24
  - **Link**: http://arxiv.org/abs/2409.16120v1
  
  
- **Title**: A Multi-agent Onboarding Assistant based on Large Language Models, Retrieval Augmented Generation, and Chain-of-Thought
  - **Authors**: Andrei Cristian Ionescu, Sergey Titov, Maliheh Izadi
  - **Published**: 2025-03-30
  - **Link**: http://arxiv.org/abs/2503.23421v1
  
  
- **Title**: Facilitating Trustworthy Human-Agent Collaboration in LLM-based Multi-Agent System oriented Software Engineering
  - **Authors**: Krishna Ronanki
  - **Published**: 2025-05-07
  - **Link**: http://arxiv.org/abs/2505.04251v1
  
  
- **Title**: Enhancing Software Development with Context-Aware Conversational Agents: A User Study on Developer Interactions with Chatbots
  - **Authors**: Glaucia Melo, Paulo Alencar, Donald Cowan
  - **Published**: 2025-05-13
  - **Link**: http://arxiv.org/abs/2505.08648v1
  
  
- **Title**: MCP-Zero: Active Tool Discovery for Autonomous LLM Agents
  - **Authors**: Xiang Fei, Xiawu Zheng, Hao Feng
  - **Published**: 2025-06-01
  - **Link**: http://arxiv.org/abs/2506.01056v4
  
  
- **Title**: Context-Aware Code Wiring Recommendation with LLM-based Agent
  - **Authors**: Taiming Wang, Yanjie Jiang, Chunhao Dong, Yuxia Zhang, Hui Liu
  - **Published**: 2025-07-02
  - **Link**: http://arxiv.org/abs/2507.01315v1
  
  
## System Integration and Tool Development
### API Integration and Service Orchestration
- **Title**: Experimenting with Multi-Agent Software Development: Towards a Unified Platform
  - **Authors**: Malik Abdul Sami, Muhammad Waseem, Zeeshan Rasheed, Mika Saari, Kari Systä, Pekka Abrahamsson
  - **Published**: 2024-06-08
  - **Link**: http://arxiv.org/abs/2406.05381v1
  
  
- **Title**: CodeNav: Beyond tool-use to using real-world codebases with LLM agents
  - **Authors**: Tanmay Gupta, Luca Weihs, Aniruddha Kembhavi
  - **Published**: 2024-06-18
  - **Link**: http://arxiv.org/abs/2406.12276v1
  
  
- **Title**: AppWorld: A Controllable World of Apps and People for Benchmarking Interactive Coding Agents
  - **Authors**: Harsh Trivedi, Tushar Khot, Mareike Hartmann, Ruskin Manku, Vinty Dong, Edward Li, Shashank Gupta, Ashish Sabharwal, Niranjan Balasubramanian
  - **Published**: 2024-07-26
  - **Link**: http://arxiv.org/abs/2407.18901v1
  
  
- **Title**: Text2BIM: Generating Building Models Using a Large Language Model-based Multi-Agent Framework
  - **Authors**: Changyu Du, Sebastian Esser, Stavros Nousias, André Borrmann
  - **Published**: 2024-08-15
  - **Link**: http://arxiv.org/abs/2408.08054v2
  
  
- **Title**: Survey of LLM Agent Communication with MCP: A Software Design Pattern Centric Review
  - **Authors**: Anjana Sarkar, Soumyendu Sarkar
  - **Published**: 2025-05-26
  - **Link**: http://arxiv.org/abs/2506.05364v1
  
  
- **Title**: MCP-Zero: Active Tool Discovery for Autonomous LLM Agents
  - **Authors**: Xiang Fei, Xiawu Zheng, Hao Feng
  - **Published**: 2025-06-01
  - **Link**: http://arxiv.org/abs/2506.01056v4
  
  
- **Title**: An Empirical Study of Multi-Agent RAG for Real-World University Admissions Counseling
  - **Authors**: Anh Nguyen-Duc, Chien Vu Manh, Bao Anh Tran, Viet Phuong Ngo, Luan Le Chi, Anh Quang Nguyen
  - **Published**: 2025-07-15
  - **Link**: http://arxiv.org/abs/2507.11272v1
  
  
### Development Environment Integration
- **Title**: AI2Apps: A Visual IDE for Building LLM-based AI Agent Applications
  - **Authors**: Xin Pang, Zhucong Li, Jiaxiang Chen, Yuan Cheng, Yinghui Xu, Yuan Qi
  - **Published**: 2024-04-07
  - **Link**: http://arxiv.org/abs/2404.04902v1
  
  
- **Title**: OpenHands: An Open Platform for AI Software Developers as Generalist Agents
  - **Authors**: Xingyao Wang, Boxuan Li, Yufan Song, Frank F. Xu, Xiangru Tang, Mingchen Zhuge, Jiayi Pan, Yueqi Song, Bowen Li, Jaskirat Singh, Hoang H. Tran, Fuqiang Li, Ren Ma, Mingzhang Zheng, Bill Qian, Yanjun Shao, Niklas Muennighoff, Yizhe Zhang, Binyuan Hui, Junyang Lin, Robert Brennan, Hao Peng, Heng Ji, Graham Neubig
  - **Published**: 2024-07-23
  - **Link**: http://arxiv.org/abs/2407.16741v3
  
  
- **Title**: ReDel: A Toolkit for LLM-Powered Recursive Multi-Agent Systems
  - **Authors**: Andrew Zhu, Liam Dugan, Chris Callison-Burch
  - **Published**: 2024-08-05
  - **Link**: http://arxiv.org/abs/2408.02248v2
  
  
- **Title**: AutoGen Studio: A No-Code Developer Tool for Building and Debugging Multi-Agent Systems
  - **Authors**: Victor Dibia, Jingya Chen, Gagan Bansal, Suff Syed, Adam Fourney, Erkang Zhu, Chi Wang, Saleema Amershi
  - **Published**: 2024-08-09
  - **Link**: http://arxiv.org/abs/2408.15247v1
  
  
- **Title**: GIS Copilot: Towards an Autonomous GIS Agent for Spatial Analysis
  - **Authors**: Temitope Akinboyewa, Zhenlong Li, Huan Ning, M. Naser Lessani
  - **Published**: 2024-11-05
  - **Link**: http://arxiv.org/abs/2411.03205v4
  
  
- **Title**: Beyond pip install: Evaluating LLM Agents for the Automated Installation of Python Projects
  - **Authors**: Louis Milliken, Sungmin Kang, Shin Yoo
  - **Published**: 2024-12-09
  - **Link**: http://arxiv.org/abs/2412.06294v1
  
  
- **Title**: VTutor: An Open-Source SDK for Generative AI-Powered Animated Pedagogical Agents with Multi-Media Output
  - **Authors**: Eason Chen, Chenyu Lin, Xinyi Tang, Aprille Xi, Canwen Wang, Jionghao Lin, Kenneth R Koedinger
  - **Published**: 2025-02-06
  - **Link**: http://arxiv.org/abs/2502.04103v2
  
  
- **Title**: CSR-Bench: Benchmarking LLM Agents in Deployment of Computer Science Research Repositories
  - **Authors**: Yijia Xiao, Runhui Wang, Luyang Kong, Davor Golac, Wei Wang
  - **Published**: 2025-02-10
  - **Link**: http://arxiv.org/abs/2502.06111v2
  
  
- **Title**: CXXCrafter: An LLM-Based Agent for Automated C/C++ Open Source Software Building
  - **Authors**: Zhengmin Yu, Yuan Zhang, Ming Wen, Yinan Nie, Wenhui Zhang, Min Yang
  - **Published**: 2025-05-27
  - **Link**: http://arxiv.org/abs/2505.21069v1
  
  
- **Title**: SetupBench: Assessing Software Engineering Agents' Ability to Bootstrap Development Environments
  - **Authors**: Avi Arora, Jinu Jang, Roshanak Zilouchian Moghaddam
  - **Published**: 2025-07-11
  - **Link**: http://arxiv.org/abs/2507.09063v1
  
  
### Tool Chain Automation
- **Title**: Experimenting with Multi-Agent Software Development: Towards a Unified Platform
  - **Authors**: Malik Abdul Sami, Muhammad Waseem, Zeeshan Rasheed, Mika Saari, Kari Systä, Pekka Abrahamsson
  - **Published**: 2024-06-08
  - **Link**: http://arxiv.org/abs/2406.05381v1
  
  
- **Title**: Beyond pip install: Evaluating LLM Agents for the Automated Installation of Python Projects
  - **Authors**: Louis Milliken, Sungmin Kang, Shin Yoo
  - **Published**: 2024-12-09
  - **Link**: http://arxiv.org/abs/2412.06294v1
  
  
- **Title**: CSR-Bench: Benchmarking LLM Agents in Deployment of Computer Science Research Repositories
  - **Authors**: Yijia Xiao, Runhui Wang, Luyang Kong, Davor Golac, Wei Wang
  - **Published**: 2025-02-10
  - **Link**: http://arxiv.org/abs/2502.06111v2
  
  
- **Title**: CompileAgent: Automated Real-World Repo-Level Compilation with Tool-Integrated LLM-based Agent System
  - **Authors**: Li Hu, Guoqiang Chen, Xiuwei Shang, Shaoyin Cheng, Benlong Wu, Gangyang Li, Xu Zhu, Weiming Zhang, Nenghai Yu
  - **Published**: 2025-05-07
  - **Link**: http://arxiv.org/abs/2505.04254v1
  
  
- **Title**: CXXCrafter: An LLM-Based Agent for Automated C/C++ Open Source Software Building
  - **Authors**: Zhengmin Yu, Yuan Zhang, Ming Wen, Yinan Nie, Wenhui Zhang, Min Yang
  - **Published**: 2025-05-27
  - **Link**: http://arxiv.org/abs/2505.21069v1
  
  

## Legacy System Modernization and Documentation
### Legacy Code Analysis and Understanding
- **Title**: Autonomous Legacy Web Application Upgrades Using a Multi-Agent System
  - **Authors**: Valtteri Ala-Salmi, Zeeshan Rasheed, Abdul Malik Sami, Zheying Zhang, Kai-Kristian Kemell, Jussi Rasku, Shahbaz Siddeeq, Mika Saari, Pekka Abrahamsson
  - **Published**: 2025-01-31
  - **Link**: http://arxiv.org/abs/2501.19204v1
  
  
- **Title**: Large Language Model-Powered Agent for C to Rust Code Translation
  - **Authors**: HoHyun Sim, Hyeonjoong Cho, Yeonghyeon Go, Zhoulai Fu, Ali Shokri, Binoy Ravindran
  - **Published**: 2025-05-21
  - **Link**: http://arxiv.org/abs/2505.15858v2
  
  
- **Title**: Code Researcher: Deep Research Agent for Large Systems Code and Commit History
  - **Authors**: Ramneet Singh, Sathvik Joel, Abhav Mehrotra, Nalin Wadhwa, Ramakrishna B Bairi, Aditya Kanade, Nagarajan Natarajan
  - **Published**: 2025-05-27
  - **Link**: http://arxiv.org/abs/2506.11060v1
  
  
- **Title**: Querying Large Automotive Software Models: Agentic vs. Direct LLM Approaches
  - **Authors**: Lukasz Mazur, Nenad Petrovic, James Pontes Miranda, Ansgar Radermacher, Robert Rasche, Alois Knoll
  - **Published**: 2025-06-16
  - **Link**: http://arxiv.org/abs/2506.13171v1
  
  
### Code Documentation Generation
- **Title**: Teamwork makes the dream work: LLMs-Based Agents for GitHub README.MD Summarization
  - **Authors**: Duc S. H. Nguyen, Bach G. Truong, Phuong T. Nguyen, Juri Di Rocco, Davide Di Ruscio
  - **Published**: 2025-03-13
  - **Link**: http://arxiv.org/abs/2503.10876v1
  
  
- **Title**: Is Multi-Agent Debate (MAD) the Silver Bullet? An Empirical Analysis of MAD in Code Summarization and Translation
  - **Authors**: Jina Chun, Qihong Chen, Jiawei Li, Iftekhar Ahmed
  - **Published**: 2025-03-15
  - **Link**: http://arxiv.org/abs/2503.12029v1
  
  
- **Title**: DocAgent: A Multi-Agent System for Automated Code Documentation Generation
  - **Authors**: Dayu Yang, Antoine Simoulin, Xin Qian, Xiaoyi Liu, Yuwei Cao, Zhaopu Teng, Grey Yang
  - **Published**: 2025-04-11
  - **Link**: http://arxiv.org/abs/2504.08725v3
  
  
- **Title**: Enhancing COBOL Code Explanations: A Multi-Agents Approach Using Large Language Models
  - **Authors**: Fangjian Lei, Jiawen Liu, Shayan Noei, Ying Zou, Derek Truong, William Alexander
  - **Published**: 2025-07-02
  - **Link**: http://arxiv.org/abs/2507.02182v1
  
  
### System Migration and Transformation
- **Title**: Autonomous Legacy Web Application Upgrades Using a Multi-Agent System
  - **Authors**: Valtteri Ala-Salmi, Zeeshan Rasheed, Abdul Malik Sami, Zheying Zhang, Kai-Kristian Kemell, Jussi Rasku, Shahbaz Siddeeq, Mika Saari, Pekka Abrahamsson
  - **Published**: 2025-01-31
  - **Link**: http://arxiv.org/abs/2501.19204v1
  
  
- **Title**: Large Language Model-Powered Agent for C to Rust Code Translation
  - **Authors**: HoHyun Sim, Hyeonjoong Cho, Yeonghyeon Go, Zhoulai Fu, Ali Shokri, Binoy Ravindran
  - **Published**: 2025-05-21
  - **Link**: http://arxiv.org/abs/2505.15858v2
  
  
### Knowledge Extraction and Preservation- **Title**: A Multi-agent Onboarding Assistant based on Large Language Models, Retrieval Augmented Generation, and Chain-of-Thought
  - **Authors**: Andrei Cristian Ionescu, Sergey Titov, Maliheh Izadi
  - **Published**: 2025-03-30
  - **Link**: http://arxiv.org/abs/2503.23421v1
  
  
