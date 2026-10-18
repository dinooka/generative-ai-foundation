# Chapter 2: Basic Prompt Engineering

## Topic 2C: Prompt Engineering for Video Creation and Transformation

**Learning objective:** Identify appropriate prompts to elicit video creation and transformation.

AI can transform static images into dynamic animations and generate complete videos from scratch with the proper prompts. This topic explores prompting for motion, transitions, colorization, avatar creation, and other video transformations.

## Learning objectives

Identify appropriate prompts to elicit video creation and transformation, including:
- Adding motion to images
- Generating video from a prompt
- Interpolating between images
- Colorizing a black-and-white movie
- Generating an avatar that reads a script
- Adding and removing objects in a video
- Automated subtitling

AI can transform static images into dynamic animations and generate complete videos from scratch with the proper prompts. This topic explores how to prompt various types of motion, transitions, colorization, and even avatar creation to bring more complex visual ideas to life.

### 1. Adding Motion to Images

AI can animate still images by adding subtle movements, camera pans, or object motions to create a more immersive experience.

- Using Runway for video generation from a static image with the prompt: “Extreme wide angle establishing shot: [subject] in vast [scene].”

- Using Runway for video generation from a static image with the prompt: “First person view shot of a fox. hyper-speed fly, dynamic motion, dynamic blur, timelapse, 30x speed.”

#### Examples of Prompts for Specific Types of Motion

- **Subtle Animation:** Sometimes, the slightest movement can create a more immersive experience for the viewer.

  - **Example:** “Add subtle animation to this image of a forest. Make it look like the leaves on the trees are swaying gently in a light breeze.”

- **Camera Panning:** This prompt makes it look like a camera is moving in the same way that you might see on a movie screen.

  - **Example:** “Animate a slow camera pan from left to right across this image of a city skyline at dusk. Focus the scene on the darkening sunset.”

- **Object Movement:** Choosing a focal point gives the viewers something specific to focus on.

  - **Example:** “Animate the bird in this image. It should take off from the branch and fly across the scene, flapping its wings while everything around it stays still.”

#### Techniques for Controlling Motion in Animated Images

- **Speed of Motion:** You can control how fast or slow you want the animation to be by including motion instructions in your prompt.

  - **Example:** “Make the butterfly’s wings flap in extra slow motion. The entire video should be 15 seconds long.”

- **Direction of Movement:** You can take the role of a director and provide details on the direction of the motion for each Object within a scene, such as “left to right,” “diagonally upward,” or “circular.”

  - **Example:** “Animate the raindrops falling diagonally from the top right of the window to the bottom left corner.”

- **Animation Style:** AI can produce clips in any animation style you can think of, but it cannot do that without a prompt. Words like realistic, stylized, jittery, or smooth are a great start.

  - **Example:** “Animate the ocean waves in an exaggerated and choppy manner to make it look like it could be a 2D cartoon.”

- **Combine Multiple Motions:** Include multiple motions in a single prompt for more complex animations.

  - **Example:** “Add a slow camera zoom into the center of the image displaying a park while animating the fireworks exploding in the background in all directions. Finish with a close-up of one final firework fizzling out.”

**Knowledge Check Topic 2C.1**

**Knowledge-check example — OpenAI Sora**

> Using Open AI Sora with the following prompt: “A stylish woman walks down a Tokyo street filled with warm glowing neon and animated city signage. She is wearing black leather jacket, a long red dress, and black boots, and carries a black purse. She wears sunglasses and red lipstick.”

### 2. Generating Video from a Prompt

AI models are already so advanced that they can create full videos from a simple text description or image. As a result, more and more creatives are being empowered to explore video production, animation, and visual storytelling with prompts related to content, style, and duration, among other elements.

#### Examples of Prompts for Generating Video Content

