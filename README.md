# 🎓 Chichi Notes Portal

A modern, responsive Student Notes Portal designed to help students access study materials for various subjects. Built with vanilla HTML, CSS, and JavaScript.

## Features

✨ **User Authentication**
- Sign up with email and password
- Secure login system
- Password validation (minimum 6 characters)
- Duplicate email detection

📚 **Subject Library**
- Mathematics (Algebra, Geometry, Calculus, Statistics, Trigonometry)
- Social Studies (History, Geography, Civics, Economics)
- Chichewa (Vocabulary, Writing, Comprehension, Proverbs, Grammar)
- Biology (Cells, Digestion, Photosynthesis, Genetics, Ecosystems)
- Agriculture (Crop Production, Animal Husbandry, Soil Science, Pest Control)
- English (Grammar, Essay Writing, Comprehension, Literature, Letter Writing)

🎨 **Modern UI/UX**
- Gradient backgrounds with smooth animations
- Mobile-first responsive design
- Touch-optimized buttons and forms
- Loading states and error messages
- Smooth page transitions

💾 **Data Persistence**
- Local storage for user accounts
- Session management
- Persistent user data between visits

## Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No server or backend required for local use

### Installation

1. Clone the repository:
```bash
git clone https://github.com/chichiwest/Chichi_notes_porta.git
cd Chichi_notes_porta
```

2. Open `index.html` in your web browser

That's it! The application runs entirely in the browser.

## Usage

### Sign Up
1. Click "Create Account"
2. Enter your first name, second name, email, and password
3. Confirm your password
4. Click "Sign Up"

### Sign In
1. Enter your registered email
2. Enter your password
3. Click "Sign In"

### Access Notes
1. After signing in, you'll see the dashboard with 6 subject cards
2. Click on any subject to view its topics
3. Use the "Back" button to return to the dashboard
4. Click "Logout" to exit

## File Structure

```
Chichi_notes_porta/
├── index.html          # Main application file
└── README.md          # This file
```

## Technical Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Storage**: Browser LocalStorage API
- **Styling**: Custom CSS with animations and gradients

## Data Storage

User data is stored in the browser's LocalStorage under the key `students`. Each user object contains:
- First Name
- Second Name
- Email (used as unique identifier)
- Password (stored in plaintext - for development only)

⚠️ **Security Note**: This is a learning/demo project. In production, passwords should be hashed and authentication should use a proper backend with a secure database.

## Future Enhancements

- [ ] Backend integration (Firebase, Node.js, etc.)
- [ ] Encrypted password storage
- [ ] More detailed notes with content
- [ ] Search functionality
- [ ] Bookmarks/Favorites
- [ ] Progress tracking
- [ ] Quiz and assessment tools
- [ ] Teacher portal for content management
- [ ] Dark mode
- [ ] Multi-language support

## Browser Compatibility

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

## License

This project is open source and available under the MIT License.

## Contact

For questions or suggestions, please reach out through GitHub issues.

---

**Made with ❤️ for students in Malawi**
