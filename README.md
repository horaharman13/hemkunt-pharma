# hemkunt-pharma
# Hemkunt Sales Analysis using NumPy

## Project Description

This project performs basic data analysis on pharmaceutical sales data using Python and NumPy.  
The dataset contains sales information for different medicines along with marketing effort and doctor visits.

The goal of this project is to practice fundamental data science concepts such as:

- NumPy arrays
- Statistical calculations
- Correlation analysis
- Data visualization
- Basic business insights

This project is part of my Machine Learning learning journey.


## Dataset

The dataset contains the following columns:

- Day
- Medicine
- Marketing
- DoctorVisits
- Sales

Medicines used in the dataset:

- Hemvital
- Glimepiride
- Consivas


## Objectives

The analysis focuses on:

- Total sales calculation
- Average sales
- Maximum and minimum sales
- Standard deviation of sales
- Sales per medicine
- Relationship between marketing and sales
- Relationship between doctor visits and sales


## Tools Used

- Python
- NumPy
- Pandas 
- Matplotlib (for visualization)


## Key Findings

- Total sales were calculated using NumPy functions
- Hemvital showed the highest overall performance
- Strong positive correlation between Marketing and Sales
- Strong positive correlation between Doctor Visits and Sales
- Dataset is suitable for regression modeling


## Example Output

Total Sales  
Average Sales  
Standard Deviation  
Correlation values  
Bar charts and scatter plots


## Project Structure

# Hemkunt Recommendation System  
Collaborative Filtering & Content-Based Filtering using Python

## Project Description

This project implements a simple Recommendation System using two approaches:

1. Collaborative Filtering
2. Content-Based Filtering

The goal of the project is to understand how recommendation systems work using
NumPy, Pandas, and Cosine Similarity.

The dataset represents doctors and their preferences for medicines, as well as
their YouTube usage behavior for education or entertainment.

This project demonstrates core Machine Learning concepts used in real-world
applications such as Netflix, Amazon, YouTube, and medical CRM systems.


--------------------------------------------------

## Part 1 — Collaborative Filtering

### Problem Statement

Recommend medicines to doctors based on prescription patterns of similar doctors.

If two doctors have similar prescription behavior, the system recommends
medicines liked by one doctor to the other.

### Dataset

Doctor × Medicine rating matrix

Columns:

- Doctor
- Hemvital
- Glimepiride
- Consivas
- Insulin
- Metformin
- Amlodipine
- Telma
- Atorvastatin
- Clopidogrel
- VitaminD

Ratings:

0 = not prescribed  
1–5 = preference score

### Concepts Used

- NumPy arrays
- Dot product
- Cosine similarity
- User similarity
- Collaborative filtering
- Recommendation systems

### Steps

1. Load dataset
2. Convert to matrix
3. Compute cosine similarity
4. Find similar doctors
5. Recommend medicines


--------------------------------------------------

## Part 2 — Content-Based Filtering

### Problem Statement

Recommend YouTube Premium usage based on doctor behavior and interests.

Doctors who have similar features such as specialization, experience,
education usage, and entertainment usage should receive similar recommendations.

### Dataset

Doctor behavior dataset

Columns:

- Doctor
- Specialization
- Age
- Experience
- Watches_Education
- Watches_Entertainment
- YouTubePremium
- HoursPerDay

This dataset represents user features instead of ratings.

### Concepts Used

- Feature vectors
- Cosine similarity
- Content-based filtering
- Vector similarity
- Recommendation systems
- Linear algebra

### Steps

1. Load dataset
2. Convert features to vectors
3. Compute similarity between doctors
4. Find similar users
5. Recommend YouTube Premium


--------------------------------------------------

## Similarity Method

Cosine Similarity

Formula:

cos(A, B) = dot(A, B) / (|A| * |B|)

Used in:

- Recommendation systems
- NLP embeddings
- Search engines
- Machine learning


--------------------------------------------------

## Project Structure

