# Topic 3A: Prompt Refinement for Targeted Outputs

**Chapter 3: Advanced Prompt Refinement**

**Learning Objective:** Given an initial prompt and its output, evaluate how the prompt can be improved to elicit more targeted output.

It is rare to produce a perfect output from a single input regardless of the media type (text, image, video, audio). LLMs use conversational language; just like human-to-human communication, there are misunderstandings.

Learning to refine prompts takes patience and iteration. It is most effective when specificity, clarity, and context come together, and mastering these elements enables users to harness generative AI's full potential.

---

## ⭐ Learning Objectives

**3.1** Given an initial prompt and its output, evaluate how the prompt can be improved to elicit more targeted output.

- i. Content
  - Creating a prompt at the right level of specificity.
  - Creating prompts that are clear and not abbreviated.
  - Not making the assumption that the AI will "know" what you're talking about.

## Content: Specifying What the Model Needs to Deliver

Specificity determines the level of detail in a prompt. A vague prompt leads to generic or unrelated outputs, but an overly restrictive prompt can deliver equally poor-quality responses that are overly predictable or too rigid. The middle ground provides the greatest space for accuracy while leaving room for creative freedom.

Imagine giving directions to visitors who have never been to a certain town. "Meet me at the park" could be confusing if multiple parks are within the area. However, instructing them to meet "at the park with the red slide on Saratoga Drive at 2:00 pm" provides enough clarity to navigate independently. Similarly, prompts should contain enough detail to guide the AI without limiting creativity.

Consider the following examples and where they fall on the specificity scale.

### Examples of Specificity in Prompts

#### Too Broad

**Prompt:**

> "Write a short story."

**Output:**

> In a quiet town where everyone followed the rules, a girl named Savannah decided she wanted to be different. She started by painting her windows bright green with yellow polka dots, angering her neighbors. It was the talk of the town, heard in whispers through the streets. After weeks of rumors and gossip, the neighbors started to change their minds. Perhaps a silly window was precisely what the town needed after all. It reminded everyone that art didn't always have to make sense and that beauty was in the eye of the beholder. Just like that, more and more neighbors started painting their own doors and windows. Their world turned a little brighter and a little friendlier, and they all lived happily ever after.

**Problem:**

The story makes sense here, but the AI picked all the elements of the story randomly, including the character's name, the setting, and the plot. If the user had something specific in mind that they forgot to relay, this output might not be even close to what they wanted. A better prompt might include the most relevant parts of the story while leaving some room for exploration.

#### Too Narrow

**Prompt:**

> "Write a 200-word mystery story about a detective named Margot or Jane who lives in Chicago, has a cat named Boots, drinks coffee at 7 AM every morning, and solves a crime involving a stolen bicycle at exactly 3 PM in Lincoln Park. The thief should be a janitor named Bob."

**Output:**

> Jane lived in Chicago. She had a cat named Boots. She drank coffee every morning at 7 AM. One day, at 3 PM, she got a call about a stolen bicycle in Lincoln Park. She went to the park. A young boy pointed to where his bike had been. Jane looked around. She saw tire tracks in the mud. She followed the tracks. They led to a maintenance shed. The door was open. Inside, she saw the bike and a janitor. The janitor's name was Bob. Bob looked nervous. Jane asked him why he took the bike. He said he needed money. Margot called the police. Bob was arrested. Jane went home. Boots was waiting for her.

**Problem:**

The prompt has so many details that the AI got confused. The output is nowhere near the requested word count, and the writing is extremely choppy. The story does not flow well and lacks creativity and emotion. A better prompt might let the AI know it has permission to take more creative risks.

#### Just Right

**Prompt:**

> "Write a mystery story featuring a detective named Jane in a large city who solves an unusual crime. Add a surprising twist to the ending. Keep the story to 100 words or less."

**Output:**

> Detective Jane prowled the dark alleys of the city, piecing together the strange case of the missing singer. Clues led her to an abandoned theater, where she found a crumpled note: "Check the rooftop." Climbing up, she saw the singer—alive, unharmed, and laughing. Jane stood confused as the singer handed her a sheet of music. "It's a publicity stunt," the singer confessed. "The new song needed a story." Jane shook her head, amused. As she turned to leave, she noticed her wallet was gone. The singer grinned, waving it from a distance. "Theatrics," she winked, "always need a hook."

**Why It Works:**

The AI model was able to follow the request for a specific word count and planned the creative twist on its own. The output includes all the elements that the user asked for while also adding some engaging dialogue.

---

## ⭐ Learning Objectives

**3.1** Given an initial prompt and its output, evaluate how the prompt can be improved to elicit more targeted output.

- iv. Context
  - The AI needs to know the context for what it is asked to do; it's a machine, so it can't derive it naturally.

## Context: Supplying Background the Model Cannot Infer

Context refers to all the relevant background information related to a prompt's purpose and desired outcomes. Context may also include details about the audience or tone of a situation. AI models produce generic outputs without context, as they rely solely on the words in the prompt without understanding the underlying intent.

Consider the following prompts and how they are easily improved:

**Lacking Context:** "Describe a volcano."

- **Problem:** Depending on its interpretation, the AI could produce anything from a basic definition to a scientific analysis.
- **Improved Version:** "Describe the process of a volcanic eruption for a 7th-grade science class, using simple language and relatable examples."
- This version specifies the audience, complexity level, and narrative style, resulting in a more relevant output.

**Lacking Context:** "Write about World War II."

