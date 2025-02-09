**Frequently Bought Together Recommendation System**

**Overview**

This project implements a 'Frequently Bought Together' recommendation system for a drug store using Apriori and FP-Growth algorithms. The goal is to identify patterns in customer transactions and recommend products that are often purchased together.

**Features**

• Loads transaction data from SKU_DATA.csv. (This is a synthetic dataset).

• Processes the data into a transactional format for mining.

• Uses Apriori Algorithm to find frequent itemsets and generate association rules.

• Uses FP-Growth Algorithm for faster frequent pattern mining.

• Extracts association rules (e.g., "If a customer buys aspirin, they are likely to buy bandages").

• Saves the recommendations to CSV files for further analysis.

**Technologies Used**

• Python

• Pandas for data manipulation

• NumPy for numerical operations

• MLxtend for Apriori, FP-Growth, and association rule mining

**Dataset**

The dataset has following columns:

• Customer_ID – Unique identifier for customers

• Order_ID – Unique identifier for orders

• SKU_ID – Stock Keeping Unit ID

• Product_Name – Name of the product

• Quantity – Number of items purchased

• Price – Price of the product

**Future Enhancements**

• Implementing a real-time recommendation engine.

• Integration with an e-commerce platform.

• Visualization of frequent patterns using network graphs.

**License**

This project is open-source and available under the MIT License.

**Author**

Developed by Dr. Amir Manzoor
