# 🎵 Audio Frequency & Brightness Analysis

This project analyzes and compares multiple audio tracks based on their **average frequency content** and **spectral brightness (centroid)**. It leverages `librosa`, `scipy`, and `matplotlib` to extract interpretable audio features and visualize them.

---

## 📌 Features

- ✅ RMS loudness normalization for fair comparison  
- ✅ Spectrogram-based average power computation  
- ✅ Spectral centroid calculation as a brightness score  
- ✅ Frequency vs. power line chart with per-track labeling  
- ✅ Printed brightness (centroid) ranking for all tracks  

---

## 📊 Sample Output

- A matplotlib chart comparing each song’s average frequency content  
- Spectral brightness (in Hz) shown in the legend  
- Sorted brightness summary printed to console  
