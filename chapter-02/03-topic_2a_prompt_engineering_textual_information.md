# Topic 2A: Prompt Engineering for Textual Information

**Chapter 2: Basic Prompt Engineering**

**Learning Objective:** Develop and apply prompts to elicit, summarize, generate, adapt, and transform textual information across diverse goals, including research, ideation, simplification, editing, translation, and audience-specific communication.

Ask ten people to make a peanut butter and jelly sandwich, and watch ten wildly different processes unfold. One person spreads peanut butter on both slices for "maximum adhesion." Another adds jelly first "to prevent the bread from tearing." A third stacks everything on one slice and folds it in half. This is where prompt engineering begins: learning how to guide a process by refining the instructions.

A vague prompt like "write about sandwiches" may result in a history lesson, a recipe, or a philosophical debate, even if a model is perfectly aligned for the task at hand. Conversely, a specific prompt, such as "write a humorous haiku about someone making a peanut butter and jelly sandwich while late for school," yields something far more exact. This lesson explores the logic behind content gathering, summarization, and idea generation through the lens of thoughtful prompting.

---

## Prompt Syntax

Before an AI model can gather facts, tell stories, or summarize research, it needs a clear prompt to follow. Think of prompt writing as managing a team member who learns quickly but does not always read between the lines. Like a helpful coworker, the AI model does not need complex code or commands. It reads everyday language and responds based on what it recognizes from its training.

Even if a prompt contains spelling or grammar mistakes, the model is often able to parse what the user meant because its training process included messy, unstructured data in preparation for such situations. Of course, consistent structure and cleaner inputs improve accuracy. Using complete sentences, specific details, and consistent formatting gives the model a more stable pattern to follow, just like giving a family member an exact recipe to follow with all the correct ingredients, measurements, and step-by-step directions.

In many ways, writing a prompt is like the famous children's story of Goldilocks and the Three Bears. Prompts that are too short leave too much room for misinterpretation, while prompts that are too long risk becoming noisy or confusing. A user wants to aim for "just right" by providing exactly enough context and information for the AI to complete the job.

Consider the prompt "Tell me about the moon." In order for an AI model to continue providing quick responses to users, it needs to pick the most obvious combination of words for the output. Unless specifically prompted to ask follow-up questions, the model will return a quick text blurb that might be overly technical, poetic, or completely off the mark. A prompt that reads, "Explain in five complete sentences how the moon affects ocean tides, using scientific vocabulary appropriate for high school students," narrows the outcome and keeps the task focused.

Prompt length should reflect the task:

- **Shorter prompts** often work best for quick answers, basic facts, or casual brainstorming.
- **Longer prompts** help guide structured responses, formal writing, or step-by-step outputs.
- **Moderate prompts** are ideal when exploring new ideas without overwhelming detail.

The art of prompt syntax is about clarity. The best prompts set the tone, identify the task, and leave just enough room for creativity. Once the structure is in place, the AI can do what it was meant to do.

---

## Visualizing Tokenization

Chapter One briefly touched on tokenization, but this section offers a visualization and a deeper understanding of it in practice.

Imagine the sentence: "I like drinking chocolate milk with my lunch."

Humans see eight words that form one complete thought. AI models, however, do not see the sentence quite the same way. They break it into tokens, which can look like this:

`I / like / drink / ing / choc / o / late / mi / lk / with / my / lu / nch`

Or sometimes, like this:

`I / li / ke / dri / nk / I / ng / choc / olate / milk / wit / h / my / lun / ch`

To the human eye, these tokens look like a jumbled mess. To an AI model, they are puzzle pieces that fit together to make a coherent sentence. The model does not understand the words the way humans do. It does not taste or imagine the smell of chocolate milk. Instead, it recognizes patterns among tokens and predicts which ones will likely come next based on the patterns it learned from its training data.

This pattern recognition allows AI models to generate text that sounds human-like, even though they do not truly understand the meaning behind the words. Tokenization is the foundation for how AI models produce creative and coherent content, setting the stage for more advanced behaviors.

