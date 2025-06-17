# In colab
# Concatenate the three dataframes back into one
df_combined = pd.concat([df1, df2, df3], ignore_index=True)

# Display the combined dataframe
print("Combined DataFrame:")
df_combined
