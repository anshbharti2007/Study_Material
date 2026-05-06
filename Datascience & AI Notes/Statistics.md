# 0. Big idea: What is Probability?

**Probability = chance of something happening.**

Examples:

- Chance of getting head when tossing a coin = $\frac{1}{2}$
- Chance of getting 6 when rolling a die = $\frac{1}{6}$
- Chance of rain tomorrow = maybe $0.30$ or $30\%$

Probability is always between:

$$
0 \leq P(A) \leq 1
$$

Meaning:

- $0$ = impossible
- $1$ = sure/certain
- $0.5$ = $50\%$ chance

**Key Takeaway:** Probability quantifies uncertainty. It ranges from 0 (impossible) to 1 (certain).

---

# 1. Data, Statistics and Probability

## 1.1 Deterministic pattern

A **deterministic** situation gives the same result every time.

Example:

If you heat water to $100^\circ C$ at normal pressure, it boils.

No randomness.

**Key Takeaway:** Deterministic events are predictable and repeatable.

---

## 1.2 Random-like pattern

A **random** situation does not give the same result every time.

Example:

- Tossing a coin: Head or Tail
- Rolling a die: $1, 2, 3, 4, 5, 6$
- Marks of students in an exam

We cannot know the exact result before doing it, but we can study the chances.

**Key Takeaway:** Random events are unpredictable but can be analyzed using probability.

---

# 2. Basic Probability Words

## 2.1 Experiment

An **experiment** is any action whose result is uncertain.

Examples:

- Tossing a coin
- Rolling a die
- Drawing a card
- Selecting a student from a class

**Key Takeaway:** Experiments are the foundation of probability analysis.

---

## 2.2 Outcome

An **outcome** is one possible result of an experiment.

Example:

Experiment: Toss a coin  
Possible outcomes: $\{\text{Head}, \text{Tail}\}$

Experiment: Roll a die  
Possible outcomes: $\{1, 2, 3, 4, 5, 6\}$

**Key Takeaway:** Outcomes are the building blocks of sample spaces.

---

## 2.3 Sample Space

The **sample space** is the set of all possible outcomes.

It is usually written as:

$$
S
$$

Example 1: Toss one coin

$$
S = \{H, T\}
$$

Example 2: Roll one die

$$
S = \{1,2,3,4,5,6\}
$$

Example 3: Toss two coins

$$
S = \{HH, HT, TH, TT\}
$$

Important: Sample space means **everything that can happen**.

**Key Takeaway:** The sample space represents all possible outcomes of an experiment.

---

# 3. Events

An **event** is a group of outcomes we are interested in.

Example:

Roll a die.

$$
S = \{1,2,3,4,5,6\}
$$

Event A: getting an even number

$$
A = \{2,4,6\}
$$

Event B: getting number greater than 4

$$
B = \{5,6\}
$$

So event = subset of sample space.

**Key Takeaway:** Events are subsets of the sample space that we analyze.

---

# 4. Occurrence of an Event

An event occurs if the actual result is inside that event.

Example:

Roll a die.

Event A = even number

$$
A = \{2,4,6\}
$$

If result is $4$, event A occurred.  
If result is $5$, event A did not occur.

**Key Takeaway:** An event occurs when the outcome matches the event's criteria.

---

# 5. Complement of an Event

Complement means **not happening**.

If event A is “getting even number,” then complement of A is “not getting even number.”

Symbol:

$$
A^c \quad \text{or} \quad A'
$$

Example:

$$
S = \{1,2,3,4,5,6\}
$$

$$
A = \{2,4,6\}
$$

$$
A^c = \{1,3,5\}
$$

Formula:

$$
P(A^c) = 1 - P(A)
$$

Simple meaning:

Chance of not A = 1 - chance of A.

**Key Takeaway:** Complements represent the opposite of an event.

---

# 6. Combining Events

There are two important ways to combine events.

---

## 6.1 Union: A or B

Union means **A happens or B happens or both happen**.

Symbol:

$$
A \cup B
$$

Read as: A union B

Example:

Roll a die.

$$
A = \{2,4,6\}
$$

even number

$$
B = \{5,6\}
$$

greater than 4

Then:

$$
A \cup B = \{2,4,5,6\}
$$