---

## ⭐ Learning Objectives

**2.1** Identify appropriate prompts to elicit textual information.

- i. Content gathering.

## Content Gathering

Users can interact with AI models in many ways, depending on their project's goals. Content gathering is one of dozens of options, and it involves prompting an AI model to find specific information, such as facts, statistics, or detailed explanations.

### Types of Content Gathering Prompts

- **Fact-Finding Prompts:** These prompts help gather specific facts about a topic.
  - Example: "What are three facts about the Great Wall of China?"
  - Example: "What do you know about the country of Estonia?"
- **Statistical Prompts:** These prompts focus on gathering numbers or statistics.
  - Example: "How many people live in New York City according to the 2015 census?"
  - Example: "How deep is Lake Superior?"
- **Comparison Prompts:** These prompts ask the AI to compare or contrast two or more things.
  - Example: "Compare the climates of deserts and rainforests."
  - Example: "How is Nebraska's agriculture different than Minnesota's?"
- **Cause-and-effect Prompts:** These prompts ask for explanations of why something happens or how something impacts another thing.
  - Example: "What are the effects of pollution on marine life?"
  - Example: "Why do flights commonly get delayed?"
- **Exploratory Prompts:** These prompts ask the AI to provide in-depth information on a broad topic.
  - Example: "Explain the history of space exploration."
  - Example: "Tell me more about Shakespeare."
- **Multi-Step Prompts:** These prompts break down complex tasks into simpler steps.
  - Example: "First, list the steps of the water cycle. Then, explain each step with an example that a kindergartener would understand."
  - Example: "I need to choose a debate topic for my 6th grade speech class. Then, I need to outline my paper with a clear thesis, beginning, middle, and end."

Content gathering showcases how AI can organize information and generate meaningful outputs to conduct better research and learning or improve the creative process by providing reliable and relevant content as a reference point.

---

## Creating Better Prompts

LLMs like ChatGPT access an enormous pool of knowledge that now includes the entire Internet and history of humanity. Every prompt requires instantaneously determining the context and patterns most relevant to the question or task.

However, LLMs are probabilistic and stochastic, so they operate on patterns and probabilities rather than fixed rules. This built-in randomness can lead to surprising and sometimes nonsensical outputs, which previous lessons defined as "hallucinations." Though occasionally inaccurate, these hallucinations show that the AI is experimenting with new connections. Each new prompt can introduce even more novelty, which can, in turn, produce sharper or more obscure outputs.

Some general prompting tips for more helpful answers include:

- **Be Specific:** Clear questions lead to clearer answers.
  - Original Prompt: "I like dogs. Tell me some facts about them."
  - Better Prompt: "What are three things that make bulldogs unique from boxers?"
- **Provide Context:** General inputs yield general outputs, but specific context produces more relevant answers.
  - Original Prompt: "Explain climate change."
  - Better Prompt: "Explain how carbon emissions affect the Amazon rainforest at a sixth-grade level."
- **Break Down Complex Questions:** Asking multiple, smaller questions keeps the AI on track.
  - Original Prompt: "Describe the human body."
  - Better Prompt: "What are the major systems in the human body?" and "What does the integumentary system do?"
- **Add Constraints:** Setting boundaries is another way to direct the AI's focus.
  - Original Prompt: "Write a poem about cats."
  - Better Prompt: "Write a haiku about a cat watching the rain. Only use words that start with the letter L."
- **Encourage Multiple Perspectives:** Broaden the scope by asking for diverse viewpoints.
  - Original Prompt: "Why are electric toothbrushes good?"
  - Better Prompt: "What are the pros and cons of electric toothbrushes?"
- **Request Step-by-Step Explanations:** Ask for a breakdown if a topic is complex.
  - Original Prompt: "How do you ride a bike?"
  - Better Prompt: "Explain how to ride a bike without training wheels, step by step."

A good prompt often includes multiple parameters and can extend beyond a sentence or two to be an entire paragraph long (or more). The upcoming sections present several more intermediate and advanced techniques.

---

