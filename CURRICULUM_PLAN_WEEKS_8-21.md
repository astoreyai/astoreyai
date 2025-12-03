# 100 Days of ML: Weeks 8-21 Curriculum Plan

**Status**: PLANNING
**Created**: December 2025
**Target**: 70 lessons (Lessons 36-105) across 14 weeks

---

## Current State (Complete)

| Week | Topic | Lessons |
|------|-------|---------|
| 0 | Preface/Overview | Overview, Challenges, Resources |
| 1 | Python Basics | 1-5 |
| 2 | ML Mathematics | 6-10 |
| 3 | Data Preprocessing | 11-15 |
| 4 | EDA/Visualization | 16-20 |
| 5 | Supervised - Regression | 21-25 |
| 6 | Supervised - Classification | 26-30 |
| 7 | Ensemble Methods | 31-35 |

---

## Planned Curriculum (Weeks 8-21)

### Week 8: Unsupervised Learning - Clustering (Lessons 36-40)

| Lesson | Title | Key Concepts |
|--------|-------|--------------|
| 36 | Introduction to Clustering | Unsupervised learning, cluster analysis, applications |
| 37 | K-Means Clustering | Algorithm, initialization, k selection |
| 38 | Hierarchical Clustering | Agglomerative, divisive, dendrograms |
| 39 | DBSCAN and Density-Based Methods | Density clustering, noise handling, OPTICS |
| 40 | Cluster Evaluation | Silhouette score, elbow method, Davies-Bouldin |

**Datasets**: Customer segmentation, image compression, document clustering

---

### Week 9: Dimensionality Reduction (Lessons 41-45)

| Lesson | Title | Key Concepts |
|--------|-------|--------------|
| 41 | Introduction to Dimensionality Reduction | Curse of dimensionality, feature extraction |
| 42 | Principal Component Analysis (PCA) | Eigenvalues, variance explained, implementation |
| 43 | t-SNE for Visualization | Perplexity, manifold learning, interpretation |
| 44 | UMAP | Topology preservation, hyperparameters |
| 45 | Practical Dimensionality Reduction | Pipelines, combining with clustering |

**Datasets**: MNIST, Fashion-MNIST, high-dimensional biological data

---

### Week 10: Model Selection & Hyperparameter Tuning (Lessons 46-50)

| Lesson | Title | Key Concepts |
|--------|-------|--------------|
| 46 | Cross-Validation Techniques | K-fold, stratified, leave-one-out |
| 47 | Grid Search | Exhaustive search, parameter grids |
| 48 | Random Search & Bayesian Optimization | Efficient search, Optuna/Hyperopt |
| 49 | Pipeline Construction | sklearn pipelines, preprocessing chains |
| 50 | Experiment Tracking | MLflow basics, logging, reproducibility |

**Tools**: scikit-learn, Optuna, MLflow

---

### Week 11: Introduction to Neural Networks (Lessons 51-55)

| Lesson | Title | Key Concepts |
|--------|-------|--------------|
| 51 | Perceptrons and Activation Functions | Biological inspiration, sigmoid, ReLU |
| 52 | Forward Propagation | Matrix operations, layer composition |
| 53 | Backpropagation | Chain rule, gradient computation |
| 54 | Multi-Layer Perceptrons | Architecture design, hidden layers |
| 55 | PyTorch Fundamentals | Tensors, autograd, nn.Module |

**Datasets**: XOR problem, MNIST, simple classification

---

### Week 12: Deep Learning Fundamentals (Lessons 56-60)

| Lesson | Title | Key Concepts |
|--------|-------|--------------|
| 56 | Loss Functions | MSE, cross-entropy, custom losses |
| 57 | Optimizers | SGD, momentum, Adam, learning rate |
| 58 | Regularization Techniques | Dropout, batch normalization, weight decay |
| 59 | Training Deep Networks | Vanishing gradients, initialization, scheduling |
| 60 | Transfer Learning Basics | Pretrained models, feature extraction |

**Tools**: PyTorch, TensorBoard

---

### Week 13: Convolutional Neural Networks (Lessons 61-65)

| Lesson | Title | Key Concepts |
|--------|-------|--------------|
| 61 | CNN Architecture | Convolutions, filters, feature maps |
| 62 | Pooling and Stride | Max pooling, average pooling, receptive field |
| 63 | Building CNNs for Image Classification | LeNet-style architecture, CIFAR-10 |
| 64 | Popular Architectures | VGG, ResNet, skip connections |
| 65 | Data Augmentation & Fine-Tuning | Transforms, pretrained models, torchvision |

**Datasets**: CIFAR-10, CIFAR-100, custom image datasets

---

### Week 14: Recurrent Neural Networks (Lessons 66-70)

| Lesson | Title | Key Concepts |
|--------|-------|--------------|
| 66 | Sequence Data and RNN Basics | Sequential patterns, hidden states |
| 67 | LSTM Networks | Gates, long-term dependencies |
| 68 | GRU and Bidirectional RNNs | Simplified gating, bidirectional processing |
| 69 | Text Preprocessing for RNNs | Tokenization, padding, vocabularies |
| 70 | Sentiment Analysis Project | End-to-end text classification |

**Datasets**: IMDB reviews, Twitter sentiment

---

### Week 15: NLP Fundamentals (Lessons 71-75)

| Lesson | Title | Key Concepts |
|--------|-------|--------------|
| 71 | Text Preprocessing Deep Dive | Cleaning, stemming, lemmatization |
| 72 | Word Embeddings | Word2Vec, GloVe, embedding layers |
| 73 | Text Classification Techniques | Bag-of-words, TF-IDF, neural approaches |
| 74 | Named Entity Recognition | Sequence labeling, BIO tagging |
| 75 | Topic Modeling | LDA, coherence, interpretation |

