# DoS-ATTACK-DETECTION-IN-POWER-DISTRIBUTION-DEVICE-USING-RANDOM-FOREST-ALGORITHM-ON-IEEE-5-BUS-SYSTEM
# DoS Attack Detection in IEEE 5-Bus Power System 🔐⚡

## 📌 Project Overview
This project detects **Denial of Service (DoS) cyber attacks** on a smart power grid 
using the **Random Forest** machine learning algorithm, simulated on the IEEE 5-Bus test system.

Presented at: Intra-College Technical Event 2026

---

## 🛠️ Tools Used
| Tool | Purpose |
|------|---------|
| MATLAB | IEEE 5-Bus system simulation + dataset generation |
| Python (Jupyter) | Random Forest model training + visualization |
| scikit-learn | Machine learning |
| pandas, numpy | Data handling |
| matplotlib, seaborn | Graphs and plots |

---

## 📊 Results
| Metric | Value |
|--------|-------|
| Model Accuracy | **100%** |
| Total Samples | 1000 (500 Normal + 500 DoS Attack) |
| Training Samples | 800 |
| Testing Samples | 200 |
| Top Feature | packet_size (0.300) |

---

## 📁 Project Structure
```
├── dos_detection.ipynb       # Main Jupyter notebook
├── dos_dataset.csv           # Dataset from MATLAB simulation
├── confusion_matrix.png      # Model results visualization
├── feature_distribution.png  # Feature analysis graph
├── feature_importance.png    # Random Forest feature importance
└── README.md
```

## 🚀 How to Run
1. Clone this repository
2. Install libraries: `pip3 install numpy pandas scikit-learn matplotlib seaborn`
3. Open `dos_detection.ipynb` in VS Code
4. Run all 9 cells in order

---

## 👨‍💻 Author
Nithin A U | Electrical and Electronics Engineering 
R N S Institute of Technology, Bangalore 2025-26