- **Narrative-Driven Video:** Anytime you hear the word “narrative,” you should think of stories. This type of prompt guides the AI to create a specific story with a particular mood, pacing, and style.

  - **Example:** “Create a 2-minute animated video of a young girl exploring a haunted house, with suspenseful music and dim lighting. The video should be created in a hand-drawn animation style.”

- **Product Advertisement:** If you watch your favorite movie again, you will likely spot a few famous products placed in the main shots. These product placements let advertisers reach new audiences and promote their products.

  - **Example:** “Generate a 30-second video ad for a new sports drink featuring football players running, jumping, and celebrating. The video should have vibrant colors and a high-energy style with upbeat background music.”

- **Educational Content:** AI can provide tailored videos for learners at different levels to help them understand the curriculum better.

  - **Example:** “Produce a 3-minute explainer video about Egypt using colorful 2D animations and a friendly, conversational tone.”

#### Techniques for Crafting Better Prompts for Video Generation

- **Define the Visual Elements:** The visual elements in a video include all the characters, settings, objects, and actions.

  - **Example:** “Include a diverse group of students in a classroom setting, with close-ups on their faces as they discuss their science project. They should all appear happy and excited to be working together.”

- **Set the Style and Tone:** Clearly indicate the style (e.g., realistic, cartoonish, minimalist) and tone (e.g., silly, scary, inspirational) to give the AI a sense of the type of film you are trying to create.

  - **Example:** “Create a minimalistic, black-and-white animation with a more serious tone that shows which animal species are endangered and which are already extinct.”

- **Specify the Duration and Pacing:** Include the minimum and maximum length of each clip. You can also provide additional details about the video’s pacing, including quick cuts, slow transitions, or dramatic build-ups.

  - **Example:** “Generate a 45-second video with quick cuts between different scenes. Maintain a fast, energetic pace throughout the entire film.”

- **Include Audio Cues:** Mention the type of audio elements you would like in the final video, such as background music, voiceovers, or sound effects. Some AI tools can handle video and audio elements together, while others require separate inputs and outputs.

  - **Example:** “Use calming, ambient music in the background, with occasional nature, sounds like birds chirping and leaves rustling.”

#### Good, Better, Best Examples for Video Generation Prompts

- **Good:** “Create a video about a dog.”

- **Better:** “Create a 1-minute video about a dog playing in a park.”

- **Best:** “Create a 1-minute video of a golden retriever playing fetch in a sunny park, with children laughing, birds chirping, and a happy soundtrack.”

### 3. Interpolating Between Images

Interpolation blends images or frames for smoother, more cohesive transitions.

#### Examples of Prompts for Image Interpolation

- **Simple Cross-Dissolve Transition:** This type of transition involves a gradual blend from one image to another.

  - **Example:** “Create a smooth cross-dissolve transition between the image of a sunset and the image of a starry night sky. The duration should be five seconds.”

- **Morphing Transition:** This type of transition demonstrates a transformation by smoothly altering one image so that it becomes another right before the viewer’s eyes.

  - **Example:** “Morph the first image of a caterpillar into the second image of a butterfly, showing the stages of metamorphosis in ten intermediate frames.”

- **Slide Transition:** This type of transition adds more movement to the animation and can be used for big reveals or to uncover other information.

  - **Example:** “Create a slide transition where the first image of a mountain landscape slides out to the left. It should reveal the second image of a beach scene from the right.”

#### Techniques for Crafting Better Image Interpolation Prompts

- **Define the Frames:** Specify which images you want the AI to start and end with, as well as any other frames it should include in between.

  - **Example:** “Interpolate between the image of a closed flower bud (keyframe 1) and a fully bloomed flower (keyframe 3), with an intermediate frame showing the flower in the process of blooming (keyframe 2).”

- **Specify the Interpolation Style:** Describe how intense or dramatic you would like the pacing of the transition to be.

  - **Example:** “Create a smooth and easy transition between the two images, starting slowly and then speeding up rapidly toward the end.”

