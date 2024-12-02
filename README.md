# **Customer Segmentation and Marketing Optimization for NextGen Financial Solutions** 🚀  

Welcome to the GitHub repository for the **Customer Segmentation and Marketing Optimization** project! This project focuses on improving subscription rates for NextGen Financial Solutions' newly launched term deposit product using advanced data analytics and machine learning techniques.  

---

## **Overview** 📋  

This project leverages data analysis, machine learning, and customer segmentation to identify key predictors of term deposit subscription and design targeted marketing campaigns.  

### **Key Objectives:**  
1. 🎯 Identify customer segments most likely to subscribe to the term deposit product.  
2. 🧠 Build predictive models to determine subscription likelihood.  
3. 💡 Develop actionable insights to inform marketing strategies.  

---

## **Project Features** ✨  

### **1. Data Exploration & Visualization** 📊  
- Performed exploratory data analysis (EDA) to uncover patterns and relationships in the dataset.  
- Visualized key insights using box plots, histograms, and feature importance graphs.  

### **2. Predictive Modeling** 🤖  
- Built and evaluated two machine learning models:  
  - **Logistic Regression**: Achieved 73.5% accuracy and provided interpretable coefficients for key features.  
  - **Decision Tree Classifier**: Achieved 72.5% accuracy, offering insights into hierarchical decision-making.  

### **3. Customer Segmentation** 🧩  
- Applied **K-Means Clustering** to segment customers into four distinct groups based on subscription likelihood.  
- Developed tailored marketing strategies for each segment to optimize campaign effectiveness.  

### **4. Marketing Strategy Recommendations** 📈  
- Designed data-driven campaigns targeting specific customer clusters with personalized incentives, educational outreach, and focused communication channels.  

---

## **Project Workflow** 🔄  

1. **Data Preprocessing**:  
   - Cleaned and standardized customer demographic and behavioral data.  
   - Handled outliers and missing values to ensure robust model performance.  

2. **Model Development**:  
   - Trained Logistic Regression and Decision Tree models to identify the most influential features.  
   - Conducted model evaluation using accuracy, precision, and recall metrics.  

3. **Customer Segmentation**:  
   - Applied K-Means clustering to group customers by deposit probability.  
   - Analyzed each cluster for unique characteristics and marketing needs.  

4. **Visualization**:  
   - Generated insightful graphs showcasing key predictors, customer clusters, and campaign performance.  

---

## **Dataset** 📂  

The project uses the [Bank Marketing Dataset](https://www.kaggle.com/datasets/janiobachmann/bank-marketing-dataset). This dataset includes customer demographics, financial health indicators, and engagement with previous campaigns.  

---

## **Repository Structure** 🗂️  

```plaintext  
📂 Customer-Segmentation-Marketing-Optimization  
├── 📁 data/                   # Dataset and preprocessed files  
├── 📂 notebooks/              # Jupyter notebooks (.ipynb)  
│   ├── analysis_notebook.ipynb  # Main notebook with EDA, modeling, and segmentation  
├── 📁 visuals/                # Visualizations and plots generated during the analysis  
├── 📁 models/                 # Saved models (if applicable)  
├── 📂 scripts/                # Optional Python scripts for specific tasks  
├── 📄 README.md               # This file  
├── 📄 requirements.txt        # Required Python libraries  
```

---

## **How to Execute the Project** 🛠️  

### **Prerequisites**  
1. 🐍 Install Python 3.7+ and Jupyter Notebook.  
2. 🔗 Clone the repository:  
   ```bash  
   git clone https://github.com/your-username/repository-name.git  
   ```  
3. 📂 Navigate to the repository folder:  
   ```bash  
   cd Customer-Segmentation-Marketing-Optimization  
   ```  
4. 📦 Install the required Python packages:  
   ```bash  
   pip install -r requirements.txt  
   ```  

### **Run the Notebook**  
1. 🖥️ Open the notebook in Jupyter:  
   ```bash  
   jupyter notebook notebooks/analysis_notebook.ipynb  
   ```  
2. ▶️ Execute the cells in sequence to:  
   - Explore the dataset and visualize key insights.  
   - Train and evaluate machine learning models.  
   - Perform customer segmentation using K-Means clustering.  

---

## **Visualizations** 🎨  

### **Key Insights from the Data**  
1. **📈 Box Plot of Target Variables**  
   - Understanding how all the customer characteristics are correlated with successful term deposit subscriptions.  
   ![image](https://github.com/user-attachments/assets/c1c9119f-f424-476c-baf0-8fc8fbcdd279)
 

2. **📊 Customer Segmentation**  
   - K-Means clustering revealed four distinct groups based on subscription probabilities.  
   ![result](https://github.com/user-attachments/assets/a8cbcaa9-e697-49bb-a9b4-4b439a3f74b8)
 

### **Feature Importance**  
- Visualized the top predictive features using both Logistic Regression coefficients and Decision Tree importance scores.  
  ![decison visal](https://github.com/user-attachments/assets/7d7bf142-1cb0-4656-9bb7-d756041d4eda)
  ![logic visual](https://github.com/user-attachments/assets/831b041e-70c9-4342-a734-cf50b64e97fc)



---

## **Future Work** 🔮  
- Enhance model performance by exploring advanced algorithms like Random Forest or Gradient Boosting.  
- Implement A/B testing for campaign strategies based on cluster-specific recommendations.  
- Integrate real-time customer data for dynamic prediction and segmentation.  

---

## **Contributors** 👥  
- [Ankit Bhatia](https://www.linkedin.com/in/ankit-bhatia12/) - Graduate MIS Student at University of Texas at Arlington | Ex-Business Data Analyst at Tata Consultancy Services (TCS)
- [Bhavesh Wadhwa](https://www.linkedin.com/in/bhaveshwadhwa/) - Graduate MIS Student at University of Texas at Arlington | Ex-Business Analyst at Infosys
- [Aarya Bhattacharyya](https://www.linkedin.com/in/aaryabhattacharyya97/) - Graduate MIS Student at University of Texas at Arlington | Ex-Senior Analyst at EY
- [Ido Shkuri](https://www.linkedin.com/in/ido-shkuri-a1148b1b4/) - Graduate MIS Student at University of Texas at Arlington | Ex- Product Manager at WobiLtd
- [Pratikshya Gautam](https://www.linkedin.com/in/pratikshya-gautam-503b31203/) - Graduate MIS Student at University of Texas at Arlington | Technology Analyst at Infosys
