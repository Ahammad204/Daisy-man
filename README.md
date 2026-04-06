# Daisy Man - Fashion E-Commerce Platform

> Your one-step destination for all your fashion needs

A modern, responsive e-commerce web application showcasing fashion products with an elegant user interface built using cutting-edge web technologies.

## 🌐 Live Demo

Visit the live application here: [**https://ahammad204.github.io/Daisy-man/**](https://ahammad204.github.io/Daisy-man/)

## ✨ Features

- **Responsive Design** - Fully responsive layout that works seamlessly on mobile, tablet, and desktop devices
- **Modern UI/UX** - Beautiful, intuitive interface with smooth interactions using DaisyUI components
- **Product Categories** - Browse through various product categories:
  - 👞 Shoes
  - 👕 Clothing & Hoodies
  - 💐 Perfumes & Fragrances
- **Shopping Cart** - Interactive shopping cart with item counter and subtotal display
- **User Profile** - User profile dropdown with settings and logout options
- **Hero Banner** - Eye-catching hero section to welcome users
- **Easy Checkout** - Streamlined purchasing experience highlighting ease of transaction

## 🛠️ Tech Stack

- **HTML5** - Semantic markup structure
- **Tailwind CSS** - Utility-first CSS framework for rapid UI development
- **DaisyUI** - Component library built on Tailwind CSS
- **Responsive Grid System** - Mobile-first responsive design approach

## 📋 Project Structure

```
Daisy-man/
├── index.html              # Main HTML file
├── tailwind.config.js      # Tailwind CSS configuration
├── README.md               # Project documentation
└── images/                 # Product and asset images
    ├── shoes.avif
    ├── hoodies.avif
    ├── perfume.avif
    ├── easy-purchase.avif
    └── [other product images]
```

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic knowledge of HTML and CSS (for modifications)

### Installation & Usage

1. **Clone the repository**
   ```bash
   git clone https://github.com/ahammad204/Daisy-man.git
   cd Daisy-man
   ```

2. **Open locally**
   - Simply open `index.html` in your web browser
   - Or use a local server:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js (with http-server)
     npx http-server
     ```

3. **View in browser**
   - Navigate to `http://localhost:8000` (or your server port)

## 🎨 Customization

### Theme Configuration

The project uses DaisyUI's `cupcake` theme. To switch themes, modify the `data-theme` attribute in `index.html`:

```html
<html lang="en" data-theme="cupcake">
```

Available DaisyUI themes include: light, dark, cupcake, bumblebee, emerald, corporate, synthwave, and more.

### Tailwind CSS Configuration

Customize colors, spacing, and other design tokens in `tailwind.config.js`:

```javascript
module.exports = {
  theme: {
    extend: {
      colors: {
        // Add custom colors
      }
    }
  }
}
```

## 📱 Responsive Breakpoints

- **Mobile**: Base styles (< 768px)
- **Tablet**: `md:` prefix (≥ 768px)
- **Desktop**: `lg:` prefix (≥ 1024px)

## 📸 Key Sections

### Header
- **Navigation Bar**: Logo, shopping cart with item count, and user profile menu
- **Hero Banner**: Full-height banner with call-to-action button

### Main Content
- **Product Categories**: Grid layout showcasing different product categories
- **Easy Purchases Section**: Marketing section highlighting the simplicity of shopping

### Footer
- (Expandable section for additional links and information)

## 🔧 Development

### Adding New Products

To add new product categories, duplicate the card components in the categories section:

```html
<div class="card bg-base-100 shadow-xl image-full">
    <figure><img src="./images/your-image.avif" alt="Product" /></figure>
    <div class="card-body">
        <h2 class="card-title">Product Name</h2>
        <p>Product description</p>
        <div class="card-actions justify-end">
            <button class="btn">Buy Now</button>
        </div>
    </div>
</div>
```

### Image Optimization

The project uses `.avif` format for optimized image delivery. Consider converting images to AVIF format for better performance:

```bash
# Using ImageMagick
convert input.jpg -format avif output.avif
```

## 📦 Dependencies

All dependencies are loaded via CDN:
- **Tailwind CSS** - `https://cdn.tailwindcss.com`
- **DaisyUI** - `https://cdn.jsdelivr.net/npm/daisyui@3.3.1/dist/full.css`

## 🤝 Contributing

Contributions are welcome! Feel free to:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the MIT License.

## 👤 Author

**Ahammad** - Frontend Developer
- GitHub: [@ahammad204](https://github.com/ahammad204)
- Project: [Daisy Man](https://github.com/ahammad204/Daisy-man)

## 🌟 Acknowledgments

- [Tailwind CSS](https://tailwindcss.com/) - For the amazing CSS framework
- [DaisyUI](https://daisyui.com/) - For the beautiful component library
- AI-generated product images for the showcase

## 📞 Support

For support or questions, please open an issue on the [GitHub repository](https://github.com/ahammad204/Daisy-man/issues).

---

**Made with ❤️ by Ahammad**

**Live Demo:** [https://ahammad204.github.io/Daisy-man/](https://ahammad204.github.io/Daisy-man/)
