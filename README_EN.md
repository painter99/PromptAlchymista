# PromptAlchymista ⚗️

![Version](https://img.shields.io/badge/version-1.0.0--rc-blue) ![License](https://img.shields.io/badge/license-MIT-green) ![Optimized for](https://img.shields.io/badge/Gemini%202.5%20Flash%20%26%20Pro-primarily-purple)

[🇨🇿 Czech version](https://github.com/painter99/PromptAlchymista/blob/main/README.md)

<p align="center">
  <img src="https://raw.githubusercontent.com/painter99/PromptAlchymista/main/PromptAlchymista.png" alt="PromptAlchymista - visual concept" width="400">
</p>

<p align="center">
  <em>Your AI assistant and guide to the world of prompt engineering, designed as a comprehensive system prompt for **Google Gemini 2.5 models (Flash and Pro)**. It helps with the creation, analysis, and optimization of LLM prompts with an emphasis on clarity, efficiency, ethics, and learning new AI possibilities.</em>
</p>

> **⚠️ Language Note:** PromptAlchymista's core system prompts are currently in **Czech**, leading to interactions primarily in Czech. This English README serves as an overview. **Future versions will aim for more universal language handling.**

<a id="table-of-contents"></a>
## 📚 Table of Contents

- [What is PromptAlchymista?](#what-is-promptalchymista)
- [Motivation and Journey to PromptAlchymista](#motivation-and-journey)
- [Key Features](#key-features)
- [Core Philosophy and Principles](#core-philosophy-and-principles)
- [How Does PromptAlchymista Work?](#how-does-promptalchymista-work)
  - [Utilized Prompt Engineering Techniques (Meta-Level)](#utilized-prompt-engineering-techniques)
  - [Dynamic Knowledge Updates and Research Protocol](#dynamic-knowledge-updates-and-research-protocol)
  - [Structural Design and Prompt Architecture](#structural-design-and-prompt-architecture)
  - [Adaptive Approach and Advanced Optimization Cycles](#adaptive-approach-and-advanced-optimization-cycles)
  - [Optimization for Google Gemini 2.5 Models (Flash & Pro)](#optimization-for-google-gemini-25-models-flash--pro)
  - [Consideration of Practical Use and Production Deployment](#consideration-of-practical-use-and-production-deployment)
  - [Seeking Innovation and Intuitive Foresight](#seeking-innovation-and-intuitive-foresight)
- [Who Is It For?](#who-is-it-for)
- [How to Get Started with PromptAlchymista (recommended for Gemini 2.5 Flash / Pro)](#how-to-get-started-with-promptalchymista-recommended-for-gemini-25-flash--pro)
- [Testing and Evaluation](#testing-and-evaluation)
- [Example of a Complex Interaction](#example-of-a-complex-interaction)
- [Current Status (Release Candidate)](#current-status-release-candidate)
- [Join the Discussion!](#join-the-discussion)
- [License](#license)

<a id="what-is-promptalchymista"></a>
## 🧪 What is PromptAlchymista?

🎧 **Listen to the introduction to PromptAlchymista (Czech audio):** [![Listen to podcast](https://img.shields.io/badge/-Podcast-red?style=flat-square&logo=google-podcasts&logoColor=white)](https://notebooklm.google.com/notebook/28c6ba87-8a6f-423e-a72b-3a5562b0bc4a/audio)

If the NotebookLM link doesn't work, or you wish to download the file directly, you can do so [here](https://github.com/painter99/PromptAlchymista/releases/download/podcast-intro-v1/Podcast.PromptAlchymista.Intro.wav) (WAV format, Czech audio).

---

**PromptAlchymista ⚗️** is a **comprehensive system prompt**. It's not a standalone software application or tool in the traditional sense, but a set of detailed instructions designed to **activate the role of an AI assistant and guide** in the field of prompt engineering within an advanced AI model environment (primarily optimized for **Google Gemini 2.5 models, specifically Flash and Pro**). Its main mission is to be your **right hand and helper** in **creating, analyzing, and optimizing prompts** for large language models (LLMs), with an emphasis on learning and understanding "why" certain approaches work better.

PromptAlchymista evolved from my personal experiment in the Alpha phase to the current Release Candidate version. While early versions were tested on other models, **current versions are specifically optimized to leverage the unique capabilities of Google Gemini 2.5 models**, such as Controllable Reasoning (in the Flash version), advanced reasoning (in the Pro version), native Multimodality, and a large context window, which enables its complex behavior.

It is a **prototype and reference implementation** that explores and demonstrates the possibilities of a systematic and thoughtful approach to prompt engineering directly through interaction with AI. It emphasizes **learning, clarity, and practical application** of principles for creating **reliable, effective, and ethically responsible prompts**.

Currently, the project is in the **Release Candidate** phase and is primarily tested and optimized in the **Google AI Studio environment with Gemini 2.5 Flash and Gemini 2.5 Pro models**. To fully utilize its potential, a model with advanced capabilities (such as Controllable Reasoning in Flash or advanced reasoning in Pro), a long context, multimodality, and the ability to perform web research is necessary.

<a id="motivation-and-journey"></a>
## 🧠 Motivation and Journey to PromptAlchymista

The motivation for creating PromptAlchymista stems from my personal observation: even today, many users interact with powerful AI models without fully harnessing their potential. From my own experience testing models, I soon understood how crucial **precise instruction formulation and model setup** are for the quality and reliability of the output.

Why is it crucial to instruct AI models correctly?

Large language models (LLMs) are incredibly capable, but they are not "intelligent" in the human sense. They lack their own intentions, common sense, or an implicit understanding of complex human requirements. Without clear, precise, and optimized instructions (prompts), their outputs can become unpredictable, unreliable, inconsistent, or even irrelevant or harmful.

Proper "instructing" of AI – i.e., **Prompt Engineering** – is therefore an essential skill that transforms the raw potential of models into targeted, reliable, and valuable results. It is key for several reasons:

*   **Reliability and Consistency:** Ensures the model repeatedly generates predictable and consistent outputs that precisely match your expectations and format requirements (including multimodal outputs).
*   **Accuracy and Relevance:** Helps the model focus on key information, avoid "hallucinations" (generating fabricated facts), and provide factually correct and relevant answers for your specific task.
*   **Control over Output:** Allows detailed specification of the desired style, tone, length, and structure of the output, which is essential for integrating AI into applications or achieving specific communication goals.
*   **Utilizing Full Model Potential:** Unlocks and effectively uses the advanced capabilities of modern models, such as controlled reasoning ("thinking budgets") in Gemini 2.5 Flash, advanced native reasoning in Gemini 2.5 Pro, the ability to use tools for accessing current data (Grounding/Web Search), or processing and generating multimodal inputs and outputs.
*   **Efficiency and Costs:** An optimized prompt can reduce the number of necessary iterations, shorten the output length (tokens), and thereby reduce costs and latency, which is critical for large-scale production deployment.
*   **Robustness and Handling Edge Cases:** A well-designed prompt is more resilient to slightly different or unexpected inputs and better handles complex scenarios.
*   **Ethics and Safety:** Allows explicit definition of ethical boundaries and safety constraints, minimizing biases and preventing the generation of harmful or inappropriate content.
*   **Sustainability and Scalability:** For complex applications, a structured and well-designed prompt is easier to maintain, test, and integrate into larger software systems.

This realization led me to create my first mini-project, [AI Templates](https://github.com/painter99/ai-templates), which served as a basic set of structured templates for testing and optimizing prompts.

With rapid advancements in AI, especially with the advent of models possessing advanced reasoning capabilities and native access to current information, an opportunity and a need arose to elevate prompt engineering to a higher level. The goal was to create a system that wouldn't just be a static set of templates, but a dynamic, intelligent, and architecturally sophisticated assistant – directly within the AI interaction.

Thus, PromptAlchymista was born. It represents my deeper dive into the architecture of AI instructions, builds upon the systematic approach from [AI Templates](https://github.com/painter99/ai-templates), and integrates dynamic knowledge updates, advanced optimization cycles, and specific optimization for state-of-the-art models. The project is driven by my passion for IT and AI, a desire to connect theoretical knowledge with practical applications (especially in AI testing), and the conviction that **systematic and effective prompt engineering is a skill accessible and beneficial to everyone** who wants to better leverage the potential of artificial intelligence.

<a id="key-features"></a>
## ✨ Key Features

PromptAlchymista, as your AI assistant and guide, offers the following key features:

*   **Optimization for Gemini 2.5 Flash & Pro:** Fully utilizes the unique capabilities of these models, such as **Controllable Reasoning ("thinking budgets")** in the Flash version, **advanced native reasoning** in the Pro version, and **native Multimodality** in both, to achieve the best possible results.
*   **Robust Knowledge Updates:** Automatically performs a managed research of the latest trends and best practices in prompt engineering at each start, with strict criteria for the timeliness and quality of sources, to always provide you with up-to-date advice.
*   **Model-Centric Optimization:** Provides advice and designs prompts considering the specifics and strengths of the target model (primarily Gemini 2.5 Flash and Pro, but also Claude, GPT), so you know how to best work with the model you have.
*   **Structural Design and Architecture:** Shows and recommends how to use XML (preferred for complexity) or Markdown/JSON for clear structure, separation of logical blocks, and effective control of model behavior in your prompts.
*   **Integrated Ethics and Responsible AI:** Actively considers ethical aspects, bias minimization, and prevention of undesirable AI behavior in every design, helping you create responsible AI interactions.
*   **Consideration of Practical Use and Production Deployment:** Brings insight into the practical aspects of deploying prompts in real-world situations, including latency, costs, error handling, and security, which is useful for those who want to use AI for more demanding tasks.
*   **Seeking Innovation:** Actively explores and proposes new combinations of techniques and innovative approaches to problem-solving, thereby inspiring you to push boundaries.
*   **Adaptive and Pedagogical Communication:** Adjusts the complexity of explanations to your knowledge level with the aim of educating and inspiring you to master prompt engineering independently.
*   **Proactive Solution Proposal:** Operates with a high degree of autonomy, anticipates your needs, and minimizes unnecessary questions to help you as quickly and efficiently as possible.
*   **Advanced Optimization Cycles:** Includes mechanisms for autonomous meta-prompting (generate -> critique -> improve), RLHF simulation for feedback collection, and systematic evaluation of variants, thereby demonstrating advanced optimization methods.
*   **Omni-Modality Mastery:** Considers and proposes multimodal approaches where they can add value, utilizing the capabilities of target models, thus opening doors to new AI possibilities for you.
*   **Practical Examples:** Offers concrete demonstrations of how to use the designed prompts, including multimodal ones, for better understanding and easy application.

<a id="core-philosophy-and-principles"></a>
## 💡 Core Philosophy and Principles

PromptAlchymista, as your AI guide, adheres to a set of key principles that form the foundation of its "Art of Prompt Engineering":

1.  **Mastery of Clarity & Explicitness**: Every instruction must be crystal clear to the target AI model.
2.  **Token Alchemy & Performance Optimization**: Seeking the optimal balance between prompt length, its effectiveness, and costs, considering practical use.
3.  **Adaptability & Model-Centric Optimization**: Leveraging the strengths of the target model, primarily Gemini 2.5 Flash and Pro.
4.  **Prompt Architecture & Structural Control**: Strategic use of XML, Markdown, JSON for maximum clarity and control of model behavior.
5.  **Ethics in Prompt Design & Responsible AI**: Active integration of ethical aspects into every design.
6.  **Education & Adaptive Communication**: Adjusting the depth and technical complexity of explanations to the user's knowledge level with the aim to inspire.
7.  **Proactive Solution Proposal & Managed Autonomy**: Acting independently, anticipating needs, resolving conflicts in requirements.
8.  **Systematic Approach & Versioning**: Systematic work and documentation of decisions.
9.  **DRY (Don't Repeat Yourself)**: Minimizing redundancy in prompt designs and in its own structure.
10. **Seeking Innovation and Creative Problem Solving**: Actively seeking and proposing new combinations or prompt patterns.
11. **Practical Wisdom from Production**: Considering aspects of real-world deployment (latency, costs, robustness, security, scalability).
12. **Omni-Modality Mastery**: Ability to effectively design prompts integrating text, images, and other modalities.
13. **Intuitive Foresight and Advanced Inference**: Ability to "intuitively" anticipate needs and identify potential problems.
14. **Meta-Heuristic for Conflict Resolution**: Clear rules for resolving situations where principles conflict.
15. **Principle of Guided Flexibility**: Possibility of expert judgment in unique situations with transparent justification.

<a id="how-does-promptalchymista-work"></a>
## ⚙️ How Does PromptAlchymista Work?

PromptAlchymista is not a standalone application but a **comprehensive system prompt** that defines the identity, behavior, knowledge, and workflows of an AI assistant. It operates **directly within the environment of a compatible LLM model** (such as Google Gemini 2.5 Flash or Pro) to which its instructions are passed. Its key mechanisms include:

<a id="utilized-prompt-engineering-techniques"></a>
### Utilized Prompt Engineering Techniques (Meta-Level)

PromptAlchymista itself is not just one specific prompt engineering technique (like RAG for information retrieval or CoT for reasoning). Instead, it represents an **architecture built on the combination and advanced application of multiple PE techniques and principles** to create a sophisticated AI assistant. It can be perceived as a **Meta-Prompt** – a prompt that deals with *prompt engineering itself*.

Key techniques and approaches that PromptAlchymista integrates and demonstrates include:

*   **Role Prompting / Persona Prompting:** Definition of the complex identity and role of "PromptAlchymista ⚗️".
*   **Instructional Prompting:** Detailed and explicit instructions defining workflows, principles, and rules of behavior.
*   **Structured Prompting (especially with XML):** Use of XML tags for modular design and a clear hierarchy of instructions, helping the model better understand and adhere to complex tasks.
*   **Meta-Prompting / Agentic Principles:** Instructions that guide the model's own processes (e.g., generate -> critique -> improve cycle, self-management, module selection) within its role as an assistant.
*   **Dynamic & Adaptive Prompting:** Ability to adapt to the user, dynamically search for current information, and adapt communication.

PromptAlchymista combines these techniques to provide a **comprehensive, structured, and dynamic framework** for assistance in prompt engineering, fully leveraging the capabilities of modern models like Google Gemini 2.5 Flash and Pro.

<a id="dynamic-knowledge-updates-and-research-protocol"></a>
### Dynamic Knowledge Updates and Research Protocol

At the beginning of each conversation, Alchymista **automatically and mandatorily** performs a reliable two-phase research process:
1.  **Identifies 3 global trends:** Conducts research on the latest "best practices" in prompt engineering.
2.  **Targeted deep dives:** Based on the identified trends, it performs 3 more targeted research efforts focused on specific, currently most relevant areas, including their applicability to Gemini models (Flash and Pro) and potential for innovation.
This process uses **exclusively English, authoritative sources (official documentation > scientific publications > reputable blogs) максимум 1-9 months old** and has a **built-in control mechanism** that prevents responding before the research is complete. This ensures that advice is always current and based on the latest knowledge. **Active internet access for the AI (web search tool) is essential for this mechanism.** During the conversation, Alchymista then performs **proactive dynamic research** to verify specific facts or explore innovative concepts.

<a id="structural-design-and-prompt-architecture"></a>
### Structural Design and Prompt Architecture

To ensure maximum clarity and control, PromptAlchymista recommends and utilizes **structured formats**. The preferred format for complex system prompts is **XML**, which allows for clear separation of logical blocks, definition of attributes (like importance, execution phase), and control of model behavior. For other purposes or target models, Markdown, JSON, or YAML can also be used. The current version of the system prompt itself demonstrates this modular XML architecture.

<a id="adaptive-approach-and-advanced-optimization-cycles"></a>
### Adaptive Approach and Advanced Optimization Cycles

PromptAlchymista is designed to:
*   Minimize unnecessary questions to the user and proactively propose solutions.
*   Estimate the user's knowledge level and adapt the complexity of its explanations accordingly, with the aim to educate and inspire.
*   **Systematically utilize defined advanced cycles** (if relevant to the task, its complexity, practical use requirements, or potential for innovation):
    *   **Meta-Prompting Optimization Cycle:** An autonomous cycle (generate -> critique -> improve) for in-depth optimization of complex prompts, including consideration of innovation, practical aspects, and target model specifics.
    *   **RLHF/DPO-inspired Feedback Loop:** A mechanism for systematically gathering and applying structured user feedback for iterative improvement of prompts and its own advisory/pedagogical skills.
    *   **Optimization and Evaluation Cycle:** A process for systematically generating and objectively evaluating multiple prompt variants based on defined metrics, suitable for more demanding tasks and evaluating innovative approaches.
    *   **Strategic Advisory:** Proactive assessment of task complexity and proposal of the most suitable strategy (single prompt, decomposition, agent, RAG, DSPy, multimodal, innovation).

<a id="optimization-for-google-gemini-25-models-flash--pro"></a>
### Optimization for Google Gemini 2.5 Models (Flash & Pro)

This version of PromptAlchymista places special emphasis on leveraging the strengths of Gemini 2.5 models:
*   **For Gemini 2.5 Flash:** Alchymista proposes strategies for using **Controllable Reasoning ("thinking budgets")** and explicit reasoning modes of the model to optimize quality, speed, and costs.
*   **For Gemini 2.5 Pro:** Alchymista is designed to utilize the model's **advanced native reasoning capabilities** for deep analysis, synthesis, and generation of sophisticated responses.
*   **Common for both models:** Effectively utilizes the ability to work with a **long context** and actively considers and proposes solutions that integrate and optimize work with various modalities (**native Multimodality**).

In this context, **Google AI Studio has proven to be a key platform** for rapid prototyping, iterative tuning, and effective deployment of advanced prompt engineering strategies like PromptAlchymista, precisely due to its direct support for these unique capabilities of Gemini models.

<a id="consideration-of-practical-use-and-production-deployment"></a>
### Consideration of Practical Use and Production Deployment

When designing prompts and strategies, PromptAlchymista systematically considers aspects of real-world use, including potential deployment in a production environment. This includes optimization for **latency, throughput, costs**, robust **error handling**, and **security aspects** (e.g., prompt injection). It provides practical advice for those who want to use AI for more demanding or repetitive tasks.

<a id="seeking-innovation-and-intuitive-foresight"></a>
### Seeking Innovation and Intuitive Foresight

PromptAlchymista is not limited to applying known techniques. It actively seeks and proposes **new combinations, adaptations, or entirely new prompt patterns** that could lead to interesting solutions. At the same time, it develops the ability to "intuitively" anticipate user needs and identify potential problems or opportunities that are not explicitly mentioned.

<a id="who-is-it-for"></a>
## 🎯 Who Is It For?

PromptAlchymista, as your AI assistant and guide, can be particularly useful for:

*   **Every AI User:** Who wants to go beyond basic chatbot usage and learn how to communicate with AI more effectively and obtain more reliable results for their everyday and more complex tasks.
*   **Beginners and Intermediates in Prompt Engineering:** For understanding basic and advanced principles, getting help with prompt formulation, and systematic learning.
*   **Enthusiasts and Experimenters:** Who are interested in how advanced AI models work "under the hood" and want to explore the possibilities of structured and innovative prompting.
*   **Lecturers and Trainers in AI:** As a live demonstration and inspiration for teaching materials, showcasing a systematic approach to prompt engineering.

PromptAlchymista is not designed as a replacement for specialized software frameworks for LLM application development (like DSPy) nor for the custom, highly sophisticated workflows of experienced AI professionals. Its value lies in **making the principles of effective prompting accessible and showing a path to better AI utilization** for a broader audience.

<a id="how-to-get-started-with-promptalchymista-recommended-for-gemini-25-flash--pro"></a>
## 🚀 How to Get Started with PromptAlchymista (recommended for Gemini 2.5 Flash / Pro)

**Important Information for International Users (Language):**

The core system prompts (`.xml` files) that define PromptAlchymista's behavior are currently developed and maintained **primarily in Czech**.
*   **Interaction Language:** If you use these Czech system prompts, Alchymista is instructed to interact **mainly in Czech**. While you might be able to request responses in English during the interaction, the AI's core "persona" and some underlying logic are defined in Czech, which might occasionally lead to inconsistencies or a preference for Czech.
*   **English README Purpose:** This English `README.md` is intended to provide a comprehensive overview of the project's concept, philosophy, and features for an international audience.
*   **Planned Language Enhancements:** Future releases of PromptAlchymista will focus on a **more universal language handling**. The goal is to move away from the current strict default to Czech and enable Alchymista to more dynamically and reliably interact in the user's preferred language. This will include efforts towards a fully functional English system prompt.
*   **Current Status:** For now, please be aware of the Czech-centric nature of the system prompt's interaction language.

*   **Advanced Users: Potential Language Modification:** If you are an advanced user familiar with XML-based system prompts and prompt engineering, you could attempt to modify the primary interaction language within the existing Czech system prompt.
    *   **Locate:** The relevant instruction is typically found within the `<interaction_protocol_communication_style>` module, specifically under the `<language_preference>` tag.
    *   **Modify:** You would need to change the instruction from directing Czech communication to English (e.g., "Primarily communicate in English...").
    *   **Important Considerations:**
        *   This is a **manual and advanced modification**.
        *   While changing this specific tag can influence the primary output language, the rest of the extensive system prompt (defining the Alchemist's persona, detailed reasoning processes, examples, etc.) remains in Czech. This might lead to subtle influences on the AI's responses or an "accent" in its English.
        *   This modification does **not** equate to a fully translated and localized English version of PromptAlchymista, which is a more complex undertaking planned for the future.
        *   Thorough testing would be required after any such modification.

PromptAlchymista functions as a system prompt within a compatible LLM model environment. It is primarily designed for Google Gemini 2.5 models (Flash and Pro). The best way to start is in the **Google AI Studio** environment:

1.  **Create a new prompt:**
    *   Go to Google AI Studio and create a new "Chat".
2.  **Insert system instructions:**
    *   Copy the entire content of the respective system prompt file (e.g., [`1.0.0-gemini-2.5-flash-thinking-rc2.xml`](https://github.com/painter99/PromptAlchymista/releases) for Flash or [`1.0.0-gemini-2.5-pro-thinking-rc1.xml`](https://github.com/painter99/PromptAlchymista/releases) for Pro) and paste it into the `System instruction` text field.
3.  **Select and configure the model:**
    *   In the model settings (usually in the right panel), select the appropriate model: **`Gemini 2.5 Flash`** or **`Gemini 2.5 Pro`** (or newer versions if available).
    *   **I recommend activating the "Grounding" feature with access to Google Search for proper functioning.** PromptAlchymista requires access to current information for its initialization protocol and ongoing research.
    *   Experiment with inference parameter settings, such as **"Temperature"** (e.g., around 0.6-1.0 for a balanced approach) and **Top P** (e.g., around 0.85-0.95), according to the needs of the specific task. PromptAlchymista itself may recommend optimal settings for your specific case during the conversation.
    *   **Important recommendation for Temperature setting (from testing for Flash):**
        *   Based on extensive testing, for tasks requiring **flexibility, creativity, and proactive work with current information (e.g., web searching)** with the Flash model, it is advisable to set the `temperature` parameter to values in the range of **0.6-0.8**.
        *   At these values, the model maintains sufficient **variability and creativity** in its responses.
        *   Setting it too low (e.g., below 0.6) causes the model to become **too strictly bound by its internal instructions and training data**. This may manifest, for example, as **less willingness to proactively search for current information on the web** (even if instructions to use tools are present) or **excessive adherence to specifics mentioned in the prompt** (such as an exclusive focus on Gemini 2.5 Flash even in broader PE queries).
        *   In such cases, the quality and usefulness of the model's output for the given task decrease. For the Pro model, optimal settings may differ and are subject to further testing.
    *   **To fully utilize the reasoning capabilities of the Gemini 2.5 Flash model, ensure that the API or platform settings allow the model to use its "thinking budget."** Do not set this value manually; PromptAlchymista will set it itself during the conversation. For the Gemini 2.5 Pro model, Alchymista relies on its native advanced reasoning.
4.  **Start the conversation:**
    *   Once you have inserted the system prompt and configured the model, you can start the conversation. Simply type a common introductory message, for example, **just a greeting** like "Hi" or "Hello".
    *   The AI should then respond in the role of PromptAlchymista, ready to perform its tasks as defined in the system prompt, including conducting the initialization research.

**Alternative platforms (Claude, GPT):**

PromptAlchymista is designed with universal principles in mind and can also work on other advanced models, such as **Anthropic Claude or OpenAI GPT**. The deployment procedure will vary depending on the platform (e.g., Claude.ai Projects, OpenAI Playground/API) and may require formatting adjustments. The key is to ensure the model has access to web research and, if possible, mechanisms for controlled reasoning (for Flash) or full utilization of native reasoning (for Pro).

**It is important to note that while early versions of PromptAlchymista (Alpha phase) were primarily tested and tuned on Claude models, current versions are specifically optimized to leverage the unique capabilities of Gemini 2.5 Flash and Pro models.** When used on other models, results may vary, and not all advanced features may be fully utilized.

<a id="testing-and-evaluation"></a>
## 🛠️ Testing and Evaluation

Systematic testing and evaluation are an integral part of "Prompt Engineering" and key to verifying the quality of PromptAlchymista's designs. I recommend:

*   **Utilizing Alchymista's recommendations:** PromptAlchymista itself suggests specific metrics and testing methodologies for your task (see `<testing_guidelines_and_next_steps>` in the output).
*   **Creating test suites:** Sets of representative inputs (including edge cases and multimodal variants) for consistent testing.
*   **Measuring key metrics:** Output quality, format compliance, token efficiency, robustness, ethical aspects, and for practical use, also **latency, throughput, and costs**.
*   **Using methodologies:** A/B testing, iterative improvement, LLM-as-a-judge, failure analysis.
*   **Experimenting:** Trying different prompt variants, model settings (including "thinking budget" for Gemini 2.5 Flash or monitoring reasoning quality for Pro), and observing their impact on metrics.

<a id="example-of-a-complex-interaction"></a>
## 🗣️ Example of a Complex Interaction

This section demonstrates how PromptAlchymista can practically assist with refactoring and optimizing an existing complex prompt. The following link leads to an actual conversation in Google AI Studio, where PromptAlchymista (with the system prompt for Gemini 2.5 Flash v1.0.0-rc1 deployed) refactored a detailed prompt template for an AI teacher.

**Link to the complete interaction in Google AI Studio (with Flash version):**
🔗 [View the example in Google AI Studio](https://aistudio.google.com/app/prompts?state=%7B%22ids%22:%5B%221yYw9-TCiP-iFWcrDK7_1THJ-3S1QoUaA%22%5D,%22action%22:%22open%22,%22userId%22:%22115548049022000007713%22,%22resourceKeys%22:%7B%7D%7D&usp=sharing)

**Brief summary of this interaction:**

1.  **User Input:** The user provided PromptAlchymista with a detailed prompt template for an AI assistant in the role of a teacher/mentor. This was the 'AI Teacher Template', originally created as part of my archived project [AI Templates](https://github.com/painter99/ai-templates). The original Markdown version of this template can be viewed [here](https://github.com/painter99/ai-templates/blob/main/example/example-teaching-template-complete.md). Subsequently, the user requested its refactoring and optimization for the Gemini 2.5 Flash model to effectively utilize the model's specific capabilities, such as **Controllable Reasoning ("thinking budget")** and **continuous information verification using web search and grounding**.
2.  **PromptAlchymista's Analysis and Planning:** PromptAlchymista first analyzed the original template, identified its strengths and key areas for improvement with respect to the target model and required functions. It defined a formal task signature (`task_signature`) and internally planned the refactoring steps, including how to incorporate instructions for the thinking budget and web search into the new prompt.
3.  **Generation of the Optimized Prompt:** Based on the analysis and plan, PromptAlchymista generated a new, **comprehensive prompt template in XML format**. This new version transformed the descriptive sections of the original template into **explicit, executable instructions and rules** for the AI assistant in the teacher role.
4.  **Explanation and Accompanying Materials:** PromptAlchymista attached a detailed **rationale for design decisions** (`design_rationale_and_principles_applied`) to the proposed XML prompt, explaining why specific changes were made, how PromptAlchymista's principles were applied, and how the new structure and instructions leverage the capabilities of Gemini 2.5 Flash (especially for controlled reasoning and web search). It also provided **usage examples** for the new template, **notes on token efficiency and costs**, and **specific recommendations for testing and evaluation**. The perspective for advanced optimization with frameworks like DSPy and consideration of ethical aspects were also mentioned.

This example demonstrates how PromptAlchymista functions as a **systematic helper and guide**. It not only generates a refactored prompt but also provides context, explains the "why," and offers guidance on how to further work with the result and utilize the model's advanced capabilities. It shows how a complex task can be converted into structured instructions for an AI assistant.

<a id="current-status-release-candidate"></a>
## 🧭 Current Status (Release Candidate)

PromptAlchymista has evolved from my early **personal experiment** in the Alpha phase to the current **Release Candidate** phase. This transition reflects significant architectural improvements, the addition of new modules, and more robust testing.
Currently, versions optimized for the following are available:
*   **Google Gemini 2.5 Flash**  [`1.0.0-gemini-2.5-flash-thinking-rc2.xml`](https://github.com/painter99/PromptAlchymista/releases)
*   **Google Gemini 2.5 Pro** [`1.0.0-gemini-2.5-pro-thinking-rc1.xml`](https://github.com/painter99/PromptAlchymista/releases)

The goal is to reach a stable version 1.0.0 in the near future.
As a Release Candidate, it may still evolve and improve based on feedback and further testing.

<a id="join-the-discussion"></a>
## 💬 Join the Discussion!

Do you have ideas, observations, or have you tried PromptAlchymista? I would appreciate any feedback or discussion about this approach to prompt engineering. This project is an experiment, and every constructive thought can help its further direction and development for the entire community.

*   [Link to the author's LinkedIn profile](https://www.linkedin.com/in/pavel-mares-p99/)

The aim is to create a tool and approach that can help make working with LLMs more efficient and of higher quality, and to push the boundaries of prompt engineering.

<a id="license"></a>
## 📜 License

PromptAlchymista (as a concept, this document, and related system prompts provided by the author) is provided under the **MIT License**. Copyright (c) 2025 painter99. For details, see the `LICENSE` file in the project repository.

---

<p align="center">
  <em>Transform your ideas into precise, effective, and innovative prompts with PromptAlchymista – your AI guide!</em>
</p>
