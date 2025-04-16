# DeliPizza
DeliPizza is a web application built with ASP.NET that provides an online ordering system for a pizza delivery business. It features user authentication, food catalog browsing by category, order placement, and an admin dashboard for user management and sales reporting.

## Features

- **User Authentication**: Secure login and registration system with role-based access
- **Food Catalog**: Browse different food categories with detailed product information
- **Shopping Cart**: Add items to cart and manage orders
- **Admin Dashboard**: Comprehensive sales reports and user management
- **Responsive Design**: Clean and intuitive UI for both customers and administrators

## Tech Stack

- **Frontend**: ASP.NET Web Forms, HTML, CSS
- **Backend**: C# (.NET Framework 4.7.2)
- **Database**: SQL Server (LocalDB)
- **Authentication**: Custom implementation with PBKDF2 password hashing

## Project Structure

- `Default.aspx` - Homepage with food catalog
- `LogIn.aspx` & `SignUp.aspx` - User authentication pages
- `WebPizzaForm.aspx` - Order placement form
- `Admin.aspx` - Administrator dashboard with sales reports
- `UserControls` - Reusable UI components
- `Style` - CSS stylesheets
- `ImagesPizza` - Product images

## Database Schema

The application uses several key tables:
- `UserAccounts` - Stores user credentials and roles
- `FoodCategories` - Food category information
- `Items` - Product details including prices and images
- `Sales` - Order information and status

## Getting Started

### Prerequisites

- Visual Studio 2019 or later
- .NET Framework 4.7.2
- SQL Server LocalDB

### Installation

1. Clone the repository
```
git clone https://github.com/yourusername/DeliPizza.git
```

2. Open the solution file `DeliPizza.sln` in Visual Studio

3. Build the solution to restore NuGet packages

4. The database file is included in the `App_Data` folder and will be automatically attached

5. Start the application (F5 or Debug > Start Debugging)

