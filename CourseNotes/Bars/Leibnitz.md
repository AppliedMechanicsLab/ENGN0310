
{% include mathjax_support %}
{% include command %}


## Proof of  $ \lim_{\epsilon\to 0}\frac{1}{\epsilon}\int_{a}^{a+\epsilon}f(\xi)\, d\xi=f(a)$


#### Proposition

Let f(x) be a continuous, real-valued function on some interval $[b,c]$. Then, for any $a \in (b,c)$

$$
\lim_{\epsilon \rightarrow 0} \frac{1}{\epsilon} \int_{a}^{a+\epsilon} f(y) dy = f(a).
$$

#### Proof: 

By the Fundamental Theorem of Calculus, the function

$$
F(x) := \int_{b}^x f(y) dy
$$

is continuous on $[b,c]$ and differentiable on $(b,c)$. In particular, $F’(x) = f(x)$ for any $x \in (b,c)$. Let $a\in(b,c)$ and from the definition of $F$, we get that

$$
\begin{align}
F(a+\epsilon) - F(a) &= \int_{a}^{a+\epsilon} f(y) dy,\\
\frac{F(a+\epsilon) - F(a)}{\epsilon} &= \frac{1}{\epsilon}\int_{a}^{a+\epsilon} f(y) dy,\\
\lim_{\epsilon \to 0^+}\frac{F(a+\epsilon) - F(a)}{\epsilon} &= \lim_{\epsilon \to 0^+}\frac{1}{\epsilon}\int_{a}^{a+\epsilon} f(y) dy
\end{align}
$$

The term on the left hand side of the last equation is in fact the  value of the right derivative of $F$ at $a$. However, since $F$ is differentiable in $(b,c)$ the term is equal to $F'(a)$. Finally, since $F’(x) = f(x)$ we get that

$$
\begin{align}
f(a)=\lim_{\epsilon \to 0^+}\frac{1}{\epsilon}\int_{a}^{a+\epsilon} f(y) dy.
\end{align}
$$


<!-- #### Remarks: 

(only for graduate students and advanced and mathematics oriented undergraduate students)

The assumption that $f$ is continuous is necessary. As a counterexample, if $f(x) = 1$ at $x = 0$ and $f(x) = 0$ everywhere else, then any (Lebesgue) integral on $[0,\epsilon]$ is identically 0, regardless of epsilon. The left/right bounds of the domain (the b and c) are fairly easily to generalize.  -->
<!-- I think if f(a) =/= 0, and f(x) were defined on [a,c] only, we could extend the function to [b,c] with b < a by simply setting f(x) = f(a) for any x < a. -->