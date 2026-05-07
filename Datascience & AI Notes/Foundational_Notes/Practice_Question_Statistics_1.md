---

# VERY IMPORTANT FORMULA SHEET

## 1. Mean

\[
\bar{x} = \frac{\sum x}{n}
\]

If the average of \(n\) observations is \(\bar{x}\), then:

\[
\text{Total sum} = n\bar{x}
\]

---

## 2. Combined Mean

If group 1 has \(n_1\), mean \(\bar{x}_1\), and group 2 has \(n_2\), mean \(\bar{x}_2\):

\[
\bar{x} = \frac{n_1\bar{x}_1 + n_2\bar{x}_2}{n_1 + n_2}
\]

---

## 3. Variance

Population variance:

\[
\sigma^2 = \frac{\sum (x - \bar{x})^2}{n}
\]

Sample variance:

\[
s^2 = \frac{\sum (x - \bar{x})^2}{n - 1}
\]

---

## 4. Transformation Rules

If every observation becomes:

\[
Y = aX + b
\]

Then:

\[
\text{Mean}(Y) = a\text{Mean}(X) + b
\]

\[
\text{Variance}(Y) = a^2\text{Variance}(X)
\]

\[
\text{SD}(Y) = |a|\text{SD}(X)
\]

Important:

Adding/subtracting a number changes the mean, but **does not change variance**.

---

## 5. Probability

\[
P(A) = \frac{\text{favourable outcomes}}{\text{total outcomes}}
\]

---

## 6. Union Formula

\[
P(A \cup B) = P(A) + P(B) - P(A \cap B)
\]

---

## 7. Conditional Probability

\[
P(A|B) = \frac{P(A \cap B)}{P(B)}
\]

---

## 8. Independence

A and B are independent if:

\[
P(A \cap B) = P(A)P(B)
\]

or:

\[
P(A|B) = P(A)
\]

---

## 9. Bayes Theorem

\[
P(A|B) = \frac{P(B|A)P(A)}{P(B)}
\]

---

## 10. Permutation

Arrangement/order matters:

\[
{}^nP_r = \frac{n!}{(n - r)!}
\]

---

## 11. Combination

Selection/order does not matter:

\[
{}^nC_r = \frac{n!}{r!(n - r)!}
\]

---

## 12. Binomial Distribution

Use when:

- Fixed trials \(n\)
- Success/failure
- Independent trials
- Same probability \(p\)

\[
P(X = k) = {n \choose k}p^k(1 - p)^{n - k}
\]

---

## 13. Poisson Distribution

\[
P(X = k) = \frac{e^{-\lambda}\lambda^k}{k!}
\]

Mean:

\[
E(X) = \lambda
\]

Variance:

\[
\text{Var}(X) = \lambda
\]

---

## 14. Exponential Distribution

If mean is \(\mu\), then:

\[
\lambda = \frac{1}{\mu}
\]

Survival probability:

\[
P(X > t) = e^{-\lambda t}
\]

Memoryless property:

\[
P(X > s + t | X > s) = P(X > t)
\]

---

# PART 1: SCALES OF MEASUREMENT PYQs

There are 4 scales:

| Scale | Meaning | Example |
|---|---|---|
| Nominal | Only names/categories | Gender, blood group, city |
| Ordinal | Order/rank matters | Poor, good, excellent |
| Interval | Difference meaningful, no true zero | Celsius temperature |
| Ratio | Difference and ratio meaningful, true zero | Height, weight, income |

---

## Q1. Which scale is used for blood group?

A. Nominal  
B. Ordinal  
C. Interval  
D. Ratio  

Answer:

\[
\boxed{A}
\]

Blood group is just a category.

---

## Q2. Which scale is used for exam rank?

A. Nominal  
B. Ordinal  
C. Interval  
D. Ratio  

Answer:

\[
\boxed{B}
\]

Rank has order.

---

## Q3. Which scale is used for temperature in Celsius?

A. Nominal  
B. Ordinal  
C. Interval  
D. Ratio  

Answer:

\[
\boxed{C}
\]

Celsius has no true zero.

---

## Q4. Which scale is used for weight?

A. Nominal  
B. Ordinal  
C. Interval  
D. Ratio  

Answer:

\[
\boxed{D}
\]

Weight has true zero.

---

## Q5. Which statements are correct for ratio scale?

A. Order is meaningful  
B. Difference is meaningful  
C. Multiplication/division are meaningful  
D. It does not have absolute zero  

Answer:

\[
\boxed{A,B,C}
\]

D is wrong because ratio scale has absolute zero.

---

# PART 2: MEAN PYQs

---

## Q6. Average of 10 observations is 25. Find their total sum.

Formula:

\[
Sum = n \times mean
\]

\[
= 10 \times 25 = 250
\]

Answer:

\[
\boxed{250}
\]

---

## Q7. Average of 15 observations is 40. Average of first 8 observations is 35. Average of last 8 observations is 48. Find the 8th observation.

This type came in your PYQ.

Step 1:

Total of 15 observations:

\[
15 \times 40 = 600
\]

Step 2:

Total of first 8:

\[
8 \times 35 = 280
\]

Step 3:

Total of last 8:

\[
8 \times 48 = 384
\]

But 8th observation is counted twice.

So:

\[
280 + 384 = 664
\]

Extra amount:

\[
664 - 600 = 64
\]

Answer:

\[
\boxed{64}
\]

---

## Q8. Average of 20 students is 60. If one student with mark 40 leaves, find new average.

Original total:

\[
20 \times 60 = 1200
\]

New total:

\[
1200 - 40 = 1160
\]

New number of students:

\[
19
\]

New average:

\[
\frac{1160}{19} = 61.05
\]

Answer:

\[
\boxed{61.05}
\]

---

## Q9. Mean of 5 numbers is 12. Four numbers are 10, 15, 8, 17. Find fifth number.

Total:

\[
5 \times 12 = 60
\]

Sum of four numbers:

\[
10 + 15 + 8 + 17 = 50
\]

Fifth number:

\[
60 - 50 = 10
\]

Answer:

\[
\boxed{10}
\]

---

# PART 3: MEDIAN AND MODE PYQs

---

## Q10. Find median of:

\[
4,8,2,10,6
\]

Step 1: Arrange:

\[
2,4,6,8,10
\]

Middle value:

\[
6
\]

Answer:

\[
\boxed{6}
\]

---

## Q11. Find median of:

\[
3,7,9,11,13,15
\]

Already arranged.

There are 6 values, even number.

Median:

\[
\frac{3rd + 4th}{2}
\]

\[
=\frac{9+11}{2}=10
\]

Answer:

\[
\boxed{10}
\]

---

## Q12. Find mode:

\[
2,3,3,4,5,5,5,6
\]

Most repeated value is 5.

Answer:

\[
\boxed{5}
\]

---

## Q13. Dataset:

\[
1,2,2,3,3,4
\]

What is the mode?

Answer:

\[
\boxed{2 \text{ and } 3}
\]

This is bimodal.

---

# PART 4: VARIANCE AND STANDARD DEVIATION PYQs

---

## Q14. If variance is 25, find standard deviation.

\[
SD = \sqrt{Variance}
\]

\[
SD = \sqrt{25} = 5
\]

Answer:

\[
\boxed{5}
\]

---

## Q15. If standard deviation is 8, find variance.

\[
Variance = SD^2
\]

\[
= 8^2 = 64
\]

Answer:

\[
\boxed{64}
\]

---

## Q16. Dataset has mean 10 and variance 4. If every observation is increased by 5, find new mean and variance.

New mean:

\[
10 + 5 = 15
\]

Variance does not change when we add constant.

