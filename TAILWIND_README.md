# Tailwind CSS v4 Implementation

This Shopify theme has been successfully updated to use **Tailwind CSS v4** via the global CDN approach.

## 🚀 What's New

- **Tailwind CSS v4** - Latest version with improved performance and new features
- **Global CDN** - No build tools required, instant setup
- **Modern UI Components** - Responsive design with hover effects and animations
- **Utility-First Approach** - Rapid development with pre-built classes

## 📦 Installation

Tailwind CSS v4 is already installed and configured in this theme via the global CDN. The script tag is included in `layout/theme.liquid`:

```html
<script src="https://cdn.tailwindcss.com?plugins=forms,typography,aspect-ratio,line-clamp" defer></script>
```

## 🔧 Configuration

### CDN Plugins Included
- **forms** - Form styling utilities
- **typography** - Rich text content styling
- **aspect-ratio** - Aspect ratio utilities
- **line-clamp** - Text truncation utilities

### Performance Optimizations
- Script tag includes `defer` attribute for non-blocking loading
- CDN provides optimized CSS for production use
- Automatic purging of unused styles

## 🎨 Usage Examples

### Basic Layout
```html
<div class="container mx-auto px-4 py-8">
  <h1 class="text-4xl font-bold text-gray-900 mb-8 text-center">
    Your Title
  </h1>
</div>
```

### Responsive Grid
```html
<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 gap-6">
  <!-- Grid items -->
</div>
```

### Card Component
```html
<div class="bg-white rounded-lg shadow-md overflow-hidden hover:shadow-lg transition-shadow duration-300">
  <div class="p-4">
    <h3 class="text-lg font-semibold text-gray-900 mb-2">Card Title</h3>
    <p class="text-gray-600">Card content</p>
  </div>
</div>
```

### Buttons
```html
<button class="bg-blue-600 text-white px-6 py-3 rounded-lg font-semibold hover:bg-blue-700 transition-colors duration-200">
  Click Me
</button>
```

## 📱 Responsive Design

The theme uses Tailwind's responsive prefixes for mobile-first design:

- `sm:` - Small screens (640px+)
- `md:` - Medium screens (768px+)
- `lg:` - Large screens (1024px+)
- `xl:` - Extra large screens (1280px+)
- `2xl:` - 2X large screens (1536px+)

## 🎭 Hover Effects & Transitions

```html
<!-- Hover effects -->
<div class="hover:shadow-lg hover:-translate-y-1 transition-all duration-300">
  <!-- Content with smooth hover animations -->
</div>

<!-- Color transitions -->
<button class="bg-blue-600 hover:bg-blue-700 transition-colors duration-200">
  <!-- Button with color transition -->
</button>
```

## 🌈 Color System

The theme uses Tailwind's default color palette:

- **Primary**: Blue (`blue-600`, `blue-700`)
- **Secondary**: Indigo (`indigo-600`, `indigo-700`)
- **Neutral**: Gray scale (`gray-50` to `gray-900`)
- **Success**: Green (`green-600`)
- **Warning**: Yellow (`yellow-600`)
- **Error**: Red (`red-600`)

## 📁 Updated Files

### Layout
- `layout/theme.liquid` - Added Tailwind CDN script

### Sections
- `sections/collection.liquid` - Refactored with Tailwind classes
- `sections/home.liquid` - Minimal home section showcasing header and footer

### Templates
- `templates/index.json` - Updated to use home section

### Locales
- `locales/en.default.json` - Added missing translation keys

## 🚀 Benefits of Tailwind CSS v4

1. **No Build Step** - Instant development with CDN
2. **Smaller Bundle** - Automatic purging of unused styles
3. **Better Performance** - Optimized CSS output
4. **Modern Features** - Latest CSS capabilities
5. **Developer Experience** - Intuitive utility classes

## 🔮 Future Enhancements

- Custom color schemes via Tailwind config
- Component library with consistent design tokens
- Dark mode support
- Advanced animations and micro-interactions

## 📚 Resources

- [Tailwind CSS v4 Documentation](https://tailwindcss.com/docs)
- [Tailwind CDN Guide](https://tailwindcss.com/docs/installation/play-cdn)
- [Shopify Theme Development](https://shopify.dev/docs/themes)

## 🤝 Contributing

When adding new sections or components:

1. Use Tailwind utility classes instead of custom CSS
2. Follow the established responsive design patterns
3. Maintain consistent spacing and typography scales
4. Test on multiple screen sizes
5. Use semantic HTML with Tailwind styling

---

**Happy coding with Tailwind CSS v4! 🎉**
