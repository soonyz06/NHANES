# Todo
- Validate on simulated data with known ground truths 
- Handle heteroscedasticity, zero-inflated, right-skew and non-negative (currently raw for 2.)
- Calibrated noise model for sigma-estimation step  

# EDA
<img width="2338" height="992" alt="image" src="https://github.com/user-attachments/assets/68f9cc8d-4f38-40c6-aaa4-3eec406fb5b1" />
- Right-skew, Zero-inflated  
<img width="2346" height="956" alt="image" src="https://github.com/user-attachments/assets/b403aaae-50df-4b46-9e8f-34dfbcf534e1" />
- Error (w1-w2) somewhat normal, mu≈0
  
# 1.Noise2noise
<img width="2474" height="880" alt="image" src="https://github.com/user-attachments/assets/34a2addb-9a78-46d8-9fab-cfa4de7d6437" />
- w1->w2 MLP (standard scaled + yj transformed)
<img width="1192" height="1376" alt="image" src="https://github.com/user-attachments/assets/e3dfb4ec-31b3-49c1-948f-3cee5cb6c9fb" />
- diff scale but good enough for now
  
# 2.Generative Model
<img width="1280" height="778" alt="image" src="https://github.com/user-attachments/assets/66873029-110f-4e3a-90b3-4e33186662ff" />
<img width="740" height="1602" alt="image" src="https://github.com/user-attachments/assets/51792601-f6a9-42c3-943e-66c6ca2f1c5b" />
<img width="738" height="1738" alt="image" src="https://github.com/user-attachments/assets/3dcbde36-123f-42cf-9064-d01fe72078a4" />



