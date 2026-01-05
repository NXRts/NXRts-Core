# 🚀 NXRts Portfolio

[![React](https://img.shields.io/badge/React-18.2.0-61DAFB?style=for-the-badge&logo=react&logoColor=white)](https://reactjs.org/)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-5.2.3-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)
[![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](LICENSE)

> A modern, responsive portfolio website built with React showcasing my projects, skills, and professional experience.

## 👨‍💻 About

Hi! I'm **Muhammad Yusuf Arrofi** (NXRts), a passionate Full Stack Developer from Karanganyar, Indonesia. This portfolio showcases my journey in web development, featuring my projects, technical skills, and professional experience.

**Live Demo**: [View Portfolio](https://nxrts.github.io/NXRts-Core/) *(Update with your actual URL)*

## ✨ Features

- 🎨 **Modern UI/UX** - Clean and professional design with smooth animations
- 📱 **Fully Responsive** - Works seamlessly on desktop, tablet, and mobile devices
- 🌓 **Dark/Light Theme** - Toggle between dark and light modes
- ⚡ **Fast Performance** - Optimized for speed and performance
- 🎯 **Animated Cursor** - Custom animated cursor for enhanced user experience
- 📧 **Contact Form** - Integrated with EmailJS for direct communication
- 🔄 **Smooth Transitions** - Page transitions with React Transition Group
- ⌨️ **Typewriter Effect** - Dynamic text animation on the home page
- 🎨 **Portfolio Showcase** - Display of projects with images and descriptions

## 🛠️ Tech Stack

### Frontend
- **React** 18.2.0 - JavaScript library for building user interfaces
- **React Router DOM** 6.6.2 - Declarative routing for React
- **Bootstrap** 5.2.3 - CSS framework for responsive design
- **React Bootstrap** 2.7.0 - Bootstrap components built with React

### Libraries & Tools
- **EmailJS** - Email service for contact form
- **React Icons** - Icon library
- **Typewriter Effect** - Animated typing effect
- **React Helmet Async** - Document head management
- **React Transition Group** - Animation library for transitions

## 📁 Project Structure

```
NXRts-Core/
├── public/              # Public assets
├── src/
│   ├── app/            # Main app configuration
│   │   ├── App.js      # Main app component
│   │   ├── App.css     # App styles
│   │   └── routes.js   # Route configuration
│   ├── assets/         # Images and static assets
│   ├── components/     # Reusable components
│   │   ├── socialicons/
│   │   └── themetoggle/
│   ├── header/         # Header component
│   ├── hooks/          # Custom hooks
│   │   ├── AnimatedCursor.js
│   │   └── withRouter.js
│   ├── pages/          # Page components
│   │   ├── home/
│   │   ├── about/
│   │   ├── portfolio/
│   │   └── contact/
│   ├── content_option.js  # Content configuration
│   ├── index.css       # Global styles
│   └── index.js        # Entry point
├── package.json
└── README.md
```

## 🚀 Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:
- **Node.js** (v14 or higher)
- **npm** or **yarn**

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/NXRts/NXRts-Core.git
   cd NXRts-Core
   ```

2. **Install dependencies**
   ```bash
   # Using npm
   npm install

   # Using yarn
   yarn install
   ```

3. **Configure EmailJS** (Optional - for contact form)
   
   Update the EmailJS configuration in `src/content_option.js`:
   ```javascript
   const contactConfig = {
       YOUR_EMAIL: "your-email@example.com",
       YOUR_FONE: "(+62)xxx-xxxx-xxxx",
       YOUR_SERVICE_ID: "your_service_id",
       YOUR_TEMPLATE_ID: "your_template_id",
       YOUR_USER_ID: "your_user_id",
   };
   ```

4. **Start the development server**
   ```bash
   # Using npm
   npm start

   # Using yarn
   yarn start
   ```

   The app will open at [http://localhost:3000](http://localhost:3000)

## 🎨 Customization

### Update Personal Information

Edit `src/content_option.js` to customize:

- **Meta Information** - Title and description
- **Introduction** - Name, animated text, and description
- **About Section** - Personal information and bio
- **Work Timeline** - Professional experience
- **Skills** - Technical skills with proficiency levels
- **Services** - Services you offer
- **Portfolio** - Your projects with images and links
- **Contact Info** - Email and phone number
- **Social Profiles** - Social media links

### Example:

```javascript
const introdata = {
    title: "I'm Your Name",
    animated: {
        first: "I Love Coding",
        second: "I Code Cool Websites",
        third: "I Develop Web API",   
    },
    description: "Your description here...",
    your_img_url: "https://your-image-url.com/image.jpg",
};
```

## 📦 Build for Production

To create a production build:

```bash
# Using npm
npm run build

# Using yarn
yarn build
```

This will create an optimized build in the `build/` folder.

## 🚢 Deployment

### GitHub Pages

1. **Install gh-pages** (if not already installed)
   ```bash
   npm install --save-dev gh-pages
   ```

2. **Update `package.json`** with your repository URL:
   ```json
   "homepage": "https://yourusername.github.io/repository-name"
   ```

3. **Deploy**
   ```bash
   npm run deploy
   ```

### Other Platforms

This project can also be deployed to:
- **Vercel** - `vercel deploy`
- **Netlify** - Drag and drop the `build` folder
- **Heroku** - Using buildpacks
- **AWS S3** - Static website hosting

## 🎯 Available Scripts

| Command | Description |
|---------|-------------|
| `yarn start` | Runs the app in development mode |
| `yarn build` | Builds the app for production |
| `yarn test` | Launches the test runner |
| `yarn eject` | Ejects from Create React App |
| `yarn deploy` | Deploys to GitHub Pages |

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/NXRts/NXRts-Core/issues).

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Muhammad Yusuf Arrofi (NXRts)**

- 🌐 Website: [Your Website](https://nxrts.github.io/NXRts-Core/)
- 💼 LinkedIn: [@muhammad-yusuf-arrofi](https://www.linkedin.com/in/muhammad-yusuf-arrofi-a26140299/)
- 🐙 GitHub: [@NXRts](https://github.com/NXRts)
- 🐦 Twitter: [@MYArrofi](https://x.com/MYArrofi)
- 📷 Instagram: [@my_arrofi](https://www.instagram.com/my_arrofi/)
- 📺 YouTube: [@MyArrofi](https://www.youtube.com/@MyArrofi)
- 📧 Email: arrofisamsung168@gmail.com

## 🙏 Acknowledgments

- [React](https://reactjs.org/) - The web framework used
- [Bootstrap](https://getbootstrap.com/) - CSS framework
- [React Icons](https://react-icons.github.io/react-icons/) - Icon library
- [EmailJS](https://www.emailjs.com/) - Email service
- [Typewriter Effect](https://www.npmjs.com/package/typewriter-effect) - Typing animation

## 📊 Project Status

This project is actively maintained and regularly updated with new features and improvements.

---

<div align="center">

**⭐ Star this repo if you like it! ⭐**

Made with ❤️ by [NXRts](https://github.com/NXRts)

</div>
