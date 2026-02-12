# RetailHub - Point of Sale System

A modern, feature-rich Point of Sale (POS) system built with vanilla HTML, CSS, and JavaScript.

## Features

- **Point of Sale (POS)** - Fast and intuitive checkout process
- **Inventory Management** - Track stock levels, get low stock alerts
- **Customer Management** - Store customer information and purchase history
- **Sales Reports** - View sales statistics, top products, and transaction history
- **Analytics** - Visual charts and graphs for business insights
- **Receipt Printing** - Professional thermal receipt generation
- **Dark/Light Theme** - Toggle between themes
- **Offline Support** - Works offline using IndexedDB

## Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Database**: IndexedDB (browser-based, no server required)
- **Charts**: Chart.js
- **Icons**: Font Awesome
- **Deployment**: Vercel-ready

## Deployment on Vercel

### Option 1: Deploy via Vercel CLI

1. Install Vercel CLI:
   ```bash
   npm install -g vercel
   ```

2. Navigate to project directory and deploy:
   ```bash
   vercel
   ```

3. Follow the prompts to complete deployment

### Option 2: Deploy via GitHub

1. Push this project to a GitHub repository
2. Go to [vercel.com](https://vercel.com)
3. Click "New Project"
4. Import your GitHub repository
5. Click "Deploy"

### Option 3: Drag and Drop

1. Go to [vercel.com](https://vercel.com)
2. Drag the project folder onto the Vercel dashboard

## Local Development

1. Clone or download the project
2. Open `index.html` in a browser, or use a local server:
   ```bash
   npx live-server --port=3000
   ```
   Or:
   ```bash
   npx serve .
   ```

## Project Structure

```
retailhub-pos/
├── index.html      # Main application file (all-in-one)
├── vercel.json     # Vercel configuration
├── package.json    # Project metadata
└── README.md       # Documentation
```

## Usage

1. **Dashboard** - View sales overview, inventory alerts, and recent transactions
2. **POS** - Add items to cart, apply discounts, process payments
3. **Inventory** - Manage products, view stock levels, add new products
4. **Sales Reports** - View detailed sales analytics and export reports
5. **Customers** - Manage customer database
6. **Analytics** - View charts and business insights
7. **Settings** - Configure store settings, tax rates, and preferences

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge

## License

MIT License - feel free to use for personal or commercial projects.

---

Built with ❤️ by RetailHub
