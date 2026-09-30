# AI Job-Readiness Curriculum

## Overview

This curriculum is designed to give a learner a broad, modern foundation in AI and enough practical experience to begin building AI projects independently.

The emphasis is on **understanding concepts and learning by building**, rather than attempting to cover every topic in AI.

The curriculum progresses through:

**Python → Classical ML → Deep Learning → LLMs → Computer Vision → Generative AI → Reinforcement Learning**

Projects are placed between major stages so that each stage ends with something the learner has actually built.

---

# Stage 1 — Python

### 1. Kaggle Python Microcourse

**Time: 5 hours**

Complete the Kaggle Python Microcourse.

Topics include:

* Variables
* Conditionals
* Loops
* Functions
* Lists
* Dictionaries
* Tuples
* Sets
* Comprehensions
* Imports and libraries
* Basic object-oriented programming
* Reading and writing files
* Debugging

### Project 1 — Python Game

**Make a simple game of your choice in Python. A CLI-based game is enough.**

Examples include:

* Hangman
* Tic-Tac-Toe
* Blackjack
* Number guessing
* Quiz game

The learner should make their own design and implementation choices.

The project should demonstrate:

* Functions
* Appropriate data structures
* Input handling
* Error handling
* Clean, readable Python

No AI/ML is required.

---

# Stage 2 — Classical Machine Learning

### 2. Kaggle Intro to Machine Learning

**Time: 3 hours**

Topics:

* Data exploration
* Model training
* Model validation
* Decision Trees
* Random Forests
* Regression
* MAE
* Underfitting
* Overfitting

The learner should understand the basic ML workflow:

**Data → Explore → Train → Validate → Evaluate → Diagnose**

### 3. Kaggle Pandas Microcourse

**Time: 4 hours**

Topics:

* Creating DataFrames
* Reading and writing data
* Indexing and selecting
* Assigning values
* Summary functions
* Maps
* Grouping
* Sorting
* Data types
* Missing values
* Renaming
* Combining data

### 4. Kaggle Intermediate Machine Learning

**Time: 4 hours**

Topics:

* Missing-value handling
* Categorical variables
* Pipelines
* Cross-validation
* XGBoost
* Data leakage

### Project 2 — Classical ML Competition

**Make your own submission to the Kaggle Home Prices Prediction Competition, or a similar beginner-friendly ML competition.**

The learner should independently go through:

**Explore → Preprocess → Train → Validate → Evaluate → Improve**

They should be able to explain:

* Their preprocessing decisions
* Their choice of models
* Their evaluation metric
* Their validation strategy
* What experiments they performed
* What they learned from the results

---

# Stage 3 — Deep Learning

### 5. NumPy — Absolute Beginners Guide

**Time: 2 hours**

Use the official NumPy beginner guide.

Topics:

* Multidimensional arrays
* Dimensions and axes
* Shape
* Size
* Data types
* Indexing and slicing
* Reshaping
* Vectorized operations

### 6. 3Blue1Brown — Neural Networks

**Time: 2 hours**

Watch:

1. But what is a neural network?
2. Gradient descent, how neural networks learn
3. Backpropagation, intuitively
4. Backpropagation calculus

The goal is to develop an intuitive understanding of:

* Neural networks
* Parameters
* Loss
* Gradient descent
* Backpropagation

### 7. PyTorch — Learn the Basics

**Time: 4 hours**

Complete the official beginner sequence:

* Quickstart
* Tensors
* Datasets and DataLoaders
* Transforms
* Build Model
* Automatic Differentiation
* Optimization Loop
* Save, Load and Use Model

### Project 3 — PyTorch Classification

**Make a handwritten digit recognizer, or a similar classification model of your choice, using PyTorch.**

The learner should build the training pipeline themselves, including:

* Dataset/DataLoader
* Model
* Loss function
* Optimizer
* Training loop
* Validation
* Evaluation

They should also perform at least some experimentation with the model or training process and explain what they changed and why.

