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
- Demo users can create an account and log in on the same browser; accounts are stored in local storage.
- This prototype has no server, shared database, or secure authentication. Accounts do not sync between collaborators or devices, and passwords are not protected for production use.

## Included screens

- Dashboard and low-stock overview
- Inventory list and product creation
- Goods receipt and quantity discrepancy recording
- Stock releases with availability validation
- Supplier directory
- Inventory report and CSV export
- Purchase order, warehouse, stock adjustment, and settings views