Because these outcomes are in A or B.

**Key Takeaway:** Union combines all outcomes from both events.

---

## 6.2 Intersection: A and B

Intersection means **both A and B happen**.

Symbol:

$$
A \cap B
$$

Read as: A intersection B

Example:

$$
A = \{2,4,6\}
$$

$$
B = \{5,6\}
$$

Then:

$$
A \cap B = \{6\}
$$

Because 6 is in both A and B.

**Key Takeaway:** Intersection identifies outcomes common to both events.

---

# 7. Disjoint Events

Two events are **disjoint** if they cannot happen together.

That means:

$$
A \cap B = \emptyset
$$

Example:

Roll a die.

A = getting even number

$$
A = \{2,4,6\}
$$

B = getting odd number

$$
B = \{1,3,5\}
$$

They have nothing common.

So A and B are disjoint.

**Key Takeaway:** Disjoint events cannot happen together.

---

# 8. Partition

A **partition** means dividing the sample space into separate non-overlapping parts.

Example:

Roll a die.

$$
S = \{1,2,3,4,5,6\}
$$

Odd numbers:

$$
A = \{1,3,5\}
$$

Even numbers:

$$
B = \{2,4,6\}
$$

A and B together cover the whole sample space, and they do not overlap.

So A and B form a partition.

**Key Takeaway:** A partition divides the sample space into non-overlapping parts.

---

# 9. De Morgan’s Laws

These laws help with “not” statements.

## Law 1

$$
(A \cup B)^c = A^c \cap B^c
$$

Meaning:

Not A or B = not A and not B.

Simple English:

If neither A nor B happened, then A did not happen and B did not happen.

---

## Law 2

$$
(A \cap B)^c = A^c \cup B^c
$$

Meaning:

Not A and B = not A or not B.

Simple English:

If both A and B did not happen together, then at least one of them did not happen.

---

# 10. Venn Diagram

A Venn diagram uses circles to show events.

- Rectangle = sample space
- Circle A = event A
- Circle B = event B
- Overlap = A and B
- Everything outside circle A = not A

Very useful for understanding union/intersection/complement.

---

# 11. Probability

Probability of event A:

$$
P(A) = \frac{\text{Number of favourable outcomes}}{\text{Total number of outcomes}}
$$

Only use this formula when all outcomes are equally likely.

Example:

Roll a fair die.

Event A = getting even number

$$
A = \{2,4,6\}
$$

Number of favourable outcomes = 3  
Total outcomes = 6

$$
P(A) = \frac{3}{6} = \frac{1}{2}
$$

---

# 12. Basic Probability Rules

## Rule 1

$$
P(S) = 1
$$

The probability of the whole sample space is 1.

Something from the sample space must happen.

---

## Rule 2

$$
P(\emptyset) = 0
$$

Impossible event has probability 0.

---

## Rule 3

$$
0 \leq P(A) \leq 1
$$

Probability cannot be negative and cannot be more than 1.

---

## Rule 4: Complement Rule

$$
P(A^c) = 1 - P(A)
$$

Example:

If probability of passing is $0.8$, probability of failing is:

$$
1 - 0.8 = 0.2
$$

---

## Rule 5: Addition Rule

For any two events:

$$
P(A \cup B) = P(A) + P(B) - P(A \cap B)
$$

Why subtract?

Because the common part is counted twice.

If A and B are disjoint:

$$
P(A \cap B) = 0
$$

So:

$$
P(A \cup B) = P(A) + P(B)
$$

---

# 13. Distribution

A **distribution** tells how probability is spread among outcomes.

Example:

Fair die:

| Outcome | Probability |
|---|---|
| 1 | 1/6 |
| 2 | 1/6 |
| 3 | 1/6 |
| 4 | 1/6 |
| 5 | 1/6 |
| 6 | 1/6 |

This is a probability distribution.

---

# 14. Uniform Distribution

Uniform means all outcomes have equal chance.

Example:

Fair coin:

$$
P(H) = \frac{1}{2}, \quad P(T) = \frac{1}{2}
$$

Fair die:

$$
P(1)=P(2)=...=P(6)=\frac{1}{6}
$$

If there are $n$ equally likely outcomes, each outcome has probability:

