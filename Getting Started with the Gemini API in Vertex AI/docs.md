# Getting Started with the Gemini API in Vertex AI

## 📖 Overview

This Provides a hands-on introduction to using the **Gemini API** within **Vertex AI**. You'll interact with the **Gemini 2.0 Flash model** using the Vertex AI SDK for Python, generating content from a variety of input types (text, images, and video) and learning to configure features to tailor the results.

---

## 🧠 About Gemini

### 🔹 Gemini
Gemini is a family of **generative AI models** developed by **Google DeepMind**, capable of understanding and generating:
- Text
- Code
- Images
- Audio
- Video

### 🔹 Gemini Models
- **Gemini Pro**: Best for complex reasoning, summarization, and multimodal analysis.
- **Gemini Flash**: Optimized for speed and cost-efficiency. Supports:
  - Sub-second response times
  - Enhanced spatial and multimodal understanding
  - Output in text, images, and audio
  - Integration with tools like Google Search and code execution

### 🔹 Gemini API in Vertex AI
The API provides a **unified interface** for interacting with Gemini models via Google Cloud, making it easy to integrate powerful AI into your applications.

---

## ✅ Prerequisites

Before starting the lab, you should be familiar with:
- Basic Python
- General API concepts
- Running notebooks in Vertex AI Workbench

---

## 🎯 Objectives

In this lab, you will learn to:
- Use the Gemini API with the Vertex AI SDK for Python
- Work with the `gemini-2.0-flash` model
- Generate text from text, image, and video prompts
- Explore configuration options (e.g., streaming, safety filters, etc.)

---

## 📂 Tasks Overview

### Task 1: Open Notebook in Vertex AI Workbench
- Navigate to Workbench > Open JupyterLab
- Choose Python 3 kernel
- Run setup cells (`Getting Started`, `Import libraries`)
- Set `Project ID` and `Region`

---

### Task 2: Use Gemini 2.0 Flash for Text Generation

#### 🔸 Generate from Text Prompts
Use `generate_content()` to send prompts and receive completions.

#### 🔸 Streaming Responses
Get real-time generation using the streaming feature.

#### 🔸 Try Your Own Prompts
Test custom prompts with different configurations.

#### 🔸 Safety Filters
Configure content safety levels and inspect response ratings.

#### 🔸 Test Chat Prompts
Enable multi-turn conversations (chatbot-style).

---

### Task 3: Generate Text from Multimodal Inputs

#### 🖼️ Text + Local Image
Generate responses by combining image files and text.

#### 🖼️ Text + Image URLs
Use web-hosted images in your prompts.

#### 🧠 Few-Shot Prompting with Multiple Images
Combine multiple examples (images + text) to guide the model.

#### 🎥 Text + Video
Provide a video file as input for analysis.

#### 🌐 Public Web Media
Analyze publicly hosted multimedia URLs directly.

---

## 🧩 Key Methods & Concepts

- `generate_content()` – core method for generating responses
- **Multimodal prompts** – blend text, images, and videos
- **Streaming** – get responses in real time
- **Safety filters** – ensure appropriate outputs
- **Few-shot prompting** – guide the model with examples

---

## 🏁 Completion Checklist

✔ Generate text from prompt  
✔ Use streaming responses  
✔ Create multimodal prompts  
✔ Adjust safety settings  
✔ Use custom and chat-based prompts  
✔ Analyze video and image inputs  

---

## 📚 Reference

- [Gemini API Documentation (Google Cloud)](https://cloud.google.com/vertex-ai/docs/generative-ai/overview)
- [Vertex AI SDK Reference](https://cloud.google.com/python/docs/reference/aiplatform/latest)

---
