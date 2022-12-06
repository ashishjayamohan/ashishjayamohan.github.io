# Dicrete Math Midterm
****
<cite>Ashish Jayamohan - G08141951</cite>
<cite>Start Time: 1:00</cite>
<cite>End Time: 2:17</cite>
****
## Question 1
We are asked to prove that for integers $a$, $b$, and $c$, $a|c$ where $a|b$ and $a|(b+c)$.
Assuming $a|b$ and $a|(b+c)$ are both true, we can conclude that there exists some $x$ and $y$ where the following statements stand true: $$x \cdot a = b$$ $$y \cdot a = b+c$$ Using systems of equations, we can subtract $b$ from $b+c$, giving us the following equation: $$(b+c) - b = c = (y \cdot a) - (x \cdot a)$$ Factoring on the right hand side gives us the following: $$c = a \cdot(y-x)$$ Thus, since $x$ and $y$ are both integers, their difference is also an integer, signifying that there is some integer $y-x$ which multiples by $a$ to give $c$, proving that $a|c$
****
## Question 2
We are asked to prove that for a given integer $n$, $n^2-2$ is not divisible by $4$.
In the case where $n^2 - 2$ is divisible by $4$, we can assume the following statement is true as well for some arbitrary $x$ where $x \in \mathbb{Z}$: $$n^2 - 2 = 4\cdot x$$ $$n^2 = 4x + 2$$ We now have to consider two cases - one where $n$ is even and the other where $n$ is odd.
Where $n$ is even, we can assume that $n = 2 \cdot y$ where $y$ is some arbitrary number where $y \in \mathbb{Z}$. Knowing this, we can use our statement from above and derive the following: $$(2y)^2 = 4 \cdot 4x + 2 \rightarrow 4y^2 = 4x + 2$$ We can now define some arbitrary value $a$ such that $a = y^2$ and $a \in \mathbb{Z}$. Using this, we can substitute to find the following: $$4a = 4x+2$$ Dividing by $2$ on both sides, we produce: $$2s = 2x + 1$$ We know that $2s$ must be even and $2x + 1$ must be odd. Thus, because an even number cannot also be odd, we have a contradiction.
We also consider the case where $n$ is odd. In this case, we can define some variable $z$ such that $(2z +1)^2 = 4x+2$ and $z \in \mathbb{Z}$. Simplifying this statement, we produce: $$4z^2 + 4z + 1 = 4x + 2$$ $$4z^2 + 4z = 4x + 1$$ Factoring the $4$ out of the left-hand side of the equation, we get: $$4(z^2+z) = 4x + 1$$ Assigning $b$ as some number where $b \in \mathbb{Z}$ and $b = z^2+z$, we produce the following equation: $$4b = 4x + 1$$ We can now define some number $c$ as $c = 2x$ where $c \in \mathbb{Z}$. This produces the following when substituted: $$2b = 2c + 1$$ Once again, $2b$ is even which $2c + 1$ is odd, thus proving a contradiction.
All cases possible for $n$ prove to be a contradiction, thus we can conclude that $n^2-2$ is not divisible by $4$ for any integer $n$.
****
## Question 3
### Part A
> Knowing $n$ to be an integer, $n \mod 3$ can produce either $0$, $1$, or $2$.

### Part B
> An integer $n$ can be written in the following ways assuming $a$ to be some arbitrary number where $a \in \mathbb{Z}$:
> $$3a$$ $$3a+1$$ $$3a+2$$

### Part C
> Using our intuition from Part B, we can presume that there are three remainders $r$ which we can get from the calculation $r = n \mod 3$ for some number $n$ where $n \in \mathbb{Z}$. The three values which $r$ can take on are $0$, $1$, and $2$. Thus, we can represent every integer $n$ as either $3a$, $3a+1$, or $3a+2$ for some integer $a$ where $a \in \mathbb{Z}$ as well. Thus, we have three cases to consider for this problem.
> In the case where we can represent our $n$ as $3a$, we know that $n$ itself is composite as it is divisible by $3$. The only possible loop in this would be when $n=3$, but we are told in the problem that $n > 3$, thus invalidating this exception.
> In the case where have an $n$ which is represented as $3a + 1$, $n+2$ can be represented as such: $$n + 2 = 3a + 3$$ We can factor the $3$ out of the right hand side of the equation to reveal the following: $$n+2 = 3 \cdot (a+1)$$ Thus, we can see that in this case, $n+2$ is divisible by $3$, thus making it a composite number.
> Finally, in the case where $n$ is represented as $3a+2$, $n+4$ can be represented as such: $$n+4 = 3a+6$$ Factoring out $3$ on the right hand side once again, we produce the following: $$n + 4 = 3 \cdot (a+2)$$ Thus, $n+4$ in this case is non-prime as it is divisible by $3$.
> Thus, for all cases of $n$, either $n$, $n+2$, or $n+4$ is a composite number.

****
## Question 4
We are asked to prove that $1+3n \leq 4^n$ where $n \geq 0$.
Let us define $\theta(n)$ as representing the inequality above. As a simple case, we find that $\theta(0)$ is true.
Assuming $k$ to be some integer where $k \geq 0$ where $\theta (k)$ is true, we can establish the following inequality: $$1+3k \leq 4^k$$ By induction, we increment $k$ by 1 will give us the following inequality: $$1+3(k+1) \leq 4^{k+1}$$ Simplifying and redistributing the right side of the inequality, we obtain: $(3k + 1) + 3$. By induction, this must be less than or equal to $4^n + 3 \leq 4^n + 3 \cdot 4^n$. Thus, $4^n + 3 \leq 4^{n+1}$, proving that $\theta(n+1)$ is true. Thus, for any $n$ where $n \in \mathbb{Z}$ and $n \geq 0$, $1+3n \leq 4^n$.