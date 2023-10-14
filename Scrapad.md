$\vec{v} = \begin{bmatrix} a_1 \\ a_2 \\ a_3 \end{bmatrix}$

$\vec{w} = \begin{bmatrix} b_1 \\ b_2 \\ b_3 \end{bmatrix}$

$\vec{v} ⋅ \vec{w} = a_1b_1 + a_2b_2 + a_3b_3$





$$e\sqrt{π}\log{7}-e^i\log{3}$$









The origins of the phrase “Survival of the fittest” is still very relevant in today’s society. Looking at the environment around us, it still very much mirrors England during the Industrial Revolution. It seems only the strongest individuals get to be successful in an industrialised country. However, while reading news about industrialising and non-industrialised countries, the sense of community and cooperation is much stronger. The question is, how does industrialisation disrupt the sense of community in a nation’s culture?

Area above the x-axis - area below the x-axis = total area of integral



[[Notepad]]


$\sim T \implies \sim((Q\implies R) \implies P)$


$L = \max(|x_1|, |x_2|, \dots, |x_N|)$


$\displaystyle \lim_{n \to \infty} n = \infty$ 


**Proof:**

Let \(\epsilon \in \mathbb{R}\) be a given positive number. We want to show that there exists a positive number \(M \in \mathbb{R}\) such that for all \(x > M\), the inequality \(\left|\frac{x^2}{2x^2+1} - \frac{1}{2}\right| < \epsilon\) is true.

Consider the expression \(\frac{x^2}{2x^2+1} - \frac{1}{2}\). We simplify this as follows:

\[
\begin{align*}
\frac{x^2}{2x^2+1} - \frac{1}{2} &= \frac{2x^2 - (2x^2+1)}{4x^2+2} \\
&= \frac{-1}{4x^2+2}.
\end{align*}
\]

Since \(\frac{-1}{4x^2+2}\) is negative for all \(x\), we can remove the absolute value signs in the inequality, yielding:

\[
\frac{1}{4x^2+2} < \epsilon.
\]

We aim to solve this inequality for \(x\), to determine the conditions under which it holds. Rearranging terms, we get:

\[
4x^2 + 2 > \frac{1}{\epsilon} \implies 4x^2 > \frac{1}{\epsilon} - 2.
\]

Solving for \(x^2\), and then for \(x\), we find:

\[
x^2 > \frac{1}{4\epsilon} - \frac{1}{2} \implies x > \sqrt{\frac{1}{4\epsilon} - \frac{1}{2}}.
\]

Let

\[
M = \sqrt{\frac{1}{4\epsilon} - \frac{1}{2}}.
\]

For \(\epsilon\) small enough such that \(\frac{1}{4\epsilon} - \frac{1}{2} > 0\) (specifically, for \(\epsilon < \frac{1}{2}\)), \(M\) is well-defined and positive. For such \(\epsilon\), if \(x > M\), then the inequality \(\left|\frac{x^2}{2x^2+1} - \frac{1}{2}\right| < \epsilon\) holds.

For \(\epsilon \geq \frac{1}{2}\), the range of the function \(\frac{x^2}{2x^2+1}\) which is [0, 0.5], ensures that \(\left|\frac{x^2}{2x^2+1} - \frac{1}{2}\right| < \epsilon\) holds for all \(x\) because \(\epsilon\) is larger than the maximum possible absolute difference.

Therefore, for every positive number \(\epsilon \in \mathbb{R}\), there exists a positive number \(M \in \mathbb{R}\) (specific as above for \(\epsilon < \frac{1}{2}\) and arbitrary positive for $\(\epsilon \geq \frac{1}{2}\)) such that for all \(x > M\), the desired inequality is satisfied. 

This completes the proof. \(\blacksquare\)
