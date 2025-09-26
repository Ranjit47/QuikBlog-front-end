# QuikBlog front end 📝

A fast and intuitive blogging platform built for modern content creators.

![License](https://img.shields.io/github/license/Ranjit47/QuikBlog)
![GitHub stars](https://img.shields.io/github/stars/Ranjit47/QuikBlog?style=social)
![GitHub forks](https://img.shields.io/github/forks/Ranjit47/QuikBlog?style=social)


## 🛠 Tech Stack

- **Frontend**:   React, Vue, HTML/CSS/JS
- **Styling**:  CSS3, Tailwind CSS
- **State Management**:   Context API,  
- **Build Tool**: Vite, Create React App
- **Deployment**: Netlify, Vercel, GitHub Pages

## 📋 Prerequisites

Before you begin, ensure you have the following installed:

- [Node.js](https://nodejs.org/) (version 16.0 or higher) - if using a build tool
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/) - if using a package manager
- A modern web browser
- Code editor (VS Code, Sublime Text, etc.)

## 🚀 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Ranjit47/QuikBlog.git
   cd QuikBlog
   ```

2. **Install dependencies** (if using a package manager)
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Set up configuration** (if needed)
   ```bash
   cp config.example.js config.js
   ```
   
   Edit the configuration file with your settings:
   ```javascript
   const config = {
     apiBaseUrl: 'https://your-api-endpoint.com',
     appTitle: 'QuikBlog',
     // Add other configuration options
   };
   ```

4. **Start the development server**
   ```bash
   npm start
   # or
   yarn start
   # or simply open index.html in your browser
   ```

5. **Visit the application**
   
   Open [http://localhost:3000](http://localhost:3000) in your browser
   
   *Or if it's a static site, simply open `index.html` directly in your browser*

  

## 📁 Project Structure

```
QuikBlog/
├── assets/                # Images, fonts, and other assets
├── css/                   # Stylesheets
├── js/                    # JavaScript files
├── components/            # Reusable components (if using a framework)
├── pages/                 # Different page templates
├── data/                  # Static data files (JSON, etc.)
├── config/                # Configuration files
├── dist/                  # Built/compiled files (if using a build tool)
├── tests/                 # Test files
├── docs/                  # Documentation
├── index.html             # Main HTML file
├── package.json           # Dependencies (if using npm)
└── README.md
```

## 🧪 Testing

Run the test suite:

```bash
npm test
# or
yarn test
```

For coverage report:

```bash
npm run test:coverage
```


## 🎯 Features Overview

Since QuikBlog is a frontend-only application, it focuses on:

- **Client-Side Rendering**: Fast, responsive user interface
- **Local Storage**: Data persistence using browser storage
- **No Server Required**: Runs entirely in the browser
- **Easy Deployment**: Host anywhere that serves static files
- **Offline Capable**: Can work without internet connection (with service workers)

## 📊 Data Storage

As a frontend-only application, QuikBlog uses:

- **Local Storage**: For saving blog posts and user preferences
- **Session Storage**: For temporary data during the session
- **JSON Files**: For static content and configuration
- **Import/Export**: Backup and restore functionality for blog data


## 👨‍💻 Author

**Ranjit47**
- GitHub: [@Ranjit47](https://github.com/Ranjit47)
- Email: ranjitsantoshrai47@gmail.com

 
## 📊 Project Status

- ✅ Basic functionality complete
- ✅ User authentication system
- ✅ Post management
- 🔄 Advanced features in development
- 📋 Mobile app planned for future release

