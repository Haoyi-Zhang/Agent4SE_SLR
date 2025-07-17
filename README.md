

cture & Tool Support](#1-agent-system-architecture--tool-support)-----------------------------------------------------------------------------------------------------------C1
  - [1.1 Patterned & Modular Architectures](#11-patterned--modular-architectures)---------------------------------------------------------------------------------------------------------------------C1.1

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
- [4. Testing & Quality Assurance](#4-testing--quality-assurance) ------------------------------------------------------------------------------------------------------------------------------------C4
  - [4.1 Automated Test Case Generation](#41-automated-test-case-generation)--------------------------------------------------------------------------------------------------------------------------C4.1
  - [4.2 Conversational / Autonomous Testing Agents](#42-conversational--autonomous-testing-agents) --------------------------------------------------------------------------------------------------C4.2
  - 
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
- [5. Debugging, Fault Localization & Automated Repair](#5-debugging-fault-localization--automated-repair)--------------------------------------------------------------------------------------------C5
  - [5.1 Defect Detection](#51-defect-detection)
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
  - [6.3 Dependency Management Agents](#63-dependency-management-agents)
- [7. Deployment, Operations & Monitoring](#7-deployment-operations--monitoring)----------------------------------------------------------------------------------------------------------------------C7
  - [7.1 Root Cause Analysis (RCA) Agents](#71-root-cause-analysis-rca-agents)

 
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
  - [7.3 Issue / Incident Resolution Agents](#73-issue--incident-resolution-agents)

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
 
  - 
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
