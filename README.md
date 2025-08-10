# 🎴 Pokédass Manager

A comprehensive static HTML collection manager for tracking vintage 1997 Bandai Carddass Pokémon cards.

<img width="1474" height="904" alt="Screenshot 2025-08-10 alle 13 08 36" src="https://github.com/user-attachments/assets/c8b5f0d5-54b3-42c9-a24d-38adb9b7b1ae" />

## 🌟 About This Project

I created this project during my free time after diving into collecting vintage Pokémon Carddass cards from 1997. Many of these cards come directly from Japan through auctions—it's quite the adventure: bidding, winning, and then patiently waiting for packages to arrive across the globe! 
I wanted something more engaging and visual than a boring Excel spreadsheet to track my collection, and this is what came to life. It's designed to make collecting more organized, enjoyable, and efficient.

## 🎯 Why I Made It

**The Problem**: Managing a growing card collection with just spreadsheets is tedious and error-prone.

**The Solution**: A beautiful, interactive web interface that makes tracking your collection actually enjoyable:
- ✅ Visual tracking of owned cards
- 📦 Order management to avoid duplicate purchases  
- 🏆 Grading status tracking for serious collectors
- 💰 Price tracking and collection value management
- 📊 Real-time statistics and completion tracking
- 🌐 Multi-language support (English, Italian, Spanish)
- 🌙 Dark mode for late-night collection sessions

## 🚀 Key Features

### 📋 **Collection Management**
- **Owned Status**: Track which cards you physically have
- **Order Tracking**: Monitor cards you've ordered but haven't received yet
- **Grading System**: Record card conditions (Raw, PSA, BGS, CGC, SGC)
- **Price Tracking**: Enter purchase prices to track collection value
- **153 Cards Total**: All 151 original Pokémon + 2 special secret cards

### 💰 **Financial Tracking**
- **Multi-Currency Support**: EUR (€), USD ($), GBP (£), JPY (¥)
- **Collection Value**: Real-time total value calculation
- **Average Price**: Track average cost per card
- **Smart Calculations**: Only counts prices for owned cards
- **Currency Preferences**: Automatically saved and restored

### 🌐 **Multi-Language Support**
- **🇬🇧 English**: Full interface translation
- **🇮🇹 Italiano**: Complete Italian localization
- **🇪🇸 Español**: Full Spanish translation
- **Language Persistence**: Your choice is automatically saved
- **Localized Messages**: All alerts and confirmations translated

### 🔍 **Advanced Filtering & Search**
- Search by Pokémon name or card number
- Filter by type (Fire, Water, Electric, etc.)
- Filter by collection status (owned/ordered/missing)
- Filter by card type (standard/secret)
- Filter by grading status

### 📱 **Responsive Design**
- **Desktop Mode**: Full table view with all details
- **Mobile Mode**: Optimized card view for touch devices
- **Adaptive UI**: Automatically adjusts to your screen size

### 🌙 **Theme Options**
- **Light Theme**: Clean, bright interface
- **Dark Theme**: Easy on the eyes for extended use
- **Instant Toggle**: Switch themes with one click

### 📊 **Real-Time Statistics**
- Total cards in collection (153)
- Cards you own
- Cards you've ordered
- Missing cards count
- Completion percentage
- **NEW**: Total collection value
- **NEW**: Average price per card

### 💾 **Data Management**
- **Auto-Save**: Your data is automatically saved as you work
- **Export Options**: Backup to JSON, Excel, or CSV formats (includes prices)
- **Import Function**: Restore from previous backups (backward compatible)
- **Print Support**: Generate physical collection lists

## 🛠️ How It's Built

This is a **pure static HTML application**—no server required! Built with:
- **HTML5 & CSS3**: Modern, responsive design
- **Vanilla JavaScript**: Fast and lightweight functionality
- **Local Storage**: Browser-based data persistence
- **XLSX.js**: Excel export capabilities
- **Multi-language System**: Client-side translations

I used AI tools to accelerate development because life's too short to write everything from scratch! 🤖

## 💻 Demo

