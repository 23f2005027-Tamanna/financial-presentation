<!-- Slide 1: Title slide -->
# Reveal.js Demo Presentation

**Prepared by:** Tamanna  
**Email:** 23f2005027@ds.study.iitm.ac.in

---

<!-- Slide 2: A Markdown slide -->
## Markdown Slide

This slide is written in **Markdown**. You can include lists:

- Item A
- Item B

And blockquotes:

> Reveal.js supports Markdown slides loaded from a file.

Note: This is also the place to show animated elements using *fragments* below.

---

<!-- Slide 3: Fragments (animated elements) -->
## Animated Items (Fragments)

1. <span class="fragment">First item (appears first)</span>  
2. <span class="fragment fade-in">Second item (fades in)</span>  
3. <span class="fragment">Third item (appears last)</span>

Note: Press forward to reveal them one-by-one.

---

<!-- Slide 4: Code sample with syntax highlighting -->
## Code Sample (Python)

```python
def predict_price(S0, r, sigma, T):
    """
    Example: Black-Scholes d1 calculation snippet
    """
    import math
    d1 = (math.log(S0) + (r + 0.5 * sigma**2) * T) / (sigma * math.sqrt(T))
    return d1

# Example usage
print(predict_price(100, 0.05, 0.2, 1.0))

---

<!-- Slide 5: Mathematical Equations -->
## Financial Formula (LaTeX)

Black–Scholes model definitions:

\[
d_1 = \frac{\ln(S_0/K) + \left(r + \tfrac{1}{2}\sigma^2\right)T}{\sigma\sqrt{T}}, 
\quad
d_2 = d_1 - \sigma\sqrt{T}
\]

Here is an inline formula example:  
The call price is given by  
$C = S_0 \Phi(d_1) - K e^{-rT} \Phi(d_2)$.

Note:
Explain verbally how the variables relate to pricing options (S0, K, r, sigma).

---

<!-- Slide 6: Speaker Notes -->
## Slide with Speaker Notes

This slide includes presenter notes.  
To see the notes during presentation, press **S** (Reveal.js opens the speaker window).

Note:
These are the speaker notes.  
Explain to the audience how the Black–Scholes formula works.  
Mention intuition behind d1 and d2.  

---

## Thank You!

Contact: 23f2005027@ds.study.iitm.ac.in
