# Yezi's Capstone Project: LLM-Based Radiology Annotation System

## About
A passionate data scientist dedicated to unlocking the power of data and exploring AI-driven solutions. 

Data-relevant working experience in a variety of industries, ranging from SaaS, Fintech, Consulting, and Education. Solid programming foundations with Python, R, SQL, Tableau, and Power BI with the combination of business capabilities of building KIP systems and dashboards, presenting data insights to non-technical stakeholders, and fostering interpersonal communication with clients and cross-functional teams.

Keen interest and passion in Machine Learning, NLP, and AI technology. Hands-on experience conducting statistical analysis, applying ML techniques, and building LLMs and AI-relevant applications.

## Education							       		
- M.S., Applied Data Science	| The University of Chicago (_December 2024_)	 			        		
- B.S., Economics & Business | The University of Washington (_June 2023_)

## Notebooks

#### _Note: this portfolio consists of code notebooks I conducted for the Medical Language Processing Capstone Project at UChicago._

### Datasets & Data Sources
1. ~ 800,000 de-identified radiology reports from the University of Chicago Medicine with 7 columns

### Notebook 1: _'BioMistral7b_testing1.0.ipynb'_
This notebook aims to test the foundational medical knowledge and capabilities of BioMistral_7B on radiology report data obtained from the University of Chicago Medicine, which helped the team select the best LLM for fine-tuning. 

It tests three LLM capabilities: 

 - Ability to answer general medical questions
 - Ability to extract important medical entities/ontologies from radiology reports and map them to a finite number of labels/categories
 - Ability to extract important medical entities and map them to corresponding RadLex IDs(RadLex is a standardized radiology terminology dictionary that provides a comprehensive set of terms and codes to ensure consistent and standardized communication and data integration in the medical field).

I used two different methods to query the LLM: LLM's own chat functionality, and various chains in langchain's text generation pipeline.
