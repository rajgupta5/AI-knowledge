# AI-knowledge

1. Quantum Machine Learning (QML)
![Quantum Machine Learning](https://pbs.twimg.com/media/EewLcVLXYAIripy?format=jpg&name=medium)
- AWS Bracket (a quantum computing infrastructure)
- Azure Quantum service
- Tensoflow Quantum

2. Semi-Supervised Learning
- Imagine that you need to classify documents but you want to give your algorithm a hint about how to build the categories. 
- You want to use only a small portion of labeled documents because not every document is labeled. 
- At the same time, you want your model to classify the unlabeled documents as accurately as possible based on the ones that are already labeled.
- Typically, this combination consists of a very small amount of labeled data and a very large amount of unlabeled data. 
- We group similar data using an unsupervised learning algorithm and then use the existing labeled data to label the rest of the unlabeled data


3. Model Serving


4. MLFlow


5. Meta Machine Learning
- dozens of learning paradigms that sit between "supervised" and "unsupervised" learning
- based on learning to learn 
- The Model-Agnostic Meta-Learning (MAML) technique explores how meta-learning can be ubiquitously applied to incredibly diverse deep learning models
- Comet.ml is a Platform for Meta Machine Learning (GitHub of machine learning)


6. Data Labeling
- Supervised learning models need labeled datasets for training, and those are expensive to create and maintain
- Labeling text datasets is different from labeling images, and that is different from labeling video or audio
- platforms such as Labelbox, Snorkel.ai, and Scale AI drive innovation into the space
- Snorkel Flow is a Platform to Unlock the Training Data Bottleneck in Machine Learning (https://www.snorkel.ai/)
- Labelbox is a Data Labeling Platform for your Machine Learning Models



7. Machine Teaching
- machine teaching is conceptually simple and based on the creation of intelligent models that can teach other models
- given a set of machine learning models, a dataset, and a target task; determine the most efficient teachers to optimize the learning process
- https://arxiv.org/abs/1912.07768 (Uber proposes a technique known as generative teaching networks (GTNs) to accelerate the training and evaluation of machine learning models.)
![Machine Teaching](https://cdn.substack.com/image/fetch/c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2F48b3d14e-bfe6-436c-bb81-4ba98cc3a4a4_696x355.png)


8. Reinformcement Learning
- Acme: A new framework for distributed reinforcement learning


9. Unsupervised Data Augmentation
- technique for addressing the challenges of training semi-supervised learning models with small labeled datasets.



10 NLP
- Researchers at Google have developed a new deep-learning model called [BigBird](https://www.infoq.com/news/2020/09/google-bigbird-nlp/?utm_source=notification_email&utm_campaign=notifications&utm_medium=link&utm_content=content_in_followed_topic&utm_term=daily) that allows Transformer neural networks to process sequences up to 8x longer than previously possible
- After OPENAI GPT2 1.5 billion followed by Microsoft’s Turing-NLG, which processed 17 billion parameters and OPENAI GPT3 175 billion parameters models , Microsoft announced a new release of its DeepSpeed framework (which powers Turing-NLG), which can train a model with up to a trillion parameters
- Above is a consequence of  Factors : Computation Power and Parallelization techniques
- GPT-3 Falls Short in Machine Comprehension


11. Bayesian Neural Networks
- are a type of machine learning structure that combines neural networks and stochastic modeling in the form of a probabilistic model
- One of the key goals of BNNs is to address some of the limitations neural networks have in scenarios of uncertainty around the parameters or structure of the network
- In traditional neural networks, you have fixed weights and biases that determine how an input is transformed into an output
- However, the results of this approach are limited in many scenarios dealing with uncertainty



12. Fair ML
- DeepMind presents the case for using a method known as Causal Bayesian Networks (CBN) to measure unfairness in datasets and machine learning models. 


13. MLOPS (machine learning operations)
- MLOps is becoming a key component of the lifecycle of machine learning models
- TFX(Tensorflow Extended) is Google’s Vision for Managing the Lifecycle of Machine Learning Models


14. Graph Neural Networks
- Graph neural networks (GNNs) is an area of deep learning that focuses on the creation of neural networks that operate efficiently in graph data structures
- Deep Graph Library (DGL) is one of the most complete open-source offerings on the current market


# Cool AI Tech releases
- DeText : LinkedIn open-sources DeText, a flexible framework for different natural language understanding tasks
- TransCoder : Facebook AI Research open-sources TransCoder, a framework that uses self-supervised learning to translate code between different programming languages
- Google open-sourced Media Pipe Iris, a new machine learning model for iris estimation, which is essential in many vision analysis applications
- PyTorch Lightning is a Keras of PyTorch
- Pyro is one of the most recent additions to the world of probabilistic programming languages and one that is being used to power statistical workflows at Uber
- [Model Zoo](https://modelzoo.dev/) : Deploying the initial machine learning model is only part of the challenge -- maintaining it can be just as hard. Model Zoo gives you the tools to diagnose, improve, and seamlessly update your model endpoints