$$
\frac{1}{n}
$$

---

# 15. Conditional Probability

Conditional probability means probability of A **given that B has already happened**.

Symbol:

$$
P(A|B)
$$

Read as:

Probability of A given B.

Formula:

$$
P(A|B) = \frac{P(A \cap B)}{P(B)}
$$

Important: This only works when:

$$
P(B) > 0
$$

---

## Example

Roll a die.

A = getting even number

$$
A = \{2,4,6\}
$$

B = getting number greater than 3

$$
B = \{4,5,6\}
$$

Now find:

$$
P(A|B)
$$

Meaning: Given that the number is greater than 3, what is probability it is even?

Since B happened, possible outcomes are only:

$$
\{4,5,6\}
$$

Even numbers among these:

$$
\{4,6\}
$$

So:

$$
P(A|B)=\frac{2}{3}
$$

---

# 16. Multiplication Rule

From conditional probability:

$$
P(A|B) = \frac{P(A \cap B)}{P(B)}
$$

So:

$$
P(A \cap B) = P(A|B)P(B)
$$

Also:

$$
P(A \cap B) = P(B|A)P(A)
$$

This is used when events happen together.

---

# 17. Law of Total Probability

Suppose the sample space is divided into parts:

$$
B_1, B_2, B_3, ...
$$

Then probability of event A can be found by:

$$
P(A) = P(A|B_1)P(B_1) + P(A|B_2)P(B_2) + ...
$$

Simple meaning:

Break a big problem into smaller cases.

---

## Simple Example

A factory has two machines.

Machine 1 makes 60% items.  
Machine 2 makes 40% items.

Machine 1 defective rate = 2%  
Machine 2 defective rate = 5%

Find probability that an item is defective.

$$
P(D) = P(D|M_1)P(M_1) + P(D|M_2)P(M_2)
$$

$$
P(D)=0.02(0.60)+0.05(0.40)
$$

$$
P(D)=0.012+0.020=0.032
$$

So probability defective = $0.032 = 3.2\%$.

---

# 18. Bayes’ Theorem

Bayes’ theorem is used to reverse conditional probability.

It helps find:

$$
P(B|A)
$$

when we know:

$$
P(A|B)
$$

Formula:

$$
P(B_j|A)=\frac{P(A|B_j)P(B_j)}{P(A)}
$$

Using total probability:

$$
P(B_j|A)=\frac{P(A|B_j)P(B_j)}
{\sum P(A|B_i)P(B_i)}
$$

---

## Simple Meaning

Bayes answers questions like:

“If something happened, what was the cause?”

Example:

If an item is defective, what is the probability it came from Machine 2?

---

# 19. Independence of Events

Two events A and B are independent if happening of one does not affect the other.

Formula:

$$
P(A \cap B) = P(A)P(B)
$$

Also:

$$
P(A|B)=P(A)
$$

and

$$
P(B|A)=P(B)
$$

---

## Example

Toss a coin and roll a die.

A = getting Head  
B = getting 6

Coin result does not affect die result.

So A and B are independent.

$$
P(A \cap B) = \frac{1}{2} \times \frac{1}{6}
$$

$$
= \frac{1}{12}
$$

---

# 20. Repeated Independent Trials

Sometimes we repeat the same experiment many times.

Example:

- Toss coin 10 times
- Roll die 5 times
- Ask 100 people yes/no question

If each trial does not affect the others, they are independent trials.

---

# 21. Bernoulli Trial

A Bernoulli trial has only two results:

- Success
- Failure

Examples:

- Toss coin: Head = success, Tail = failure
- Pass/fail exam
- Defective/not defective item

Let:

$$
p = P(\text{success})
$$

Then:

$$
1-p = P(\text{failure})
$$

---

# 22. Bernoulli Random Variable

A Bernoulli random variable X takes values:

$$
X = 1 \quad \text{if success}
$$

$$
X = 0 \quad \text{if failure}
$$

Probability:

$$
P(X=1)=p
$$

$$
P(X=0)=1-p
$$

---

# 23. Binomial Distribution

Binomial distribution is used when:

1. There are fixed number of trials, say $n$
2. Each trial has success/failure
3. Probability of success is same each time
4. Trials are independent

