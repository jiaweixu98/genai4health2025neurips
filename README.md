# GenAI4Health 2025 Workshop Website

This is the official website for **The Second Workshop on GenAI for Health: Potential, Trust, and Policy Compliance** at NeurIPS 2025.

## 🚀 Quick Start

### Prerequisites
- Node.js (version 14 or higher)
- npm (comes with Node.js)

### Installation & Running

1. **Clone the repository**
   ```bash
   git clone https://github.com/jiaweixu98/genai4health2025neurips.git
   cd genai4health2025neurips
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
   Navigate to `http://localhost:3000` to view the website.

The development server will automatically reload when you make changes to the code.

## 📁 Project Structure

```
genai4health2025neurips/
├── public/
│   ├── data/
│   │   └── images/
│   │       ├── bg/
│   │       ├── logo/
│   │       ├── organizers/
│   │       ├── speakers/
│   │       └── sponsor/
│   ├── index.html
│   ├── robots.txt
│   └── sitemap.xml
├── src/
│   ├── components/
│   │   └── SEOFallback.js
│   ├── App.js          # Main application component
│   ├── index.js        # Entry point
│   └── index.css       # Global styles
├── package.json
├── README.md
└── .gitignore
```

## 🛠️ Available Scripts

- `npm start` - Start development server
- `npm run build` - Build for production (after that, you can check the webpage under `/build`, which is ready to use for deployment)


## 🎨 Features

- **Responsive Design** - Works on desktop, tablet, and mobile
- **Smooth Scrolling** - Navigation with smooth scroll animations
- **Speaker Information** - Detailed speaker profiles and keynote information
- **Interactive Agenda** - Complete workshop schedule
- **Call for Papers** - Submission guidelines and important dates
- **Organizer Profiles** - Information about workshop organizers

## 📞 Contact

For questions about the workshop:
- **Jiawei Xu**: jiaweixu@utexas.edu
- **Tiange Xiang**: xtiange@stanford.edu

For technical issues with the website, please open an issue on GitHub.

## 🚀 Deployment

The website works for both deployment locations:
- **GitHub Pages**: https://genai4health.github.io/ 
- **University of Texas**: https://aihealth.ischool.utexas.edu/GenAI4HealthNeurips2025/

### Simple Deployment Steps

1. **Build the site:**
   ```bash
   npm run build
   ```

 **For University of Texas:**
   - Upload the contents of the `build` folder to your server

The site uses relative paths for assets, so it works in both root domains and subdirectories without any configuration changes needed.

## 🤝 Contributing

This is an open-source project. Feel free to fork, modify, and use it as a base for your own projects. If you'd like to contribute improvements back to this repository, please:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. 