New variance:

\[
4
\]

Answer:

\[
\boxed{Mean=15,\ Variance=4}
\]

---

## Q17. Dataset has mean 20 and variance 9. If every observation is multiplied by 3, find new mean and variance.

New mean:

\[
3 \times 20 = 60
\]

New variance:

\[
3^2 \times 9 = 81
\]

Answer:

\[
\boxed{Mean=60,\ Variance=81}
\]

---

## Q18. Dataset has mean 5 and variance 2. If \(Y=4X+3\), find mean and variance of Y.

Mean:

\[
E(Y) = 4E(X) + 3
\]

\[
= 4(5) + 3 = 23
\]

Variance:

\[
Var(Y) = 4^2Var(X)
\]

\[
= 16(2) = 32
\]

Answer:

\[
\boxed{Mean=23,\ Variance=32}
\]

---

# PART 5: QUARTILE, IQR, BOXPLOT PYQs

---

## Q19. Find range of:

\[
5,8,2,10,12
\]

Range:

\[
Maximum - Minimum
\]

\[
= 12 - 2 = 10
\]

Answer:

\[
\boxed{10}
\]

---

## Q20. If \(Q_1=20\) and \(Q_3=50\), find IQR.

\[
IQR = Q_3 - Q_1
\]

\[
= 50 - 20 = 30
\]

Answer:

\[
\boxed{30}
\]

---

## Q21. If \(Q_1=10\), \(Q_3=30\), find lower fence and upper fence.

Step 1:

\[
IQR = 30 - 10 = 20
\]

Lower fence:

\[
Q_1 - 1.5IQR
\]

\[
= 10 - 1.5(20)
\]

\[
= 10 - 30 = -20
\]

Upper fence:

\[
Q_3 + 1.5IQR
\]

\[
= 30 + 30 = 60
\]

Answer:

\[
\boxed{-20,\ 60}
\]

---

## Q22. In a boxplot, values outside lower and upper fences are called?

Answer:

\[
\boxed{Outliers}
\]

---

# PART 6: PERMUTATION AND COMBINATION PYQs

This is very important in your PYQs.

---

## Q23. In how many ways can a team of 4 be selected from 9 students?

Selection means combination:

\[
{}^9C_4 = \frac{9!}{4!5!}
\]

\[
= \frac{9\times8\times7\times6}{4\times3\times2\times1}
\]

\[
= 126
\]

Answer:

\[
\boxed{126}
\]

---

## Q24. A team of 4 is selected from 9 students. If 2 particular students must be included, find number of ways.

2 students are fixed.

Need to choose remaining 2 from remaining 7:

\[
{}^7C_2 = 21
\]

Answer:

\[
\boxed{21}
\]

---

## Q25. A team of 4 is selected from 9 students. If 2 particular students must not be included, find number of ways.

Remove those 2 students.

Remaining students:

\[
7
\]

Choose 4 from 7:

\[
{}^7C_4 = 35
\]

Answer:

\[
\boxed{35}
\]

---

## Q26. In how many ways can the letters of “READING” be arranged?

READING has 7 different letters.

\[
7! = 5040
\]

Answer:

\[
\boxed{5040}
\]

---

## Q27. In how many ways can letters of “READING” be arranged if vowels always come together?

Word:

\[
READING
\]

Vowels:

\[
E,A,I
\]

Treat vowels as one block.

So blocks are:

\[
(EAI), R, D, N, G
\]

Total blocks:

\[
5
\]

Arrange blocks:

\[
5!
\]

Arrange vowels inside block:

\[
3!
\]

Total:

\[
5! \times 3!
\]

\[
= 120 \times 6 = 720
\]

Answer:

\[
\boxed{720}
\]

---

## Q28. There are 11 players. Each player shakes hands with every other player once. Find number of handshakes.

Choose 2 people from 11:

\[
{}^{11}C_2 = \frac{11\times10}{2} = 55
\]

Answer:

\[
\boxed{55}
\]

---

## Q29. A committee of 5 is selected from 6 men and 4 women. Find number of committees with exactly 3 women.

Choose 3 women from 4:

\[
{}^4C_3 = 4
\]

Choose 2 men from 6:

\[
{}^6C_2 = 15
\]

Total:

\[
4 \times 15 = 60
\]

Answer:

\[
\boxed{60}
\]

---

## Q30. A box has 3 white, 3 black and 4 red balls. In how many ways can 3 balls be drawn with at least one red ball?

Total balls:

\[
10
\]

Total ways to choose 3:

\[
{}^{10}C_3 = 120
\]

Ways with no red:

There are 6 non-red balls.

\[
{}^6C_3 = 20
\]

At least one red:

\[
120 - 20 = 100
\]

Answer:

\[
\boxed{100}
\]

---

## Q31. 7 people sit around a circular table. In how many ways?

Circular arrangement:

\[
(n-1)!
\]

\[
=(7-1)!=6!=720
\]

Answer:

\[
\boxed{720}
\]

---

# PART 7: BASIC PROBABILITY PYQs

---

## Q32. A t-shirt is chosen from 6 yellow, 2 black and 4 blue t-shirts. Find probability of black or blue.

Total:

\[
6+2+4=12
\]

Black or blue:

\[
2+4=6
\]

Probability:

\[
\frac{6}{12}=0.5
\]

Answer:

\[
\boxed{0.5}
\]

---

## Q33. In a survey of 120 people, 70 like tea, 50 like coffee, and 30 like both. Find probability that a person likes tea or coffee.

Formula:

\[
P(T\cup C)=\frac{n(T)+n(C)-n(T\cap C)}{Total}
\]

\[
=\frac{70+50-30}{120}
\]

\[
=\frac{90}{120}=0.75
\]

Answer:

\[
\boxed{0.75}
\]

---

## Q34. A die is rolled. Find probability of getting an even number.

Even numbers:

\[
2,4,6
\]

Probability:

\[
\frac{3}{6}=\frac{1}{2}
\]

Answer:

\[
\boxed{0.5}
\]

---

## Q35. A card is drawn from a deck of 52 cards. Find probability of getting a king.

There are 4 kings.

\[
P=\frac{4}{52}=\frac{1}{13}
\]

Answer:

\[
\boxed{\frac{1}{13}}
\]

---

# PART 8: CONDITIONAL PROBABILITY PYQs

---

## Q36. A jar has 6 red and 8 blue balls. Two balls are drawn without replacement. Find probability first is red and second is blue.

Total balls:

\[
14
\]

First red:

\[
\frac{6}{14}
\]

After red is removed, remaining balls:

\[
13
\]

Blue balls still:

\[
8
\]

Second blue:

\[
\frac{8}{13}
\]

Total probability:

\[
\frac{6}{14}\times \frac{8}{13}
\]

\[
=\frac{24}{91}
\]

Answer:

\[
\boxed{\frac{24}{91}}
\]

---

## Q37. A jar has 6 red and 8 blue balls. First ball is red. Find probability second ball is blue.

After first red is removed:

Total remaining:

\[
13
\]

Blue remaining:

\[
8
\]

Probability:

\[
\frac{8}{13}
\]

Answer:

\[
\boxed{\frac{8}{13}}
\]

---

## Q38. In a class, 40 students like Maths, 30 like Stats, and 20 like both. Total students = 60. Find probability that a student likes Maths given that he likes Stats.

\[
P(M|S)=\frac{P(M\cap S)}{P(S)}
\]

Using counts:

\[
P(M|S)=\frac{20}{30}
\]

\[
=\frac{2}{3}
\]

Answer:

\[
\boxed{\frac{2}{3}}
\]

---

# PART 9: INDEPENDENCE PYQs

---

