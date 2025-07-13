# CODECRAFT_DS_01
import pandas as pd
import matplotlib.pyplot as plt


df = pd.read_csv("API_SP.POP.TOTL_DS2_en_csv_v2_38144[1].csv", skiprows=4)


df['2024'] = pd.to_numeric(df['2024'], errors='coerce')


population_2024 = df['2024'].dropna()


plt.figure(figsize=(10, 6))
plt.hist(population_2024, bins=30, color='skyblue', edgecolor='black')
plt.title('Distribution of Population Across Countries (2024)', fontsize=14)
plt.xlabel('Population', fontsize=12)
plt.ylabel('Number of Countries', fontsize=12)
plt.grid(True)
plt.tight_layout()
plt.show()
