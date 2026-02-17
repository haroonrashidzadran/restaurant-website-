# Gourmet Restaurant Website

A modern, professional restaurant website built with HTML, CSS (custom + Bootstrap), and JavaScript. Features a stunning design with smooth animations, reservation system, menu display, and responsive layout.

![Restaurant Preview](https://images.unsplash.com/photo-1414235077428-338989a2e8c0?w=1200&h=600&fit=crop)

## ✨ Features

### Core Features
- **Responsive Design** - Works perfectly on all devices (desktop, tablet, mobile)
- **Modern UI/UX** - Clean, elegant design with smooth animations
- **Reservation System** - Fully functional table booking form
- **Dynamic Menu** - Tab-based menu with categories (Starters, Mains, Desserts, Drinks)
- **Image Gallery** - Beautiful photo gallery with hover effects
- **Customer Reviews** - Interactive carousel testimonials
- **Contact Section** - Location map and contact information
- **Newsletter Signup** - Email subscription form

### Technical Features
- **Bootstrap 5.3** - For responsive grid and components
- **Font Awesome 6.4** - For beautiful icons
- **Google Fonts** - Playfair Display & Poppins typography
- **Smooth Animations** - CSS transitions and JavaScript animations
- **Intersection Observer** - Scroll-triggered animations
- **Form Validation** - Client-side form validation
- **Notification System** - User feedback notifications

## 🚀 Getting Started

### Prerequisites
- Any modern web browser (Chrome, Firefox, Safari, Edge)
- No server required - works as a static site

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/haroonrashidzadran/restaurant-website-.git
cd restaurant-website-
```

2. **Open in browser**
Simply open `index.html` in your preferred web browser.

```bash
# Using Python (if installed)
python -m http.server 8000

# Then visit http://localhost:8000
```

## 📁 Project Structure

```
restaurant-website/
├── index.html          # Main HTML file
├── css/
│   └── style.css      # Custom styles
├── js/
│   └── main.js        # JavaScript functionality
├── images/            # (Optional) Local images
└── README.md          # This file
```

## 🎨 Design Highlights

### Color Palette
- **Primary Gold**: #c9a227 - Elegant accent color
- **Dark Background**: #1a1a1a - Sophisticated dark theme
- **Light Background**: #f8f8f8 - Clean, readable areas
- **White Text**: #ffffff - For dark sections

### Typography
- **Headings**: Playfair Display - Elegant serif font
- **Body**: Poppins - Clean, modern sans-serif

## 📱 Responsive Breakpoints

| Breakpoint | Description |
|------------|-------------|
| < 576px | Mobile devices |
| 576px - 768px | Large phones |
| 768px - 992px | Tablets |
| 992px - 1200px | Laptops |
| > 1200px | Desktops |

## 🔧 Customization

### Changing Colors
Edit `:root` variables in `css/style.css`:
```css
:root {
    --primary: #c9a227;      /* Change gold color */
    --dark: #1a1a1a;         /* Dark background */
    --light: #f8f8f8;        /* Light background */
}
```

### Adding Menu Items
Edit the menu sections in `index.html`. Each menu item uses this structure:
```html
<div class="menu-item">
    <img src="image-url.jpg" alt="Dish Name">
    <div class="menu-item-content">
        <div class="menu-item-header">
            <h5>Dish Name</h5>
            <span class="price">$XX</span>
        </div>
        <p>Description</p>
        <button class="btn btn-sm btn-primary add-to-cart">Add to Cart</button>
    </div>
</div>
```

### Modifying Reservation Form
The form sends data to JavaScript for validation. Customize `initReservationForm()` in `js/main.js` to connect to your backend.

## 📄 Sections

1. **Hero** - Eye-catching header with call-to-action
2. **About** - Restaurant story and features
3. **Services** - Dine-in, takeaway, delivery, catering
4. **Menu** - Interactive tabbed menu
5. **Gallery** - Photo gallery with lightbox effect
6. **Reviews** - Customer testimonials carousel
7. **Reservation** - Table booking form
8. **Contact** - Map and contact info
9. **Footer** - Quick links and newsletter

## 🛠️ Built With

- **HTML5** - Semantic markup
- **CSS3** - Custom styling with CSS variables
- **JavaScript (ES6+)** - Interactive features
- **Bootstrap 5.3** - CSS framework
- **Font Awesome 6.4** - Icon library
- **Google Fonts** - Typography

## 📈 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📝 License

This project is licensed under the MIT License.

## 📞 Contact

- **Website**: [Gourmet Restaurant](https://github.com/haroonrashidzadran/restaurant-website-)
- **GitHub**: [@haroonrashidzadran](https://github.com/haroonrashidzadran)

## 🙏 Acknowledgments

- [Unsplash](https://unsplash.com) for beautiful placeholder images
- [Bootstrap](https://getbootstrap.com) for the amazing CSS framework
- [Font Awesome](https://fontawesome.com) for icons
- [Google Fonts](https://fonts.google.com) for typography

---

⭐ Star this repository if you found it helpful!
