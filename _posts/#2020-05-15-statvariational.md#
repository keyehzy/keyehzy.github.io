---
layout: default
title:  "Using minimum principle in statistical mechanics"
date:   2020-05-15 16:00:00 -0300
categories: physics
---
<body>
<div id="content">
<h1 class="title">Using minimum principle in statistical mechanics</h1>
<p>
This post follow really closely Feynman notes on Statistical Mechanics. I guess this is equivalent to first order pertubation theory, but is goes as follows: Let us have a hamiltonian \(H_0\) for which we know how to calculate the partition function and therefore all of its statistical properties.
Then 
</p>

<div class="latex">
\begin{align*}
  F \le F_0 + \left< H-H_0 \right>_0
\end{align*}

</div>

<p>
In the book, the example used is of an anharmonic oscillator, a harmonics oscillator with an additional \(x^3\) term. Then our \(H_0\) is the harmonics oscillator, that we know how to calculate
</p>

<div class="latex">
\begin{align*}
  H_0 = \frac{p^2}{2m} + \frac{m \omega^2}{2} (x-a)^2
\end{align*}

</div>

<p>
We can find by usual means that 
</p>

<div class="latex">
\begin{align*}
  F_0 = kT \ln \left( 2 \sinh \frac{\hbar \omega}{2 k T}\right)
\end{align*}

</div>

<p>
and then we need to evaluate
</p>

<div class="latex">
\begin{align*}
  \left< H-H_0\right>_0 = \left< \frac{m \omega^2}{2}x^2 + k x^3 - \frac{m w^2}{2} (x-a)^2\right>_0
\end{align*}

</div>

<p>
The trick is to make a substitution \(y=x-a\)
</p>

<div class="latex">
\begin{align*}
  \left< H-H_0 \right>_0 =  \left< a^3 k+3 a^2 k y+\frac{1}{2} a^2 m \omega^2+3 a k y^2+a m y \omega^2+k y^3\right>_0 
\end{align*}

</div>

<p>
Odd terms in y cancel out and we are left with
</p>

<div class="latex">
\begin{align*}
  \left< H-H_0 \right>_0 = a^3 k+\frac{1}{2} a^2 m \omega^2+3 a k \left< y^2\right>_0
\end{align*}

</div>

<p>
with \(\left< y^2\right>_0 = \frac{\hbar}{2 m \omega} \cosh \frac{\hbar \omega}{2 k T}\) and 
</p>

<div class="latex">
\begin{align*}
  F \le F_0 + a^3 k+\frac{1}{2} a^2 m \omega^2+3 a k \left< y^2 \right>_0
\end{align*}

</div>

<p>
Minimizing the right-hand side gives 
</p>

<div class="latex">
\begin{align*}
  &=3 k a ^2 + m \omega^2 a + 3k \left< y^2 \right>_0=0\\
  &a = \frac{-m \omega^2 \pm \sqrt{-36 k^2 \left< y^2 \right>_0 + m^2 \omega^4}}{6 k}
\end{align*}

</div>

<p>
Taking the positive root and expanding for \(k \ll 1\) we find
</p>

<div class="latex">
\begin{align*}
  a = \frac{-3 k}{m \omega^2} \left< y^2 \right>_0 \iff \left< y^2 \right>_0 = -\frac{m \omega^2 a}{3 k}
\end{align*}

</div>

<p>
plugging back we have
</p>

<div class="latex">
\begin{align*}
  F \le F_0 -\frac{1}{2} a^2 m \omega^2 + \mathcal{O} (k)
\end{align*}

</div>

<p>
Therefore the correction for the free energy comes proportional to the displacement \(a\), which has the interpretation of the position where the average force vanishes (see book).
</p>

<p>
This is very nice but we can extend this concept to \(x^4\) terms as well, then we would need to evaluate 
</p>

<div class="latex">
\begin{align*}
  \left< H-H_0\right>_0 &= \left< \frac{m \omega^2}{2}x^2 + \lambda x^4 - \frac{m w^2}{2} (x-a)^2\right>_0 \\
  &= \left< a^4 \lambda +4 a^3 \lambda  y+\frac{1}{2} a^2 m \omega ^2+6 a^2 \lambda  y^2+a m y \omega ^2+4 a \lambda  y^3+\lambda  y^4 \right>_0 \\
  &= \left< a^4 \lambda +\frac{1}{2} a^2 m \omega ^2+6 a^2 \lambda  y^2+\lambda  y^4 \right>_0 \\
  &= a^4 \lambda +\frac{1}{2} a^2 m \omega ^2+6 a^2 \lambda  \left< y^2 \right>_0+\lambda \left<  y^4 \right>_0