- **Problem:** Without clear direction, the AI could focus on any aspect, from battles to political leaders.
- **Improved Version:** "Write about World War II from the perspective of a young American soldier landing on Omaha Beach, describing his thoughts and experiences."
- This version provides a specific narrative perspective, enhancing emotional engagement and historical context.

**Lacking Context:** "Explain fractions."

- **Problem:** The explanation could be overly technical or simplistic without knowing the audience.
- **Improved Version:** "Explain fractions to 10-year-olds using relatable examples like pizza slices and video game scores."
- This version tailors the explanation to the audience's age and interests, increasing engagement and comprehension.

Adding context is as easy as remembering to add notes about the preferred language, style, complexity, and objective, such as persuading, informing, entertaining, or instructing the end user.

---

## Clarity

Clarity refers to the precision of the language used in each prompt. Ambiguity is on the opposite end of the spectrum.

Generative AI functions similarly to Amelia Bedelia, a fictional character known for interpreting instructions too literally. If told to "dress the turkey," Amelia would put clothes on it, while most Americans would understand this phrase means to prepare a meal with the proper spices and seasonings.

Likewise, vague prompts confuse AI models, resulting in outputs that may not align with the user's intentions.

**Unclear Prompt:** "Explain the process."

- **Problem:** The AI does not know which process is being referenced.
- **Improved Version:** "Explain the process of photosynthesis, focusing on how plants convert sunlight into energy."
- The improved prompt specifies the topic and the focus of the explanation.

**Unclear Prompt:** "Describe the results."

- **Problem:** Results can be quantitative or qualitative. The AI cannot infer which type to prioritize.
- **Improved Version:** "Describe the results of the science experiment on plant growth, including both quantitative data (height and growth rate) and qualitative observations (color and leaf health)."
- The improved prompt outlines the types of results required, reducing ambiguity.

**Unclear Prompt:** "Summarize the report."

- **Problem:** The AI cannot determine the topic, length, or audience.
- **Improved Version:** "Summarize this report on Ancient Egypt for a 7th-grade social studies class, highlighting key historical events and cultural practices."
- This version provides clear guidance on the content, audience, and style.

Clear prompts are much more likely to lead to relevant, accurate outputs that are tailored to the user's needs.

---

## Assumptions

Assumptions are often made without realizing it and occur when information is implied but not explicitly stated. This can confuse AI models and misdirect the output.

Consider how assumptions play a role in the following examples:

### Common Assumptions in AI Prompts and How to Avoid Them

**Assumption about Prior Knowledge:**

- **Prompt:** "Explain why this theorem is important."
- **Problem:** The AI does not know which theorem is being referenced.
- **Improved Version:** "Explain why the Pythagorean theorem is important in geometry and how it applies to real-world problems."

**Assumption about Context:**

- **Prompt:** "Describe Hermione's plan."
- **Problem:** The AI may not know this refers to Hermione Granger from "Harry Potter" or which specific plan is being discussed.
- **Improved Version:** "Describe how Hermione Granger convinced Harry Potter to join Dumbledore's Army in 'Harry Potter and the Order of the Phoenix.'"

To avoid making assumptions, users should always be clear about names, historical events, or cultural references, spell out acronyms, avoid field-specific language unless the context is explicitly stated, and define all expectations relating to an LLM conversation's desired perspective or depth.

---

## ⭐ Learning Objectives

**3.1** Given an initial prompt and its output, evaluate how the prompt can be improved to elicit more targeted output.

- ii. Style
  - Including information about the style and tone of the output.
  - Including a style guide.
- iii. Persona
  - Giving the AI a persona or role.

## Personas and Style Guides

Personas and style guides give generative AI a consistent voice and identity across multiple outputs.

Personas allow AI to assume specific roles or perspectives, such as that of a friendly teacher, a professional journalist, or a playful storyteller. This approach creates outputs that resonate more deeply with the intended audience.

### Incorporating Style and Tone in Prompts

**Example:**

- **Prompt:** "Write an informative article about climate change from the perspective of a passionate environmental activist. Use an urgent and persuasive tone."

Style guides standardize tone, language, and formatting across all written outputs by setting the mandatory rules an AI model must follow for all its grammar, vocabulary, and structure.

**Example:**

- **Prompt:** "Write a blog post about digital safety for teenagers, following our brand's style guide. Use an empathetic and conversational tone. Also, avoid all technical jargon."

Personas and style guides allow users to adapt AI's voice and tone to fit any context, audience, or purpose.

---

## Iterative Prompting in Action

Prompting consists of these four steps:

1. **Test the Prompt:** Generate an output to see how the AI interprets the input.
2. **Evaluate the Output:** Compare the result with the intended outcome and identify areas where the output was too vague, overly specific, or otherwise produced content outside of what was desired.
3. **Refine the Prompt:** Adjust the language, add context, or clarify instructions. Another important tip is to avoid making too many changes at once. This makes it easier to pinpoint exactly which element led to an improvement or introduced a new issue.
4. **Repeat the Process:** Continue refining and testing until the output meets expectations.

This iterative process should speed up the more users interact with a particular model, especially if its memory features are toggled on. This is a major benefit of most of the top generative AI models.

---

## Up Next: Topic 3B – Advanced Prompting

Prompt refinement blends strategy, creativity, and problem-solving; it brings ideas to life when done well. The next section explores advanced prompting techniques, including zero-shot, one-shot, and few-shot prompting, giving users more control over their AI-generated content.
