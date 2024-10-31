# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

A complete graph is a graph with n vertices and every pair of vertices is connected by an edge.

Let $G_1$ and $G_2$ be two complete graphs, $G_1=(V_1 , E_1)$, $G_2 = (V_2, E_2)$, both graphs have the sane number of vertices n.

Assume $V_1$ have vertices $[u_1,u_2,u_3,....,u_n]$ and $V_2$ have vertices $[w_1,w_2,w_3,....,w_n]$. Because both graphs have the same number of vertices n, each vertex in $V_1$ can be then paired with a vertex in $V_2$, so there exist a bijection relation $f: V_1 \rightarrow V_2$, which specified that the $f(u_i)$ can be mapped to $w_i$, with each i=1,2,3,...,n

Assume $E_1=[(u_i,u_j) | u_i,u_j\in G_1,i\not=j]$ and $E_2=[(w_i,w_j) | w_i,w_j\in G_2,i\not=j]$. 

Beucase two graphs are complete graphs, therefore, in $G_1$, for any two vertices $u_i,u_j\in V_1$, $(u_i,u_j)\in E_1$, same for graph $G_2$, $w_i,w_j\in V_2$, $(w_i,w_j)\in E_2$

Since $f(u_i)$ can be mapped to $w_i$, $f(u_j)$ can be mapped to $w_j$ becuase of the bijection relation, therefore $f(u_i),f(u_j)\in V_2$, and $(f(u_i), f(u_j))\in E_2$

This proved that $(u,v)\in E_1$ iff $(f(u),f(v)) \in E_2$, therefore, the graphs must be isomorphic.

“I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.” --Doris Yan

