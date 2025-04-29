#  Project Title: Analyzing-Missed-Appointments-in-Brazilian-Healthcare

This data analysis project aims to identify factors contributing to missed appointments in the Brazilian healthcare system. The project explores the relationships between missed appointments and various attributes such as system-related factors (scholarship, SMS received, same-day scheduling) and patient-related factors (age, gender, medical conditions).

# Objectives
1. Identify Significant Factors: Determine the most significant factors influencing missed appointments.
2. Analyze Relationships: Analyze the relationships between missed appointments and key factors.
3. Visualize Findings: Visualize the relationships between missed appointments and significant factors.

# Methodology
1. Data Cleaning: Handling input errors, removing unnecessary columns, and converting variables to suitable formats.
2. Exploratory Data Analysis (EDA): Understanding variable distributions, identifying correlations, and visualizing relationships.
3. Analysis: Focusing on system-related (scholarship, SMS received, same-day scheduling) and patient-related factors (age, gender, medical conditions).

# Tools and Technologies
1. Python Programming Language: Used for data analysis and visualization.
2. Libraries:
    - Pandas: Data manipulation and analysis.
    - NumPy: Numerical computations.
    - Matplotlib: Data visualization.
    - Seaborn: Data visualization.
3. Development Environment: Jupyter Notebook on VS Code.

# Key Findings
1. Same-Day Scheduling: Patients who scheduled appointments on the same day were less likely to miss.
2. SMS Notifications: Sending SMS reminders did not reduce no-shows and was weakly positively correlated with missed appointments.
3. Bolsa Família Benefits: Receiving benefits from Bolsa Família did not significantly impact no-show rates.
4. Personal Attributes:
    - Age: Patients who missed appointments were generally younger.
    - Medical Conditions: Having multiple illnesses was associated with lower no-show rates.

# Limitations
1. Binary Variables: Most columns are binary, limiting statistical methods.
2. Correlation vs. Causation: Analysis focuses on correlation, not causation, requiring further studies.
3. Weak Correlations: Many correlations were weak due to categorical variables.

# Future Directions
Further studies using inferential statistics are required to establish causal relationships between variables and identify effective strategies to reduce missed appointments.

# Conclusion
The project identified same-day scheduling as a key factor in reducing missed appointments. Patient-related factors like age and medical conditions also played a role. However, sending SMS reminders and receiving benefits from Bolsa Família did not significantly impact no-show rates.
