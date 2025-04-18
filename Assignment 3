import pandas as pd

# Sample data
data = {
    'Date': pd.date_range(start='2024-01-01', periods=7),
    'Cases': [100, 150, 200, 180, 170, 300, 400]
}
df = pd.DataFrame(data)

print("Total Cases:", df['Cases'].sum())
print("\nAverage per day:", df['Cases'].mean())
print("\nHighest Day:\n", df[df['Cases'] == df['Cases'].max()])
