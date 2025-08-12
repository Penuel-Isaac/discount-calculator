markdown
Discount Calculator (Python)

This project contains a simple Python program that calculates the final price of an item after applying a discount. It uses a user-defined function to handle the discount logic.

🔧 Functionality

- Prompts the user to input:
  - Original price of the item
  - Discount percentage
- Applies the discount *only if* it is *20% or higher*
- Returns the final price or the original price if the discount is below 20%

🧠 Function Definition

python
def calculate_discount(price, discount_percent):


Parameters:
- `price` (float): The original price of the item
- `discount_percent` (float): The discount percentage to be applied

📥 Input Example

Enter the original price: 100
Enter the discount percentage: 25


📤 Output Example

Discount applied! Final price: $75.00


📌 Requirements
- Python 3.x

✅ How to Run
1. Clone or download the repository
2. Run the script using a terminal or Python IDE:

python discount_calculator.py
