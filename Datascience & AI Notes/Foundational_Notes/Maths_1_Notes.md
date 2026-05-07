# Maths for Data Science

* Set & Functions.  
* Straight line.  
* Quadratic Functions.  
* Polynomial Functions.  
* Exponential Functions.  
* Logarithmic Functions.  
* Limits.  
* Continuity.  
* Differentiability.  
* Integration.  
**` graph theory`**  
* Graphs and general graph problems.  
* DAGs. Topological sorting and Longest path.  
* Weighted graphs and shortest path algorithms.  

The PDF mainly has these chapters:

1. Set Theory  
2. Straight Lines  
3. Quadratic Functions  
4. Polynomial Functions  
5. Exponential Functions  
6. Logarithmic Functions  

---

# CHAPTER 1: SET THEORY

---

## 1. Natural Numbers

Natural numbers are counting numbers.

$$
1,2,3,4,5,\dots
$$

Usually:

$$
\mathbb{N} = \{1,2,3,4,\dots\}
$$

Sometimes 0 is also included depending on the book, but basic natural numbers start from 1.

### Example

- Number of students in a class = 40  
  **40 is a natural number.**

### Key Takeaway
- Natural numbers are positive integers starting from 1 (or sometimes 0).

---

## 2. Integers

Integers include:

- Negative numbers  
- Zero  
- Positive numbers

$$
\mathbb{Z} = \{\dots,-3,-2,-1,0,1,2,3,\dots\}
$$

### Example

- $$-5, 0, 8$$ are integers.

### Key Takeaway
- Integers include all whole numbers, both positive and negative, including zero.

---

## 3. Arithmetic Operations

Basic operations:

| Operation | Meaning | Example |
|---|---|---|
| $+$ | Addition | $3+2=5$ |
| $-$ | Subtraction | $5-2=3$ |
| $\times$ | Multiplication | $4\times 3=12$ |
| $\div$ | Division | $10\div 2=5$ |
| Modulo | Remainder | $10 \mod 3 = 1$ |

### Key Takeaway
- Arithmetic operations form the foundation of mathematics and are used in everyday calculations.

---

## 4. Modulo

Modulo means **remainder after division**.

### Example

$$
17 \mod 5
$$

5 goes into 17 three times:

$$
5 \times 3 = 15
$$

Remainder:

$$
17-15=2
$$

So:

$$
17 \mod 5 = 2
$$

### Key Takeaway
- Modulo gives the remainder when one number is divided by another.

---

## 5. Factors

A factor of a number divides it exactly.

### Example

Factors of 12:

$$
1,2,3,4,6,12
$$

Because all divide 12 without remainder.

### Key Takeaway
- Factors are numbers that divide a given number without leaving a remainder.

---

## 6. Rational Numbers

A rational number can be written as:

$$
\frac{p}{q}
$$

where $p$ and $q$ are integers and $q \neq 0$.

### Examples

$$
\frac{1}{2}, \frac{3}{4}, -\frac{5}{7}, 2
$$

Even 2 is rational because:

$$
2 = \frac{2}{1}
$$

### Key Takeaway
- Rational numbers can always be expressed as a fraction of two integers.

---

## 7. Greatest Common Divisor, GCD

GCD means the **largest number that divides two numbers exactly**.

### Example

Find GCD of 12 and 18.

Factors of 12:

$$
1,2,3,4,6,12
$$

Factors of 18:

$$
1,2,3,6,9,18
$$

Common factors:

$$
1,2,3,6
$$

Greatest common factor:

$$
6
$$

So:

$$
GCD(12,18)=6
$$

### Key Takeaway
- GCD is the largest number that divides two or more numbers without leaving a remainder.

---

## 8. Real Numbers

Real numbers include almost all numbers we use:

- Natural numbers  
- Integers  
- Rational numbers  
- Irrational numbers

Examples:

$$
1, -2, 0, \frac{3}{4}, \sqrt{2}, \pi
$$

### Key Takeaway
- Real numbers include all rational and irrational numbers.

---

## 9. Irrational Numbers

Irrational numbers **cannot** be written as $\frac{p}{q}$.

Examples:

$$
\sqrt{2}, \sqrt{3}, \pi, e
$$

Their decimal form never ends and never repeats.

Example:

$$
\pi = 3.14159265\dots
$$

### Key Takeaway
- Irrational numbers have non-repeating, non-terminating decimal expansions.

---

# 10. Sets

A set is a collection of objects.

### Example

$$
A = \{1,2,3,4\}
$$

Here set $A$ contains 1, 2, 3, 4.

### Key Takeaway
- A set is a well-defined collection of distinct objects.

---

## 11. Elements of a Set

The objects inside a set are called elements.

If:

$$
A = \{2,4,6,8\}
$$

Then 2 is an element of A.

We write:

$$
2 \in A
$$

Read as:

“2 belongs to A.”

If 3 is not in A:

$$
3 \notin A
$$

### Key Takeaway
- Elements are the individual objects in a set.

---

## 12. Empty Set

A set with no element is called empty set.

$$
\emptyset
$$

### Example

Set of natural numbers less than 0:

$$
\emptyset
$$

### Key Takeaway
- The empty set contains no elements and is denoted by $\emptyset$.

---

## 13. Subset

A set $A$ is a subset of $B$ if every element of $A$ is also in $B$.

Symbol:

$$
A \subseteq B
$$

### Example

$$
A = \{1,2\}
$$

$$
B = \{1,2,3,4\}
$$

Every element of A is inside B.

So:

$$
A \subseteq B
$$

### Key Takeaway
- A subset is a set whose elements are all contained in another set.

---

## 14. Proper Subset

If $A$ is inside $B$, but $A\neq B$, then A is a proper subset.

Symbol:

$$
A \subset B
$$

Example:

$$
\{1,2\} \subset \{1,2,3\}
$$

### Key Takeaway
- A proper subset is a subset that is not equal to the original set.

---

## 15. Set Builder Form / Set Comprehension

This is a short way to describe sets.

Example:

$$
A = \{x : x \text{ is an even number less than 10}\}
$$

This means:

$$
A = \{2,4,6,8\}
$$

Another example:

$$
B = \{x \in \mathbb{N}: x < 5\}
$$

This means:

$$
B = \{1,2,3,4\}
$$

### Key Takeaway
- Set builder form describes a set using a condition.

---

# 16. Cartesian Product

If:

$$
A = \{1,2\}
$$

and:

$$
B = \{a,b\}
$$

Then Cartesian product:

$$
A \times B
$$

means all ordered pairs:

$$
A \times B = \{(1,a),(1,b),(2,a),(2,b)\}
$$

Important:

$$
A \times B \neq B \times A
$$

because:

$$
(1,a) \neq (a,1)
$$

### Key Takeaway
- Cartesian product gives all possible ordered pairs.

---

# 17. Relations

A relation is a connection between elements of two sets.

A relation is a subset of Cartesian product.

Example:

$$
A = \{1,2,3\}
$$

$$
B = \{2,4,6\}
$$

Relation:

$$
R = \{(1,2),(2,4),(3,6)\}
$$

This relation means:

$$
y = 2x
$$

### Key Takeaway
- A relation is a subset of Cartesian product.

---

## 18. Properties of Relations

Suppose relation $R$ is on set $A$.

---

### 18.1 Reflexive Relation

A relation is reflexive if every element is related to itself.

That means:

$$
(a,a) \in R
$$

for every $a \in A$.

Example:

$$
A=\{1,2,3\}
$$

For reflexive relation, we must have:

$$
(1,1),(2,2),(3,3)
$$

### Key Takeaway
- A reflexive relation has every element related to itself.

---

### 18.2 Symmetric Relation

A relation is symmetric if:

$$
(a,b) \in R
$$

then:

$$
(b,a) \in R
$$

Example:

If:

$$
(1,2) \in R
$$

then for symmetric relation:

$$
(2,1) \in R
$$

must also be present.

### Key Takeaway
- A symmetric relation has the property that if $(a,b)$ is in the relation, then $(b,a)$ is also in the relation.

---

### 18.3 Transitive Relation

A relation is transitive if:

If:

$$
(a,b) \in R
$$

and:

$$
(b,c) \in R
$$

then:

$$
(a,c) \in R
$$

Example:

If:

$$
(1,2), (2,3)
$$

are in relation, then transitive relation must contain:

$$
(1,3)
$$

### Key Takeaway
- A transitive relation has the property that if $(a,b)$ and $(b,c)$ are in the relation, then $(a,c)$ is also in the relation.

---

# 19. Functions

A function is a special relation.

A function takes input and gives output.

Usually:

$$
f(x)
$$

means function of $x$.

Example:

$$
f(x)=2x+1
$$

If $x=3$:

$$
f(3)=2(3)+1=7
$$

So input 3 gives output 7.

---

## Very Important Rule of Function

Each input must have **only one output**.

Example:

This is a function:

$$
1 \to 2
$$

$$
2 \to 4
$$

$$
3 \to 6
$$

But this is not a function:

$$
1 \to 2
$$

$$
1 \to 5
$$

because input 1 has two outputs.

### Key Takeaway
- Each input must have exactly one output.

---

## 20. Domain, Codomain, Range

For function:

$$
f: A \to B
$$

- $A$ is domain
- $B$ is codomain
- Actual outputs are range

Example:

$$
A=\{1,2,3\}
$$

$$
B=\{2,4,6,8\}
$$

Function:

$$
f(x)=2x
$$

Then:

$$
f(1)=2
$$

$$
f(2)=4
$$

$$
f(3)=6
$$

Domain:

$$
\{1,2,3\}
$$

Codomain:

$$
\{2,4,6,8\}
$$

Range:

$$
\{2,4,6\}
$$

8 is in codomain but not in range.

### Key Takeaway
- Domain is the set of all inputs.
- Codomain is the set of all possible outputs.
- Range is the set of actual outputs.

---

## 21. Types of Functions

### 21.1 One-One Function / Injective

Different inputs give different outputs.

Example:

$$
f(x)=2x
$$

If inputs are different, outputs are also different.

### Key Takeaway
- One-one function means different inputs give different outputs.

---

### 21.2 Onto Function / Surjective

Every element of codomain is used.

That means range = codomain.

### Key Takeaway
- Onto function means every element of the codomain is used.

---

### 21.3 Bijective Function

A function is bijective if it is both:

- One-one
- Onto

Bijective functions have inverses.

### Key Takeaway
- Bijective functions are both one-one and onto.

---

# 22. Finding Domain

Domain means allowed input values.

Rules:

### Rule 1: Denominator cannot be zero

Example:

$$
f(x)=\frac{1}{x-2}
$$

Denominator:

$$
x-2 \neq 0
$$

So:

$$
x \neq 2
$$

Domain:

All real numbers except 2.

### Key Takeaway
- Denominator cannot be zero.

---

### Rule 2: Inside square root cannot be negative

Example:

$$
f(x)=\sqrt{x-3}
$$

Inside root:

$$
x-3 \geq 0
$$

So:

$$
x \geq 3
$$

Domain:

$$
[3,\infty)
$$

### Key Takeaway
- Inside square root must be non-negative.

---

# PRACTICE QUESTIONS: SET THEORY

## Q1. Write the set of first five natural numbers.

Answer:

$$
\{1,2,3,4,5\}
$$

---

## Q2. Find $15 \mod 4$.

$$
15 = 4 \times 3 + 3
$$

Answer:

$$
15 \mod 4 = 3
$$

---

## Q3. Find GCD of 20 and 30.

Factors of 20:

$$
1,2,4,5,10,20
$$

Factors of 30:

$$
1,2,3,5,6,10,15,30
$$

Common greatest:

$$
10
$$

Answer:

$$
GCD(20,30)=10
$$

---

## Q4. If $A=\{1,2\}$, $B=\{a,b\}$, find $A\times B$.

Answer:

$$
A\times B=\{(1,a),(1,b),(2,a),(2,b)\}
$$

---

## Q5. Is this a function?

$$
\{(1,2),(2,3),(1,4)\}
$$

Answer:

No, because input 1 has two outputs: 2 and 4.

---

# CHAPTER 2: STRAIGHT LINES

---

# 1. Coordinate System

A point in a plane is written as:

$$
(x,y)
$$

Example:

$$
(3,4)
$$

Here:

- $x=3$
- $y=4$

The horizontal line is x-axis.  
The vertical line is y-axis.

---

# 2. Distance Between Two Points

If:

$$
A(x_1,y_1)
$$

and:

$$
B(x_2,y_2)
$$

Then distance:

$$
d = \sqrt{(x_2-x_1)^2+(y_2-y_1)^2}
$$

---

## Example

Find distance between:

$$
A(1,2), B(4,6)
$$

