# GRV Financing Calculator

This is a simple web-based calculator that helps compute the full down payment, loan amount, and monthly payment for financing a vacation club membership. The calculations are based on user inputs and a fixed interest rate and loan term.

## Features
- **Inputs**:
  - Sales Price: The total cost of the vacation club membership.
  - Down Payment Percentage: The percentage of the net sales price used for the down payment.
- **Outputs**:
  - Full Down Payment (Rounded to the nearest $100).
  - Loan Amount after subtracting the down payment.
  - Monthly Payment calculated with a fixed APR of 17.9% and a 48-month term.

## Formula Details
1. **Net Sales Price** = `Sales Price - $355 (Fee)`
2. **Net Down Payment** = `Net Sales Price × Down Payment Percentage`
3. **Full Down Payment (Rounded)** = `Net Down Payment + $355, rounded up to the nearest $100`
4. **Loan Amount** = `Sales Price - Full Down Payment`
5. **Monthly Payment** is calculated using the loan amortization formula:

## How to Use
1. Open the `index.html` file in any modern web browser.
2. Enter the **Sales Price** and **Down Payment Percentage** in the input fields.
3. Click the **Calculate** button.
4. The results will display:
- Full Down Payment (Rounded)
- Loan Amount
- Monthly Payment

## Technology Used
- **HTML**: For structure and layout.
- **CSS**: For styling.
- **JavaScript**: For calculations and interactivity.

## Hosting
You can host this project on any static website hosting platform. For free hosting, consider:
- [GitHub Pages](https://pages.github.com)
- [Netlify](https://www.netlify.com)
- [Vercel](https://vercel.com)

### Steps for GitHub Pages Hosting
1. Create a new repository on GitHub.
2. Upload the `index.html` file to the repository.
3. Go to **Settings** > **Pages**.
4. Select the branch and root folder (`/`).
5. GitHub will generate a public URL for your calculator.

## Example Use Case
- **Sales Price**: $10,000
- **Down Payment Percentage**: 20%
- **Results**:
- Full Down Payment: $2,300
- Loan Amount: $7,700
- Monthly Payment: $236.56

## Future Enhancements
- Add more customization for loan term or interest rate.
- Make the UI more dynamic and mobile-friendly.
- Include support for different currencies.

## License
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

---

### Author
Created by [Steven Shields. Feel free to contribute or suggest enhancements!
