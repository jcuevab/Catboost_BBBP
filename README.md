df1 = pd.read_csv('df_padel_part1.csv')
df2 = pd.read_csv('df_padel_part2.csv')
df3 = pd.read_csv('df_padel_part3.csv')

# Join the three parts into one dataframe
df_combined = pd.concat([df1, df2, df3], ignore_index=True)

# Display the combined dataframe
print("Combined DataFrame:")
print(df_combined)
print("\nShape of combined DataFrame:", df_combined.shape)

# You can also verify if the combined dataframe is identical to the original df_padel
# if df_combined.equals(df_padel):
#     print("\nCombined dataframe is identical to the original df_padel.")
# else:
#     print("\nCombined dataframe is NOT identical to the original df_padel.")
