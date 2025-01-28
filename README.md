# Cleaning & Standardizing Customer Data with Pandas

- Utilized Pandas to clean and standardize a dataset with 1,020 customer records, ensuring consistency and usability.

- Removed duplicate rows using drop_duplicates() to eliminate redundant data entries.

- Dropped irrelevant columns such as Not Useful to focus on actionable insights.

- Standardized inconsistent Last Name entries by removing unwanted characters (slashes, dots, underscores) using .str.replace().

- Formatted and cleaned Phone Number column by removing non-numeric characters with regex and applying a consistent 123-456-7890 format.

- Split Address column into Street Address, State, and Zip Code for improved data clarity and usability.

- Standardized categorical columns like Paying Customer and Do Not Contact to uniform values ("Yes"/"No").

- Removed rows with Do Not Contact = "Yes" or blank Phone Number values to ensure data relevance.

- Replaced all missing values with blank strings using fillna() for consistent handling of null entries.

- Reset the DataFrame’s index using reset_index() to maintain clean row references after transformations.
