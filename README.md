# Ebook Storefront Theme

A modern, professional Shopify theme specifically designed for selling ebooks and digital books.

## Features

### 🎨 Design
- Modern, clean interface optimized for showcasing ebook covers
- Luxurious red color scheme with smooth animations
- Fully responsive design for all devices
- Book-focused card layouts with format badges

### 📚 Ebook-Specific Features
- Display multiple file formats (PDF, EPUB, MOBI)
- Show book details (pages, file size, language)
- Sample chapter links support
- Author information display
- Rating display support
- Instant download messaging

### 🛍️ Shopping Experience
- Intuitive product browsing by category
- Advanced filtering and sorting
- Quick add-to-cart from product cards
- Streamlined checkout process
- Shopping cart with format indicators

### 📱 Templates Included
- `index.liquid` - Homepage with featured ebooks
- `collection.liquid` - Browse ebooks by collection
- `product.liquid` - Individual ebook details page
- `cart.liquid` - Shopping cart page

### 🧩 Sections
- `header.liquid` - Navigation with search and cart
- `hero-banner.liquid` - Homepage hero section
- `footer.liquid` - Footer with links and newsletter

### 🎯 Snippets
- `ebook-card.liquid` - Reusable ebook card component

## Theme Structure

```
theme/
├── assets/
│   └── extravagant-enterprise.css  # Main stylesheet
├── layout/
│   └── theme.liquid                # Main layout template
├── templates/
│   ├── index.liquid                # Homepage
│   ├── collection.liquid           # Collection listing
│   ├── product.liquid              # Product details
│   └── cart.liquid                 # Shopping cart
├── sections/
│   ├── header.liquid               # Site header
│   ├── hero-banner.liquid          # Hero banner
│   └── footer.liquid               # Site footer
├── snippets/
│   └── ebook-card.liquid           # Product card
└── config/
    └── settings_schema.json        # Theme configuration
```

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

### Metafields Support
The theme supports the following custom metafields for products:

- `custom.pages` - Number of pages in the ebook
- `custom.file_size` - File size (e.g., "5.2 MB")
- `custom.language` - Language of the ebook
- `custom.rating` - Rating out of 5
- `custom.sample_link` - URL to sample chapter

## Installation

1. Upload the theme to your Shopify store
2. Activate the theme from the Shopify admin
3. Configure your collections and products
4. Add ebook covers as product images
5. Set up metafields for additional ebook details

## Best Practices

### Product Setup
1. Use high-quality book cover images (recommended: 800x1200px)
2. Add author name in the "Vendor" field
3. Use collections to organize by genre or category
4. Add tags for better filtering
5. Write compelling descriptions

### Collections
- Create collections like "Bestsellers", "New Releases", "Fiction", "Non-Fiction"
- Use clear, descriptive collection titles
- Add collection descriptions

### Navigation
- Keep main navigation simple and clear
- Use dropdown menus for subcategories
- Make search easily accessible

## Support

For support and updates, visit the [GitHub repository](https://github.com/10300507/theme).

## License

This theme is proprietary software developed for Extravagant Enterprises LLC.

---

**Version:** 1.0.0  
**Last Updated:** 2025  
**Designed for:** Digital Book Sales
