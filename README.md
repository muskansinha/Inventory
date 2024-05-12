# Inventory Data Management Script

## Description
This Python script, `inventory.py`, is designed for managing and analyzing inventory data specifically for a retail garden supply store. The script performs operations such as reading inventory data, filtering items based on criteria, calculating stock statuses, total values, and generating full descriptions for items.

## Key Features
- **Data Loading**: Loads inventory data from a CSV file.
- **Data Segmentation**: Extracts inventory details for specific locations and conditions.
- **Stock Status Calculation**: Computes a Boolean status indicating whether items are in stock.
- **Value Calculation**: Calculates the total value of each item in the inventory based on its price and quantity.
- **Descriptive Label Generation**: Creates a descriptive label for each item by combining product type and description.

## Installation

### Prerequisites
Ensure you have Python installed on your system along with Pandas, a powerful data manipulation library. This script is compatible with Python 3.x.

### Required Libraries
- `pandas`: For data manipulation and analysis.

You can install Pandas using pip if you haven't installed it yet:

```bash
pip install pandas
```

## Usage
1. Ensure your inventory data is in a CSV file named `inventory.csv` located in the same directory as the script. The CSV file should have columns labeled `location`, `product_type`, `product_description`, `quantity`, and `price`.
2. Run the script with the following command:
   ```bash
   python inventory.py
   ```

### Example Data Format
Your CSV should include the following columns:
- **location**: The location of the inventory.
- **product_type**: Type of product (e.g., seed, tool).
- **product_description**: Description of the product.
- **quantity**: Available quantity of the product.
- **price**: Price per unit of the product.

## Output
The script will print the modified inventory DataFrame to the console, which includes:
- Calculations of stock status (`in_stock`).
- Total value of each item (`total_value`).
- A combined description (`full_description`).

## Contributing
Contributions to this project are welcome! Please fork the repository, make your changes, and submit a pull request.

## License
This script is released under the MIT License. Details can be found in the LICENSE file.
