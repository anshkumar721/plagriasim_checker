AI Plagiarism Checker
Ensure the originality and integrity of your written work with an intelligent AI-powered plagiarism detection system.

This comprehensive Flask-based web application provides robust content analysis, leveraging machine learning, web search capabilities, and secure user authentication to help students, academics, and writers maintain academic honesty and verify the uniqueness of their texts.

Features:
Advanced AI Detection: Utilizes TF-IDF vectorization and a Logistic Regression model to accurately identify potential plagiarism.
Web Source Comparison: Integrates with the Google Custom Search API to cross-reference submitted text against billions of web pages for comprehensive originality checks.
Secure User Authentication: Features a complete login and signup system with hashed passwords and persistent sessions for personalized access.
Personalized History Tracking: Stores and retrieves a detailed history of all plagiarism checks for authenticated users via a local SQLite database.
Real-time Character Count: Provides instant feedback on text length, enhancing usability for writers and content creators.
Intuitive & Responsive UI: Built with Tailwind CSS and vanilla JavaScript for a clean, modern, and adaptive user experience across devices.
Technologies Used
Backend:
Python 
Flask (Web Framework)
Scikit-learn (Machine Learning)
NLTK (Natural Language Toolkit)
Pandas (Data Manipulation)
SQLite (Database)
Requests (HTTP client)
hashlib (Password Hashing)
Frontend:
HTML5
Tailwind CSS (Utility-first CSS framework)
JavaScript (DOM manipulation, Fetch API)
How It Works:
The system preprocesses input text by cleaning, tokenizing, and removing stopwords. This processed text is then vectorized using a pre-trained TF-IDF model. A Logistic Regression model predicts potential plagiarism, while cosine similarity calculates the textual resemblance against a curated internal dataset. For deeper analysis, the application intelligently queries the web for similar phrases, providing source links if matches are found. All analyses are recorded in the user's private history.