---

# Stage 4 — NLP, Transformers and LLMs

### 8. 3Blue1Brown — Modern NLP and LLM Concepts

**Time: 1.5 hours**

Watch:

* Large Language Models explained briefly
* Chapter 5: Transformers, the tech behind LLMs
* Chapter 6: Attention in transformers, step-by-step
* Chapter 7: How might LLMs store facts

Topics:

* Large language models
* Transformers
* Attention
* Embeddings
* How information can be represented inside LLMs

### 9. Andrej Karpathy — Let's Build GPT

**Time: 4 hours**

**Let's build GPT: from scratch, in code, spelled out**

Follow along with the implementation.

The project progresses from a simple bigram language model toward a Transformer/GPT-style model and ends with a character-level model trained on Tiny Shakespeare.

### 10. Local AI Agent with Python

**Time: 1.5 hours**

Build a local AI application using:

* Ollama
* LangChain
* RAG
* Local LLMs
* Agents

The goal is to move from understanding LLMs to actually using them in applications.

### 11. LangGraph

**Time: 3 hours**

Learn:

* LangGraph fundamentals
* Graph-based workflows
* Chatbots
* Graph visualization
* More complex agentic workflows

### 12. Hugging Face + LoRA Fine-Tuning

**Time: 2.5 hours**

Learn how to fine-tune a pretrained LLM using Hugging Face, PyTorch, PEFT and LoRA.

Topics:

* Prompting
* Dataset creation
* Input-output pairs
* Loss functions
* PyTorch optimizers
* Transformers
* PEFT
* LoRA
* Fine-tuning
* Evaluation

### Project 4 — Knowledge Assistant

**Make a chatbot that can assist users with research papers, documentation, books, or a knowledge domain of your choice.**

The learner should determine how to build it.

They should consider:

* How knowledge is provided to the chatbot
* Retrieval
* RAG
* Which LLM to use
* How information is incorporated
* How sources are handled
* How the system should be evaluated

The project should go beyond simply reproducing a tutorial.

---

# Stage 5 — Computer Vision

### 13. Kaggle Computer Vision Microcourse

**Time: 4 hours**

Topics:

* Convolutional classifiers
* Convolution + ReLU
* Maximum pooling
* Sliding windows
* Stride and padding
* Custom convolutional networks
* Data augmentation

### 14. Learn Modern Computer Vision in 2026: From Basics to Advanced

**Time: 5 hours**

Topics include:

* OpenCV fundamentals
* Image processing
* Video processing
* Face detection
* Hand detection
* Pose detection
* Object detection
* Custom object detection
* OCR
* Semantic segmentation
* Image inpainting
* Practical computer vision projects

### Project 5 — Vision-Controlled Game

**Build a game that tracks the facial expressions or hand gestures of the user.**

The learner should decide how to implement it.

Possible directions include:

* Gesture-controlled games
* Face-controlled Pong
* Rock-paper-scissors
* Gesture-controlled racing
* Hand-controlled Flappy Bird

The technical approach is deliberately left open. The learner can research and decide whether to use tools such as OpenCV, MediaPipe, pretrained models, or their own model.

---

# Stage 6 — Generative AI

### 15. How Do AI Images and Videos Actually Work?

**Time: 1 hour**

Watch the Welch Labs guest video.

Topics:

* CLIP
* Shared embedding spaces
* Diffusion models
* DDPM
* Learning vector fields
* DDIM
* DALL-E 2
* Conditioning
* Guidance
* Negative prompts

The purpose is to develop a conceptual understanding of modern generative image and video systems.

No implementation is required.

---

# Stage 7 — Reinforcement Learning

### 16. Kaggle — Intro to Game AI and Reinforcement Learning

**Time: 4 hours**

Topics:

1. Play the game
2. One-step lookahead
3. N-step lookahead
4. Deep reinforcement learning

The course provides a compact introduction to:

* Game-playing agents
* Search
* Lookahead
* Reinforcement learning
* Deep reinforcement learning