Formula:

$$
P(X=k)= {n \choose k} p^k(1-p)^{n-k}
$$

Where:

- $n$ = total trials
- $k$ = number of successes wanted
- $p$ = probability of success
- \({n \choose k}\) = number of ways to choose k successes from n trials

---

## Example

A coin is tossed 3 times. Find probability of exactly 2 heads.

Here:

$$
n=3
$$

$$
k=2
$$

$$
p=\frac{1}{2}
$$

Formula:

$$
P(X=2)= {3 \choose 2}\left(\frac{1}{2}\right)^2 \left(\frac{1}{2}\right)^1
$$

$$
{3 \choose 2}=3
$$

$$
P(X=2)=3 \times \frac{1}{4} \times \frac{1}{2}
$$

$$
=\frac{3}{8}
$$

---

# 24. Geometric Distribution

Geometric distribution is used when we want:

**Probability that first success happens on the kth trial.**

Formula:

$$
P(X=k)=(1-p)^{k-1}p
$$

Where:

- first $k-1$ trials are failures
- kth trial is success

---

## Example

A coin is tossed until first Head appears.

Find probability first Head appears on 3rd toss.

Here:

First two tosses must be Tail, third must be Head.

$$
T,T,H
$$

$$
P = \frac{1}{2}\times \frac{1}{2}\times \frac{1}{2}
$$

$$
=\frac{1}{8}
$$

Using formula:

$$
P(X=3)=\left(\frac{1}{2}\right)^2\left(\frac{1}{2}\right)
$$

$$
=\frac{1}{8}
$$

---

# 25. Discrete Random Variable

A **random variable** is a number assigned to outcomes.

Discrete means it takes countable values like:

$$
0,1,2,3,...
$$

Example:

Toss two coins.

Sample space:

$$
S = \{HH, HT, TH, TT\}
$$

Let X = number of heads.

Then:

| Outcome | X |
|---|---|
| HH | 2 |
| HT | 1 |
| TH | 1 |
| TT | 0 |

So X can be:

$$
0,1,2
$$

That is a discrete random variable.

---

# 26. Probability Mass Function PMF

A PMF gives probabilities for each value of a discrete random variable.

Example:

For two coin tosses, X = number of heads.

| X | Probability |
|---|---|
| 0 | 1/4 |
| 1 | 2/4 |
| 2 | 1/4 |

This table is the PMF.

Properties of PMF:

1. Every probability must be non-negative:

$$
P(X=x) \ge 0
$$

2. Total probability must be 1:

$$
\sum P(X=x)=1
$$

---

# 27. Common Discrete Distributions

## 27.1 Discrete Uniform Distribution

All values have equal probability.

Example:

Roll a fair die.

$$
P(X=x)=\frac{1}{6}, \quad x=1,2,3,4,5,6
$$

---

## 27.2 Bernoulli Distribution

Used for one success/failure trial.

$$
P(X=1)=p
$$

$$
P(X=0)=1-p
$$

---

## 27.3 Binomial Distribution

Used for number of successes in fixed number of trials.

$$
P(X=k)= {n \choose k}p^k(1-p)^{n-k}
$$

---

## 27.4 Geometric Distribution

Used for first success on kth trial.

$$
P(X=k)=(1-p)^{k-1}p
$$

---

## 27.5 Negative Binomial Distribution

Used for finding when the rth success occurs.

Formula:

$$
P(X=n)= {n-1 \choose r-1}p^r(1-p)^{n-r}
$$

Where:

- r = number of successes wanted
- n = trial number on which rth success happens
- p = probability of success

Simple meaning:

To get the rth success on nth trial:

- nth trial must be success
- before nth trial, there must be exactly r-1 successes

---

## 27.6 Poisson Distribution

Poisson distribution is used for counting number of events in a fixed time/area/space.

Examples:

- Number of phone calls in one hour
- Number of accidents in a day
- Number of emails received in one minute
- Number of printing mistakes in a page

Formula:

$$
P(X=k)=\frac{e^{-\lambda}\lambda^k}{k!}
$$

Where:

- \(\lambda\) = average number of events
- k = number of events wanted
- e ≈ 2.718

---

### Example

