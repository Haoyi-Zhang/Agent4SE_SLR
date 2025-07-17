

cture & Tool Support](#1-agent-system-architecture--tool-support)-----------------------------------------------------------------------------------------------------------C1
  - [1.1 Patterned & Modular Architectures](#11-patterned--modular-architectures)---------------------------------------------------------------------------------------------------------------------C1.1

  - 
标题:       MASAI: Modular Architecture for Software-engineering AI Agents
作者:       Daman Arora, Atharv Sonwane, Nalin Wadhwa, Abhav Mehrotra, Saiteja Utpala, Ramakrishna Bairi, Aditya Kanade, Nagarajan Natarajan
发布时间:   2024-06-17
链接:       http://arxiv.org/abs/2406.11638v1
摘要:       A common method to solve complex problems in software engineering, is to
divide the problem into multiple sub-problems. Inspired by this, we propose a
Modular Architecture for Software-engineering AI (MASAI) agents, where
different LLM-powered sub-agents are instantiated with well-defined objectives
and strategies tuned to achieve those objectives. Our modular architecture
offers several advantages: (1) employing and tuning different problem-solving
strategies across sub-agents, (2) enabling sub-agents to gather information
from different sources scattered throughout a repository, and (3) avoiding
unnecessarily long trajectories which inflate costs and add extraneous context.
MASAI enabled us to achieve the highest performance (28.33% resolution rate) on
the popular and highly challenging SWE-bench Lite dataset consisting of 300
GitHub issues from 11 Python repositories. We conduct a comprehensive
evaluation of MASAI relative to other agentic methods and analyze the effects
of our design decisions and their contribution to the success of MASAI.
文中引用: arora2024masaimodulararchitecturesoftwareengineering


  - 标题:       Towards autonomous system: flexible modular production system enhanced
  with large language model agents
作者:       Yuchen Xia, Manthan Shenoy, Nasser Jazdi, Michael Weyrich
发布时间:   2023-04-28
链接:       http://arxiv.org/abs/2304.14721v4
摘要:       In this paper, we present a novel framework that combines large language
models (LLMs), digital twins and industrial automation system to enable
intelligent planning and control of production processes. We retrofit the
automation system for a modular production facility and create executable
control interfaces of fine-granular functionalities and coarse-granular skills.
Low-level functionalities are executed by automation components, and high-level
skills are performed by automation modules. Subsequently, a digital twin system
is developed, registering these interfaces and containing additional
descriptive information about the production system. Based on the retrofitted
automation system and the created digital twins, LLM-agents are designed to
interpret descriptive information in the digital twins and control the physical
system through service interfaces. These LLM-agents serve as intelligent agents
on different levels within an automation system, enabling autonomous planning
and control of flexible production. Given a task instruction as input, the
LLM-agents orchestrate a sequence of atomic functionalities and skills to
accomplish the task. We demonstrate how our implemented prototype can handle
un-predefined tasks, plan a production process, and execute the operations.
This research highlights the potential of integrating LLMs into industrial
automation systems in the context of smart factory for more agile, flexible,
and adaptive production processes, while it also underscores the critical
insights and limitations for future work. Demos at:
https://github.com/YuchenXia/GPT4IndustrialAutomation
文中引用: xia2023autonomoussystemflexiblemodular
  - [1.2 Reference Architectures & Taxonomies](#12-reference-architectures--taxonomies)---------------------------------------------------------------------------------------------------------------C1.2


标题:       MOSS: Enabling Code-Driven Evolution and Context Management for AI
  Agents
作者:       Ming Zhu, Yi Zhou
发布时间:   2024-09-24
链接:       http://arxiv.org/abs/2409.16120v1
摘要:       Developing AI agents powered by large language models (LLMs) faces
significant challenges in achieving true Turing completeness and adaptive,
code-driven evolution. Current approaches often generate code independently of
its runtime context, relying heavily on the LLM's memory, which results in
inefficiencies and limits adaptability. Manual protocol development in sandbox
environments further constrains the agent's autonomous adaptability. Crucially,
achieving consistency in code and context across multi-turn interactions and
ensuring isolation of local variables within each interaction remains an
unsolved problem.
  We introduce MOSS (llM-oriented Operating System Simulation), a novel
framework that addresses these challenges by integrating code generation with a
dynamic context management system. MOSS ensures consistency and adaptability by
using a mechanism that maintains the Python context across interactions,
including isolation of local variables and preservation of runtime integrity.
At its core, the framework employs an Inversion of Control (IoC) container in
conjunction with decorators to enforce the least knowledge principle, allowing
agents to focus on abstract interfaces rather than concrete implementations.
This facilitates seamless integration of new tools and libraries, enables
runtime instance replacement, and reduces prompt complexity, providing a "what
you see is what you get" environment for the agent.
  Through a series of case studies, we show how this framework can enhance the
efficiency and capabilities of agent development and highlight its advantages
in moving towards Turing-complete agents capable of evolving through code.
文中引用: zhu2024mossenablingcodedrivenevolution


标题:       LLM-Agent-UMF: LLM-based Agent Unified Modeling Framework for Seamless
  Integration of Multi Active/Passive Core-Agents
作者:       Amine Ben Hassouna, Hana Chaari, Ines Belhaj
发布时间:   2024-09-17
链接:       http://arxiv.org/abs/2409.11393v2
摘要:       In an era where vast amounts of data are collected and processed from diverse
sources, there is a growing demand to develop sophisticated AI systems capable
of intelligently fusing and analyzing this information. To address these
challenges, researchers have turned towards integrating tools into LLM-powered
agents to enhance the overall information fusion process. However, the
conjunction of these technologies and the proposed enhancements in several
state-of-the-art works followed a non-unified software architecture resulting
in a lack of modularity and terminological inconsistencies among researchers.
To address these issues, we propose a novel LLM-based Agent Unified Modeling
Framework (LLM-Agent-UMF) that aims to establish a clear foundation for agent
development from both functional and software architectural perspectives. Our
framework distinguishes between the different components of an LLM-based agent,
setting LLMs, and tools apart from a new element, the core-agent, playing the
role of the central coordinator of the agent. This pivotal entity comprises
five modules: planning, memory, profile, action, and security - the latter
often neglected in previous works. By classifying core-agents into passive and
active types based on their authoritative natures, we propose various
multi-core agent architectures that combine unique characteristics of
distinctive agents to tackle complex tasks more efficiently. We evaluate our
framework by applying it to thirteen state-of-the-art agents, thereby
demonstrating its alignment with their functionalities and clarifying the
overlooked architectural aspects. Moreover, we thoroughly assess five of our
proposed architectures through the integration of existing agents into new
hybrid active/passive core-agents architectures. This analysis provides
insights into potential improvements and highlights challenges involved in
combining specific agents.
文中引用: hassouna2024llmagentumfllmbasedagentunified


标题:       A Review of Prominent Paradigms for LLM-Based Agents: Tool Use
  (Including RAG), Planning, and Feedback Learning
作者:       Xinzhe Li
发布时间:   2024-06-09
链接:       http://arxiv.org/abs/2406.05804v6
摘要:       Tool use, planning, and feedback learning are currently three prominent
paradigms for developing Large Language Model (LLM)-based agents across various
tasks. Although numerous frameworks have been devised for each paradigm, their
intricate workflows and inconsistent taxonomy create challenges in
understanding and reviewing the frameworks across different paradigms. This
survey introduces a unified taxonomy to systematically review and discuss these
frameworks. Specifically, 1) the taxonomy defines environments/tasks, common
LLM-profiled roles or LMPRs (policy models, evaluators, and dynamic models),
and universally applicable workflows found in prior work, and 2) it enables a
comparison of key perspectives on the implementations of LMPRs and workflow
designs across different agent paradigms and frameworks. 3) Finally, we
identify three limitations in existing workflow designs and systematically
discuss the future work. Resources have been made publicly available at in our
GitHub repository https://github.com/xinzhel/LLM-Agent-Survey.
文中引用: li2024reviewprominentparadigmsllmbased


标题:       Towards Responsible Generative AI: A Reference Architecture for
  Designing Foundation Model based Agents
作者:       Qinghua Lu, Liming Zhu, Xiwei Xu, Zhenchang Xing, Stefan Harrer, Jon Whittle
发布时间:   2023-11-22
链接:       http://arxiv.org/abs/2311.13148v3
摘要:       Foundation models, such as large language models (LLMs), have been widely
recognised as transformative AI technologies due to their capabilities to
understand and generate content, including plans with reasoning capabilities.
Foundation model based agents derive their autonomy from the capabilities of
foundation models, which enable them to autonomously break down a given goal
into a set of manageable tasks and orchestrate task execution to meet the goal.
Despite the huge efforts put into building foundation model based agents, the
architecture design of the agents has not yet been systematically explored.
Also, while there are significant benefits of using agents for planning and
execution, there are serious considerations regarding responsible AI related
software quality attributes, such as security and accountability. Therefore,
this paper presents a pattern-oriented reference architecture that serves as
guidance when designing foundation model based agents. We evaluate the
completeness and utility of the proposed reference architecture by mapping it
to the architecture of two real-world agents.
文中引用: lu2024responsiblegenerativeaireference
  - 
标题:       Balancing Autonomy and Alignment: A Multi-Dimensional Taxonomy for
  Autonomous LLM-powered Multi-Agent Architectures
