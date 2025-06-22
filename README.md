# group_22_formative_3 contribution

## 1. James Jok Dut Akuei

### Manual Gradient Descent Implementation
I implemented and explained the first iteration of gradient descent using gradient descent formulas, computing predictions, and MSE step-by-step.

### Visualization
I created clear Matplotlib plots to show how the slope (m), intercept (b), and error (MSE) changed over iterations.

### Optimization Using SciPy
I used SciPy’s minimize() function with BFGS method and a custom callback to track and print updates during optimization.

## 2. Mariam Issah
 I implemented and explained the Exponential Distribution in Python using the scenario David gave in the group discussion.  

### Exponential Distribution

## Real World Example
In this assignment, we are given four questions, and my group has to tackle one question at a time to make sure that everyone understands what we are doing. Suppose each group member takes on average 2 hours to fully understand and complete their assigned question. The time taken to understand a question varies, but follows a random and independent pattern.
 What is the probability that a group member completes a question in 1 hour or less?
 
We assumed that, on average, a member takes 60 minutes (1 hours) to complete a question. This gives a rate λ = 2 per hour. We implemented the PDF and CDF formulas manually and visualized them using Matplotlib.

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