## Q39. If \(P(A)=0.4\), \(P(B)=0.5\), and \(P(A\cap B)=0.2\), are A and B independent?

Check:

\[
P(A)P(B)=0.4\times0.5=0.2
\]

Given:

\[
P(A\cap B)=0.2
\]

Both equal.

Answer:

\[
\boxed{Yes,\ independent}
\]

---

## Q40. If \(P(A)=0.3\), \(P(B)=0.6\), and \(P(A\cap B)=0.1\), are A and B independent?

\[
P(A)P(B)=0.3\times0.6=0.18
\]

But:

\[
P(A\cap B)=0.1
\]

Not equal.

Answer:

\[
\boxed{No}
\]

---

# PART 10: BAYES THEOREM PYQs

---

## Q41. Bag 1 has 3 red and 2 blue balls. Bag 2 has 4 red and 6 blue balls. One bag is chosen randomly and one ball is drawn. If ball is red, find probability it came from Bag 1.

Let:

\[
B_1 = \text{Bag 1}
\]

\[
B_2 = \text{Bag 2}
\]

\[
R = \text{Red}
\]

Given:

\[
P(B_1)=\frac12,\quad P(B_2)=\frac12
\]

\[
P(R|B_1)=\frac{3}{5}
\]

\[
P(R|B_2)=\frac{4}{10}=\frac25
\]

Bayes formula:

\[
P(B_1|R)=\frac{P(R|B_1)P(B_1)}
{P(R|B_1)P(B_1)+P(R|B_2)P(B_2)}
\]

\[
=\frac{\frac35 \times \frac12}
{\frac35 \times \frac12+\frac25 \times \frac12}
\]

\[
=\frac{\frac{3}{10}}{\frac{3}{10}+\frac{2}{10}}
\]

\[
=\frac{3}{5}
\]

Answer:

\[
\boxed{0.6}
\]

---

## Q42. A taxi company problem: Green taxis are 40%, Yellow taxis are 60%. Probability of engine issue is 5% for Green and 10% for Yellow. Find probability that a randomly chosen taxi has engine issue.

\[
P(E)=P(E|G)P(G)+P(E|Y)P(Y)
\]

\[
=0.05(0.40)+0.10(0.60)
\]

\[
=0.02+0.06=0.08
\]

Answer:

\[
\boxed{0.08}
\]

---

## Q43. In Q42, given taxi has engine issue, find probability it is Green.

\[
P(G|E)=\frac{P(E|G)P(G)}{P(E)}
\]

\[
=\frac{0.05(0.40)}{0.08}
\]

\[
=\frac{0.02}{0.08}=0.25
\]

Answer:

\[
\boxed{0.25}
\]

---

# PART 11: BINOMIAL DISTRIBUTION PYQs

---

## Q44. Indian cricket team has 65% chance of winning a match. They play 5 independent matches. Find probability they win exactly 4 matches.

Here:

\[
n=5,\quad p=0.65,\quad k=4
\]

\[
P(X=4)={5\choose4}(0.65)^4(0.35)^1
\]

\[
=5(0.65)^4(0.35)
\]

\[
=5(0.1785)(0.35)
\]

\[
=0.3124
\]

Answer:

\[
\boxed{0.31}
\]

---

## Q45. Same cricket team. Find probability they win at least 4 matches.

At least 4 means:

\[
X=4 \text{ or } X=5
\]

\[
P(X\ge4)=P(X=4)+P(X=5)
\]

\[
P(X=4)=5(0.65)^4(0.35)
\]

\[
=0.3124
\]

\[
P(X=5)=(0.65)^5
\]

\[
=0.1160
\]

Total:

\[
0.3124+0.1160=0.4284
\]

Answer:

\[
\boxed{0.43}
\]

---

## Q46. A student guesses 4 MCQs. Each question has 4 options. Find probability exactly 2 answers are correct.

Probability correct:

\[
p=\frac14
\]

Probability wrong:

\[
q=\frac34
\]

\[
n=4,\quad k=2
\]

\[
P(X=2)={4\choose2}\left(\frac14\right)^2\left(\frac34\right)^2
\]

\[
=6\times\frac{1}{16}\times\frac{9}{16}
\]

\[
=\frac{54}{256}=0.2109
\]

Answer:

\[
\boxed{0.21}
\]

---

# PART 12: POISSON DISTRIBUTION PYQs

---

## Q47. Number of customers entering a store follows Poisson distribution with average 8 customers per hour. Find probability exactly 5 customers enter in 15 minutes.

Average per hour:

\[
8
\]

15 minutes is:

\[
\frac{15}{60}=\frac14 \text{ hour}
\]

So average in 15 minutes:

\[
\lambda=8\times\frac14=2
\]

Need:

\[
P(X=5)
\]

\[
P(X=5)=\frac{e^{-2}2^5}{5!}
\]

\[
=\frac{e^{-2}32}{120}
\]

Approx:

\[
=0.036
\]

Answer:

\[
\boxed{0.036}
\]

---

## Q48. If \(X\sim Poisson(3)\), find \(P(X=2)\).

\[
P(X=2)=\frac{e^{-3}3^2}{2!}
\]

\[
=\frac{9e^{-3}}{2}
\]

Approx:

\[
=0.224
\]

Answer:

\[
\boxed{0.224}
\]

---

## Q49. If \(X\sim Poisson(5)\), find mean and variance.

For Poisson:

\[
Mean=\lambda
\]

\[
Variance=\lambda
\]

Answer:

\[
\boxed{Mean=5,\ Variance=5}
\]

---

## Q50. If \(X\) and \(Y\) are independent Poisson random variables with expectations 3 and 5, find variance of \(2X+Y\).

Given:

\[
Var(X)=3
\]

\[
Var(Y)=5
\]

Formula:

\[
Var(aX+bY)=a^2Var(X)+b^2Var(Y)
\]

\[
Var(2X+Y)=2^2Var(X)+1^2Var(Y)
\]

\[
=4(3)+5
\]

\[
=12+5=17
\]

Answer:

\[
\boxed{17}
\]

---

# PART 13: EXPONENTIAL DISTRIBUTION PYQs

---

## Q51. Lifetime of an electronic device follows exponential distribution with mean 500 hours. It has already worked for 400 hours. Find probability it works at least another 100 hours.

This is exactly like your PYQ pattern.

Exponential distribution has memoryless property.

So:

\[
P(X>500|X>400)=P(X>100)
\]

Mean:

\[
500
\]

So:

\[
\lambda=\frac1{500}
\]

\[
P(X>100)=e^{-100/500}
\]

\[
=e^{-0.2}
\]

\[
=0.8187
\]

Answer:

\[
\boxed{0.82}
\]

---

## Q52. A bulb lifetime is exponential with mean 1000 hours. Find probability it lasts more than 500 hours.

\[
\lambda=\frac1{1000}
\]

\[
P(X>500)=e^{-500/1000}
\]

\[
=e^{-0.5}
\]

\[
=0.6065
\]

Answer:

\[
\boxed{0.61}
\]

---

## Q53. Bus waiting time follows exponential distribution with mean 10 minutes. Find probability waiting time is more than 15 minutes.

\[
P(X>15)=e^{-15/10}
\]

\[
=e^{-1.5}
\]

\[
=0.223
\]

Answer:

\[
\boxed{0.22}
\]

---

# PART 14: UNIFORM DISTRIBUTION PYQs

---

## Q54. Metros arrive every 10 minutes. A person arrives randomly. Find probability he waits at least 4 minutes.

Waiting time is uniform from 0 to 10.

Need:

\[
P(X\ge4)
\]

Length from 4 to 10:

\[
10-4=6
\]

