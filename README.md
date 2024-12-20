# Student-Performance-Analysis-Tool
This tool can help educators and students understand performance trends, identify areas for improvement, and make data-driven decisions.


import pandas as pd

# Load the CSV file into a DataFrame
data = pd.read_csv('student_scores.csv')

# Display the first few rows of the DataFrame
print("Data Preview:")
print(data.head())

# Calculate the average score
average_score = data['score'].mean()

# Print the average score
print(f"\nThe average score of the students is: {average_score:.2f}")