---

# Curriculum Time

| Stage                  | Learning | Project        |
| ---------------------- | -------: | -------------- |
| Python                 |       5h | Project 1      |
| Classical ML           |      11h | Project 2      |
| Deep Learning          |       8h | Project 3      |
| NLP / LLMs             |      12h | Project 4      |
| Computer Vision        |       9h | Project 5      |
| Generative AI          |       1h | —              |
| Reinforcement Learning |       4h | —              |
| **Total**              |  **50h** | **5 projects** |

The learning content itself is approximately **50 hours**, excluding project time.

---

# Project Portfolio

The five projects progressively reduce the amount of hand-holding:

### Project 1 — Python Game

**Can you program?**

### Project 2 — Kaggle ML Competition

**Can you solve a problem using data and machine learning?**

### Project 3 — PyTorch Classifier

**Can you build and train a neural network?**

### Project 4 — Knowledge Assistant

**Can you build a useful modern AI application?**

### Project 5 — Vision-Controlled Game

**Can you independently apply AI to an interactive problem?**

For every project, the learner should ideally maintain a README containing:

* What was built
* Problem being solved
* Approach
* Experiments
* Results
* Limitations
* Possible improvements

This makes the projects useful as portfolio pieces rather than merely course exercises.

---

# Appendices

## Appendix A — Topics Deliberately Not Included

The curriculum intentionally does not attempt to cover every important AI topic.

### Feature Engineering

The Kaggle Feature Engineering course covers:

* Mutual information
* Creating features
* Clustering with K-means
* Principal Component Analysis
* Target encoding

It is useful, but was omitted from the required curriculum to keep the learning path compact.

### Traditional NLP Progression

The curriculum does not separately cover:

* N-grams
* Word2Vec
* RNNs
* LSTMs

Modern Transformer/LLM material is introduced directly, with simpler language-model concepts appearing naturally during the GPT-from-scratch implementation.

### AI Engineering / Deployment

Topics such as:

* Git/GitHub
* FastAPI
* Docker
* Cloud deployment
* Kubernetes
* Terraform
* CI/CD
* MLOps

are not included as a separate learning stage.

These are better learned while deploying an actual project, where the engineering requirements have a concrete purpose.

### Statistics and Probability

Statistics and probability are important foundations for machine learning, but a dedicated statistics curriculum was not added because of the time constraint. The learner can deepen these topics as required by later projects or study.

---

## Appendix B — Learning Philosophy

The curriculum follows:

**Learn → Build → Learn → Build**

Each project comes immediately after a coherent group of concepts.

The learner should not simply reproduce tutorial projects. Tutorials provide the knowledge and tools; the projects require the learner to make their own decisions.

As the curriculum progresses, the learner should become increasingly independent:

**Follow instructions → Make choices → Design systems → Research independently → Build independently**

---

## Appendix C — What This Curriculum Covers

The curriculum provides exposure to:

* Python
* NumPy
* Pandas
* Classical machine learning
* Regression
* Classification
* Decision Trees
* Random Forests
* XGBoost
* Cross-validation
* Pipelines
* Data leakage
* Missing-value handling
* Categorical variables
* Neural networks
* Gradient descent
* Backpropagation
* PyTorch
* CNNs
* Computer vision
* Transformers
* Attention
* LLMs
* GPT
* RAG
* Agents
* LangGraph
* Hugging Face
* LoRA
* Fine-tuning
* Diffusion models
* CLIP
* Reinforcement learning
* Deep reinforcement learning

It is intended as a **broad AI foundation**, not as a specialization in any single subfield.

---

## Appendix D — What Comes After the Curriculum

After completing the curriculum and projects, the learner should move toward **independent projects, specialization, and job-oriented development**.

At that point, areas such as deployment, software engineering, cloud infrastructure, MLOps, advanced model architectures, research papers, or specialized AI domains can be learned according to the projects and roles they pursue.
