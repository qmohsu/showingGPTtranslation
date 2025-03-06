# AAE6102 Satellite Communication and Navigation Lab

## Hong Kong Polytechnic University  
**Department of Aeronautical and Aviation Engineering**  
**2025/26 Semester 2**  

- **Laboratory Date:** 27th March 2025, 15:30-18:20  
- **Lab Report Due Date:** Before [TBA]  

---

## Objective
The objective of this lab is to explore open-source **GNSS libraries**, evaluate their performance using publicly available **datasets**, and analyze their **strengths, limitations, and comparative effectiveness** through **parameter tuning and evaluation**.

---

## 1. Testing GNSS Libraries

### 1.1 Select a GNSS Library
Choose one open-source GNSS library from the following examples:

- **RTKLIB** (C/C++, Python wrapper, MATLAB wrapper):  
  - [Original version (C/C++)](https://github.com/tomojitakasu/RTKLIB)  
  - [Optimized version (C/C++)](https://github.com/rtklibexplorer/RTKLIB)  
  - [Python wrapper 1](https://github.com/IPNL-POLYU/pyrtklib_demo5)  
  - [Python wrapper 2](https://github.com/rtklibexplorer/rtklib-py)  
  - [MATLAB wrapper](https://github.com/taroz/MatRTKLIB)  
- **GoGPS** (MATLAB): [GitHub Repository](https://github.com/goGPS-Project/goGPS_MATLAB)  
- **GICI** (C/C++): [GitHub Repository](https://github.com/chichengcn/gici-open)  

### 1.2 Exploring the Library
- Review the functionality provided by the library.
- Identify key components such as:
  - Algorithms used
  - Inputs and outputs
  - Parameters available for tuning

---

## 2. Testing Open-Source Datasets with the Selected GNSS Library

### 2.1 Select a Dataset
Choose one or more datasets for testing:
- **UrbanNav Dataset**: [GitHub Repository](https://github.com/IPNL-POLYU/UrbanNavDataset)
- **Google Smartphone Decimeter Challenge**: [Kaggle Competition](https://www.kaggle.com/competitions/smartphone-decimeter-2023/data)

### 2.2 Process the Dataset
- Use the GNSS library to process the selected dataset.
- Generate positioning results such as:
  - **Trajectory** visualization
  - **Error analysis**
  - **Signal quality analysis**

---

## 3. Parameter Tuning and Performance Evaluation

### 3.1 Tune Parameters
Identify and modify tunable parameters, such as:
- **Positioning Mode**: Kinematic/Static, Single/Differential
- **Filter Settings**: Kalman Filter parameters
- **Satellite Selection Criteria**: Signal-to-noise ratio thresholds

Observe the effects of parameter changes on results.

### 3.2 Analyze Results
- Compare results before and after tuning.
- Evaluate performance metrics:
  - **Positioning accuracy**
  - **Processing time**
  - **Robustness to challenging conditions**

---

## 4. Lab Report Preparation
Prepare a detailed lab report covering the following aspects:

### 4.1 Parameter Tuning and Effects
- List the parameters tuned.
- Explain how parameter changes affected:
  - **Accuracy**
  - **Processing speed**
  - **Robustness**

### 4.2 Strengths and Limitations
- **Strengths**: Flexibility, robustness, ease of use.
- **Limitations**: Computational efficiency, lack of specific features.

### 4.3 Comparison with Other Libraries (Optional)
If time permits, test another GNSS library using the same dataset and compare based on:
- **Accuracy**
- **Ease of use**
- **Flexibility**
- **Computational efficiency**

### 4.4 Suggestions for Improvement
Provide recommendations to enhance:
- The selected GNSS library
- The parameter tuning process

---

## References
- [RTKLIB (Original)](https://github.com/tomojitakasu/RTKLIB)
- [RTKLIB (Optimized)](https://github.com/rtklibexplorer/RTKLIB)
- [UrbanNav Dataset](https://github.com/IPNL-POLYU/UrbanNavDataset)
- [Google Smartphone Decimeter Challenge](https://www.kaggle.com/competitions/smartphone-decimeter-2023/data)

---

**End of README**
