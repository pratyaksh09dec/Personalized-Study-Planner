# Personalized-Study-Planner
Personalized Study planner using student behaviour like study hours, attendance, sleep hours, previous marks etc. to achieve their target score.
This project is a Smart Study Planner System built using Python and Machine Learning. It analyzes student-related factors such as study hours, attendance, sleep, distractions, and previous marks to predict academic performance and generate personalized study improvement plans.

The project uses:
    Data preprocessing
    Feature engineering
    Clustering
    Machine learning prediction
    Personalized recommendation generation
    Features
  
1. Data Preprocessing
    Missing value detection
    Data cleaning
    Data type analysis
    Outlier visualization using boxplots
2. Feature Engineering
    New features are created from the dataset, including:
    Study Hours
    Attendance Percentage
    Sleep Hours
    Distraction Time
    Assignment Completion Rate
3. Data Standardization
    Uses StandardScaler for normalization of numerical features
4. Student Clustering
    Students are grouped into difficulty/performance categories using:
    K-Means Clustering
    Clusters help identify:
    Easy learners
    Medium learners
    Hard learners
6. Performance Prediction
    The system predicts student scores using:
    Random Forest Regressor
6. Personalized Study Plan Generator
    The notebook generates custom study recommendations by:
    Increasing study hours
    Reducing distraction time
    Optimizing performance parameters
   
Technologies Used
    Python 3.x
    NumPy
    Pandas
    Matplotlib
    Seaborn
    Scikit-learn
    Jupyter Notebook
