![ml road map](assets/road_map.png)

<p align="center">
  <a href="https://github.com/loganthorneloe/ml-road-map">
    <img src="https://img.shields.io/github/stars/loganthorneloe/ml-road-map?style=social" alt="Star on GitHub">
  </a>
  <a href="https://aiforswes.com">
    <img src="https://img.shields.io/badge/Subscribe-More%20learning%20resources-orange?style=social&logo=substack" alt="Get all resources from AI for Software Engineers">
  </a>
  <a href="https://twitter.com/loganthorneloe">
    <img src="https://img.shields.io/twitter/follow/loganthorneloe?style=social" alt="Follow on X">
  </a>
  <a href="https://youtube.com/@loganthorneloe">
    <img src="https://img.shields.io/youtube/channel/subscribers/UC3H55I0SqNKQgJU77LsFiBw?style=social&logo=youtube" alt="Subscribe on YouTube">
  </a>
</p>

# Machine Learning Road Map

Your free guide to learning ML and AI. Streamlined—one or two high-quality resources per topic.

```mermaid
graph LR
    subgraph Foundation
        PREREQ[📚 Prerequisites]
    end

    subgraph Learning
        ML[🧠 ML Fundamentals]
    end

    subgraph Building
        AIE[🤖 AI Engineering]
        MLE[🔧 ML Engineering]
    end

    subgraph Ethics
        ETH[⚖️ Ethics]
    end

    PREREQ --> ML
    ML --> AIE
    ML --> MLE
    MLE --> AIE

    style PREREQ fill:#e1f5fe
    style ML fill:#fff3e0
    style AIE fill:#e8f5e9
    style MLE fill:#e8f5e9
    style ETH fill:#fce4ec
```

| Section | What You'll Learn |
|---------|-------------------|
| 📚 [**Prerequisites**](./prerequisites/) | Python, math, and dev tools you need before starting ML |
| 🧠 [**Machine Learning Fundamentals**](./ml-fundamentals/) | Core concepts, deep learning, RL, computer vision, NLP, and LLMs |
| 🤖 [**AI Engineering**](./ai-engineering/) | Build AI products: prompts, agents, RAG, evals |
| 🔧 [**ML Engineering**](./ml-engineering/) | Take models to production: data pipelines, MLOps, deployment |
| ⚖️ [**Responsible AI**](./ethics/) | Ethics, explainability, and building systems people can trust |

## 📖 Interview Prep

- 📘 Elements of Programming Interviews in [Python](https://www.amazon.com/Elements-Programming-Interviews-Python-Insiders/dp/1537713949/) / [Java](https://www.amazon.com/Elements-Programming-Interviews-Java-Insiders/dp/1517671272/) / [C++](https://www.amazon.com/Elements-Programming-Interviews-Insiders-Guide/dp/1479274836/)
- 📘 System Design Interview by Alex Xu - [Volume 1](https://www.amazon.com/System-Design-Interview-insiders-Second/dp/B08CMF2CQF/) and [Volume 2](https://www.amazon.com/System-Design-Interview-Insiders-Guide/dp/1736049119/)
- 📋 [Study Plan for ML Interviews](https://github.com/khangich/machine-learning-interview) by Khang Pham

## 🖥️ Free Compute Resources

| Resource | What You Get |
|----------|--------------|
| 🥇 [Google Colab](https://colab.google/) | Free T4/P100 GPUs, easiest to start |
| 🥇 [Kaggle Notebooks](https://www.kaggle.com/code) | 30 hours/week of P100/T4 GPU |
| [Lightning AI](https://lightning.ai/) | 22 GPU hours free |
| [Google Cloud](https://cloud.google.com/gpu) | $300 free credits |
| [Amazon SageMaker](https://aws.amazon.com/machine-learning/accelerate-machine-learning-P3/) | Free tier available |
| [Paperspace Gradient](https://www.paperspace.com/notebooks) | Free community tier |

---

**Subscribe to [AI for Software Engineers](https://aiforswes.com/)** for more resources.

**Support the creators!** Many of these resources took hundreds of hours to make. Buy the books, leave reviews, follow the authors.

**Questions?** [Message me on X](https://x.com/loganthorneloe)
