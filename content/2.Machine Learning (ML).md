# 🧠 **Machine Learning (ML)**

## 🔹 Definition:

**Machine Learning** is a subset of Artificial Intelligence (AI) that enables a system to **learn patterns from data** and **make predictions or decisions** without being explicitly programmed for every rule.
![[WhatsApp Image 2025-10-12 at 18.42.20_83a32672.jpg]]

---

## ⚙️ **How ML Training Works (Step-by-Step)**

1. **Collect Data** → Gather input data (like images, text, numbers).  
    _Example:_ Housing prices dataset with area, location, and price.
    
2. **Preprocess Data** → Clean data (remove nulls, convert text to numbers).  
    _Standardization_ (scaling values) is often done because  
    ➤ If features have large differences (e.g., area = 1500 vs. price = 10,00,000),  
    then models may give more importance to large-valued features.  
    So we scale all values to a similar range (like 0–1).
    
3. **Split Data** → Divide data into:
    
    - **Training Set (e.g., 80%)** → Used to train the model.
        
    - **Testing Set (e.g., 20%)** → Used to check how well the model performs on unseen data.
        
4. **Train the Model** → The algorithm learns the relationship between input (X) and output (Y).
    
5. **Test & Evaluate** → Use metrics like **accuracy, precision, recall, RMSE** etc.  
    _Example:_ Model predicts housing price with 92% accuracy.
    

---

## 🧩 **Types of Machine Learning**

### **1️⃣ Supervised Learning**

Model learns from **labeled data** (data with both input and output values known).  
The goal is to **predict or classify** future data.

#### ✴ Categories:

|Category|Description|Example|
|---|---|---|
|**Regression**|Predicts **continuous numerical values**|Predicting house prices, temperature, sales|
|**Classification**|Predicts **discrete categories**|Spam (Yes/No), disease detection (Positive/Negative)|

#### 🔹 Example – **Regression Model**

👉 _Linear Regression / Logistic Regression_

- **Linear Regression:** Predicts continuous output.  
    _Example:_ Predicting house prices based on area and location.
    
- **Logistic Regression:** Used for classification (outputs 0 or 1).  
    _Example:_ Predict if an email is spam (1) or not spam (0).
    

🧠 _The model learns the relationship between inputs (features) and output using training data and adjusts parameters to minimize error._

---

### **2️⃣ Unsupervised Learning**

Model learns **without labeled data** — it finds **patterns or groupings** on its own.

|Technique|Description|Example|
|---|---|---|
|**Clustering**|Groups similar data points|Customer segmentation, market analysis|
|**Association**|Finds relationships between variables|“People who bought X also bought Y” – e-commerce recommendation systems|

#### 🔹 Example – **Recommendation System**

- Netflix recommends movies similar to what you’ve watched.
    
- The model groups users or movies based on viewing patterns **without labels**.
    

---

### **3️⃣ Reinforcement Learning**

Model **learns by interacting with the environment** and **receiving rewards or penalties** for actions — just like humans learn from trial and error.

|Concept|Description|Example|
|---|---|---|
|**Agent**|Learner or decision-maker|Self-driving car software|
|**Environment**|The system it interacts with|Roads, traffic, signals|
|**Reward**|Feedback from environment|Safe drive = +10, crash = -100|

#### 🔹 Example – **Autonomous Cars**

- The car (agent) observes surroundings, makes decisions (accelerate, brake),  
    and learns over time which actions **maximize total rewards (safe driving)**.
    

---

## 🧾 **Quick Summary Table**

|Type of Learning|Data Type|Output Type|Example|
|---|---|---|---|
|**Supervised**|Labeled data|Known output|Predicting prices, spam detection|
|**Unsupervised**|Unlabeled data|Unknown output (patterns)|Customer segmentation, recommendations|
|**Reinforcement**|Environment interaction|Learn best actions via reward|Self-driving cars, games (Chess, Go)|

---

✅ **In short:**

> Machine Learning is the process of teaching computers to learn from examples — by training on data, identifying patterns, and improving with experience.



