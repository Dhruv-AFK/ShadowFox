<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AI/ML Internship Projects - Report Overview</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            font-family: 'Inter', sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f0f2f5;
            padding: 2rem;
        }
        .container {
            max-width: 960px;
            margin: 0 auto;
            background-color: #ffffff;
            border-radius: 0.75rem; /* rounded-xl */
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05); /* shadow-xl */
            padding: 2.5rem;
        }
        h1 {
            font-size: 2.5rem; /* text-4xl */
            font-weight: bold;
            color: #1a202c; /* gray-900 */
            margin-bottom: 1.5rem;
            text-align: center;
            border-bottom: 2px solid #e2e8f0; /* border-b-2 border-gray-200 */
            padding-bottom: 1rem;
        }
        h2 {
            font-size: 2rem; /* text-3xl */
            font-weight: 600; /* font-semibold */
            color: #2d3748; /* gray-800 */
            margin-top: 2.5rem;
            margin-bottom: 1rem;
            padding-bottom: 0.5rem;
            border-bottom: 1px solid #edf2f7; /* border-b border-gray-100 */
        }
        h3 {
            font-size: 1.5rem; /* text-2xl */
            font-weight: 600; /* font-semibold */
            color: #4a5568; /* gray-700 */
            margin-top: 1.5rem;
            margin-bottom: 0.75rem;
        }
        p {
            margin-bottom: 1rem;
        }
        ul {
            list-style-type: disc;
            margin-left: 1.5rem; /* ml-6 */
            margin-bottom: 1rem;
        }
        ul ul { /* Nested lists */
            list-style-type: circle;
            margin-left: 1.5rem; /* ml-6 */
            margin-top: 0.5rem;
            margin-bottom: 0.5rem;
        }
        strong {
            font-weight: 600; /* font-semibold */
            color: #2d3748; /* gray-800 */
        }
        a {
            color: #3182ce; /* blue-600 */
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        /* Highlight style for tasks */
        .task-highlight {
            background-color: #f0f9ff; /* light blue background */
            border-left: 4px solid #38bdf8; /* blue border on the left */
            padding: 1rem;
            border-radius: 0.5rem;
            margin-bottom: 1.5rem;
        }
    </style>
</head>
<body class="font-inter antialiased">
    <div class="container">
        <h1>AI/ML Internship Projects Overview</h1>

        <h2 class="flex items-center">
            <span class="mr-2">🚀</span> Overview
        </h2>
        <p>This repository provides an overview of key projects undertaken during an Artificial Intelligence and Machine Learning (AI/ML) internship. The focus was on building foundational and advanced AI/ML knowledge, gaining practical experience with end-to-end machine learning pipelines, and understanding real-world applications through various tasks.</p>

        <h2 class="flex items-center">
            <span class="mr-2">🎯</span> Objectives
        </h2>
        <p>The primary objectives for this AI/ML internship were to:</p>
        <ul>
            <li>Build foundational and advanced knowledge in Artificial Intelligence and Machine Learning.</li>
            <li>Gain practical experience by implementing end-to-end machine learning pipelines.</li>
            <li>Understand real-world applications of AI through regression, classification, and Natural Language Processing (NLP) tasks.</li>
        </ul>

        <h2 class="flex items-center">
            <span class="mr-2">📋</span> Key Tasks & Responsibilities
        </h2>
        <p>During the internship, the following key tasks were completed:</p>

        <div class="task-highlight">
            <h3>Task 1: Boston House Price Prediction (Beginner – Regression)</h3>
            <ul>
                <li>Developed a Linear Regression model using the Boston Housing dataset.</li>
                <li>Conducted Exploratory Data Analysis (EDA), feature selection, and data preprocessing.</li>
                <li>Trained and evaluated the model using Mean Squared Error (MSE) and R² Score.</li>
                <li>Gained insights into supervised learning regression techniques.</li>
            </ul>
        </div>

        <div class="task-highlight">
            <h3>Task 2: Loan Approval Prediction (Intermediate – Classification)</h3>
            <ul>
                <li>Implemented a binary classification model to predict loan approvals.</li>
                <li>Performed data cleaning, missing value imputation, and categorical data encoding.</li>
                <li>Utilized Logistic Regression and Decision Tree algorithms.</li>
                <li>Evaluated model performance using Accuracy, Confusion Matrix, and Precision/Recall.</li>
                <li>Improved model performance through cross-validation and hyperparameter tuning.</li>
            </ul>
        </div>

        <div class="task-highlight">
            <h3>Task 3: Language Model Implementation (Advanced – NLP)</h3>
            <ul>
                <li>Explored Transformer-based models, specifically BERT, using HuggingFace Transformers.</li>
                <li>Fine-tuned a pre-trained BERT model for sentiment classification.</li>
                <li>Understood tokenization, positional encoding, and attention mechanisms.</li>
                <li>Learned about the pre-training and adaptation of large language models for downstream tasks.</li>
            </ul>
        </div>

        <h2 class="flex items-center">
            <span class="mr-2">💡</span> Learning Outcomes
        </h2>
        <p>Through this internship, the following learning outcomes were achieved:</p>
        <ul>
            <li>Developed hands-on experience in core AI/ML concepts including regression, classification, and NLP.</li>
            <li>Gained proficiency in essential Python libraries such as <code>pandas</code>, <code>scikit-learn</code>, and <code>HuggingFace Transformers</code>.</li>
            <li>Learned practical approaches to handling real-world datasets, including preprocessing, feature engineering, and model validation.</li>
            <li>Strengthened coding, debugging, documentation, and result interpretation skills.</li>
            <li>Enhanced the ability to break down complex problems into solvable machine learning components.</li>
            <li>Gained confidence to independently implement and evaluate machine learning projects.</li>
        </ul>

        <h2 class="flex items-center">
            <span class="mr-2">🚧</span> Challenges and Solutions
        </h2>
        <ul>
            <li>
                <strong>Challenge:</strong> Understanding and implementing advanced NLP models like BERT.
                <ul>
                    <li><strong>Solution:</strong> Official HuggingFace documentation was referred to, and models were simplified into small test cases before scaling up to complex implementations.</li>
                </ul>
            </li>
            <li>
                <strong>Challenge:</strong> Dealing with missing values and class imbalance in the Loan Approval dataset.
                <ul>
                    <li><strong>Solution:</strong> Imputation techniques, one-hot encoding for categorical data, and SMOTE (Synthetic Minority Over-sampling Technique) were employed to balance the dataset.</li>
                </ul>
            </li>
            <li>
                <strong>Challenge:</strong> Overfitting in the regression model.
                <ul>
                    <li><strong>Solution:</strong> Cross-validation and regularization techniques such as Ridge and Lasso Regression were applied to mitigate overfitting.</li>
                </ul>
            </li>
        </ul>

        <h2 class="flex items-center">
            <span class="mr-2">✨</span> Conclusion
        </h2>
        <p>This internship was a transformative learning experience, providing the opportunity to work on real-world AI/ML problems. From foundational regression tasks to implementing modern transformer-based language models, the journey was deeply rewarding and enriching. The exposure to diverse domains and use cases significantly increased confidence and skills in building machine learning solutions, preparing for more complex roles in the field of AI and ML.</p>
    </div>
</body>
</html>
