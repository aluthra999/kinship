# Kinship - Punjabi Relationship Names Learning App

A beautiful, mobile-first web application for learning Indian Punjabi relationship names (rishte). Perfect for anyone wanting to understand and memorize the rich vocabulary of family relationships in Punjabi culture.

![Punjabi Relations App](https://img.shields.io/badge/version-1.0.0-orange) ![License](https://img.shields.io/badge/license-MIT-blue) ![Mobile Friendly](https://img.shields.io/badge/mobile-friendly-green)

## ✨ Features

### 📚 Learn Mode
- **45+ Relationship Names** covering all major family connections
- **Smart Search** - Find relationships instantly by English or Punjabi names
- **Category Filters** - Browse by:
  - Paternal (Father's side)
  - Maternal (Mother's side)
  - Siblings
  - Husband's Family
  - Wife's Family
  - Children & Grandchildren
  - Cousins
  - Immediate Family
  - Others
- **Beautiful Cards** - Each relationship displayed with English description, Punjabi name (Gurmukhi + Roman script), and category tag

### 🎯 Quiz Mode
- **10 Random Questions** per quiz session
- **Bidirectional Testing** - Questions alternate between English→Punjabi and Punjabi→English
- **Instant Feedback** - Correct/incorrect answers highlighted in real-time
- **Smart Answer Selection** - Wrong answers grouped from the same category for realistic difficulty
- **Score Tracking** - See your progress and final results with encouraging messages
- **Retry Anytime** - Take the quiz as many times as you want

### 🎨 Design Highlights
- **Warm Cultural Aesthetic** - Rich orange and gold colors inspired by Punjabi culture
- **Typewriter Effect** - Dynamic header with rotating texts including time-based greetings
- **Elegant Typography** - Playfair Display for headings, Karla for readability
- **Smooth Animations** - Fade-ins, hover effects, and seamless transitions
- **Mobile-Optimized** - Fully responsive design that works perfectly on all screen sizes
- **Intuitive Navigation** - Easy switching between Learn and Quiz modes


## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS Grid, Flexbox, and animations
- **Vanilla JavaScript** - No frameworks, pure ES6+ JavaScript
- **Google Fonts** - Playfair Display & Karla

## 📦 Installation

### Option 1: Direct Usage
Simply download the `punjabi-relations.html` file and open it in any modern web browser. No installation or build process required!

### Option 2: Clone Repository
```bash
git clone https://github.com/yourusername/punjabi-relations.git
cd kinship
```

Then open `kinship.html` in your browser.

### Option 3: GitHub Pages
Fork this repository and enable GitHub Pages in Settings to host your own version online.

## 💻 Usage

1. **Learn Mode**: Use the search bar to find specific relationships or click on category filters to browse by family type
2. **Quiz Mode**: Click the "Quiz" button to test your knowledge with 10 random questions
3. **Mobile Access**: The app is fully responsive and works great on phones and tablets

## 🎓 Relationship Categories Included

- **Paternal Relations**: Dada, Dadi, Taya, Chacha, Bua, and more
- **Maternal Relations**: Nana, Nani, Mama, Mami, Masi, and more
- **Siblings**: Veer, Bhra, Bhen, Bhabhi, Jeeja
- **In-Laws**: Saura, Sass, Devar, Nanad, Jeth, Sala, Sali
- **Children**: Puttar, Dhee, Nooh, Jawayi, Pota, Poti
- **Cousins**: Chachera, Phupera, Mamera, and variations
- **Immediate Family**: Pita, Mata, Pati, Patni

## 🤝 Contributing

Contributions are welcome! Here are some ways you can help:

- Add more relationship names
- Improve translations
- Add audio pronunciations
- Enhance UI/UX
- Report bugs
- Suggest new features

### How to Contribute
1. Fork the repository
2. Create a new branch (`git checkout -b feature/improvement`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add new feature'`)
5. Push to the branch (`git push origin feature/improvement`)
6. Create a Pull Request

## 📝 Adding New Relationships

To add new relationships, edit the `relationships` array in the JavaScript section:

```javascript
const relationships = [
    { 
        english: "Relationship in English", 
        punjabi: "ਪੰਜਾਬੀ (Romanized)", 
        category: "Category" 
    },
    // Add more relationships here
];
```

## 🐛 Known Issues

None at the moment! Please report any bugs in the [Issues](https://github.com/yourusername/punjabi-relations/issues) section.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👏 Acknowledgments

- Inspired by the need to preserve and share Punjabi cultural knowledge
- Thanks to all contributors and users
- Special thanks to the Punjabi community for cultural insights

## 📧 Contact

For questions, suggestions, or feedback:
- Create an issue on GitHub

## 🌟 Show Your Support

If you find this project helpful, please consider:
- ⭐ Starring the repository
- 🍴 Forking it to contribute
- 📢 Sharing it with friends and family

---

Made with ❤️ for the Punjabi community
