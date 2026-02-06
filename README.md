

# 🟢 LEVEL 1: NORMAL (FOUNDATION — “I GET IT”)

## 1. What is Probability?

Probability = **measure of uncertainty**

[
P(A) = \frac{\text{Number of favourable outcomes}}{\text{Total outcomes}}
]

Values always lie between **0 and 1**.

* 0 → impossible
* 1 → certain

---

## 2. Sample Space & Events

* **Sample Space (S)**: All possible outcomes
* **Event (A)**: A subset of S

Example:
Toss a coin
[
S = {H, T}
]
Event A = “Head”

---

## 3. Types of Events

* **Simple event**: one outcome
* **Compound event**: multiple outcomes
* **Impossible event**: ∅
* **Certain event**: S

---

## 4. Complement of an Event

If A is an event, then
[
P(A') = 1 - P(A)
]

Example:
Probability of NOT getting head = 1 − P(H)

---

## 5. Classical Probability (Equal Likelihood)

Used when outcomes are equally likely.

Example: Dice
[
P(rolling\ 3) = \frac{1}{6}
]

---

## 6. Basic Rules

* (0 \le P(A) \le 1)
* (P(S) = 1)
* (P(\emptyset) = 0)

---

## 7. Mutually Exclusive Events

Events that **cannot happen together**.

[
P(A \cup B) = P(A) + P(B)
]

Example: Getting 2 or 5 on a dice.

---

## 8. Non-Mutually Exclusive

[
P(A \cup B) = P(A) + P(B) - P(A \cap B)
]

---

## 9. Independent vs Dependent

* **Independent**: one does not affect the other
* **Dependent**: outcome changes probabilities

Independent:
[
P(A \cap B) = P(A)P(B)
]

---

That’s enough to **clear exams**.

---

# 🔵 LEVEL 2: TOPPER LEVEL (EXAM DESTROYER)

Now we sharpen the weapons.

---

## 10. Conditional Probability

Key formula:

[
P(A|B) = \frac{P(A \cap B)}{P(B)}
]

Meaning: probability of A **given that B has occurred**.

👉 Most mistakes in exams happen here.

---

## 11. Bayes’ Theorem (FAVOURITE EXAM QUESTION)

[
P(A_i|B) = \frac{P(B|A_i)P(A_i)}{\sum P(B|A_j)P(A_j)}
]

Used in:

* Medical testing
* Faulty machines
* Truth/lie problems

💡 **Topper trick**:
Always **draw a tree diagram first**.

---

## 12. Total Probability Theorem

If events (A_1, A_2, ..., A_n) partition S:

[
P(B) = \sum P(B|A_i)P(A_i)
]

---

## 13. Random Variable

A function assigning numbers to outcomes.

* Discrete → finite/countable
* Continuous → infinite

---

## 14. Probability Distribution

For discrete random variable X:

| x | P(X=x) |
| - | ------ |

Conditions:

* (P(X=x) \ge 0)
* (\sum P(X=x) = 1)

---

## 15. Mean, Variance, SD

[
E(X) = \sum xP(X=x)
]

[
Var(X) = E(X^2) - [E(X)]^2
]

---

## 16. Standard Distributions

Know these **cold**:

### (a) Binomial Distribution

Conditions:

* Fixed number of trials
* Two outcomes
* Constant probability

[
P(X=r) = \binom{n}{r} p^r q^{n-r}
]

---

### (b) Poisson Distribution

Rare events.

[
P(X=r) = \frac{e^{-\lambda}\lambda^r}{r!}
]

Mean = Variance = λ

---

### (c) Normal Distribution

Bell curve.

[
f(x) = \frac{1}{\sigma\sqrt{2\pi}}e^{-\frac{(x-\mu)^2}{2\sigma^2}}
]

Use **Z-score**:
[
Z = \frac{X-\mu}{\sigma}
]

---

## 17. Expectation Properties

* (E(aX+b) = aE(X)+b)
* Used in games, fairness, gambling problems

---

This level = **top 10% scorer**.

---

# 🔴 LEVEL 3: ULTRA-TOPPER / RANKER LEVEL (PAPER BREAKER)

Now we think like examiners.

---

## 18. Counting Before Probability

Probability = Counting / Total outcomes
So **combinatorics is king**.

* Permutations
* Combinations
* Arrangements with restrictions

🔥 Ranker trick:
**Always count indirectly** (complement method).

---

## 19. Conditional Independence

[
P(A \cap B | C) = P(A|C)P(B|C)
]

Used in advanced Bayes problems.

---

## 20. Law of Large Numbers

As trials → ∞,
Experimental probability → Theoretical probability.

---

## 21. Common Hidden Traps

* “At least one” → use complement
* “Given that” → conditional probability
* Replacement vs No replacement
* Independence wrongly assumed

---

## 22. Symmetry Arguments

Used in Olympiad-style problems.

Example:
Probability a random chord is longer than radius → symmetry beats calculation.

---

## 23. Expectation Without Distribution

Linearity of expectation:

[
E(X+Y) = E(X) + E(Y)
]

Even if X, Y are dependent.

🔥 **This wins impossible-looking problems**.

---

## 24. Random Variables as Indicators

Let:
[
I =
\begin{cases}
1, & \text{if event occurs} \
0, & \text{otherwise}
\end{cases}
]

Used to find:

* Expected number of successes
* Matches, derangements, birthdays

---

## 25. Advanced Bayes Intuition

Bayes ≠ formula
Bayes = **belief update**

Prior → Evidence → Posterior

Rankers explain answers in **words**, not math.

---

## 26. How Rankers Practice

* Solve fewer problems
* But **analyze mistakes deeply**
* Ask: *Why did this work?*
* Create **counter-examples**

---

## 27. Mental Checklist Before Answering

✔ What is given?
✔ What is asked?
✔ Conditional or unconditional?
✔ Replacement or not?
✔ Independent or not?
✔ Can I use complement?

---

## 28. Ranker Mindset

> Probability is not calculation.
> It is **controlled reasoning under uncertainty**.