## Intermediate Prompting Techniques

More advanced prompting techniques push models to provide more variety and novelty in their responses. While not exhaustive, this list offers a starting point for such:

- **Challenge-Based Prompts:** Request questions or hints to encourage critical thinking.
  - Example: "Provide three clues for remembering the Pythagorean theorem."
- **Feedback Requests:** Use AI as an editor or advisor when making revisions.
  - Example: "Suggest three ways to expand this paragraph."
- **Role-Playing:** Assign the AI a specific persona for more creative or specialized outputs.
  - Example: "Take on the role of Sherlock Holmes and describe how to solve the case."
- **Expert Emulation:** Instruct the AI to emulate a subject-matter expert for in-depth answers.
  - Example: "As a historian specializing in Ancient Greece, explain the significance of the Olympic Games."
- **Negative Prompts:** Specify which elements to exclude.
  - Example: "Describe a sunset without using the words 'beautiful' or 'golden.'"
- **Custom Models:** Some platforms allow custom training for specialized tasks or fields.
  - Example: "Describe the habitat of a red panda using information from the provided wildlife database."

These prompting techniques are not always necessary to create better outputs but can be experimented with at any point in the creative process.

---

## ⭐ Learning Objectives

**2.1** Identify appropriate prompts to elicit textual information.

- ii. Summarization.

## Summarization

Summarization helps break down complex information into smaller pieces, which makes it easier to grasp. AI models are beneficial because they can sift through large amounts of text and immediately highlight the most relevant points.

A good prompt specifies the requested summary's length, focus, and style. For example, instead of saying, "Summarize this article," a more effective prompt would be, "Summarize this article in three sentences. Focus on the causes and impacts of the event." This directs the AI only to highlight the most relevant aspects.

### Using Summaries

A user might prompt a model with one of four types of summaries:

- **General Summary:** "Summarize the main arguments of this article in bullet points."
- **Detailed Summary:** "Summarize this chapter. Include the main events and the character's motivations."
- **Focused Summary:** "Summarize the introduction and conclusion. Focus on the author's main argument."
- **Comparative Summary:** "Compare the first and last chapters. Describe how the author's viewpoint evolves."

### Techniques for Generating Accurate and Coherent Summaries

Additionally, not all summarize prompts must use the word "summary." New keywords can change the output depending on the desired outcome.

The following list contains a few examples:

- **Condense:** "Condense this article into three key points."
- **Paraphrase:** "Paraphrase the main ideas of this chapter."
- **Outline:** "Outline the major events of the Civil War."
- **Brief:** "Give a brief version of the report on climate change impacts."
- **Simplify:** "Simplify this explanation of photosynthesis for a 5th grader."
- **Recap:** "Recap the main arguments in this debate."
- **Highlight:** "Highlight the most important details in this research paper."
- **Abstract:** "Provide an abstract of this scientific study."

AI summarization is not perfect. At times, it might oversimplify complex ideas, misinterpret nuanced arguments, or miss important context, which might require using advanced prompting techniques like progressive summarization. This means starting broad and refining the output through follow-up prompts.

---

## ⭐ Learning Objectives

**2.1** Identify appropriate prompts to elicit textual information.

- iii. Content creation and ideation.

## Content Creation and Creative Prompts

Generative AI models turn simple ideas into a cohesive narrative through creative prompting.

Some use cases might include the following:

- **New Concepts:** "Imagine a future where kids rule the world. How might they create renewable energy?"
- **Storytelling and Character Development:** "Create a story about a wizard who forgets how to cast spells and meets an unexpected ally on his journey in the woods."
- **Poems or Songs:** "Write a playful rhyming poem about a dog that likes digging holes."
- **What-If Scenarios:** "Describe an Earth where dinosaurs never went extinct, and humans live alongside them."
- **Style and Tone:** "Describe a mountain that feels alive, using a mysterious, eerie tone."
- **Imagery:** "Describe a haunted castle using vivid sensory details."
- **Creative Constraints:** "Write a science fiction story set on a planet where people can only speak backward."

