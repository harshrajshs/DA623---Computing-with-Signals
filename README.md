# Clustering-Based Spectrum Sensing with OFDM Modulation for Cognitive Radio Networks

*Author: [Harsh Raj]*

---

## Motivation

The rapid expansion of wireless communications has resulted in increased spectrum scarcity. Cognitive Radio Networks (CRNs) offer a promising solution by enabling dynamic spectrum access, allowing secondary users to opportunistically utilize underused frequency bands. Robust spectrum sensing, especially in OFDM-based systems, is crucial for this. I chose this topic to explore how unsupervised machine learning (clustering) can enhance spectrum sensing and contribute to more efficient wireless communication.

---

## Historical Perspective

Traditional spectrum sensing methods (energy detection, matched filtering, cyclostationary detection) have limitations, particularly under noise uncertainty and with unknown signals. Unsupervised learning, like clustering, is increasingly applied for adaptive, threshold-free signal detection, aligning with trends in  AI where data-driven approaches outperform hand-crafted methods.

---

## What I Learned

- Gained hands-on experience with OFDM modulation/demodulation using FFT/IFFT.
  ### 📺 **FFT and IFFT Algorithm Explanation**

  *For a clear visual and conceptual explanation of the FFT and IFFT algorithms, you can refer to this helpful video:*
  
  [![FFT and IFFT Algorithm](http://img.youtube.com/vi/h7apO7q16V0/0.jpg)](https://www.youtube.com/watch?v=h7apO7q16V0)
- Understood the limitations of basic energy detection and the benefits of adaptive, data-driven approaches.
- Applied KMeans clustering to sliding window energy values, enabling unsupervised, threshold-free spectrum sensing.
- Used visualization and ROC analysis to evaluate sensing performance.
- Simulated end-to-end transmission to measure bit error rate (BER) and reliability.

---

## Code / Notebook

The complete code and experiments are in [main.ipynb](main.ipynb).

**Highlights:**
- Custom FFT/IFFT for OFDM modulation/demodulation.
- AWGN channel simulation.
- Sliding window energy detection.
- KMeans clustering for adaptive signal detection.
- ROC curve and BER analysis.
- Visualizations for energy, clusters, and performance.

<details>
<summary>Example: Energy & Cluster Visualization</summary>


