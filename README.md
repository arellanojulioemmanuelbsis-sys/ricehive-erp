# RiceHive Inventory ERP

A responsive, browser-based inventory ERP prototype for Honeybee Ricemill. The interface follows the screens and visual style in the project proposal PDF.

## Run locally

Open `index.html` in a modern web browser. No build step or dependencies are required.

## Deploy to Vercel

This is a static site. Import the GitHub repository into Vercel and use these settings:

- Framework preset: **Other**
- Build command: leave blank
- Output directory: `.`
- Install command: leave blank

The included `vercel.json` keeps clean URL handling enabled.

## Demo behavior

- Demo records are saved in the current browser's local storage.
- Demo login accepts any valid email and non-empty password.
- This prototype has no server, shared database, or real authentication. Do not use it for production inventory or credentials.

## Included screens

- Dashboard and low-stock overview
- Inventory list and product creation
- Goods receipt and quantity discrepancy recording
- Stock releases with availability validation
- Supplier directory
- Inventory report and CSV export
- Purchase order, warehouse, stock adjustment, and settings views