Formula:

$$
d=\sqrt{(4-1)^2+(6-2)^2}
$$

$$
d=\sqrt{3^2+4^2}
$$

$$
d=\sqrt{9+16}
$$

$$
d=\sqrt{25}=5
$$

Answer:

$$
5
$$

---

# 3. Section Formula

Section formula finds a point dividing a line segment.

If point $P$ divides $A(x_1,y_1)$ and $B(x_2,y_2)$ in ratio $m:n$, then:

$$
P=\left(\frac{mx_2+nx_1}{m+n}, \frac{my_2+ny_1}{m+n}\right)
$$

---

## Midpoint Formula

If ratio is $1:1$, then midpoint is:

$$
\left(\frac{x_1+x_2}{2}, \frac{y_1+y_2}{2}\right)
$$

Example:

Midpoint of $(2,4)$ and $(6,8)$:

$$
\left(\frac{2+6}{2}, \frac{4+8}{2}\right)
$$

$$
= (4,6)
$$

---

# 4. Area of Triangle

If triangle vertices are:

$$
(x_1,y_1), (x_2,y_2), (x_3,y_3)
$$

Area:

$$
\frac{1}{2}\left|x_1(y_2-y_3)+x_2(y_3-y_1)+x_3(y_1-y_2)\right|
$$

---

# 5. Slope of a Line

Slope means steepness of a line.

Formula:

$$
m = \frac{y_2-y_1}{x_2-x_1}
$$

---

## Example

Find slope between:

$$
(1,2), (3,6)
$$

$$
m=\frac{6-2}{3-1}
$$

$$
m=\frac{4}{2}=2
$$

Answer:

$$
m=2
$$

---

# 6. Equation of a Line

## 6.1 Slope-intercept form

$$
y=mx+c
$$

where:

- $m$ = slope
- $c$ = y-intercept

Example:

$$
y=2x+3
$$

Slope = 2  
Y-intercept = 3

---

## 6.2 Point-slope form

If line passes through $(x_1,y_1)$ and has slope $m$:

$$
y-y_1=m(x-x_1)
$$

Example:

Line with slope 2 passing through $(1,3)$:

$$
y-3=2(x-1)
$$

$$
y-3=2x-2
$$

$$
y=2x+1
$$

---

## 6.3 Two-point form

If line passes through two points:

$$
(x_1,y_1), (x_2,y_2)
$$

then:

$$
y-y_1=\frac{y_2-y_1}{x_2-x_1}(x-x_1)
$$

---

# 7. Parallel and Perpendicular Lines

## Parallel Lines

Parallel lines have same slope.

$$
m_1=m_2
$$

Example:

$$
y=2x+1
$$

and:

$$
y=2x+5
$$

Both have slope 2, so they are parallel.

---

## Perpendicular Lines

Perpendicular lines meet at 90 degrees.

Condition:

$$
m_1m_2=-1
$$

Example:

If one line has slope 2, perpendicular line has slope:

$$
-\frac{1}{2}
$$

because:

$$
2 \times \left(-\frac{1}{2}\right)=-1
$$

---

# 8. Distance of Point from Line

For line:

$$
Ax+By+C=0
$$

Distance from point $(x_1,y_1)$:

$$
d=\frac{|Ax_1+By_1+C|}{\sqrt{A^2+B^2}}
$$

---

# 9. SSE: Sum Squared Error

SSE is used in data science.

If actual value is $y$ and predicted value is $\hat y$, then error:

$$
y-\hat y
$$

Squared error:

$$
(y-\hat y)^2
$$

SSE:

$$
SSE=\sum (y-\hat y)^2
$$

Small SSE means better prediction.

---

# PRACTICE QUESTIONS: STRAIGHT LINES

## Q1. Find distance between $(0,0)$ and $(3,4)$.

$$
d=\sqrt{3^2+4^2}=5
$$

Answer:

$$
5
$$

---

## Q2. Find slope between $(2,3)$ and $(4,7)$.

$$
m=\frac{7-3}{4-2}=\frac{4}{2}=2
$$

Answer:

$$
2
$$

---

## Q3. Find equation of line with slope 3 passing through $(1,2)$.

$$
y-2=3(x-1)
$$

$$
y-2=3x-3
$$

$$
y=3x-1
$$

Answer:

$$
y=3x-1
$$

---

# CHAPTER 3: QUADRATIC FUNCTIONS

---

# 1. Quadratic Function

A quadratic function has form:

$$
f(x)=ax^2+bx+c
$$

where:

$$
a \neq 0
$$

Example:

$$
f(x)=x^2+2x+1
$$

---

# 2. Shape of Quadratic Function

Graph of quadratic function is called parabola.

If:

$$
a>0
$$

parabola opens upward.

Like:

$$
\cup
$$

If:

$$
a<0
$$

parabola opens downward.

Like:

$$
\cap
$$

---

# 3. Axis of Symmetry

Axis of symmetry is the vertical line that cuts parabola into two equal halves.

Formula:

$$
x=\frac{-b}{2a}
$$

---

# 4. Vertex of Parabola

Vertex is the turning point.

For:

$$
f(x)=ax^2+bx+c
$$

x-coordinate of vertex:

$$
x=\frac{-b}{2a}
$$

Then put this x value into function to get y-coordinate.

---

## Example

Find vertex of:

$$
f(x)=x^2-4x+3
$$

Here:

$$
a=1, b=-4, c=3
$$

$$
x=\frac{-b}{2a}
$$

$$
x=\frac{-(-4)}{2(1)}
$$

$$
x=\frac{4}{2}=2
$$

Now:

$$
f(2)=2^2-4(2)+3
$$

$$
=4-8+3=-1
$$

Vertex:

$$
(2,-1)
$$

---

# 5. Quadratic Equation

A quadratic equation is:

$$
ax^2+bx+c=0
$$

We solve it to find roots.

---

# 6. Methods to Solve Quadratic Equation

## Method 1: Factorization

Example:

$$
x^2+5x+6=0
$$

Find two numbers whose product is 6 and sum is 5.

Numbers:

$$
2,3
$$

So:

$$
x^2+5x+6=(x+2)(x+3)
$$

$$
(x+2)(x+3)=0
$$

So:

$$
x=-2
$$

or:

$$
x=-3
$$

---

## Method 2: Quadratic Formula

For:

$$
ax^2+bx+c=0
$$

Formula:

$$
x=\frac{-b\pm \sqrt{b^2-4ac}}{2a}
$$

---

## Example

Solve:

$$
x^2-5x+6=0
$$

Here:

$$
a=1,b=-5,c=6
$$

$$
x=\frac{-(-5)\pm \sqrt{(-5)^2-4(1)(6)}}{2(1)}
$$

$$
x=\frac{5\pm \sqrt{25-24}}{2}
$$

$$
x=\frac{5\pm 1}{2}
$$

So:

$$
x=3
$$

or:

$$
x=2
$$

---

# PRACTICE QUESTIONS: QUADRATIC

## Q1. Find axis of symmetry of:

$$
f(x)=x^2-6x+5
$$

$$
x=\frac{-b}{2a}=\frac{-(-6)}{2(1)}=3
$$

Answer:

$$
x=3
$$

---

## Q2. Solve:

$$
x^2+7x+12=0
$$

$$
x^2+7x+12=(x+3)(x+4)
$$

Answer:

$$
x=-3,-4
$$

---

# CHAPTER 4: POLYNOMIAL FUNCTIONS

---

# 1. Polynomial Function

A polynomial is an expression with powers of $x$ like:

$$
x^2, x^3, x^4
$$

Example:

$$
f(x)=3x^2+2x+1
$$

This is a polynomial.

---

# 2. Degree of Polynomial

Degree is the highest power of $x$.

Examples:

$$
2x+1
$$

Degree = 1

$$
x^2+3x+2
$$

Degree = 2

$$
x^5+x^2+1
$$

Degree = 5

---

# 3. Classification by Degree

| Degree | Name |
|---|---|
| 0 | constant |
| 1 | linear |
| 2 | quadratic |
| 3 | cubic |
| 4 | quartic |

---

# 4. Classification by Number of Terms

| Number of terms | Name |
|---|---|
| 1 | monomial |
| 2 | binomial |
| 3 | trinomial |

Examples:

$$
5x
$$

monomial

$$
x+2
$$

binomial

$$
x^2+x+1
$$

trinomial

---

# 5. Addition of Polynomials

Add like terms.

Example:

$$
(2x^2+3x+1)+(x^2+4x+5)
$$

$$
=3x^2+7x+6
$$

---

# 6. Subtraction of Polynomials

Example:

$$
(3x^2+5x+4)-(x^2+2x+1)
$$

$$
=2x^2+3x+3
$$

---

# 7. Multiplication of Polynomials

Example:

$$
(x+2)(x+3)
$$

Multiply each term:

$$
x(x+3)+2(x+3)
$$

$$
=x^2+3x+2x+6
$$

$$
=x^2+5x+6
$$

---

# 8. Division of Polynomial

Example:

$$
\frac{x^2+5x+6}{x+2}
$$

Since:

$$
x^2+5x+6=(x+2)(x+3)
$$

So:

$$
\frac{(x+2)(x+3)}{x+2}=x+3
$$

Answer:

$$
x+3
$$

---

# 9. Zeroes of Polynomial

Zeroes are values of $x$ for which:

$$
f(x)=0
$$

Example:

$$
f(x)=x^2-5x+6
$$

$$
x^2-5x+6=(x-2)(x-3)
$$

Zeroes:

$$
x=2,3
$$

---

# PRACTICE QUESTIONS: POLYNOMIALS

## Q1. Find degree:

$$
f(x)=4x^5+2x^3+x+1
$$

Answer:

$$
5
$$

---

## Q2. Add:

$$
(2x^2+x+3)+(x^2+4x+1)
$$

Answer:

$$
3x^2+5x+4
$$

---

## Q3. Multiply:

$$
(x+4)(x+2)
$$

$$
=x^2+6x+8
$$

Answer:

$$
x^2+6x+8
$$

---

# CHAPTER 5: EXPONENTIAL FUNCTIONS

---

# 1. Vertical Line Test

A graph is a function if any vertical line cuts it at only one point.

If a vertical line cuts graph at more than one point, it is not a function.

Simple meaning:

One input cannot have two outputs.

---

# 2. Horizontal Line Test

Horizontal line test checks if a function is one-one.

If any horizontal line cuts graph at only one point, function is one-one.

One-one functions have inverse functions.

---

# 3. Exponential Function

An exponential function has variable in power.

Example:

$$
f(x)=2^x
$$

Here $x$ is in the exponent.

---

# 4. Laws of Exponents

Very important formulas:

## Law 1

$$
a^m \times a^n = a^{m+n}
$$

Example:

$$
2^3 \times 2^2=2^5
$$

---

## Law 2

$$
\frac{a^m}{a^n}=a^{m-n}
$$

Example:

$$
\frac{2^5}{2^2}=2^3
$$

---

## Law 3

$$
(a^m)^n=a^{mn}
$$

Example:

$$
(2^3)^2=2^6
$$

---

## Law 4

$$
a^0=1
$$

Example:

$$
5^0=1
$$

---

## Law 5

$$
a^{-n}=\frac{1}{a^n}
$$

Example:

$$
2^{-3}=\frac{1}{2^3}=\frac{1}{8}
$$

---

# 5. Graph of $f(x)=2^x$

Make table:

| x | $2^x$ |
|---|---|
| -2 | $1/4$ |
| -1 | $1/2$ |
| 0 | 1 |
| 1 | 2 |
| 2 | 4 |
| 3 | 8 |

Important points:

- Graph always positive
- It passes through $(0,1)$
- It increases fast
- Domain: all real numbers
- Range: positive numbers

$$
(0,\infty)
$$

---

# 6. When $a>1$

For:

$$
f(x)=a^x
$$

if:

$$
a>1
$$

then graph is increasing.

Example:

$$
2^x, 3^x, 10^x
$$

---

# 7. When $0<a<1$

If:

$$
0<a<1
$$

then graph is decreasing.

Example:

$$
\left(\frac{1}{2}\right)^x
$$

As $x$ increases, value becomes smaller.

---

# 8. Natural Exponential Function

Natural exponential is:

$$
e^x
$$

where:

$$
e \approx 2.718
$$

It is very important in mathematics, statistics, data science, and machine learning.

---

# 9. Composition of Functions

Composition means function inside another function.

If:

$$
f(x)=x^2
$$

and:

$$
g(x)=x+1
$$

Then:

$$
(f\circ g)(x)=f(g(x))
$$

First apply $g$, then apply $f$.

$$
g(x)=x+1
$$

Now:

$$
f(g(x))=(x+1)^2
$$

