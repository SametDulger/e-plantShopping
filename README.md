# Paradise Nursery - Plant Shopping Cart

A beautiful and interactive plant shopping cart application built with React, featuring Redux state management, modern UI design, and a comprehensive catalog of plants. Paradise Nursery offers a seamless shopping experience for plant enthusiasts with categorized plant collections and a fully functional cart system.

## 🌿 Project Overview

Paradise Nursery is a modern e-commerce application designed for plant lovers. The application features a stunning landing page, categorized plant collections, and a sophisticated shopping cart system. Built with React 18 and Redux Toolkit, it provides a smooth, responsive user experience with beautiful plant imagery and intuitive navigation.

## ✨ Features

### 🏠 Landing Page
- **Welcome Screen** - Beautiful landing page with "Where Green Meets Serenity" theme
- **About Us Section** - Company information and mission statement
- **Smooth Transitions** - Elegant fade animations between pages
- **Responsive Design** - Mobile-friendly layout and navigation

### 🌱 Plant Catalog
- **Categorized Collections** - Plants organized by type and purpose:
  - **Air Purifying Plants** - Snake Plant, Spider Plant, Peace Lily, Boston Fern, Rubber Plant, Aloe Vera
  - **Aromatic Fragrant Plants** - Lavender, Jasmine, Rosemary, Mint, Lemon Balm, Hyacinth
  - **Insect Repellent Plants** - Oregano, Marigold, Geraniums, Basil, Lavender, Catnip
  - **Medicinal Plants** - Aloe Vera, Echinacea, Peppermint, Lemon Balm, Chamomile, Calendula
  - **Low Maintenance Plants** - ZZ Plant, Pothos, Snake Plant, Cast Iron Plant, Succulents, Aglaonema

### 🛒 Shopping Cart System
- **Add to Cart** - One-click product addition with visual feedback
- **Cart Management** - View, modify, and remove items
- **Quantity Control** - Increment/decrement item quantities
- **Total Calculation** - Real-time price calculations
- **Cart Persistence** - Items maintained during navigation
- **Visual Indicators** - Cart icon with item count

### 🎨 User Interface
- **Modern Design** - Clean, professional plant-themed interface
- **High-Quality Images** - Beautiful plant photography from Pixabay and Unsplash
- **Responsive Layout** - Optimized for desktop and mobile devices
- **Interactive Elements** - Hover effects and smooth animations
- **Color Scheme** - Green and natural color palette

### 🔧 Technical Features
- **State Management** - Redux Toolkit for cart state management
- **Component Architecture** - Modular, reusable React components
- **CSS Styling** - Custom CSS with modern design patterns
- **Performance Optimized** - Efficient rendering and state updates

## 🛠️ Technologies Used

### Frontend Framework
- **React 18.2.0** - Modern JavaScript library for building user interfaces
- **React DOM 18.2.0** - React rendering for web applications

### State Management
- **Redux Toolkit 2.2.3** - Modern Redux with simplified setup
- **React Redux 9.1.1** - React bindings for Redux

### Build Tools
- **Vite 5.2.0** - Fast build tool and development server
- **@vitejs/plugin-react 4.2.1** - React plugin for Vite

### Development Tools
- **ESLint 8.57.0** - Code linting and quality assurance
- **eslint-plugin-react 7.34.1** - React-specific ESLint rules
- **eslint-plugin-react-hooks 4.6.0** - ESLint rules for React Hooks
- **eslint-plugin-react-refresh 0.4.6** - ESLint plugin for React Refresh

### Deployment
- **gh-pages 6.3.0** - GitHub Pages deployment automation

### TypeScript Support
- **@types/react 18.2.66** - TypeScript definitions for React
- **@types/react-dom 18.2.22** - TypeScript definitions for React DOM

## 🚀 Getting Started

### Prerequisites
- **Node.js** (version 16 or higher)
- **npm** or **yarn** package manager
- **Modern web browser** (Chrome, Firefox, Safari, Edge)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/SametDulger/e-plantShopping.git
   cd e-plantShopping
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

4. **Access the application**
   - **Development**: `http://localhost:5173`
   - **Production**: `https://sametdulger.github.io/e-plantShopping`

### Build for Production

```bash
# Build the application
npm run build

# Preview production build
npm run preview

# Deploy to GitHub Pages
npm run deploy
```

## 📁 Project Structure

