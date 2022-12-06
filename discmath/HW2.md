# Discrete Math Homework 2
## 4.6.18
We can assume that both $a$ and $d$ are integers where $d>0$ and such integers $q_1$, $q_2$, $r_1$, and $r_2$ exist such that the following conditions are fulfilled: $$d \cdot q_1 + r_1 = d \cdot q_2 + r_2$$ Assuming this to be true, we can then use simple algebra to derive: $$r_2 - r_1 = d \cdot (q_1 - q_2)$$ We can be certain that both $r_1$ and $r_2$ fall between $0$ and $d$ as it signifies the remainder. As a result, we can assume the following conditions to be true: $$0 \leq r_1 < d$$ $$0 \leq r_2 < d$$ Using these assumptions, we can derive the following: $$-d < r_2 - r_1 < d$$ Knowing that $r_2-r_1 = d \cdot (q_1 - q_2)$, we can substitute to get the following: $$-d < d \cdot (q_1 - q_2) < d$$ Knowing that $d > 0$, we can divide the entire inequality by $d$, producing the following: $$-1 < q_1 - q_2 < 1$$ Since we know that $q_1 - q_2$ must be an integer ($a-b \in \mathbb{Z}$ where $a,b \in \mathbb{Z}$), we can conclude that the only possible value for $q_1 - q_2$ is $0$. Thus, we can conclude that since $q_1 - q_2 = 0$, $q_1 = q_2$.
Because we know that $q_1 = q_2$ and $r_2 - r_1 = d \cdot (q_1 - q_2)$, we can follow this stream of logic: $$r_2 - r_1 = d \cdot 0$$ $$r_2 - r_1 = 0$$ $$r_1 = r_2$$
Thus, we conclude that $q_1 = q_2$ and $r_1 = r_2$
****
## 5.1.48
Since we are given that $i = k+1$, we can simple substitute all $k$ with $i-1$. Knowing this, we can follow this stream of logic: $$\sum_{k=1}^5 k\cdot (k-1)$$ $$= \sum_{i=2}^6 (i-1) \cdot ((i-1)-1)$$ $$= \sum_{i=2}^6 (i-1) \cdot (i-2)$$
****
## 5.2.10
We are asked to prove the following where $n \geq 1$: $$1^2 + 2^2 + \cdots + n^2 = \dfrac{n(n+1)(2n+1)}{6}$$ We begin assuming some integer $m$ where $m=n$. Substituting, we get: $$1^2 + 2^2 + \cdots + m^2 = \dfrac{m(m+1)(2m+1)}{6}$$ Thus, we can also conclude that the following is also true: $$1^2 + 2^2 + \cdots + m^2 + (m+1)^2 = \dfrac{(m+1)(m+2)(2m+3)}{6}$$ We can also presume the following is true: $$(1^2 + 2^2 + \cdots + m^2) + (m+1)^2 = \dfrac{m(m+1)(2m+1)}{6} + (m+1)^2$$ We can thus follow this stream of logic: $$(1^2 + 2^2 + \cdots + m^2) + (m+1)^2 = \dfrac{m(m+1)(2m+1) + 6(m+1)^2}{6}$$ $$= \dfrac{(m+1) \cdot \{m(2m+1) + 6(m+1)\}}{6}$$ $$= \dfrac{(m+1) (2m^2+7m+6)}{6}$$ $$= \dfrac{(m+1)(m+2)(2m+3)}{6}$$ Thus, because we arrive at this result which we predicted above, we have proven that $$1^2 + 2^2 + \cdots + n^2 = \dfrac{n(n+1)(2n+1)}{6}$$
****
## 5.3.29
Let us assume $P(n)$ where $P(n) = \frac{n(n-1)}{2}$. We can also assume an integer $k$ such that $P(k) = \frac{k(k-1)}{2}$. If we assume that the prior equation is true for $k$ people in the room, we can easily expand this situation to $k+1$ people in the room. With one extra person, that extra person would need to give handshakes to all the people existing in the room ($k$). Thus, we can say that the following is true: $$P(k+1) = \frac{k(k-1)}{2} + k$$ $$= \dfrac{k^2-k+2k}{2}$$ $$=\frac{k^2+k}{2} = \frac{k(k+1)}{2}$$
Using our initial formula of $P(n) = \frac{n(n-1)}{2}$, we can see that $P(k+1) = \frac{(k+1)k}{2}$, which is exactly what we have derive. Thus, the situation is proven.
****
## 5.4.7
For some number $k$, we can assume the following is correct, given the formula in the problem: $$g_k - g_{k-1} = 2 \cdot (g_{k-1} - g_{k-2})$$ Extending this formula, we can extrapolate the following: $$2 \cdot (g_{k-1} - g_{k-2}) = 2^{k-2} \cdot (g_2 - g_1) = 2^{k-1}$$ We can analyze this pattern as such: $$g_2 - g_1 = 2$$ $$g_3 - g_2 = 4$$ $$\cdots$$ $$g_n - g_{n-1} = 2^{n-1}$$ We know that $g_n - g_1$ for some arbitrary $n$ must be $2+4+\cdots+2^{n-1}$, which is equal to $2^n-2$. Thus, we know that $g_n$ must be $2^n - 2 + g_1$, which is equal to $2^n+1$
****
## 5.5.38
Let us define $c_n$ as the number of distinct ways in which to climb $n$ stairs.
Where $n=1$, $c_1 = 1$ and where $n=2$, $c_2 = 2$. This is solved intuitively. We can therefore generalize the following where $n \geq 3$, there are two options: the last step being either $1$ or $2$ steps. In the case of a $1$ step as the last step, there are $c_{n-1}$ ways to reach the last step. Similarly, the case of $2$ steps as the last move brings about $c_{n-2}$ ways to reach the last set of $2$ stairs. Thus, the number of ways that we can reach a certain $n$ number of steps using the two aforementioned step sizes is by summing these two, generating the following: $$c_n = c_{n-1} + c_{n-2}$$. Thus, we can conclude the following for the situation: $$c_1 = 1, c_2 = 2$$ $$c_n = c_{n-1} + c_{n-2}\, | \,n \geq 3$$
****
## 5.6.25
Let us assume that $n$ is the input size for the program. Let us also assume that $O_n$ signifies the number of operations done for a particular number of inputs, $n$.
We are given, in the problem that $O_1 = 7$ and that $O_n = O_{n-1} \cdot 2$. Knowing this, we can intuitively say that $O_n = 7 \cdot 2^{n-1}$. Knowing this, we can plug in $25$ as our input to compute the answer: $$O_{25} = 7 \cdot 2^{24}$$