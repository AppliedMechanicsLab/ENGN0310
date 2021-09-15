markdown


Let f(x) be a continuous, real-valued function on some interval [b,c]. Then, for any a \in (b,c)
$$
\lim_{\epsilon \rightarrow 0} \frac{1}{\epsilon} \int_{a}^{a+\epsilon} f(y) dy = f(a).
$$
Proof: By the Fundamental Theorem of Calculus, the function
$$
F(x) := \int_{b}^x f(y) dy
$$
is continuous on [b,c] and differentiable on (b,c) (in particular, F’(x) = f(x) for any x \in (b,c)). Hence
$$
F(a+\epsilon) - F(a) = \int_{a}^{a+\epsilon} f(y) dy
$$
and the statement in the proposition is simply the definition of the derivative of F(x) at x = a (i.e. a Newton quotient).
Remarks:
The assumption that f(x) is continuous is necessary. As a counterexample, if f(x) = 1 at x = 0 and f(x) = 0 everywhere else, then any (Lebesgue) integral on [0,\epsilon] is identically 0, regardless of epsilon.
The left/right bounds of the domain (the b and c) are fairly easily to generalize. I think if f(a) =/= 0, and f(x) were defined on [a,c] only, we could extend the function to [b,c] with b < a by simply setting f(x) = f(a) for any x < a.