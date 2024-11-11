
# International Payment Portal

The **International Payment Portal** is a React-based web application that enables users to perform secure login and manage transactions. The application supports two main user types—employees and customers—with distinct workflows for each.

## Features

- **Employee Login**: Access to transaction management.
- **Customer Login**: Access to the payment processing form.
- **Dynamic Navigation**: Users can navigate between landing, login, transaction, and payment views.
- **Session Management**: The app retains the session-specific view state for a smooth user experience.

## Project Structure

- `App.js`: Main application component that manages view states and navigation.
- `components/EmployeeLoginForm`: Form for employee login.
- `components/LoginForm`: Form for customer login.
- `components/TransactionManagement`: Interface for managing transactions (available post employee login).
- `components/PaymentForm`: Payment processing form (available post customer login).

## Getting Started

### Prerequisites

Ensure Node.js and npm are installed.

### Installation

1. Clone the repository.
   git clone https://github.com/your-repo/International-Payment-Portal.git
   cd International-Payment-Portal
   ```
2. Install dependencies:
   npm install
   ```

### Running the Application

To start the application, use:
cd payment_portal
cd payment_portal
npm install
npm start
```
The app will run on `http://localhost:3000`.

## Usage

1. **Landing Page**: Select either "Employee" or "Customer" login.
2. **Employee Login**: Access the transaction management view.
3. **Customer Login**: Access the payment form for processing payments.

## Component Details

- **App Component**: Central component managing navigation.
- **EmployeeLoginForm**: Contains fields for employee credentials and redirects upon successful login.
- **LoginForm**: Form for customer credentials, with success redirect to the payment form.
- **TransactionManagement**: Manages transaction processes.
- **PaymentForm**: Provides a secure payment interface for customers.

