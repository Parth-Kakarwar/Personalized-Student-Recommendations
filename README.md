Personalized Student Recommendations for Quiz Performance
Overview

This project analyzes student quiz performance and generates personalized recommendations to improve preparation. The solution processes two datasets:

    Current Quiz Data: Contains the latest quiz responses.
    Historical Quiz Data: Contains performance from the last 5 quizzes.

Approach:

    Data Preprocessing: Combines current quiz responses with metadata and processes historical quiz data.
    Performance Analysis: Calculates accuracy per topic and difficulty level.
    Insights Generation: Identifies weak and strong topics based on accuracy.
    Recommendations: Provides actionable suggestions based on performance, including focusing on weak topics and practicing higher or lower difficulty questions.
    Visualizations: Generates charts showing performance by topic and difficulty.

Setup Instructions
Prerequisites:

    Python 3.6+
    Required libraries: pandas, matplotlib, seaborn, numpy

Install dependencies:

pip install pandas matplotlib seaborn numpy

Running the Code:

Place the following datasets in the same folder as the script:

        Quiz Submission Data.json
        Quiz Endpoint.json
        Historical Quiz Data.json

 Run the script:

    python student_recommendations.py

Output:

The script generates:

    insights_summary.txt (Performance Summary)
    recommendations.txt (Personalized Recommendations)
    topic_accuracy.png (Accuracy by Topic)
    difficulty_performance.png (Performance by Difficulty Level)

Conclusion

This project provides personalized insights and recommendations based on student quiz performance, helping them improve in weak areas and build on their strengths.
