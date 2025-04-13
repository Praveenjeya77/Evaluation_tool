# **AI-Powered Employability Evaluator** 🎯

The **AI-Powered Employability Evaluator** is a Gradio web application that uses machine learning to predict whether a student is employable based on their skill ratings. It utilizes a Perceptron model trained on a dataset of student employability factors. By entering personal information and rating various skills, users can instantly get an evaluation of their employability status.

## **Features** ✨
- **Skill Evaluation**: Rate skills on a scale from 1 to 5.
- **Employability Prediction**: Get a personalized result on whether you are employable based on your skill ratings.
- **Interactive Interface**: A simple, easy-to-use interface powered by Gradio.
- **Instant Feedback**: Receive an immediate employability prediction after entering your data.

## **How It Works** 🔄
1. **Data Input**:
   - Users input their name and rate various skills using sliders (from 1 to 5).
2. **Prediction**:
   - The model processes the entered data and predicts employability using a trained Perceptron model.
3. **Output**:
   - A message is displayed based on the model’s prediction, informing the user if they are employable or need to improve.
4. **Employment Evaluation**:
   - The model is based on the `Student-Employability-Datasets (1).xlsx`, a dataset containing student ratings across various skills and employability outcomes.

## **Technologies Used** ⚙️
- **Gradio**: For building the interactive web application interface.
- **Scikit-learn**: For the machine learning model (Perceptron).
- **Pandas**: For data handling and processing.
- **NumPy**: For array manipulation.

## **Dataset Explanation** 📊
The **`Student-Employability-Datasets (1).xlsx`** contains data on students' skills and employability. This data is used to train the Perceptron model. The dataset includes the following columns:
- Various skill ratings for each student (on a scale from 1 to 5).
- The **CLASS** column, which indicates whether a student is **Employable** (1) or **Not Employable** (0).

### **Data Columns**:
- The dataset consists of various columns representing different student ratings across skills such as communication, problem-solving, teamwork, etc.
- The target variable (**CLASS**) is used to train the model, where 'Employable' students are labeled as `1`, and 'Not Employable' students are labeled as `0`.

## **Inputs** 💬
- **Name**: Enter your name to personalize the feedback.
- **Skill Ratings**: Rate various skills from 1 (poor) to 5 (excellent) using sliders.

## **Outputs** 📥
- **Employability Result**: A message telling you if you're employable or if you need to upgrade your skills.
