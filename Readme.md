# JSON Extraction Engine – Fine-Tuned LLM Project

##  Project Overview

This project builds and fine-tunes a Large Language Model (LLM) to act as a **JSON Extraction Engine**.

The model is trained to:
- Take natural language queries
- Extract structured information
- Return responses strictly formatted as JSON objects

The training dataset is synthetically generated across multiple structured knowledge domains such as:
- Capital of countries
- Currency of countries
- Population of cities
- Famous landmarks
- Color conversion (RGB → Hex)
- Simple math operations
- Programming language features
- Animal classification
- Famous quote authors

The model is fine-tuned using **Supervised Fine-Tuning (SFT)** with Hugging Face Transformers and TRL.

---

##  Project Architecture

1. Synthetic Dataset Generation  
2. Instruction Formatting  
3. Supervised Fine-Tuning (SFT)  
4. Model Saving  
5. Interactive Inference

---

##  Project Workflow

###  Synthetic Data Generation

The project dynamically generates training examples using Python.

Each example contains:
- **Input:** Natural language question
- **Output:** Structured JSON response

Example:

Input:
