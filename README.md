# Node Farm

A simple Node.js HTTP server application that displays a dynamic farm product catalog.

## Features

- Product overview page with all items
- Individual product detail pages
- Dynamic HTML templating
- JSON-based product data
- Responsive design

## Tech Stack

- Node.js
- JavaScript
- HTML/CSS

## Installation

```bash
npm install
```

## Usage

```bash
npm start
```

Visit `http://localhost:8000` in your browser.

## Routes

- `/` - View all products
- `/product/:id` - View product details

## Project Structure

```
├── index.js              # Main server
├── package.json          # Dependencies
├── dev-data/data.json    # Product data
├── modules/              # Utility modules
└── templates/            # HTML templates
```