Total length:

\[
10
\]

\[
P=\frac{6}{10}=0.6
\]

Answer:

\[
\boxed{0.6}
\]

---

## Q55. Waiting time is uniform between 0 and 20 minutes. Find probability waiting time is less than 5 minutes.

\[
P(X<5)=\frac{5-0}{20-0}
\]

\[
=\frac{5}{20}=0.25
\]

Answer:

\[
\boxed{0.25}
\]

---

## Q56. \(X\sim Uniform(2,8)\). Find \(P(X>5)\).

Total interval length:

\[
8-2=6
\]

Favourable length:

\[
8-5=3
\]

\[
P=\frac{3}{6}=0.5
\]

Answer:

\[
\boxed{0.5}
\]

---

# PART 15: COVARIANCE AND CORRELATION PYQs

---

## Q57. If covariance between X and Y is positive, what does it mean?

Answer:

\[
\boxed{\text{X and Y tend to increase together}}
\]

---

## Q58. If correlation is -0.8, what type of relationship is there?

Answer:

\[
\boxed{\text{Strong negative relationship}}
\]

---

## Q59. Can correlation be greater than 1?

Answer:

\[
\boxed{No}
\]

Correlation always lies between:

\[
-1 \le r \le 1
\]

---

## Q60. If \(Cov(X,Y)=12\), \(SD(X)=3\), \(SD(Y)=4\), find correlation.

\[
r=\frac{Cov(X,Y)}{SD(X)SD(Y)}
\]

\[
=\frac{12}{3\times4}
\]

\[
=\frac{12}{12}=1
\]

Answer:

\[
\boxed{1}
\]

---

# PART 16: DATA TABLE / COMPREHENSION PYQs

These questions are common in your PDF. Usually they give a table and ask probability or totals.

---

## Comprehension 1

A family monthly expenditure is:

| Item | Amount |
|---|---|
| Rent | ₹20,000 |
| Groceries | ₹15,000 |
| Utilities | ₹5,000 |
| Transport | ₹8,000 |
| Others | ₹12,000 |

---

### Q61. Find difference between Groceries and Utilities.

\[
15000-5000=10000
\]

Answer:

\[
\boxed{₹10,000}
\]

---

### Q62. Find expenditure on Rent and Utilities combined.

\[
20000+5000=25000
\]

Answer:

\[
\boxed{₹25,000}
\]

---

### Q63. Find total monthly expenditure.

\[
20000+15000+5000+8000+12000=60000
\]

Answer:

\[
\boxed{₹60,000}
\]

---

### Q64. What percentage is spent on Rent?

\[
\frac{20000}{60000}\times100
\]

\[
=33.33\%
\]

Answer:

\[
\boxed{33.33\%}
\]

---

## Comprehension 2

Reaction to a gadget:

| Reaction | Male | Female |
|---|---|---|
| Favourable | 30 | 20 |
| Neutral | 10 | 15 |
| Unfavourable | 5 | 20 |

---

### Q65. Total number of people?

\[
30+20+10+15+5+20=100
\]

Answer:

\[
\boxed{100}
\]

---

### Q66. Probability that a randomly selected person is female.

Female total:

\[
20+15+20=55
\]

\[
P(Female)=\frac{55}{100}=0.55
\]

Answer:

\[
\boxed{0.55}
\]

---

### Q67. Probability that reaction is favourable.

Favourable total:

\[
30+20=50
\]

\[
P(Favourable)=\frac{50}{100}=0.5
\]

Answer:

\[
\boxed{0.5}
\]

---

### Q68. Find probability person is female given reaction is favourable.

\[
P(Female|Favourable)=\frac{Female \cap Favourable}{Favourable}
\]

\[
=\frac{20}{50}=0.4
\]

Answer:

\[
\boxed{0.4}
\]

---

# PART 17: MULTIPLE SELECT CONCEPT PYQs

These are tricky because more than one option can be correct.

---

## Q69. Which are true for nominal data?

A. Data are categories  
B. Order is meaningful  
C. Arithmetic operations are meaningful  
D. Examples include blood group and gender  

Answer:

\[
\boxed{A,D}
\]

---

## Q70. Which are true for ordinal data?

A. Order matters  
B. Difference between ranks is always meaningful  
C. Examples include ratings poor/good/excellent  
D. It has true zero  

Answer:

\[
\boxed{A,C}
\]

---

## Q71. Which are true for mean?

A. Mean uses all observations  
B. Mean is affected by extreme values  
C. Mean can be found for nominal data  
D. Mean is sum divided by number of observations  

Answer:

\[
\boxed{A,B,D}
\]

---

## Q72. Which are true for median?

A. Median is middle value  
B. Median is less affected by outliers  
C. Median requires data to be arranged  
D. Median is always equal to mean  

Answer:

\[
\boxed{A,B,C}
\]

---

## Q73. Which are true for probability?

A. Probability is always between 0 and 1  
B. Probability can be negative  
C. Probability of sample space is 1  
D. Probability of impossible event is 0  

Answer:

\[
\boxed{A,C,D}
\]

---

## Q74. Which are true for independent events?

A. \(P(A\cap B)=P(A)P(B)\)  
B. \(P(A|B)=P(A)\)  
C. \(P(B|A)=P(B)\)  
D. They must be mutually exclusive  

Answer:

\[
\boxed{A,B,C}
\]

D is wrong. Independent and mutually exclusive are different.

---

# FULL MOCK TEST 1

Try this like exam.

---

## Q1. Which scale is used for customer satisfaction: poor, average, good, excellent?

Answer:

\[
\boxed{Ordinal}
\]

---

## Q2. Average of 12 observations is 30. Find total sum.

\[
12\times30=360
\]

Answer:

\[
\boxed{360}
\]

---

## Q3. Find median:

\[
9,3,5,7,1
\]

Arrange:

\[
1,3,5,7,9
\]

Answer:

\[
\boxed{5}
\]

---

## Q4. Find mode:

\[
4,4,5,6,6,6,7
\]

Answer:

\[
\boxed{6}
\]

---

## Q5. If variance is 49, find SD.

Answer:

\[
\boxed{7}
\]

---

## Q6. If mean is 10 and variance is 3, find mean and variance of \(Y=2X+5\).

Mean:

\[
2(10)+5=25
\]

Variance:

\[
2^2(3)=12
\]

Answer:

\[
\boxed{Mean=25,\ Variance=12}
\]

---

## Q7. Choose 3 students from 8 students.

\[
{}^8C_3=56
\]

Answer:

\[
\boxed{56}
\]

---

## Q8. Arrange 5 different books in a row.

\[
5!=120
\]

Answer:

\[
\boxed{120}
\]

---

## Q9. Probability of getting head when tossing a fair coin.

Answer:

\[
\boxed{0.5}
\]

---

## Q10. If \(P(A)=0.6\), find \(P(A^c)\).

\[
1-0.6=0.4
\]

Answer:

\[
\boxed{0.4}
\]

---

## Q11. If \(P(A)=0.5\), \(P(B)=0.4\), \(P(A\cap B)=0.2\), find \(P(A\cup B)\).

\[
0.5+0.4-0.2=0.7
\]

Answer:

\[
\boxed{0.7}
\]

---

## Q12. If \(X\sim Poisson(4)\), find variance.

Answer:

\[
\boxed{4}
\]

---

## Q13. If \(X\sim Binomial(3,0.5)\), find \(P(X=2)\).

\[
{}^3C_2(0.5)^2(0.5)^1
\]

\[
=3(0.125)=0.375
\]

Answer:

\[
\boxed{0.375}
\]

---

## Q14. Waiting time is uniform from 0 to 10 minutes. Find probability wait is less than 3 minutes.

