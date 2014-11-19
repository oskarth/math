---
layout: post
title: "Introduction to Perturbation Analysis"
---

<!--- MathJax Configuration -->
<script type="text/javascript"
src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML,http://drz.ac/javascripts/MathJaxLocal.js">
</script>

Hello world.

Here's a standard enzyme-substrate equation:

$$
\begin{align}
 E + S  \underset{k_{-1}}{\overset{k_{1}}
 {\begin{smallmatrix}
  \displaystyle\longrightarrow \\
   \displaystyle\longleftarrow
  \end{smallmatrix}}}
  C
   \overset{k_2}
  {\longrightarrow}
  E + P
\end{align}
$$

First we represent it as a systems of ODEs.

$$
\begin{align}
\frac{dE}{dt} &= -k_1 ES + k_{-1} C + k_2 C \\
\frac{dS}{dt} &= -k_1 ES + k_{-1} C \\
\frac{dC}{dt} &=  k_1 ES - k_{-1} C - k_2 C \\
\frac{dP}{dt} &= k_2 C
\end{align}
$$
