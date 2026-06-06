# Cashly
A modern self-hosted personal finance management platform featuring Material You design, advanced analytics, recurring transactions, receipt management, and multi-user support.
✨ Overview

FinanceTracker v4 is a powerful financial management application designed to help individuals and families track income, expenses, budgets, and financial trends through a clean, modern interface.

Built for self-hosting environments such as Synology NAS, home servers, Docker hosts, and Raspberry Pi systems, FinanceTracker keeps all financial data under your control without relying on external cloud services.

🎨 User Interface
Dashboard

The dashboard provides a complete financial overview at a glance:

Current balance
Monthly income
Monthly expenses
Net savings
Spending breakdown by category
Financial trends and history

Categories

Create and customize financial categories to match your needs.

Examples:

🍔 Food & Dining
🏠 Housing
🚗 Transportation
🎬 Entertainment
💊 Healthcare
🎓 Education
💼 Income

Each category supports:

Custom icons
Colors
Images
Favorites
Income/Expense assignment
Merchants

Organize recurring spending by linking transactions to merchants.

Examples:

Amazon
Netflix
Spotify
Local Supermarkets
Utility Providers
Insurance Companies

Merchant profiles can include:

Name
Logo
Image
Default category
Favorite status
Settings
┌──────────────────────────────────────────────┐
│ 🎨 Appearance & Themes                       │
│ 👤 User Management                           │
│ 💾 Backup & Restore                          │
│ 🐳 Docker Information                        │
│ 🔒 Security Settings                         │
└──────────────────────────────────────────────┘
🚀 Core Features
💰 Income & Expense Tracking

Record and manage:

Income
Expenses
Transfers
One-time transactions
Custom notes and descriptions

Every transaction includes:

Amount
Category
Merchant
Date
Receipt attachment
Additional notes
🔄 Recurring Transactions

Automate recurring financial activities.

Perfect for:

Rent
Utilities
Streaming subscriptions
Insurance
Salary payments
Savings plans
Loan repayments

Supported schedules:

Daily
Weekly
Monthly
Yearly
📸 Receipt Management

Attach receipts and invoices directly to transactions.

Supported formats:

JPG
PNG
WEBP
HEIC

Benefits:

Centralized document storage
Easy retrieval
Improved financial auditing
Paperless bookkeeping
📊 Analytics & Reporting

Gain deeper insights into your finances through interactive visualizations.

Financial Overview

Track:

Total income
Total expenses
Current balance
Savings rate
Interactive Charts
Income vs Expenses

Compare earnings and spending over time.

Available periods:

Weekly
Monthly
Yearly
Category Distribution

Visualize spending patterns using donut and pie charts.

Financial Trends

Analyze long-term financial behavior and identify opportunities for improvement.

🏷 Category Management

Fully customizable category system.

Features:

Unlimited categories
Custom colors
Icons and emojis
Images
Favorite categories
Income or expense classification
🏪 Merchant Management

Create reusable merchant profiles for frequently used businesses.

Features:

Merchant logos
Custom images
Default categories
Quick transaction assignment
Favorite merchants
🔍 Advanced Search & Filtering

Quickly locate any transaction.

Filter by:

Text search
Date range
Income
Expenses
Categories
Merchants

Designed to scale efficiently even with large datasets.

👥 Multi-User Support

Built-in user authentication and account management.

Administrator

Can:

Manage users
Configure system settings
Access backups
Perform maintenance tasks
User

Can:

Manage personal financial records
Create transactions
Access analytics
💾 Backup & Restore

Protect your financial data with built-in backup tools.

Export

Includes:

Transactions
Categories
Merchants
Application settings

Export format:

JSON
Restore

Restore complete application state in seconds.

Ideal for:

Migrations
Disaster recovery
Device replacement
Scheduled backups
🎨 Material You Design

FinanceTracker v4 follows modern Material Design 3 (Material You) principles.

Highlights:

Light Mode
Dark Mode
Dynamic color themes
Responsive layouts
Smooth animations
Mobile-first experience
Card-based interface
📱 Responsive Experience

Optimized for:

Smartphones
Tablets
Desktop computers
Synology NAS browsers
Touchscreen devices

Enjoy a seamless experience across all screen sizes.

🏗 Architecture
Frontend
React 18
Vite
Zustand
React Router
Recharts
date-fns
Backend
Node.js
Express
Better-SQLite3
Multer
UUID
Database
SQLite
WAL Mode enabled
No external database required
🐳 Docker Ready

FinanceTracker v4 includes everything needed for containerized deployment.

Quick Start
docker compose up -d --build
Included
Dockerfile
Docker Compose configuration
Persistent data volumes
Automatic database initialization
🔒 Privacy First

Your financial data remains entirely under your control.

No cloud dependency
No third-party analytics
No tracking services
Local data storage only

Perfect for:

Privacy-conscious users
Home labs
Synology NAS deployments
Self-hosted environments
✅ Feature Highlights
Income & expense tracking
Recurring transactions
Interactive dashboards
Financial analytics
Receipt management
Category management
Merchant management
Advanced filtering & search
Multi-user support
Role-based permissions
Backup & restore
Material You design
Dark mode
Mobile responsive interface
SQLite database
Docker deployment
Synology NAS compatible
🎯 Who Is It For?

FinanceTracker v4 is ideal for:

Individuals
Families
Freelancers
Small households
Home-lab enthusiasts
Self-hosting users
Synology NAS owners
Privacy-focused users

A modern, self-hosted alternative to spreadsheets and cloud-based budgeting tools, designed to give you complete control over your financial data.
