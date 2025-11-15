### PROLOGUE:

*Hyper-BEAF* is an extension for the notation **BEAF** (*Bowers' Exploding Array Functions*) postulated to grow faster than **FGH** (*Fast Growing Hierarchy*).

## NOTE:
A deep knowledge of the **BEAF** notation is required to understand *Hyper-BEAF*.

---

### EPISODE I:
Starting with the *Superplus Notation*:

1. **Superplus Notation:**  
   `(#n) = {L(n)}`  
   Which is a **Ligion** “N” times.

2. **Duperplus Notation:**  
   `(#n, m) = {L(#(m)n)}`  
   Which is a **Ligion** “Superplus M times N times”.

3. **Metaplus Notation:**  
   `(#n, m, q) = {L(#(#m(#q))n)}`  
   While more arguments, more Superplus-es.

4. **Block:**  
   `n_m = (#n, n, n, ... m)`  
   A block is an array of Metaplus-es.

---

### EPISODE II:
*Superblocks* and more:

1. **Superblock:**  
   `n__m = (n_m, n_m, ... n_m)`  
   A *Superblock* is an array of *blocks*.

2. **Duperblock:**  
   `n[q]m = n_(q)m`  
   A *Duperblock* is an *argument-based* Superblock.

3. **Metablock:**  
   `n[q:a]m = (n[q]m, n[q]m, ... a)`  
   A *Metablock* is a *linear array* of a *Duperblock*.

4. You can add more arguments to a *Metablock*:  
   `n[q:a:b]m = (n[q]m, n[q]m, ... a)[q:a]` of itself.

---

### EPISODE III:
*Terminialis* function hierarchy:  
*Where the variable “Q” is “N” itself.*

1. **Terminialis-Alpha Function:**  
   `Ter(α, n) = n[q:q:q:q:q... α]n`  
   Reiterations of a *Metablock*.

2. **Terminialis-Beta Function:**  
   `Ter(β, n) = n[q:q:q... β[q:q:q... β... β]n]n`  
   It's a multi-array of `Ter(α, n)`.

3. **Terminialis-Gamma Function:**  
   `Ter(γ, n) = Ter(β)(n[q:q:q:q:q... γ]n, n[q:q:q:q:q... γ]n)`  
   It's a multi-array of `Ter(β, n)`.

---

### EPISODE IV:

## Terminialis-Alpha basic examples:
Here we have some *Terminialis-Alpha* examples:

> **Ter(3, 3)**  
> `= 3[3:3:3]3 = (3[3]3, 3[3]3, 3[3]3)`  
> of **BEAF Ligions** of itself. This means it is equal to this:
> `{ { L(3) # L(3) # L(3) , 3 , 3 } , { L(3) # L(3) # L(3) , 3 , 3 } , { L(3) # L(3) # L(3) , 3 , 3 } }`
> So this is a hybrid beetween *BEAF* Ligions and *Superpluses*.

> **Ter(4, 2)**  
> `= 2[2:2:2:2]2 = (2[2]2, 2[2]2, 2[2]2, 2[2]2)`  
> of **BEAF Ligions** of itself.

---

## Growth rate approximation

The maximum **FGH** class estimated of **BEAF**:  
`θ(Ω^Ω)`  *(Ordinal collapsing FGH)*

And my **FGH** approximation of **Hyper-BEAF**:  
`ψ₀(ε_{Ω+1})` *(Ordinal collapsing FGH)*


