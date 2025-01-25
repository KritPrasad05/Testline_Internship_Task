# 📊 **Student Quiz Performance Analyzer**

This project is a Python-based application designed to analyze student quiz performance by extracting and analyzing quiz data. It generates insights, recommendations, and visualizations to help students improve their performance over time. The project focuses on leveraging historical data trends and providing personalized feedback.

---

## 🛠️ **Features**
- **Data Analysis**: Analyze quiz data for insights such as accuracy, weak topics, and improvement trends.
- **Recommendations**: Generate actionable feedback for students based on their performance.
- **Visualization**: Plot performance trends using historical quiz scores.
- **Student Persona Definition**: Classify students as "High Achiever," "Needs Improvement," etc., based on their accuracy and improvement trends.
- **Data Handling**: Fetch and process JSON data from APIs.

---

## 📝 **Project Overview**
The **Student Quiz Performance Analyzer** helps in understanding a student's performance by analyzing quiz data. Using both current and historical data, it evaluates:
- Quiz accuracy rates.
- Improvement trends over time.
- Weak topics for focused learning.

It also provides visual performance trends and categorizes students into personas based on their performance, offering a comprehensive learning assessment.

---

## 🧠 **Approach Description**
1. **Data Fetching**:
   - JSON data is fetched from multiple API endpoints.
   - The data is saved locally in a structured format for further analysis.

2. **Data Processing**:
   - JSON files are loaded into pandas DataFrames for preprocessing.
   - Flattening nested structures like quiz questions and response maps for easier analysis.

3. **Performance Analysis**:
   - Calculates quiz accuracy, trends in historical scores, and identifies weak topics.
   - Uses metrics such as correct answers and overall scores for insights.

4. **Recommendations**:
   - Based on weak topics, accuracy, and trends, actionable feedback is provided.

5. **Visualization**:
   - Generates a performance trend plot using matplotlib for better understanding.

6. **Student Persona Classification**:
   - Categorizes students into personas like "High Achiever" or "Needs Improvement" based on their accuracy and trends.

---

## 🚀 **Setup Instructions**

### **Step 1: Clone the Repository**
```bash
git clone https://github.com/yourusername/quiz-performance-analyzer.git
cd quiz-performance-analyzer
```
### **Step 2: Install Dependencies**
Ensure you have Python 3.8+ installed. Install the required libraries using:
```bash
pip install -r requirements.txt
```
### **Step 3: Run the Script**
Run the project using:
```bash
python internship_task.py
```
### **Step 4: View Output**
- Insights and recommendations will appear in the terminal.
- The performance trend graph will open in a pop-up window.

### 🖥️ **Code Structure**
- internship_task.py: Main script containing all logic, including data fetching, analysis, visualization, and recommendations.
- data/: Directory where JSON data files are stored.
- APIs Used:
- Current quiz data: https://www.jsonkeeper.com/b/LLQT
- Historical data: https://api.jsonserve.com/XgAgFJ

## 🌟 **Acknowledgement**
This project was created as part of an internship assessment for [Testline](https://testline.in ). Special thanks to Testline for the opportunity to work on this task.




