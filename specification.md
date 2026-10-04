# Inventory Management Demo - Specification

## 1. Purpose

A lightweight inventory management web application for small teams.

The application is intended to demonstrate a simple replacement for
Excel / CSV-based inventory workflows.

## 2. Target Users

- Small businesses
- Small internal teams
- Users currently managing inventory with spreadsheets

## 3. Core Data

Each inventory item contains:

- Name
- SKU
- Category
- Quantity
- Reorder level
- Storage location
- Created at
- Updated at

## 4. Core Features

- User login
- Inventory list
- Add inventory item
- Edit inventory item
- Delete inventory item
- Search by item name or SKU
- Filter by category
- Update stock quantity
- Highlight low-stock items
- Export inventory data as CSV
- Responsive layout for desktop and mobile

## 5. Main Screens

1. Login
2. Dashboard
3. Inventory List
4. Add / Edit Item

## 6. Definition of Done

The project is complete when:

- Users can log in
- Inventory items can be created, viewed, edited, and deleted
- Search and category filtering work
- Low-stock items are clearly indicated
- Inventory can be exported as CSV
- The UI works on both desktop and mobile
- Secrets are not committed to GitHub
- `.env.example` is included
- Setup instructions are documented in README
- The application can be deployed to a public demo environment