So:

$$
(f\circ g)(x)=(x+1)^2
$$

---

# 10. Inverse Function

Inverse function reverses the function.

If:

$$
f(x)=2x+3
$$

To find inverse:

Step 1:

$$
y=2x+3
$$

Step 2: Swap $x$ and $y$

$$
x=2y+3
$$

Step 3: Solve for $y$

$$
x-3=2y
$$

$$
y=\frac{x-3}{2}
$$

So:

$$
f^{-1}(x)=\frac{x-3}{2}
$$

---

# PRACTICE QUESTIONS: EXPONENTIAL FUNCTIONS

## Q1. Simplify:

$$
2^3 \times 2^4
$$

$$
=2^{3+4}=2^7=128
$$

Answer:

$$
128
$$

---

## Q2. Simplify:

$$
\frac{5^6}{5^2}
$$

$$
=5^{6-2}=5^4=625
$$

Answer:

$$
625
$$

---

## Q3. If $f(x)=2x+5$, find inverse.

$$
y=2x+5
$$

Swap:

$$
x=2y+5
$$

$$
x-5=2y
$$

$$
y=\frac{x-5}{2}
$$

Answer:

$$
f^{-1}(x)=\frac{x-5}{2}
$$

---

# CHAPTER 6: LOGARITHMIC FUNCTIONS

---

# 1. What is Logarithm?

Logarithm is the opposite of exponent.

If:

$$
2^3=8
$$

Then:

$$
\log_2 8=3
$$

Read:

“log base 2 of 8 is 3.”

Simple meaning:

Log asks:  
**2 raised to what power gives 8?**

Answer:

3.

---

# 2. Exponential and Log Relation

$$
a^x=y
$$

is same as:

$$
\log_a y=x
$$

Example:

$$
3^2=9
$$

So:

$$
\log_3 9=2
$$

---

# 3. Conditions for Log

For:

$$
\log_a x
$$

we need:

$$
x>0
$$

and:

$$
a>0,\quad a\neq 1
$$

Important:

You cannot take log of zero or negative number.

---

# 4. Graph of $f(x)=\log_2 x$

Make table:

| x | $\log_2 x$ |
|---|---|
| $1/4$ | -2 |
| $1/2$ | -1 |
| 1 | 0 |
| 2 | 1 |
| 4 | 2 |
| 8 | 3 |

Important points:

- Domain: $x>0$
- Range: all real numbers
- Graph passes through $(1,0)$

---

# 5. When $a>1$

For:

$$
f(x)=\log_a x
$$

if:

$$
a>1
$$

graph is increasing.

Example:

$$
\log_2 x
$$

---

# 6. When $0<a<1$

If:

$$
0<a<1
$$

graph is decreasing.

Example:

$$
\log_{\frac12} x
$$

---

# 7. Natural Logarithm

Natural log has base $e$.

$$
\ln x = \log_e x
$$

where:

$$
e \approx 2.718
$$

---

# 8. Common Logarithm

Common log has base 10.

$$
\log x = \log_{10} x
$$

Example:

$$
\log 100 = 2
$$

because:

$$
10^2=100
$$

---

# 9. Laws of Logarithms

## Law 1: Product Rule

$$
\log_a(MN)=\log_a M+\log_a N
$$

Example:

$$
\log_2(8 \times 4)=\log_2 8+\log_2 4
$$

$$
=3+2=5
$$

---

## Law 2: Quotient Rule

$$
\log_a\left(\frac{M}{N}\right)=\log_a M-\log_a N
$$

Example:

$$
\log_2\left(\frac{8}{4}\right)=\log_2 8-\log_2 4
$$

$$
=3-2=1
$$

---

## Law 3: Power Rule

$$
\log_a(M^n)=n\log_a M
$$

Example:

$$
\log_2(8^2)=2\log_2 8
$$

$$
=2(3)=6
$$

---

## Law 4

$$
\log_a 1=0
$$

because:

$$
a^0=1
$$

---

## Law 5

$$
\log_a a=1
$$

because:

$$
a^1=a
$$

---

# PRACTICE QUESTIONS: LOGARITHMS

## Q1. Evaluate:

$$
\log_2 16
$$

Since:

$$
2^4=16
$$

Answer:

$$
4
$$

---

## Q2. Evaluate:

$$
\log_3 27
$$

Since:

$$
3^3=27
$$

Answer:

$$
3
$$

---

## Q3. Simplify:

$$
\log_2 8+\log_2 4
$$

$$
=3+2=5
$$

Answer:

$$
5
$$

---

# FINAL FORMULA SHEET

## Sets

$$
a \in A
$$

means a belongs to A.

$$
A \subseteq B
$$

means A is subset of B.

---

## Distance Formula

$$
d = \sqrt{(x_2-x_1)^2+(y_2-y_1)^2}
$$

---

## Midpoint Formula

$$
\left(\frac{x_1+x_2}{2}, \frac{y_1+y_2}{2}\right)
$$

---

## Slope Formula

$$
m=\frac{y_2-y_1}{x_2-x_1}
$$

---

## Line Equation

$$
y=mx+c
$$

---

## Point-Slope Form

$$
y-y_1=m(x-x_1)
$$

---

## Quadratic Function

$$
f(x)=ax^2+bx+c
$$

---

## Axis of Symmetry

$$
x=\frac{-b}{2a}
$$

---

## Quadratic Formula

$$
x=\frac{-b\pm \sqrt{b^2-4ac}}{2a}
$$

---

## Exponent Laws

$$
a^m a^n=a^{m+n}
$$

$$
\frac{a^m}{a^n}=a^{m-n}
$$

$$
(a^m)^n=a^{mn}
$$

$$
a^0=1
$$

$$
a^{-n}=\frac{1}{a^n}
$$

---

## Log Laws

$$
\log_a(MN)=\log_a M+\log_a N
$$

$$
\log_a\left(\frac{M}{N}\right)=\log_a M-\log_a N
$$

$$
\log_a(M^n)=n\log_a M
$$

---

# MIXED PRACTICE QUESTIONS

Try these yourself first.

---

## Q1. Is $-7$ an integer?

Answer:

Yes.

---

## Q2. Is $\frac{5}{2}$ rational?

Answer:

Yes.

---

## Q3. Find $23 \mod 5$.

$$
23=5\times 4+3
$$

Answer:

$$
3
$$

---

## Q4. If $A=\{1,2,3\}$, is $\{1,2\}\subseteq A$?

Answer:

Yes.

---

## Q5. Find slope between $(1,1)$ and $(3,5)$.

$$
m=\frac{5-1}{3-1}=\frac{4}{2}=2
$$

Answer:

$$
2
$$

---

## Q6. Solve:

$$
x^2-9=0
$$

$$
(x-3)(x+3)=0
$$

Answer:

$$
x=3,-3
$$

---

## Q7. Find degree:

$$
7x^4+3x^2+1
$$

Answer:

$$
4
$$

---

## Q8. Simplify:

$$
3^2 \times 3^5
$$

$$
=3^7
$$

Answer:

$$
3^7
$$

---

## Q9. Evaluate:

$$
\log_{10}1000
$$

Since:

$$
10^3=1000
$$

Answer:

$$
3
$$

---

## Q10. Find inverse of:

$$
f(x)=x+4
$$

Let:

$$
y=x+4
$$

Swap:

$$
x=y+4
$$

$$
y=x-4
$$

Answer:

$$
f^{-1}(x)=x-4
$$

---

# How You Should Study This PDF

Study in this order:

1. Number systems  
2. Sets  
3. Relations  
4. Functions  
5. Straight lines  
6. Quadratic functions  
7. Polynomials  
8. Exponents  
9. Logarithms  

Do not try to learn everything in one day.

A good plan:

| Day | Topic |
|---|---|
| Day 1 | Numbers and sets |
| Day 2 | Relations and functions |
| Day 3 | Straight lines |
| Day 4 | Quadratic functions |
| Day 5 | Polynomials |
| Day 6 | Exponential functions |
| Day 7 | Logarithms + revision |

Most important idea:

**Function means one input gives one output.**  
**Logarithm is opposite of exponent.**  
**Slope means steepness.**  
**Quadratic graph is parabola.**

---

# BEFORE CALCULUS: Basic Things You Must Know

## 1. What is a Function?

A function is like a machine that takes an input, processes it, and gives an output. Functions are everywhere in real life! For example:

- **Temperature Conversion**: Converting Celsius to Fahrenheit is a function: $f(C) = 1.8C + 32$.
- **Bank Interest**: Calculating interest earned on savings: $f(P) = P(1 + r)^t$.

Example:

$$
f(x)=2x+3
$$

If input is $x=1$:

$$
f(1)=2(1)+3=5
$$

If input is $x=4$:

$$
f(4)=2(4)+3=11
$$

So:

| Input $x$ | Output $f(x)$ |
|---|---|
| 1 | 5 |
| 4 | 11 |

Very important:

> One input must give only one output.

---

## 2. Graph of a Function

A graph is a picture of a function. It helps us visualize how the function behaves.

Example:

$$
f(x)=x^2
$$

Make table:

| $x$ | $f(x)=x^2$ |
|---|---|
| -2 | 4 |
| -1 | 1 |
| 0 | 0 |
| 1 | 1 |
| 2 | 4 |

Then plot points:

$$
(-2,4),(-1,1),(0,0),(1,1),(2,4)
$$

The graph becomes a U-shape called parabola.

---

## 3. Types of Functions

### Linear Function

Linear functions are used in real life to calculate things like total cost or distance.

$$
f(x)=mx+c
$$

Example:

$$
f(x)=2x+1
$$

Graph is a straight line.

---

### Quadratic Function

Quadratic functions are used to model things like projectile motion.

$$
f(x)=ax^2+bx+c
$$

Example:

$$
f(x)=x^2+2x+1
$$

Graph is a parabola.

---

### Exponential Function

Exponential functions are used in population growth, radioactive decay, etc.

Example:

$$
f(x)=2^x
$$

Here $x$ is in the power.

---

# CHAPTER 1: LIMITS AND CONTINUITY

---

# 1. What is a Limit?

Limit means:

> What value is the function getting close to?

Real-life example:

- Imagine a car approaching a red light. The car slows down and gets closer to the light. The "limit" is the position of the car as it approaches the light.

Suppose:

$$
f(x)=x+2
$$

If $x$ gets close to 3, then $f(x)$ gets close to:

$$
3+2=5
$$

So:

$$
\lim_{x\to 3}(x+2)=5
$$

Read as:

“Limit of $x+2$ as $x$ approaches 3 is 5.”

---

## Practice Questions

1. Find:

$$
\lim_{x\to 5}(3x+2)
$$

2. Evaluate:

$$
\lim_{x\to -2}(x^2+4x+4)
$$

3. Real-life application: A car's speed $v(t)$ is given by $v(t) = 5t + 10$. Find the speed as $t \to 2$.

---

# 2. Important: $x\to a$ Does Not Always Mean $x=a$

This is very important.

$$
x\to 3
$$

means $x$ is going near 3, like:

$$
2.9,\ 2.99,\ 2.999
$$

or:

$$
3.1,\ 3.01,\ 3.001
$$

It may not be exactly 3.

---

# 3. Direct Substitution Method

For simple limits, just put the value.

Example:

$$
\lim_{x\to 2}(x^2+3x)
$$

Put $x=2$:

$$
=2^2+3(2)
$$

$$
=4+6=10
$$

Answer:

$$
10
$$

---

## Practice 1

Find:

$$
\lim_{x\to 4}(2x+1)
$$

Solution:

Put $x=4$:

$$
2(4)+1=9
$$

Answer:

$$
9
$$

---

# 4. Left-Hand Limit and Right-Hand Limit

Sometimes we check limit from left side and right side.

## Left-Hand Limit

$$
\lim_{x\to a^-}f(x)
$$

Means $x$ approaches $a$ from smaller values.

Example:

For $a=3$:

$$
2.9,\ 2.99,\ 2.999
$$

---

## Right-Hand Limit

$$
\lim_{x\to a^+}f(x)
$$

Means $x$ approaches $a$ from bigger values.

Example:

$$
3.1,\ 3.01,\ 3.001
$$

---

## Limit Exists When Both Are Equal

$$
\lim_{x\to a^-}f(x)=\lim_{x\to a^+}f(x)
$$

If left limit and right limit are same, then limit exists.

If they are different, limit does not exist.

---

# 5. Example of Limit Not Existing

Suppose:

$$
f(x)=
\begin{cases}
1, & x<0\\
2, & x>0
\end{cases}
$$

As $x\to 0^-$, function value is 1.

$$
\lim_{x\to 0^-}f(x)=1
$$

