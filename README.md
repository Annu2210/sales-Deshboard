# 📊 Sales Dashboard

A professional-grade, fully interactive sales dashboard with real-time data visualization and filtering capabilities.

## ✨ Features

### 🎯 Interactive Filters
- **City Filter** - Filter data by Mumbai, Delhi, Bangalore, Chennai, or Hyderabad
- **Month Filter** - Select specific months (Jan-Dec)
- **Product Filter** - Choose from Laptop, Mobile, Tablet, Headphones, Monitor
- **Payment Mode Filter** - Filter by Online or Offline payments
- **Reset All Button** - Clear all filters with one click

### 📈 KPI Cards (Top Section)
- **Total Revenue** - Overall revenue across all transactions
- **Online Payment Revenue** - Revenue from online transactions
- **Offline Payment Revenue** - Revenue from offline transactions
- **Total Orders** - Complete order count

### 📊 Dynamic Charts
1. **Revenue by Month** - Line chart showing monthly revenue trends
2. **Revenue by Product** - Horizontal bar chart of product-wise revenue
3. **Payment Mode Distribution** - Donut chart (Online vs Offline)
4. **Revenue by City** - Bar chart showing city-wise performance

### 🏆 Performance Sections
- **Top 3 Selling Products** - Horizontal bar chart with revenue values
- **Top 3 Sellers** - Leaderboard style with medal rankings (Gold, Silver, Bronze)

## 🎨 Design Features

### Visual Elements
- **Dark Background** - Professional black gradient background with purple and navy tones
- **Colorful Cards** - Vibrant gradient cards with hover effects
- **Modern Layout** - Clean, responsive grid-based design
- **Smooth Animations** - Transitions and animations for better UX

### Color Palette
- Primary: Cyan Blue (#00d4ff)
- Secondary: Purple (#7b2ff7)
- Accents: Hot Pink (#ff006e), Gold (#ffbe0b), Orange (#fb5607)
- Dark Theme: Black background with transparent glassmorphism cards

## 🚀 How to Use

### 1. Open the Dashboard
- Open `index.html` in any modern web browser
- The dashboard will load with sample data automatically

### 2. Apply Filters
- Select desired filter values from the filter section
- Click "Apply Filters" button to update all charts
- Filters are cumulative - combine multiple filters as needed

### 3. Reset Filters
- Click "Reset All" button to clear all filters and view complete data

### 4. View Metrics
- KPI cards update instantly based on filtered data
- All charts and leaderboards reflect the filtered dataset
- Hover over data points for detailed tooltips

## 📁 Files

- **index.html** - Main dashboard application
- **sales_data.csv** - Sample sales data (can be replaced with your own)
- **README.md** - Documentation

## 📊 Data Format

The dashboard expects a CSV file with the following columns:
- Date (Month)
- City
- Product
- Revenue
- Orders
- PaymentMode
- Seller

## 💡 Customization

### Replace Data
1. Prepare your Excel data in CSV format
2. Save as `sales_data.csv`
3. Place in the same directory as `index.html`
4. Refresh the browser

### Modify Colors
Edit the `colors` object in the JavaScript section to customize the color scheme.

### Add More Cities/Products
Simply add data to your CSV file - filters will auto-populate!

## 🌐 Browser Compatibility
- Chrome (Latest)
- Firefox (Latest)
- Safari (Latest)
- Edge (Latest)

## 📦 Dependencies
- Chart.js 3.9.1 (for charts)
- PapaParse 5.4.1 (for CSV parsing)
- All served via CDN - no installation needed!

## 🎯 Key Highlights
✅ Fully responsive design  
✅ Real-time data filtering  
✅ Professional styling  
✅ No external dependencies to install  
✅ Sample data included  
✅ Easy to customize  
✅ Mobile-friendly  

---

**Created for Professional Sales Analytics** 📈
