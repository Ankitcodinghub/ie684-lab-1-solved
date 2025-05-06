# ie684-lab-1-solved
**TO GET THIS SOLUTION VISIT:** [IE684 Lab 1 Solved](https://www.ankitcodinghub.com/product/ie684-lab-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;97626&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;IE684 Lab 1 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Exercise 1: Gradient Descent

We will start with a procedure which helps to find a minimizer of the function f(x),x ∈ Rn.

We will use the following gradient descent type algorithm:

Input: Starting point x0, Stopping tolerance τ, Step length η. Initialize k = 0

while ∥∇f(xk)∥2 &gt; τ do

xk+1 ←xk −η∇f(xk)

</div>
<div class="column">
05-January-2022

</div>
</div>
<div class="layoutArea">
<div class="column">
k=k+1 end

Output: xk .

</div>
</div>
<div class="layoutArea">
<div class="column">
Algorithm 1: Gradient Descent Procedure with constant step length

</div>
</div>
<div class="layoutArea">
<div class="column">
<ol>
<li>Note that in the notebook file shared with you, Algorithm 1 is implemented to solve f(x) = f(x1,x2) = (x1 + 100)2 + (x2 − 25)2 with a constant step length η = 0.1, stopping tolerance τ = 0.001 and with the starting point x0 = (10, 10).</li>
<li>[R]Whatistheminimizerandminimumfunctionvalueoff(x)=f(x1,x2)=(x1+100)2+(x2−25)2?</li>
<li>[R] With starting point x0 = (10, 10) and η = 0.1, we will now study the behavior of the algorithm for different tolerance values. Try τ = 10−p where p = 1,2,…,10. For each τ, record the final minimizer, final objective function value and number of iterations taken by the algorithm to terminate. Prepare a plot where the number of iterations is plotted against τ values. Comment on the observations. Comment about the minimizers and objective function values obtained for different choices of the tolerance values.</li>
<li>[R] With starting point x0 = (10,10) and τ = 10−5, we will study the behavior of the algorithm for different step length values. Try η ∈ {0.0001, 0.001, 0.01, 0.1, 0.2, 0.4, 0.5, 0.6, 0.7, 0.8, 0.9}. For each η, record the final minimizer, final objective function value and number of iterations taken by the algorithm to terminate. Prepare a plot where the number of iterations is plotted against η values. Comment on the observations. Comment about the minimizers and objective function values obtained for different choices of the step length values.</li>
<li>[R] With τ = 10−5 and η = 0.1, we will study the behavior of the algorithm for different starting points. Consider x0 ∈ {(10000, 10000), (500, 0), (0, 1000), (1, 1), (−500, −2)}. Prepare a table listing the final minimizer, final objective function value and number of iterations taken by the algorithm to terminate for the different starting points. Comment on your observations.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
IE684, IEOR Lab

Lab 01 05-January-2022

Exercise 2: Line Search

In this exercise, we will design a procedure to find a suitable step length. We consider the following algorithm:

Input: Starting point x0, Stopping tolerance τ. Initialize k = 0

while ∥∇f(xk)∥2 &gt; τ do

ηk = arg minη≥0 f(xk − η∇f(xk)) xk+1 ←xk −ηk∇f(xk)

k=k+1

end

Output: xk .

Algorithm 2: Gradient Descent Procedure with line search to compute step length

1. [R] Write the function f(x) = f(x1,x2) = (x1 + 100)2 + (x2 − 25)2 in the form x⊤Ax + 2b⊤x + c, where

x∈R2,Aisasymmetricmatrixofsize2×2,b∈R2 andc∈R.

2. [R] It turns out that for a function of the form f(x) = x⊤Ax + 2b⊤x + c, where A ∈ Rn×n is a symmetric matrix, b ∈ Rn and c ∈ R, the analytical solution to minα≥0 f (x − α∇f (x)) can be found in closed form. Find the solution.

3. Use the answers to Questions 1 and 2 to design a procedure to compute the step length ηk in Algorithm 2 forthefunctionf(x)=f(x1,x2)=(x1+100)2+(x2−25)2. ImplementtheprocedureasaPythonfunction (complete the code in compute steplength module in the notebook).

4. [R] With starting point x0 = (10,10) and the new module to compute ηk, try τ = 10−p where p = 1,2,…,10. For each τ, record the number of iterations taken by the algorithm to terminate. Prepare a plot where the number of iterations is plotted against τ values. Compare and contrast the plot with the plots obtained in Exercise 1 with fixed step length values.

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
