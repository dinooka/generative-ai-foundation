# Topic 3B: Types of Prompts

**Chapter 3: Advanced Prompt Refinement**

**Learning Objective:** Given an initial prompt and its output, evaluate how the prompt can be improved to elicit more targeted output.

*Topic 3B: Advanced Prompting*

In many ways, prompting is like building a pizza. Everyone has their preferences. Some like pepperoni and mushrooms, others like ham and pineapple, and sometimes preferences change depending on the setting. A plain cheese pizza might suit a relaxing Friday night, but something bolder could feel right on vacation. Clear communication ensures that the pizza order meets expectations. Similarly, clear prompts guide AI models in producing better outputs. This topic explores refining prompts by adding "toppings" like examples, glossaries, and templates.

---

## ⭐ Learning Objectives

**3.3** Recognize common prompting techniques.

- i. Zero-shot, few-shot, chain-of-thought, self-consistency, generate knowledge, prompt chaining.

## The Art and Science Behind Advanced Prompting

Prompt engineering sits at the intersection of structure and intuition. The science comes from understanding how a model processes tokens, follows constraints, retrieves patterns, and reasons through sequences. The art emerges in the deliberate choices that guide its behavior, such as its narrative frame, the evidence a user supplies, the scaffolding of examples, and the way each instruction shapes the next step. These two sides shift together every time a model gains new capabilities, new reasoning capacities, or a larger context window. It is also why a technique that worked smoothly six months ago might behave differently after a system update adjusts how the model weighs constraints or interprets demonstrations.

Generative AI benefits the most from prompting strategies that sharpen reasoning and reduce guesswork, as the coming sections will demonstrate. These techniques appear throughout high-level generative work, such as analysis, writing, classification, translation, planning, and summarization, and they anchor the most reliable paths to targeted outputs.

---

## Zero-Shot Prompting

Zero-shot prompting challenges AI to generate content without providing examples or prior context. It is like building a sandcastle from scratch with no blueprint. The AI relies on its general training data, just as someone might rely on memories of sandcastles seen at the beach.

This prompt type allows the AI model to generate creative ideas and explore paths the user might not have considered. However, the lack of specificity can lead to inconsistencies with quality, which requires extra refinement and follow-up prompts.

### Practical Examples of Zero-Shot Prompting

- **Descriptions:** "Describe a futuristic city with flying cars."
- **Brainstorming:** "List five science fair project ideas."
- **Alternatives:** "What if humans could communicate with animals?"

---

## Few-Shot Prompting

Few-shot prompting offers an AI context and reference points before producing its output. Think of it as pointing to a picture of pizza on the menu for a chef to replicate.

AI models use examples to recognize style, structure, and tone patterns and predict the best output. In theory, this process results in faster, more accurate outputs and reduces trial and error.

The best way to approach few-shot prompting is to provide just enough examples directly related to the task without overwhelming the model or giving it extraneous information.

### Practical Examples of Few-Shot Prompting

**Example:**

- **Without Few-Shot:** "Write a news article about a new coffee shop opening."
- **With Few-Shot:** "Here are some examples of positive community news reports. Now, write a news article about a new coffee shop opening."

---

## Chain-of-Thought Prompting

Chain-of-thought prompting guides the AI through a step-by-step logical reasoning process similar to how humans form a thought. This prompting technique is most helpful with complex tasks that require critical thinking or problem-solving, and the user does not want the model to rush to an answer.

### Practical Examples of Chain-of-Thought Prompting

**Math Problems:**

- **Example:** "Solve the equation 3x + 5 = 20. First, isolate x. Then, show the steps to solve for x and provide the final answer."
- **AI Output:**
  - Subtract to Isolate x: 3x = 20 - 5
  - Simplify the Right: 3x = 15
  - Divide: x = 15/3
  - Simplify: x = 5

**Historical Events:**

- **Example:** "Explain the causes of the American Revolution. Start with the political, economic, and social reasons, and then describe how each factor contributed to the decision to declare independence."
- **AI Output:**
  - Political Reason: "Colonists felt unfairly taxed without representation."
  - Economic Reason: "British trade restrictions hurt colonial businesses."
  - Social Reason: "Desire for self-governance grew among the colonies."
  - Summary: "These factors combined led to the American Revolution."

**Creative Writing:**

- **Example:** "Write a short story about a detective solving a mystery. First, describe the setting. Then, introduce the detective and the mystery. Finally, explain how the detective uncovers the truth step-by-step."
- **AI Output:**
  - Setting: "A foggy London street."
  - Detective Introduction: "Meet Detective Miller, a clever investigator."
  - Mystery: "A priceless painting has vanished from the museum."
  - Solution: "Detective Miller follows a trail of clues leading to the thief."
  - Note: The solution step here technically explains how the detective uncovers the truth, but it appears to be missing information. This is a great example of an output that may need a new follow-up prompt.

---

## Consistency

A model is consistent when it maintains the same style, facts, and tone throughout a conversation. Sometimes, models need to be prompted to do so.

This looks like the following:

### Practical Examples of Consistency in AI Tasks

**Storytelling**

- **Prompt:** "Continue the story about Sam building a sandcastle. Keep the same character names and setting."

**Academic Writing**

- **Prompt:** "Explain the life cycle of a butterfly and keep all scientific terms consistent throughout."

**Customer Service Chatbots**

