# group_22_formative_3 contribution

## 1. James Jok Dut Akuei

### Manual Gradient Descent Implementation
I implemented and explained the first iteration of gradient descent using gradient descent formulas, computing predictions, and MSE step-by-step.

### Visualization
I created clear Matplotlib plots to show how the slope (m), intercept (b), and error (MSE) changed over iterations.

### Optimization Using SciPy
I used SciPy’s minimize() function with BFGS method and a custom callback to track and print updates during optimization.

## 2. Mariam Issah

### Exponential Distribution

## Real World Example
We were given four major tasks to complete, and as a group, we shared these tasks among ourselves, tackling one question at a time. Before starting any coding or calculations, we all took the time to understand what each part of the assignment was about. Since every group member works at a different pace, the time it takes each person to finish their part varies.

We assumed that, on average, a member takes 30 minutes (0.5 hours) to complete a question. This gives a rate λ = 2 per hour. We implemented the PDF and CDF formulas manually and visualized them using Matplotlib.

PDF (
𝑓
(
𝑥
)
=
𝜆
𝑒
−
𝜆
𝑥
f(x)=λe 
−λx
 ) shows that quicker completions are more likely.

CDF (
𝐹
(
𝑥
)
=
1
−
𝑒
−
𝜆
𝑥
F(x)=1−e 
−λx
 ) shows the growing chance of completion over time.

The exponential process is useful here because it models the time between independent events (question completions) and assumes a memoryless process — how long we've been working doesn't affect how soon we finish.

This helped us understand how the distribution works in real life and how to code and visualize it from scratch.

## 3. Innocente Aline

In this section, I demonstrate Bayesian inference using a COVID-19 testing scenario:

### Problem Definition  
   Estimate the probability that a person truly has COVID-19 given a positive test result.

### Model Setup
   - Prior (Prevalence): 2% of the population is infected  
   - Sensitivity: 90% true positive rate  
   - Specificity: 95% true negative rate

### Bayesian Update Steps  
   1. Marginal Probability of a Positive Test  
      Combine the probabilities of positive results from both infected and uninfected groups.  
   2. Posterior Probability  
      Use Bayes’ theorem to update the prior with the observed positive result, yielding the probability of infection given a positive test (~26.9%).   

### Practical Significance  
   - Highlights how low prevalence leads to a high proportion of false positives  
   - Shows the importance of integrating prior knowledge (prevalence) with test accuracy  
   - Illustrates the general power of Bayesian inference to update beliefs based on new evidence

## 4. David zuokumor 

### Debugging and Explanation
I analyzed the differences between manual and SciPy-based approaches and explained key mathematical concepts like gradient signs and the role of x in updates.
