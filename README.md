# Inventory Management System

A modern, responsive web-based inventory management system built with HTML, CSS, JavaScript, and Bootstrap. This system helps businesses track products, manage suppliers, and monitor stock levels with an intuitive dashboard interface.

## Features

### 📊 Dashboard
- **Real-time Statistics**: View total products, stock levels, low stock alerts, and supplier count
- **Smart Alerts**: Automatic notifications for out-of-stock and low-stock products
- **Visual Indicators**: Color-coded cards and status badges for quick assessment

### 📦 Product Management
- **Complete Product Tracking**: Manage product details including name, category, stock, price, and minimum stock levels
- **Stock Status Monitoring**: Visual indicators for normal, low, and out-of-stock items
- **Category Organization**: Pre-defined categories (Electronics, Clothing, Food, Books, Home, Other)
- **Supplier Association**: Link products to their respective suppliers

### 🚚 Supplier Management
- **Comprehensive Supplier Database**: Store supplier information including contact details and addresses
- **Relationship Tracking**: View which suppliers provide which products
- **Data Integrity**: Prevent deletion of suppliers that have associated products

## Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Framework**: Bootstrap 5.3.0
- **Icons**: Font Awesome 6.4.0
- **Storage**: In-memory storage (for demonstration)
- **Responsive Design**: Mobile-first approach

## Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No server setup required - runs entirely in the browser

### Installation
1. Clone or download the project files
2. Open `index.html` in your web browser
3. Start managing your inventory immediately!

### Sample Data
The system comes pre-loaded with sample data:
- **Products**: Laptop, T-Shirt, Coffee Beans, Python Book
- **Suppliers**: Tech Solutions Inc, Fashion Hub, Food Distributors

## Usage Guide

### Navigation
Use the top navigation bar to switch between sections:
- **Dashboard**: Overview of your inventory status
- **Products**: Manage your product catalog
- **Suppliers**: Manage supplier information

### Adding Products
1. Navigate to the Products section
2. Click "Add Product" button
3. Fill in the product details:
   - Product name
   - Category
   - Stock quantity
   - Price
   - Minimum stock level
   - Associated supplier
4. Click "Save Product"

### Managing Stock Levels
- Products are automatically flagged when stock falls below minimum levels
- Color coding helps identify stock status:
  - **Red**: Out of stock
  - **Yellow**: Low stock
  - **Normal**: Adequate stock

### Adding Suppliers
1. Navigate to the Suppliers section
2. Click "Add Supplier" button
3. Enter supplier details:
   - Company name
   - Contact person
   - Email and phone
   - Address
4. Click "Save Supplier"

## File Structure

```
inventory-management-system/
├── index.html              # Main application file
├── README.md              # This file
└── assets/                # External dependencies loaded via CDN
    ├── Bootstrap 5.3.0    # CSS framework
    └── Font Awesome 6.4.0 # Icon library
```

## Key Functions

### Core Functions
- `showDashboard()` - Display dashboard with statistics
- `showProducts()` - Navigate to products section
- `showSuppliers()` - Navigate to suppliers section
- `loadDashboard()` - Update dashboard statistics
- `saveProduct()` - Add/edit product information
- `saveSupplier()` - Add/edit supplier information

### Data Management
- `products[]` - Array storing product data
- `suppliers[]` - Array storing supplier data
- In-memory storage with persistence during browser session

## Customization Options

### Adding New Categories
Modify the category dropdown in the product modal:
```html
<option value="YourCategory">Your Category</option>
```

### Styling Customization
The system uses CSS custom properties and Bootstrap classes. Key styling areas:
- Gradient colors for navbar and buttons
- Card hover effects
- Alert styling for stock warnings

### Extending Functionality
The modular JavaScript structure makes it easy to:
- Add new data fields
- Implement data persistence (localStorage/database)
- Add reporting features
- Integrate with external APIs

## Browser Compatibility

- ✅ Chrome 60+
- ✅ Firefox 60+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## Limitations

- **Data Persistence**: Data is stored in memory and will be lost on page refresh
- **Multi-user**: Single-user system, no authentication or multi-user support
- **Reporting**: Basic statistics only, no advanced reporting features
- **Import/Export**: No data import/export functionality

## Future Enhancements

- [ ] Database integration for data persistence
- [ ] User authentication and authorization
- [ ] Advanced reporting and analytics
- [ ] Barcode scanning support
- [ ] Print functionality for reports
- [ ] Data import/export (CSV, Excel)
- [ ] Multi-location inventory tracking
- [ ] Purchase order management
- [ ] Low stock automatic reordering

## Contributing

This is a demonstration project. To contribute:
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

For questions or issues:
- Check the code comments for implementation details
- Review the browser console for any JavaScript errors
- Ensure all CDN resources are loading properly

---

**Note**: This system uses in-memory storage for demonstration purposes. For production use, implement proper database storage and user authentication.
