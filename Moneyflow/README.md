# Finance Manager Application - Page Navigation Guide

## Overview

This is a vanilla HTML/CSS/JavaScript finance management application. All pages are in the `/PAGE` directory.

## Pages & Navigation

### Entry Points

1. **welcome.html** - Landing/home page with features and CTAs
2. **login.html** - User login page
3. **signup.html** - User registration page

### App Pages (After Login)

1. **dashboard.html** - Main dashboard showing overview stats and recent activity
2. **budget.html** - Budget management with category allocation
3. **analytics.html** - Financial analytics and spending breakdown
4. **transacition.html** (Note: filename has typo) - Transaction list with filters
5. **settings.html** - User account settings

## Navigation Structure

### Sidebar Navigation (App Pages)

All app pages (dashboard, budget, analytics, transacition, settings) have a consistent sidebar with these links:

- Dashboard
- Budget
- Analytics
- Transactions
- Settings

## Local Storage Integration

All pages use `localStorage` for data persistence:

- `user_data` - User account information
- `expenses` - Transaction/expense data
- `budgets` - Budget allocations
- `isUserLoggedIn` - Login state

## Responsive Design

- Mobile breakpoint: 768px
- Sidebar toggles to hamburger menu on mobile
- All pages are fully responsive
