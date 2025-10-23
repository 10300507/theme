# Ecommerce Storefront Theme

A modern, professional Shopify theme designed for selling both digital products (ebooks, courses, software) and physical products with advanced user management features.

## Features

### 🎨 Design
- Modern, clean interface optimized for showcasing products
- Luxurious red color scheme with smooth animations
- Fully responsive design for all devices
- Product-focused card layouts with badges and indicators

### 🛒 Ecommerce Features
- **Digital Products**: Support for ebooks, audiobooks, courses, software
- **Physical Products**: Full support for traditional ecommerce items
- Product type indicators (Digital vs Physical badges)
- Multiple file format display (PDF, EPUB, MOBI)
- Stock status indicators
- Free shipping badges
- Quick add-to-cart from product cards

### 👤 User Profile & Account Management
- **User Dashboard**: Personalized welcome with order statistics
- **Profile Dropdown**: Quick access to account, orders, addresses
- **Account Page**: Complete profile management with sidebar navigation
- **Order History**: View and track all orders
- **Address Management**: Save and manage shipping addresses
- **Loyalty Points**: Track rewards and total spending

### ⚙️ Settings & Preferences
- **Display Settings**: Grid/List view toggle, items per page
- **Shopping Preferences**: Currency display, email notifications
- **Content Filters**: Show all products, digital only, or physical only
- **Persistent Storage**: Settings saved in browser localStorage

### 📱 Enhanced Navigation
- **Mega Menu**: Multi-column dropdown with featured items
- **Quick Search**: Overlay search with instant access
- **Category Browsing**: Organized by product type and genre
- **Mobile Optimized**: Responsive menu for all devices

### 📚 Homepage Enhancements
- **User Dashboard Preview**: Quick stats for logged-in users
- **Featured Categories Showcase**: Visual category browser
- **Product Type Tabs**: Filter by all, digital, or physical products
- **Benefits Section**: Highlight store advantages

### 🛍️ Shopping Experience
- Intuitive product browsing by category
- Advanced filtering and sorting
- Streamlined checkout process
- Shopping cart with format indicators
- Instant download messaging for digital products

### 📱 Templates Included
- `index.liquid` - Homepage with featured products and user dashboard
- `collection.liquid` - Browse products by collection
- `product.liquid` - Individual product details page
- `cart.liquid` - Shopping cart page
- `customers/account.liquid` - User profile and dashboard
- Additional templates: search, 404, page, list-collections

### 🧩 Sections
- `header.liquid` - Enhanced navigation with account dropdown and mega menu
- `hero-banner.liquid` - Homepage hero section with customizable text
- `footer.liquid` - Footer with links and newsletter

### 🎯 Snippets
- `ebook-card.liquid` - Reusable product card component (supports all product types)

## Theme Structure

```
theme/
├── assets/
│   └── extravagant-enterprise.css  # Main stylesheet (2400+ lines)
├── layout/
│   └── theme.liquid                # Main layout template
├── templates/
│   ├── index.liquid                # Homepage
│   ├── collection.liquid           # Collection listing
│   ├── product.liquid              # Product details
│   ├── cart.liquid                 # Shopping cart
│   └── customers/
│       └── account.liquid          # User account page
├── sections/
│   ├── header.liquid               # Site header with dropdown
│   ├── hero-banner.liquid          # Hero banner
│   └── footer.liquid               # Site footer
├── snippets/
│   └── ebook-card.liquid           # Product card
└── config/
    └── settings_schema.json        # Theme configuration
```

## New Features Added

### User Account Features
- Profile avatar with user initials
- Order statistics dashboard
- Loyalty points tracking
- Quick access dropdown menu
- Comprehensive account page

### Settings Modal
- Display preferences (view type, items per page)
- Shopping preferences (currency, notifications)
- Content filtering options
- Save/reset functionality with localStorage

### Enhanced Navigation
- Mega menu with 4-column layout
- Separate digital and physical product sections
- Featured items showcase
- Smooth hover animations

### Product Features
- Digital/Physical product badges
- Stock status indicators
- Shipping information
- Enhanced metadata display
- Format badges for digital products

## Customization

### Colors
The theme uses CSS variables for easy color customization. Edit these in `extravagant-enterprise.css`:

```css
:root {
  --enterprise-red: #dc143c;
  --enterprise-dark-red: #8b0000;
  --enterprise-accent: #ff4500;
  --enterprise-gold: #ffd700;
  --enterprise-white: #ffffff;
  --enterprise-black: #000000;
}
```

### Product Types
To mark products as digital, add one of these tags:
- `digital`
- `ebook`
- `download`

Physical products will be automatically detected if they don't have these tags.

### Metafields Support
The theme supports the following custom metafields for products:

- `custom.pages` - Number of pages (for books)
- `custom.file_size` - File size (e.g., "5.2 MB")
- `custom.language` - Language of the product
- `custom.rating` - Rating out of 5
- `custom.sample_link` - URL to sample chapter/preview

## Installation

1. Upload the theme to your Shopify store
2. Activate the theme from the Shopify admin
3. Configure your collections and products
4. Add product images (recommended: 800x1200px for books)
5. Set up metafields for additional product details
6. Configure navigation and mega menu categories

## Best Practices

### Product Setup
1. Use high-quality product images
2. Add vendor name for products
3. Use collections to organize by type and category
4. Add appropriate tags (including 'digital' for digital products)
5. Write compelling descriptions

### Collections
- Create collections like "Bestsellers", "New Releases", "Featured"
- Organize by product type: "Ebooks", "Physical Books", "Courses"
- Use clear, descriptive collection titles
- Add collection descriptions and images

### Navigation
- Keep main navigation simple and clear
- Use mega menu for detailed categorization
- Make search easily accessible
- Ensure mobile menu is easy to use

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Support

For support and updates, visit the [GitHub repository](https://github.com/10300507/theme).

## License

This theme is proprietary software developed for Extravagant Enterprises LLC.

---

**Version:** 2.0.0  
**Last Updated:** 2025  
**Designed for:** Digital and Physical Product Sales
