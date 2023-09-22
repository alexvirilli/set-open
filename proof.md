**Note on Notation**: Let $V_{\alpha}(x)$ indicate the neighborhood around $x$ given by $(x - \alpha, x + \alpha)$  
Let f be continuous, and let A be some set $(a, b)$. We will show that A is a topologically open set.  
Let $x_0 \in f^{-1}(A)$  
Then, $f(x_0) \in A$.  
Since $f$ is continuous, $\forall \epsilon > 0, \exists \delta > 0$ such that $|x - x_0| < \delta$  
This implies $|f(x) - f(x_0)| < \epsilon$  
$\Rightarrow f(x) \in V_{\epsilon}(f(x_0)) \subseteq A$  
$\Rightarrow x \in V_{\delta}(x_0) \subseteq f^{-1}(A)$  
Thus, the set $A$ is open
