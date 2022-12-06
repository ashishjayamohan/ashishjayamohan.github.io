# Discrete Math Final
****
<cite>Ashish Jayamohan - G08141951</cite>
<cite>Start Time: 3:00</cite>
<cite>End Time: 3:27</cite>
****
## Question 1
We assume, upon the information given in the problem, that since $a|bc$, there exists some $k$ such that $k \in \mathbb{Z}$ and $bc = k \cdot a$
We first multiply $ax+by=1$ by $c$. Doing do produces the following: $$axc+byc = c$$ Using our assumptions from the beginning, we can substitute to generate the following: $$axc + kay = c$$ Factoring $a$ out gives us: $$a \cdot (cx+ky) = c$$ Assuming that $c$, $x$, $k$, and $y$ are all included in $\mathbb{Z}$, we can define some arbitrary value $n$ such that $n = cx + ky$. Using this substitution, we can derive the following: $$a \cdot n = c$$ This equation is the definition of $a|c$, so our statement is proven.
****
## Question 2
![[IMG_5747.jpg]]
> ### Part A
> **How many pea plants had at least 1 characteristic?**
> The problem statement says that there were $50$ plants in total, with $4$ showing no characteristics at all. Using this information, we can conclude that $46$ plants have at least one characteristic.

> ### Part B
> Using the information that we derive from the venn diagram above, we can tell that the number of plants that are tall and have smooth peas will be $b+a$. Thus, we find that this number is equal to $17$.
****
## Question 3
![[IMG_5748.jpg]]
****
## Question 4
> ### Part A
> $$n(A) = 100, P(A) = 0.04$$ $$A_\text{(defective)} = 0.04 \cdot 100$$ $$A_\text{(defective)} = 4$$
> $$n(B) = 80, P(B) = 0.05$$ $$B_\text{(defective)} = 0.05 \cdot 80$$ $$B_\text{(defective)} = 4$$
> $$A_\text{(defective)} + B_\text{(defective)} = 8$$
> $$P(\text{Defective}) = \dfrac{8}{180}$$

> ### Part B
> From a sample of $180$ items, $100$ were from $A$, thus making the following statement true: $$P(\frac{S}{A}) = \frac{100}{180} = \frac{5}{9}$$ This continues on with those from $B$, showing that $$P(\frac{S}{B}) = \frac{80}{180} = \frac{4}{9}$$ We know that the following stands true, so we can substitute our known values: $$P(\frac{A}{B}) = \dfrac{P(A) \cdot P(\frac{S}{A})}{P(A) \cdot P(\frac{S}{A}) + P(B) \cdot P(\frac{S}{B})}$$ Substituting our known values gives us: $$\dfrac{0.04 \cdot \frac{5}{9}}{0.04 \cdot \frac{5}{9} + 0.05 \cdot \frac{4}{9}} = \dfrac{\frac{0.2}{9}}{\frac{0.2}{9} + \frac{0.2}{9}}$$ Simplifying, we see the solution must be the following: $$\frac{0.0222}{0.0444} = \frac{1}{2} = 0.5$$ Thus, the probability given in the problem statement is $0.5$ or $$50\%$$
****
## Question 5
Using induction and the information given to us in the problem, we assume that the following statement is true where $y \in \mathbb{Z}$: $$5^k-1 = 4 \cdot y$$ Using the above statement, we can derive the following: $$5^k = 4y + 1$$ Incrementing $k$ by $1$ gives us: $$5^{k+1} - 1 = 5 \cdot 5^k - 1$$ Using our equivalences from above, we can substitute to derive the following: $$5\cdot (4y+1) - 1 = 20 \cdot y + 4$$ Factoring again gives us: $$4 \cdot (5y+1)$$ We know that $5y+1 \in \mathbb{Z}$, so we can conclude that $5^{k+1} - 1$ is divisible by $4$, proving the problem statement.