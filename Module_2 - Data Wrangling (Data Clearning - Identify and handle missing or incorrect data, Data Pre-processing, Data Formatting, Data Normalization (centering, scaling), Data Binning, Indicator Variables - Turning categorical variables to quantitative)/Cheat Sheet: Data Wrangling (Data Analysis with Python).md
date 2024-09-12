#Cheat Sheet: Data Wrangling

| Package/Method | Description |Code Example |
| --- | --- | --- |
| Replace missing data with frequency | Replace the missing values of the data set attribute with the mode common occurring entry in the column. | MostFrequentEntry = df['attribute_name'].value_counts().idxmax() 
df['attribute_name'].replace(np.nan,MostFrequentEntry,>df['attribute_name'].replace(np.nan,MostFrequentEntry, inplace=True) |