作者:       Thorsten Händler
发布时间:   2023-10-05
链接:       http://arxiv.org/abs/2310.03659v1
摘要:       Large language models (LLMs) have revolutionized the field of artificial
intelligence, endowing it with sophisticated language understanding and
generation capabilities. However, when faced with more complex and
interconnected tasks that demand a profound and iterative thought process, LLMs
reveal their inherent limitations. Autonomous LLM-powered multi-agent systems
represent a strategic response to these challenges. Such systems strive for
autonomously tackling user-prompted goals by decomposing them into manageable
tasks and orchestrating their execution and result synthesis through a
collective of specialized intelligent agents. Equipped with LLM-powered
reasoning capabilities, these agents harness the cognitive synergy of
collaborating with their peers, enhanced by leveraging contextual resources
such as tools and datasets. While these architectures hold promising potential
in amplifying AI capabilities, striking the right balance between different
levels of autonomy and alignment remains the crucial challenge for their
effective operation. This paper proposes a comprehensive multi-dimensional
taxonomy, engineered to analyze how autonomous LLM-powered multi-agent systems
balance the dynamic interplay between autonomy and alignment across various
aspects inherent to architectural viewpoints such as goal-driven task
management, agent composition, multi-agent collaboration, and context
interaction. It also includes a domain-ontology model specifying fundamental
architectural concepts. Our taxonomy aims to empower researchers, engineers,
and AI practitioners to systematically analyze the architectural dynamics and
balancing strategies employed by these increasingly prevalent AI systems. The
exploratory taxonomic classification of selected representative LLM-powered
multi-agent systems illustrates its practical utility and reveals potential for
future research and development.
文中引用: händler2023balancingautonomyalignmentmultidimensional
  - [1.3 IDE / Plugin-based Tooling Support](#13-ide--plugin-based-tooling-support)-------------------------------------------------------------------------------------------------------------------C1.3

标题:       AutoGen Studio: A No-Code Developer Tool for Building and Debugging
  Multi-Agent Systems
作者:       Victor Dibia, Jingya Chen, Gagan Bansal, Suff Syed, Adam Fourney, Erkang Zhu, Chi Wang, Saleema Amershi
发布时间:   2024-08-09
链接:       http://arxiv.org/abs/2408.15247v1
摘要:       Multi-agent systems, where multiple agents (generative AI models + tools)
collaborate, are emerging as an effective pattern for solving long-running,
complex tasks in numerous domains. However, specifying their parameters (such
as models, tools, and orchestration mechanisms etc,.) and debugging them
remains challenging for most developers. To address this challenge, we present
AUTOGEN STUDIO, a no-code developer tool for rapidly prototyping, debugging,
and evaluating multi-agent workflows built upon the AUTOGEN framework. AUTOGEN
STUDIO offers a web interface and a Python API for representing LLM-enabled
agents using a declarative (JSON-based) specification. It provides an intuitive
drag-and-drop UI for agent workflow specification, interactive evaluation and
debugging of workflows, and a gallery of reusable agent components. We
highlight four design principles for no-code multi-agent developer tools and
contribute an open-source implementation at
https://github.com/microsoft/autogen/tree/main/samples/apps/autogen-studio
文中引用: dibia2024autogenstudionocodedeveloper


标题:       ReDel: A Toolkit for LLM-Powered Recursive Multi-Agent Systems
作者:       Andrew Zhu, Liam Dugan, Chris Callison-Burch
发布时间:   2024-08-05
链接:       http://arxiv.org/abs/2408.02248v2
摘要:       Recently, there has been increasing interest in using Large Language Models
(LLMs) to construct complex multi-agent systems to perform tasks such as
compiling literature reviews, drafting consumer reports, and planning
vacations. Many tools and libraries exist for helping create such systems,
however none support recursive multi-agent systems -- where the models
themselves flexibly decide when to delegate tasks and how to organize their
delegation structure. In this work, we introduce ReDel: a toolkit for recursive
multi-agent systems that supports custom tool-use, delegation schemes,
event-based logging, and interactive replay in an easy-to-use web interface. We
show that, using ReDel, we are able to easily identify potential areas of
improvements through the visualization and debugging tools. Our code,
documentation, and PyPI package are open-source and free to use under the MIT
license at https://github.com/zhudotexe/redel.
文中引用: zhu2024redeltoolkitllmpoweredrecursive


标题:       OpenHands: An Open Platform for AI Software Developers as Generalist
  Agents
作者:       Xingyao Wang, Boxuan Li, Yufan Song, Frank F. Xu, Xiangru Tang, Mingchen Zhuge, Jiayi Pan, Yueqi Song, Bowen Li, Jaskirat Singh, Hoang H. Tran, Fuqiang Li, Ren Ma, Mingzhang Zheng, Bill Qian, Yanjun Shao, Niklas Muennighoff, Yizhe Zhang, Binyuan Hui, Junyang Lin, Robert Brennan, Hao Peng, Heng Ji, Graham Neubig
发布时间:   2024-07-23
链接:       http://arxiv.org/abs/2407.16741v3
摘要:       Software is one of the most powerful tools that we humans have at our
disposal; it allows a skilled programmer to interact with the world in complex
and profound ways. At the same time, thanks to improvements in large language
models (LLMs), there has also been a rapid development in AI agents that
interact with and affect change in their surrounding environments. In this
paper, we introduce OpenHands (f.k.a. OpenDevin), a platform for the
development of powerful and flexible AI agents that interact with the world in
similar ways to those of a human developer: by writing code, interacting with a
command line, and browsing the web. We describe how the platform allows for the
implementation of new agents, safe interaction with sandboxed environments for
code execution, coordination between multiple agents, and incorporation of
evaluation benchmarks. Based on our currently incorporated benchmarks, we
perform an evaluation of agents over 15 challenging tasks, including software
engineering (e.g., SWE-BENCH) and web browsing (e.g., WEBARENA), among others.
Released under the permissive MIT license, OpenHands is a community project
spanning academia and industry with more than 2.1K contributions from over 188
contributors.
文中引用: wang2025openhandsopenplatformai

  - 
标题:       AI2Apps: A Visual IDE for Building LLM-based AI Agent Applications
作者:       Xin Pang, Zhucong Li, Jiaxiang Chen, Yuan Cheng, Yinghui Xu, Yuan Qi
发布时间:   2024-04-07
链接:       http://arxiv.org/abs/2404.04902v1
摘要:       We introduce AI2Apps, a Visual Integrated Development Environment (Visual
IDE) with full-cycle capabilities that accelerates developers to build
deployable LLM-based AI agent Applications. This Visual IDE prioritizes both
the Integrity of its development tools and the Visuality of its components,
ensuring a smooth and efficient building experience.On one hand, AI2Apps
integrates a comprehensive development toolkit ranging from a prototyping
canvas and AI-assisted code editor to agent debugger, management system, and
deployment tools all within a web-based graphical user interface. On the other
hand, AI2Apps visualizes reusable front-end and back-end code as intuitive
drag-and-drop components. Furthermore, a plugin system named AI2Apps Extension
(AAE) is designed for Extensibility, showcasing how a new plugin with 20
components enables web agent to mimic human-like browsing behavior. Our case
study demonstrates substantial efficiency improvements, with AI2Apps reducing
token consumption and API calls when debugging a specific sophisticated
multimodal agent by approximately 90% and 80%, respectively. The AI2Apps,
including an online demo, open-source code, and a screencast video, is now
publicly accessible.
文中引用: pang2024ai2appsvisualidebuilding
  - [1.4 Multi-Agent Collaboration Paradigms](#14-multi-agent-collaboration-paradigms)----------------------------------------------------------------------------------------------------------------C1.4


标题:       Think-on-Process: Dynamic Process Generation for Collaborative
  Development of Multi-Agent System
作者:       Leilei Lin, Yingming Zhou, Wenlong Chen, Chen Qian
发布时间:   2024-09-10
链接:       http://arxiv.org/abs/2409.06568v1
摘要:       Software development is a collaborative endeavor that requires individuals
from different departments to work together in order to collectively develop a
high-quality software system. In this context, people have begun to explore a
method that leverages multi-agent systems based on LLMs to carry out software
development. However, existing research tends to rigidly fix the software
development process in a framework in code form, thus failing to dynamically
adjust the software development process in real-time to meet the more flexible
and variable software environment. In this paper, we propose a dynamic process
generation framework, named ToP (Think-on-Process). The core idea of ToP is to
leverage experiential knowledge (i.e., process models) to guide LLMs in
generating software development processes (i.e., instances). These instances
will guide multi-agent in software development and employ a compiler to provide
feedback on the development outcomes. Subsequently, we utilize heuristic
algorithms to filter the instances and apply process mining algorithms to
derive process model. Finally, the process model will be converted into text,
formatted as prompts, to enhance the ability of LLMs to generate other
instances. Experiments demonstrate that our framework ToP significantly
enhances the dynamic process generation capability of the GPT-3.5 and GPT-4 for
five categories of software development tasks.
文中引用: lin2024thinkonprocessdynamicprocessgeneration

标题:       HyperAgent: Generalist Software Engineering Agents to Solve Coding Tasks
  at Scale
作者:       Huy Nhat Phan, Tien N. Nguyen, Phong X. Nguyen, Nghi D. Q. Bui
发布时间:   2024-09-09
链接:       http://arxiv.org/abs/2409.16299v2
摘要:       Large Language Models (LLMs) have revolutionized software engineering (SE),
showcasing remarkable proficiency in various coding tasks. Despite recent
advancements that have enabled the creation of autonomous software agents
utilizing LLMs for end-to-end development tasks, these systems are typically
designed for specific SE functions. We introduce HyperAgent, an innovative
generalist multi-agent system designed to tackle a wide range of SE tasks
across different programming languages by mimicking the workflows of human
developers. HyperAgent features four specialized agents-Planner, Navigator,
Code Editor, and Executor-capable of handling the entire lifecycle of SE tasks,
from initial planning to final verification. HyperAgent sets new benchmarks in
diverse SE tasks, including GitHub issue resolution on the renowned SWE-Bench
benchmark, outperforming robust baselines. Furthermore, HyperAgent demonstrates
exceptional performance in repository-level code generation (RepoExec) and
fault localization and program repair (Defects4J), often surpassing
state-of-the-art baselines.
文中引用: phan2024hyperagentgeneralistsoftwareengineering


标题:       Diversity Empowers Intelligence: Integrating Expertise of Software
  Engineering Agents
作者:       Kexun Zhang, Weiran Yao, Zuxin Liu, Yihao Feng, Zhiwei Liu, Rithesh Murthy, Tian Lan, Lei Li, Renze Lou, Jiacheng Xu, Bo Pang, Yingbo Zhou, Shelby Heinecke, Silvio Savarese, Huan Wang, Caiming Xiong
发布时间:   2024-08-13
链接:       http://arxiv.org/abs/2408.07060v1
摘要:       Large language model (LLM) agents have shown great potential in solving
real-world software engineering (SWE) problems. The most advanced open-source
SWE agent can resolve over 27% of real GitHub issues in SWE-Bench Lite.
However, these sophisticated agent frameworks exhibit varying strengths,
excelling in certain tasks while underperforming in others. To fully harness
the diversity of these agents, we propose DEI (Diversity Empowered
Intelligence), a framework that leverages their unique expertise. DEI functions
as a meta-module atop existing SWE agent frameworks, managing agent collectives
for enhanced problem-solving. Experimental results show that a DEI-guided
committee of agents is able to surpass the best individual agent's performance
by a large margin. For instance, a group of open-source SWE agents, with a
maximum individual resolve rate of 27.3% on SWE-Bench Lite, can achieve a 34.3%
resolve rate with DEI, making a 25% improvement and beating most closed-source
solutions. Our best-performing group excels with a 55% resolve rate, securing
the highest ranking on SWE-Bench Lite. Our findings contribute to the growing
body of research on collaborative AI systems and their potential to solve
complex software engineering challenges.
文中引用: zhang2024diversityempowersintelligenceintegrating

标题:       Multi-Agent Collaboration via Cross-Team Orchestration
作者:       Zhuoyun Du, Chen Qian, Wei Liu, Zihao Xie, YiFei Wang, Rennai Qiu, Yufan Dang, Weize Chen, Cheng Yang, Ye Tian, Xuantang Xiong, Lei Han
发布时间:   2024-06-13
链接:       http://arxiv.org/abs/2406.08979v2
摘要:       Large Language Models (LLMs) have significantly impacted various domains,
especially through organized LLM-driven autonomous agents. A representative
scenario is in software development, where agents can collaborate in a team
like humans, following predefined phases to complete sub-tasks sequentially.
However, for an agent team, each phase yields only one possible outcome. This
results in the completion of only one development chain, thereby losing the
opportunity to explore multiple potential decision paths within the solution
space. Consequently leading to suboptimal results or extensive trial and error.
To address this, we introduce Cross-Team Orchestration (Croto), a scalable
multi-team framework that enables orchestrated teams to jointly propose various
task-oriented solutions and interact with their insights in a self-independence
while cross-team collaboration environment for superior solutions generation.
Experiments reveal a notable increase in software quality compared to
state-of-the-art baselines. We further tested our framework on story generation
tasks, which demonstrated a promising generalization ability of our framework
in other domains. The code and data is available at
https://github.com/OpenBMB/ChatDev/tree/macnet
文中引用: du2025multiagentcollaborationcrossteamorchestration


标题:       CodePori: Large-Scale System for Autonomous Software Development Using
  Multi-Agent Technology
作者:       Zeeshan Rasheed, Malik Abdul Sami, Kai-Kristian Kemell, Muhammad Waseem, Mika Saari, Kari Systä, Pekka Abrahamsson
发布时间:   2024-02-02
链接:       http://arxiv.org/abs/2402.01411v2
摘要:       Context: Large Language Models (LLMs) and Generative Pre-trained Transformers
(GPTs) have transformed the field of Software Engineering (SE). Existing
LLM-based multi-agent models have successfully addressed basic dialogue tasks.
However, the potential of LLMs for more challenging tasks, such as automated
code generation for large and complex projects, has been investigated in only a
few existing works. Objective: This paper aims to investigate the potential of
LLM-based agents in the software industry, particularly in enhancing
productivity and reducing time-to-market for complex software solutions. Our
primary objective is to gain insights into how these agents can fundamentally
transform the development of large-scale software. Methods: We introduce
CodePori, a novel system designed to automate code generation for large and
complex software projects based on functional and non-functional requirements
defined by stakeholders. To assess the proposed system performance, we utilized
the HumanEval benchmark and manually tested the CodePori model, providing 20
different project descriptions as input and then evaluated the code accuracy by
manually executing the code. Results: CodePori is able to generate running code
for large-scale projects, aligned with the typical software development
process. The HumanEval benchmark results indicate that CodePori improves code
accuracy by 89%. A manual assessment conducted by the first author shows that
the CodePori system achieved an accuracy rate of 85%. Conclusion: Based on the
results, our conclusion is that proposed system demonstrates the transformative
potential of LLM-based agents in SE, highlighting their practical applications
and opening new opportunities for broader adoption in both industry and
academia. Our project is publicly available at
https://github.com/GPT-Laboratory/CodePori.
文中引用: rasheed2024codeporilargescaleautonomoussoftware

标题:       ChatDev: Communicative Agents for Software Development
作者:       Chen Qian, Wei Liu, Hongzhang Liu, Nuo Chen, Yufan Dang, Jiahao Li, Cheng Yang, Weize Chen, Yusheng Su, Xin Cong, Juyuan Xu, Dahai Li, Zhiyuan Liu, Maosong Sun
发布时间:   2023-07-16
链接:       http://arxiv.org/abs/2307.07924v5
摘要:       Software development is a complex task that necessitates cooperation among
multiple members with diverse skills. Numerous studies used deep learning to
improve specific phases in a waterfall model, such as design, coding, and
testing. However, the deep learning model in each phase requires unique
designs, leading to technical inconsistencies across various phases, which
results in a fragmented and ineffective development process. In this paper, we
introduce ChatDev, a chat-powered software development framework in which
specialized agents driven by large language models (LLMs) are guided in what to
communicate (via chat chain) and how to communicate (via communicative
dehallucination). These agents actively contribute to the design, coding, and
testing phases through unified language-based communication, with solutions
derived from their multi-turn dialogues. We found their utilization of natural
language is advantageous for system design, and communicating in programming
language proves helpful in debugging. This paradigm demonstrates how linguistic
communication facilitates multi-agent collaboration, establishing language as a
unifying bridge for autonomous task-solving among LLM agents. The code and data
are available at https://github.com/OpenBMB/ChatDev.
文中引用: qian2024chatdevcommunicativeagentssoftware
     - [1.4.1 Planning-Driven](#141-planning-driven)---------------------------------------------------------------------------------------------------------------------------------------------------C1.4.1
   
    - 标题:       Towards autonomous system: flexible modular production system enhanced
  with large language model agents
作者:       Yuchen Xia, Manthan Shenoy, Nasser Jazdi, Michael Weyrich
发布时间:   2023-04-28
链接:       http://arxiv.org/abs/2304.14721v4
摘要:       In this paper, we present a novel framework that combines large language
models (LLMs), digital twins and industrial automation system to enable
intelligent planning and control of production processes. We retrofit the
automation system for a modular production facility and create executable
control interfaces of fine-granular functionalities and coarse-granular skills.
Low-level functionalities are executed by automation components, and high-level
skills are performed by automation modules. Subsequently, a digital twin system
is developed, registering these interfaces and containing additional
descriptive information about the production system. Based on the retrofitted
automation system and the created digital twins, LLM-agents are designed to
interpret descriptive information in the digital twins and control the physical
system through service interfaces. These LLM-agents serve as intelligent agents
on different levels within an automation system, enabling autonomous planning
and control of flexible production. Given a task instruction as input, the
LLM-agents orchestrate a sequence of atomic functionalities and skills to
accomplish the task. We demonstrate how our implemented prototype can handle
un-predefined tasks, plan a production process, and execute the operations.
This research highlights the potential of integrating LLMs into industrial
automation systems in the context of smart factory for more agile, flexible,
and adaptive production processes, while it also underscores the critical
insights and limitations for future work. Demos at:
https://github.com/YuchenXia/GPT4IndustrialAutomation
文中引用: xia2023autonomoussystemflexiblemodular
   
    - 标题:       Towards autonomous system: flexible modular production system enhanced
  with large language model agents
作者:       Yuchen Xia, Manthan Shenoy, Nasser Jazdi, Michael Weyrich
发布时间:   2023-04-28
链接:       http://arxiv.org/abs/2304.14721v4
摘要:       In this paper, we present a novel framework that combines large language
models (LLMs), digital twins and industrial automation system to enable
intelligent planning and control of production processes. We retrofit the
automation system for a modular production facility and create executable
control interfaces of fine-granular functionalities and coarse-granular skills.
Low-level functionalities are executed by automation components, and high-level
skills are performed by automation modules. Subsequently, a digital twin system
is developed, registering these interfaces and containing additional
descriptive information about the production system. Based on the retrofitted
automation system and the created digital twins, LLM-agents are designed to
interpret descriptive information in the digital twins and control the physical
system through service interfaces. These LLM-agents serve as intelligent agents
on different levels within an automation system, enabling autonomous planning
and control of flexible production. Given a task instruction as input, the
LLM-agents orchestrate a sequence of atomic functionalities and skills to
accomplish the task. We demonstrate how our implemented prototype can handle
un-predefined tasks, plan a production process, and execute the operations.
This research highlights the potential of integrating LLMs into industrial
automation systems in the context of smart factory for more agile, flexible,
and adaptive production processes, while it also underscores the critical
insights and limitations for future work. Demos at:
https://github.com/YuchenXia/GPT4IndustrialAutomation
文中引用: xia2023autonomoussystemflexiblemodular
    - [1.4.2 Tool-Invocation-Driven](#142-tool-invocation-driven)-------------------------------------------------------------------------------------------------------------------------------------C1.4.2
    
标题:       CodeAgent: Enhancing Code Generation with Tool-Integrated Agent Systems
  for Real-World Repo-level Coding Challenges
作者:       Kechi Zhang, Jia Li, Ge Li, Xianjie Shi, Zhi Jin
发布时间:   2024-01-14
链接:       http://arxiv.org/abs/2401.07339v2
摘要:       Large Language Models (LLMs) have shown promise in automated code generation
but typically excel only in simpler tasks such as generating standalone code
units. Real-world software development, however, often involves complex code
repositories (named repo) with complex dependencies and extensive
documentation. To fill this gap, our research pivots towards evaluating LLMs in
a more realistic setting -- real-world repo-level code generation. We introduce
CodeAgentBench, a manually curated benchmark for repo-level code generation.
This benchmark comprises five high-quality Python projects, encompassing a
total of 101 samples. We assess nine leading LLMs on repo-level tasks and
observe a decline in their performance. To tackle this, we present CodeAgent, a
novel LLM-based agent framework that employs external tools for effective
repo-level code generation. CodeAgent integrates five programming tools,
enabling interaction with software artifacts for information retrieval, code
symbol navigation, and code testing. We implement four agent strategies to
optimize these tools' usage. Our experiments on CodeAgentBench show that
CodeAgent enhances LLM performance significantly, with improvements ranging
from 18.1\% to 250\%. Further tests on the HumanEval benchmark confirm
CodeAgent's adaptability and efficacy across various code generation tasks.
Notably, CodeAgent outperforms commercial products like Github Copilot,
showcasing superior accuracy and efficiency. These results demonstrate
CodeAgent's robust capabilities in code generation, highlighting its potential
for real-world repo-level coding challenges.
文中引用: zhang2024codeagentenhancingcodegeneration
    - [1.4.3 Feedback-Learning-Driven](#143-feedback-learning-driven)---------------------------------------------------------------------------------------------------------------------------------C1.4.3


标题:       Iterative Experience Refinement of Software-Developing Agents
作者:       Chen Qian, Jiahao Li, Yufan Dang, Wei Liu, YiFei Wang, Zihao Xie, Weize Chen, Cheng Yang, Yingli Zhang, Zhiyuan Liu, Maosong Sun
发布时间:   2024-05-07
链接:       http://arxiv.org/abs/2405.04219v1
摘要:       Autonomous agents powered by large language models (LLMs) show significant
potential for achieving high autonomy in various scenarios such as software
development. Recent research has shown that LLM agents can leverage past
experiences to reduce errors and enhance efficiency. However, the static
experience paradigm, reliant on a fixed collection of past experiences acquired
heuristically, lacks iterative refinement and thus hampers agents'
adaptability. In this paper, we introduce the Iterative Experience Refinement
framework, enabling LLM agents to refine experiences iteratively during task
execution. We propose two fundamental patterns: the successive pattern,
refining based on nearest experiences within a task batch, and the cumulative
pattern, acquiring experiences across all previous task batches. Augmented with
our heuristic experience elimination, the method prioritizes high-quality and
frequently-used experiences, effectively managing the experience space and
enhancing efficiency. Extensive experiments show that while the successive
pattern may yield superior results, the cumulative pattern provides more stable
performance. Moreover, experience elimination facilitates achieving better
performance using just 11.54% of a high-quality subset.
文中引用: qian2024iterativeexperiencerefinementsoftwaredeveloping

    
标题:       Experiential Co-Learning of Software-Developing Agents
作者:       Chen Qian, Yufan Dang, Jiahao Li, Wei Liu, Zihao Xie, Yifei Wang, Weize Chen, Cheng Yang, Xin Cong, Xiaoyin Che, Zhiyuan Liu, Maosong Sun
发布时间:   2023-12-28
链接:       http://arxiv.org/abs/2312.17025v3
摘要:       Recent advancements in large language models (LLMs) have brought significant
changes to various domains, especially through LLM-driven autonomous agents. A
representative scenario is in software development, where LLM agents
demonstrate efficient collaboration, task division, and assurance of software
quality, markedly reducing the need for manual involvement. However, these
agents frequently perform a variety of tasks independently, without benefiting
from past experiences, which leads to repeated mistakes and inefficient
attempts in multi-step task execution. To this end, we introduce Experiential
Co-Learning, a novel LLM-agent learning framework in which instructor and
assistant agents gather shortcut-oriented experiences from their historical
trajectories and use these past experiences for future task execution. The
extensive experiments demonstrate that the framework enables agents to tackle
unseen software-developing tasks more effectively. We anticipate that our
insights will guide LLM agents towards enhanced autonomy and contribute to
their evolutionary growth in cooperative learning. The code and data are
available at https://github.com/OpenBMB/ChatDev.
文中引用: qian2024experientialcolearningsoftwaredevelopingagents
- [2. Requirements Engineering & Project Planning](#2-requirements-engineering--project-planning)-----------------------------------------------------------------------------------------------------C2
  - [2.1 Automated Requirements Elicitation & Modeling](#21-automated-requirements-elicitation--modeling)---------------------------------------------------------------------------------------------C2.1

标题:       MARE: Multi-Agents Collaboration Framework for Requirements Engineering
作者:       Dongming Jin, Zhi Jin, Xiaohong Chen, Chunhui Wang
发布时间:   2024-05-06
链接:       http://arxiv.org/abs/2405.03256v1
摘要:       Requirements Engineering (RE) is a critical phase in the software development
process that generates requirements specifications from stakeholders' needs.
Recently, deep learning techniques have been successful in several RE tasks.
However, obtaining high-quality requirements specifications requires
collaboration across multiple tasks and roles. In this paper, we propose an
innovative framework called MARE, which leverages collaboration among large
language models (LLMs) throughout the entire RE process. MARE divides the RE
process into four tasks: elicitation, modeling, verification, and
specification. Each task is conducted by engaging one or two specific agents
and each agent can conduct several actions. MARE has five agents and nine
actions. To facilitate collaboration between agents, MARE has designed a
workspace for agents to upload their generated intermediate requirements
artifacts and obtain the information they need. We conduct experiments on five
public cases, one dataset, and four new cases created by this work. We compared
MARE with three baselines using three widely used metrics for the generated
requirements models. Experimental results show that MARE can generate more
correct requirements models and outperform the state-of-the-art approaches by
15.4%. For the generated requirements specifications, we conduct a human
evaluation in three aspects and provide insights about the quality
文中引用: jin2024maremultiagentscollaborationframework

   - [2.2 User Story Quality Assessment & Improvement](#22-user-story-quality-assessment--improvement)-------------------------------------------------------------------------------------------------C2.2
 
  - 
标题:       LLM-based agents for automating the enhancement of user story quality:
  An early report
作者:       Zheying Zhang, Maruf Rayhan, Tomas Herda, Manuel Goisauf, Pekka Abrahamsson
发布时间:   2024-03-14
链接:       http://arxiv.org/abs/2403.09442v1
摘要:       In agile software development, maintaining high-quality user stories is
crucial, but also challenging. This study explores the use of large language
models to automatically improve the user story quality in Austrian Post Group
IT agile teams. We developed a reference model for an Autonomous LLM-based
Agent System and implemented it at the company. The quality of user stories in
the study and the effectiveness of these agents for user story quality
improvement was assessed by 11 participants across six agile teams. Our
findings demonstrate the potential of LLMs in improving user story quality,
contributing to the research on AI role in agile development, and providing a
practical example of the transformative impact of AI in an industry setting.
文中引用: zhang2024llmbasedagentsautomatingenhancement

  - [2.3 Autonomous Project Planning & Vision](#23-autonomous-project-planning--vision) --------------------------------------------------------------------------------------------------------------C2.3
- [3. Code Generation & Implementation](#3-code-generation--implementation) --------------------------------------------------------------------------------------------------------------------------C3
  - [3.1 Repository-Level Code Generation](#31-repository-level-code-generation) ---------------------------------------------------------------------------------------------------------------------C3.1


标题:       HyperAgent: Generalist Software Engineering Agents to Solve Coding Tasks
  at Scale
作者:       Huy Nhat Phan, Tien N. Nguyen, Phong X. Nguyen, Nghi D. Q. Bui
发布时间:   2024-09-09
链接:       http://arxiv.org/abs/2409.16299v2
摘要:       Large Language Models (LLMs) have revolutionized software engineering (SE),
showcasing remarkable proficiency in various coding tasks. Despite recent
advancements that have enabled the creation of autonomous software agents
utilizing LLMs for end-to-end development tasks, these systems are typically
designed for specific SE functions. We introduce HyperAgent, an innovative
generalist multi-agent system designed to tackle a wide range of SE tasks
across different programming languages by mimicking the workflows of human
developers. HyperAgent features four specialized agents-Planner, Navigator,
Code Editor, and Executor-capable of handling the entire lifecycle of SE tasks,
from initial planning to final verification. HyperAgent sets new benchmarks in
diverse SE tasks, including GitHub issue resolution on the renowned SWE-Bench
benchmark, outperforming robust baselines. Furthermore, HyperAgent demonstrates
exceptional performance in repository-level code generation (RepoExec) and
fault localization and program repair (Defects4J), often surpassing
state-of-the-art baselines.
文中引用: phan2024hyperagentgeneralistsoftwareengineering

标题:       Self-Organized Agents: A LLM Multi-Agent Framework toward Ultra
  Large-Scale Code Generation and Optimization
作者:       Yoichi Ishibashi, Yoshimasa Nishimura
发布时间:   2024-04-02
链接:       http://arxiv.org/abs/2404.02183v1
摘要:       Recent advancements in automatic code generation using large language model
(LLM) agent have brought us closer to the future of automated software
development. However, existing single-agent approaches face limitations in
generating and improving large-scale, complex codebases due to constraints in
context length. To tackle this challenge, we propose Self-Organized multi-Agent
framework (SoA), a novel multi-agent framework that enables the scalable and
efficient generation and optimization of large-scale code. In SoA,
self-organized agents operate independently to generate and modify code
components while seamlessly collaborating to construct the overall codebase. A
key feature of our framework is the automatic multiplication of agents based on
problem complexity, allowing for dynamic scalability. This enables the overall
code volume to be increased indefinitely according to the number of agents,
while the amount of code managed by each agent remains constant. We evaluate
SoA on the HumanEval benchmark and demonstrate that, compared to a single-agent
system, each agent in SoA handles significantly less code, yet the overall
generated code is substantially greater. Moreover, SoA surpasses the powerful
single-agent baseline by 5% in terms of Pass@1 accuracy.
文中引用: ishibashi2024selforganizedagentsllmmultiagent
 
标题:       CodePori: Large-Scale System for Autonomous Software Development Using
  Multi-Agent Technology
作者:       Zeeshan Rasheed, Malik Abdul Sami, Kai-Kristian Kemell, Muhammad Waseem, Mika Saari, Kari Systä, Pekka Abrahamsson
发布时间:   2024-02-02
链接:       http://arxiv.org/abs/2402.01411v2
摘要:       Context: Large Language Models (LLMs) and Generative Pre-trained Transformers
(GPTs) have transformed the field of Software Engineering (SE). Existing
LLM-based multi-agent models have successfully addressed basic dialogue tasks.
However, the potential of LLMs for more challenging tasks, such as automated
code generation for large and complex projects, has been investigated in only a
few existing works. Objective: This paper aims to investigate the potential of
LLM-based agents in the software industry, particularly in enhancing
productivity and reducing time-to-market for complex software solutions. Our
primary objective is to gain insights into how these agents can fundamentally
transform the development of large-scale software. Methods: We introduce
CodePori, a novel system designed to automate code generation for large and
complex software projects based on functional and non-functional requirements
defined by stakeholders. To assess the proposed system performance, we utilized
the HumanEval benchmark and manually tested the CodePori model, providing 20
different project descriptions as input and then evaluated the code accuracy by
manually executing the code. Results: CodePori is able to generate running code
for large-scale projects, aligned with the typical software development
process. The HumanEval benchmark results indicate that CodePori improves code
accuracy by 89%. A manual assessment conducted by the first author shows that
the CodePori system achieved an accuracy rate of 85%. Conclusion: Based on the
results, our conclusion is that proposed system demonstrates the transformative
potential of LLM-based agents in SE, highlighting their practical applications
and opening new opportunities for broader adoption in both industry and
academia. Our project is publicly available at
https://github.com/GPT-Laboratory/CodePori.
文中引用: rasheed2024codeporilargescaleautonomoussoftware
  - 
标题:       CodeAgent: Enhancing Code Generation with Tool-Integrated Agent Systems
  for Real-World Repo-level Coding Challenges
作者:       Kechi Zhang, Jia Li, Ge Li, Xianjie Shi, Zhi Jin
发布时间:   2024-01-14
链接:       http://arxiv.org/abs/2401.07339v2
摘要:       Large Language Models (LLMs) have shown promise in automated code generation
but typically excel only in simpler tasks such as generating standalone code
units. Real-world software development, however, often involves complex code
repositories (named repo) with complex dependencies and extensive
documentation. To fill this gap, our research pivots towards evaluating LLMs in
a more realistic setting -- real-world repo-level code generation. We introduce
CodeAgentBench, a manually curated benchmark for repo-level code generation.
This benchmark comprises five high-quality Python projects, encompassing a
total of 101 samples. We assess nine leading LLMs on repo-level tasks and
observe a decline in their performance. To tackle this, we present CodeAgent, a
novel LLM-based agent framework that employs external tools for effective
repo-level code generation. CodeAgent integrates five programming tools,
enabling interaction with software artifacts for information retrieval, code
symbol navigation, and code testing. We implement four agent strategies to
optimize these tools' usage. Our experiments on CodeAgentBench show that
CodeAgent enhances LLM performance significantly, with improvements ranging
from 18.1\% to 250\%. Further tests on the HumanEval benchmark confirm
CodeAgent's adaptability and efficacy across various code generation tasks.
Notably, CodeAgent outperforms commercial products like Github Copilot,
showcasing superior accuracy and efficiency. These results demonstrate
CodeAgent's robust capabilities in code generation, highlighting its potential
for real-world repo-level coding challenges.
文中引用: zhang2024codeagentenhancingcodegeneration
  - [3.2 Process-Driven Generation (Waterfall / TDD / Scrum, etc.)](#32-process-driven-generation-waterfall--tdd--scrum-etc) -------------------------------------------------------------------------C3.2

  - 
标题:       SOEN-101: Code Generation by Emulating Software Process Models Using
  Large Language Model Agents
作者:       Feng Lin, Dong Jae Kim, Tse-Husn, Chen
发布时间:   2024-03-23
链接:       http://arxiv.org/abs/2403.15852v2
摘要:       Software process models are essential to facilitate collaboration and
communication among software teams to solve complex development tasks. Inspired
by these software engineering practices, we present FlowGen - a code generation
framework that emulates software process models based on multiple Large
Language Model (LLM) agents. We emulate three process models, FlowGenWaterfall,
FlowGenTDD, and FlowGenScrum, by assigning LLM agents to embody roles (i.e.,
requirement engineer, architect, developer, tester, and scrum master) that
correspond to everyday development activities and organize their communication
patterns. The agents work collaboratively using chain-of-thought and prompt
composition with continuous self-refinement to improve the code quality. We use
GPT3.5 as our underlying LLM and several baselines (RawGPT, CodeT, Reflexion)
to evaluate code generation on four benchmarks: HumanEval, HumanEval-ET, MBPP,
and MBPP-ET. Our findings show that FlowGenScrum excels compared to other
process models, achieving a Pass@1 of 75.2, 65.5, 82.5, and 56.7 in HumanEval,
HumanEval-ET, MBPP, and MBPP-ET, respectively (an average of 15% improvement
over RawGPT). Compared with other state-of-the-art techniques, FlowGenScrum
achieves a higher Pass@1 in MBPP compared to CodeT, with both outperforming
Reflexion. Notably, integrating CodeT into FlowGenScrum resulted in
statistically significant improvements, achieving the highest Pass@1 scores.
Our analysis also reveals that the development activities impacted code smell
and exception handling differently, with design and code review adding more
exception handling and reducing code smells. Finally, FlowGen models maintain
stable Pass@1 scores across GPT3.5 versions and temperature values,
highlighting the effectiveness of software process models in enhancing the
quality and stability of LLM-generated code.
文中引用: lin2024soen101codegenerationemulating

  - [3.3 Integrated Code Navigation & Retrieval](#33-integrated-code-navigation--retrieval)-----------------------------------------------------------------------------------------------------------C3.3


标题:       LLM Agents Improve Semantic Code Search
作者:       Sarthak Jain, Aditya Dora, Ka Seng Sam, Prabhat Singh
发布时间:   2024-08-05
链接:       http://arxiv.org/abs/2408.11058v1
摘要:       Code Search is a key task that many programmers often have to perform while
developing solutions to problems. Current methodologies suffer from an
inability to perform accurately on prompts that contain some ambiguity or ones
that require additional context relative to a code-base. We introduce the
approach of using Retrieval Augmented Generation (RAG) powered agents to inject
information into user prompts allowing for better inputs into embedding models.
By utilizing RAG, agents enhance user queries with relevant details from GitHub
repositories, making them more informative and contextually aligned.
Additionally, we introduce a multi-stream ensemble approach which when paired
with agentic workflow can obtain improved retrieval accuracy, which we deploy
on application called repo-rift.com. Experimental results on the CodeSearchNet
dataset demonstrate that RepoRift significantly outperforms existing methods,
achieving an 78.2% success rate at Success@10 and a 34.6% success rate at
Success@1. This research presents a substantial advancement in semantic code
search, highlighting the potential of agentic LLMs and RAG to enhance code
retrieval systems.
文中引用: jain2024llmagentsimprovesemantic

  - 
标题:       CodeNav: Beyond tool-use to using real-world codebases with LLM agents
作者:       Tanmay Gupta, Luca Weihs, Aniruddha Kembhavi
发布时间:   2024-06-18
链接:       http://arxiv.org/abs/2406.12276v1
摘要:       We present CodeNav, an LLM agent that navigates and leverages previously
unseen code repositories to solve user queries. In contrast to tool-use LLM
agents that require ``registration'' of all relevant tools via manual
descriptions within the LLM context, CodeNav automatically indexes and searches
over code blocks in the target codebase, finds relevant code snippets, imports
them, and uses them to iteratively generate a solution with execution feedback.
To highlight the core-capabilities of CodeNav, we first showcase three case
studies where we use CodeNav for solving complex user queries using three
diverse codebases. Next, on three benchmarks, we quantitatively compare the
effectiveness of code-use (which only has access to the target codebase) to
tool-use (which has privileged access to all tool names and descriptions).
Finally, we study the effect of varying kinds of tool and library descriptions
on code-use performance, as well as investigate the advantage of the agent
seeing source code as opposed to natural descriptions of code. All code will be
made open source under a permissive license.
文中引用: gupta2024codenavtooluseusingrealworld

- [4. Testing & Quality Assurance](#4-testing--quality-assurance) ------------------------------------------------------------------------------------------------------------------------------------C4
  - [4.1 Automated Test Case Generation](#41-automated-test-case-generation)--------------------------------------------------------------------------------------------------------------------------C4.1


标题:       SWT-Bench: Testing and Validating Real-World Bug-Fixes with Code Agents
作者:       Niels Mündler, Mark Niklas Müller, Jingxuan He, Martin Vechev
发布时间:   2024-06-18
链接:       http://arxiv.org/abs/2406.12952v3
摘要:       Rigorous software testing is crucial for developing and maintaining
high-quality code, making automated test generation a promising avenue for both
improving software quality and boosting the effectiveness of code generation
methods. However, while code generation with Large Language Models (LLMs) is an
extraordinarily active research area, test generation remains relatively
unexplored. We address this gap and investigate the capability of LLM-based
Code Agents to formalize user issues into test cases. To this end, we propose a
novel benchmark based on popular GitHub repositories, containing real-world
issues, ground-truth bug-fixes, and golden tests. We find that LLMs generally
perform surprisingly well at generating relevant test cases, with Code Agents
designed for code repair exceeding the performance of systems designed
specifically for test generation. Further, as test generation is a similar but
more structured task than code generation, it allows for a more fine-grained
analysis using issue reproduction rate and coverage changes, providing a dual
metric for analyzing systems designed for code repair. Finally, we find that
generated tests are an effective filter for proposed code fixes, doubling the
precision of SWE-Agent. We release all data and code at
https://github.com/logic-star-ai/SWT-Bench
文中引用: mündler2025swtbenchtestingvalidatingrealworld


  - [4.2 Conversational / Autonomous Testing Agents](#42-conversational--autonomous-testing-agents) --------------------------------------------------------------------------------------------------C4.2

    
标题:       AutoSafeCoder: A Multi-Agent Framework for Securing LLM Code Generation
  through Static Analysis and Fuzz Testing
作者:       Ana Nunez, Nafis Tanveer Islam, Sumit Kumar Jha, Peyman Najafirad
发布时间:   2024-09-16
链接:       http://arxiv.org/abs/2409.10737v2
摘要:       Recent advancements in automatic code generation using large language models
(LLMs) have brought us closer to fully automated secure software development.
However, existing approaches often rely on a single agent for code generation,
which struggles to produce secure, vulnerability-free code. Traditional program
synthesis with LLMs has primarily focused on functional correctness, often
neglecting critical dynamic security implications that happen during runtime.
To address these challenges, we propose AutoSafeCoder, a multi-agent framework
that leverages LLM-driven agents for code generation, vulnerability analysis,
and security enhancement through continuous collaboration. The framework
consists of three agents: a Coding Agent responsible for code generation, a
Static Analyzer Agent identifying vulnerabilities, and a Fuzzing Agent
performing dynamic testing using a mutation-based fuzzing approach to detect
runtime errors. Our contribution focuses on ensuring the safety of multi-agent
code generation by integrating dynamic and static testing in an iterative
process during code generation by LLM that improves security. Experiments using
the SecurityEval dataset demonstrate a 13% reduction in code vulnerabilities
compared to baseline LLMs, with no compromise in functionality.
文中引用: nunez2024autosafecodermultiagentframeworksecuring

标题:       Towards Autonomous Testing Agents via Conversational Large Language
  Models
作者:       Robert Feldt, Sungmin Kang, Juyeon Yoon, Shin Yoo
发布时间:   2023-06-08
链接:       http://arxiv.org/abs/2306.05152v2
摘要:       Software testing is an important part of the development cycle, yet it
requires specialized expertise and substantial developer effort to adequately
test software. Recent discoveries of the capabilities of large language models
(LLMs) suggest that they can be used as automated testing assistants, and thus
provide helpful information and even drive the testing process. To highlight
the potential of this technology, we present a taxonomy of LLM-based testing
agents based on their level of autonomy, and describe how a greater level of
autonomy can benefit developers in practice. An example use of LLMs as a
testing assistant is provided to demonstrate how a conversational framework for
testing can help developers. This also highlights how the often criticized
hallucination of LLMs can be beneficial for testing. We identify other tangible
benefits that LLM-driven testing agents can bestow, and also discuss potential
limitations.
文中引用: feldt2023autonomoustestingagentsconversational
  - [4.3 Test-Driven Validation Benchmarks](#43-test-driven-validation-benchmarks) -------------------------------------------------------------------------------------------------------------------C4.3
 
  - 
标题:       CoSQA+: Pioneering the Multi-Choice Code Search Benchmark with
  Test-Driven Agents
作者:       Jing Gong, Yanghui Wu, Linxi Liang, Yanlin Wang, Jiachi Chen, Mingwei Liu, Zibin Zheng
发布时间:   2024-06-17
链接:       http://arxiv.org/abs/2406.11589v5
摘要:       Semantic code search, retrieving code that matches a given natural language
query, is an important task to improve productivity in software engineering.
Existing code search datasets face limitations: they rely on human annotators
who assess code primarily through semantic understanding rather than functional
verification, leading to potential inaccuracies and scalability issues.
Additionally, current evaluation metrics often overlook the multi-choice nature
of code search. This paper introduces CoSQA+, pairing high-quality queries from
CoSQA with multiple suitable codes. We develop an automated pipeline featuring
multiple model-based candidate selections and the novel test-driven agent
annotation system. Among a single Large Language Model (LLM) annotator and
Python expert annotators (without test-based verification), agents leverage
test-based verification and achieve the highest accuracy of 92.0%. Through
extensive experiments, CoSQA+ has demonstrated superior quality over CoSQA.
Models trained on CoSQA+ exhibit improved performance. We provide the code and
data at https://github.com/DeepSoftwareAnalytics/CoSQA_Plus.
文中引用: gong2025cosqapioneeringmultichoicecode

- [5. Debugging, Fault Localization & Automated Repair](#5-debugging-fault-localization--automated-repair)--------------------------------------------------------------------------------------------C5
  - [5.1 Defect Detection](#51-defect-detection)
 
  - 
标题:       A Multi-Agent Approach to Fault Localization via Graph-Based Retrieval
  and Reflexion
作者:       Md Nakhla Rafi, Dong Jae Kim, Tse-Hsun Chen, Shaowei Wang
发布时间:   2024-09-20
链接:       http://arxiv.org/abs/2409.13642v2
摘要:       Identifying and resolving software faults remains a challenging and
resource-intensive process. Traditional fault localization techniques, such as
Spectrum-Based Fault Localization (SBFL), leverage statistical analysis of test
coverage but often suffer from limited accuracy. While learning-based
approaches improve fault localization, they demand extensive training datasets
and high computational resources. Recent advances in Large Language Models
(LLMs) offer new opportunities by enhancing code understanding and reasoning.
However, existing LLM-based fault localization techniques face significant
challenges, including token limitations, performance degradation with long
inputs, and scalability issues in complex software systems. To overcome these
obstacles, we propose LLM4FL, a multi-agent fault localization framework that
utilizes three specialized LLM agents. First, the Context Extraction Agent
applies an order-sensitive segmentation strategy to partition large coverage
data within the LLM's token limit, analyze failure context, and prioritize
failure-related methods. The Debugger Agent then processes the extracted data,
which employs graph-based retrieval-augmented code navigation to reason about
failure causes and rank suspicious methods. Finally, the Reviewer Agent
re-evaluates the identified faulty methods using verbal reinforcement learning,
engaging in self-criticism and iterative refinement. Evaluated on the Defects4J
(V2.0.0) benchmark, which includes 675 faults from 14 Java projects, LLM4FL
achieves an 18.55\% improvement in Top-1 accuracy over AutoFL and 4.82\% over
SoapFL. It outperforms supervised techniques such as DeepFL and Grace, all
without requiring task-specific training. Furthermore, its coverage
segmentation and prompt chaining strategies enhance performance, increasing
Top-1 accuracy by up to 22\%.
文中引用: rafi2025multiagentapproachfaultlocalization

    - [5.1.1 Static Analysis](#511-static-analysis)
   
    - 
标题:       Static Code Analysis in the AI Era: An In-depth Exploration of the
  Concept, Function, and Potential of Intelligent Code Analysis Agents
作者:       Gang Fan, Xiaoheng Xie, Xunjin Zheng, Yinan Liang, Peng Di
发布时间:   2023-10-13
链接:       http://arxiv.org/abs/2310.08837v1
摘要:       The escalating complexity of software systems and accelerating development
cycles pose a significant challenge in managing code errors and implementing
business logic. Traditional techniques, while cornerstone for software quality
assurance, exhibit limitations in handling intricate business logic and
extensive codebases. To address these challenges, we introduce the Intelligent
Code Analysis Agent (ICAA), a novel concept combining AI models, engineering
process designs, and traditional non-AI components. The ICAA employs the
capabilities of large language models (LLMs) such as GPT-3 or GPT-4 to
automatically detect and diagnose code errors and business logic
inconsistencies. In our exploration of this concept, we observed a substantial
improvement in bug detection accuracy, reducing the false-positive rate to 66\%
from the baseline's 85\%, and a promising recall rate of 60.8\%. However, the
token consumption cost associated with LLMs, particularly the average cost for
analyzing each line of code, remains a significant consideration for widespread
adoption. Despite this challenge, our findings suggest that the ICAA holds
considerable potential to revolutionize software quality assurance,
significantly enhancing the efficiency and accuracy of bug detection in the
software development process. We hope this pioneering work will inspire further
research and innovation in this field, focusing on refining the ICAA concept
and exploring ways to mitigate the associated costs.
文中引用: fan2023staticcodeanalysisai
    - [5.1.2 Dynamic Monitoring](#512-dynamic-monitoring)
  - [5.2 Interactive Debugging Agents](#52-interactive-debugging-agents)
 
- 
标题:       COAST: Enhancing the Code Debugging Ability of LLMs through
  Communicative Agent Based Data Synthesis
作者:       Weiqing Yang, Hanbin Wang, Zhenghao Liu, Xinze Li, Yukun Yan, Shuo Wang, Yu Gu, Minghe Yu, Zhiyuan Liu, Ge Yu
发布时间:   2024-08-09
链接:       http://arxiv.org/abs/2408.05006v3
摘要:       Code debugging is a vital stage of software development, essential for
ensuring the reliability and performance of Large Language Models (LLMs) in the
code generation task. Human debugging typically follows a multi-stage process,
which includes Bug Localization, Bug Identification, Code Repair, and Code
Recognition. However, existing code debugging benchmarks predominantly focus on
the Code Repair stage, which offers only a limited perspective on evaluating
the debugging capabilities of LLMs. In this paper, we introduce DEBUGEVAL, a
comprehensive benchmark for evaluating the debugging abilities of LLMs by
emulating the multi-stage human debugging process. Through evaluating on
DEBUGEVAL, we observe that 7B-scale models consistently underperform compared
to their larger counterparts, highlighting their limitations in comprehending
code semantics. In this case, we propose the COmmunicative Agent-based data
SynThesis (COAST) framework, which employs a multi-agent system to generate
high-quality training data for supervised fine-tuning (SFT). Experimental
results demonstrate that COAST-generated data outperform human-curated and
GPT-4-generated data, enabling 7B-scale LLMs to achieve debugging performance
comparable to GPT-3.5. All data and codes are available at
https://github.com/NEUIR/COAST.
文中引用: yang2025coastenhancingcodedebugging

标题:       A Unified Debugging Approach via LLM-Based Multi-Agent Synergy
作者:       Cheryl Lee, Chunqiu Steven Xia, Longji Yang, Jen-tse Huang, Zhouruixin Zhu, Lingming Zhang, Michael R. Lyu
发布时间:   2024-04-26
链接:       http://arxiv.org/abs/2404.17153v2
摘要:       Software debugging is a time-consuming endeavor involving a series of steps,
such as fault localization and patch generation, each requiring thorough
analysis and a deep understanding of the underlying logic. While large language
models (LLMs) demonstrate promising potential in coding tasks, their
performance in debugging remains limited. Current LLM-based methods often focus
on isolated steps and struggle with complex bugs. In this paper, we propose the
first end-to-end framework, FixAgent, for unified debugging through multi-agent
synergy. It mimics the entire cognitive processes of developers, with each
agent specialized as a particular component of this process rather than
mirroring the actions of an independent expert as in previous multi-agent
systems. Agents are coordinated through a three-level design, following a
cognitive model of debugging, allowing adaptive handling of bugs with varying
complexities. Experiments on extensive benchmarks demonstrate that FixAgent
significantly outperforms state-of-the-art repair methods, fixing 1.25$\times$
to 2.56$\times$ bugs on the repo-level benchmark, Defects4J. This performance
is achieved without requiring ground-truth root-cause code statements, unlike
the baselines. Our source code is available on
https://github.com/AcceptePapier/UniDebugger.
文中引用: lee2024unifieddebuggingapproachllmbased
  - [5.3 Autonomous Program Repair](#53-autonomous-program-repair)


标题:       HyperAgent: Generalist Software Engineering Agents to Solve Coding Tasks
  at Scale
作者:       Huy Nhat Phan, Tien N. Nguyen, Phong X. Nguyen, Nghi D. Q. Bui
发布时间:   2024-09-09
链接:       http://arxiv.org/abs/2409.16299v2
摘要:       Large Language Models (LLMs) have revolutionized software engineering (SE),
showcasing remarkable proficiency in various coding tasks. Despite recent
advancements that have enabled the creation of autonomous software agents
utilizing LLMs for end-to-end development tasks, these systems are typically
designed for specific SE functions. We introduce HyperAgent, an innovative
generalist multi-agent system designed to tackle a wide range of SE tasks
across different programming languages by mimicking the workflows of human
developers. HyperAgent features four specialized agents-Planner, Navigator,
Code Editor, and Executor-capable of handling the entire lifecycle of SE tasks,
from initial planning to final verification. HyperAgent sets new benchmarks in
diverse SE tasks, including GitHub issue resolution on the renowned SWE-Bench
benchmark, outperforming robust baselines. Furthermore, HyperAgent demonstrates
exceptional performance in repository-level code generation (RepoExec) and
fault localization and program repair (Defects4J), often surpassing
state-of-the-art baselines.
文中引用: phan2024hyperagentgeneralistsoftwareengineering
 
标题:       MarsCode Agent: AI-native Automated Bug Fixing
作者:       Yizhou Liu, Pengfei Gao, Xinchen Wang, Jie Liu, Yexuan Shi, Zhao Zhang, Chao Peng
发布时间:   2024-09-02
链接:       http://arxiv.org/abs/2409.00899v2
摘要:       Recent advances in large language models (LLMs) have shown significant
potential to automate various software development tasks, including code
completion, test generation, and bug fixing. However, the application of LLMs
for automated bug fixing remains challenging due to the complexity and
diversity of real-world software systems. In this paper, we introduce MarsCode
Agent, a novel framework that leverages LLMs to automatically identify and
repair bugs in software code. MarsCode Agent combines the power of LLMs with
advanced code analysis techniques to accurately localize faults and generate
patches. Our approach follows a systematic process of planning, bug
reproduction, fault localization, candidate patch generation, and validation to
ensure high-quality bug fixes. We evaluated MarsCode Agent on SWE-bench, a
comprehensive benchmark of real-world software projects, and our results show
that MarsCode Agent achieves a high success rate in bug fixing compared to most
of the existing automated approaches.
文中引用: liu2024marscodeagentainativeautomated

  - 
标题:       RepairAgent: An Autonomous, LLM-Based Agent for Program Repair
作者:       Islem Bouzenia, Premkumar Devanbu, Michael Pradel
发布时间:   2024-03-25
链接:       http://arxiv.org/abs/2403.17134v2
摘要:       Automated program repair has emerged as a powerful technique to mitigate the
impact of software bugs on system reliability and user experience. This paper
introduces RepairAgent, the first work to address the program repair challenge
through an autonomous agent based on a large language model (LLM). Unlike
existing deep learning-based approaches, which prompt a model with a fixed
prompt or in a fixed feedback loop, our work treats the LLM as an agent capable
of autonomously planning and executing actions to fix bugs by invoking suitable
tools. RepairAgent freely interleaves gathering information about the bug,
gathering repair ingredients, and validating fixes, while deciding which tools
to invoke based on the gathered information and feedback from previous fix
attempts. Key contributions that enable RepairAgent include a set of tools that
are useful for program repair, a dynamically updated prompt format that allows
the LLM to interact with these tools, and a finite state machine that guides
the agent in invoking the tools. Our evaluation on the popular Defects4J
dataset demonstrates RepairAgent's effectiveness in autonomously repairing 164
bugs, including 39 bugs not fixed by prior techniques. Interacting with the LLM
imposes an average cost of 270,000 tokens per bug, which, under the current
pricing of OpenAI's GPT-3.5 model, translates to 14 cents of USD per bug. To
the best of our knowledge, this work is the first to present an autonomous,
LLM-based agent for program repair, paving the way for future agent-based
techniques in software engineering.
文中引用: bouzenia2024repairagentautonomousllmbasedagent

- [6. Code Review & Maintenance](#6-code-review--maintenance) ----------------------------------------------------------------------------------------------------------------------------------------C6
  - [6.1 Automated Code Review Agents](#61-automated-code-review-agents)
 
  - 
标题:       CodeAgent: Autonomous Communicative Agents for Code Review
作者:       Xunzhu Tang, Kisub Kim, Yewei Song, Cedric Lothritz, Bei Li, Saad Ezzini, Haoye Tian, Jacques Klein, Tegawende F. Bissyande
发布时间:   2024-02-03
链接:       http://arxiv.org/abs/2402.02172v5
摘要:       Code review, which aims at ensuring the overall quality and reliability of
software, is a cornerstone of software development. Unfortunately, while
crucial, Code review is a labor-intensive process that the research community
is looking to automate. Existing automated methods rely on single input-output
generative models and thus generally struggle to emulate the collaborative
nature of code review. This work introduces \tool{}, a novel multi-agent Large
Language Model (LLM) system for code review automation. CodeAgent incorporates
a supervisory agent, QA-Checker, to ensure that all the agents' contributions
address the initial review question. We evaluated CodeAgent on critical code
review tasks: (1) detect inconsistencies between code changes and commit
messages, (2) identify vulnerability introductions, (3) validate code style
adherence, and (4) suggest code revision. The results demonstrate CodeAgent's
effectiveness, contributing to a new state-of-the-art in code review
automation. Our data and code are publicly available
(\url{https://github.com/Code4Agent/codeagent}).
文中引用: tang2024codeagentautonomouscommunicativeagents

  - [6.2 Iterative Improvement & Refactoring Agents](#62-iterative-improvement--refactoring-agents)
 
  - 
标题:       Agent-Driven Automatic Software Improvement
作者:       Fernando Vallecillos Ruiz
发布时间:   2024-06-24
链接:       http://arxiv.org/abs/2406.16739v1
摘要:       With software maintenance accounting for 50% of the cost of developing
software, enhancing code quality and reliability has become more critical than
ever. In response to this challenge, this doctoral research proposal aims to
explore innovative solutions by focusing on the deployment of agents powered by
Large Language Models (LLMs) to perform software maintenance tasks. The
iterative nature of agents, which allows for continuous learning and
adaptation, can help surpass common challenges in code generation. One distinct
challenge is the last-mile problems, errors at the final stage of producing
functionally and contextually relevant code. Furthermore, this project aims to
surpass the inherent limitations of current LLMs in source code through a
collaborative framework where agents can correct and learn from each other's
errors. We aim to use the iterative feedback in these systems to further
fine-tune the LLMs underlying the agents, becoming better aligned to the task
of automated software improvement. Our main goal is to achieve a leap forward
in the field of automatic software improvement by developing new tools and
frameworks that can enhance the efficiency and reliability of software
development.
文中引用: ruiz2024agentdrivenautomaticsoftwareimprovement

  - [6.3 Dependency Management Agents](#63-dependency-management-agents)
 
  - 
标题:       DepsRAG: Towards Agentic Reasoning and Planning for Software Dependency
  Management
作者:       Mohannad Alhanahnah, Yazan Boshmaf
发布时间:   2024-05-30
链接:       http://arxiv.org/abs/2405.20455v5
摘要:       In the era of Large Language Models (LLMs) with their advanced capabilities,
a unique opportunity arises to develop LLM-based digital assistant tools that
can support software developers by facilitating comprehensive reasoning about
software dependencies and open-source libraries before importing them. This
reasoning process is daunting, mandating multiple specialized tools and
dedicated expertise, each focusing on distinct aspects (e.g., security analysis
tools may overlook design flaws such as circular dependencies, which hinder
software maintainability). Creating a significant bottleneck in the software
development lifecycle. In this paper, we introduce DepsRAG, a multi-agent
framework designed to assist developers in reasoning about software
dependencies. DepsRAG first constructs a comprehensive Knowledge Graph (KG)
that includes both direct and transitive dependencies. Developers can interact
with DepsRAG through a conversational interface, posing queries about the
dependencies. DepsRAG employs Retrieval-Augmented Generation (RAG) to enhance
these queries by retrieving relevant information from the KG as well as
external sources, such as the Web and vulnerability databases, thus
demonstrating its adaptability to novel scenarios. DepsRAG incorporates a
Critic-Agent feedback loop to ensure the accuracy and clarity of LLM-generated
responses. We evaluated DepsRAG using GPT-4-Turbo and Llama-3 on three
multi-step reasoning tasks, observing a threefold increase in accuracy with the
integration of the Critic-Agent mechanism. DepsRAG demo and implementation are
available: https://github.com/Mohannadcse/DepsRAG.
文中引用: alhanahnah2024depsragagenticreasoningplanning
- [7. Deployment, Operations & Monitoring](#7-deployment-operations--monitoring)----------------------------------------------------------------------------------------------------------------------C7
  - [7.1 Root Cause Analysis (RCA) Agents](#71-root-cause-analysis-rca-agents)


标题:       Building AI Agents for Autonomous Clouds: Challenges and Design
  Principles
作者:       Manish Shetty, Yinfang Chen, Gagan Somashekar, Minghua Ma, Yogesh Simmhan, Xuchao Zhang, Jonathan Mace, Dax Vandevoorde, Pedro Las-Casas, Shachee Mishra Gupta, Suman Nath, Chetan Bansal, Saravan Rajmohan
发布时间:   2024-07-16
链接:       http://arxiv.org/abs/2407.12165v2
摘要:       The rapid growth in the use of Large Language Models (LLMs) and AI Agents as
part of software development and deployment is revolutionizing the information
technology landscape. While code generation receives significant attention, a
higher-impact application lies in using AI agents for operational resilience of
cloud services, which currently require significant human effort and domain
knowledge. There is a growing interest in AI for IT Operations (AIOps) which
aims to automate complex operational tasks, like fault localization and root
cause analysis, thereby reducing human intervention and customer impact.
However, achieving the vision of autonomous and self-healing clouds through
AIOps is hampered by the lack of standardized frameworks for building,
evaluating, and improving AIOps agents. This vision paper lays the groundwork
for such a framework by first framing the requirements and then discussing
design decisions that satisfy them. We also propose AIOpsLab, a prototype
implementation leveraging agent-cloud-interface that orchestrates an
application, injects real-time faults using chaos engineering, and interfaces
with an agent to localize and resolve the faults. We report promising results
and lay the groundwork to build a modular and robust framework for building,
evaluating, and improving agents for autonomous clouds.
文中引用: shetty2024buildingaiagentsautonomous
------------------------------------------------------------

标题:       Exploring LLM-based Agents for Root Cause Analysis
作者:       Devjeet Roy, Xuchao Zhang, Rashi Bhave, Chetan Bansal, Pedro Las-Casas, Rodrigo Fonseca, Saravan Rajmohan
发布时间:   2024-03-07
链接:       http://arxiv.org/abs/2403.04123v1
摘要:       The growing complexity of cloud based software systems has resulted in
incident management becoming an integral part of the software development
lifecycle. Root cause analysis (RCA), a critical part of the incident
management process, is a demanding task for on-call engineers, requiring deep
domain knowledge and extensive experience with a team's specific services.
Automation of RCA can result in significant savings of time, and ease the
burden of incident management on on-call engineers. Recently, researchers have
utilized Large Language Models (LLMs) to perform RCA, and have demonstrated
promising results. However, these approaches are not able to dynamically
collect additional diagnostic information such as incident related logs,
metrics or databases, severely restricting their ability to diagnose root
causes. In this work, we explore the use of LLM based agents for RCA to address
this limitation. We present a thorough empirical evaluation of a ReAct agent
equipped with retrieval tools, on an out-of-distribution dataset of production
incidents collected at Microsoft. Results show that ReAct performs
competitively with strong retrieval and reasoning baselines, but with highly
increased factual accuracy. We then extend this evaluation by incorporating
discussions associated with incident reports as additional inputs for the
models, which surprisingly does not yield significant performance improvements.
Lastly, we conduct a case study with a team at Microsoft to equip the ReAct
agent with tools that give it access to external diagnostic services that are
used by the team for manual RCA. Our results show how agents can overcome the
limitations of prior work, and practical considerations for implementing such a
system in practice.
文中引用: roy2024exploringllmbasedagentsroot

  - 
标题:       RCAgent: Cloud Root Cause Analysis by Autonomous Agents with
  Tool-Augmented Large Language Models
作者:       Zefan Wang, Zichuan Liu, Yingying Zhang, Aoxiao Zhong, Jihong Wang, Fengbin Yin, Lunting Fan, Lingfei Wu, Qingsong Wen
发布时间:   2023-10-25
链接:       http://arxiv.org/abs/2310.16340v3
摘要:       Large language model (LLM) applications in cloud root cause analysis (RCA)
have been actively explored recently. However, current methods are still
reliant on manual workflow settings and do not unleash LLMs' decision-making
and environment interaction capabilities. We present RCAgent, a tool-augmented
LLM autonomous agent framework for practical and privacy-aware industrial RCA
usage. Running on an internally deployed model rather than GPT families,
RCAgent is capable of free-form data collection and comprehensive analysis with
tools. Our framework combines a variety of enhancements, including a unique
Self-Consistency for action trajectories, and a suite of methods for context
management, stabilization, and importing domain knowledge. Our experiments show
RCAgent's evident and consistent superiority over ReAct across all aspects of
RCA -- predicting root causes, solutions, evidence, and responsibilities -- and
tasks covered or uncovered by current rules, as validated by both automated
metrics and human evaluations. Furthermore, RCAgent has already been integrated
into the diagnosis and issue discovery workflow of the Real-time Compute
Platform for Apache Flink of Alibaba Cloud.
文中引用: wang2024rcagentcloudrootcause
  - [7.2 Configuration & Performance Sensitivity Analysis](#72-configuration--performance-sensitivity-analysis)

  - 
标题:       Identifying Performance-Sensitive Configurations in Software Systems
  through Code Analysis with LLM Agents
作者:       Zehao Wang, Dong Jae Kim, Tse-Hsun Chen
发布时间:   2024-06-18
链接:       http://arxiv.org/abs/2406.12806v1
摘要:       Configuration settings are essential for tailoring software behavior to meet
specific performance requirements. However, incorrect configurations are
widespread, and identifying those that impact system performance is challenging
due to the vast number and complexity of possible settings. In this work, we
present PerfSense, a lightweight framework that leverages Large Language Models
(LLMs) to efficiently identify performance-sensitive configurations with
minimal overhead. PerfSense employs LLM agents to simulate interactions between
developers and performance engineers using advanced prompting techniques such
as prompt chaining and retrieval-augmented generation (RAG). Our evaluation of
seven open-source Java systems demonstrates that PerfSense achieves an average
accuracy of 64.77% in classifying performance-sensitive configurations,
outperforming both our LLM baseline (50.36%) and the previous state-of-the-art
method (61.75%). Notably, our prompt chaining technique improves recall by 10%
to 30% while maintaining similar precision levels. Additionally, a manual
analysis of 362 misclassifications reveals common issues, including LLMs'
misunderstandings of requirements (26.8%). In summary, PerfSense significantly
reduces manual effort in classifying performance-sensitive configurations and
offers valuable insights for future LLM-based code analysis research.
文中引用: wang2024identifyingperformancesensitiveconfigurationssoftware

  - [7.3 Issue / Incident Resolution Agents](#73-issue--incident-resolution-agents)


标题:       GoNoGo: An Efficient LLM-based Multi-Agent System for Streamlining
  Automotive Software Release Decision-Making
作者:       Arsham Gholamzadeh Khoee, Yinan Yu, Robert Feldt, Andris Freimanis, Patrick Andersson Rhodin, Dhasarathy Parthasarathy
发布时间:   2024-08-19
链接:       http://arxiv.org/abs/2408.09785v2
摘要:       Traditional methods for making software deployment decisions in the
automotive industry typically rely on manual analysis of tabular software test
data. These methods often lead to higher costs and delays in the software
release cycle due to their labor-intensive nature. Large Language Models (LLMs)
present a promising solution to these challenges. However, their application
generally demands multiple rounds of human-driven prompt engineering, which
limits their practical deployment, particularly for industrial end-users who
need reliable and efficient results. In this paper, we propose GoNoGo, an LLM
agent system designed to streamline automotive software deployment while
meeting both functional requirements and practical industrial constraints.
Unlike previous systems, GoNoGo is specifically tailored to address
domain-specific and risk-sensitive systems. We evaluate GoNoGo's performance
across different task difficulties using zero-shot and few-shot examples taken
from industrial practice. Our results show that GoNoGo achieves a 100% success
rate for tasks up to Level 2 difficulty with 3-shot examples, and maintains
high performance even for more complex tasks. We find that GoNoGo effectively
automates decision-making for simpler tasks, significantly reducing the need
for manual intervention. In summary, GoNoGo represents an efficient and
user-friendly LLM-based solution currently employed in our industrial partner's
company to assist with software release decision-making, supporting more
informed and timely decisions in the release process for risk-sensitive vehicle
systems.
文中引用: khoee2024gonogoefficientllmbasedmultiagent

  - 
标题:       MAGIS: LLM-Based Multi-Agent Framework for GitHub Issue Resolution
作者:       Wei Tao, Yucheng Zhou, Yanlin Wang, Wenqiang Zhang, Hongyu Zhang, Yu Cheng
发布时间:   2024-03-26
链接:       http://arxiv.org/abs/2403.17927v2
摘要:       In software development, resolving the emergent issues within GitHub
repositories is a complex challenge that involves not only the incorporation of
new code but also the maintenance of existing code. Large Language Models
(LLMs) have shown promise in code generation but face difficulties in resolving
Github issues, particularly at the repository level. To overcome this
challenge, we empirically study the reason why LLMs fail to resolve GitHub
issues and analyze the major factors. Motivated by the empirical findings, we
propose a novel LLM-based Multi-Agent framework for GitHub Issue reSolution,
MAGIS, consisting of four agents customized for software evolution: Manager,
Repository Custodian, Developer, and Quality Assurance Engineer agents. This
framework leverages the collaboration of various agents in the planning and
coding process to unlock the potential of LLMs to resolve GitHub issues. In
experiments, we employ the SWE-bench benchmark to compare MAGIS with popular
LLMs, including GPT-3.5, GPT-4, and Claude-2. MAGIS can resolve 13.94% GitHub
issues, significantly outperforming the baselines. Specifically, MAGIS achieves
an eight-fold increase in resolved ratio over the direct application of GPT-4,
the advanced LLM.
文中引用: tao2024magisllmbasedmultiagentframework

- [8. Security, Compliance & Auditing](#8-security-compliance--auditing)
  - [8.1 Smart Contract Auditing Agents](#81-smart-contract-auditing-agents)
 
  - 
标题:       Combining Fine-Tuning and LLM-based Agents for Intuitive Smart Contract
  Auditing with Justifications
作者:       Wei Ma, Daoyuan Wu, Yuqiang Sun, Tianwen Wang, Shangqing Liu, Jian Zhang, Yue Xue, Yang Liu
发布时间:   2024-03-24
链接:       http://arxiv.org/abs/2403.16073v3
摘要:       Smart contracts are decentralized applications built atop blockchains like
Ethereum. Recent research has shown that large language models (LLMs) have
potential in auditing smart contracts, but the state-of-the-art indicates that
even GPT-4 can achieve only 30% precision (when both decision and justification
are correct). This is likely because off-the-shelf LLMs were primarily
pre-trained on a general text/code corpus and not fine-tuned on the specific
domain of Solidity smart contract auditing.
  In this paper, we propose iAudit, a general framework that combines
fine-tuning and LLM-based agents for intuitive smart contract auditing with
justifications. Specifically, iAudit is inspired by the observation that expert
human auditors first perceive what could be wrong and then perform a detailed
analysis of the code to identify the cause. As such, iAudit employs a two-stage
fine-tuning approach: it first tunes a Detector model to make decisions and
then tunes a Reasoner model to generate causes of vulnerabilities. However,
fine-tuning alone faces challenges in accurately identifying the optimal cause
of a vulnerability. Therefore, we introduce two LLM-based agents, the Ranker
and Critic, to iteratively select and debate the most suitable cause of
vulnerability based on the output of the fine-tuned Reasoner model. To evaluate
iAudit, we collected a balanced dataset with 1,734 positive and 1,810 negative
samples to fine-tune iAudit. We then compared it with traditional fine-tuned
models (CodeBERT, GraphCodeBERT, CodeT5, and UnixCoder) as well as prompt
learning-based LLMs (GPT4, GPT-3.5, and CodeLlama-13b/34b). On a dataset of 263
real smart contract vulnerabilities, iAudit achieves an F1 score of 91.21% and
an accuracy of 91.11%. The causes generated by iAudit achieved a consistency of
about 38% compared to the ground truth causes.
文中引用: ma2024combiningfinetuningllmbasedagents

  - [8.2 Human-in-the-Loop Security Co-Design Agents](#82-human-in-the-loop-security-co-design-agents)

 
标题:       AutoSafeCoder: A Multi-Agent Framework for Securing LLM Code Generation
  through Static Analysis and Fuzz Testing
作者:       Ana Nunez, Nafis Tanveer Islam, Sumit Kumar Jha, Peyman Najafirad
发布时间:   2024-09-16
链接:       http://arxiv.org/abs/2409.10737v2
摘要:       Recent advancements in automatic code generation using large language models
(LLMs) have brought us closer to fully automated secure software development.
However, existing approaches often rely on a single agent for code generation,
which struggles to produce secure, vulnerability-free code. Traditional program
synthesis with LLMs has primarily focused on functional correctness, often
neglecting critical dynamic security implications that happen during runtime.
To address these challenges, we propose AutoSafeCoder, a multi-agent framework
that leverages LLM-driven agents for code generation, vulnerability analysis,
and security enhancement through continuous collaboration. The framework
consists of three agents: a Coding Agent responsible for code generation, a
Static Analyzer Agent identifying vulnerabilities, and a Fuzzing Agent
performing dynamic testing using a mutation-based fuzzing approach to detect
runtime errors. Our contribution focuses on ensuring the safety of multi-agent
code generation by integrating dynamic and static testing in an iterative
process during code generation by LLM that improves security. Experiments using
the SecurityEval dataset demonstrate a 13% reduction in code vulnerabilities
compared to baseline LLMs, with no compromise in functionality.
文中引用: nunez2024autosafecodermultiagentframeworksecuring

  - 
标题:       Concept-Guided LLM Agents for Human-AI Safety Codesign
作者:       Florian Geissler, Karsten Roscher, Mario Trapp
发布时间:   2024-04-03
链接:       http://arxiv.org/abs/2404.15317v1
摘要:       Generative AI is increasingly important in software engineering, including
safety engineering, where its use ensures that software does not cause harm to
people. This also leads to high quality requirements for generative AI.
Therefore, the simplistic use of Large Language Models (LLMs) alone will not
meet these quality demands. It is crucial to develop more advanced and
sophisticated approaches that can effectively address the complexities and
safety concerns of software systems. Ultimately, humans must understand and
take responsibility for the suggestions provided by generative AI to ensure
system safety. To this end, we present an efficient, hybrid strategy to
leverage LLMs for safety analysis and Human-AI codesign. In particular, we
develop a customized LLM agent that uses elements of prompt engineering,
heuristic reasoning, and retrieval-augmented generation to solve tasks
associated with predefined safety concepts, in interaction with a system model
graph. The reasoning is guided by a cascade of micro-decisions that help
preserve structured information. We further suggest a graph verbalization which
acts as an intermediate representation of the system model to facilitate
LLM-graph interactions. Selected pairs of prompts and responses relevant for
safety analytics illustrate our method for the use case of a simplified
automated driving system.
文中引用: geissler2024conceptguidedllmagentshumanai

  - [8.3 Compliance Detection Agents](#83-compliance-detection-agents)
- [9. Education & Learning Agents](#9-education--learning-agents)
  - [9.1 Programming Tutoring & Educational Agents](#91-programming-tutoring--educational-agents)
 
  
标题:       Co-Learning: Code Learning for Multi-Agent Reinforcement Collaborative
  Framework with Conversational Natural Language Interfaces
作者:       Jiapeng Yu, Yuqian Wu, Yajing Zhan, Wenhao Guo, Zhou Xu, Raymond Lee
发布时间:   2024-09-02
链接:       http://arxiv.org/abs/2409.00985v1
摘要:       Online question-and-answer (Q\&A) systems based on the Large Language Model
(LLM) have progressively diverged from recreational to professional use. This
paper proposed a Multi-Agent framework with environmentally reinforcement
learning (E-RL) for code correction called Code Learning (Co-Learning)
community, assisting beginners to correct code errors independently. It
evaluates the performance of multiple LLMs from an original dataset with 702
error codes, uses it as a reward or punishment criterion for E-RL; Analyzes
input error codes by the current agent; selects the appropriate LLM-based agent
to achieve optimal error correction accuracy and reduce correction time.
Experiment results showed that 3\% improvement in Precision score and 15\%
improvement in time cost as compared with no E-RL method respectively. Our
source code is available at: https://github.com/yuqian2003/Co_Learning
文中引用: yu2024colearningcodelearningmultiagent

标题:       How to Teach Programming in the AI Era? Using LLMs as a Teachable Agent
  for Debugging
作者:       Qianou Ma, Hua Shen, Kenneth Koedinger, Tongshuang Wu
发布时间:   2023-10-08
链接:       http://arxiv.org/abs/2310.05292v5
摘要:       Large Language Models (LLMs) now excel at generative skills and can create
content at impeccable speeds. However, they are imperfect and still make
various mistakes. In a Computer Science education context, as these models are
widely recognized as "AI pair programmers," it becomes increasingly important
to train students on evaluating and debugging the LLM-generated code. In this
work, we introduce HypoCompass, a novel system to facilitate deliberate
practice on debugging, where human novices play the role of Teaching Assistants
and help LLM-powered teachable agents debug code. We enable effective task
delegation between students and LLMs in this learning-by-teaching environment:
students focus on hypothesizing the cause of code errors, while adjacent skills
like code completion are offloaded to LLM-agents. Our evaluations demonstrate
that HypoCompass generates high-quality training materials (e.g., bugs and
fixes), outperforming human counterparts fourfold in efficiency, and
significantly improves student performance on debugging by 12% in the
pre-to-post test.
文中引用: ma2024teachprogrammingaiera
  - [9.2 Simulation & Modeling Interface Agents](#92-simulation--modeling-interface-agents)
 
  - 
标题:       Text2BIM: Generating Building Models Using a Large Language Model-based
  Multi-Agent Framework
作者:       Changyu Du, Sebastian Esser, Stavros Nousias, André Borrmann
发布时间:   2024-08-15
链接:       http://arxiv.org/abs/2408.08054v2
摘要:       The conventional BIM authoring process typically requires designers to master
complex and tedious modeling commands in order to materialize their design
intentions within BIM authoring tools. This additional cognitive burden
complicates the design process and hinders the adoption of BIM and model-based
design in the AEC (Architecture, Engineering, and Construction) industry. To
facilitate the expression of design intentions more intuitively, we propose
Text2BIM, an LLM-based multi-agent framework that can generate 3D building
models from natural language instructions. This framework orchestrates multiple
LLM agents to collaborate and reason, transforming textual user input into
imperative code that invokes the BIM authoring tool's APIs, thereby generating
editable BIM models with internal layouts, external envelopes, and semantic
information directly in the software. Furthermore, a rule-based model checker
is introduced into the agentic workflow, utilizing predefined domain knowledge
to guide the LLM agents in resolving issues within the generated models and
iteratively improving model quality. Extensive experiments were conducted to
compare and analyze the performance of three different LLMs under the proposed
framework. The evaluation results demonstrate that our approach can effectively
generate high-quality, structurally rational building models that are aligned
with the abstract concepts specified by user input. Finally, an interactive
software prototype was developed to integrate the framework into the BIM
authoring software Vectorworks, showcasing the potential of modeling by
chatting. The code is available at: https://github.com/dcy0577/Text2BIM
文中引用: du2025text2bimgeneratingbuildingmodels

    
标题:       Solution-oriented Agent-based Models Generation with Verifier-assisted
  Iterative In-context Learning
作者:       Tong Niu, Weihao Zhang, Rong Zhao
发布时间:   2024-02-04
链接:       http://arxiv.org/abs/2402.02388v1
摘要:       Agent-based models (ABMs) stand as an essential paradigm for proposing and
validating hypothetical solutions or policies aimed at addressing challenges
posed by complex systems and achieving various objectives. This process demands
labor-intensive endeavors and multidisciplinary expertise. Large language
models (LLMs) encapsulating cross-domain knowledge and programming proficiency
could potentially alleviate the difficulty of this process. However, LLMs excel
in handling sequential information, making it challenging for analyzing the
intricate interactions and nonlinear dynamics inherent in ABMs. Additionally,
due to the lack of self-evaluation capability of LLMs, relying solely on LLMs
is insufficient to effectively accomplish this process. In this paper, we
present SAGE, a general solution-oriented ABM generation framework designed for
automatic modeling and generating solutions for targeted problems. Unlike
approaches reliant on expert handcrafting or resource-intensive neural network
training, SAGE establishes a verifier-assisted iterative in-context learning
process employing large language models (LLMs) to leverages their inherent
cross-domain knowledge for tackling intricate demands from diverse domain
scenarios. In SAGE, we introduce an semi-structured conceptual representation
expliciting the intricate structures of ABMs and an objective representation to
guide LLMs in modeling scenarios and proposing hypothetical solutions through
in-context learning. To ensure the model executability and solution
feasibility, SAGE devises a two-level verifier with chain-of-thought prompting
tailored to the complex interactions and non-linear dynamics of ABMs, driving
the iterative generation optimization. Moreover, we construct an evaluation
dataset of solution-oriented ABMs from open sources.It contains practical
models across various domains.
文中引用: niu2024solutionorientedagentbasedmodelsgeneration

标题:       ChatLogo: A Large Language Model-Driven Hybrid Natural-Programming
  Language Interface for Agent-based Modeling and Programming
作者:       John Chen, Uri Wilensky
发布时间:   2023-08-16
链接:       http://arxiv.org/abs/2308.08102v1
摘要:       Building on Papert (1980)'s idea of children talking to computers, we propose
ChatLogo, a hybrid natural-programming language interface for agent-based
modeling and programming. We build upon previous efforts to scaffold ABM & P
learning and recent development in leveraging large language models (LLMs) to
support the learning of computational programming. ChatLogo aims to support
conversations with computers in a mix of natural and programming languages,
provide a more user-friendly interface for novice learners, and keep the
technical system from over-reliance on any single LLM. We introduced the main
elements of our design: an intelligent command center, and a conversational
interface to support creative expression. We discussed the presentation format
and future work. Responding to the challenges of supporting open-ended
constructionist learning of ABM & P and leveraging LLMs for educational
purposes, we contribute to the field by proposing the first constructionist
LLM-driven interface to support computational and complex systems thinking.
文中引用: chen2023chatlogolargelanguagemodeldriven
- [10. Research Automation & Evaluation](#10-research-automation--evaluation)
  - [10.1 Automated Literature Review Agents](#101-automated-literature-review-agents)
  - 
标题:       System for systematic literature review using multiple AI agents:
  Concept and an empirical evaluation
作者:       Abdul Malik Sami, Zeeshan Rasheed, Kai-Kristian Kemell, Muhammad Waseem, Terhi Kilamo, Mika Saari, Anh Nguyen Duc, Kari Systä, Pekka Abrahamsson
发布时间:   2024-03-13
链接:       http://arxiv.org/abs/2403.08399v1
摘要:       Systematic Literature Reviews (SLRs) have become the foundation of
evidence-based studies, enabling researchers to identify, classify, and combine
existing studies based on specific research questions. Conducting an SLR is
largely a manual process. Over the previous years, researchers have made
significant progress in automating certain phases of the SLR process, aiming to
reduce the effort and time needed to carry out high-quality SLRs. However,
there is still a lack of AI agent-based models that automate the entire SLR
process. To this end, we introduce a novel multi-AI agent model designed to
fully automate the process of conducting an SLR. By utilizing the capabilities
of Large Language Models (LLMs), our proposed model streamlines the review
process, enhancing efficiency and accuracy. The model operates through a
user-friendly interface where researchers input their topic, and in response,
the model generates a search string used to retrieve relevant academic papers.
Subsequently, an inclusive and exclusive filtering process is applied, focusing
on titles relevant to the specific research area. The model then autonomously
summarizes the abstracts of these papers, retaining only those directly related
to the field of study. In the final phase, the model conducts a thorough
analysis of the selected papers concerning predefined research questions. We
also evaluated the proposed model by sharing it with ten competent software
engineering researchers for testing and analysis. The researchers expressed
strong satisfaction with the proposed model and provided feedback for further
improvement. The code for this project can be found on the GitHub repository at
https://github.com/GPT-Laboratory/SLR-automation.
文中引用: sami2024systematicliteraturereviewusing

  - [10.2 Performance Benchmarking & Evaluation](#102-performance-benchmarking--evaluation)


标题:       AppWorld: A Controllable World of Apps and People for Benchmarking
  Interactive Coding Agents
作者:       Harsh Trivedi, Tushar Khot, Mareike Hartmann, Ruskin Manku, Vinty Dong, Edward Li, Shashank Gupta, Ashish Sabharwal, Niranjan Balasubramanian
发布时间:   2024-07-26
链接:       http://arxiv.org/abs/2407.18901v1
摘要:       Autonomous agents that address day-to-day digital tasks (e.g., ordering
groceries for a household), must not only operate multiple apps (e.g., notes,
messaging, shopping app) via APIs, but also generate rich code with complex
control flow in an iterative manner based on their interaction with the
environment. However, existing benchmarks for tool use are inadequate, as they
only cover tasks that require a simple sequence of API calls.
  To remedy this gap, we built $\textbf{AppWorld Engine}$, a high-quality
execution environment (60K lines of code) of 9 day-to-day apps operable via 457
APIs and populated with realistic digital activities simulating the lives of
~100 fictitious users. We then created $\textbf{AppWorld Benchmark}$ (40K lines
of code), a suite of 750 natural, diverse, and challenging autonomous agent
tasks requiring rich and interactive code generation. It supports robust
programmatic evaluation with state-based unit tests, allowing for different
ways of completing a task while also checking for unexpected changes, i.e.,
collateral damage. The state-of-the-art LLM, GPT-4o, solves only ~49% of our
'normal' tasks and ~30% of 'challenge' tasks, while other models solve at least
16% fewer. This highlights the benchmark's difficulty and AppWorld's potential
to push the frontiers of interactive coding agents. The project website is
available at https://appworld.dev/.
文中引用: trivedi2024appworldcontrollableworldapps


标题:       PyBench: Evaluating LLM Agent on various real-world coding tasks
作者:       Yaolun Zhang, Yinxu Pan, Yudong Wang, Jie Cai
发布时间:   2024-07-23
链接:       http://arxiv.org/abs/2407.16732v2
摘要:       The LLM Agent, equipped with a code interpreter, is capable of automatically
solving real-world coding tasks, such as data analysis and image editing.
  However, existing benchmarks primarily focus on either simplistic tasks, such
as completing a few lines of code, or on extremely complex and specific tasks
at the repository level, neither of which are representative of various daily
coding tasks.
  To address this gap, we introduce \textbf{PyBench}, a benchmark encompassing
five main categories of real-world tasks, covering more than 10 types of files.
Given a high-level user query and related files, the LLM Agent needs to reason
and execute Python code via a code interpreter for a few turns before making a
formal response to fulfill the user's requirements. Successfully addressing
tasks in PyBench demands a robust understanding of various Python packages,
superior reasoning capabilities, and the ability to incorporate feedback from
executed code. Our evaluations indicate that current open-source LLMs are
struggling with these tasks. Hence, we conduct analysis and experiments on four
kinds of datasets proving that comprehensive abilities are needed for PyBench.
Our fine-tuned 8B size model: \textbf{PyLlama3} achieves an exciting
performance on PyBench which surpasses many 33B and 70B size models. Our
Benchmark, Training Dataset, and Model are available at:
{https://github.com/Mercury7353/PyBench}
文中引用: zhang2024pybenchevaluatingllmagent


标题:       Agentless: Demystifying LLM-based Software Engineering Agents
作者:       Chunqiu Steven Xia, Yinlin Deng, Soren Dunn, Lingming Zhang
发布时间:   2024-07-01
链接:       http://arxiv.org/abs/2407.01489v2
摘要:       Recent advancements in large language models (LLMs) have significantly
advanced the automation of software development tasks, including code
synthesis, program repair, and test generation. More recently, researchers and
industry practitioners have developed various autonomous LLM agents to perform
end-to-end software development tasks. These agents are equipped with the
ability to use tools, run commands, observe feedback from the environment, and
plan for future actions. However, the complexity of these agent-based
approaches, together with the limited abilities of current LLMs, raises the
following question: Do we really have to employ complex autonomous software
agents? To attempt to answer this question, we build Agentless -- an agentless
approach to automatically solve software development problems. Compared to the
verbose and complex setup of agent-based approaches, Agentless employs a
simplistic three-phase process of localization, repair, and patch validation,
without letting the LLM decide future actions or operate with complex tools.
Our results on the popular SWE-bench Lite benchmark show that surprisingly the
simplistic Agentless is able to achieve both the highest performance (32.00%,
96 correct fixes) and low cost ($0.70) compared with all existing open-source
software agents! Furthermore, we manually classified the problems in SWE-bench
Lite and found problems with exact ground truth patch or
insufficient/misleading issue descriptions. As such, we construct SWE-bench
Lite-S by excluding such problematic issues to perform more rigorous evaluation
and comparison. Our work highlights the current overlooked potential of a
simple, interpretable technique in autonomous software development. We hope
Agentless will help reset the baseline, starting point, and horizon for
autonomous software agents, and inspire future work along this crucial
direction.
文中引用: xia2024agentlessdemystifyingllmbasedsoftware

标题:       ShortcutsBench: A Large-Scale Real-world Benchmark for API-based Agents
作者:       Haiyang Shen, Yue Li, Desong Meng, Dongqi Cai, Sheng Qi, Li Zhang, Mengwei Xu, Yun Ma
发布时间:   2024-06-28
链接:       http://arxiv.org/abs/2407.00132v3
摘要:       Recent advancements in integrating large language models (LLMs) with
application programming interfaces (APIs) have gained significant interest in
both academia and industry. Recent work demonstrates that these API-based
agents exhibit relatively strong autonomy and planning capabilities. However,
their ability to handle multi-dimensional difficulty levels, diverse task
types, and real-world demands remains unknown. In this paper, we introduce
\textsc{ShortcutsBench}, a large-scale benchmark for the comprehensive
evaluation of API-based agents in solving real-world complex tasks.
\textsc{ShortcutsBench} includes a wealth of real APIs from Apple Inc., refined
user queries, human-annotated high-quality action sequences, detailed parameter
filling values, and parameters requesting necessary input from the system or
user. We revealed how existing benchmarks~/~datasets struggle to accommodate
the advanced reasoning capabilities of existing more intelligent LLMs.
Moreover, our extensive evaluation of agents built with $5$ leading open-source
(size $\geq$ 57B) and $5$ closed-source LLMs (e.g. Gemini-1.5-Pro and
GPT-4o-mini) with varying intelligence level reveals significant limitations of
existing API-based agents in the whole process of handling complex queries
related to API selection, parameter filling, and requesting necessary input
from the system and the user. These findings highlight the great challenges
that API-based agents face in effectively fulfilling real and complex user
queries. All datasets, code, experimental logs, and results are available at
\url{https://github.com/EachSheep/ShortcutsBench}.
文中引用: shen2025shortcutsbenchlargescalerealworldbenchmark

 
标题:       HumanEvalComm: Benchmarking the Communication Competence of Code
  Generation for LLMs and LLM Agent
作者:       Jie JW Wu, Fatemeh H Fard
发布时间:   2024-05-31
链接:       http://arxiv.org/abs/2406.00215v3
摘要:       Large language models (LLMs) have significantly improved their ability to
perform tasks in the field of code generation. However, there is still a gap
between LLMs being capable coders and being top-tier software engineers. Based
on the observation that top-level software engineers often ask clarifying
questions to reduce ambiguity in both requirements and coding solutions, we
argue that the same should be applied to LLMs for code generation tasks.
  In this work, we conducted an empirical study on the benchmark and analysis
of the communication skills of LLMs for code generation. We define
communication skills of LLMs as ``being able to ask clarifying questions when
the description of the code generation problem has issues''. We created a new
benchmark, HumanEvalComm, by modifying problem descriptions according to three
issues: inconsistency, ambiguity, incompleteness. We defined new evaluation
metrics such as Communication Rate and Good Question Rate, and then
experimented on HumanEvalComm with different Code LLMs, and a new LLM agent
approach, Okanagan, to identify and ask questions in ambiguous parts from code
and descriptions for further refining the generated code. Finally, we discussed
evaluation results by comparing Code LLMs and Okanagan with our findings.
文中引用: wu2025humanevalcommbenchmarkingcommunicationcompetence

标题:       Large Language Model Evaluation Via Multi AI Agents: Preliminary results
作者:       Zeeshan Rasheed, Muhammad Waseem, Kari Systä, Pekka Abrahamsson
发布时间:   2024-04-01
链接:       http://arxiv.org/abs/2404.01023v1
摘要:       As Large Language Models (LLMs) have become integral to both research and
daily operations, rigorous evaluation is crucial. This assessment is important
not only for individual tasks but also for understanding their societal impact
and potential risks. Despite extensive efforts to examine LLMs from various
perspectives, there is a noticeable lack of multi-agent AI models specifically
designed to evaluate the performance of different LLMs. To address this gap, we
introduce a novel multi-agent AI model that aims to assess and compare the
performance of various LLMs. Our model consists of eight distinct AI agents,
each responsible for retrieving code based on a common description from
different advanced language models, including GPT-3.5, GPT-3.5 Turbo, GPT-4,
GPT-4 Turbo, Google Bard, LLAMA, and Hugging Face. Our developed model utilizes
the API of each language model to retrieve code for a given high-level
description. Additionally, we developed a verification agent, tasked with the
critical role of evaluating the code generated by its counterparts. We
integrate the HumanEval benchmark into our verification agent to assess the
generated code's performance, providing insights into their respective
capabilities and efficiencies. Our initial results indicate that the GPT-3.5
Turbo model's performance is comparatively better than the other models. This
preliminary analysis serves as a benchmark, comparing their performances side
by side. Our future goal is to enhance the evaluation process by incorporating
the Massively Multitask Benchmark for Python (MBPP) benchmark, which is
expected to further refine our assessment. Additionally, we plan to share our
developed model with twenty practitioners from various backgrounds to test our
model and collect their feedback for further improvement.
文中引用: rasheed2024largelanguagemodelevaluation
  - 
标题:       Understanding the Weakness of Large Language Model Agents within a
  Complex Android Environment
作者:       Mingzhe Xing, Rongkai Zhang, Hui Xue, Qi Chen, Fan Yang, Zhen Xiao
发布时间:   2024-02-09
链接:       http://arxiv.org/abs/2402.06596v1
摘要:       Large language models (LLMs) have empowered intelligent agents to execute
intricate tasks within domain-specific software such as browsers and games.
However, when applied to general-purpose software systems like operating
systems, LLM agents face three primary challenges. Firstly, the action space is
vast and dynamic, posing difficulties for LLM agents to maintain an up-to-date
understanding and deliver accurate responses. Secondly, real-world tasks often
require inter-application cooperation}, demanding farsighted planning from LLM
agents. Thirdly, agents need to identify optimal solutions aligning with user
constraints, such as security concerns and preferences. These challenges
motivate AndroidArena, an environment and benchmark designed to evaluate LLM
agents on a modern operating system. To address high-cost of manpower, we
design a scalable and semi-automated method to construct the benchmark. In the
task evaluation, AndroidArena incorporates accurate and adaptive metrics to
address the issue of non-unique solutions. Our findings reveal that even
state-of-the-art LLM agents struggle in cross-APP scenarios and adhering to
specific constraints. Additionally, we identify a lack of four key
capabilities, i.e., understanding, reasoning, exploration, and reflection, as
primary reasons for the failure of LLM agents. Furthermore, we provide
empirical analysis on the failure of reflection, and improve the success rate
by 27% with our proposed exploration strategy. This work is the first to
present valuable insights in understanding fine-grained weakness of LLM agents,
and offers a path forward for future research in this area. Environment,
benchmark, and evaluation code for AndroidArena are released at
https://github.com/AndroidArenaAgent/AndroidArena.
文中引用: xing2024understandingweaknesslargelanguage

  - [10.3 Domain Surveys & Future Vision](#103-domain-surveys--future-vision)


标题:       Agents in Software Engineering: Survey, Landscape, and Vision
作者:       Yanlin Wang, Wanjun Zhong, Yanxian Huang, Ensheng Shi, Min Yang, Jiachi Chen, Hui Li, Yuchi Ma, Qianxiang Wang, Zibin Zheng
发布时间:   2024-09-13
链接:       http://arxiv.org/abs/2409.09030v2
摘要:       In recent years, Large Language Models (LLMs) have achieved remarkable
success and have been widely used in various downstream tasks, especially in
the tasks of the software engineering (SE) field. We find that many studies
combining LLMs with SE have employed the concept of agents either explicitly or
implicitly. However, there is a lack of an in-depth survey to sort out the
development context of existing works, analyze how existing works combine the
LLM-based agent technologies to optimize various tasks, and clarify the
framework of LLM-based agents in SE. In this paper, we conduct the first survey
of the studies on combining LLM-based agents with SE and present a framework of
LLM-based agents in SE which includes three key modules: perception, memory,
and action. We also summarize the current challenges in combining the two
fields and propose future opportunities in response to existing challenges. We
maintain a GitHub repository of the related papers at:
https://github.com/DeepSoftwareAnalytics/Awesome-Agent4SE.
文中引用: wang2024agentssoftwareengineeringsurvey

标题:       Large Language Model-Based Agents for Software Engineering: A Survey
作者:       Junwei Liu, Kaixin Wang, Yixuan Chen, Xin Peng, Zhenpeng Chen, Lingming Zhang, Yiling Lou
发布时间:   2024-09-04
链接:       http://arxiv.org/abs/2409.02977v1
摘要:       The recent advance in Large Language Models (LLMs) has shaped a new paradigm
of AI agents, i.e., LLM-based agents. Compared to standalone LLMs, LLM-based
agents substantially extend the versatility and expertise of LLMs by enhancing
LLMs with the capabilities of perceiving and utilizing external resources and
tools. To date, LLM-based agents have been applied and shown remarkable
effectiveness in Software Engineering (SE). The synergy between multiple agents
and human interaction brings further promise in tackling complex real-world SE
problems. In this work, we present a comprehensive and systematic survey on
LLM-based agents for SE. We collect 106 papers and categorize them from two
perspectives, i.e., the SE and agent perspectives. In addition, we discuss open
challenges and future directions in this critical domain. The repository of
this survey is at https://github.com/FudanSELab/Agent4SE-Paper-List.
文中引用: liu2024largelanguagemodelbasedagents


标题:       From LLMs to LLM-based Agents for Software Engineering: A Survey of
  Current, Challenges and Future
作者:       Haolin Jin, Linghan Huang, Haipeng Cai, Jun Yan, Bo Li, Huaming Chen
发布时间:   2024-08-05
链接:       http://arxiv.org/abs/2408.02479v2
摘要:       With the rise of large language models (LLMs), researchers are increasingly
exploring their applications in var ious vertical domains, such as software
engineering. LLMs have achieved remarkable success in areas including code
generation and vulnerability detection. However, they also exhibit numerous
limitations and shortcomings. LLM-based agents, a novel tech nology with the
potential for Artificial General Intelligence (AGI), combine LLMs as the core
for decision-making and action-taking, addressing some of the inherent
limitations of LLMs such as lack of autonomy and self-improvement. Despite
numerous studies and surveys exploring the possibility of using LLMs in
software engineering, it lacks a clear distinction between LLMs and LLM based
agents. It is still in its early stage for a unified standard and benchmarking
to qualify an LLM solution as an LLM-based agent in its domain. In this survey,
we broadly investigate the current practice and solutions for LLMs and
LLM-based agents for software engineering. In particular we summarise six key
topics: requirement engineering, code generation, autonomous decision-making,
software design, test generation, and software maintenance. We review and
differentiate the work of LLMs and LLM-based agents from these six topics,
examining their differences and similarities in tasks, benchmarks, and
evaluation metrics. Finally, we discuss the models and benchmarks used,
providing a comprehensive analysis of their applications and effectiveness in
software engineering. We anticipate this work will shed some lights on pushing
the boundaries of LLM-based agents in software engineering for future research.
文中引用: jin2025llmsllmbasedagentssoftware

标题:       LLM-Based Multi-Agent Systems for Software Engineering: Literature
  Review, Vision and the Road Ahead
作者:       Junda He, Christoph Treude, David Lo
发布时间:   2024-04-07
链接:       http://arxiv.org/abs/2404.04834v3
摘要:       Integrating Large Language Models (LLMs) into autonomous agents marks a
significant shift in the research landscape by offering cognitive abilities
that are competitive with human planning and reasoning. This paper explores the
transformative potential of integrating Large Language Models into Multi-Agent
(LMA) systems for addressing complex challenges in software engineering (SE).
By leveraging the collaborative and specialized abilities of multiple agents,
LMA systems enable autonomous problem-solving, improve robustness, and provide
scalable solutions for managing the complexity of real-world software projects.
In this paper, we conduct a systematic review of recent primary studies to map
the current landscape of LMA applications across various stages of the software
development lifecycle (SDLC). To illustrate current capabilities and
limitations, we perform two case studies to demonstrate the effectiveness of
state-of-the-art LMA frameworks. Additionally, we identify critical research
gaps and propose a comprehensive research agenda focused on enhancing
individual agent capabilities and optimizing agent synergy. Our work outlines a
forward-looking vision for developing fully autonomous, scalable, and
trustworthy LMA systems, laying the foundation for the evolution of Software
Engineering 2.0.
文中引用: he2024llmbasedmultiagentsystemssoftware

标题:       Personal LLM Agents: Insights and Survey about the Capability,
  Efficiency and Security
作者:       Yuanchun Li, Hao Wen, Weijun Wang, Xiangyu Li, Yizhen Yuan, Guohong Liu, Jiacheng Liu, Wenxing Xu, Xiang Wang, Yi Sun, Rui Kong, Yile Wang, Hanfei Geng, Jian Luan, Xuefeng Jin, Zilong Ye, Guanjing Xiong, Fan Zhang, Xiang Li, Mengwei Xu, Zhijun Li, Peng Li, Yang Liu, Ya-Qin Zhang, Yunxin Liu
发布时间:   2024-01-10
链接:       http://arxiv.org/abs/2401.05459v2
摘要:       Since the advent of personal computing devices, intelligent personal
assistants (IPAs) have been one of the key technologies that researchers and
engineers have focused on, aiming to help users efficiently obtain information
and execute tasks, and provide users with more intelligent, convenient, and
rich interaction experiences. With the development of smartphones and IoT,
computing and sensing devices have become ubiquitous, greatly expanding the
boundaries of IPAs. However, due to the lack of capabilities such as user
intent understanding, task planning, tool using, and personal data management
etc., existing IPAs still have limited practicality and scalability. Recently,
the emergence of foundation models, represented by large language models
(LLMs), brings new opportunities for the development of IPAs. With the powerful
semantic understanding and reasoning capabilities, LLM can enable intelligent
agents to solve complex problems autonomously. In this paper, we focus on
Personal LLM Agents, which are LLM-based agents that are deeply integrated with
personal data and personal devices and used for personal assistance. We
envision that Personal LLM Agents will become a major software paradigm for
end-users in the upcoming era. To realize this vision, we take the first step
to discuss several important questions about Personal LLM Agents, including
their architecture, capability, efficiency and security. We start by
summarizing the key components and design choices in the architecture of
Personal LLM Agents, followed by an in-depth analysis of the opinions collected
from domain experts. Next, we discuss several key challenges to achieve
intelligent, efficient and secure Personal LLM Agents, followed by a
comprehensive survey of representative solutions to address these challenges.
文中引用: li2024personalllmagentsinsights

标题:       Autonomous Agents in Software Development: A Vision Paper
作者:       Zeeshan Rasheed, Muhammad Waseem, Kai-Kristian Kemell, Wang Xiaofeng, Anh Nguyen Duc, Kari Systä, Pekka Abrahamsson
发布时间:   2023-11-30
链接:       http://arxiv.org/abs/2311.18440v1
摘要:       Large Language Models (LLM) and Generative Pre-trained Transformers (GPT),
are reshaping the field of Software Engineering (SE). They enable innovative
methods for executing many software engineering tasks, including automated code
generation, debugging, maintenance, etc. However, only a limited number of
existing works have thoroughly explored the potential of GPT agents in SE. This
vision paper inquires about the role of GPT-based agents in SE. Our vision is
to leverage the capabilities of multiple GPT agents to contribute to SE tasks
and to propose an initial road map for future work. We argue that multiple GPT
agents can perform creative and demanding tasks far beyond coding and
debugging. GPT agents can also do project planning, requirements engineering,
and software design. These can be done through high-level descriptions given by
the human developer. We have shown in our initial experimental analysis for
simple software (e.g., Snake Game, Tic-Tac-Toe, Notepad) that multiple GPT
agents can produce high-quality code and document it carefully. We argue that
it shows a promise of unforeseen efficiency and will dramatically reduce
lead-times. To this end, we intend to expand our efforts to understand how we
can scale these autonomous capabilities further.
文中引用: rasheed2023autonomousagentssoftwaredevelopment
