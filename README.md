# Heart_Disease_Dataset_Analysis

<h3>Overview</h3>
<p>This project provides a comprehensive exploratory and statistical analysis of a Heart Disease Dataset, containing 297 patients and 14 key clinical attributes. The primary goal was to identify the most critical biological and demographic factors that distinguish patients with heart disease from healthy individuals.</p>

<h3>Objectives</h3>
<ul>
  <li>Explore and clean data</li>
  <li>Analyze clinical and demographic tests and patterns</li>
  <li>Investigate relationships between features and the target</li>
  <li>Create visualizations to communicate findings effectively</li>
</ul>

<h3>Tools & Libraries</h3>
<ul>
  <li>Python</li>
  <li>Pandas</li>
  <li>Seaborn</li>
  <li>Matplotlib</li>
  <li>Plotly</li>
  <li>SciPy</li>
  <li>Google Colab</li>
</ul>

<h3>Dataset</h3>
<p>Heart disease dataset, obtained from Kaggle, containing 13 features and 1 target.</p>
<a href="https://www.kaggle.com/datasets/yaminh/heart-disease-dataset">Link to Dataset</a>

<h3>Key Findings</h3>
<p>Thalassemia type is the strongest predictor for heart disease. It had the highest correlation efficient (0.52) and the lowest p-value (1.2417e-18). A "Reversible Defect" result is a significant indicator for heart disease, while a "Normal" result is the strongest indicator of a negative diagnosis.</p>
<p>ST Depression is also a strong predictor for heart disease. A higher "sag" in the EKG during exercise is a definitive marker for heart disease.</p>
<p>Maximum heart rate has a negative relationship with heart health. The higher the maximum heart rate is the lower the chance of heart disease.</p>
<p>Age and Gender are weaker predictors for heart disease, although still statistically significant. Patients that are male have a higher chance of developing heart disease. Patients that are older (above 50) have a higher chance of developing heart disease.</p>
<p>For this particular study population it was identified that as the number of colored vessels from fluoroscopy increased, the likelihood of a positive diagnosis dropped significantly.</p>
<p>Cholesterol and Blood sugar were shown to have almost no correlation with heart disease in this specific group of patients.</p>


<h3>Visualizations</h3>
<figure>
<img width="1219" height="487" alt="Gender distribution" src="https://github.com/user-attachments/assets/42fd1574-c70e-48eb-80f9-6cde7a5d5ae3" />
<figcaption>Gender distribution among patients</figcaption>
</figure>
<figure>
<img width="1215" height="490" alt="Diagnosis" src="https://github.com/user-attachments/assets/b995626e-838f-410d-92fe-cd000838b39a" />
  <figcaption>Diagnostic distribution of patients</figcaption>
</figure>
<figure>
<img width="1247" height="297" alt="chest pain vs num vessels" src="https://github.com/user-attachments/assets/108b8ecb-e23a-4433-bf2c-c242de76470c" />
<figcaption>Chest pain vs Number of Vessels</figcaption>
</figure>
<figure>
<img width="866" height="561" alt="Thalassemia" src="https://github.com/user-attachments/assets/2bc9850f-2de0-4534-88c1-1e79ed681f42" />
<figcaption>Thalassemia</figcaption>
</figure>
<figure>
<img width="795" height="631" alt="Correlation Matrix" src="https://github.com/user-attachments/assets/baff6623-6d0e-4014-b557-bfbb790c0f28" />
<figcaption>Correlation Matrix</figcaption>
</figure>
<figure>
<img width="586" height="603" alt="ST depression" src="https://github.com/user-attachments/assets/644d4c99-8d55-497f-a3c8-77bdba8998bf" />
<figcaption>ST Depression vs Age</figcaption>
</figure>

<h3>Limitations</h3>
<p>Relatively small sample size (297 patients).</p>
<p>Gender imbalance may affect representativeness.</p>
<p>The dataset represents a single point in time for each patient. It doesn't account for changes as time progresses (how a patient's heart rate or ST depression changes over several years).</p>
<p>Observed relationships are correlational rather than causal.</p>

<h3>Conclusion</h3>
<p>This analysis successfully identified the primary predictors of heart disease within this clinical dataset. Through rigorous exploratory data analysis and statistical testing, it was determined that clinical stress-test indicators—specifically Thalassemia type, ST Depression, and Maximum Heart Rate—are the most significant predictors of a positive diagnosis. These features demonstrated far greater predictive power (with p-values as low as 1.24e-18) compared to traditional demographic factors like Age and Gender, or standard metrics like Cholesterol.

The findings highlight a "clinical profile" for high-risk patients: those exhibiting a reversible thalassemia defect, lower maximum heart rates during exertion, and significant ST segment depression on an EKG. However, it is important to note the limitations of this study, including the relatively small sample size of 297 patients and a notable gender imbalance. While these results are statistically definitive for this specific group, the geographical and time constraints of the data mean that further research using larger, more diverse, and modern datasets is required to ensure these findings generalize to the global population.

Ultimately, this project proves that while age and gender play a role, the biological response of the heart under stress remains the most critical factor in diagnosing coronary heart disease.</p>

<h3>Future Improvements</h3>
<ul>
  <li>The next logical step is to transition from statistical testing to predictive modelling. Implementing a Logistic Regression model would allow for the calculation of the specific probability of heart disease for new patients.</li>
  <li>To address the current limitation of a small sample size, future work should incorporate larger, multi-centre datasets.</li>
  <li>Tracking patient data over months or years would help identify early warning trends and the rate of disease progression, rather than just the current state of the heart.</li>
  <li>To make these insights accessible to medical professionals, the project could be expanded into a dynamic dashboard.</li>
</ul>