- **Include Timing and Duration:** Provide details on the length of the transition and how much time each frame should take.

  - **Example:** “Generate a ten-frame interpolation sequence over three seconds, with each frame displayed for 0.4 seconds.”

### 4. Colorizing Black-and-White Footage

AI can add color to black-and-white images or videos to transform historical footage or enhance creative projects.

#### Techniques for Better Colorization Prompts

- **Basic Colorization:** Most colorization tasks focus on staying true to historical footage with natural and realistic colorizing.

  - **Example:** “Colorize this 1920s black and white film using natural skin tones, muted earth colors for clothing, and soft hues for the backgrounds.”

- **Mood-Based Colorization:** This type of prompt asks the AI to match the new color of a film with its emotional tone to tell a story.

  - **Example:** “Colorize this war movie footage with a darker, desaturated color palette to convey a serious and gritty atmosphere.”

- **Historical Accuracy:** AI does not understand the context of certain historical events, or any historical event, for that matter. We need to remind it to be sensitive and accurate.

  - **Example:** “Colorize this 1950s documentary using colors that were accurate for the time period. This includes bright cars and muted interior décor. Pay extra attention to the historical accuracy and relevancy.”

### 5. Creating Script-Driven Avatars

AI-generated avatars can perform scripts, present educational material, and appear in entertainment content. In this case, prompts define their appearance, voice, emotional expressions, and context.

- **Virtual Presentations:** Professional avatars for corporate videos or webinars.

  - **Example:** “Create a realistic avatar in business attire with a friendly, authoritative voice.”

- **Educational Avatars:** Personal tutors or engaging e-learning coaches.

  - **Example:** “Design a teenage avatar with curly red hair and an enthusiastic American accent.”

- **Entertainment and Media:** Animated characters for storytelling or games.

  - **Example:** “Create a fantasy elf with silver hair and a playful demeanor.”

Some techniques for creating better avatar prompts include:

- **Describe Appearance:** Specify physical features, clothing, and accessories.

  - **Example:** “Young woman with short black hair wearing a yellow hoodie.”

- **Define Voice and Accent:** Control speech pattern, accent, and tone.

  - **Example:** “Soft, soothing voice with a Southern American accent.”

- **Include Emotional Expressions:** Guide facial expressions and gestures.

  - **Example:** “Wide eyes and a big smile to convey excitement.”

- **Specify Script Context:** Match the avatar to the scenario’s purpose.

  - **Example:** “A bedtime story narrator with a warm, gentle voice and soft expressions.”

*AI image of an avatar with the prompt:  “Create an avatar of a young woman with short black hair, wearing a yellow hoodie”.*

### 6. Localized Video Editing

AI systems adjust specific parts of a video through generative inpainting and outpainting, which gives creators the ability to add new elements, remove distractions, or repair continuity issues without rebuilding an entire scene. These localized edits operate on defined regions of the frame and follow the instructions inside the prompt to match lighting, motion, and perspective. This targeted control supports a wide range of practical needs across commercial content, social media, training modules, and narrative footage.

Localized adjustments help maintain continuity by correcting small errors, such as removing a stray object that breaks the visual rhythm of a shot. They also support creative additions, such as placing new props, signage, or environmental elements that elevate the scene. Each prompt outlines what changes occur and how the new or altered element integrates with the original footage.

Object Identity states what should appear or disappear. This includes props, clothing details, background items, or light sources.

  - **Example:** “Remove the coffee cup from the desk and replace it with a closed notebook.”

Placement and Scale define where the new object sits inside the frame and how large it should appear relative to nearby elements.

  - **Example:** “Place a small lantern on the left side of the table.”

Lighting and Environmental Integration ensure the added or altered element matches the scene’s highlights, color temperature, and shadow direction.

  - **Example:** “Add a street sign that matches the warm, late-afternoon lighting.”

