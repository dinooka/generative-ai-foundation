# Topic 1A: AI Terminology

> Study notes summarized in our own words. Not verbatim course text. Single scrollable page.

## Key points
- AI splits into action-oriented types and data-examination types:
  - **Predictive AI** forecasts future outcomes from historical data.
  - **Discriminative AI** assigns inputs to categories by drawing boundaries between classes.
  - **Analytical AI** finds relationships in complex datasets.
  - **Statistical AI** uses regression, probability, and hypothesis testing.
- **Machine learning** is a subset of AI with three learning styles: supervised (labeled data), unsupervised (clustering unlabeled data), reinforcement (trial-and-error guided by rewards/penalties).
- **Generative AI** is a distinct ML branch: earlier model types interpret existing information, while generative models create new text, images, audio, or video from learned patterns.
- Models store knowledge as statistical relationships across training data (e.g., text models learn word connections across billions of sentences; image models learn visual elements paired with descriptive language).
- Five core architectures:
  - **Transformer models** — sequence relationships; translation/summarization.
  - **Diffusion models** — rebuild data from noise; image generation.
  - **VAEs** — compress-then-reconstruct; stylized variations.
  - **GANs** — generator vs. discriminator; realistic synthetic media.
  - **CNNs** — layered image understanding; classification.
- Generative AI differs from search engines: search retrieves and ranks existing pages, while generative models synthesize new content from learned patterns; some platforms combine both.
- Training pipeline: pre-training on vast collections, parameter adjustment at massive scale, then **inference**, where the model predicts likely outputs (tokens for text) rather than retrieving facts.
- Training data scale introduces viewpoints, phrasing habits, and cultural assumptions; image training relies on manually tagged text-image pairs and heavy GPU/energy use.
- Confident-but-wrong outputs happen because models predict probable sequences, not verified facts.
- Embedded knowledge checks appear after major sections.

## Key terms
predictive AI, discriminative AI, analytical AI, statistical AI, machine learning, supervised learning, unsupervised learning, reinforcement learning, generative AI, transformer model, diffusion model, VAE, GAN, CNN, token, pre-training, inference, refinement step.


## Knowledge checks
1. **Drag-and-drop fill-in-the-blanks** (after "Machine Learning"): match the four AI types (predictive, discriminative, analytical, statistical) to their definitions.
2. **Drag-and-drop matching** (after "Different Types of Generative AI Models"): match generative model architectures (transformer, diffusion, VAE, GAN, CNN) to their primary applications.