As $x\to 0^+$, function value is 2.

$$
\lim_{x\to 0^+}f(x)=2
$$

Since:

$$
1\neq 2
$$

Limit does not exist.

---

# 6. Limit of a Sequence

A sequence is a list of numbers.

Example:

$$
1,\frac12,\frac13,\frac14,\frac15,\dots
$$

This sequence is:

$$
a_n=\frac1n
$$

As $n$ becomes very large:

$$
\frac1n \to 0
$$

So:

$$
\lim_{n\to\infty}\frac1n=0
$$

Simple meaning:

As $n$ grows bigger and bigger, $\frac1n$ gets closer and closer to 0.

---

## Common Sequence Limits

### 1.

$$
\lim_{n\to\infty}\frac1n=0
$$

### 2.

$$
\lim_{n\to\infty}\frac{1}{n^2}=0
$$

### 3.

$$
\lim_{n\to\infty}\frac{n}{n+1}=1
$$

Why?

Divide numerator and denominator by $n$:

$$
\frac{n}{n+1}=\frac{1}{1+\frac1n}
$$

As $n\to\infty$:

$$
\frac1n\to 0
$$

So:

$$
\frac{1}{1+0}=1
$$

---

# 7. Limit at Infinity

Limit at infinity means:

> What happens when $x$ becomes very large?

Example:

$$
\lim_{x\to\infty}\frac1x=0
$$

Because when $x$ becomes bigger:

$$
\frac1x
$$

becomes smaller.

Examples:

$$
\frac1{10}=0.1
$$

$$
\frac1{100}=0.01
$$

$$
\frac1{1000}=0.001
$$

So it goes to 0.

---

# 8. Limits of Fractions / Rational Functions

Example:

$$
\lim_{x\to\infty}\frac{2x+1}{x+3}
$$

For large $x$, highest powers matter.

Divide numerator and denominator by $x$:

$$
\frac{2x+1}{x+3}
=
\frac{2+\frac1x}{1+\frac3x}
$$

As $x\to\infty$:

$$
\frac1x\to 0,\quad \frac3x\to 0
$$

So:

$$
\frac{2+0}{1+0}=2
$$

Answer:

$$
2
$$

---

# 9. Continuity

Continuity means:

> You can draw the graph without lifting your pen.

A function is continuous at $x=a$ if:

1. $f(a)$ exists  
2. $\lim_{x\to a}f(x)$ exists  
3. $\lim_{x\to a}f(x)=f(a)$

---

## Simple Example

$$
f(x)=x+2
$$

This is continuous everywhere because it is a straight line.

---

## Discontinuous Example

$$
f(x)=\frac1{x-2}
$$

At $x=2$, denominator becomes zero:

$$
2-2=0
$$

Division by zero is not allowed.

So $f(x)$ is not continuous at $x=2$.

---

# 10. Types of Discontinuity

## 1. Removable Discontinuity

There is a hole in the graph.

Example:

$$
f(x)=\frac{x^2-1}{x-1}
$$

Factor numerator:

$$
x^2-1=(x-1)(x+1)
$$

So:

$$
f(x)=\frac{(x-1)(x+1)}{x-1}
$$

Cancel $x-1$:

$$
f(x)=x+1
$$

But originally $x=1$ was not allowed because denominator becomes 0.

So there is a hole at $x=1$.

---

## 2. Jump Discontinuity

Left and right limits are different.

Example:

$$
f(x)=
\begin{cases}
1, & x<0\\
2, & x>0
\end{cases}
$$

There is a jump at 0.

---

## 3. Infinite Discontinuity

Function goes to infinity.

Example:

$$
f(x)=\frac1x
$$

At $x=0$, function becomes infinite/undefined.

---

# PRACTICE QUESTIONS: LIMITS AND CONTINUITY

## Q1. Find:

$$
\lim_{x\to 3}(x+5)
$$

Solution:

Put $x=3$:

$$
3+5=8
$$

Answer:

$$
8
$$

---

## Q2. Find:

$$
\lim_{x\to 2}(x^2+1)
$$

$$
2^2+1=5
$$

Answer:

$$
5
$$

---

## Q3. Find:

$$
\lim_{x\to\infty}\frac1x
$$

Answer:

$$
0
$$

---

## Q4. Find:

$$
\lim_{x\to\infty}\frac{3x+2}{x+5}
$$

Divide by $x$:

$$
\frac{3+\frac2x}{1+\frac5x}
$$

As $x\to\infty$:

$$
\frac2x\to 0,\quad \frac5x\to 0
$$

Answer:

$$
3
$$

---

## Q5. Is $f(x)=x^2$ continuous?

Answer:

Yes, $x^2$ is continuous for all real numbers.

---

# CHAPTER 2: DIFFERENTIATION

---

# 1. What is Differentiation?

Differentiation means finding the **rate of change**.

Simple examples:

- Speed = rate of change of distance
- Slope = rate of change of graph
- Profit change = rate of change of profit
- Temperature change = rate of change of temperature

Derivative tells:

> How fast $y$ changes when $x$ changes.

---

# 2. Slope of a Straight Line

For a straight line:

$$
y=mx+c
$$

The slope is $m$.

Example:

$$
y=3x+2
$$

Slope is:

$$
3
$$

This means:

If $x$ increases by 1, $y$ increases by 3.

---

# 3. Slope Between Two Points

If points are:

$$
(x_1,y_1), (x_2,y_2)
$$

Slope:

$$
m=\frac{y_2-y_1}{x_2-x_1}
$$

Example:

Find slope between:

$$
(1,2),(3,6)
$$

$$
m=\frac{6-2}{3-1}
$$

$$
m=\frac4 2=2
$$

Answer:

$$
2
$$

---

# 4. Derivative Meaning

For curved graph, slope keeps changing.

Derivative gives slope at one exact point.

Symbol:

$$
f'(x)
$$

or:

$$
\frac{dy}{dx}
$$

Both mean derivative.

---

# 5. Derivative from First Principle

Definition:

$$
f'(x)=\lim_{h\to 0}\frac{f(x+h)-f(x)}{h}
$$

Don’t panic.

Simple meaning:

$$
\frac{f(x+h)-f(x)}{h}
$$

means change in $y$ divided by change in $x$.

That is slope.

When $h\to 0$, we get slope at a point.

---

## Example: Derivative of $x^2$

Let:

$$
f(x)=x^2
$$

Formula:

$$
f'(x)=\lim_{h\to 0}\frac{f(x+h)-f(x)}{h}
$$

Now:

$$
f(x+h)=(x+h)^2
$$

So:

$$
f'(x)=\lim_{h\to 0}\frac{(x+h)^2-x^2}{h}
$$

Expand:

$$
(x+h)^2=x^2+2xh+h^2
$$

So:

$$
f'(x)=\lim_{h\to 0}\frac{x^2+2xh+h^2-x^2}{h}
$$

Cancel $x^2$:

$$
=\lim_{h\to 0}\frac{2xh+h^2}{h}
$$

Take $h$ common:

$$
=\lim_{h\to 0}\frac{h(2x+h)}{h}
$$

Cancel $h$:

$$
=\lim_{h\to 0}(2x+h)
$$

Put $h=0$:

$$
=2x
$$

So:

$$
\frac{d}{dx}(x^2)=2x
$$

---

# 6. Basic Derivative Rules

These are very important.

---

## Rule 1: Constant Rule

Derivative of a constant is 0.

$$
\frac{d}{dx}(5)=0
$$

$$
\frac{d}{dx}(100)=0
$$

Why?

Constant does not change.

---

## Rule 2: Derivative of $x$

$$
\frac{d}{dx}(x)=1
$$

---

## Rule 3: Power Rule

$$
\frac{d}{dx}(x^n)=nx^{n-1}
$$

Examples:

$$
\frac{d}{dx}(x^2)=2x
$$

$$
\frac{d}{dx}(x^3)=3x^2
$$

$$
\frac{d}{dx}(x^5)=5x^4
$$

---

## Rule 4: Constant Multiple Rule

$$
\frac{d}{dx}(cf(x))=c f'(x)
$$

Example:

$$
\frac{d}{dx}(5x^2)=5(2x)=10x
$$

---

## Rule 5: Sum Rule

$$
\frac{d}{dx}[f(x)+g(x)]=f'(x)+g'(x)
$$

Example:

$$
\frac{d}{dx}(x^2+x)=2x+1
$$

---

## Rule 6: Difference Rule

$$
\frac{d}{dx}[f(x)-g(x)]=f'(x)-g'(x)
$$

Example:

$$
\frac{d}{dx}(x^3-x^2)=3x^2-2x
$$

---

# 7. Common Derivatives Table

Memorize this table slowly.

| Function | Derivative |
|---|---|
| \(c\) | \(0\) |
| \(x\) | \(1\) |
| \(x^n\) | \(nx^{n-1}\) |
| \(e^x\) | \(e^x\) |
| \(a^x\) | \(a^x\ln a\) |
| \(\ln x\) | \(\frac1x\) |
| \(\sin x\) | \(\cos x\) |
| \(\cos x\) | \(-\sin x\) |
| \(\tan x\) | \(\sec^2 x\) |

---

# 8. Product Rule

Use when two functions are multiplied.

$$
\frac{d}{dx}[u v]=u'v+uv'
$$

Example:

$$
y=x^2\sin x
$$

Here:

$$
u=x^2,\quad v=\sin x
$$

$$
u'=2x,\quad v'=\cos x
$$

So:

$$
y'=2x\sin x+x^2\cos x
$$

---

# 9. Quotient Rule

Use when one function is divided by another.

$$
\frac{d}{dx}\left(\frac{u}{v}\right)=\frac{u'v-uv'}{v^2}
$$

Example:

$$
y=\frac{x^2}{x+1}
$$

Here:

$$
u=x^2,\quad v=x+1
$$

$$
u'=2x,\quad v'=1
$$

$$
y'=\frac{2x(x+1)-x^2(1)}{(x+1)^2}
$$

$$
=\frac{2x^2+2x-x^2}{(x+1)^2}
$$

$$
=\frac{x^2+2x}{(x+1)^2}
$$

---

# 10. Chain Rule

Use when function is inside another function.

Example:

$$
y=(3x+1)^5
$$

Outer function: power 5  
Inner function: \(3x+1\)

Chain rule:

$$
\frac{d}{dx}[u^n]=nu^{n-1}\cdot u'
$$

Here:

$$
u=3x+1
$$

$$
u'=3
$$

So:

$$
y'=5(3x+1)^4\cdot 3
$$

$$
y'=15(3x+1)^4
$$

---

# 11. Differentiability

A function is differentiable at a point if derivative exists there.

Simple meaning:

> The graph must be smooth at that point.

If graph has sharp corner, derivative may not exist.

Example:

$$
f(x)=|x|
$$

At \(x=0\), graph has sharp corner.

So derivative does not exist at \(x=0\).

---

# 12. Important Fact

If a function is differentiable, then it is continuous.

But if a function is continuous, it may not be differentiable.

Example:

$$
f(x)=|x|
$$

It is continuous at 0 but not differentiable at 0.

---

# 13. L’Hospital’s Rule

This is used for difficult limits.

Use when direct substitution gives:

$$
\frac00
$$

or:

$$
\frac{\infty}{\infty}
$$

Formula:

$$
\lim_{x\to a}\frac{f(x)}{g(x)}
=
\lim_{x\to a}\frac{f'(x)}{g'(x)}
$$

if conditions are satisfied.

---

## Example

Find:

$$
\lim_{x\to 0}\frac{\sin x}{x}
$$

Direct substitution:

$$
\frac{\sin 0}{0}=\frac00
$$

Use L’Hospital:

Derivative of numerator:

$$
\frac{d}{dx}(\sin x)=\cos x
$$

Derivative of denominator:

$$
\frac{d}{dx}(x)=1
$$

So:

$$
\lim_{x\to 0}\frac{\sin x}{x}
=
\lim_{x\to 0}\frac{\cos x}{1}
$$

Put \(x=0\):

$$
\frac{\cos 0}{1}=1
$$

Answer:

$$
1
$$

---

## Another Example

$$
\lim_{x\to 0}\frac{e^x-1}{x}
$$

Direct substitution:

$$
\frac{1-1}{0}=\frac00
$$

Use L’Hospital:

$$
\frac{d}{dx}(e^x-1)=e^x
$$

$$
\frac{d}{dx}(x)=1
$$

So:

$$
\lim_{x\to 0}\frac{e^x-1}{x}
=
\lim_{x\to 0}e^x
$$

$$
=e^0=1
$$

---

# 14. Tangent Line

A tangent line touches a curve at one point and has same slope as curve there.

Equation of tangent line:

