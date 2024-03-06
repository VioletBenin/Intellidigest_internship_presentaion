---

author: Beining Xu
title: IntelliDigest Weekly Meeting
date: Feb 26, 2024

---

<link rel="stylesheet" href="../reveal.js/dist/reveal.css">
<link rel="stylesheet" href="../reveal.js/dist/theme/sky.css">  

# IntelliDigest Weekly Meeting

Author: Beining Xu

Date: 28 Feb 2024

---

# Two Papers

- African soil properties and nutrients mapped at 30 m spatial resolution using two‐scale ensemble machine learning

- Earth Observation Data-Driven Cropland Soil Monitoring: A Review

--- 



African *soil properties and nutrients mapped* at 30 m spatial resolution using two‐scale ensemble machine learning

<!-- African * *soil properties and nutrients mapped* *  -->

# *Overview*

---

# Goals



---

# Methodolgy




---

# Two‐scale ensemble machine learning

Using two set of Fine-grained and Coarse-grained Level to build the model

## How it works?

- Using 2 diffrent scale to 

- For example, 

using about 350 covariate layers available at 250 m resolution—mainly climatic/atmospheric images—and 
some 60 layers—mainly EO data and DTM derivatives—at 30 m.

This partitioning helped to speed up processing so that production time remained comparable to e.g. producing the global predictions at 250 m21.

##

- Complexity and Computation Cost 
- Accuracy Improvement 
- Robustness Against Overfitting 


---

# Implement

## Feature Selection and Model Selection


<!-- 
---


$$
y(S_B) = S_4(S_B) + S_3(S_B) + S_2(S_B) + S_1(S_B) + \varepsilon
$$

---

$$
\hat{y}(S_B) = \frac{\sum_{i=1}^{2} w_i \cdot S_i(S_B)}{\sum_{i=1}^{2} w_i}, \quad w_i = \frac{1}{\sigma^2_{i,CV}}
$$


y(φ, θ, d) = d + x1(φ, θ) + x2(φ, θ) + · · · + Xp(φ, θ)

--- -->

 Random Forest, XGBoost, deepnet, Cubist and GLM-net

---
<!-- 
# What we got

---

Earth Observation Data-Driven Cropland Soil Monitoring: A Review

# *Overview*



---

# Similarity

**with two papers**

---

1. 
1. 
1. 

---

# Comparation
with two papers

---

|  | Soil Monitoring    | nutrients mapping |
| -------- | -------- | ------- |
| Methodolgy | January  | $250    |
| February | $80     | $250    |
| March    | $420    | $250    |

--- -->