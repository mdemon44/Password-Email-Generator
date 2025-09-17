# 🛡️ PASSWORD & E-MAIL GENERATOR

A powerful and user-friendly command-line tool for generating secure passwords and professional email addresses. Built with Python, this tool offers multiple security levels and customization options for all your security needs.

---

## 🚀 Features

### 🔐 Password Generator
- **Multiple Security Levels**: Normal (8 chars), Medium (12 chars), and High (16 chars)
- **Customizable Options**: Choose length (4–120 characters) and character sets
- **Character Set Control**: Toggle uppercase, lowercase, digits, and special characters
- **Strong Encryption**: Uses cryptographically secure random generation

### 📧 Email Generator
- **Name-based Generation**: Create professional emails from first and last names
- **Random Generation**: Generate completely random email addresses
- **Multiple Domains**: Supports Gmail, Yahoo, Outlook, Hotmail, iCloud
- **Various Formats**: Multiple naming conventions and patterns

### 🎨 User Experience
- **Colorful Interface**: Beautiful ANSI-colored terminal interface
- **Interactive Menus**: Intuitive navigation with numbered options
- **Help Section**: Comprehensive built-in documentation
- **Cross-Platform**: Works on Windows, macOS, and Linux

---

## 🛠️ Installation

### Prerequisites
- Python 3.6 or higher
- pip (Python package manager)

### Setup
1. Clone or download the reposatory
2. Navigate to the script directory
3. Run the script directly:
   ```bash
   python pass_&_email.py

✅ No additional dependencies required! The script uses only Python's standard library.

---

## 📋 Usage

### Main Menu
Upon running the script, you'll see:
1. Password Generator  
2. Email Generator  
3. Help  
4. Exit  

### Password Generator Options
1. **Normal**: 8 characters with letters and numbers  
2. **Medium**: 12 characters with letters, numbers, and basic symbols  
3. **High**: 16 characters with letters, numbers, and all symbols  
4. **Custom**: Configure your own parameters  
5. Back to main menu  

### Email Generator Options
1. **Name-based**: Generate emails from first and last names  
2. **Random**: Generate completely random emails  
3. Back to main menu  

### 🔍 Examples

#### Generating a Password
```
Select an option (1–5): 3
Generated Password: k5@8Gm#2!qL9$vR*
```

#### Generating Email Addresses
```
Enter first name: John
Enter last name: Smith

Generated Emails:
john.smith@gmail.com
johnsmith@yahoo.com
john_smith@outlook.com
j.smith@hotmail.com
jsmith@icloud.com
j.s@icloud.com
johns@outlook.com
js@gmail.com
```

---

## 🔒 Technical Details

### Security Considerations
- Cryptographically secure random number generation
- No data is stored or transmitted
- All processing happens locally
- No internet connection required

### Character Sets
- **Uppercase Letters**: A–Z  
- **Lowercase Letters**: a–z  
- **Digits**: 0–9  
- **Special Characters**: !"#$%&'()*+,-./:;<=>?@[\]^_`{|}~

### Supported Email Domains
- gmail.com  
- yahoo.com  
- outlook.com  
- hotmail.com  
- icloud.com  

---

## 🤝 Contributing

We welcome contributions to the EMONSEC Security Tools Suite!

1. Fork the repository  
2. Create a feature branch:  
   ```bash
   git checkout -b new-feature
   ```
3. Commit your changes:  
   ```bash
   git commit -am 'Add new feature'
   ```
4. Push to the branch:  
   ```bash
   git push origin new-feature
   ```
5. Submit a pull request

### 🔧 Areas for Improvement
- Additional password strength options  
- More email domain options  
- Export functionality for generated credentials  
- GUI version  
- Password strength meter  
- Bulk generation options  

---

## 📄 License

This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT).

---

## ⚠️ Disclaimer

This tool is intended for legitimate security purposes only. Please ensure you have proper authorization before using these tools on any system. The developers are not responsible for misuse of this software.

---

## 💬 Support

For questions, suggestions, or issues:
1. Check the built-in help section (Option 3 in main menu)  
2. Review the examples in this README  
3. Open an issue on the GitHub repository  

---

## 🕒 Version History

- **v1.0** – Initial release with password and email generation

---

> **Note**: This tool is developed for educational and professional security purposes. Always practice ethical hacking and obtain proper permissions before testing system.
