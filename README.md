This README contains a summary of the data quality issues identified in the Electronics Sales dataset, the rules applied for data cleaning, and any assumptions made during the cleaning process before preparing it for analysis.
1. Data Issues Found The following potential data quality issues were detected in the dataset:
* Missing Values: Several records contain missing or blank values for various attributes.
* Inconsistent Formatting: Text fields, particularly product names, categories, and customer details, exhibit inconsistent capitalization and presence of leading/trailing spaces.
* Duplicate Records: Potential duplicate records were observed, which might skew the analysis.
* Date Format Variations: Date values appear in different formats across the dataset.
* Incorrect Data Type: Some numeric fields are incorrectly stored as text types.
* Minor Naming Inconsistencies: Small discrepancies in the spelling or naming conventions for categories and products were found.
2. Data Cleaning Rules Applied The following cleaning actions were performed on the raw data:
* Trimming Whitespace: Leading and trailing whitespace was removed from all text-based columns to standardize string entries.
* Standardizing Case: All text data was converted to a consistent case (e.g., lowercase or proper case) to ensure uniform representation.
* Date Normalization: Dates were converted to a single, uniform date format (e.g., YYYY-MM-DD).
* Type Conversion: Numeric columns stored as text were converted to the appropriate numeric data type (e.g., integer, float).
* Duplicate Removal: Duplicate records were identified and removed, based on a combination of key fields.
* Categorical Unification: Categories and product names with minor variations were consolidated into consistent entries.
* Preservation of Valid Data: No valid data points were discarded unless they were part of a clearly erroneous record or duplicate. All valid observations were retained, with only necessary corrections applied.
3. Assumptions Made During Cleaning The following assumptions guided the data cleaning process:
* Blank Value Handling: Blank values were generally left as they were, unless a reasonable inference could be made based on other data points in the record or the dataset's overall context.
* Correction Ambiguity: Corrections were only made when the intended value was clear and unambiguous. If there was doubt, the original value was preserved.
* Unit Consistency: Currencies, quantities, and measurements were assumed to be recorded in consistent units as specified by the dataset's schema, without any implicit unit conversions required.
* Analysis Suitability: The dataset was considered sufficiently cleaned and accurate for subsequent analytical tasks after the application of the rules outlined above.
Conclusion This document outlines the key data quality concerns, the strategies implemented to address them, and the underlying assumptions during the preparation of the Electronics Sales dataset. The cleaning process ensured a more robust and reliable foundation for analytical work.
4. Members:
Mary Ngure,
Joy Esther Andati,
Callum Pello, 
Collins Ochola and
Charles Gatere.
