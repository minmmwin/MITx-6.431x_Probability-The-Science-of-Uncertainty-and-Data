# 🧠 Probability — Key Concepts (MITx 6.431x)

This document summarizes key probability concepts learned in the course.  
Focus is on intuition and understanding rather than formal proofs.

---

## 📌 1. Probability Space

A probability space consists of:
- Sample space (Ω): all possible outcomes  
- Events: subsets of Ω  
- Probability measure: assigns probabilities to events  

👉 Think of it as the foundation for modeling uncertainty.

---

## 📌 2. Conditional Probability

Probability of an event given another event:

P(A | B) = P(A ∩ B) / P(B)

👉 Updates belief when new information is known.

---

## 📌 3. Independence

Two events are independent if:

P(A ∩ B) = P(A)P(B)

👉 Knowing one event does NOT change the probability of the other.

---

## 📌 4. Random Variables

A random variable maps outcomes → numbers.

Types:
- Discrete (e.g., Bernoulli, Binomial)  
- Continuous (e.g., Normal, Exponential)

👉 Converts abstract outcomes into measurable quantities.

---

## 📌 5. Expectation (Mean)

Expected value:

E[X] = average outcome over many trials  

👉 Long-run average behavior of a random variable.

---

## 📌 6. Variance

Measures spread:

Var(X) = E[(X - E[X])²]

👉 How much values deviate from the mean.

---

## 📌 7. Law of Large Numbers (LLN)

As number of samples increases:

Sample average → Expected value  

👉 Explains why averages stabilize over time.

---

## 📌 8. Central Limit Theorem (CLT)

Sum (or average) of many independent variables:

→ Approximately Normal distribution  

  Even non-normal data becomes normal when aggregated.

---

## 📌 9. Joint Distributions

Describes multiple variables together:

- Joint probability  
- Marginal distribution  
- Conditional distribution  

  Helps analyze relationships between variables.

---

## 📌 10. Covariance & Correlation

- Covariance: measures direction of relationship  
- Correlation: normalized version (between -1 and 1)

  Shows how variables move together.

---

## 📌 11. Bayes’ Theorem

P(A | B) = [P(B | A) P(A)] / P(B)

  Updates probability using new evidence.

---

## 🎯 Key Takeaway

Probability provides the mathematical framework for:
- reasoning under uncertainty  
- modeling real-world randomness  
- building foundations for statistics and machine learning  

---

## 📝 Note

- This is a simplified summary for learning purposes  
- Focus is on intuition, not formal derivations

