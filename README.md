# SPT-Depth
SPT Depth & Liquefaction Analysis

### 📌 Purpose
This notebook analyzes the **Standard Penetration Test (SPT)** data with respect to soil depth to assess the potential for **liquefaction during earthquakes**. The goal is to evaluate **Factor of Safety (FS)** against liquefaction using empirical methods and visualize critical depth zones.

### 🛠️ Tools Used
- **Python**
- **NumPy** for numerical computation
- **Matplotlib** for plotting and visualization
- **Seed & Idriss (1971)** method for Cyclic Stress Ratio (CSR)
- **Empirical correlation** for Cyclic Resistance Ratio (CRR)

### 📈 Key Outputs
- A dual-graph visualization:
  - **Left plot**: SPT values vs. depth
  - **Right plot**: FS against liquefaction vs. depth
- A clear threshold line at **FS = 1.0**, indicating the boundary of soil stability.

### 🧾 Interpretation
- Shallow soil (1 meter) has **FS = 1.3**, close to the liquefaction limit.
- Deeper layers show **high FS values (>> 1.0)**, indicating stable conditions.
- **Recommendation**: Pay extra attention to shallow layers, especially under high groundwater table conditions.