Average number of calls per hour = 3.

Find probability of exactly 2 calls in an hour.

$$
\lambda = 3
$$

$$
k = 2
$$

$$
P(X=2)=\frac{e^{-3}3^2}{2!}
$$

$$
=\frac{e^{-3}9}{2}
$$

---

## 27.7 Hypergeometric Distribution

Used when sampling is done **without replacement**.

Example:

A box has 5 red balls and 3 blue balls.  
You pick 2 balls without putting them back.

Because you do not replace the first ball, probabilities change.

Formula:

$$
P(X=k)=\frac{{K \choose k}{N-K \choose n-k}}{{N \choose n}}
$$

Where:

- N = total items
- K = total successes in population
- n = number selected
- k = successes selected

---

# 28. Functions of a Discrete Random Variable

Sometimes we create a new variable from old variable.

Example:

Let X = number on a die.

Define:

$$
Y = X^2
$$

If:

$$
X=1,2,3,4,5,6
$$

Then:

$$
Y=1,4,9,16,25,36
$$

So Y is a function of X.

If we know probabilities of X, we can find probabilities of Y.



28. Cumulative Distribution Function (CDF)

The PMF tells you the probability of an exact value, but the CDF tells you the probability of getting that value or anything smaller.

- Symbol: $$F(x)$$
- Formula: $$F(x) = P(X \leq x)$$
- Properties of CDF:
	- It always starts at 0 and ends at 1.
	- It never decreases (it either stays the same or goes up).

Example

Roll a fair die. Let X = number on the die.

Find $F(3)$. Meaning: Probability of getting 3 or less.

$$F(3) = P(X \leq 3) = P(X=1) + P(X=2) + P(X=3)$$

$$F(3) = \frac{1}{6} + \frac{1}{6} + \frac{1}{6} = \frac{3}{6} = \frac{1}{2}$$

Key Takeaway: PMF is for exact values ($=$). CDF is for cumulative values ($\leq$).

29. Expected Value (Mean)

Expected value is the long-run average of a random variable. If you repeated an experiment thousands of times and averaged the results, you would get the expected value.

- Symbol: $$E(X) \quad \text{or} \quad \mu$$
- Formula: $$E(X) = \sum x \cdot P(X=x)$$

Simple meaning: Multiply each possible value by its probability, then add them all up.

Example

Let X be the number of heads when tossing 1 coin. X can be $0$ (Tail) or $1$ (Head).

$$P(X=0) = \frac{1}{2}$$

$$P(X=1) = \frac{1}{2}$$

Find $E(X)$:

$$E(X) = (0 \times \frac{1}{2}) + (1 \times \frac{1}{2})$$

$$E(X) = 0 + 0.5 = 0.5$$

Note: You cannot actually get 0.5 heads in one toss. It just means over many tosses, you average half a head per toss.

30. Variance and Standard Deviation

Variance measures how much the values spread out from the expected value (mean).

- Symbol for Variance: $$Var(X) \quad \text{or} \quad \sigma^2$$
- Formula: $$Var(X) = E(X^2) - [E(X)]^2$$
- How to calculate $E(X^2)$: Square every x value, multiply by its probability, and add them up.

$$E(X^2) = \sum x^2 \cdot P(X=x)$$

Standard Deviation

Standard deviation is simply the square root of the variance. It brings the spread back to the original units.

- Symbol: $$SD(X) \quad \text{or} \quad \sigma$$
- Formula: $$SD(X) = \sqrt{Var(X)}$$

31. Properties of Expectation and Variance

Often, we change a random variable by adding a constant or multiplying by a constant. Let $X$ be a random variable, and let $a$ and $b$ be constant numbers.

Rule 1: Linearity of Expectation

$$E(aX + b) = aE(X) + b$$

Meaning: If you multiply all values by $a$ and add $b$, the new mean simply gets multiplied by $a$ and increased by $b$.

Rule 2: Transformation of Variance

$$Var(aX + b) = a^2 Var(X)$$