```
e-plantShopping/
├── public/                    # Static assets
├── src/                       # Source code
│   ├── assets/               # Images and static files
│   ├── App.jsx               # Main application component
│   ├── App.css               # Main application styles
│   ├── main.jsx              # Application entry point
│   ├── index.css             # Global styles
│   ├── store.js              # Redux store configuration
│   ├── CartSlice.jsx         # Redux cart slice
│   ├── ProductList.jsx       # Product catalog component
│   ├── ProductList.css       # Product list styles
│   ├── CartItem.jsx          # Shopping cart component
│   ├── CartItem.css          # Cart item styles
│   ├── AboutUs.jsx           # About us component
│   └── AboutUs.css           # About us styles
├── index.html                # HTML template
├── package.json              # Project dependencies
├── vite.config.js            # Vite configuration
├── .eslintrc.cjs             # ESLint configuration
└── README.md                 # Project documentation
```

## 🛒 Shopping Cart Features

### Cart State Management
```javascript
// Cart state structure
{
  items: [
    {
      name: "Snake Plant",
      image: "image-url",
      cost: "$15",
      quantity: 2
    }
  ],
  numOfItems: 2
}
```

### Cart Actions
- **Add Item** - Add product to cart with quantity tracking
- **Remove Item** - Remove product from cart
- **Update Quantity** - Modify item quantity
- **Calculate Total** - Real-time price calculations

### Cart UI Features
- **Visual Feedback** - "Added to Cart" button state
- **Quantity Controls** - Increment/decrement buttons
- **Item Removal** - Delete button for each item
- **Total Display** - Real-time total calculation
- **Continue Shopping** - Return to product catalog

## 🌱 Plant Categories

### Air Purifying Plants
- **Snake Plant** - Produces oxygen at night, improving air quality
- **Spider Plant** - Filters formaldehyde and xylene from the air
- **Peace Lily** - Removes mold spores and purifies the air
- **Boston Fern** - Adds humidity to the air and removes toxins
- **Rubber Plant** - Easy to care for and effective at removing toxins
- **Aloe Vera** - Purifies the air and has healing properties

### Aromatic Fragrant Plants
- **Lavender** - Calming scent, used in aromatherapy
- **Jasmine** - Sweet fragrance, promotes relaxation
- **Rosemary** - Invigorating scent, often used in cooking
- **Mint** - Refreshing aroma, used in teas and cooking
- **Lemon Balm** - Citrusy scent, relieves stress and promotes sleep
- **Hyacinth** - Beautiful flowering plant known for its fragrance

### Insect Repellent Plants
- **Oregano** - Contains compounds that deter certain insects
- **Marigold** - Natural insect repellent, adds color to garden
- **Geraniums** - Known for insect-repelling properties
- **Basil** - Repels flies and mosquitoes, used in cooking
- **Lavender** - Calming scent, used in aromatherapy
- **Catnip** - Repels mosquitoes and attracts cats

### Medicinal Plants
- **Aloe Vera** - Soothing gel used for skin ailments
- **Echinacea** - Boosts immune system, helps fight colds
- **Peppermint** - Relieves digestive issues and headaches
- **Lemon Balm** - Calms nerves and promotes relaxation
- **Chamomile** - Soothes anxiety and promotes sleep
- **Calendula** - Heals wounds and soothes skin irritations

### Low Maintenance Plants
- **ZZ Plant** - Thrives in low light and requires minimal watering
- **Pothos** - Tolerates neglect and can grow in various conditions
- **Snake Plant** - Needs infrequent watering and is resilient to pests
- **Cast Iron Plant** - Hardy plant that tolerates low light and neglect
- **Succulents** - Drought-tolerant plants with unique shapes and colors
- **Aglaonema** - Requires minimal care and adds color to indoor spaces

## 🎨 Design Features

### Color Scheme
- **Primary Green** - #4CAF50 (Natural, plant-themed)
- **White** - Clean, modern background
- **Black** - Text and contrast elements
- **Accent Colors** - Various shades for plant categories

### Typography
- **Headings** - Bold, prominent display
- **Body Text** - Clean, readable fonts
- **Product Names** - Clear, descriptive labels
- **Prices** - Prominent, easy-to-read formatting

### Layout
- **Grid System** - Responsive product grid
- **Card Design** - Clean product cards with images
- **Navigation** - Fixed header with cart icon
- **Spacing** - Consistent padding and margins

## 🔧 Configuration

