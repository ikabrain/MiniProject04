# 📝 Mini Project 04 - ComboFinder
> **Course**: [Thapar's Machine Learning Summer School, 2025](https://www.thaparsummerschool.com/)
> 
> **Student Name**: Ikansh Mahajan
>
> **Student Roll No.**: 102303754

## 🔎 Problem Statement
Find the list of products whose sum of prices is between a lower and upper bound.

![image](https://user-images.githubusercontent.com/7460892/173579493-d718c024-4844-4c30-afd5-71bd641a49d0.png)

## 🔬 Solution
```mermaid
---
title: Random Approach
---
flowchart TD
K[Select a random length of subset 'k'] --> A[Select a random set of size 'k']
A --> B[Calculate sum]
B --> C{If sum is within lower and upper bounds}
C -- Yes --> D[Save set in list]
C -- No --> E{Termination Condition}
D --> E
E -- Yes --> F[/Return list of sets/]
E -- No --> K
```

## 🚀 How to Run Notebook
Click on the  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab">  button on top of the notebook to open it in Google Colab and experiment with my solution by copying it to your Drive.

![07 57 08 PM](https://github.com/user-attachments/assets/e65efa6e-aa6b-45a3-a5e4-c11ea84ecb99)

## 🧾 Reflections
This assignment gave me a hands-on exposure to:
- Randomisation in Python
- Clean notebook structuring
- Writing Pythonic and optimized code
- Mathematical reasoning and edge case handling
- GitHub handling

## ⚠️ Report Issues
Create an issue ticket using the `Issues` section up above.
