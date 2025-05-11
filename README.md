## (h) Formal Lack-of-Fit Test

### Monday Section (n = 28)

1. **Height groups (6 intervals):**  
   - 150–165 cm: 3 students  
   - 166–170 cm: 3 students  
   - 171–175 cm: 5 students  
   - 176–180 cm: 8 students  
   - 181–185 cm: 8 students  
   - 186–190 cm: 1 student  

2. **Simple linear model:**  
   - Model:  
     Weight = 6.5793 + 0.3499 × Height  
   - Residual sum of squares:  
     SSE_linear = 2222.47 (df = 26)  

3. **Grouped‐categorical model (height intervals as factor):**  
   - Pure‐error sum of squares:  
     SSE_grouped = 2180.13 (df = 22)  

4. **Lack‐of‐fit sums of squares:**  
   - SS_LOF = SSE_linear − SSE_grouped  
     = 2222.47 − 2180.13  
     = 42.34  
   - df_LOF = k − 2  
     = 6 − 2  
     = 4  
   - MS_PE = SSE_grouped / df_PE  
     = 2180.13 / 22  
     = 99.10  
   - MS_LOF = SS_LOF / df_LOF  
     = 42.34 / 4  
     = 10.59  

5. **Lack‐of‐fit F‐statistic & p‐value:**  
   - F = MS_LOF / MS_PE  
     = 10.59 / 99.10  
     ≈ 0.107  
   - df = (4, 22)  
   - p ≈ 0.979  

6. **Conclusion:**  
   p ≫ 0.05 → fail to reject H₀ → **no significant lack‐of‐fit** → linear model is adequate.

---

### Tuesday Section (n = 32)

1. **Height groups (6 intervals):**  
   - 150–165 cm: 2 students  
   - 166–170 cm: 10 students  
   - 171–175 cm: 6 students  
   - 176–180 cm: 9 students  
   - 181–185 cm: 4 students  
   - 186–190 cm: 1 student  

2. **Simple linear model:**  
   - Model:  
     Weight = –91.8493 + 0.8934 × Height  
   - Residual sum of squares:  
     SSE_linear = 1860.91 (df = 30)  

3. **Grouped‐categorical model:**  
   - Pure‐error sum of squares:  
     SSE_grouped = 1737.82 (df = 26)  

4. **Lack‐of‐fit sums of squares:**  
   - SS_LOF = 1860.91 − 1737.82  
     = 123.09  
   - df_LOF = 6 − 2  
     = 4  
   - MS_PE = 1737.82 / 26  
     = 66.84  
   - MS_LOF = 123.09 / 4  
     = 30.77  

5. **Lack‐of‐fit F‐statistic & p‐value:**  
   - F = 30.77 / 66.84  
     ≈ 0.460  
   - df = (4, 26)  
   - p ≈ 0.764  

6. **Conclusion:**  
   p ≫ 0.05 → fail to reject H₀ → **no significant lack‐of‐fit** → linear model is adequate.
