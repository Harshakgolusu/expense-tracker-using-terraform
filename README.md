# TRACKER - Expense Tracking Application

A simple expense tracking application built with React and Terraform.

## Project Structure

```
TRACKER/
├── frontend/         # React frontend application
├── terraform/        # Infrastructure as Code
└── README.md        # Project documentation
```

## Features

- Track daily expenses
- Categorize expenses
- View expense history
- Generate expense reports

## Prerequisites

- Node.js (v18 or higher)
- Terraform

## Getting Started

1. Clone the repository
2. Set up the development environment:
   ```bash
   cd terraform
   terraform init
   terraform apply
   ```
3. Start the frontend application:
   ```bash
   cd frontend
   npm install
   npm start
   ```

## Infrastructure

The project uses Terraform to manage the following resources:
- Development configuration
- Log directories
- Environment settings

## License

MIT 