\end{align*}

</div>

<p>
We find that \(\left< y^4 \right>_0 = \frac{3 \hbar ^2 \coth ^2 \frac{\hbar \omega}{2 k T}}{4 m^2 \omega ^2}\) and 
</p>

<div class="latex">
\begin{align*}
  F \leq F_0 + a^4 \lambda +\frac{1}{2} a^2 m \omega ^2+6 a^2 \lambda  \left< y^2 \right>_0+\lambda \left<  y^4 \right>_0
\end{align*}

</div>

<p>
Minimizing the right-hand side yields three solution
</p>

<div class="latex">
\begin{align*}
  4 a^3 \lambda +a m \omega ^2+12 a \lambda \left< y^2\right>_0 =0
\end{align*}

</div>

<p>
we see that \(a = 0\) is a solution and the other two are given by the quadratic formula
</p>

<div class="latex">
\begin{align*}
  a_{\pm} = \pm \frac{1}{2}\sqrt{\frac{-m \omega ^2-12 \lambda \left< y^2\right>_0 }{\lambda}}
\end{align*}

</div>

<p>
We must interprete this result as follows, if \(\lambda \ge 0\) then \(a=0\) always. This is the case because \(x^4\) has the same parity as the original Hamiltonian. It means the following, if the original Hamiltonian is even in \(x\) and the perturbation is also even in x, then no drift from the origin must occur. This becomes clear when look at the graph the aggregated potential. On the other hand, in order to have a real value for a we must have \(\lambda<0\), this is the case because we know that there is two additional ground states when this occur. Although interesting in itself, these solutions are no use for us here, because we are interested in the statistical mechanics of oscillators, and such oscillators must have bound states. This is not the case when \(\lambda < 0\), all the states decay away to infinity.
</p>


<center><div class="figure">
<img src="{{site.baseurl}}/imgs/x4.jpg" alt="x4.jpg" />
<p style="text-align:center;"><span class="figure-number">Figure 1: </span>Difference between the sign of \(\lambda\) on the potential</p>
</div></center>

<p>
Putting this minimized a, \(\left< y^2\right>_0\) and \(\left< y^4\right>_0\) back in to the equation we have for \(\lambda \ge 0\) (\(a=0\))
</p>

<div class="latex">
\begin{align*}
  F \leq F_0 + \frac{3 \lambda  \hbar ^2 \coth ^2\left(\frac{\omega  \hbar }{2 k T}\right)}{4 m^2 \omega ^2}
\end{align*}

</div>

<p>
To see this better we can look at the high temperature regime \(\hbar \omega \ll kT\). First we write \(x = \frac{\hbar \omega}{k T}\) and expand these expression for small \(x\). In the first case the expansion is straight forward
</p>

<div class="latex">
\begin{align*}
  F \leq F_0 + \frac{3 \lambda  \hbar ^2 \coth ^2\left(\frac{\omega  \hbar }{2 k T}\right)}{4 m^2 \omega ^2} \approx F_0 + \frac{\lambda  \hbar ^2}{2 m^2 \omega ^2}+\frac{3 \lambda  \hbar ^2}{m^2 x^2 \omega ^2}
\end{align*}

</div>

<p>
and the interpretation is the following, first we write this term as
</p>

<div class="latex">
\begin{align*}
  \left(\frac{ \lambda \hbar ^2}{2 m^2 \omega ^2}+\frac{3 \lambda \hbar ^2}{m^2 x^2 \omega ^2}\right) = \frac{\lambda \hbar ^2}{m^2 \omega ^2} \left(\frac{1}{2}+\frac{3}{x^2}\right) \approx \frac{3 \lambda \hbar ^2}{x^2 m^2 \omega ^2} = \frac{3 \lambda k^2 T^2}{ m^2 \omega^4} 
\end{align*}

</div>

<p>
And this term is nothing but a fraction of the inverse \(\alpha = \frac{m \omega}{2}\) squared
</p>

<div class="latex">
\begin{align*}
  \frac{3 \lambda k^2 T^2}{ m^2 \omega^4}  = \frac{3}{4} \frac{k^2 T^2}{\alpha^2}
\end{align*}

</div>

<p>
We see that, as it is expected, for high temperatures the system has a energy scale \(\alpha\) and as such the correction to the free energy \(F\) is porportional to this energy scale.
</p>
</div>
