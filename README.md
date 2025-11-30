# 🧠 Brain-Atlas-Mini 
A compact, SEO-optimized neuroscience toolkit containing **brain atlas regions**, **color legend**, and **ready-to-use JSON files** for plotting and data visualization.

This repo is designed to help researchers, students, and developers quickly access **clean, minimalist brain-region maps** for figures, diagrams, and neuroscience apps.

---

## 📦 What's Inside?

1. High-quality PNG/SVG diagrams
- Cortex  
- Hippocampus  
- Striatum  
- Thalamus  
- Cerebellum

2. `brain_regions.json`
A structured file containing:
- Region names  
- Color-blind-friendly hex codes  
- Short descriptions  
- Coordinates for plotting  

3. Demo plotting scripts  
Both **Python** and **R** versions included:
- `brain_plot.py`  
- `brain_plot.R`

---

## 🎯 Why This Repo?
Millions of people search for:

- “brain atlas png”  
- “hippocampus diagram transparent”  
- “brain region color palette”  

This repo provides clean, uniform, downloadable diagrams + code — **perfect for neuroscience papers, posters, and GitHub SEO.**

---

## 🧬 Example: How To Load the JSON File

### **Python**
```python
import json

with open("brain_regions.json") as f:
    regions = json.load(f)

for r in regions:
    print(r["name"], r["color"])