\[
\frac{3}{10}=0.3
\]

Answer:

\[
\boxed{0.3}
\]

---

## Q15. Exponential lifetime has mean 200 hours. Find probability lifetime exceeds 100 hours.

\[
P(X>100)=e^{-100/200}
\]

\[
=e^{-0.5}=0.6065
\]

Answer:

\[
\boxed{0.61}
\]

---

# FULL MOCK TEST 2

---

## Q1. Height is measured on which scale?

Answer:

\[
\boxed{Ratio}
\]

---

## Q2. Gender is measured on which scale?

Answer:

\[
\boxed{Nominal}
\]

---

## Q3. Temperature in Celsius is measured on which scale?

Answer:

\[
\boxed{Interval}
\]

---

## Q4. Mean of 6 observations is 20. Five observations are:

\[
10,12,15,18,20
\]

Find the sixth observation.

---

### Q5. Find range:

\[
3,8,12,20,25
\]

\[
25-3=22
\]

Answer:

\[
\boxed{22}
\]

---

### Q6. If \(Q_1=15\) and \(Q_3=35\), find IQR.

\[
35-15=20
\]

Answer:

\[
\boxed{20}
\]

---

### Q7. A die is rolled. Find probability of getting number greater than 4.

Numbers greater than 4:

\[
5,6
\]

\[
P=\frac{2}{6}=\frac13
\]

Answer:

\[
\boxed{\frac13}
\]

---

### Q8. A bag has 5 red and 5 blue balls. One ball is drawn. Find probability of red ball.

\[
\frac{5}{10}=0.5
\]

Answer:

\[
\boxed{0.5}
\]

---

### Q9. A committee of 3 is selected from 5 men and 4 women. Find number of committees with 2 men and 1 woman.

\[
{}^5C_2\times{}^4C_1
\]

\[
=10\times4=40
\]

Answer:

\[
\boxed{40}
\]

---

### Q10. If \(P(A)=0.4\), \(P(B)=0.5\), and A and B are independent, find \(P(A\cap B)\).

\[
0.4\times0.5=0.2
\]

Answer:

\[
\boxed{0.2}
\]

---

# HOW TO TOP THE EXAM USING THESE PYQs

## Step 1: First master these 10 question types

1. Mean missing observation  
2. Variance transformation  
3. Median/mode  
4. Combination selection  
5. Arrangement with vowels together  
6. Union probability  
7. Conditional probability  
8. Bayes theorem  
9. Binomial distribution  
10. Poisson/exponential distribution  

---

## Step 2: Learn these calculator values

Useful values:

\[
e^{-0.2}=0.82
\]

\[
e^{-0.5}=0.61
\]

\[
e^{-1}=0.37
\]

\[
e^{-1.5}=0.22
\]

\[
e^{-2}=0.135
\]

---

## Step 3: Mistakes to avoid

### Mistake 1

For combinations, do not use permutation.

If question says **select**, use:

\[
{}^nC_r
\]

If question says **arrange**, use:

\[
{}^nP_r
\]

---

### Mistake 2

For variance transformation:

If:

\[
Y=aX+b
\]

Do not include \(b\) in variance.

\[
Var(Y)=a^2Var(X)
\]

---

### Mistake 3

For exponential distribution, remember memoryless property.

If already worked 400 hours and asks next 100 hours:

Use only 100 hours.

---

### Mistake 4

For Poisson rate, adjust time.

If rate is 8 per hour and time is 15 minutes:

\[
\lambda=8\times\frac{15}{60}=2
\]

---

### Mistake 5

For “at least” questions:

At least 4 means:

\[
4,5,6,\dots
\]

For binomial with \(n=5\):

\[
P(X\ge4)=P(X=4)+P(X=5)
\]

---

# FINAL HIGH-SCORE REVISION LIST

Before exam, revise:

| Topic | Must Know |
|---|---|
| Scales | nominal, ordinal, interval, ratio |
| Mean | total = mean × number |
| Median | arrange data first |
| Mode | most repeated |
| Variance | transformation rules |
| IQR | \(Q_3-Q_1\) |
| Combination | selection |
| Permutation | arrangement |
| Probability | favourable / total |
| Conditional probability | \(P(A|B)\) |
| Bayes | reverse probability |
| Binomial | fixed number of trials |
| Poisson | average rate |
| Exponential | waiting/lifetime, memoryless |
| Uniform | length favourable / total length |
| Correlation | between -1 and 1 |

---

If you want, I can next make you a **100-question exam-style Statistics mock test PDF-like set** with only questions first and answer key at the end.


# Statistics PYQ-Style 100 Question Mock Test  
**Questions first, answers at the end.**  
Try solving first like a real exam.

---

# MOCK TEST: STATISTICS 1  
**Total Questions: 100**

---

## Section A: Scales of Measurement

### Q1. Blood group is measured on which scale?

A. Nominal  
B. Ordinal  
C. Interval  
D. Ratio  

---

### Q2. Exam rank is measured on which scale?

A. Nominal  
B. Ordinal  
C. Interval  
D. Ratio  

---

### Q3. Temperature in Celsius is measured on which scale?

A. Nominal  
B. Ordinal  
C. Interval  
D. Ratio  

---

### Q4. Height of students is measured on which scale?

A. Nominal  
B. Ordinal  
C. Interval  
D. Ratio  

---

### Q5. Customer satisfaction levels: poor, average, good, excellent are measured on which scale?

A. Nominal  
B. Ordinal  
C. Interval  
D. Ratio  

---

### Q6. Which scale has a true zero?

A. Nominal  
B. Ordinal  
C. Interval  
D. Ratio  

---

### Q7. Gender is an example of:

A. Nominal data  
B. Ordinal data  
C. Interval data  
D. Ratio data  

---

### Q8. Which of the following is interval scale?

A. Weight  
B. Temperature in Celsius  
C. Blood group  
D. Rank  

---

## Section B: Mean, Median, Mode

### Q9. Find the mean of:

\[
4,6,8,10,12
\]

---

### Q10. Average of 10 observations is 25. Find their total sum.

---

### Q11. Mean of 6 numbers is 15. Five numbers are:

\[
10,12,15,18,20
\]

Find the sixth number.

---

### Q12. Average of 20 students is 50. One student with mark 30 leaves. Find the new average.

---

### Q13. Average of 15 observations is 40. Average of first 8 observations is 35. Average of last 8 observations is 48. Find the 8th observation.

---

### Q14. Find median:

\[
3,7,1,9,5
\]

---

### Q15. Find median:

\[
2,4,6,8,10,12
\]

---

### Q16. Find mode:

\[
2,3,3,4,5,5,5,6
\]

---

### Q17. Dataset:

\[
1,2,2,3,3,4,5
\]

What is/are the mode?

---

### Q18. Which measure is most affected by extreme values?

A. Mean  
B. Median  
C. Mode  
D. None  

---

### Q19. Which measure is the middle value after arranging data?

A. Mean  
B. Median  
C. Mode  
D. Range  

---

### Q20. The mode is:

A. Average value  
B. Middle value  
C. Most frequent value  
D. Largest value  

---

## Section C: Range, Quartiles, IQR, Boxplot

### Q21. Find range:

\[
5,8,2,10,12
\]

---

### Q22. If maximum value is 80 and minimum value is 20, find range.

---

### Q23. If \(Q_1=15\) and \(Q_3=35\), find IQR.

---

### Q24. If \(Q_1=10\) and \(Q_3=30\), find lower fence and upper fence.

---

### Q25. In boxplot, values outside fences are called:

A. Median  
B. Quartiles  
C. Outliers  
D. Mean  