$$
y-y_1=m(x-x_1)
$$

where:

$$
m=f'(x_1)
$$

---

## Example

Find tangent to:

$$
f(x)=x^2
$$

at \(x=2\).

Step 1: Find point.

$$
f(2)=2^2=4
$$

Point:

$$
(2,4)
$$

Step 2: Find derivative.

$$
f'(x)=2x
$$

Step 3: Find slope at \(x=2\).

$$
f'(2)=2(2)=4
$$

So slope \(m=4\).

Step 4: Use tangent formula.

$$
y-4=4(x-2)
$$

$$
y-4=4x-8
$$

$$
y=4x-4
$$

Answer:

$$
y=4x-4
$$

---

# 15. Linear Approximation

Linear approximation means using tangent line to estimate nearby values.

Formula:

$$
f(x)\approx f(a)+f'(a)(x-a)
$$

Example:

Estimate:

$$
\sqrt{4.1}
$$

Let:

$$
f(x)=\sqrt{x}
$$

Choose easy point:

$$
a=4
$$

because \(\sqrt4=2\).

$$
f(4)=2
$$

Derivative:

$$
f'(x)=\frac{1}{2\sqrt{x}}
$$

$$
f'(4)=\frac{1}{2\cdot2}=\frac14
$$

Now:

$$
f(4.1)\approx f(4)+f'(4)(4.1-4)
$$

$$
=2+\frac14(0.1)
$$

$$
=2+0.025
$$

$$
=2.025
$$

So:

$$
\sqrt{4.1}\approx 2.025
$$

---

# 16. Critical Points

Critical points are points where:

$$
f'(x)=0
$$

or derivative does not exist.

They help us find maximum/minimum.

---

# 17. Local Maximum and Local Minimum

## Local Maximum

A point is local maximum if nearby values are smaller.

Like top of a hill.

## Local Minimum

A point is local minimum if nearby values are bigger.

Like bottom of a valley.

---

# 18. First Derivative Test

Step method:

