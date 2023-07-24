# Tip Calculator - Mini Project #4

This mini-project is a simple HTML file that includes a JavaScript function for calculating tips. The provided function takes in the total bill amount and the desired tip percentage as inputs and returns either the total bill amount with the tip included or just the tip amount based on the user's preference.

## Getting Started

To use this tip calculator, you can open the provided HTML file named `index.html` in your web browser. No additional setup or installation is required.

## How to Use

1. Open the `index.html` file in your web browser.

2. The web page will display the heading "Mini Project #4: Tip Calculator."

3. The JavaScript function `tip()` is defined within the `<script>` tag of the HTML file.

4. The `tip()` function takes three arguments:

   - `totalAmount` (required): The total bill amount.
   - `tip` (optional): The desired tip percentage. The default value is 10 if not provided.
   - `returnTipOnly` (optional): A boolean value to control whether the function returns only the tip amount. The default value is false if not provided.

5. The function calculates the tip amount based on the given percentage and adds it to the total bill amount to get the new total if `returnTipOnly` is false. Otherwise, it returns only the tip amount.

6. The calculated results are printed to the browser console using `console.log()`.

7. In the example provided in the code, the function is called twice:
   - The first call calculates the total bill amount with a 10% tip (default value).
   - The second call calculates and returns only the tip amount for a 10% tip.

## Customization

You can modify the `tip()` function calls to calculate tips for different bill amounts and tip percentages. Feel free to experiment with different inputs to see how the function performs.