---

### Q26. Formula of IQR is:

A. \(Q_1-Q_3\)  
B. \(Q_3-Q_1\)  
C. \(Q_2-Q_1\)  
D. \(Q_3+Q_1\)  

---

## Section D: Variance and Standard Deviation

### Q27. If variance is 36, find standard deviation.

---

### Q28. If standard deviation is 9, find variance.

---

### Q29. If mean is 20 and every observation is increased by 5, find new mean.

---

### Q30. If variance is 16 and every observation is increased by 10, find new variance.

---

### Q31. If mean is 10 and variance is 4, and \(Y=3X\), find mean and variance of \(Y\).

---

### Q32. If \(Y=2X+5\), \(E(X)=8\), find \(E(Y)\).

---

### Q33. If \(Y=4X+3\), \(Var(X)=2\), find \(Var(Y)\).

---

### Q34. Adding a constant to every observation changes:

A. Mean only  
B. Variance only  
C. Both mean and variance  
D. Neither mean nor variance  

---

### Q35. Multiplying every observation by 3 multiplies variance by:

A. 3  
B. 6  
C. 9  
D. 12  

---

## Section E: Permutation and Combination

### Q36. In how many ways can 3 students be selected from 8 students?

---

### Q37. In how many ways can 4 students be selected from 9 students?

---

### Q38. In how many ways can 5 different books be arranged in a row?

---

### Q39. In how many ways can letters of the word “READING” be arranged?

---

### Q40. In how many ways can letters of “READING” be arranged if vowels always come together?

---

### Q41. 10 people shake hands with each other once. Find number of handshakes.

---

### Q42. A committee of 5 is selected from 6 men and 4 women. Find number of committees with exactly 3 women.

---

### Q43. A team of 4 is selected from 9 students. If 2 particular students must be included, find number of ways.

---

### Q44. A team of 4 is selected from 9 students. If 2 particular students must not be included, find number of ways.

---

### Q45. In how many ways can 7 people sit around a circular table?

---

### Q46. If order matters, we use:

A. Combination  
B. Permutation  
C. Mean  
D. Median  

---

### Q47. If order does not matter, we use:

A. Combination  
B. Permutation  
C. Variance  
D. Probability  

---

## Section F: Basic Probability

### Q48. A fair coin is tossed. Find probability of getting head.

---

### Q49. A die is rolled. Find probability of getting an even number.

---

### Q50. A die is rolled. Find probability of getting a number greater than 4.

---

### Q51. A card is drawn from a standard deck of 52 cards. Find probability of getting a king.

---

### Q52. A card is drawn from a standard deck. Find probability of getting a heart.

---

### Q53. A bag has 5 red and 3 blue balls. One ball is drawn. Find probability of red ball.

---

### Q54. A t-shirt is chosen from 6 yellow, 2 black and 4 blue t-shirts. Find probability of black or blue.

---

### Q55. If \(P(A)=0.7\), find \(P(A^c)\).

---

### Q56. If \(P(A)=0.5\), \(P(B)=0.4\), and \(P(A\cap B)=0.2\), find \(P(A\cup B)\).

---

### Q57. In a survey of 120 people, 70 like tea, 50 like coffee, and 30 like both. Find probability that a randomly selected person likes tea or coffee.

---

### Q58. If two events are mutually exclusive, then:

A. \(P(A\cap B)=1\)  
B. \(P(A\cap B)=0\)  
C. \(P(A)=P(B)\)  
D. \(P(A\cup B)=0\)  

---

## Section G: Conditional Probability and Independence

### Q59. Formula of conditional probability is:

A. \(P(A|B)=P(A)P(B)\)  
B. \(P(A|B)=\frac{P(A\cap B)}{P(B)}\)  
C. \(P(A|B)=P(A)+P(B)\)  
D. \(P(A|B)=P(A)-P(B)\)  

---

### Q60. In a class, 40 students like Maths, 30 like Statistics, and 20 like both. Find probability that a student likes Maths given that he likes Statistics.

---

### Q61. A jar has 6 red and 8 blue balls. Two balls are drawn without replacement. Find probability first is red and second is blue.

---

### Q62. A jar has 6 red and 8 blue balls. First ball is red. Find probability second ball is blue.

---

### Q63. If \(P(A)=0.4\), \(P(B)=0.5\), and \(P(A\cap B)=0.2\), are A and B independent?

---

### Q64. If \(P(A)=0.3\), \(P(B)=0.6\), and \(P(A\cap B)=0.1\), are A and B independent?

---

### Q65. If A and B are independent, then:

A. \(P(A\cap B)=P(A)P(B)\)  
B. \(P(A|B)=P(A)\)  
C. \(P(B|A)=P(B)\)  
D. All of the above  

---

## Section H: Bayes Theorem

### Q66. A factory has two machines. Machine 1 produces 60% items and Machine 2 produces 40% items. Defective rate of Machine 1 is 2%, and Machine 2 is 5%. Find probability an item is defective.

---

### Q67. In Q66, given that an item is defective, find probability it came from Machine 2.

---

### Q68. Bag 1 has 3 red and 2 blue balls. Bag 2 has 4 red and 6 blue balls. One bag is selected randomly and one ball is drawn. If ball is red, find probability it came from Bag 1.

---

### Q69. Green taxis are 40%, yellow taxis are 60%. Engine issue probability is 5% for green and 10% for yellow. Find probability that randomly selected taxi has engine issue.

---

### Q70. In Q69, given taxi has engine issue, find probability it is green.

---

## Section I: Binomial Distribution

### Q71. Which distribution is used for fixed number of independent success/failure trials?

A. Poisson  
B. Binomial  
C. Exponential  
D. Uniform  

---

### Q72. Formula of binomial distribution is:

A. \(\frac{e^{-\lambda}\lambda^x}{x!}\)  
B. \({n\choose x}p^x(1-p)^{n-x}\)  
C. \(e^{-\lambda x}\)  
D. \(\frac{1}{b-a}\)  

---

### Q73. A coin is tossed 3 times. Find probability of exactly 2 heads.

---

### Q74. A student guesses 4 MCQs. Each question has 4 options. Find probability exactly 2 answers are correct.

---

### Q75. Indian cricket team has 65% chance of winning a match. They play 5 independent matches. Find probability they win exactly 4 matches.

---

### Q76. Same cricket team: find probability they win all 5 matches.

---

### Q77. Same cricket team: find probability they win at least 4 matches.

---

### Q78. If \(X\sim Binomial(10,0.3)\), find mean.

---

### Q79. If \(X\sim Binomial(10,0.3)\), find variance.

---

## Section J: Poisson Distribution

### Q80. Which distribution is used for counting number of events in fixed time/area?

A. Binomial  
B. Poisson  
C. Uniform  
D. Normal  

---

### Q81. Formula of Poisson distribution is:

A. \({n\choose x}p^xq^{n-x}\)  
B. \(\frac{e^{-\lambda}\lambda^x}{x!}\)  
C. \(e^{-\lambda x}\)  
D. \(\frac{1}{b-a}\)  

---

### Q82. If \(X\sim Poisson(3)\), find \(P(X=2)\).

---

### Q83. If \(X\sim Poisson(5)\), find mean and variance.

---

### Q84. Number of customers entering a store follows Poisson distribution with average 8 customers per hour. Find probability exactly 5 customers enter in 15 minutes.

---

### Q85. If \(X\sim Poisson(4)\), find \(P(X=0)\).

---

### Q86. If \(X\) and \(Y\) are independent Poisson random variables with expectations 3 and 5, find variance of \(2X+Y\).

---

## Section K: Exponential Distribution

