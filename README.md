# Price-Quotation-App
a one-page functional app for price quotation 
## Specifications
1. when the app starts, it should display the Price Quotation page with no subtotal or discount percent and should set the discount amount and total to $0.00
2. if the user enters a valid subtotal and discount percent and clicks the Calculate button, the app should calculate and display the discount amount and total
3. if the user enters invalid data and clicks the Calculate button, the app should display a summary of validation errors above the form
4. valid data requirements:
-> the sales price is required and must be a valid number that's greater than 0
-> the discount percent is required and must be a valid number from 0 to 100
5. if the user clicks the Clear link, the app should reset the form to how it was when the app first started
6. use the MVC pattern. To do that, create a model class that stores the subtotal and discount percent and calculates the discount amount and total. Make sure to bind that model to the Razor view that displays the Price Quotation page shown above
7. use a Razor layout to store the html, head, and body elements
8. use a custom CSS style sheet to style the HTML elements so they appear as shown above
