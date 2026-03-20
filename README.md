## Causal Inference and Epidemiology for Data Scientists

Throughout my training and professional experience as a data scientist, I’ve noticed that data science often overemphasizes the power of prediction. Over the last 15+  years, we've witnessed the rise of big data, increased data availability, along with the common belief that more data leads to better predictions, and that with enough data, we should be able to solve the most pressing problems in any field, especially in areas like disease and healthcare.

So why haven’t we?

I don't think that data is the problem. There are countless large, rich datasets available. If anything, we have more data than ever before. But having data doesn’t mean that the people working with it are trained to understand the processes that generate it, or even to ask the right questions, especially when the goal is not just prediction, but real-world impact.

Part of the challenge, as alluded to in *The Premonition* by Michael Lewis, is that we tend to operate in silos. People can be very strong in their own field, yet what often slows progress is not a lack of expertise, but a lack of communication across fields that are trying to solve similar problems.

For example, epidemiologists are often trained in rigorous causal reasoning, but sometimes in more theoretical or less computationally modern frameworks, which can make it feel less approachable to data scientists interested in asking disease or health-related questions beyond prediction. Data scientists, on the other hand, are trained to combine mathematics, statistics, and machine learning within a domain, but are often taught to think of data with a two-dimensional lens:  

**X (features) → Y (outcome)**

While this paradigm is incredibly powerful for prediction, it rarely forces us to ask: *why?*

Data scientists are taught early on that correlation does not imply causation. But in the era of AI and increasingly complex models, it is easy to lose sight of that principle. Models become more powerful, data becomes more abundant, and yet the underlying assumptions, and how the data is generated, are often left unexamined.

Modern data science excels at prediction, but answering causal questions, especially with observational data, requires a different way of thinking.

This repository is meant to bridge data science and epidemiology to help data scientists move from prediction to causal reasoning in real-world data.

Ideally, this will help us think in a different way, beyond prediction:

**who → when → why → what → outcome**

---

## What you will learn

- How to think causally with observational data  
- Core epidemiologic principles (bias, confounding, study design)  
- Practical causal inference methods (propensity scores, IPW, MSMs, etc.)  
- Real-world applications using health data  

---

## Structure

1. Expanding the data science lens  
2. Asking causal questions  
3. Study design and epidemiology  
4. Causal graphs  
5. Methods  
6. Real-world applications  
7. Case studies  

---

## Goal

To provide a practical, intuitive, and applied introduction to causal inference and epidemiology for data scientists working with real-world data.
