# Tushar Jain - Personal Portfolio

A modern, responsive personal portfolio website built with React and Tailwind CSS. This project showcases Tushar Jain's skills, experience, and projects in an elegant and professional design.

## 🚀 Features

- **Modern Design**: Clean and professional dark theme with orange-yellow accents
- **Responsive Layout**: Fully responsive design that works on all devices
- **Smooth Animations**: Beautiful animations using Framer Motion
- **Interactive Components**: Dynamic portfolio filtering and contact form
- **Performance Optimized**: Fast loading with optimized images and code
- **Accessible**: Built with accessibility in mind

## 🛠️ Technologies Used

- **React 18** - Modern React with hooks and functional components
- **Tailwind CSS** - Utility-first CSS framework for styling
- **Framer Motion** - Animation library for smooth transitions
- **React Icons** - Beautiful icons from various icon sets
- **Vite** - Fast build tool and development server

## 📁 Project Structure

```
src/
├── components/
│   ├── About.js          # About page component
│   ├── Contact.js        # Contact form component
│   ├── Navbar.js         # Navigation component
│   ├── Portfolio.js      # Portfolio with filtering
│   ├── Resume.js         # Resume/experience component
│   └── Sidebar.js        # Sidebar with profile info
├── App.js                # Main app component
├── index.js              # React entry point
└── index.css             # Global styles and Tailwind imports

public/
├── assets/               # Images and static assets
└── index.html            # HTML template
```

## 🎨 Design Features

- **Dark Theme**: Professional dark color scheme
- **Gradient Backgrounds**: Subtle gradients for visual depth
- **Card-based Layout**: Modern card design for content sections
- **Hover Effects**: Interactive hover animations
- **Custom Scrollbars**: Styled scrollbars matching the theme
- **Typography**: Clean typography using Poppins font

## 🚀 Getting Started

### Prerequisites

- Node.js (version 16 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd tushar-jain-portfolio
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm start
   ```

4. **Open your browser**
   Navigate to `http://localhost:3000` to view the application

### Building for Production

```bash
npm run build
```

This creates an optimized production build in the `build` folder.

## 📱 Responsive Design

The portfolio is fully responsive and optimized for:
- **Mobile**: 320px and up
- **Tablet**: 768px and up
- **Desktop**: 1024px and up
- **Large Desktop**: 1280px and up

## 🎯 Key Components

### Sidebar
- Profile information with avatar
- Contact details (email, phone, location)
- Social media links
- Collapsible contact section

### Navigation
- Clean navigation bar with active states
- Mobile-responsive hamburger menu
- Smooth page transitions

### Portfolio
- Project filtering by category
- Interactive project cards
- Hover effects and animations
- External project links

### Contact Form
- Form validation
- Responsive layout
- Success/error handling

## 🎨 Customization

### Colors
The color scheme can be customized in `tailwind.config.js`:

```javascript
colors: {
  'jet': '#383838',
  'onyx': '#2b2b2b',
  'orange-yellow': '#ffd93d',
  // ... more colors
}
```

### Content
Update the content in respective component files:
- Personal information in `Sidebar.js`
- Projects in `Portfolio.js`
- Experience in `Resume.js`
- About text in `About.js`

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📞 Contact

- **Email**: tusharjainqwerty@gmail.com
- **Phone**: 9306695193
- **Location**: Bahadurgarh, Haryana, India

---

Built with ❤️ by Tushar Jain
