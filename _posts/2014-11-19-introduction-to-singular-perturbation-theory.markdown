---
layout: post
title: "Introduction to Perturbation Analysis"
---

<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"></script>
<script type="text/x-mathjax-config">
      MathJax.Hub.Config({
        tex2jax: {inlineMath: [['$','$']]},
        "HTML-CSS": 
          {scale: 92},
        TeX: { equationNumbers: { autoNumber: "AMS" }}});
</script>

*Intended audience: Someone with interest in applied problems that can be
described in terms of differental equations. Familarity with limits, power laws and ordinary differential equations required.*

What is singular perturbation theory and why should you care? If you have a
system of differential equations, it's often hard to solve it exactly. One way
out of this is to divide the solution into two parts: one exactly solvable, and
one approximative part. The latter is usually defined in terms of a power series
around a small error term that can be treated more rigorously.

What is the difference between singular and regular perturbation theory? Both
deal with error terms, but they difference is that, in regular perturbation, the
effect of the perturbation is small. For singular perturbations, the effect is
large. For singular perturbation theory, you can imagine a pendulum straight up
in the air. A small "touch" will make it go a lot to the left or a lot to the
right.


What is the simplest possible example of a singular and regular perturbation
problem?

$$ ex^2 + x + 1 = 0 $$


- What is a singularity in the domain vs singularity in the model?
