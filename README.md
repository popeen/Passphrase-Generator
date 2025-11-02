[![issues-shield]](issues)
[![license-shield]](LICENSE.md)
[![Buy me a coffee][buymeacoffee-shield]][buymeacoffee-link]

# 🔐 Passphrase Generator

A **secure, browser-based passphrase generator**. Everything happens locally, your passphrase never leaves your browser.

---

## 🌟 Features

- Generate **random passphrases** from English, Swedish, German, or mixed wordlists  
- Adjustable **number of words**
- Custom **separator** and options:
  - Capitalize words  
  - Include numbers  
  - Include special characters  
- Check passphrase against known data breaches via [Have I Been Pwned](https://haveibeenpwned.com/) using **k-anonymity** (safe & private)  
- **Mobile-friendly** and responsive  

---

## 💻 Live Demo

Check it out: [Live Demo](https://pwd.popeen.com)

---

## ⚡ Usage

1. Clone or download the repository:

```bash
git clone https://github.com/popeen/Passphrase-Generator
cd passphrase-generator
```

2. Open `index.html` in your browser.  

3. Select language, number of words, separator, and options.  

4. Click **Generate Passphrase**, optionally check HIBP, and copy your passphrase.  

---

## 🔒 Security Notes

- **Local generation only** - no server sees your passphrase  
- HIBP checks use **first 5 characters of SHA‑1 hash only** (k-anonymity)  

---

## 📜 License

MIT License © [Patrik Johansson](https://github.com/popeen)  

---

## 🙏 Acknowledgments

- Inspired by [xkcd 936: Password Strength](https://xkcd.com/936/)  
- Uses [Have I Been Pwned API](https://haveibeenpwned.com/API/v3) for breach checking


[issues-shield]: https://img.shields.io/github/issues-raw/popeen/Passphrase-Generator.svg

[license-shield]: https://img.shields.io/github/license/popeen/Passphrase-Generator.svg

[buymeacoffee-shield]: https://img.shields.io/badge/donation-Buy%20me%20a%20coffee-orange
[buymeacoffee-link]: https://www.buymeacoffee.com/popeen