Motion Consistency keeps the edit aligned with moving footage. The new object follows camera shifts, environmental motion, or character movement.

  - **Example:** “Add a floating hologram that rises slightly as the camera tilts upward.”

Localized edits guide attention inside the frame, but accessibility expands who receives the message. The next section turns to automated subtitling, where prompts tweak language, formatting, and timing to support more inclusive video delivery.

#### Examples of Prompts for Object Removal

- **Removing a Static Object:** A static object does not move. This might be something like a coffee mug or other distracting element in the video, which the AI must remove.

  - **Example:** “Remove the microphone stand from the left side of the frame in this interview footage and fill in the background with the pattern of the carpet and wall.”

- **Removing a Moving Object:** A moving object is called a dynamic object. These objects might accidentally mess with the focus of a video and, therefore, need to be removed to avoid distracting the viewers.

  - **Example:** “Remove the car driving through the street in the background of this scene, and fill in the road and surrounding buildings to match the original footage.”

- **Removing Watermarks or Logos:** This type of prompt helps remove watermarks, logos, or text overlays from footage to repurpose it for different contexts. Just be careful that you have permission to do so.

  - **Example:** “Remove the watermark from the bottom right corner of the video and blend the background to match the surrounding elements.”

#### Applications of AI-Powered Object Removal in Video Editing

- **Film and TV Production:** Removing unwanted elements, such as boom microphones, crew members, or other distractions, can improve the quality of the scenes and give the viewers a better overall experience. Boom mics surprisingly appear in many old shows like Gilmore Girls, most likely unintentionally.

- **Marketing and Advertising:** Editing footage to remove unwanted branding, logos, or other elements can ensure a video does not conflict with a business’ standards or customers’ expectations.

- **Content Repurposing:** Reusing footage by removing dated elements or irrelevant objects can make it “evergreen” or useable in other contexts for a long time.

### 7. Automating Subtitling and Video Accessibility

Just as AI can improve image accessibility, it can also generate subtitles to improve video accessibility. Prompts should specify language, formatting, speaker differentiation, and timing.

#### Examples of Prompts for Subtitling

- **Basic Subtitling:** A simple prompt can produce subtitles that traditionally play at the bottom of the screen during movies and videos.

  - **Example:** “Generate English subtitles for this 5-minute interview video, synchronizing with the speaker’s speech and formatting the text in a white, basic sans-serif font.”

- **Multilingual Subtitling:** This prompt can help a video reach a wider audience.

  - **Example:** “Generate subtitles in Spanish, French, and Mandarin for our promotional video, ensuring that all translations maintain the original tone and style.”

- **Subtitling for Accessibility:** Viewers who are deaf or hard of hearing often appreciate additional context beyond spoken dialogue, like the music playing in the background or the tone of the speakers.

  - **Example:** “Generate English subtitles for this documentary with speaker identification and descriptive audio cues for background sounds and music.”

#### Techniques for Crafting Better Prompts for Automated Subtitling

- **Specify the Language and Formatting:** Clearly state the desired language and any specific formatting requirements, such as font type, color, size, or position.

  - **Example:** “Generate German subtitles in a yellow, bold font at the bottom of the screen.”

- **Include Speaker Differentiation:** For videos with multiple speakers, prompt the AI to identify and differentiate between speakers to avoid confusion.

  - **Example:** “Subtitle this debate video with speaker names and color-coded text for each participant.”

- **Set Timing and Synchronization Parameters:** Indicate how closely the subtitles should synchronize with the spoken content, whether by word, phrase, or sentence.

  - **Example:** “Make sure the subtitles are synced to each sentence spoken, with no more than a 0.5-second delay.”

**Knowledge Check Topic 2C.2**

**Up Next: Chapter 3 -Advanced Prompt Refinement**

This section explored how to effectively prompt for animation and videos, including prompts related to colorization, avatars, and subtitles. The following sections examine the content and prompt refinement process, demonstrating the difference between clear and ambiguous prompts in various contexts.
