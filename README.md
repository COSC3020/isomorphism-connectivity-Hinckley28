[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/QM7QGF1q)
# Isomorphism

Prove that if two graphs $A$ and $B$ are isomorphic they do *not* have to
be completely connected. I have started with the formal definition of
isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

Answer: 
Lets take the example where graph $A$ has nodes $(a, b, c, d)$ and graph $B$ has nodes $(1, 2, 3, 4)$.\
graph $A$ has edges $(a,b), (b,c), (c,d)$ and graph $B$ has edges $(1, 2), (2, 3), (3, 4)$\ 

If we take a bijection $f: V_1 \rightarrow V_2$, where $f(a) = 1, f(b) = 2, f(c) = 3, f(d) = 4.
We can see that the graphs are isomorphic because where there is an edge $(a, b)$, is an edge $f(a), f(b)$.\
For edge $(b, c)$ there is the edge $f(b), f(c)$ and this proves to be true trough the whole graph.\
This proves by definition that the graphs $A$ and $B$ are isomorphic by definition even though they are not completely connected themselves. 