**🔗 [Try the Live Demo](https://stinocon.github.io/Pokedass-Manager/index.html)**

### ⚠️ Important Data Storage Information

This application stores your collection data **locally in your browser** using localStorage. Here's what you need to know:

#### ✅ **Your Data WILL Persist When:**
- Closing and reopening the browser
- Restarting your computer
- Navigating to other websites
- Regular browser usage

#### ❌ **Your Data WILL BE LOST When:**
- Clearing browser cache/cookies
- Using incognito/private browsing mode
- Switching to a different browser
- Using a different device
- Browser storage quota is exceeded

#### 🛡️ **Data Protection Tips:**
1. **Regular Backups**: Use the "💾 Backup" button to export your data as JSON
2. **Multiple Formats**: Export to Excel/CSV for external storage
3. **Cloud Storage**: Save backup files to Google Drive, Dropbox, etc.
4. **Before Maintenance**: Always backup before clearing browser data

#### 🔄 **Data Recovery:**
If you lose your data, you can restore it using the "📂 Import" function with any previously saved backup file.

## 📱 Mobile Experience

The mobile version has been completely optimized for touch devices:

- **Compact Controls**: 4-column grid layout for easy thumb navigation
- **Card View**: Swipe-friendly card interface alternative to table view
- **Fixed Bottom Menu**: Quick access to all functions
- **Touch-Optimized**: Larger buttons and checkboxes for better usability
- **Price Input**: Optimized number inputs for mobile keyboards

## 🎮 How to Use

1. **📖 Open the Page**: Load the HTML file in any modern browser
2. **🌐 Choose Language**: Select your preferred language (English/Italian/Spanish)
3. **💰 Set Currency**: Choose your currency (EUR/USD/GBP/JPY)
4. **🎯 Track Ownership**: Check "Owned" for cards you have
5. **📦 Monitor Orders**: Check "Ordered" for cards you've purchased but not received
6. **🏆 Record Grading**: Select grading status from dropdown (Raw, PSA, BGS, etc.)
7. **💵 Enter Prices**: Add purchase prices to track collection value
8. **🔍 Use Filters**: Find specific cards or view subsets of your collection
9. **💾 Backup Regularly**: Export your data to prevent loss
10. **📱 Go Mobile**: Switch to mobile mode for on-the-go collection management

## 🆕 Recent Updates

### Version 2.1 - Multi-Language & Financial Tracking
- **🌐 Multi-Language Support**: English, Italian, Spanish
- **💰 Price Tracking**: Enter and track card purchase prices
- **🏷️ Multi-Currency**: Support for EUR, USD, GBP, JPY
- **📊 Enhanced Statistics**: Total collection value and average price
- **🔄 Improved Export**: All formats now include price data
- **📱 Mobile Optimization**: Better price input on mobile devices
- **💾 Backward Compatibility**: Old backups automatically upgraded

## 🤝 Contributing

Got ideas? Found bugs? Want to contribute?

- 🐛 **Report Issues**: Open an issue on GitHub
- 💡 **Suggest Features**: Share your ideas in the discussions
- 🔧 **Submit PRs**: Fork, improve, and submit pull requests
- ⭐ **Star the Repo**: Show your support!

## ☕ Support the Project

If this tool has helped you organize your collection and you'd like to support its development, consider buying me a coffee! Your support helps keep the project alive and motivates me to add new features.

<div align="center">

[![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://www.paypal.com/paypalme/stefanoconter)

*Every contribution, no matter how small, is greatly appreciated! 🙏*

</div>

## 📄 License & Disclaimer

### 🎮 Trademark Notice
Pokémon, Pokémon character names, and related trademarks are the property of Nintendo, Creatures Inc., and Game Freak Inc. Bandai and related trademarks belong to their respective owners.

### ⚖️ Project License
This project is **not affiliated with, endorsed, or sponsored by** any of these entities. This is a fan-made tool created for recreational purposes only, with no commercial intent or profit.

All trademarks remain the property of their respective owners worldwide. No copyright or trademark infringement is intended.

---

<div align="center">

**Made with ❤️ for the Pokémon collecting community**

[🌟 Star this repo](../../stargazers) • [🐛 Report issues](../../issues) • [💬 Discussions](../../discussions) • [☕ Support](https://www.paypal.com/paypalme/stefanoconter)

</div>
