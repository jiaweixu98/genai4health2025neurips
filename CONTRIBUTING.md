# Contributing to GenAI4Health 2025 Workshop Website

Thank you for your interest in contributing to this project! This document provides guidelines and instructions for contributing.

## 🚀 Getting Started

1. **Fork the repository** on GitHub
2. **Clone your fork** locally:
   ```bash
   git clone https://github.com/YOUR_USERNAME/genai4health2025neurips.git
   cd genai4health2025neurips
   ```
3. **Install dependencies**:
   ```bash
   npm install
   ```
4. **Create a branch** for your changes:
   ```bash
   git checkout -b feature/your-feature-name
   ```

## 📝 Making Changes

- Write clean, readable code
- Follow the existing code style
- Add comments for complex logic
- Test your changes locally before submitting

## 🧪 Testing

Before submitting your changes:

1. **Run the development server** to test your changes:
   ```bash
   npm start
   ```

2. **Check for linting errors**:
   ```bash
   npm run lint
   ```

3. **Format your code**:
   ```bash
   npm run format
   ```

4. **Build the project** to ensure there are no build errors:
   ```bash
   npm run build
   ```

## 📤 Submitting Changes

1. **Commit your changes** with a clear message:
   ```bash
   git add .
   git commit -m "Add: description of your changes"
   ```

2. **Push to your fork**:
   ```bash
   git push origin feature/your-feature-name
   ```

3. **Open a Pull Request** on GitHub with:
   - A clear title and description
   - Reference to any related issues
   - Screenshots (if applicable)

## 🎯 Using This as a Base for Your Own Project

This project is designed to be easily adaptable for other workshops or events. To use it as a base:

1. **Fork or clone** this repository
2. **Update the content** in `src/App.js`:
   - Workshop name and dates
   - Speaker information
   - Organizer details
   - Call for Papers content
   - Schedule/agenda
3. **Replace images** in `public/data/images/`:
   - Organizer photos
   - Speaker photos
   - Logos and backgrounds
4. **Update metadata** in `public/index.html`:
   - Title, description, and SEO tags
5. **Customize styling** in `src/index.css`:
   - Colors, fonts, and layout
6. **Update package.json**:
   - Project name and description
   - Repository URL
7. **Update README.md** with your project information

## 📋 Code Style

- Use meaningful variable and function names
- Keep functions focused and small
- Use React hooks appropriately
- Follow the existing component structure

## ❓ Questions?

If you have questions or need help, please:
- Open an issue on GitHub
- Contact the maintainers listed in README.md

## 🙏 Thank You!

Your contributions help make this project better for everyone!
