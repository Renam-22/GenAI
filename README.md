# GenAI-Assignments

# Generative AI Assignments Repository

This repository contains a collection of Generative AI assignments implemented as part of coursework. The projects cover core concepts in probabilistic generative modeling, prompt engineering, language model fine-tuning, question answering, diffusion models, multimodal learning, speech synthesis, AI-based video generation, and transformer-based text-to-image systems.

## Repository Objective

The main objective of this repository is to demonstrate practical implementation of important Generative AI techniques through small, focused assignments. Each task explores a different category of generative systems and helps build understanding of how modern AI models create text, images, speech, captions, and multimedia outputs.

## Assignments Overview

### 1. Probabilistic Generative Model / Markov Chain Text Generator
This assignment focuses on foundational generative approaches.

- **Option 1:** Implement a basic probabilistic generative model such as **Gaussian Mixture Models (GMM)** to learn data distributions and generate similar samples.
- **Option 2:** Build a simple **text generator using Markov Chains**, where the next word or token is predicted from previous states.

**Learning outcome:** Understand early generative methods and how probabilistic modeling can be used for data or text generation.

---

### 2. Prompt Engineering Approaches
This assignment studies multiple prompting strategies for large language models.

Covered approaches:
- **Interview Approach**
- **Chain of Thought (CoT)**
- **Tree of Thought (ToT)**
- **Zero-shot Prompting**
- **Few-shot Prompting**

The work includes implementation, comparison, contrast, and analysis of their applications and performance.

**Learning outcome:** Understand how prompt design affects reasoning quality, response structure, and model performance.

---

### 3. Fine-tuning GPT / GPT-2 for Creative Story Generation
This assignment involves fine-tuning a pre-trained language model such as GPT or GPT-2 on a story dataset to generate creative text.

Typical steps include:
- Preparing a story dataset
- Tokenization and preprocessing
- Fine-tuning the language model
- Generating stories from prompts
- Evaluating generated outputs

**Learning outcome:** Learn transfer learning, text generation, and how domain-specific fine-tuning improves language model outputs.

---

### 4. Question-Answering Chatbot Using a Pre-trained Language Model
This task builds a simple question-answering chatbot using a pre-trained transformer model.

The chatbot:
- Accepts user questions
- Processes them using a language model
- Returns relevant answers
- May be general-purpose or domain-specific

**Learning outcome:** Understand the basics of conversational AI, NLP pipelines, and pre-trained language model deployment.

---

### 5. Artwork Generation Using Stable Diffusion / Custom Diffusion Model
This assignment explores image generation using diffusion models.

- **Option 1:** Generate creative artwork using **Stable Diffusion**
- **Option 2:** Implement and modify a **pre-trained diffusion model** for a custom dataset

Possible tasks include:
- Prompt-based image generation
- Fine-tuning or adapting the diffusion model
- Comparing outputs with different prompts or datasets

**Learning outcome:** Learn how modern diffusion models generate high-quality visual content.

---

### 6. Text-to-Image Generation Pipeline Using DALL-E
This project builds a text-to-image pipeline using a pre-trained model like DALL-E.

The system:
- Takes textual prompts as input
- Uses a pre-trained model for generation
- Produces corresponding images

**Learning outcome:** Explore multimodal AI and the connection between language understanding and visual content generation.

---

### 7. Multimodal Image Captioning Using CLIP
This assignment develops a basic multimodal system for image captioning using CLIP or a related model.

Main steps:
- Extract visual features from images
- Connect image features with text understanding
- Generate meaningful image captions

**Learning outcome:** Understand multimodal learning and how AI combines image and text information.

---

### 8. Text-to-Speech Model Using Tacotron or WaveNet
This project focuses on speech synthesis using deep learning models such as Tacotron or WaveNet.

The system converts text into speech by:
- Processing written text
- Generating intermediate speech representations
- Producing natural-sounding audio output

**Learning outcome:** Learn the basics of neural speech synthesis and its real-world applications.

---

### 9. AI-based Tool for Simple Video Animations
This assignment uses an AI-based tool to generate simple video animations from text, images, or scene ideas.

Possible outputs include:
- Animated text videos
- Scene-based visual clips
- Basic AI-generated motion graphics

**Learning outcome:** Explore how generative AI can be applied to creative media and video content generation.

---

### 10. Text-to-Image Generation to Explore Transformer Capabilities in Multimodal Tasks
This assignment investigates transformer-based generative models in multimodal AI by generating images from text prompts.

The focus is on:
- Text prompt understanding
- Transformer-based multimodal generation
- Output quality and prompt variation analysis

**Learning outcome:** Study the role of transformers in cross-modal tasks involving both language and image generation.

---

## Suggested Repository Structure

```text
gen-ai-assignments/
│
├── Assignment-1-Probabilistic-Model-or-Markov/
├── Assignment-2-Prompt-Engineering/
├── Assignment-3-GPT-Finetuning-Story-Generation/
├── Assignment-4-QA-Chatbot/
├── Assignment-5-Stable-Diffusion-or-Custom-Diffusion/
├── Assignment-6-Text-to-Image-DALLE/
├── Assignment-7-Image-Captioning-CLIP/
├── Assignment-8-Text-to-Speech/
├── Assignment-9-AI-Video-Animation/
├── Assignment-10-Transformer-Multimodal-Text-to-Image/
│
├── assets/
├── requirements.txt
└── README.md
