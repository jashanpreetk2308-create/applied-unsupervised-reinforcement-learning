# Applied Unsupervised & Reinforcement Learning

A practical implementation of **Unsupervised Learning** and **Reinforcement Learning** with a focus on real-world business applications.

This project demonstrates how machine learning can be used to identify customer segments and support decision-making through reward-based learning.

## 📌 Project Overview

This repository contains a Google Colab practical covering two major machine learning concepts:

* **Unsupervised Learning** — Customer segmentation using K-Means Clustering
* **Reinforcement Learning** — Route selection using rewards, exploration, and exploitation

The practical is designed to connect machine learning concepts with **business decision-making and real-world applications**.

## 🚀 Key Concepts

### 1. Customer Segmentation — K-Means Clustering

K-Means clustering is used to divide customers into **3 groups** based on:

* Monthly Spending
* App Visits

The model identifies customers with similar behavioural patterns and assigns them to different clusters.

The clusters can then be interpreted from a business perspective, such as:

* Premium Customers
* Medium-Value Customers
* Low-Engagement Customers

Possible business actions include loyalty rewards, personalized recommendations, and re-engagement campaigns.

### 2. Reinforcement Learning — Route Optimization

The second part introduces the basic concept of Reinforcement Learning through a delivery-route scenario.

A delivery system chooses between:

* Route A
* Route B

Each route produces different rewards based on delivery performance. The system can use these rewards to identify which route performs better.

The practical demonstrates the fundamental components:

| Component   | Example                       |
| ----------- | ----------------------------- |
| Agent       | Delivery decision system      |
| Environment | Roads and traffic             |
| Action      | Choosing Route A or Route B   |
| Reward      | Delivery performance feedback |

## 🔍 Exploration vs Exploitation

The project also demonstrates the difference between:

**Exploration**
Trying a new or less-used option to gather more information.

**Exploitation**
Choosing an option that is already known to perform well.

For example, the system may explore Route A even when Route B has historically performed better, or exploit the known better-performing Route B.

## 🛠️ Technologies Used

* Python
* Pandas
* Matplotlib
* Scikit-learn
* Google Colab
* K-Means Clustering

The notebook uses Pandas for dataset handling, Scikit-learn's K-Means implementation for clustering, and Matplotlib for visualization.

## 📂 Project Structure

```text
applied-unsupervised-reinforcement-learning/
│
├── part-a/
│   └── unsupervised-learning/
│       ├── Unsupervised_and_Reinforcement_Learning_Practical_Name.ipynb
│       └── customer-segmentation.png
│
└── README.md
```

The practical specifies placing the notebook under `part-a/unsupervised-learning/` and adding a screenshot of the customer-segmentation graph.

## 📊 Machine Learning Comparison

| Learning Type          | Main Idea                      | Business Application      |
| ---------------------- | ------------------------------ | ------------------------- |
| Supervised Learning    | Learn from known answers       | Customer churn prediction |
| Unsupervised Learning  | Discover hidden patterns       | Customer segmentation     |
| Reinforcement Learning | Learn from actions and rewards | Route optimization        |

## 🎯 Learning Outcomes

After completing this practical, the learner can:

* Understand customer segmentation using K-Means.
* Identify behavioural patterns within customer groups.
* Interpret clustering results from a business perspective.
* Understand the basic concept of Reinforcement Learning.
* Identify an Agent, Action, Environment, and Reward.
* Understand Exploration and Exploitation.
* Connect machine learning techniques with business applications.

## 💼 Business Applications

The concepts demonstrated in this project can support business use cases such as:

* Customer segmentation
* Personalized marketing
* Customer re-engagement
* Loyalty programs
* Delivery route optimization
* Decision-making based on historical rewards

## ▶️ How to Run

1. Open the `.ipynb` notebook in **Google Colab** or Jupyter Notebook.
2. Run the cells sequentially.
3. Review the K-Means clustering output.
4. Analyze the customer-segmentation visualization.
5. Run the Reinforcement Learning examples.
6. Compare exploration and exploitation behaviour.
7. Review the final business interpretation.

## 📈 Expected Outcome

The K-Means section produces customer groups based on spending and app activity, while the Reinforcement Learning section demonstrates how reward feedback can influence route selection.

The overall objective is to understand **how different machine learning approaches can solve different types of business problems**.

## 👤 Author

**[Your Name]**

BBA Student | Business & Data Analytics | Artificial Intelligence & Machine Learning

---

⭐ *This project was developed as part of a practical learning exercise in Machine Learning and its business applications.*
