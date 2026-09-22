# Data Science, ML & AI Mastery

A structured, practical, math-backed GitHub curriculum designed to progress from classical Machine Learning to modern AI, LLMs, MLOps, system design, and production projects.

## Learning method

Every major concept follows:

**Theory → Mathematics → Visualization → From-scratch implementation → Industry implementation → Real dataset → Evaluation → Comparison → Interview preparation**

## Curriculum

### 01 — Regression
Linear, Multiple and Polynomial Regression; Ridge, Lasso, Elastic Net; train/validation/test splits; cross-validation; MAE, MSE, RMSE, R², adjusted R², MAPE; residual analysis and assumptions. Math: vectors, matrices, dot products, derivatives, gradients, least squares, normal equation, gradient descent.

### 02 — Classification
Logistic Regression, KNN, Naive Bayes, Decision Trees, Random Forest, SVM. Sigmoid, log-odds, cross-entropy, Bayes theorem, Gini, entropy, information gain, hinge loss, margins, probability prediction and thresholds.

### 03 — Model Evaluation & Feature Engineering
Confusion matrix, precision, recall, specificity, F1, F-beta, ROC-AUC, PR-AUC, log loss, calibration and threshold tuning. Missing data, categorical encoding, scaling, outliers, transformations, feature creation/selection, pipelines, ColumnTransformer, leakage prevention and class imbalance.

### 04 — Ensemble & Advanced Machine Learning
Bagging, Extra Trees, AdaBoost, Gradient Boosting, XGBoost, LightGBM, CatBoost, stacking, Grid/Random/Bayesian/Optuna hyperparameter optimization and model comparisons.

### 05 — Unsupervised Learning
K-Means, Hierarchical Clustering, DBSCAN, GMM, PCA, t-SNE, UMAP and anomaly detection with Isolation Forest, One-Class SVM, LOF and autoencoders.

### 06 — Practical Data Science
Time-series analysis and forecasting; recommendation systems; explainable AI; advanced statistics, multicollinearity, VIF, heteroscedasticity, bootstrap and causal-inference fundamentals.

### 07 — Deep Learning Foundations
Perceptrons, neurons, forward pass, loss, backpropagation, computational graphs, chain rule, activations, losses, optimizers, learning-rate scheduling and regularization.

### 08 — PyTorch
Tensors, shapes, broadcasting, CPU/GPU, autograd, computational graphs, nn.Module, Dataset, DataLoader, training/validation loops, checkpoints and transfer learning.

### 09 — Computer Vision
Image tensors, convolution, kernels, stride, padding, feature maps, pooling and receptive fields. LeNet, AlexNet, VGG, Inception, ResNet, EfficientNet, MobileNet, transfer learning and augmentation.

### 10 — Advanced Computer Vision
Object detection, bounding boxes, IoU, precision/recall, mAP, NMS, R-CNN family, SSD, YOLO, semantic/instance segmentation, U-Net, U-Net++ and Mask R-CNN.

### 11 — Natural Language Processing
Tokenization, normalization, stopwords, stemming, lemmatization, POS, n-grams, one-hot, BoW, TF-IDF, Naive Bayes, Linear SVM, Word2Vec, CBOW, Skip-gram, negative sampling, GloVe and cosine similarity.

### 12 — Sequence Models
Sequence data, RNNs, hidden states, BPTT, vanishing/exploding gradients, LSTM gates, GRU gates and sequence generation.

### 13 — Attention & Transformers
Encoder-decoder attention, Q/K/V, attention scores, softmax, context vectors, self-attention, scaled dot-product attention, multi-head attention, residuals, LayerNorm, FFN, positional encoding, masks and Transformer architectures.

### 14 — BERT & Modern NLP
BERT, bidirectional attention, token/position/segment embeddings, special tokens, MLM, NSP, fine-tuning, DistilBERT, RoBERTa, ALBERT and DeBERTa.

### 15 — Hugging Face
Transformers, tokenizers, pipelines, AutoTokenizer, AutoModel, task-specific models, datasets, Trainer, fine-tuning, inference and Hub workflows.

### 16 — LLM Fundamentals
BPE/tokenization, embeddings, Transformer blocks, decoder-only models, causal attention, autoregressive next-token prediction, context windows, KV cache, pretraining, instruction tuning, SFT, RLHF, preference optimization and generation strategies.