### Q87. Exponential distribution is commonly used for:

A. Waiting time  
B. Blood group  
C. Ranking  
D. Gender  

---

### Q88. If lifetime follows exponential distribution with mean 500 hours, find \(\lambda\).

---

### Q89. Lifetime follows exponential distribution with mean 500 hours. Find probability lifetime is more than 100 hours.

---

### Q90. Lifetime of a device follows exponential distribution with mean 500 hours. It has already worked for 400 hours. Find probability it works at least another 100 hours.

---

### Q91. Bus waiting time follows exponential distribution with mean 10 minutes. Find probability waiting time is more than 15 minutes.

---

### Q92. Exponential distribution has which property?

A. Symmetry  
B. Memoryless property  
C. Fixed trials  
D. Equal probability interval only  

---

## Section L: Uniform Distribution

### Q93. Waiting time is uniform between 0 and 10 minutes. Find probability waiting time is less than 3 minutes.

---

### Q94. Waiting time is uniform between 0 and 10 minutes. Find probability waiting time is at least 4 minutes.

---

### Q95. If \(X\sim Uniform(2,8)\), find \(P(X>5)\).

---

### Q96. If \(X\sim Uniform(0,20)\), find \(P(5<X<15)\).

---

## Section M: Covariance, Correlation, Data Interpretation

### Q97. Correlation always lies between:

A. 0 and 1  
B. -1 and 1  
C. -10 and 10  
D. 1 and 100  

---

### Q98. If covariance between X and Y is positive, what does it mean?

A. X increases, Y decreases  
B. X and Y tend to increase together  
C. No relationship  
D. Both are constant  

---

### Q99. If \(Cov(X,Y)=12\), \(SD(X)=3\), \(SD(Y)=4\), find correlation.

---

### Q100. Table below shows monthly expenditure:

| Item | Amount |
|---|---|
| Rent | 20000 |
| Groceries | 15000 |
| Utilities | 5000 |
| Transport | 8000 |
| Others | 12000 |

Find total monthly expenditure.

---

# ANSWER KEY WITH SHORT SOLUTIONS

---

## Section A Answers

### A1.  
\[
\boxed{A}
\]  
Blood group is nominal.

### A2.  
\[
\boxed{B}
\]  
Rank has order, so ordinal.

### A3.  
\[
\boxed{C}
\]  
Celsius has no true zero.

### A4.  
\[
\boxed{D}
\]  
Height has true zero.

### A5.  
\[
\boxed{B}
\]  
Poor, average, good, excellent have order.

### A6.  
\[
\boxed{D}
\]  
Ratio scale has true zero.

### A7.  
\[
\boxed{A}
\]

### A8.  
\[
\boxed{B}
\]

---

## Section B Answers

### A9.  
\[
\frac{4+6+8+10+12}{5}=\frac{40}{5}=8
\]

\[
\boxed{8}
\]

### A10.  
\[
10\times25=250
\]

\[
\boxed{250}
\]

### A11.  
Total:

\[
6\times15=90
\]

Sum of five:

\[
10+12+15+18+20=75
\]

Sixth:

\[
90-75=15
\]

\[
\boxed{15}
\]

### A12.  
Original total:

\[
20\times50=1000
\]

New total:

\[
1000-30=970
\]

New average:

\[
\frac{970}{19}=51.05
\]

\[
\boxed{51.05}
\]

### A13.  
Total 15 observations:

\[
15\times40=600
\]

First 8 total:

\[
8\times35=280
\]

Last 8 total:

\[
8\times48=384
\]

8th observation counted twice:

\[
280+384-600=64
\]

\[
\boxed{64}
\]

### A14.  
Arrange:

\[
1,3,5,7,9
\]

Median:

\[
\boxed{5}
\]

### A15.  
Middle two values are 6 and 8.

\[
\frac{6+8}{2}=7
\]

\[
\boxed{7}
\]

### A16.  
Most repeated value is 5.

\[
\boxed{5}
\]

### A17.  
2 and 3 both repeat twice.

\[
\boxed{2,3}
\]

### A18.  
\[
\boxed{A}
\]

### A19.  
\[
\boxed{B}
\]

### A20.  
\[
\boxed{C}
\]

---

## Section C Answers

### A21.  
\[
12-2=10
\]

\[
\boxed{10}
\]

### A22.  
\[
80-20=60
\]

\[
\boxed{60}
\]

### A23.  
\[
IQR=35-15=20
\]

\[
\boxed{20}
\]

### A24.  
\[
IQR=30-10=20
\]

Lower fence:

\[
10-1.5(20)=10-30=-20
\]

Upper fence:

\[
30+1.5(20)=30+30=60
\]

\[
\boxed{-20,\ 60}
\]

### A25.  
\[
\boxed{C}
\]

### A26.  
\[
\boxed{B}
\]

---

## Section D Answers

### A27.  
\[
SD=\sqrt{36}=6
\]

\[
\boxed{6}
\]

### A28.  
\[
Variance=9^2=81
\]

\[
\boxed{81}
\]

### A29.  
\[
20+5=25
\]

\[
\boxed{25}
\]

### A30.  
Variance does not change after adding constant.

\[
\boxed{16}
\]

### A31.  
Mean:

\[
3(10)=30
\]

Variance:

\[
3^2(4)=36
\]

\[
\boxed{Mean=30,\ Variance=36}
\]

### A32.  
\[
E(Y)=2E(X)+5=2(8)+5=21
\]

\[
\boxed{21}
\]

### A33.  
\[
Var(Y)=4^2Var(X)=16(2)=32
\]

\[
\boxed{32}
\]

### A34.  
\[
\boxed{A}
\]

### A35.  
\[
3^2=9
\]

\[
\boxed{C}
\]

---

## Section E Answers

### A36.  
\[
{}^8C_3=56
\]

\[
\boxed{56}
\]

### A37.  
\[
{}^9C_4=126
\]

\[
\boxed{126}
\]

### A38.  
\[
5!=120
\]

\[
\boxed{120}
\]

### A39.  
READING has 7 different letters.

\[
7!=5040
\]

\[
\boxed{5040}
\]

### A40.  
Vowels: E, A, I.

Treat vowels as one block.

Total blocks:

\[
5
\]

Arrangement:

\[
5!\times3!=120\times6=720
\]

\[
\boxed{720}
\]

### A41.  
\[
{}^{10}C_2=45
\]

\[
\boxed{45}
\]

### A42.  
Choose 3 women from 4:

\[
{}^4C_3=4
\]

Choose 2 men from 6:

\[
{}^6C_2=15
\]

Total:

\[
4\times15=60
\]

\[
\boxed{60}
\]

### A43.  
2 students fixed. Choose remaining 2 from 7.

\[
{}^7C_2=21
\]

\[
\boxed{21}
\]

### A44.  
Remove 2 students. Choose 4 from 7.

\[
{}^7C_4=35
\]

\[
\boxed{35}
\]

### A45.  
Circular arrangement:

\[
(7-1)!=6!=720
\]

\[
\boxed{720}
\]

### A46.  
\[
\boxed{B}
\]

### A47.  
\[
\boxed{A}
\]

---

## Section F Answers

### A48.  
\[
\boxed{\frac12}
\]

### A49.  
Even numbers: 2, 4, 6.

\[
\frac36=\frac12
\]

\[
\boxed{\frac12}
\]

### A50.  
Numbers greater than 4: 5, 6.

\[
\frac26=\frac13
\]

\[
\boxed{\frac13}
\]

### A51.  
There are 4 kings.

\[
\frac{4}{52}=\frac{1}{13}
\]

\[
\boxed{\frac{1}{13}}
\]

### A52.  
There are 13 hearts.

