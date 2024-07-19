# Composable VLMs

## Current Use Case: Enhancing Computer Vision with Multimodal Integration

Our focus is on developing a comprehensive, multimodal Computer Vision solution through a two-phase approach:

1. **Optimization of Individual Sight Tools:**
   - Refine and enhance the performance of standalone tools for:
     * Object detection
     * Image and video segmentation
     * Automated labeling
     * Multi-class classification
   - Rigorously validate each tool's accuracy and efficiency in isolation

2. **Integration for True Perception:**
   - Synthesize inputs from various optimized tools to create a cohesive, multi-faceted understanding of visual data
   - Develop algorithms to meaningfully combine tool outputs, mirroring human-like perceptual abilities
   - Enhance the overall solution's ability to interpret complex visual scenarios

3. **Leveraging Vision-Language Models (VLMs):**
   - Incorporate VLMs as a complementary component within our broader Computer Vision toolkit
   - Utilize VLMs to augment and enrich the outputs of traditional Computer Vision algorithms
   - Explore synergies between VLMs and other AI models to boost overall solution quality

Our ultimate goal is to create a robust, adaptable Computer Vision system that not only excels in individual tasks but also demonstrates advanced, context-aware visual understanding. By optimizing individual components and then integrating them thoughtfully, we aim to push the boundaries of what AI can perceive and interpret in visual data.

## Analogies for Better Understanding:

1. **The Senses Analogy**:
   - Humans rely on multiple senses to perceive the world comprehensively.
   - Even within a single sense like sight, there are various components:
     * Color vision (cones) for daytime visual processing
     * Night vision (rods) for low-light conditions
     * Motion perception through specialized neural pathways
     * Depth perception using binocular vision
   - Integration of these visual components creates our complete visual experience.
   - Beyond sight, we correlate information from sound, touch, taste, and smell.
   - Example: Detecting spoiled milk
     * Smell and taste often alert us before visual cues become apparent
     * This demonstrates the importance of integrating multiple sensory inputs for accurate perception

2. **The Olympic Gymnast Robot**:
   - Imagine training a humanoid robot to win the balance beam event at the Olympics.
   - This task requires harmonious integration of various sensory inputs and motor controls:
     * Visual data processing for spatial awareness
     * Proprioception for body position sensing
     * Balance information from vestibular system equivalent
     * Force feedback from points of contact with the beam
   - The robot must process all these inputs simultaneously to perform complex routines.
   - This analogy illustrates the importance of true perception and seamless integration of multiple "senses" in AI systems.

3. **The AI Art Critic**:
   - Envision an AI system tasked with critiquing modern art installations.
   - It would need to integrate:
     * Visual analysis of composition, color, and form
     * Audio processing for sound installations
     * Natural language understanding for artwork titles and descriptions
     * Contextual knowledge of art history and cultural references
   - This example showcases the need for AI to synthesize information across modalities to form higher-level interpretations and judgments.

These analogies underscore the importance of developing AI systems that can process and integrate multiple streams of information. For example, OpenAI's CLIP model successfully combines text and image data to enhance contextual understanding, demonstrating the potential of multimodal integration. Similarly, Boston Dynamics’ robots utilize sensory data fusion to navigate complex environments effectively.

By refining the integration of visual inputs, we're participating in the broader effort to create AI systems with more human-like perceptual abilities. This approach not only builds upon existing progress but also positions our work within the larger context of advancing AI perception and integration across multiple sensory modalities.

The ultimate goal is to develop AI systems that can seamlessly combine inputs from various sensory domains, leading to more sophisticated, context-aware, and adaptable artificial intelligence. This multi-modal integration is crucial for creating AI that can interact with and understand the world in ways that more closely mirror human cognition and perception.

---

## Project Title: OmniScience: Adaptive AI for Dynamic Life Sciences Manufacturing Monitoring

---

**Problem:**

Current biomanufacturing processes lack real-time, adaptive monitoring systems capable of ensuring consistent quality and safety across diverse cell types, bioproducts, and production scenarios.

---

**Why It Matters:**

Biomanufacturing demands precise, adaptable, and continuous monitoring to ensure product efficacy and safety. OmniScience™ addresses this by leveraging Vision-Language Models (VLMs) with adaptive fine-tuning to enhance perception and provide dynamic insights throughout the manufacturing process. This is crucial because:

1. **Enhanced Quality and Safety:** OmniScience's adaptive perception mirrors the evolving complexity of bioproducts, leading to higher quality and safer therapies and products.
2. **Increased Efficiency:** Automating routine monitoring augments specialists' capabilities, allowing them to focus on critical decision-making.
3. **Rapid Adaptation:** OmniScience quickly adapts to new bioproducts or manufacturing conditions, essential in the dynamic field of life sciences.
4. **Comprehensive Monitoring:** The shifting perceptive approach extends to various stages of the manufacturing process, from initial cultivation to final product formulation.
5. **Future-Ready Manufacturing:** By pushing the boundaries of adaptive AI in biomanufacturing, OmniScience contributes to a future where production is more reliable, efficient, and scalable.

---

