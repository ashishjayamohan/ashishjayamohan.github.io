# Discrete Math Homework 1
****
## 1.1.11
**Every positive number has a positive square root.**
a. All positive numbers have a positive square root.
b. For any positive number $e$, there is a positive square root for $e$.
c. For all positive numbers $e$, there is a positive number $r$
such that $r^2 = e$.
****
## 1.2.8
**Let $A = \{c, d, f, g\}$, $B = \{ f, j\}$, and $C = \{d, g\}$. Answer each of the following questions. Give reasons for your answers.**
a. Is $B \subseteq A$? $\rightarrow$ $B \not\subset A$
b. Is $C \subseteq A$? $\rightarrow$ $C \subseteq A$
c. Is $C \subseteq C$? $\rightarrow$ $C \subseteq C$
d. Is $C \subset A$? $\rightarrow$ $C \subset A$
****
## 1.3.6
**Define a relation $R$ from $R$ to $R$ as follows: For all $(x, y) ∈ R × R$, $(x, y) ∈ R$ means that $y = x^2$.**
a. Is $(2, 4) ∈ R$? Is $(4, 2) ∈ R$? Is $(−3) R 9$? Is $9 R (−3)$? $\rightarrow$ $(2,4) \in R$, $(4,2) \not\in R$, $(-3) R 9$ is True, $(-9) R 3$ is False
b. ![[Screen Shot 2021-06-17 at 11.20.40 AM.png]]
****
## 2.1.39
** $(num\_orders < 50$ and $num\_instock > 300)$ or $(50 ≤ num\_orders < 75$ and $num\_instock > 500)$**
Negation: $[num\_orders \geq 50$ or $num\_instock \leq 300]$ and $[(num\_orders < 50$ or $num\_orders \geq 75)$ or $num\_instock \leq 500]$
****
## 2.2.36
**Taking the long view on your education, you go to the Prestige Corporation and ask what you should do in college to be hired when you graduate. The personnel director replies that you will be hired only if you major in mathematics or computer science, get a B average or better, and take accounting. You do, in fact, become a math major, get a B+ average, and take accounting. You return to Prestige Corporation, make a formal application, and are turned down. Did the personnel director lie to you?**
No, the personnel director did not lie to you. Using the definition of a contrapositive statement: $$~q \to ~p \equiv p \to q$$ Using the following definitions:
$$p = \text{You will be hired}$$ $$q = \text{You major in mathematics or computer science, get a B average or better, and take accounting}$$
We can then fill in the contrapositive statement: $$~q \to ~p \equiv p \to q$$ $$\text{If you do not major in mathematics or computer science, get a B average or better, and take accounting, you will not be hired}$$ $$\equiv$$ $$\text{If you are hired, you majored in mathematics or computer science, got a B average or better, and took accounting}$$
Thus, because the director did not say that the major and grade average requirements would result in a job at the company, *he did not lie to you*.
****
## 2.3.36
**Given the following information about a computer program, find the mistake in the program. 
a. There is an undeclared variable or there is a syntax error in the first five lines. 
b. If there is a syntax error in the first five lines, then there is a missing semicolon or a variable name is misspelled. 
c. There is not a missing semicolon. 
d. There is not a misspelled variable name.**
There is an undeclared variable.
****
## 4.1.57
**If $m$ and $n$ are positive integers and $mn$ is a perfect square, then $m$ and $n$ are perfect squares.**
The statement is false. Take for example where $m=3$ and $n=3$. Although $mn=9$, which is a perfect square, neither $m$ or $n$ are perfect squares.
****
## 4.2.38
**Suppose $r$ and $s$ are rational numbers. Then $r = \frac{a}{b}$ and $s = \frac{c}{d}$ for some integers $a$, $b$, $c$, and $d$ with $b \neq 0$ and $d \neq 0$ (by definition of rational). Then $$r+s = \frac{a}{b} + \frac{c}{d}$$ But this is a sum of two fractions, which is a fraction. So $r + s$ is a rational number since a rational number is a fraction.**
This proof states that "a rational number is a fraction," which is fundamentally untrue. Although rational numbers are numbers that can be represented as simple fractions, an irrational number can be represented as a fraction (take for example $\frac{\pi}{2}$). Additionally, the proof says that the sum of two fractions must be a fraction, which is unproved.
****
## 4.3.28
**For all integers $a$, $b$, and $c$, if $a | bc$ then $a | b$ or $a | c$.**
No, this statement is not true. An example which disproves this situation is where $a=8$, $b=4$, and $c=2$. Whilst $a|bc$ is true, $8|4$ and $8|2$ are both false.
****
## 4.4.42
**Every prime number except $2$ and $3$ has the form $6q + 1$ or $6q + 5$ for some integer $q$.**
We can represent any given integer $m$ as any of the following: $6n$, $6n+1$, $6n+2$, $6n+3$, $6n+4$, or $6n+5$.
In the case where $m>2$, $6n$, $6n+2$, and $6n+4$ are all even because they are all fundamentally divisible by $2$.
In the case where $m>3$, $6n+3$ is divisible by $3$.
Because the prior statements are divisible by $2$ and $3$, they are not prime, so the only statements that are left are $6n+1$ and $6n+5$.
****
## 4.5.24
Proof by contraposition:
We can assume that if $x^{-1}$ is not irrational, then $x$ is not irrational.
If we assume a number $\frac{1}{x}$ where $x \in \mathbb{Z}$. We can represent $\frac{1}{x}$ as $\frac{a}{b}$ where $a,b \in \mathbb{Z}$ and $a,b \neq 0$. We can therefore represent $x$ as $\frac{b}{a}$. Because both $b$ and $a$ are integers, we know that $x$ must be rational.

Proof by contradiction:
We can assume that the reciprocal of any irrational number must be rational.
In the case where $x$ is a rational number, we can represent the reciprocal of $x$ as $\frac{1}{x}$ or, more generically, as $\frac{a}{b}$ where $a,b \in \mathbb{Z}$ and $a,b \neq 0$. We can therefore represent $x$ as $\frac{b}{a}$. Because $x$ cannot be both irrational and rational, there is a contradiction.