These prompts will inspire new ideas that may lead to even more prompts and outputs.

---

## ⭐ Learning Objectives

**2.2** Identify appropriate prompts to transform content.

- i. Reformat content to meet a requirement.
- ii. Editing and proofreading documents.
- iii. Providing a visualization of content.
- iv. Transforming content into a different media type.
- v. Translating content to a different language.
- vi. Personalizing and adapting content to facilitate learning and comprehension.

## Translating and Personalizing Content

Generative AI can also translate text between languages and personalize content to resonate with specific audiences better.

- Example: "Translate this article from English to Spanish. Maintain a humorous and playful tone."
- Example: "Rewrite this science lesson for middle school students using simple language and real-world examples."

Of course, users still need to pay close attention to the way the models attempt to convey idioms, cultural references, and emotional tones, as direct word-for-word translations may not always produce the best result.

- Example: "Translate this poem into Japanese. Preserve its poetic rhythm and emotional impact."
- Example: "Rewrite this motivational speech for a corporate team, using relatable language and examples."

## Restructuring, Reformatting, and Editing with AI

AI can transform content into new formats, simplify complex ideas, and polish writing at any stage of the writing process.

- Example: "Turn this article about killer whales into a 6-10 slide presentation. Include an introduction, habitat, behaviors, facts, a summary, and a final slide thanking the audience. Add brief speaker notes for each slide."

Asking the AI to focus on main ideas, repeat certain information, provide an outline, or evaluate its own work tends to improve structure, flow, and logic.

- Example: "Focus on the three main arguments. Ignore all the extra details."
- Example: "Use the keywords biology, ecosystem, and conservation throughout the text."
- Example: "Evaluate this story for coherence and suggest improvements."

AI tools like Grammarly can edit and proofread by correcting grammar, suggesting better phrasing, and enhancing sentence structure. However, AI tools can make inaccurate corrections, and some models struggle with long texts. In the latter case, breaking up prompts into one step at a time is better. Future sections revisit this idea.

- Example: "Identify grammatical errors and explain each correction."
- Example: "Suggest three alternative ways to phrase this sentence for better flow."
- Example: "Rewrite this paragraph for greater engagement."

## Visualization and Transforming Content

AI can also organize information visually, create headlines for digital platforms, or outline processes as flowcharts.

- Example: "Rewrite this text as bullet points. Each bullet point should be less than two sentences."
- Example: "Summarize this article and create five engaging headlines suitable for a newsletter."
- Example: "Outline the water cycle process as a flowchart."

In addition to generating multimedia content, AI can convert content from one format to another, especially useful for catering to different audiences.

- Example: "Rewrite this blog post as a podcast script with an engaging opening and a call to action at the end."
- Example: "Summarize the main points of this podcast in one paragraph."
- Example: "Describe this image of a rainforest, including the main objects, colors, and mood."

Cross-media transformations enhance and adapt content to different learning styles or abilities and can expand the reach of ideas by adapting them for multiple platforms, such as social media posts, YouTube videos, or presentations. However, maintaining the original message and tone across different formats can be challenging and require additional prompting.

- Example: "Turn this article into a lighthearted video script for a young audience. Use a school-appropriate, positive voice and tone."
- Example: "Adapt this essay into a fun, clean rap song."
- Example: "Provide five ideas to enhance this presentation for visual and auditory learners."

Users can also create different prompts to experiment with unconventional formats.

- Example: "Rewrite this historical event as if George Washington were writing a diary entry."
- Example: "Turn this science lesson into a treasure hunt game where solving equations unlocks clues."
- Example: "Create a mystery case file narrative using the facts from my research paper."

The biggest takeaway here is that AI can be a wonderful tool for inspiring new ways of thinking about content. The number of prompt ideas and combinations is as limitless as human imagination itself.

---

## Up Next: Topic 2B – Prompt Engineering for Image Generation

Nowadays, most prompt engineering relies on the ability to communicate effectively through text and written words. The following sections build on these text-prompting skills and apply the same principles to image and video generation.
