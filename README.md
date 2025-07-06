# Online-Shoppers-Intention-Analysis-Project


**Goal**: Predict if a visitor will make a purchase (Revenue = True/False)  

### Key Steps:  
1. **Data**: 12,330 samples, 18 features (numerical + categorical)  
2. **Preprocessing**:  
   - Label encoding for categorical features  
   - SMOTE for class imbalance (only ~15-20% make purchases)  
   - StandardScaler for normalization  
3. **Models**: Tested 7 algorithms (Logistic Regression, Random Forest, XGBoost, etc.)  
4. **Best Model**: **Random Forest** (88% accuracy, 0.65 F1-score for Revenue=True)  

### Insights:  
- **PageValues** and **ExitRates** are top predictors  
- High precision for "No Revenue" (95%) but lower for "Revenue" (59%)  

**Conclusion**: Random Forest performs best, but further tuning could improve minority class predictions.  


