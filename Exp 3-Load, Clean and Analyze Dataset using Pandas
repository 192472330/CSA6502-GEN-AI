import pandas as pd

# Create a student dataset
data = {
    'Name': ['Sunil', 'Ravi', 'Kiran', 'Anu'],
    'Marks': [85, None, 92, 78]
}

# Load dataset into DataFrame
df = pd.DataFrame(data)

print("Original Dataset:")
print(df)

# Clean missing values (replace with average)
df['Marks'] = df['Marks'].fillna(df['Marks'].mean())

print("\nCleaned Dataset:")
print(df)

# Calculate statistical information
average_marks = df['Marks'].mean()
highest_score = df['Marks'].max()

print("\nAverage Marks:", average_marks)
print("Highest Score:", highest_score)