### 17 — LLM Engineering
Prompt engineering, zero-shot/few-shot prompting, templates, system instructions, structured outputs, JSON/Pydantic validation, tool/function calling, APIs and LLM application architecture.

### 18 — Retrieval-Augmented Generation
Document extraction/OCR, cleaning, chunking, metadata, embeddings, cosine similarity, FAISS, pgvector, HNSW, IVF, BM25, hybrid retrieval, query expansion, reranking, metadata filters, parent-child retrieval and RAG evaluation.

### 19 — LangChain & LLM Frameworks
LangChain prompts, models, chains, LCEL, retrievers, loaders, vector stores, parsers, tools and agents; LlamaIndex ingestion, indexing and retrieval. RAG is first built without a framework, then with frameworks.

### 20 — Fine-Tuning & Model Optimization
SFT, instruction-tuning datasets, evaluation, PEFT, LoRA, QLoRA, adapters, quantization, distillation, pruning and model compression.

### 21 — AI Agents
Tool calling, agent loops, planning, state, memory, ReAct, workflows, autonomous and multi-agent systems, permissions, retries, timeouts, cost, observability, evaluation and security.

### 22 — Data Engineering for ML
PostgreSQL, data modeling, normalization, indexes, ETL/ELT, ingestion, transformation, validation, scheduling, dbt, Airflow and data-quality checks.

### 23 — MLOps
ML lifecycle, experiment tracking, model versioning/registry, MLflow, Docker, FastAPI, CI/CD, batch/real-time inference, serving, monitoring, drift and retraining.

### 24 — Cloud & Deployment
Compute, storage, databases, networking, IAM, containers and cloud ML services, with one cloud provider studied deeply enough for practical deployment.

### 25 — Advanced Data Science
Causal inference, advanced recommendation systems, advanced anomaly detection, A/B testing, sequential testing, CUPED and guardrails.

### 26 — Graph Machine Learning
Graphs, nodes, edges, adjacency matrices, graph embeddings, message passing, GCN, GAT, GraphSAGE and MPNN, with fraud, recommendation, social, knowledge-graph and molecular applications.

### 27 — Multimodal AI
Vision Transformers, CLIP-style models, vision-language models, image embeddings, multimodal LLMs, image+text RAG, document AI and OCR+LLM workflows.

### 28 — AI/ML System Design
Recommendation, fraud, search, RAG, real-time/batch prediction and LLM applications; latency, throughput, scalability, caching, queues, feature stores, serving and monitoring.

### 29 — Responsible AI & AI Security
Bias, fairness, explainability, privacy, leakage, adversarial examples, prompt injection, jailbreaks, poisoning, model security, RAG security and PII handling.

### 30 — Real-World Projects
1. E-commerce Business Analytics
2. House Price Prediction
3. Customer Churn Prediction
4. Customer Segmentation
5. Demand Forecasting
6. Visual Quality Inspection
7. Customer Support Intelligence
8. Production RAG System
9. End-to-End ML Platform
10. Final AI/ML Capstone

### 31 — Interview Preparation
Python coding, data manipulation, OOP and debugging; SQL from beginner to advanced; statistics; ML algorithm theory/math/assumptions/failure cases; ML case studies and ML/LLM system design.

## Repository structure

Each major section is a folder. As we work through the curriculum, sections can contain:

```
topic/
├── README.md
├── theory.md
├── mathematics.md
├── from_scratch.py
├── implementation.py
├── visualization.ipynb
├── practical_example.ipynb
├── comparison.md
└── interview_questions.md
```

Not every small concept needs every file.

## Progression

**Regression → Classification → Model Evaluation → Feature Engineering → Ensemble ML → Unsupervised Learning → Practical Data Science → Deep Learning → Computer Vision → NLP → Attention → Transformers → BERT → LLMs → LLM Engineering → RAG → LangChain → Fine-Tuning → Agents → Data Engineering → MLOps → Cloud → Advanced AI/ML → System Design → Final Capstone**

Current structuring work is being done on `structuring-repo-bychatgpt`.

## Goal

Build genuine understanding and implementation ability, not just a collection of copied notebooks: strong mathematics, practical coding, real datasets, comparisons, production thinking, projects and interview readiness.
