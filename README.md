# Create a full HTML page with the enhanced project descriptions

html_content = """
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Jahnavi Chintala | Data Science Portfolio</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #f4f4f4; }
    header { background: #003366; color: white; padding: 30px 20px; text-align: center; }
    section { max-width: 1000px; margin: 40px auto; padding: 0 20px; }
    h2 { color: #003366; }
    .project { background: white; margin-bottom: 25px; padding: 20px; border-radius: 8px;
               box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1); }
    .project a { display: inline-block; margin-top: 10px; color: #003366; font-weight: bold;
                 text-decoration: none; }
    .project a:hover { text-decoration: underline; }
  </style>
</head>
<body>

<header>
  <h1>Jahnavi Chintala</h1>
  <p>Data Scientist | Machine Learning | Deep Learning | Time Series | Analytics</p>
</header>

<section>
  <h2>Projects</h2>

  <div class="project">
    <h3>1. Time Series Analysis of Oil and Gas</h3>
    <p>Developed ARIMA and SARIMA models to forecast oil and gas prices. Conducted seasonal decomposition, ADF/KPSS testing, and performance evaluation using RMSE and MAE. Provided actionable insights on price volatility and demand trends.</p>
    <a href="Project_Timeseries analysis of oil and gas.zip" download>Download Project Files</a>
  </div>

  <div class="project">
    <h3>2. Regression Models Benchmarking</h3>
    <p>Benchmarked 20+ regression models (e.g., Ridge, Lasso, XGBoost) across diverse datasets. Focused on feature engineering, error diagnostics, and comparative analysis using RMSE, R², and cross-validation. Built a model recommendation framework.</p>
    <a href="Regression_models_benchmarking.zip" download>Download Project Files</a>
  </div>

  <div class="project">
    <h3>3. Candida Auris Infection Prediction</h3>
    <p>Built machine learning models (Logistic Regression, Decision Trees) to predict Candida auris risk in hospitals. Identified critical clinical features like ICU stay and patient age. Delivered 88% accuracy and developed an infographic for awareness.</p>
    <a href="DMC_CANDIDA_AURSIS.zip" download>Download Project Files</a>
  </div>

  <div class="project">
    <h3>4. Brain Tumor Classification</h3>
    <p>Designed a CNN model to classify MRI brain scans into tumor types. Used Grad-CAM for interpretability, and performed data augmentation and normalization. Achieved over 95% accuracy and high sensitivity across classes.</p>
    <a href="Brain_tumor_classification.zip" download>Download Project Files</a>
  </div>

  <div class="project">
    <h3>5. Avila Bible Handwriting Classification</h3>
    <p>Analyzed medieval manuscript images using Random Forest, KNN, and SVM. Identified authorship of scanned Latin texts with 99.66% accuracy. Applied PCA, DBSCAN, and ensemble modeling for robust paleographic pattern discovery.</p>
    <a href="Group 12 Project Report.pdf" download>View Report</a>
  </div>

  <div class="project">
    <h3>6. Accidental Drug Deaths in Connecticut</h3>
    <p>Analyzed 10 years of opioid-related deaths using public health data. Built classifiers and ARIMA/SARIMA models to uncover risk factors and trends. Identified males aged 30–60 and fentanyl as key drivers of increasing overdose deaths.</p>
    <a href="6100_Accidental_Drug_Deaths_in_Connecticut_Project_Report[1].docx" download>View Report</a>
  </div>

</section>

</body>
</html>
"""





