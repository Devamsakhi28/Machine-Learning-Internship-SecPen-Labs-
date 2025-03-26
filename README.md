# Machine-Learning-Internship-SecPen-Labs-
Simple README for Jupyter Notebook

1. Requirements
- Python 3.8+  
- Jupyter Notebook (install via `pip install notebook`)  
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`  

*2. Setup  
1. Download the notebook file (.ipynb)  
2. Place your dataset (CSV) in the same folder (optional)  
3. Launch Jupyter:  
   ```bash
   jupyter notebook
   ```  
4. Open the notebook file
   

3. How to Run 
- For synthetic data: Just run all cells (default)  
- For your dataset:  
  - Replace `df = pd.read_csv('your_dataset.csv')`  
  - Ensure CSV has:  
    - 20+ network features  
    - Label column (0=Normal, 1=DDoS, 2=PortScan, 3=BruteForce)
      

4. Key Cells  
| Cell Type | What It Does | Output |  
|-----------|--------------|--------|  
| **Data Load** | Generates/loads data | Sample data preview |  
| **Preprocess** | Cleans & prepares data | Selected features list |  
| **Train Models** | Runs 3 ML models | Training progress |  
| **Evaluate** | Tests model performance | Accuracy scores & confusion matrices |  

5. Results You'll Get 
✅ **Confusion Matrix Plots** (PNG files):  
   - Shows correct/wrong predictions per model  
✅ **Feature Importance Plot**:  
   - Reveals which network features matter most  
✅ **Performance Table**:  
   - Compares Random Forest, SVM, and Neural Network  
 

6. Troubleshooting**  
⚠️ **Errors?** Try:  
- `pip install` missing packages  
- Check CSV file path is correct  
- Restart kernel if memory issues

  
8. Support  
Contact: ndevamsakhi@gmail.com 
GitHub:   
