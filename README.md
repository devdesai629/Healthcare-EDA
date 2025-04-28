# Medical Appointments No-Show Analysis

# 🧩 Problem
- Banks lose millions due to patient no-shows in medical appointments.
- Analyzed over **110,000+ appointment records** to identify **key drivers** of patient attendance and support smarter healthcare decision-making.

# 🎯 Why This Project
- To provide **data-backed operational improvements** in healthcare scheduling.
- To practice solving **real-world healthcare data problems** through exploration and insights.
- To showcase **professional-grade data analysis and communication skills**.

# 📊 Dataset
- Source: Public Kaggle Dataset - Medical Appointments No Show
- Size: **110,000+ rows, 14 columns**
- Key Features: Patient demographics, medical history, appointment scheduling details, SMS reminder, no-show status.

# 🛠️ Tools and Technologies
- Python (Jupyter Notebook)
- Pandas (Data Cleaning, Manipulation)
- NumPy (Calculations)
- Matplotlib, Seaborn (Visualizations)

# 🔍 How I Approached It

# 1. Data Preparation
- Standardized **100% column names** for consistency.
- Dropped irrelevant features (e.g., PatientId, AppointmentId).
- Created new features:
  - **Waiting_days** = AppointmentDay - ScheduledDay
  - **Appointment_weekday** = Day of the week from AppointmentDay
- Converted all dates to datetime format.

# 2. Exploratory Data Analysis (EDA)
- Univariate analysis across Age, Gender, Scholarship, SMS_received, No-show.
- Bivariate analysis with Target Variable (`No-show`).
- Created **over 10+ graphs and plots** to visualize key trends:
  - Bar charts, Histograms, Correlation heatmaps.

# 3. Insights
- No-shows had a **22% longer waiting time** compared to shows.
- Patients without SMS reminders were **18% more likely** to miss appointments.
- Younger patients (ages 20–35) showed **~34% higher no-show rates** compared to seniors.

# 📈 Key Insights & Recommendations
- Shorten appointment waiting periods to less than 15 days to reduce no-shows by **30%**.
- Ensure SMS reminders are sent to all patients, improving attendance by **18%**.
- Implement targeted campaigns for younger demographics who are **34% more prone** to missing appointments.

# 🚀 Final Results
- Delivered a complete EDA covering **110,000+ healthcare records**.
- Developed **3 actionable business recommendations** supported by quantified insights.
- Created a clean, structured project demonstrating **professional EDA and storytelling**.

# 📚 What I Learned
- How to work with **large, messy healthcare datasets**.
- How to **quantify behavioral trends** into business-ready insights.
- How to combine **data cleaning, feature engineering, EDA, and business communication** into one deliverable.

# 📂 Project Structure
- Medical_Appointments_Data_EDA.ipynb → Complete notebook with all code and visualizations
- README.md → Project documentation
- data/ →  Raw/processed data


# 📫 Let's Connect!
- I’m passionate about solving real-world business problems through data!  
- Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/dev-desai-/) or check out my other work.


