

# Stock-Billing system Overview
This script is designed to manage SKU numbers, product names, prices, and quantities efficiently. It consists of two main parts: data entry and product lookup.

## Data Entry:

The script starts by asking the user to input the number of items they wish to add (size).

For each item, the user is prompted to enter a unique SKU number, product name, quantity, and price.

After entering the details for each product, the user is asked whether they want to add more items. If they choose "Y" or "y," the script continues; otherwise, 
it stops data entry.

# Product Lookup:

The script then enters a loop where the user can input an SKU number to retrieve information about a specific product.

If the SKU number exists in the list, the script retrieves and displays the corresponding product name, total cost (calculated as quantity multiplied by price), quantity, and single price.

If the SKU number is not found, the script prompts the user to enter a valid SKU number. This process continues until a valid SKU number is entered.

# Key Features:
Interactive User Input: The script interacts with the user to gather product details and validate SKU numbers.

# Data Storage: 
Product details, including SKU numbers, names, quantities, and prices, are stored in separate lists for easy access and management.

# Error Handling:
The script handles invalid SKU number inputs by prompting the user to enter a valid number, ensuring accurate data retrieval.

# Calculation of Total Cost:
The script calculates and displays the total cost based on the quantity and price of the product.

# Benefits:
This script is a simple yet effective way to manage product inventory, allowing users to input and retrieve product details based on SKU numbers.

The interactive nature of the script ensures that users can easily manage and access their inventory without the need for complex software.