1. Find \(f'(x)\)
2. Solve \(f'(x)=0\)
3. Check sign of derivative before and after critical point

If derivative changes:

$$
+ \to -
$$

then local maximum.

If derivative changes:

$$
- \to +
$$

then local minimum.

---

## Example

Find local max/min of:

$$
f(x)=x^2-4x+3
$$

Step 1:

$$
f'(x)=2x-4
$$

Step 2:

$$
2x-4=0
$$

$$
2x=4
$$

$$
x=2
$$

Step 3: Check value:

$$
f(2)=2^2-4(2)+3
$$

$$
=4-8+3=-1
$$

Since parabola opens upward, this is minimum.

Answer:

Local minimum at:

$$
(2,-1)
$$

---

# 19. Global Maximum and Minimum

Global means biggest/smallest value on whole interval.

For closed interval \([a,b]\), do this:

1. Find critical points inside interval
2. Find function value at critical points
3. Find function value at endpoints
4. Compare values

Largest value = global maximum  
Smallest value = global minimum

---

## Example

Find global max/min of:

$$
f(x)=x^2
$$

on:

$$
[-1,2]
$$

Step 1:

$$
f'(x)=2x
$$

Step 2:

$$
2x=0
$$

$$
x=0
$$

Step 3: Check values at \(-1,0,2\)

$$
f(-1)=1
$$

$$
f(0)=0
$$

$$
f(2)=4
$$

Smallest = 0  
Largest = 4

Global minimum:

$$
0 \text{ at } x=0
$$

Global maximum:

$$
4 \text{ at } x=2
$$

---

# PRACTICE QUESTIONS: DIFFERENTIATION

## Q1. Differentiate:

$$
f(x)=x^3
$$

Answer:

$$
f'(x)=3x^2
$$

---

## Q2. Differentiate:

$$
f(x)=5x^2+3x+7
$$

Solution:

$$
f'(x)=10x+3
$$

---

## Q3. Differentiate:

$$
f(x)=\sin x+x^2
$$

Answer:

$$
f'(x)=\cos x+2x
$$

---

## Q4. Differentiate:

$$
f(x)=(2x+1)^4
$$

Using chain rule:

$$
f'(x)=4(2x+1)^3\cdot 2
$$

$$
=8(2x+1)^3
$$

---

## Q5. Find tangent to:

$$
f(x)=x^2+1
$$

at \(x=1\).

Step 1:

$$
f(1)=1^2+1=2
$$

Point:

$$
(1,2)
$$

Step 2:

$$
f'(x)=2x
$$

$$
f'(1)=2
$$

Tangent:

$$
y-2=2(x-1)
$$

$$
y=2x
$$

Answer:

$$
y=2x
$$

---

# CHAPTER 3: INTEGRATION

---

# 1. What is Integration?

Integration is opposite of differentiation.

Differentiation breaks change into small pieces.

Integration adds small pieces together.

Simple meanings of integration:

- Area under curve
- Total distance from speed
- Total profit from profit rate
- Total quantity from rate

---

# 2. Area Under Curve

Suppose graph is:

$$
y=f(x)
$$

Area from \(x=a\) to \(x=b\) is:

$$
\int_a^b f(x)\,dx
$$

This is called a definite integral.

---

# 3. Rectangle Idea

Area of rectangle:

$$
\text{Area}=\text{base}\times \text{height}
$$

For curve, we divide area into many thin rectangles.

Each rectangle area is approximately:

$$
f(x)\Delta x
$$

Add them:

$$
\sum f(x)\Delta x
$$

When rectangles become very thin, we get exact area:

$$
\int_a^b f(x)\,dx
$$

This is the idea of Riemann sum.

---

# 4. Riemann Sum

Riemann sum means approximating area using rectangles.

Formula:

$$
\sum_{i=1}^n f(x_i^*)\Delta x
$$

Where:

- \(\Delta x\) = width of each rectangle
- \(f(x_i^*)\) = height of rectangle

As number of rectangles becomes very large:

$$
n\to\infty
$$

we get exact integral.

---

# 5. Definite Integral

A definite integral has limits:

$$
\int_a^b f(x)\,dx
$$

It gives a number.

Example:

$$
\int_0^2 x\,dx
$$

This means area under \(y=x\) from \(x=0\) to \(x=2\).

---

# 6. Indefinite Integral

Indefinite integral has no limits:

$$
\int f(x)\,dx
$$

It gives a function.

Example:

$$
\int 2x\,dx=x^2+C
$$

Why \(+C\)?

Because derivative of any constant is 0.

$$
\frac{d}{dx}(x^2+5)=2x
$$

$$
\frac{d}{dx}(x^2+100)=2x
$$

So we write general answer:

$$
x^2+C
$$

---

# 7. Basic Integration Rules

## Rule 1: Power Rule

$$
\int x^n\,dx=\frac{x^{n+1}}{n+1}+C
$$

where:

$$
n\neq -1
$$

Example:

$$
\int x^2\,dx=\frac{x^3}{3}+C
$$

---

## Rule 2: Constant Rule

$$
\int c\,dx=cx+C
$$

Example:

$$
\int 5\,dx=5x+C
$$

---

## Rule 3: Constant Multiple Rule

$$
\int c f(x)\,dx=c\int f(x)\,dx
$$

Example:

$$
\int 3x^2\,dx=3\int x^2\,dx
$$

$$
=3\cdot \frac{x^3}{3}
$$

$$
=x^3+C
$$

---

## Rule 4: Sum Rule

$$
\int [f(x)+g(x)]dx=\int f(x)dx+\int g(x)dx
$$

Example:

$$
\int (x^2+x)dx
$$

$$
=\frac{x^3}{3}+\frac{x^2}{2}+C
$$

---

# 8. Common Integrals Table

| Function | Integral |
|---|---|
| \(x^n\) | \(\frac{x^{n+1}}{n+1}+C\) |
| \(1\) | \(x+C\) |
| \(e^x\) | \(e^x+C\) |
| \(\frac1x\) | \(\ln|x|+C\) |
| \(\cos x\) | \(\sin x+C\) |
| \(\sin x\) | \(-\cos x+C\) |
| \(\sec^2 x\) | \(\tan x+C\) |

---

# 9. Definite Integral Calculation

To calculate:

$$
\int_a^b f(x)\,dx
$$

Step 1: Find antiderivative \(F(x)\)

Step 2: Put upper limit \(b\)

Step 3: Put lower limit \(a\)

Step 4: Subtract:

$$
F(b)-F(a)
$$

---

## Example

Find:

$$
\int_0^2 x\,dx
$$

Step 1:

$$
\int x\,dx=\frac{x^2}{2}
$$

Step 2:

$$
\left[\frac{x^2}{2}\right]_0^2
$$

Step 3:

$$
\frac{2^2}{2}-\frac{0^2}{2}
$$

$$
=\frac4 2-0
$$

$$
=2
$$

Answer:

$$
2
$$

---

# 10. Fundamental Theorem of Calculus

This connects differentiation and integration.

If:

$$
F'(x)=f(x)
$$

then:

$$
\int_a^b f(x)\,dx=F(b)-F(a)
$$

Simple meaning:

> To find area, find reverse derivative and subtract values.

---

# 11. Substitution Method

Use when function has something inside another function.

Example:

$$
\int 2x(x^2+1)^3dx
$$

Let:

$$
u=x^2+1
$$

Differentiate:

$$
du=2x\,dx
$$

So integral becomes:

$$
\int u^3du
$$

$$
=\frac{u^4}{4}+C
$$

Put back:

$$
=\frac{(x^2+1)^4}{4}+C
$$

---

# 12. Integration by Parts

Use when two functions are multiplied.

Formula:

$$
\int u v\,dx=u\int vdx-\int \left(u'\int vdx\right)dx
$$

Common form:

$$
\int u\,dv=uv-\int v\,du
$$

Remember:

> Product rule reversed.

---

## Example

Find:

$$
\int x e^x dx
$$

Choose:

$$
u=x
$$

$$
dv=e^x dx
$$

Then:

$$
du=dx
$$

$$
v=e^x
$$

Formula:

$$
\int u\,dv=uv-\int v\,du
$$

$$
=x e^x-\int e^x dx
$$

$$
=x e^x-e^x+C
$$

Answer:

$$
e^x(x-1)+C
$$

---

# 13. Properties of Definite Integral

## Property 1

$$
\int_a^a f(x)dx=0
$$

Area from same point to same point is zero.

---

## Property 2

$$
\int_a^b f(x)dx=-\int_b^a f(x)dx
$$

Changing limits changes sign.

---

## Property 3

$$
\int_a^b [f(x)+g(x)]dx
=
\int_a^b f(x)dx+\int_a^b g(x)dx
$$

---

## Property 4

$$
\int_a^b c f(x)dx=c\int_a^b f(x)dx
$$

---

## Property 5

If \(a<c<b\), then:

$$
\int_a^b f(x)dx=\int_a^c f(x)dx+\int_c^b f(x)dx
$$

---

# 14. Piecewise Function Integration

Piecewise means function has different formulas in different intervals.

Example:

$$
f(x)=
\begin{cases}
x, & 0\le x\le 1\\
2, & 1<x\le 3
\end{cases}
$$

Find:

$$
\int_0^3 f(x)dx
$$

Break at \(x=1\):

$$
\int_0^3 f(x)dx=\int_0^1 xdx+\int_1^3 2dx
$$

First part:

$$
\int_0^1 xdx=\left[\frac{x^2}{2}\right]_0^1
$$

$$
=\frac12
$$

Second part:

$$
\int_1^3 2dx=[2x]_1^3
$$

$$
=6-2=4
$$

Total:

$$
\frac12+4=\frac92
$$

Answer:

$$
\frac92
$$

---

# PRACTICE QUESTIONS: INTEGRATION

## Q1. Find:

$$
\int x^3dx
$$

Solution:

$$
\int x^3dx=\frac{x^4}{4}+C
$$

---

## Q2. Find:

$$
\int (2x+3)dx
$$

$$
=\int 2xdx+\int 3dx
$$

$$
=x^2+3x+C
$$

---

## Q3. Find:

$$
\int_0^1 x^2dx
$$

$$
=\left[\frac{x^3}{3}\right]_0^1
$$

$$
=\frac13-0
$$

Answer:

$$
\frac13
$$

---

## Q4. Find:

$$
\int e^x dx
$$

Answer:

$$
e^x+C
$$

---

## Q5. Find:

$$
\int 2x(x^2+4)^5dx
$$

Let:

$$
u=x^2+4
$$

$$
du=2x dx
$$

So:

$$
\int u^5du=\frac{u^6}{6}+C
$$

Answer:

$$
\frac{(x^2+4)^6}{6}+C
$$

---

# FINAL FORMULA SHEET

## Limits

$$
\lim_{x\to a}f(x)
$$

means value of $f(x)$ as $x$ goes near $a$.

---

## Continuity

Function is continuous at $x=a$ if:

$$
\lim_{x\to a}f(x)=f(a)
$$

---

## Derivative Definition

$$
f'(x)=\lim_{h\to 0}\frac{f(x+h)-f(x)}{h}
$$

---

## Basic Derivatives

$$
\frac{d}{dx}(c)=0
$$

$$
\frac{d}{dx}(x)=1
$$

$$
\frac{d}{dx}(x^n)=nx^{n-1}
$$

$$
\frac{d}{dx}(e^x)=e^x
$$

$$
\frac{d}{dx}(\ln x)=\frac1x
$$

$$
\frac{d}{dx}(\sin x)=\cos x
$$

$$
\frac{d}{dx}(\cos x)=-\sin x
$$

---

## Product Rule

$$
(uv)'=u'v+uv'
$$

---

## Quotient Rule

$$
\left(\frac uv\right)'=\frac{u'v-uv'}{v^2}
$$

---

## Chain Rule

$$
\frac{d}{dx}[f(g(x))]=f'(g(x))g'(x)
$$

---

## Tangent Line

$$
y-y_1=m(x-x_1)
$$

where:

$$
m=f'(x_1)
$$

---

## L’Hospital Rule

If limit gives:

$$
\frac00
$$

or:

$$
\frac{\infty}{\infty}
$$

then:

$$
\lim \frac{f(x)}{g(x)}=\lim \frac{f'(x)}{g'(x)}
$$

if conditions are satisfied.

---

## Integration Power Rule

$$
\int x^n dx=\frac{x^{n+1}}{n+1}+C
$$

---

## Definite Integral

$$
\int_a^b f(x)dx=F(b)-F(a)
$$

where:

$$
F'(x)=f(x)
$$

---

# MIXED PRACTICE QUESTIONS WITH ANSWERS

---

## Q1. Find:

$$
\lim_{x\to 5}(x^2-1)
$$

Solution:

$$
5^2-1=24
$$

Answer:

$$
24
$$

---

## Q2. Find:

$$
\lim_{x\to\infty}\frac{5x+1}{2x+3}
$$

Highest powers matter:

$$
\frac{5x}{2x}=\frac52
$$

Answer:

$$
\frac52
$$

---

## Q3. Differentiate:

$$
f(x)=4x^3+2x^2+x+10
$$

$$
f'(x)=12x^2+4x+1
$$

---

## Q4. Differentiate:

$$
f(x)=e^x+x^2
$$

$$
f'(x)=e^x+2x
$$

---

## Q5. Differentiate:

$$
f(x)=(x^2+1)^3
$$

Chain rule:

$$
f'(x)=3(x^2+1)^2(2x)
$$

$$
=6x(x^2+1)^2
$$

---

## Q6. Find critical point of:

$$
f(x)=x^2-6x+5
$$

$$
f'(x)=2x-6
$$

Set zero:

$$
2x-6=0
$$

$$
x=3
$$

Answer:

$$
x=3
$$

---

## Q7. Find:

$$
\int x^4dx
$$

$$
=\frac{x^5}{5}+C
$$

---

## Q8. Find:

$$
\int (3x^2+2x+1)dx
$$

$$
=x^3+x^2+x+C
$$

---

## Q9. Find:

$$
\int_0^2 3x^2dx
$$

$$
=\left[x^3\right]_0^2
$$

$$
=8-0=8
$$

Answer:

$$
8
$$

---

## Q10. Find:

$$
\int \frac1x dx
$$

Answer:

$$
\ln|x|+C
$$

---

# HOW TO STUDY THIS CALCULUS PDF IF YOU DID NOT HAVE MATHS IN 11TH/12TH

Follow this order. Do not jump directly to difficult questions.

## Week 1: Basics

Study:

1. Functions  
2. Graphs  
3. Powers  
4. Basic algebra  
5. Lines and slopes  

You must understand:

$$
f(x),\quad x^2,\quad \sqrt{x},\quad \frac1x
$$

---

## Week 2: Limits and Continuity

Study:

1. Direct substitution limits  
2. Left and right limits  
3. Limits at infinity  
4. Continuity  

Practice at least 20 simple limits.

---

## Week 3: Differentiation

Study:

1. Meaning of derivative  
2. Power rule  
3. Sum rule  
4. Product rule  
5. Quotient rule  
6. Chain rule  

Practice 30 derivative questions.

---

## Week 4: Applications of Derivative

Study:

1. Tangent line  
2. Increasing/decreasing  
3. Critical points  
4. Max/min problems  
5. L’Hospital rule  

---

## Week 5: Integration

Study:

1. Antiderivative  
2. Power rule  
3. Definite integral  
4. Area under curve  
5. Substitution  
6. Integration by parts  

---

# Most Important Simple Summary

| Topic | Simple Meaning |
|---|---|
| Function | Input-output machine |
| Limit | Value function approaches |
| Continuity | No break in graph |
| Derivative | Slope / rate of change |
| Tangent | Line touching curve at a point |
| Critical point | Where derivative is 0 or undefined |
| Maximum | Highest value |
| Minimum | Lowest value |
| Integration | Area / total quantity |
| Definite integral | Area between two limits |
| Indefinite integral | Reverse derivative |

---

# One-Line Memory Trick

Calculus has two main ideas:

$$
\boxed{\text{Differentiation = slope/change}}
$$

$$
\boxed{\text{Integration = area/total}}
$$

If you understand these two ideas, calculus becomes much easier.

---

# GRAPH THEORY

Graph Theory is one of the friendliest maths topics because it is mostly about **dots and lines**, not heavy classes 11/12 calculus or algebra.

Your PDF **M1_VOL3_GRAPHTHEORY** has mainly:

1. Graphs and general graph problems  
2. DAGs, Topological Sorting, Longest Path  
3. Weighted Graphs and Shortest Path Algorithms  
4. Spanning Trees, Prim’s Algorithm, Kruskal’s Algorithm  

I will explain everything in very simple language with examples and practice questions.

---

# 0. What is Graph Theory?

Graph theory studies **connections**.

A graph has:

- **Vertices / Nodes** = points / objects
- **Edges** = lines / connections between objects

Example:

Imagine people and friendships.

- People = vertices
- Friendship = edge

If A is friend of B, draw a line between A and B.

---

# CHAPTER 1: GRAPHS AND GENERAL GRAPH PROBLEMS

---

# 1. Graph

A graph is written as:

$$
G=(V,E)
$$

Where:

- \(V\) = set of vertices
- \(E\) = set of edges

---

## Example

Suppose:

$$
V=\{A,B,C,D\}
$$

and:

$$
E=\{(A,B),(A,C),(B,D)\}
$$

This means:

- A is connected to B
- A is connected to C
- B is connected to D

Simple drawing:

```text
    C
    |
A---B---D
```

Actually here A-B, A-C, B-D are connected.

---

# 2. Vertices and Edges

## Vertex

A vertex is a point.

Example:

$$
A,B,C,D
$$

are vertices.

---

## Edge

An edge is a connection between two vertices.

Example:

$$
(A,B)
$$

means A is connected to B.

---

# 3. Types of Graphs

---

## 3.1 Simple Graph

A **simple graph** has:

1. No self-loop  
2. No multiple edges between same pair of vertices

---

### What is a self-loop?

A self-loop means a vertex connected to itself.

Example:

$$
(A,A)
$$

Drawing:

```text
A ↺
```

A simple graph does not allow this.

---

### What are multiple edges?

Multiple edges mean more than one edge between same two vertices.

Example:

```text
A === B
```

There are many lines between A and B.

A simple graph does not allow this.

---

## Simple Graph Example

```text
A---B
|   |
C---D
```

This is simple because:

- No vertex connects to itself
- No repeated edge

---

# 3.2 Directed Graph

A directed graph has arrows.

Edges have direction.

Example:

$$
(A,B)
$$

means:

$$
A \to B
$$

This does **not necessarily** mean:

$$
B \to A
$$

---

## Example

```text
A ---> B
B ---> C
```

Here:

- You can go from A to B
- You can go from B to C
- But you cannot go from B to A unless there is another arrow

---

# 3.3 Undirected Graph

An undirected graph has no arrows.

Example:

```text
A --- B
```

This means:

- A connected to B
- B connected to A

So direction does not matter.

$$
(A,B) = (B,A)
$$

---

# 3.4 Complete Graph

A complete graph is a graph where **every vertex is connected to every other vertex**.

---

## Example: Complete graph with 3 vertices

```text
A
|\
| \
B--C
```

Edges:

$$
(A,B),(A,C),(B,C)
$$

This is called:

$$
K_3
$$

---

## Complete Graph Formula

For \(n\) vertices, number of edges in complete graph:

$$
\frac{n(n-1)}{2}
$$

---

### Example

Complete graph with 4 vertices:

$$
\frac{4(4-1)}{2}
=
\frac{4 \times 3}{2}
=6
$$

So \(K_4\) has 6 edges.

---

# Practice 1

## Q1. What are vertices and edges in this graph?

```text
A---B---C
```

### Answer

Vertices:

$$
\{A,B,C\}
$$

Edges:

$$
\{(A,B),(B,C)\}
$$

---

## Q2. Is this graph directed or undirected?

```text
A ---> B
```

### Answer

Directed graph because it has arrow.

---

## Q3. How many edges are there in complete graph with 5 vertices?

$$
\frac{5(5-1)}{2}
=
\frac{5 \times 4}{2}
=10
$$

Answer:

$$
10
$$

---

# 4. Path

A path means a way to go from one vertex to another by following edges.

---

## Example

```text
A---B---C---D
```

A path from A to D is:

$$
A \to B \to C \to D
$$

---

## Length of Path

Length of path = number of edges used.

For:

$$
A \to B \to C \to D
$$

Edges used:

1. A-B
2. B-C
3. C-D

So length = 3.

---

# 5. Reachability

A vertex \(B\) is reachable from vertex \(A\) if there is a path from A to B.

---

## Example

```text
A---B---C     D
```

From A:

- B is reachable
- C is reachable
- D is not reachable

Because D is separate.

---

# 6. Connected Graph

An undirected graph is connected if every vertex can reach every other vertex.

---

## Connected Example

```text
A---B---C
    |
    D
```

Every vertex is connected somehow.

So graph is connected.

---

## Not Connected Example

```text
A---B     C---D
```

There are two separate parts.

So graph is not connected.

---

# Practice 2

## Q1. Find path from A to D.

```text
A---B---C---D
```

Answer:

$$
A \to B \to C \to D
$$

---

## Q2. Is this graph connected?

```text
A---B     C
```

Answer:

No, because C is separate.

---

# 7. Graph Coloring

Graph coloring means coloring vertices so that **no two adjacent vertices have the same color**.

Adjacent means directly connected by edge.

---

## Simple Example

```text
A---B
```

A and B must have different colors.

Example:

- A = Red
- B = Blue

---

## Triangle Example

```text
A
|\
| \
B--C
```

A, B, C all connected to each other.

So each must have different color.

Minimum colors needed = 3.

---

## Chromatic Number

The minimum number of colors needed to color graph properly is called **chromatic number**.

Symbol:

$$
\chi(G)
$$

---

### Example

For a line:

```text
A---B---C
```

Use:

- A = Red
- B = Blue
- C = Red

Minimum colors = 2.

So:

$$
\chi(G)=2
$$

---

# 8. Vertex Cover

A vertex cover is a set of vertices such that **every edge touches at least one chosen vertex**.

Simple meaning:

> Pick some vertices so that all edges are covered.

---

## Example

```text
A---B---C
```

Edges:

$$
(A,B),(B,C)
$$

If we choose vertex B:

$$
\{B\}
$$

Then:

- Edge A-B touches B
- Edge B-C touches B

So \(\{B\}\) is a vertex cover.

---

## Another Example

```text
A---B
|   |
C---D
```

Edges:

$$
(A,B),(A,C),(B,D),(C,D)
$$

One possible vertex cover:

$$
\{A,D\}
$$

Check:

- A-B touches A
- A-C touches A
- B-D touches D
- C-D touches D

All edges covered.

---

# 9. Independent Set

An independent set is a set of vertices where **no two selected vertices are directly connected**.

Simple meaning:

> Choose vertices that are not friends with each other.

---

## Example

```text
A---B---C
```

Can choose:

$$
\{A,C\}
$$

Because A and C are not directly connected.

But cannot choose:

$$
\{A,B\}
$$

because A and B have an edge.

---

# 10. Relation Between Vertex Cover and Independent Set

In a graph:

- Vertex cover chooses vertices to touch all edges.
- Independent set chooses vertices with no edges among them.

Important relation:

If \(S\) is a vertex cover, then remaining vertices \(V-S\) form an independent set.

---

# 11. Matching

A matching is a set of edges such that no two edges share a vertex.

Simple meaning:

> Pair people, but one person cannot be in two pairs.

---

## Example

```text
A---B---C---D
```

Edges:

$$
(A,B),(B,C),(C,D)
$$

A matching can be:

$$
\{(A,B),(C,D)\}
$$

Because:

- A-B uses A and B
- C-D uses C and D
- No vertex repeated

But:

$$
\{(A,B),(B,C)\}
$$

is not a matching because B is used twice.

---

# Practice 3

Use this graph:

```text
A---B---C
```

## Q1. Give one vertex cover.

Answer:

$$
\{B\}
$$

---

## Q2. Give one independent set.

Answer:

$$
\{A,C\}
$$

---

## Q3. Give one matching.

Answer:

$$
\{(A,B)\}
$$

or

$$
\{(B,C)\}
$$

---

# 12. Representing Graphs

Computers cannot understand drawings directly.  
So we represent graphs using:

1. Adjacency matrix
2. Adjacency list

---

# 12.1 Adjacency Matrix

An adjacency matrix is a table showing which vertices are connected.

If there is an edge, write 1.  
If no edge, write 0.

---

## Example

Graph:

```text
A---B
|   
C
```

Edges:

$$
(A,B),(A,C)
$$

Vertices:

$$
A,B,C
$$

Adjacency matrix:

|   | A | B | C |
|---|---|---|---|
| A | 0 | 1 | 1 |
| B | 1 | 0 | 0 |
| C | 1 | 0 | 0 |

Why?

- A connected to B → 1
- A connected to C → 1
- B not connected to C → 0

For undirected graphs, matrix is symmetric.

That means:

$$
M[i][j]=M[j][i]
$$

---

# 12.2 Adjacency List

Adjacency list stores neighbors of each vertex.

Same graph:

```text
A---B
|   
C
```

Adjacency list:

```text
A: B, C
B: A
C: A
```

This is easier when graph has fewer edges.

---

# Practice 4

Graph:

```text
A---B---C
```

## Q1. Write adjacency list.

Answer:

```text
A: B
B: A, C
C: B
```

---

## Q2. Write adjacency matrix.

Answer:

|   | A | B | C |
|---|---|---|---|
| A | 0 | 1 | 0 |
| B | 1 | 0 | 1 |
| C | 0 | 1 | 0 |

---

# 13. Breadth First Search, BFS

BFS is a graph searching method.

It explores level by level.

Simple meaning:

> Visit nearest nodes first.

BFS uses a **queue**.

Queue means:

> First In, First Out

Like a line at a ticket counter.

---

## BFS Example

Graph:

```text
    A
   / \
  B   C
 / \
D   E
```

Start BFS from A.

Step-by-step:

### Start

Visit A.

Queue:

```text
A
```

---

### Remove A, add its neighbors B and C

Visited:

$$
A
$$

Queue:

```text
B, C
```

---

### Remove B, add its unvisited neighbors D and E

Visited:

$$
A,B
$$

Queue:

```text
C, D, E
```

---

### Remove C

Visited:

$$
A,B,C
$$

Queue:

```text
D, E
```

---

### Remove D

Visited:

$$
A,B,C,D
$$

Queue:

```text
E
```

---

### Remove E

Visited:

$$
A,B,C,D,E
$$

Queue empty.

BFS order:

$$
A,B,C,D,E
$$

---

## BFS Uses

BFS is used for:

- Finding shortest path in unweighted graph
- Checking connected graph
- Finding reachable nodes
- Level order traversal

---

# 14. Depth First Search, DFS

DFS explores as deep as possible first.

Simple meaning:

> Go deep first, then come back.

DFS uses a **stack** or recursion.

Stack means:

> Last In, First Out

Like plates stacked on top of each other.

---

## DFS Example

Graph:

```text
    A
   / \
  B   C
 / \
D   E
```

Start from A.

One possible DFS order:

$$
A,B,D,E,C
$$

Explanation:

1. Start A
2. Go to B
3. Go to D
4. D has no unvisited neighbor, come back
5. Go to E
6. Come back to A
7. Go to C

---

## DFS Uses

DFS is used for:

- Detecting cycles
- Topological sorting
- Finding connected components
- Solving maze-like problems

---

# BFS vs DFS

| BFS | DFS |
|---|---|
| Goes level by level | Goes deep first |
| Uses queue | Uses stack/recursion |
| Good for shortest path in unweighted graph | Good for exploring all paths |
| Visits neighbors first | Visits depth first |

---

# Practice 5

Graph:

```text
    A
   / \
  B   C
  |
  D
```

## Q1. BFS from A?

Answer:

$$
A,B,C,D
$$

---

## Q2. One DFS from A?

Answer:

$$
A,B,D,C
$$

---

# 15. Degree of Vertex in Undirected Graph

Degree of a vertex = number of edges touching it.

---

## Example

```text
A---B---C
    |
    D
```

Degree of A:

$$
1
$$

because only edge A-B touches A.

Degree of B:

$$
3
$$

because B connects to A, C, D.

Degree of C:

$$
1
$$

Degree of D:

$$
1
$$

---

# 16. Handshaking Lemma

In any undirected graph:

$$
\text{Sum of degrees} = 2 \times \text{number of edges}
$$

Why?

Because every edge touches two vertices.

---

## Example

```text
A---B---C
```

Degrees:

- deg(A)=1
- deg(B)=2
- deg(C)=1

Sum:

$$
1+2+1=4
$$

Edges = 2

$$
2 \times 2=4
$$

Correct.

---

# 17. Indegree and Outdegree in Directed Graph

In a directed graph:

## Indegree

Number of arrows coming into a vertex.

## Outdegree

Number of arrows going out from a vertex.

---

## Example

```text
A ---> B ---> C
```

For A:

- Indegree = 0
- Outdegree = 1

For B:

- Indegree = 1
- Outdegree = 1

For C:

- Indegree = 1
- Outdegree = 0

---

# Practice 6

Graph:

```text
A---B---C
    |
    D
```

## Q1. Find degrees.

Answer:

$$
deg(A)=1
$$

$$
deg(B)=3
$$

$$
deg(C)=1
$$

$$
deg(D)=1
$$

---

## Q2. Sum of degrees?

$$
1+3+1+1=6
$$

So number of edges:

$$
\frac{6}{2}=3
$$

---

# CHAPTER 2: DAGs, TOPOLOGICAL SORTING AND LONGEST PATH

---

# 1. DAG

DAG means:

$$
\text{Directed Acyclic Graph}
$$

Break it:

- Directed = arrows
- Acyclic = no cycle

So DAG is a directed graph with no cycle.

---

## What is a Cycle?

A cycle means starting from a vertex and coming back to it.

Example:

```text
A ---> B
^      |
|      v
C <--- D
```

You can go:

$$
A \to B \to D \to C \to A
$$

This is a cycle.

So this is not a DAG.

---

## DAG Example

```text
A ---> B ---> D
 \           ^
  \          |
   ---> C ---
```

There are arrows, but no way to come back to A.

So this is a DAG.

---

# 2. Real-Life Examples of DAG

DAGs are used when some tasks must be done before others.

---

## Example 1: Course Prerequisites

Suppose:

```text
Basic Maths ---> Calculus ---> Machine Learning
```

You must study Basic Maths before Calculus.

This is a DAG.

---

## Example 2: Cooking

```text
Buy vegetables ---> Cut vegetables ---> Cook food
```

One step comes before another.

---

## Example 3: Software Installation

```text
Install Python ---> Install Libraries ---> Run Program
```

---

# 3. Topological Sorting

Topological sorting means arranging vertices in an order such that:

> If there is an edge \(A \to B\), then A must come before B.

This only works for DAGs.

---

## Example

Graph:

```text
A ---> B
A ---> C
B ---> D
C ---> D
```

A must come before B and C.  
B and C must come before D.

One topological order:

$$
A,B,C,D
$$

Another valid order:

$$
A,C,B,D
$$

Both are correct.

---

# 4. How to Do Topological Sort: Easy Method

Use indegree.

Steps:

1. Find indegree of every vertex.
2. Choose a vertex with indegree 0.
3. Remove it and its outgoing edges.
4. Repeat.

---

## Example

Graph:

```text
A ---> B
A ---> C
B ---> D
C ---> D
```

### Step 1: Indegrees

- A = 0
- B = 1
- C = 1
- D = 2

### Step 2: Pick indegree 0

Pick A.

Order:

$$
A
$$

Remove A’s edges:

$$
A \to B,\quad A \to C
$$

Now:

- B = 0
- C = 0
- D = 2

### Step 3: Pick B

Order:

$$
A,B
$$

Remove B → D.

Now D indegree becomes 1.

### Step 4: Pick C

Order:

$$
A,B,C
$$

Remove C → D.

Now D indegree becomes 0.

### Step 5: Pick D

Order:

$$
A,B,C,D
$$

Done.

---

# 5. Longest Path in a DAG

Longest path means path with maximum total length.

In general graphs, longest path is hard.  
But in DAGs, it is easier because there are no cycles.

---

## Simple Method

1. Do topological sorting.
2. Process vertices in that order.
3. Update longest distance to neighbors.

---

## Simple Example

```text
A ---> B ---> D
 \           ^
  \          |
   ---> C ---
```

Edges all have weight 1.

Paths from A to D:

1. A → B → D has length 2
2. A → C → D has length 2

Longest path length = 2.

---

# 6. Transitive Closure

Transitive closure tells reachability.

It answers:

> Can I reach vertex B from vertex A?

---

## Example

```text
A ---> B ---> C
```

Direct edges:

$$
A \to B
$$

$$
B \to C
$$

But A can also reach C through B.

So transitive closure includes:

$$
A \to C
$$

---

## Simple Meaning

If:

$$
A \to B
$$

and:

$$
B \to C
$$

then transitive closure adds:

$$
A \to C
$$

---

# 7. Matrix Representation and Reachability

Adjacency matrix shows direct connections.

Reachability matrix shows direct or indirect reachability.

---

## Example

Graph:

```text
A ---> B ---> C
```

Adjacency matrix:

|   | A | B | C |
|---|---|---|---|
| A | 0 | 1 | 0 |
| B | 0 | 0 | 1 |
| C | 0 | 0 | 0 |

Reachability matrix:

|   | A | B | C |
|---|---|---|---|
| A | 0 | 1 | 1 |
| B | 0 | 0 | 1 |
| C | 0 | 0 | 0 |

Why A to C is 1?

Because A can reach C through B.

---

# Practice 7

Graph:

```text
A ---> B ---> C
A ---> D
```

## Q1. Is this a DAG?

Answer:

Yes, because there is no cycle.

---

## Q2. Give one topological ordering.

Answer:

$$
A,B,D,C
$$

or

$$
A,D,B,C
$$

Both valid.

---

## Q3. Can A reach C?

Answer:

Yes.

$$
A \to B \to C
$$

---

# CHAPTER 3: WEIGHTED GRAPHS AND SHORTEST PATH ALGORITHMS

---

# 1. Weighted Graph

A weighted graph has numbers on edges.

These numbers are called weights.

Weights can represent:

- Distance
- Cost
- Time
- Difficulty
- Price

---

## Example

```text
A --5-- B --2-- C
```

Weight of A-B = 5  
Weight of B-C = 2

Distance from A to C through B:

$$
5+2=7
$$

---

# 2. Shortest Path

Shortest path means path with minimum total weight.

---

## Example

```text
A --10-- C
A --3--- B --4-- C
```

Paths from A to C:

1. Direct A → C = 10
2. A → B → C = 3 + 4 = 7

Shortest path = A → B → C

Distance = 7.

---

# 3. Dijkstra’s Algorithm

Dijkstra’s algorithm finds shortest path from one starting vertex to all other vertices.

Important:

> Dijkstra works when edge weights are non-negative.

So weights should not be negative.

---

## Dijkstra Simple Idea

Imagine you are finding shortest road distances from your home.

Steps:

1. Start distance of source = 0.
2. All other distances = infinity.
3. Pick unvisited vertex with smallest distance.
4. Update its neighbors.
5. Repeat.

---

## Dijkstra Example

Graph:

```text
A --1-- B
A --4-- C
B --2-- C
B --5-- D
C --1-- D
```

Find shortest distances from A.

---

### Step 1: Initial distances

| Vertex | Distance from A |
|---|---|
| A | 0 |
| B | ∞ |
| C | ∞ |
| D | ∞ |

Visited:

$$
\emptyset
$$

---

### Step 2: Pick A

A has smallest distance 0.

Neighbors:

- B through A: \(0+1=1\)
- C through A: \(0+4=4\)

Update:

| Vertex | Distance |
|---|---|
| A | 0 |
| B | 1 |
| C | 4 |
| D | ∞ |

Visited:

$$
A
$$

---

### Step 3: Pick B

B has smallest unvisited distance 1.

Neighbors:

- C through B: \(1+2=3\), better than 4, update C to 3
- D through B: \(1+5=6\), update D to 6

| Vertex | Distance |
|---|---|
| A | 0 |
| B | 1 |
| C | 3 |
| D | 6 |

Visited:

$$
A,B
$$

---

### Step 4: Pick C

C has smallest unvisited distance 3.

Neighbor:

- D through C: \(3+1=4\), better than 6, update D to 4

| Vertex | Distance |
|---|---|
| A | 0 |
| B | 1 |
| C | 3 |
| D | 4 |

Visited:

$$
A,B,C
$$

---

### Step 5: Pick D

D distance = 4.

Done.

Final shortest distances from A:

| Vertex | Shortest Distance |
|---|---|
| A | 0 |
| B | 1 |
| C | 3 |
| D | 4 |

Shortest path A to D:

$$
A \to B \to C \to D
$$

Distance:

$$
1+2+1=4
$$

---

# 4. Bellman-Ford Algorithm

Bellman-Ford also finds shortest paths.

But Bellman-Ford can handle negative weights.

Dijkstra cannot handle negative weights properly.

---

## When to Use Bellman-Ford?

Use Bellman-Ford if graph may contain negative edge weights.

---

## Bellman-Ford Main Idea

If graph has \(V\) vertices, repeat edge relaxation:

$$
V-1
$$

times.

---

## What is Relaxation?

Relaxation means checking:

> Can I improve the distance to this vertex?

For edge:

$$
u \to v
$$

with weight \(w\):

If:

$$
dist[u]+w < dist[v]
$$

then update:

$$
dist[v]=dist[u]+w
$$

---

## Bellman-Ford Also Detects Negative Cycles

A negative cycle is a cycle whose total weight is negative.

Example:

```text
A --2--> B
B --(-5)--> C
C --1--> A
```

Total:

$$
2+(-5)+1=-2
$$

This is negative.

If graph has negative cycle, shortest path may not exist because you can keep going around cycle and distance keeps decreasing.

---

# Dijkstra vs Bellman-Ford

| Dijkstra | Bellman-Ford |
|---|---|
| Faster | Slower |
| Does not allow negative weights | Allows negative weights |
| Cannot detect negative cycle | Can detect negative cycle |
| Used commonly in maps/networks | Used when negative weights exist |

---

# Practice 8

Graph:

```text
A --2-- B --3-- C
A --10-- C
```

## Q1. Shortest path from A to C?

Path 1:

$$
A \to C = 10
$$

Path 2:

$$
A \to B \to C = 2+3=5
$$

Answer:

$$
A \to B \to C
$$

Distance:

$$
5
$$

---

## Q2. Which algorithm can handle negative weights?

Answer:

Bellman-Ford.

---

# 5. Spanning Tree

A spanning tree is a subgraph that:

1. Contains all vertices
2. Is connected
3. Has no cycle

---

## Tree

A tree is a connected graph with no cycle.

Example tree:

```text
A---B---C
    |
    D
```

No cycle.

---

## Not a Tree

```text
A---B
|   |
C---D
```

This has a cycle:

$$
A \to B \to D \to C \to A
$$

So it is not a tree.

---

## Spanning Tree Example

Original graph:

```text
A---B
| \ |
C---D
```

One spanning tree:

```text
A---B
|
C---D
```

It includes all vertices:

$$
A,B,C,D
$$

It is connected.

It has no cycle.

---

## Important Formula

A tree with \(n\) vertices always has:

$$
n-1
$$

edges.

Example:

If tree has 5 vertices, it has:

$$
5-1=4
$$

edges.

---

# 6. Minimum Spanning Tree, MST

A minimum spanning tree is a spanning tree with minimum total weight.

Used for:

- Building cheapest network
- Connecting cities with minimum road cost
- Laying cables
- Network design

---

# 7. Prim’s Algorithm

Prim’s algorithm finds MST.

Simple idea:

> Start from one vertex and keep adding the cheapest edge that connects a new vertex.

---

## Prim’s Algorithm Steps

1. Start with any vertex.
2. Choose smallest edge from selected vertices to unselected vertex.
3. Add that edge and vertex.
4. Repeat until all vertices included.

---

## Prim Example

Graph:

```text
A --1-- B
A --4-- C
B --2-- C
B --5-- D
C --3-- D
```

Find MST.

---

### Step 1: Start at A

Selected:

$$
\{A\}
$$

Available edges:

- A-B = 1
- A-C = 4

Choose smallest:

$$
A-B=1
$$

---

### Step 2: Selected A, B

Selected:

$$
\{A,B\}
$$

Available edges to outside:

- A-C = 4
- B-C = 2
- B-D = 5

Choose smallest:

$$
B-C=2
$$

---

### Step 3: Selected A, B, C

Available edges to outside:

- B-D = 5
- C-D = 3

Choose smallest:

$$
C-D=3
$$

---

### MST Edges

$$
(A,B),(B,C),(C,D)
$$

Total weight:

$$
1+2+3=6
$$

---

# 8. Kruskal’s Algorithm

Kruskal’s algorithm also finds MST.

Simple idea:

> Sort all edges by weight and keep choosing smallest edge if it does not create a cycle.

---

## Kruskal Steps

1. Sort edges from smallest to largest.
2. Pick smallest edge.
3. If it forms cycle, skip it.
4. Continue until MST has \(n-1\) edges.

---

## Kruskal Example

Same graph:

```text
A --1-- B
A --4-- C
B --2-- C
B --5-- D
C --3-- D
```

Edges sorted:

1. A-B = 1
2. B-C = 2
3. C-D = 3
4. A-C = 4
5. B-D = 5

Pick:

$$
B-C=1
$$

Pick:

$$
A-B=2
$$

Pick:

$$
C-D=3
$$

Now all vertices connected.

MST:

$$
(A,B),(B,C),(C,D)
$$

Total:

$$
1+2+3=6
$$

---

# Prim vs Kruskal

| Prim | Kruskal |
|---|---|
| Starts from a vertex | Starts from smallest edge |
| Grows one tree | Builds forest and joins parts |
| Chooses cheapest edge from selected set | Chooses cheapest edge overall |
| Avoids connecting to already selected vertex | Avoids cycles |

---

# Practice 9

Graph edges:

$$
A-B=2
$$

$$
A-C=5
$$

$$
B-C=1
$$

$$
B-D=4
$$

$$
C-D=3
$$

## Q1. Find MST using Kruskal.

Sorted edges:

1. B-C = 1
2. A-B = 2
3. C-D = 3
4. B-D = 4
5. A-C = 5

Pick:

$$
B-C=1
$$

Pick:

$$
A-B=2
$$

Pick:

$$
C-D=3
$$

Now all vertices connected.

Total weight:

$$
1+2+3=6
$$

Answer:

MST edges:

$$
(B,C),(A,B),(C,D)
$$

Weight:

$$
6
$$

---

# IMPORTANT FORMULA SHEET

## Graph

$$
G=(V,E)
$$

where:

- \(V\) = vertices
- \(E\) = edges

---

## Complete Graph Edges

$$
\frac{n(n-1)}{2}
$$

---

## Degree Sum Formula

$$
\sum deg(v)=2|E|
$$

---

## Tree Edges

If a tree has \(n\) vertices:

$$
\text{edges}=n-1
$$

Example:

If tree has 5 vertices, it has:

$$
5-1=4
$$

edges.

---

## Directed Graph

$$
indegree = \text{arrows coming in}
$$

$$
outdegree = \text{arrows going out}
$$

---

## Dijkstra Relaxation

$$
dist[v] = \min(dist[v], dist[u]+w)
$$

---

## Bellman-Ford

Repeat relaxation:

$$
|V|-1
$$

times.

---

## MST

Minimum spanning tree.

---

# MIXED PRACTICE QUESTIONS WITH ANSWERS

---

## Q1. Define graph.

Answer:

A graph is a structure made of vertices and edges.

$$
G=(V,E)
$$

---

## Q2. What are vertices in this graph?

```text
P---Q---R
```

Answer:

$$
\{P,Q,R\}
$$

---

## Q3. What are edges?

Answer:

$$
(P,Q),(Q,R)
$$

---

## Q4. Is this graph connected?

```text
A---B   C---D
```

Answer:

No, because there are two separate parts.

---

## Q5. Find degree of B.

```text
A---B---C
    |
    D
```

Answer:

$$
deg(B)=3
$$

---

## Q6. If a graph has 6 edges, what is sum of degrees?

Using:

$$
\sum deg(v)=2|E|
$$

$$
=2 \times 6=12
$$

Answer:

$$
12
$$

---

## Q7. How many edges in complete graph with 6 vertices?

$$
\frac{6(6-1)}{2}
=
\frac{6 \times 5}{2}
=15
$$

Answer:

$$
15
$$

---

## Q8. What is BFS?

Answer:

BFS is Breadth First Search. It visits graph level by level using a queue.

---

## Q9. What is DFS?

Answer:

DFS is Depth First Search. It goes deep first using stack or recursion.

---

## Q10. What is a DAG?

Answer:

A Directed Acyclic Graph. It has arrows and no cycles.

---

## Q11. Can topological sorting be done on graph with cycle?

Answer:

No.

Topological sort works only for DAGs.

---

## Q12. What is weighted graph?

Answer:

A graph where edges have weights/costs/distances.

---

## Q13. Which algorithm finds shortest path with non-negative weights?

Answer:

Dijkstra’s algorithm.

---

## Q14. Which algorithm works with negative weights?

Answer:

Bellman-Ford algorithm.

---

## Q15. What is MST?

Answer:

Minimum Spanning Tree. It connects all vertices with minimum total weight and no cycle.

---

# BEGINNER STUDY PLAN FOR GRAPH THEORY

Since you did not have Maths in class 11/12, follow this order.

---

## Day 1: Basic Graphs

Study:

- Vertex
- Edge
- Directed graph
- Undirected graph
- Complete graph
- Path
- Connected graph

Practice:

Draw 10 small graphs and write vertices/edges.

---

## Day 2: Degree and Representation

Study:

- Degree
- Indegree
- Outdegree
- Adjacency matrix
- Adjacency list

Practice:

Convert 5 graphs into matrix and list.

---

## Day 3: BFS and DFS

Study:

- BFS = level by level
- DFS = deep first

Practice:

Do BFS and DFS on small graphs.

---

## Day 4: Coloring, Vertex Cover, Independent Set, Matching

Study:

- Graph coloring
- Vertex cover
- Independent set
- Matching

Practice:

Take simple line, triangle, square graphs.

---

## Day 5: DAG and Topological Sort

Study:

- DAG
- Cycle
- Topological ordering

Practice:

Do topological sort on task-order graphs.

---

## Day 6: Shortest Path

Study:

- Weighted graph
- Dijkstra
- Bellman-Ford

Practice:

Find shortest path in small weighted graphs.

---

## Day 7: MST

Study:

- Tree
- Spanning tree
- Minimum spanning tree
- Prim
- Kruskal

Practice:

Find MST using both Prim and Kruskal.

---

# FINAL SIMPLE SUMMARY

| Topic | Simple Meaning |
|---|---|
| Graph | Dots and lines |
| Vertex | Dot / point |
| Edge | Connection / line |
| Directed graph | Edges have arrows |
| Undirected graph | Edges have no arrows |
| Path | Way to go from one vertex to another |
| Connected graph | Every vertex can reach every other |
| Degree | Number of edges touching a vertex |
| BFS | Visit level by level |
| DFS | Go deep first |
| DAG | Directed graph with no cycle |
| Topological sort | Arrange tasks in correct order |
| Weighted graph | Edges have cost/distance |
| Dijkstra | Shortest path without negative weights |
| Bellman-Ford | Shortest path with negative weights |
| Tree | Connected graph with no cycle |
| MST | Cheapest way to connect all vertices |
| Prim | Build MST from one vertex |
| Kruskal | Build MST by choosing smallest edges |

---

# Most Important Memory Trick

Graph theory is just:

$$
\boxed{\text{Objects + Connections}}
$$

Shortest path is:

$$
\boxed{\text{Cheapest route}}
$$

MST is:

$$
\boxed{\text{Cheapest network connecting everyone}}
$$

BFS is:

$$
\boxed{\text{Nearby first}}
$$

DFS is:

$$
\boxed{\text{Deep first}}
$$