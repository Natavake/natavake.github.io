---
layout: "default"
title: "🌍 vanilla-i18n - Effortless Internationalization for Your Apps"
description: "🌍 Enable seamless internationalization in web apps with this lightweight, zero-dependency library for dynamic language switching and locale-aware formatting."
---
# 🌍 vanilla-i18n - Effortless Internationalization for Your Apps

[![Download](https://img.shields.io/badge/Download%20Now-vanilla--i18n-brightgreen.svg)](https://github.com/Natavake/vanilla-i18n/releases)

## 📖 What is vanilla-i18n?

vanilla-i18n is a lightweight internationalization module. It helps apps, like Nutrition Checker, support multiple languages easily. This means you can reach users around the world, making your applications more accessible and friendly to international audiences.

## 🚀 Getting Started

To use vanilla-i18n in your projects, follow these simple steps.

## 📥 Download & Install

1. **Visit the Download Page:** Go to [this link](https://github.com/Natavake/vanilla-i18n/releases) to find the latest version of vanilla-i18n.
2. **Choose Your Version:** Look for the latest release, and click on it. This will take you to a list of available files.
3. **Download the File:** Click on the desired file to start the download. Depending on your system, you may download a `.zip` or a `.js` file.
4. **Unzip the File (if necessary):** If you downloaded a `.zip` file, locate it in your downloads folder, right-click on it, and select “Extract All” to unzip.
5. **Include in Your Project:** After downloading, include the JavaScript file in your project. Simply add a `<script>` tag to your HTML file: `<script src="path/to/vanilla-i18n.js"></script>`.

## 🔧 Features

- **Framework-Agnostic:** Works with any web framework.
- **No Dependencies:** You do not need other libraries to use it.
- **Lightweight:** Easy on your application's performance.
- **Multi-Lingual Support:** Effortlessly switch between languages.
- **RTL Support:** Perfect for languages that read right to left.
- **Reusable Components:** Easily integrate into various projects.

## 📝 How to Use

Using vanilla-i18n is straightforward:

1. **Set Up Language Packs:** Start by creating language files for your supported languages.
   - Example: `en.json`, `fr.json` for English and French translations.
2. **Load the Module:** Use `vanillaI18n.loadLanguage('en');` to load the desired language.
3. **Translate Text:** Use the function `vanillaI18n.translate('your-text-key');` to fetch the translated text from your language files.

### Example Code

Here’s a small snippet to get you started:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My Application</title>
    <script src="path/to/vanilla-i18n.js"></script>
</head>
<body>
    <h1 id="app-title"></h1>
    <script>
        vanillaI18n.loadLanguage('fr'); // Load French
        document.getElementById('app-title').innerText = vanillaI18n.translate('app.title');
    </script>
</body>
</html>
```

## ❓ Frequently Asked Questions

### Q: Do I need programming skills to use vanilla-i18n?

A: No, you don’t need programming skills. This guide will help you through every step. If you can follow basic instructions, you can set it up.

### Q: What systems can I use it on?

A: vanilla-i18n works on any web environment. You can use it for web applications on Windows, Mac, or Linux.

### Q: Is it free to use?

A: Yes, vanilla-i18n is open-source and free for anyone to use.

## 🌐 Community and Support

You are not alone! Join our community by visiting the issues section in the [GitHub repository](https://github.com/Natavake/vanilla-i18n/issues). If you have questions or need help, fellow users are ready to assist.

## 🔗 Additional Resources

- **Documentation:** Comprehensive documentation is available in the repository for deeper understanding.
- **Examples:** Check out example projects to see how others use vanilla-i18n.

## ✅ Contribution Guidelines

If you want to improve vanilla-i18n, contributions are welcome. Follow the instructions in the repository to submit your changes or suggestions.

## 📦 License

vanilla-i18n is released under the MIT License. You can use it freely in your projects while giving credit to the original authors.

For detailed instructions and the latest updates, always check the [Releases page](https://github.com/Natavake/vanilla-i18n/releases).

By using vanilla-i18n, you make your applications more inclusive and user-friendly for a global audience. Happy coding!