### Vite Configuration
```javascript
import { defineConfig } from 'vite'
import react from '@vitejs/plugin-react'

export default defineConfig({
  base: "/e-plantShopping",
  plugins: [react()],
})
```

### Redux Store Configuration
```javascript
import { configureStore } from '@reduxjs/toolkit';
import cartReducer from './CartSlice';

const store = configureStore({
  reducer: {
    cart: cartReducer,
  },
});
```

### ESLint Configuration
- **React Rules** - Enforce React best practices
- **Hooks Rules** - Ensure proper Hooks usage
- **Code Quality** - Maintain code standards

## 🧪 Testing

### Manual Testing
1. **Navigation** - Test page transitions and navigation
2. **Cart Functionality** - Add, remove, and modify cart items
3. **Responsive Design** - Test on different screen sizes
4. **Performance** - Check loading times and animations

### Browser Compatibility
- **Chrome** - Full support
- **Firefox** - Full support
- **Safari** - Full support
- **Edge** - Full support

## 🚀 Deployment

### GitHub Pages Deployment
```bash
# Build and deploy
npm run deploy
```

### Manual Deployment
```bash
# Build for production
npm run build

# Serve static files
npm run preview
```

### Deployment Features
- **Base Path Configuration** - Proper routing for GitHub Pages
- **Static Asset Optimization** - Optimized images and resources
- **SEO Optimization** - Meta tags and descriptions

## 🤝 Contributing

1. **Fork the repository**
2. **Create a feature branch** (`git checkout -b feature/amazing-feature`)
3. **Commit your changes** (`git commit -m 'Add some amazing feature'`)
4. **Push to the branch** (`git push origin feature/amazing-feature`)
5. **Open a Pull Request**

### Development Guidelines
- Follow React best practices
- Use proper component structure
- Maintain consistent styling
- Test thoroughly before submitting
- Update documentation as needed

## 🔮 Future Enhancements

### Planned Features
- **User Authentication** - Login and registration system
- **Wishlist** - Save favorite plants for later
- **Plant Care Guides** - Detailed care instructions
- **Reviews & Ratings** - Customer feedback system
- **Search & Filter** - Advanced product search
- **Payment Integration** - Secure checkout process

### Technical Improvements
- **TypeScript Migration** - Add type safety
- **Unit Testing** - Comprehensive test coverage
- **Performance Optimization** - Code splitting and lazy loading
- **PWA Features** - Offline support and app-like experience
- **API Integration** - Backend data management
- **Analytics** - User behavior tracking

## 📝 License

This project is licensed under the **Apache License 2.0** - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **IBM Developer Skills Network** - Original project template and inspiration
- **Pixabay** - High-quality plant images
- **Unsplash** - Beautiful photography resources
- **React Team** - Excellent frontend framework
- **Redux Team** - Powerful state management solution

## 📚 Learning Resources

### Documentation
- [React Documentation](https://reactjs.org/docs/)
- [Redux Toolkit Guide](https://redux-toolkit.js.org/)
- [Vite Documentation](https://vitejs.dev/)
- [ESLint Configuration](https://eslint.org/docs/user-guide/)

### Tutorials
- [React Shopping Cart](https://reactjs.org/tutorial/tutorial.html)
- [Redux State Management](https://redux.js.org/tutorials/essentials/part-1-overview-concepts)
- [Vite Build Tool](https://vitejs.dev/guide/)
- [Modern React Patterns](https://reactpatterns.com/)

## 📞 Support

For questions, issues, or contributions:
- **Issues**: [GitHub Issues](https://github.com/SametDulger/e-plantShopping/issues)
- **Discussions**: [GitHub Discussions](https://github.com/SametDulger/e-plantShopping/discussions)

## 🌟 Key Highlights

### Plant Shopping Excellence
- **Comprehensive Catalog** - 30+ plants across 5 categories
- **Beautiful Design** - Stunning plant imagery and modern UI
- **Smooth Experience** - Intuitive navigation and interactions
- **Cart Management** - Full-featured shopping cart system

### Modern Technology Stack
- **React 18** - Latest React features and performance
- **Redux Toolkit** - Simplified state management
- **Vite** - Fast development and build tool
- **Modern CSS** - Responsive and beautiful styling

### Developer Experience
- **Hot Reload** - Instant development feedback
- **ESLint Integration** - Code quality assurance
- **GitHub Pages** - Easy deployment
- **Production Ready** - Optimized for performance

---

**Built with ❤️ using React, Redux Toolkit, and Vite**