Meaning: Adding a constant ($b$) does not change the variance (shifting data doesn't change the spread). Multiplying by a constant ($a$) multiplies the variance by $a^2$.

Rule 3: Expected value of a constant

$$E(c) = c$$

The expected value of a fixed number is just that number.

Example

Suppose the average temperature in Celsius is $E(C) = 20^\circ$ and variance $Var(C) = 4$.

Convert this to Fahrenheit using $F = 1.8C + 32$.

Find Expected Value in Fahrenheit:

$$E(F) = 1.8E(C) + 32$$

$$E(F) = 1.8(20) + 32 = 36 + 32 = 68^\circ$$

Find Variance in Fahrenheit:

$$Var(F) = Var(1.8C + 32)$$

$$Var(F) = (1.8)^2 Var(C)$$

$$Var(F) = 3.24 \times 4 = 12.96$$
---

# 29. Important Formula Summary

## Probability of event

$$
P(A)=\frac{\text{favourable outcomes}}{\text{total outcomes}}
$$

## Complement

$$
P(A^c)=1-P(A)
$$

## Union

$$
P(A \cup B)=P(A)+P(B)-P(A \cap B)
$$

## Disjoint events

$$
P(A \cap B)=0
$$

## Conditional probability

$$
P(A|B)=\frac{P(A \cap B)}{P(B)}
$$

## Multiplication rule

$$
P(A \cap B)=P(A|B)P(B)
$$

## Independence

$$
P(A \cap B)=P(A)P(B)
$$

## Total probability

$$
P(A)=\sum P(A|B_i)P(B_i)
$$

## Bayes’ theorem

$$
P(B_j|A)=\frac{P(A|B_j)P(B_j)}{\sum P(A|B_i)P(B_i)}
$$

## Binomial

$$
P(X=k)= {n \choose k}p^k(1-p)^{n-k}
$$

## Geometric

$$
P(X=k)=(1-p)^{k-1}p
$$

## Poisson

$$
P(X=k)=\frac{e^{-\lambda}\lambda^k}{k!}
$$

---

# 30. How to Solve Probability Questions Step by Step

Whenever you get a question, follow this method:

## Step 1: Identify the experiment

Ask: What is being done?

Example: Tossing coin, rolling die, drawing card.

---

## Step 2: Write the sample space if possible

Example:

Roll die:

$$
S=\{1,2,3,4,5,6\}
$$

---

## Step 3: Define the event

Example:

A = getting even number

$$
A=\{2,4,6\}
$$

---

## Step 4: Count favourable outcomes

Here favourable outcomes = 3.

---

## Step 5: Count total outcomes

Total outcomes = 6.

---

## Step 6: Apply formula

$$
P(A)=\frac{3}{6}=\frac{1}{2}
$$

---

# 31. Most Important Intuition

Probability is just:

$$
\text{Chance} = \frac{\text{what you want}}{\text{everything possible}}
$$

Conditional probability is:

$$
\text{Chance after new information}
$$

Distribution is:

$$
\text{probability table}
$$

Random variable is:

$$
\text{number assigned to random result}
$$

---

# 32. Very Small Practice

## Question 1

A die is rolled. Find probability of getting 5.

Total outcomes:

$$
6
$$

Favourable outcomes:

$$
1
$$

$$
P(5)=\frac{1}{6}
$$

---

## Question 2

A die is rolled. Find probability of getting odd number.

Odd numbers:

$$
\{1,3,5\}
$$

Favourable outcomes = 3  
Total outcomes = 6

$$
P(\text{odd})=\frac{3}{6}=\frac{1}{2}
$$

---

## Question 3

A coin is tossed 3 times. Find probability of exactly 3 heads.

Only one way:

$$
HHH
$$

Total outcomes:

$$
2^3=8
$$

$$
P(3 \text{ heads})=\frac{1}{8}
$$

---

## Question 4

If \(P(A)=0.7\), find \(P(A^c)\).

$$
P(A^c)=1-P(A)
$$

$$
=1-0.7=0.3
$$

---

# Final Advice

Do not try to memorize everything at once.

Study in this order:

1. Sample space  
2. Events  
3. Union/intersection/complement  
4. Probability rules  
5. Conditional probability  
6. Bayes theorem  
7. Random variables  
8. Distributions: Bernoulli, Binomial, Geometric, Poisson, Hypergeometric  

If you want, I can next explain the PDF **page by page with examples**, starting from Chapter 1.