**Tools**: NLTK, spaCy, Gensim

---

### Week 16: Transformers and Attention (Lessons 76-80)

| Lesson | Title | Key Concepts |
|--------|-------|--------------|
| 76 | Attention Mechanism | Self-attention, query-key-value |
| 77 | Transformer Architecture | Encoder-decoder, positional encoding |
| 78 | BERT Introduction | Masked language modeling, [CLS] token |
| 79 | HuggingFace Transformers | Pipeline API, model hub |
| 80 | Fine-Tuning BERT | Classification head, training loop |

**Tools**: HuggingFace Transformers, Datasets

---

### Week 17: Generative Models (Lessons 81-85)

| Lesson | Title | Key Concepts |
|--------|-------|--------------|
| 81 | Autoencoders | Encoder-decoder, latent space |
| 82 | Variational Autoencoders | Latent distribution, reparameterization |
| 83 | Introduction to GANs | Generator, discriminator, adversarial training |
| 84 | GAN Variants | DCGAN, conditional GANs |
| 85 | Generative AI Ethics | Deepfakes, bias, responsible use |

**Datasets**: CelebA, MNIST generation

---

### Week 18: Reinforcement Learning Basics (Lessons 86-90)

| Lesson | Title | Key Concepts |
|--------|-------|--------------|
| 86 | RL Fundamentals | Agent, environment, reward, policy |
| 87 | Markov Decision Processes | States, actions, transitions, value functions |
| 88 | Q-Learning | Action-value function, exploration-exploitation |
| 89 | Deep Q-Networks | Neural Q-function, experience replay |
| 90 | OpenAI Gym Projects | CartPole, Atari basics |

**Tools**: Gymnasium (OpenAI Gym), Stable-Baselines3

---

### Week 19: Time Series Analysis (Lessons 91-95)

| Lesson | Title | Key Concepts |
|--------|-------|--------------|
| 91 | Time Series Fundamentals | Stationarity, trends, seasonality |
| 92 | ARIMA Models | AR, MA, differencing, forecasting |
| 93 | Seasonal Decomposition | Trend, seasonal, residual components |
| 94 | Prophet for Forecasting | Facebook Prophet, holiday effects |
| 95 | Neural Networks for Time Series | LSTM forecasting, multivariate |

**Datasets**: Stock prices, weather data, energy consumption

---

### Week 20: MLOps and Production (Lessons 96-100)

| Lesson | Title | Key Concepts |
|--------|-------|--------------|
| 96 | Model Serialization | Pickle, joblib, ONNX export |
| 97 | Building ML APIs | FastAPI, request handling |
| 98 | Docker for ML | Containerization, reproducibility |
| 99 | Model Monitoring | Drift detection, performance tracking |
| 100 | CI/CD for ML | Testing, automation, deployment |

**Tools**: FastAPI, Docker, GitHub Actions

---

### Week 21: Capstone Projects (Lessons 101-105)

| Lesson | Title | Project Focus |
|--------|-------|---------------|
| 101 | Capstone 1: Classification Pipeline | End-to-end tabular ML |
| 102 | Capstone 2: NLP Application | Text classification or NER |
| 103 | Capstone 3: Computer Vision | Image classification or object detection |
| 104 | Capstone 4: Time Series | Forecasting application |
| 105 | Portfolio Presentation | Documentation, GitHub, demo |

---

## Development Priority

### Phase 1: Foundation (Weeks 8-10)
- Unsupervised learning completes classical ML
- Model selection is critical practical skill
- Lower complexity, builds on existing content

### Phase 2: Neural Networks (Weeks 11-14)
- Natural progression to deep learning
- PyTorch as primary framework
- Practical focus with CNNs and RNNs

### Phase 3: Advanced Topics (Weeks 15-19)
- NLP and Transformers (high demand)
- Generative models and RL
- Time series (practical applications)

### Phase 4: Production & Capstones (Weeks 20-21)
- MLOps is essential for career readiness
- Capstones demonstrate comprehensive skills

---

## Implementation Notes

### Each Lesson Should Include:
1. **Learning Objectives** (3-5 bullet points)
2. **Theory Section** (~500-1000 words with visuals)
3. **Code Implementation** (working notebook)
4. **Exercise** (practice problem)
5. **Challenge** (advanced application)
6. **Resources** (papers, tutorials, docs)

### Technical Requirements:
- Google Colab compatible
- GPU-optional (fallback to CPU where possible)
- Datasets < 100MB (or downloaded programmatically)
- Clear package versions specified

### Style Guidelines:
- Consistent with Weeks 1-7 format
- Same naming convention (Lesson_XX.ipynb)
- Dual attribution: Aaron S. & John M.
- MIT License

---

## Estimated Effort

| Phase | Weeks | Lessons | Est. Hours |
|-------|-------|---------|------------|
| Phase 1 | 8-10 | 15 | 30-45 |
| Phase 2 | 11-14 | 20 | 50-70 |
| Phase 3 | 15-19 | 25 | 60-80 |
| Phase 4 | 20-21 | 10 | 25-35 |
| **Total** | **14** | **70** | **165-230** |

---

## Next Steps

1. [ ] Review plan with co-author (John M.)
2. [ ] Set up Week 8 directory structure
3. [ ] Create template notebook
4. [ ] Begin Lesson 36 (K-Means introduction)
5. [ ] Establish weekly publication schedule
