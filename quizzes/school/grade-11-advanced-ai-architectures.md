# Advanced AI Architectures and Transformers

**Category**: school
**Level**: advanced
**Topics**: transformers, attention mechanisms, BERT, GPT, advanced architectures
**Questions**: 11

---

## About This Quiz

Eleventh graders dive into modern AI architectures, focusing on Transformers and attention mechanisms. These concepts power state-of-the-art language models and computer vision systems.

---

## Questions

### Question 1
**Type**: multiple-choice
**Difficulty**: hard

**What is the transformer architecture?**

- A) A robot that changes shape
- B) A neural network architecture based on attention mechanisms, introduced in 2017
- C) An electrical device
- D) A method for changing data format

**Correct Answer**: B

**Explanation**

The Transformer architecture, introduced in the paper "Attention Is All You Need," revolutionized NLP and AI. It uses self-attention mechanisms instead of recurrent connections, allowing parallel processing and better handling of long sequences.

---

### Question 2
**Type**: true-false
**Difficulty**: hard

**Attention mechanisms allow a model to focus on relevant parts of input.**

**Correct Answer**: True

**Explanation**

Attention is a mechanism that lets neural networks focus on important parts of the input. In translation, the model attends to relevant words. In vision, it focuses on relevant image regions. Attention weights are learned during training.

---

### Question 3
**Type**: multiple-choice
**Difficulty**: hard

**What is self-attention?**

- A) Paying attention to yourself
- B) A mechanism where each element attends to other elements in the same sequence
- C) Monitoring your own performance
- D) A type of meditation

**Correct Answer**: B

**Explanation**

Self-attention allows each element in a sequence to relate to every other element. This enables the model to capture long-range dependencies. It's what makes Transformers so powerful - every word can "see" every other word.

---

### Question 4
**Type**: true-false
**Difficulty**: hard

**BERT is a pre-trained language model based on the Transformer architecture.**

**Correct Answer**: True

**Explanation**

BERT (Bidirectional Encoder Representations from Transformers) is a pre-trained Transformer model. It's trained on vast amounts of text and can be fine-tuned for specific tasks like sentiment analysis or question answering.

---

### Question 5
**Type**: multiple-choice
**Difficulty**: hard

**What does "pre-training" mean in the context of modern language models?**

- A) Training before you start
- B) Training a model on large unlabeled data for general language understanding before fine-tuning for specific tasks
- C) Training in advance of an event
- D) Initial training only

**Correct Answer**: B

**Explanation**

Pre-training involves training a large model on massive amounts of text data. The model learns general language patterns, word relationships, and knowledge. This learned knowledge can then be fine-tuned for specific downstream tasks with smaller labeled datasets.

---

### Question 6
**Type**: true-false
**Difficulty**: hard

**GPT models use Transformer decoders and are designed for text generation.**

**Correct Answer**: True

**Explanation**

GPT (Generative Pre-trained Transformer) models are decoder-only Transformers trained to generate text. They predict the next word based on previous context. GPT models are extremely good at generating human-like text, code, and following instructions.

---

### Question 7
**Type**: multiple-choice
**Difficulty**: hard

**What is the difference between BERT and GPT?**

- A) One is better than the other
- B) BERT is bidirectional (sees left and right context); GPT is unidirectional (left-to-right)
- C) BERT is older
- D) They're the same thing with different names

**Correct Answer**: B

**Explanation**

BERT uses bidirectional context (sees words before and after) and is good for understanding tasks. GPT uses unidirectional context (left-to-right) and is good for generation. Both are Transformers but designed for different purposes.

---

### Question 8
**Type**: true-false
**Difficulty**: hard

**Vision Transformers (ViTs) apply the Transformer architecture to image recognition tasks.**

**Correct Answer**: True

**Explanation**

Vision Transformers split images into patches and treat them like sequences. This allows Transformers to be applied to vision tasks. They've shown competitive or superior performance compared to CNNs on image classification.

---

### Question 9
**Type**: multiple-choice
**Difficulty**: hard

**What is an embedding in modern language models?**

- A) Code embedded in a webpage
- B) A numerical vector representation that captures semantic meaning of tokens/words
- C) Text embedded in an image
- D) A hidden layer in a neural network

**Correct Answer**: B

**Explanation**

Embeddings convert tokens (words or subwords) into high-dimensional vectors. Embeddings capture semantic relationships - similar words have similar embeddings. Token embeddings are a key component of Transformers.

---

### Question 10
**Type**: true-false
**Difficulty**: hard

**The attention mechanism in Transformers uses query, key, and value vectors.**

**Correct Answer**: True

**Explanation**

Self-attention works by computing queries, keys, and values for each element. The model learns to compute similarity between queries and keys to determine which elements to attend to, then aggregates the corresponding values.

---

### Question 11
**Type**: multiple-choice
**Difficulty**: hard

**What is prompt engineering?**

- A) Engineering that requires prompts
- B) The art and science of crafting input text to guide large language models to produce desired outputs
- C) Engineering a computer prompt
- D) Prompting engineers

**Correct Answer**: B

**Explanation**

Prompt engineering involves carefully crafting text prompts to get language models like ChatGPT to behave as desired. Good prompts can improve accuracy, creativity, and task performance. It's an important skill for working with modern AI systems.

---

## Answer Key

| Question | Answer | Difficulty |
|----------|--------|------------|
| 1        | B      | hard       |
| 2        | True   | hard       |
| 3        | B      | hard       |
| 4        | True   | hard       |
| 5        | B      | hard       |
| 6        | True   | hard       |
| 7        | B      | hard       |
| 8        | True   | hard       |
| 9        | B      | hard       |
| 10       | True   | hard       |
| 11       | B      | hard       |

---

## Scoring Guide

- **100%**: Perfect! You master advanced AI!
- **91-99%**: Excellent! You understand Transformers!
- **82-90%**: Very good! Strong architecture knowledge!
- **73-81%**: Good effort! Advanced topics are complex!
- **Below 73%**: Keep learning! These concepts are cutting-edge!

---

## Resources

- Original "Attention Is All You Need" paper
- BERT and GPT research papers
- Vision Transformer papers
- Hugging Face model tutorials
