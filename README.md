# My-Resume
I make my resume using latex 1st time.


\documentclass[11pt,a4paper]{article}
\usepackage[left=0.5in,right=0.5in,top=0.5in,bottom=0.5in]{geometry}
\usepackage{enumitem}
\usepackage{hyperref}
\usepackage{titlesec}
\usepackage{xcolor}

% Remove page numbers
\pagestyle{empty}

% Section formatting
\titleformat{\section}{\large\bfseries\uppercase}{}{0em}{}[\titlerule]
\titlespacing{\section}{0pt}{8pt}{4pt}

% Custom commands
\newcommand{\resumeSubheading}[4]{
  \vspace{2pt}
  \begin{tabular*}{\textwidth}{l@{\extracolsep{\fill}}r}
    \textbf{#1} & #2 \\
    \textit{#3} & \textit{#4} \\
  \end{tabular*}\vspace{-5pt}
}

\newcommand{\resumeProjectHeading}[2]{
  \vspace{2pt}
  \begin{tabular*}{\textwidth}{l@{\extracolsep{\fill}}r}
    \textbf{#1} & \textit{#2} \\
  \end{tabular*}\vspace{-5pt}
}

\begin{document}

% Header
\begin{center}
    \textbf{\Huge MD GULAM HUSSAIN} \\
    \vspace{4pt}
    Bihar, India \\
    \vspace{2pt}
   Mob: \href{tel:7491923242}{+91-7491923242} $|$ 
    \href{mailto:mdgulamhussain.cusb@gmail.com}{mdgulamhussain.cusb@gmail.com}  $|$
    \vspace{2pt}
    \href{https://www.linkedin.com/in/md-gulam-hussain-197499298}{LinkedIn} $|$ 
    \href{https://github.com/mdgulamhussain-cusb-ai}{GitHub}
\end{center}

% Summary
\section{Professional Summary}
Master's student in Artificial Intelligence with strong expertise in machine learning, deep learning, and NLP. Proven ability to develop intelligent solutions through data-driven innovation using Python, TensorFlow, and scikit-learn. Experience in building and optimizing Machine Learning /Deep Learning models for predictive analytics, data classification, and customer segmentation. Passionate about responsible AI development and committed to continuous learning and innovation in dynamic environments.

% Education
\section{Education}
\resumeSubheading
{Central University of South Bihar}{Gaya, Bihar}
{Master of Science in Artificial Intelligence}{July 2024 -- May 2026}
\vspace{-8pt}
\begin{itemize}[leftmargin=0.15in, label={--}, itemsep=0pt, parsep=2pt]
    \item Core coursework: Machine Learning, Deep Learning, Neural Networks, NLP, AI Ethics
    \item Focus: Predictive modelling, intelligent systems, and data-driven decision making
\end{itemize}

\resumeSubheading
{Maharaja College, Ara}{Ara, Bihar}
{Bachelor's Degree in Computer Applications}{Graduated -- 2024}
\vspace{-8pt}
\begin{itemize}[leftmargin=0.15in, label={--}, itemsep=0pt, parsep=2pt]
    \item Strong foundation in computer science fundamentals, mathematics, and programming principles
\end{itemize}

% Technical Skills
\section{Technical Skills}
\begin{itemize}[leftmargin=0.15in, label={}, itemsep=0pt, parsep=2pt]
    \item \textbf{Programming Languages:} Python, SQL
    \item \textbf{Machine Learning \& AI:} Scikit-learn, TensorFlow, Keras, Neural Networks, Supervised Learning, Unsupervised Learning
    \item \textbf{Data Science:} NumPy, Pandas, Feature Engineering, Data Preprocessing, Model Optimization
    \item \textbf{Visualization \& Analysis:} Matplotlib, Seaborn, Statistical Analysis, Exploratory Data Analysis
    \item \textbf{ML Algorithms:} Linear Regression, K-Nearest Neighbors, K-Means Clustering, Classification, Regression
    \item \textbf{Core Competencies:} NLP Basics, Predictive Analytics, Customer Segmentation, Ethical AI, Problem-solving
    \item \textbf{Tools \& Platforms:} Jupyter Notebook, Git, GitHub, Kaggle, HackerRank, Google Colab
    \item \textbf{Languages:} English, Hindi, Urdu
\end{itemize}

% Projects
\section{Projects \& Technical Experience}
\resumeProjectHeading 
{Predictive Analytics System $|$ \small{\textit{Python, Scikit-learn, Pandas, NumPy}}}{2025}
\vspace{-8pt}
\begin{itemize}[leftmargin=0.15in, label={--}, itemsep=0pt, parsep=1pt]
    \item Engineering ed end-to-end machine learning pipeline for predictive analytics using Python and scikit-learn
    \item Implemented feature engineering and data preprocessing techniques to improve model accuracy by 25\%
    \item Deployed regression and classification models achieving 92\% accuracy on test datasets
\end{itemize}

\resumeProjectHeading
{Customer Segmentation using Deep Learning $|$ \small\textit{TensorFlow, Keras, Pandas, Matplotlib}}{2025}
\vspace{-8pt}
\begin{itemize}[leftmargin=0.15in, label={--}, itemsep=0pt, parsep=2pt]
    \item Built unsupervised learning model using TensorFlow to segment customer data into distinct behavioural groups
    \item Analyzed large datasets with Pandas and NumPy to extract meaningful patterns and insights
    \item Created visualization dashboards to present segmentation results to stakeholders
\end{itemize}

\resumeProjectHeading
{Multi-Class Data Classification Model $|$ \small\textit{TensorFlow, Neural Networks, Scikit-learn}}{2025}
\vspace{-8pt}
\begin{itemize}[leftmargin=0.15in, label={--}, itemsep=0pt, parsep=2pt]
    \item Designed and optimized deep neural network architecture for multi-class classification tasks
    \item Performed hyperparameter tuning and cross-validation to enhance model performance
    \item Achieved 89\% F1-score through systematic experimentation and iterative model refinement
\end{itemize}

\resumeProjectHeading
{Natural Language Processing Application $|$ \small\textit{TensorFlow, NLTK, Word Embeddings}\TransferLearning} {2025}
\vspace{-8pt}
\begin{itemize}[leftmargin=0.15in, label={--}, itemsep=0pt, parsep=2pt]
    \item Developed NLP-based text classification system using TensorFlow and word embeddings
    \item Implemented sentiment analysis and text preprocessing pipelines for unstructured data
    \item Applied transfer learning techniques to improve model efficiency and reduce training time
\end{itemize}

% Certificate 
\section{CERTIFICATES \& HAND-ON PRACTICE }
\begin{itemize}[leftmargin=0.15in, label={--}, itemsep=0pt, parsep=2pt]
    \item \textbf{Generative AI \& Deep Learning } $|$ HCL GUVI |\textcolor{blue}{\href{https://drive.google.com/file/d/14T6fhwXMov64jpaqF8y9bZCNl0e878Mz/view}{LINK}}\hfill{Dec 2025}
    \item \textbf{Master Git \& GitHub } $|$ WsCube Tech |\textcolor{blue}{\href{https://drive.google.com/file/d/1HpTnHkISla3Zc9OgY-gVJJ565ZQ3zpVK/view}{LINK}}\hfill{Dec 2025}
    \item \textbf{Autonomous Vehicles } $|$ Robolearn India |\textcolor{blue}{\href{https://drive.google.com/file/d/1-kgycp07Iz0YSTtuSA1FAExrRUfgsXyA/view}{LINK}}\hfill{Aug 2025}
    \item \textbf{Freedom with AI Masterclass } $|$ Freedom With AI |\textcolor{blue}{\href{https://drive.google.com/file/d/1O4D1A3wBo86hOCL4HYOt7_biOik1bk8U/view}{LINK}}\hfill{Aug 2025}   
    \item \textbf{Prompt Engneering } $|$ AI IXX |\textcolor{blue}{\href{https://drive.google.com/file/d/1gAuAJFutB1BZ8Xr6_FZklGFs25bNS3cF/view}{LINK}}\hfill{Aug 2025}
    \item \textbf{Agentic AI } $|$ Progression School |\textcolor{blue}{\href{https://drive.google.com/file/d/1hboP3hBreKyYvOvvcD-Ttqf74a4msycD/view}{LINK}}\hfill{Jul 2025}  
    \item\textbf{Cybersecurity } $|$ Central University of South Bihar|\textcolor{blue}{\href{https://drive.google.com/file/d/1v9nv626kHwCNNYCK3WByQ9O6zVYdxXv9/view}{LINK}}\hfill{Mar 2025}
    \item\textbf{Power BI } $|$ Jobaaj Learning |\textcolor{blue}{\href{https://drive.google.com/file/d/1-3Jpkr9FQP3TtJ6zhQyMidSV7qx70Q5i/view}{LINK}}\hfill{Aug 2025}


% Achievements & Leadership
\section{Additional Experience \& Achievements}
\begin{itemize}[leftmargin=0.10in, label={--}, itemsep=0pt, parsep=2pt]
    \item \textbf{Data Science Competitions:} Active participant on Kaggle and HackerRank, applying ML skills to real-world datasets
    \item \textbf{Emerging AI Research:} Regular exploration of technical blogs and research papers on Large Language Models (LLMs), Generative AI, and Computer Vision
    \item \textbf{Open Source Contribution:} Contributing to and utilizing open-source Python libraries including TensorFlow and scikit-learn
    \item \textbf{Responsible AI Advocacy:} Deep interest in ethical AI frameworks, bias mitigation, and societal impact of machine learning
    \item \textbf{Continuous Learning:} Self-directed learning through online courses, technical documentation, and hands-on experimentation
    \item \textbf{Collaboration:} Strong teamwork and communication skills demonstrated through academic projects and group assignments
\end{itemize}

\end{document}
