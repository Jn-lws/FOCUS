# C$50 FINANCE APP
#### Video Demo:  <URL HERE>
#### Description: C$50 Finance
C$50 Finance is a Flask web application for managing a simulated stock portfolio. Users can create an account, check stock quotes, buy and sell shares, review their transaction history, and change their password. The application tracks each user's cash balance and calculates the current value of their holdings using stock quote data.
Features
- User accounts: Register, log in, and log out.
- Password security: Passwords are stored as hashes, and users can change their password after confirming their current password.
- Stock quotes: Look up a stock by its ticker symbol.
- Buy shares: Purchase a positive number of shares when the account has enough cash.
- Sell shares: Sell shares the user owns, without selling more than the available quantity.
- Portfolio overview: View holdings, share counts, current prices, total holding values, remaining cash, and the portfolio's combined value.
- Transaction history: Review purchases and sales, including the symbol, number of shares, price per share, and timestamp.
- Input validation: Invalid symbols, missing fields, mismatched passwords, invalid share amounts, and insufficient funds are rejected with an error page.
Built With
- Python
- Flask
- CS50 SQL
- Flask-Session
- SQLite
- Requests
- Jinja templates
- HTML and CSS
- Bootstrap 5.3