\[
\frac{13}{52}=\frac14
\]

\[
\boxed{\frac14}
\]

### A53.  
\[
\frac{5}{8}
\]

\[
\boxed{\frac58}
\]

### A54.  
Total:

\[
6+2+4=12
\]

Black or blue:

\[
2+4=6
\]

\[
\frac6{12}=\frac12
\]

\[
\boxed{\frac12}
\]

### A55.  
\[
1-0.7=0.3
\]

\[
\boxed{0.3}
\]

### A56.  
\[
P(A\cup B)=0.5+0.4-0.2=0.7
\]

\[
\boxed{0.7}
\]

### A57.  
\[
\frac{70+50-30}{120}
=
\frac{90}{120}=0.75
\]

\[
\boxed{0.75}
\]

### A58.  
\[
\boxed{B}
\]

---

## Section G Answers

### A59.  
\[
\boxed{B}
\]

### A60.  
\[
P(M|S)=\frac{20}{30}=\frac23
\]

\[
\boxed{\frac23}
\]

### A61.  
\[
\frac{6}{14}\times\frac{8}{13}
=
\frac{24}{91}
\]

\[
\boxed{\frac{24}{91}}
\]

### A62.  
After red removed, total = 13, blue = 8.

\[
\boxed{\frac{8}{13}}
\]

### A63.  
\[
P(A)P(B)=0.4\times0.5=0.2
\]

Given \(P(A\cap B)=0.2\), so independent.

\[
\boxed{Yes}
\]

### A64.  
\[
P(A)P(B)=0.3\times0.6=0.18
\]

But \(P(A\cap B)=0.1\).

\[
\boxed{No}
\]

### A65.  
\[
\boxed{D}
\]

---

## Section H Answers

### A66.  
\[
P(D)=0.02(0.60)+0.05(0.40)
\]

\[
=0.012+0.020=0.032
\]

\[
\boxed{0.032}
\]

### A67.  
\[
P(M_2|D)=\frac{0.05(0.40)}{0.032}
\]

\[
=\frac{0.020}{0.032}=0.625
\]

\[
\boxed{0.625}
\]

### A68.  
\[
P(B_1|R)=
\frac{\frac35\times\frac12}
{\frac35\times\frac12+\frac25\times\frac12}
\]

\[
=
\frac{3/10}{3/10+2/10}
=
\frac35
\]

\[
\boxed{0.6}
\]

### A69.  
\[
P(E)=0.05(0.40)+0.10(0.60)
\]

\[
=0.02+0.06=0.08
\]

\[
\boxed{0.08}
\]

### A70.  
\[
P(G|E)=\frac{0.05(0.40)}{0.08}
=
\frac{0.02}{0.08}=0.25
\]

\[
\boxed{0.25}
\]

---

## Section I Answers

### A71.  
\[
\boxed{B}
\]

### A72.  
\[
\boxed{B}
\]

### A73.  
\[
{}^3C_2\left(\frac12\right)^2\left(\frac12\right)
=
3\times\frac18
=
\frac38
\]

\[
\boxed{\frac38}
\]

### A74.  
\[
{}^4C_2\left(\frac14\right)^2\left(\frac34\right)^2
\]

\[
=6\times\frac1{16}\times\frac9{16}
=
\frac{54}{256}
=
0.2109
\]

\[
\boxed{0.21}
\]

### A75.  
\[
{}^5C_4(0.65)^4(0.35)
\]

\[
=5(0.65)^4(0.35)
\approx0.312
\]

\[
\boxed{0.312}
\]

### A76.  
\[
(0.65)^5\approx0.116
\]

\[
\boxed{0.116}
\]

### A77.  
\[
P(X\ge4)=P(X=4)+P(X=5)
\]

\[
=0.312+0.116=0.428
\]

\[
\boxed{0.428}
\]

### A78.  
\[
Mean=np=10(0.3)=3
\]

\[
\boxed{3}
\]

### A79.  
\[
Variance=npq=10(0.3)(0.7)=2.1
\]

\[
\boxed{2.1}
\]

---

## Section J Answers

### A80.  
\[
\boxed{B}
\]

### A81.  
\[
\boxed{B}
\]

### A82.  
\[
P(X=2)=\frac{e^{-3}3^2}{2!}
=
\frac{9e^{-3}}{2}
\approx0.224
\]

\[
\boxed{0.224}
\]

### A83.  
For Poisson:

\[
Mean=\lambda=5
\]

\[
Variance=\lambda=5
\]

\[
\boxed{Mean=5,\ Variance=5}
\]

### A84.  
Average per hour = 8.

15 minutes:

\[
\frac{15}{60}=\frac14
\]

\[
\lambda=8\times\frac14=2
\]

\[
P(X=5)=\frac{e^{-2}2^5}{5!}
=
\frac{32e^{-2}}{120}
\approx0.036
\]

\[
\boxed{0.036}
\]

### A85.  
\[
P(X=0)=\frac{e^{-4}4^0}{0!}=e^{-4}
\]

\[
\boxed{e^{-4}}
\]

Approx:

\[
\boxed{0.0183}
\]

### A86.  
\[
Var(2X+Y)=2^2Var(X)+Var(Y)
\]

For Poisson:

\[
Var(X)=3,\quad Var(Y)=5
\]

\[
=4(3)+5=17
\]

\[
\boxed{17}
\]

---

## Section K Answers

### A87.  
\[
\boxed{A}
\]

### A88.  
\[
\lambda=\frac1{500}
\]

\[
\boxed{\frac1{500}}
\]

### A89.  
\[
P(X>100)=e^{-100/500}=e^{-0.2}
\]

\[
\boxed{0.8187}
\]

### A90.  
Use memoryless property.

\[
P(X>500|X>400)=P(X>100)
\]

\[
=e^{-100/500}=e^{-0.2}
\]

\[
\boxed{0.8187}
\]

### A91.  
\[
P(X>15)=e^{-15/10}=e^{-1.5}
\]

\[
\boxed{0.223}
\]

### A92.  
\[
\boxed{B}
\]

---

## Section L Answers

### A93.  
\[
P(X<3)=\frac{3}{10}=0.3
\]

\[
\boxed{0.3}
\]

### A94.  
\[
P(X\ge4)=\frac{10-4}{10}=\frac6{10}=0.6
\]

\[
\boxed{0.6}
\]

### A95.  
\[
P(X>5)=\frac{8-5}{8-2}
=
\frac36=\frac12
\]

\[
\boxed{0.5}
\]

### A96.  
\[
P(5<X<15)=\frac{15-5}{20-0}
=
\frac{10}{20}=0.5
\]

\[
\boxed{0.5}
\]

---

## Section M Answers

### A97.  
\[
\boxed{B}
\]

Correlation lies between:

\[
-1 \le r \le 1
\]

### A98.  
\[
\boxed{B}
\]

### A99.  
\[
r=\frac{Cov(X,Y)}{SD(X)SD(Y)}
\]

\[
=\frac{12}{3\times4}
=
\frac{12}{12}=1
\]

\[
\boxed{1}
\]

### A100.  
\[
20000+15000+5000+8000+12000=60000
\]

\[
\boxed{60000}
\]

---

# Your Revision Strategy

Before exam, solve this mock test in this order:

1. First solve Q1–Q35  
2. Then solve Q36–Q58  
3. Then solve Q59–Q79  
4. Finally solve Q80–Q100  

Most important topics to master:

\[
\boxed{Mean,\ Variance,\ Probability,\ Combination,\ Bayes,\ Binomial,\ Poisson,\ Exponential}
\]

If you can solve this full mock test without seeing answers, you are in a very strong position for the exam.