**Success Metrics:**

1. **Adaptive Accuracy:** Achieve a 95% or higher agreement rate with expert analysts across diverse bioproducts and manufacturing stages.
2. **Process Efficiency:** Demonstrate the ability to shift and incorporate new insights within hours, reducing production delays and enhancing overall manufacturing efficiency by 30%.

---

**Audience:**

OmniScience™ is designed for biopharmaceutical manufacturers, quality control specialists, and bioprocess engineers who need:

- Rapid perception-shifting tools to identify process deviations or anomalies across various bioproducts.
- Dynamic insights into bioproduct characteristics throughout the manufacturing pipeline.
- Adaptive AI assistants for real-time decision-making on large volumes of in-process data.

---

**Potential Solution:**

We will enhance our existing adapter-based fine-tuned PaliGemma model to create OmniScience™:

1. **Dynamic Data Integration:**
   - Expand our dataset to include diverse bioproducts and manufacturing stages, focusing on critical quality attributes.
   - Implement data augmentation techniques that mimic real-world manufacturing variability.
2. **Shifting Insight Modules:**
   - Refine our LoRA (Low-Rank Adaptation) configuration to create specialized "sight-shifting modules" for different manufacturing aspects.
   - Develop a meta-learning framework for rapid adaptation to new bioproducts or process parameters.
3. **Adaptive Knowledge Integration:**
   - Implement a dynamic knowledge retrieval system focusing on current manufacturing stages and bioproduct characteristics.
   - Create an adaptive prompt generation system based on OmniScience's current perceptions and process uncertainties.
4. **Multi-faceted Process Insights:**
   - Train complementary adapters for various manufacturing stages that can be dynamically combined for comprehensive insights.
   - Implement an adaptive fusion mechanism to shift the weight of insights from different stages based on relevance.
5. **Dynamic Inference Pipeline:**
   - Develop a system for real-time adaptation of OmniScience's perceptive capabilities based on in-process feedback.
   - Implement adaptive quantization techniques to maintain perceptive accuracy while optimizing for in-line monitoring.
6. **Explainable Insights:**
   - Create an adaptive visualization system highlighting OmniScience's perception shifts across manufacturing stages.
   - Train a specialized adapter for generating natural language explanations tailored to different stakeholders' needs.

---

**Sharing OmniScience™:**

1. **Industry:** Engage with biopharmaceutical manufacturers and biotech companies, focusing on rapid adaptability to diverse manufacturing processes.
2. **Academic:** Present at bioprocessing and life sciences conferences, emphasizing OmniScience's adaptive and perceptive nature.
3. **Regulatory:** Collaborate with regulatory bodies to explore how adaptive AI can enhance manufacturing quality and consistency.
4. **Open Source:** Release select modules and training pipelines on GitHub, encouraging community extension and adaptation.

---

**Conclusion:**

OmniScience™ represents a groundbreaking advancement in adaptive AI for life sciences manufacturing. It offers real-time, dynamic monitoring and insights, enhancing quality, efficiency, and scalability. By addressing current gaps and setting clear performance goals, OmniScience™ aims to revolutionize biomanufacturing, paving the way for more consistent, efficient, and scalable production processes.

---

## Appendix

### Overview of Vision Models - a different perspecitve

- a big shout out to LandingAI and Andrew Ng for sharing this uncommon perspective and approach

| Model Name          | Hugging Face Model                  | Primary Function               | Use Cases                                                    |
|---------------------|-------------------------------------|-------------------------------|--------------------------------------------------------------|
| OWL-ViT v2          | google/owlv2-base-patch16-ensemble  | Object detection and localization | - Open-world object detection<br>- Locating specific objects based on text prompts |
| Florence-2          | microsoft/florence-base             | Multi-purpose vision tasks      | - Image captioning<br>- Visual question answering<br>- Object detection |
| Depth Anything V2   | LiheYoung/depth-anything-v2-small   | Depth estimation                | - Estimating depth in images<br>- Generating depth maps      |
| CLIP                | openai/clip-vit-base-patch32        | Image-text similarity           | - Zero-shot image classification<br>- Image-text matching    |
| BLIP                | Salesforce/blip-image-captioning-base | Image captioning                | - Generating text descriptions of images                    |
| LOCA                | Custom implementation               | Object counting                 | - Zero-shot object counting<br>- Object counting with visual prompts |
| GIT v2              | microsoft/git-base-textcaps         | Visual question answering and image captioning | - Answering questions about image content<br>- Generating text descriptions of images |
| Grounding DINO      | groundingdino/groundingdino-swint-ogc | Object detection and localization | - Detecting objects based on text prompts                   |
| SAM                 | facebook/sam-vit-huge               | Instance segmentation           | - Text-prompted instance segmentation                       |
| DETR                | facebook/detr-resnet-50             | Object detection                | - General object detection                                  |
| ViT                 | google/vit-base-patch16-224         | Image classification            | - General image classification<br>- NSFW content detection  |
| DPT                 | Intel/dpt-hybrid-midas              | Monocular depth estimation      | - Estimating depth from single images                       |
