<h1 align="center">A/B Testing - Comparing Conversion of Bidding Methods</h1>

<br/>

<h2>🚀 <strong>Project Overview</strong></h2>
<p>
This project focuses on A/B testing to evaluate Facebook's newly introduced bidding method, "Average Bidding," against the existing "Maximum Bidding." The goal is to determine whether the new method results in a statistically significant improvement in conversions (Purchases). Using rigorous statistical methods, we analyze the performance of both bidding strategies and provide actionable insights to the client.
</p>

<h2>📄 <strong>Dataset Story</strong></h2>
<p>
The dataset contains information about user interactions with advertisements and related conversions. It is divided into two groups:
<ul>
  <li><strong>Control Group:</strong> Used Maximum Bidding.</li>
  <li><strong>Test Group:</strong> Used Average Bidding.</li>
</ul>
Data points include impressions, clicks, purchases, and earnings from each group. These datasets are sourced from the <code>ab_testing_data.xlsx</code> file.
</p>
<p><em>Dataset available on <a href="https://www.kaggle.com/datasets/yusufbehrambayindir/ab-test12" target="_blank">Kaggle</a>.</em></p>

<h3>Key Features:</h3>
<ul>
  <li><strong>Impression:</strong> Number of ad views.</li>
  <li><strong>Click:</strong> Number of ad clicks.</li>
  <li><strong>Purchase:</strong> Number of products purchased after ad clicks.</li>
  <li><strong>Earning:</strong> Earnings generated from purchases.</li>
</ul>

<h2>📈 <strong>Project Workflow</strong></h2>
<ul>
  <li><strong>Data Preparation:</strong> Read and combined control and test group data, performed exploratory data analysis, and checked for outliers.</li>
  <li><strong>Hypothesis Setup:</strong> Established null (H₀) and alternative (H₁) hypotheses for conversion rates.</li>
  <li><strong>Assumption Checks:</strong> Verified normality and variance homogeneity assumptions using statistical tests.</li>
  <li><strong>Hypothesis Testing:</strong> Conducted Independent Two-Sample T-Test or Mann-Whitney U Test based on assumptions.</li>
  <li><strong>Result Interpretation:</strong> Analyzed p-values to determine statistical significance.</li>
</ul>

<h2>🛠️ <strong>Methods Applied</strong></h2>
<ul>
  <li><strong>Shapiro-Wilk Test:</strong> Tested normality of the data.</li>
  <li><strong>Levene's Test:</strong> Checked homogeneity of variances between groups.</li>
  <li><strong>Independent Two-Sample T-Test:</strong> Compared group means when assumptions were met.</li>
  <li><strong>Mann-Whitney U Test:</strong> Used when normality assumptions were violated.</li>
</ul>

<h2>🔧 <strong>Tools & Technologies Used</strong></h2>
<div align="center">
    <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" alt="Python"/>
    <img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"/>
    <img src="https://img.shields.io/badge/seaborn-4C6EF5?style=for-the-badge&logo=seaborn&logoColor=white" alt="Seaborn"/>
    <img src="https://img.shields.io/badge/matplotlib-013243?style=for-the-badge&logo=matplotlib&logoColor=white" alt="Matplotlib"/>
    <img src="https://img.shields.io/badge/scipy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white" alt="SciPy"/>
</div>

<h2>📊 <strong>Key Insights</strong></h2>
<ul>
  <li><strong>Control Group:</strong> Mean Purchase = 550.894</li>
  <li><strong>Test Group:</strong> Mean Purchase = 582.106</li>
  <li><strong>Normality and Variance Assumptions:</strong> Met for both groups.</li>
  <li><strong>Statistical Test Used:</strong> Independent Two-Sample T-Test.</li>
  <li><strong>p-Value:</strong> 0.349 (No statistically significant difference between groups).</li>
</ul>

<h2>📢 <strong>Recommendations</strong></h2>
<p>
The analysis indicates no statistically significant difference in conversions between Maximum Bidding and Average Bidding. It is recommended that the client consider other performance metrics such as Clicks or Earnings to decide on the optimal bidding strategy.
</p>

<h2>📢 <strong>Contact</strong></h2>
<ul>
    <li><a href="https://www.linkedin.com/in/yourusername/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white" alt="LinkedIn"/></a></li>
    <li><a href="mailto:your.email@example.com"><img src="https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white" alt="Email"/></a></li>
</ul>

<p align="center">&copy; 2025 Your Name. All rights reserved.</p>

<hr>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=ecembayindir&repo=AB-testing-facebook-bidding&label=Repository%20views&color=0e75b6&style=flat" alt="Repository Views">
</p>
