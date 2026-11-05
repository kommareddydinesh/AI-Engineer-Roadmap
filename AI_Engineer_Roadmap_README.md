# AI Engineer Roadmap & Learning Hub

A beginner-to-advanced, practical roadmap for learning Artificial
Intelligence, Machine Learning, Generative AI, RAG, AI Agents, and
deployment.

> **Goal:** Learn concepts, build projects, document your work, and
> publish your progress on GitHub.\
> **How to use this repository:** Follow the phases in order, tick off
> the checklist, and add your own notes and project links.

------------------------------------------------------------------------

## Table of Contents

-   [Roadmap at a glance](#roadmap-at-a-glance)
-   [Phase 1: Programming foundations](#phase-1-programming-foundations)
-   [Phase 2: Mathematics and data
    analysis](#phase-2-mathematics-and-data-analysis)
-   [Phase 3: Machine Learning](#phase-3-machine-learning)
-   [Phase 4: Deep Learning](#phase-4-deep-learning)
-   [Phase 5: NLP and Transformers](#phase-5-nlp-and-transformers)
-   [Phase 6: Generative AI and LLMs](#phase-6-generative-ai-and-llms)
-   [Phase 7: RAG and vector
    databases](#phase-7-rag-and-vector-databases)
-   [Phase 8: Knowledge Graphs and
    GraphRAG](#phase-8-knowledge-graphs-and-graphrag)
-   [Phase 9: AI Agents and agentic
    systems](#phase-9-ai-agents-and-agentic-systems)
-   [Phase 10: Deployment and MLOps](#phase-10-deployment-and-mlops)
-   [Project ideas](#project-ideas)
-   [Useful GitHub repositories](#useful-github-repositories)
-   [Interview preparation](#interview-preparation)
-   [Weekly study plan](#weekly-study-plan)
-   [Progress checklist](#progress-checklist)

------------------------------------------------------------------------

## Roadmap at a glance

1.  Python, OOP, Git, SQL
2.  Mathematics, statistics, NumPy, Pandas, visualization
3.  Supervised and unsupervised Machine Learning
4.  Neural networks, CNNs, sequence models, PyTorch
5.  NLP, tokenization, attention, Transformers
6.  Prompt engineering, LLM APIs, fine-tuning concepts
7.  Embeddings, retrieval, vector databases, RAG evaluation
8.  Knowledge graphs, graph databases, GraphRAG
9.  Tool calling, workflows, multi-agent systems
10. APIs, Docker, testing, CI/CD, monitoring and deployment

**Suggested pace:** 20--24 weeks at 2--3 focused hours per day. Adjust
the pace to your schedule; understanding and projects matter more than
speed.

## Phase 1: Programming foundations

**Learn** - Python syntax, functions, collections, exceptions and file
handling - Object-oriented programming - Virtual environments, packages
and debugging - Git and GitHub basics - SQL fundamentals

**Resources** - [Python official
tutorial](https://docs.python.org/3/tutorial/) - [Kaggle Learn --
Python](https://www.kaggle.com/learn/python) - [GitHub
Skills](https://skills.github.com/) - [SQLBolt](https://sqlbolt.com/) -
[W3Schools Python](https://www.w3schools.com/python/)

**Practice:** Build a calculator, file organizer, expense tracker and
SQL CRUD application.

## Phase 2: Mathematics and data analysis

**Learn** - Descriptive statistics, probability and distributions -
Vectors, matrices and basic linear algebra - Derivatives and gradient
intuition - NumPy, Pandas and Matplotlib - Data cleaning, missing values
and exploratory data analysis

**Resources** - [Khan Academy -- Statistics and
Probability](https://www.khanacademy.org/math/statistics-probability) -
[3Blue1Brown -- Essence of Linear
Algebra](https://www.3blue1brown.com/topics/linear-algebra) - [NumPy
Learn](https://numpy.org/learn/) - [Pandas Getting
Started](https://pandas.pydata.org/docs/getting_started/) - [Matplotlib
Tutorials](https://matplotlib.org/stable/tutorials/index.html)

**Practice:** Analyze a public dataset and publish a notebook with
charts and conclusions.

## Phase 3: Machine Learning

**Learn** - Supervised vs. unsupervised learning - Linear and logistic
regression - Decision trees, random forests and gradient boosting -
K-nearest neighbors and support vector machines - K-means clustering and
dimensionality reduction - Train/test split, cross-validation, feature
engineering - Accuracy, precision, recall, F1, ROC-AUC, MAE and RMSE -
Data leakage and overfitting

**Resources** - [Google Machine Learning Crash
Course](https://developers.google.com/machine-learning/crash-course) -
[Microsoft ML for
Beginners](https://github.com/microsoft/ML-For-Beginners) -
[Scikit-learn User
Guide](https://scikit-learn.org/stable/user_guide.html) - [Kaggle Learn
-- Intro to Machine
Learning](https://www.kaggle.com/learn/intro-to-machine-learning) -
[Kaggle Datasets](https://www.kaggle.com/datasets)

**Practice projects:** House price prediction, customer churn
prediction, spam classification and customer segmentation.

## Phase 4: Deep Learning

**Learn** - Perceptrons, neural networks and backpropagation -
Activation functions, loss functions and optimizers - CNNs for image
tasks - RNNs, LSTMs and sequence modelling - Transfer learning and
regularization - GPU training basics

**Resources** - [PyTorch Tutorials](https://pytorch.org/tutorials/) -
[fast.ai -- Practical Deep Learning](https://course.fast.ai/) - [Dive
into Deep Learning](https://d2l.ai/) - [TensorFlow
Tutorials](https://www.tensorflow.org/tutorials)

**Practice projects:** Image classifier, plant disease detection,
sentiment classifier and time-series forecasting.

## Phase 5: NLP and Transformers

**Learn** - Text preprocessing and tokenization - Word and sentence
embeddings - Attention and self-attention - Encoder, decoder and
encoder-decoder architectures - BERT-style and GPT-style models - Using
pretrained models

**Resources** - [Hugging Face NLP
Course](https://huggingface.co/learn/nlp-course/) - [The Illustrated
Transformer](https://jalammar.github.io/illustrated-transformer/) -
[Stanford CS224N](https://web.stanford.edu/class/cs224n/) - [Hugging
Face Transformers
documentation](https://huggingface.co/docs/transformers/index)

## Phase 6: Generative AI and LLMs

**Learn** - How LLMs generate text and their limitations - Prompt design
and structured outputs - API-based model integration - Context windows,
tokens and temperature - Hallucination, grounding, privacy and
responsible AI - Fine-tuning concepts and when not to fine-tune - Model
evaluation

**Resources** - [DeepLearning.AI Short
Courses](https://www.deeplearning.ai/short-courses/) - [Hugging Face
Learn](https://huggingface.co/learn) - [OpenAI API
Documentation](https://platform.openai.com/docs/) - [Prompt Engineering
Guide](https://www.promptingguide.ai/) - [LLMs from Scratch --
GitHub](https://github.com/rasbt/LLMs-from-scratch)

## Phase 7: RAG and vector databases

**Learn** - Retrieval-Augmented Generation architecture - Document
loading, chunking and metadata - Dense and sparse retrieval - Embeddings
and similarity search - Vector databases and indexing - Reranking,
citations and grounded answers - Retrieval and answer evaluation

**Resources** - [LlamaIndex
Documentation](https://docs.llamaindex.ai/) - [LangChain
Documentation](https://python.langchain.com/docs/) - [Chroma
Documentation](https://docs.trychroma.com/) - [FAISS --
GitHub](https://github.com/facebookresearch/faiss) - [Pinecone Learning
Center](https://www.pinecone.io/learn/) - [RAGAS
Documentation](https://docs.ragas.io/)

**Practice project:** Build a PDF question-answering assistant that
cites the source document and evaluates retrieval quality.

## Phase 8: Knowledge Graphs and GraphRAG

**Learn** - Nodes, relationships, properties and graph modelling -
Cypher query language - Entity and relationship extraction - Combining
graph retrieval with vector retrieval - GraphRAG architecture,
provenance and evaluation

**Resources** - [Neo4j GraphAcademy](https://graphacademy.neo4j.com/) -
[Neo4j Cypher Manual](https://neo4j.com/docs/cypher-manual/current/) -
[Microsoft GraphRAG -- GitHub](https://github.com/microsoft/graphrag) -
[Neo4j GraphRAG for
Python](https://neo4j.com/docs/neo4j-graphrag-python/current/)

**Practice project:** Build a knowledge assistant that answers questions
using both graph relationships and document passages.

## Phase 9: AI Agents and agentic systems

**Learn** - Tools and function calling - Agent state, memory and
planning - Workflow orchestration - Human approval and guardrails -
Multi-agent coordination - Tracing, evaluation and failure handling -
MCP fundamentals

**Resources** - [AI Agents for Beginners --
Microsoft](https://github.com/microsoft/ai-agents-for-beginners) -
[LangGraph
Documentation](https://docs.langchain.com/oss/python/langgraph/overview) -
[CrewAI Documentation](https://docs.crewai.com/) - [AutoGen --
GitHub](https://github.com/microsoft/autogen) - [Model Context
Protocol](https://modelcontextprotocol.io/introduction)

**Practice project:** Create an agent that researches a topic, uses
approved tools, cites sources and asks for human confirmation before
external actions.

## Phase 10: Deployment and MLOps

**Learn** - FastAPI and REST APIs - Unit and integration testing -
Docker and containers - GitHub Actions and CI/CD - Experiment tracking
and model versioning - Logging, monitoring and reproducibility - Cloud
deployment basics and secrets management

**Resources** - [FastAPI
Tutorial](https://fastapi.tiangolo.com/tutorial/) - [Docker Get
Started](https://docs.docker.com/get-started/) - [GitHub Actions
Documentation](https://docs.github.com/en/actions) - [MLflow
Documentation](https://mlflow.org/docs/latest/) - [Made With
ML](https://madewithml.com/)

------------------------------------------------------------------------

## Project ideas

  -----------------------------------------------------------------------
  Level                   Project                 Main skills
  ----------------------- ----------------------- -----------------------
  Beginner                House price prediction  Pandas, regression,
                                                  Scikit-learn

  Beginner                Spam detection          NLP, classification

  Intermediate            Solar power forecasting Time series, LSTM

  Intermediate            Image classification    CNN, PyTorch

  Intermediate            Resume analyser         LLM API, structured
                                                  output

  Advanced                PDF chatbot with        RAG, embeddings, vector
                          citations               DB

  Advanced                Research assistant      Agents, tools,
                                                  evaluation

  Advanced                Company intelligence    Knowledge Graph,
                          platform                GraphRAG, multi-agent
                                                  workflows
  -----------------------------------------------------------------------

For every project, include a clear README, dataset/source attribution,
setup instructions, screenshots or demo, evaluation results, limitations
and license information. Never upload API keys, passwords, private
datasets or personal information.

## Useful GitHub repositories

-   [Microsoft ML for
    Beginners](https://github.com/microsoft/ML-For-Beginners)
-   [Microsoft AI Agents for
    Beginners](https://github.com/microsoft/ai-agents-for-beginners)
-   [LLMs from Scratch](https://github.com/rasbt/LLMs-from-scratch)
-   [Hugging Face Course](https://github.com/huggingface/course)
-   [Prompt Engineering
    Guide](https://github.com/dair-ai/Prompt-Engineering-Guide)
-   [Microsoft GraphRAG](https://github.com/microsoft/graphrag)
-   [Made With ML](https://github.com/GokuMohandas/Made-With-ML)
-   [Scikit-learn](https://github.com/scikit-learn/scikit-learn)
-   [PyTorch](https://github.com/pytorch/pytorch)

## Interview preparation

Keep a parallel interview routine: - Python: strings, lists,
dictionaries, functions, OOP and problem solving - DSA: arrays, strings,
hashing, sorting, searching, stacks, queues, trees and dynamic
programming - SQL: joins, grouping, subqueries, CTEs and window
functions - ML: algorithm selection, metrics, overfitting, leakage and
feature engineering - AI: embeddings, transformers, RAG, agents,
evaluation and deployment - Projects: explain the problem, architecture,
your contribution, trade-offs and results

Practice: [LeetCode](https://leetcode.com/),
[HackerRank](https://www.hackerrank.com/), [NeetCode
Roadmap](https://neetcode.io/roadmap).

## Weekly study plan

  Day         Focus
  ----------- ------------------------------------
  Monday      Learn a new concept
  Tuesday     Code small examples
  Wednesday   Solve practice problems
  Thursday    Build a project feature
  Friday      Test, debug and document
  Saturday    Push work to GitHub and revise
  Sunday      Review progress and plan next week

## Progress checklist

-   [ ] Python and OOP
-   [ ] NumPy, Pandas and SQL
-   [ ] Statistics and mathematics
-   [ ] Machine Learning algorithms
-   [ ] Deep Learning and PyTorch
-   [ ] NLP and Transformers
-   [ ] Generative AI and LLMs
-   [ ] RAG and vector databases
-   [ ] Knowledge Graphs and GraphRAG
-   [ ] AI Agents and orchestration
-   [ ] FastAPI, Docker and MLOps
-   [ ] Build and document at least 3 portfolio projects
-   [ ] Prepare for AI/ML interviews

------------------------------------------------------------------------

## Contribution and updates

This is a personal learning repository. Update the checklist as you
learn, add notes in topic folders, and link your completed projects.

Suggested folder structure:

``` text
ai-engineer-roadmap/
├── README.md
├── 01-python-foundations/
├── 02-math-and-data-analysis/
├── 03-machine-learning/
├── 04-deep-learning/
├── 05-nlp-transformers/
├── 06-generative-ai/
├── 07-rag-vector-databases/
├── 08-knowledge-graphs-graphrag/
├── 09-ai-agents/
├── 10-deployment-mlops/
├── projects/
└── interview-preparation/
```

**Keep learning. Build in public. Improve one project at a time.**
