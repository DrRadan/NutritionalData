# NutritionalData

Goal: to extract nutritional information for any branded food product from the USDA database and at the same time use the Wal-mart product classification to extract nutritional information of all similar products. Visualize the comparison

1. Search the USDA DB for product
2. Extract the product's unique USDA ID from the search results
3. Use the product's unique ID to extract nutritional information
4. Search the Wal-mart DB for the product
5. Extract the lowest level category the product belongs to
6. Extract all products in the wal-mart DB that belong to this lowest category
7. Some filter for irrelevant data
8. Repeat 1-3 for each of the extracted products
10. Visualise the results (histograms?)