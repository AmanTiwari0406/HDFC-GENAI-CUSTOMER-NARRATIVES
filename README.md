# HDFC-GENAI-CUSTOMER-NARRATIVES

Hyper-Personalized Banking Narratives using GenAI & RAG

Project Overview
This project, developed during my internship at HDFC Bank, focuses on leveraging Generative AI to create hyper-personalized marketing communications. By integrating customer data with Large Language Models (LLMs), the system generates unique customer narratives and tailored home loan pitches for a synthetic dataset of 1,000,000 customers.



Key Features

Customer Segmentation: Utilized K-Means Clustering to segment customers based on Age, Income, and EMI Amount.


LLM Integration: Successfully deployed the google/gemma-2b-it model via Hugging Face.


Resource Optimization: Optimized the model to run efficiently in a CPU environment, ensuring scalability without relying on expensive proprietary APIs.


RAG Architecture: Developed a framework for Retrieval-Augmented Generation to provide accurate answers to Standard Operating Procedures (SOP) questions.


Automated Evaluation: Referenced the Ragas framework to ensure the quality and accuracy of the generated content.

Tech Stack

Language: Python 

AI/ML: LangChain, Hugging Face Transformers, Scikit-learn, PyTorch 

Data Processing: Pandas, NumPy 

Visualization: Seaborn, Matplotlib 

How it Works

Data Prep: Synthetic banking data is cleaned and features like DigitalEngagement are engineered.


Clustering: Customers are grouped into four distinct segments to define marketing targets.


Prompt Engineering: Structured templates guide the LLM to act as a banking assistant.



Narrative Generation: The system produces personalized pitches highlighting low interest rates and flexible tenures based on individual profiles.


Outcomes
Demonstrated a full pipeline from raw data to actionable AI-generated marketing content.

Proved the feasibility of using Open-Source LLMs for high-scale banking applications.


