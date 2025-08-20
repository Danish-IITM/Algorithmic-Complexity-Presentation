---
marp: true
theme: default
class: invert
math: mathjax
paginate: true
style: |
.columns {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 1rem;
  }
---

# <!--fit-->Computational Calculations of Algorithms :rocket:
<span style="color:grey">By: 23f3001327@ds.study.iitm.ac.in

---
# Mathematical equation
![bg left height:4in](logo.jpg)
Inline math works like $O(n \log n)$, $\Theta(n^2)$, $\Omega(\log n)$, $\tilde O(n)$ (soft-O), and $o(n)$.

Block math uses double dollars:

$$
O(n^k),\quad \Theta(f(n)),\quad \Omega(g(n))
$$

---
<!-- _backgroundColor: skyblue -->
## Types of complexities
<div class="columns">
<div>
* Constant Time Complexity (O(1))
* Logarithmic Time Complexity (O(log n))
* Linear Time Complexity (O(n))
</div>
<div>
* Loglinear Time Complexity (O(n log n))
* Quadratic Time Complexity (O(n²))
* Cubic Time Complexity (O(n³))
</div>