- **Prompt:** "Maintain consistent store hours throughout the conversation."

Self-consistency improves the user experience and makes the AI-generated content appear more reliable and trustworthy.

---

## Generated Knowledge Prompting

Generated knowledge prompting guides an AI model to gather relevant facts or background information before completing a task, hoping it will build context and logical consistency on its own.

### Examples of Generated Knowledge Prompting

**Example:**

- **Without Generated Knowledge:** "Summarize the impact of social media on teenagers."
- **With Generated Knowledge:**
  - Step 1: "Gather relevant facts about social media usage among teenagers, including statistics and psychological impacts."
  - Step 2: "Summarize the impact of social media on teenagers using the gathered information."

---

## Prompt Chaining

Prompt chaining breaks down complex tasks into a series of connected prompts to reduce the chance of errors or misinterpretations.

In practice, this looks like the following:

### Examples of Prompt Chaining in Real-Life Applications

**Storytelling**

- Prompt 1: "Describe a young explorer entering a pyramid."
- Prompt 2: "Present a choice. Continue down the dark corridor or climb the hidden staircase."
- Prompt 3: "Based on the choice, narrate the next part of the adventure."

**Customer Service**

- Prompt 1: "Ask the user for their order number."
- Prompt 2: "Check the order status."
- Prompt 3: "If delayed, offer a resolution such as a refund or expedited shipping."

**Virtual Assistance**

- Prompt 1: "Ask the user for their preferred travel destination."
- Prompt 2: "Suggest three activities in that location."
- Prompt 3: "Ask if they need hotel or restaurant recommendations."

A key indicator of this type of prompting usually includes conditional language like "If…then…" which guides a model's decision-making.

---

## Glossaries, Templates, Reference Materials, and Memory

Creating the perfect prompt sometimes requires more than examples or detailed instructions.

Glossaries, templates, reference materials, and AI memory are all relevant to interacting with modern generative AI models.

## ⭐ Learning Objectives

**3.2** Given an initial prompt and its output, identify additional inputs you can use to elicit more targeted output.

- i. Examples
- ii. Glossary for translation.
- iii. Templates.
- iv. Documents to use for research.
- v. Earlier conversation in the same thread.

---

## Glossaries

Imagine learning a new subject, like astrophysics, without knowing the terms for stars, planets, or black holes. It would not necessarily be impossible, but it is more complicated than it needs to be. In the same way, some AI models struggle with domain-specific jargon or industry terms without a glossary.

A glossary is simply a list of terms with precise definitions relevant to a particular field. This document aims to eliminate any ambiguity by clearly defining terms that could have multiple meanings and create more consistent outputs.

### Practical Use of a Glossary

For example, a legal firm may include the following terms in their glossary:

- 'Confidential Information' → 'Any non-public data disclosed by the disclosing party'
- 'Breach' → 'Violation of contract terms'
- 'Indemnity' → 'Compensation for damages or losses'

Sometimes, it is also helpful to list synonyms for the most frequently used words alongside their definitions.

---

## Templates

Templates provide the most structured framework for AI outputs and may outline the expected order of sections, the tone of voice, and/or the preferred writing style. They might also define where there is still room for creativity within the predefined structure.

### Practical Use of a Template

For example, a legal firm may include the following terms in their glossary:

**Email Writing**

- **Without a Template:** "Write an email about a product recall."
- **With a Template:** "Use this template for the product recall email:
  - Subject Line: Important Safety Notice: Product Recall
  - Greeting: Dear [Customer's Name],
  - Body: We have identified a safety issue with [Product Name] and are issuing a recall…
  - Conclusion: We apologize for any inconvenience…"

Users should choose the template structure based on the audience and purpose (e.g., formal for business, conversational for blogs). They should also adjust the length and complexity according to the context of each specific task.

---

## Research Materials

AI models do not always have access to the most current or domain-specific information in their training data, especially if they lack access to the Internet. In this case, the models rely on the user to provide reference materials to help them produce more accurate outputs.

### Practical Uses of Reference Materials

For example, a legal firm may include the following terms in their glossary:

**Research Summaries**

- **Without Reference Materials:** "Summarize the causes of climate change."
- **With Reference Materials:** "Summarize the causes of climate change using this article: [Link to Scientific Journal]. Focus on human activities and natural influences."
- **Why It Works:** The reference material ensures the summary reflects accurate, up-to-date research findings.

**Historical Analysis**

- **Without Reference Materials:** "Explain the causes of World War I."
- **With Reference Materials:** "Using this history textbook excerpt, explain the causes of World War I. Focus on the political alliances and economic tensions."

To avoid overwhelming the AI, a user must select reputable sources and provide only specific excerpts or sections. Some AI tools even allow users to submit URLs and links to online resources.

---

## AI Memory

AI models do not always have access to the most current or domain-specific information in their training data, especially if they lack access to the Internet. In this case, the models rely on the user to provide reference materials to help them produce more accurate outputs.

---

## Up Next: Topic 3C – Reverse Prompting and Fact-Checking

This topic explored ways to guide AI: zero-shot, few-shot, chain-of-thought, self-consistency, generated knowledge prompting, prompt chaining, glossaries, templates, reference materials, and AI memory. These tools help users create better outputs by giving clear directions and setting expectations. Next, the course will cover reverse prompting, where users can specify what to avoid or prioritize in outputs.
