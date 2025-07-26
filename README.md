# 🍳 Cooking Rota Manager

A modern, responsive web application for managing cooking schedules with rotating weekend partners. Perfect for shared houses, dormitories, or any group living situation where cooking duties need to be fairly distributed.

## ✨ Features

- **Smart Rotation System**: Automatic weekend partner rotation based on weekday pairs
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Flexible Group Management**: Add/remove people to customize for different groups
- **Week Navigation**: Easy browsing through past and future weeks
- **Modern UI**: Beautiful gradient design with smooth animations and hover effects
- **No Dependencies**: Pure HTML, CSS, and JavaScript - runs anywhere
- **Offline Ready**: No internet connection required after initial load

## 🚀 Demo

The application comes pre-configured with a 6-person setup but can be easily customized for any group size (minimum 4 people).

**Default Schedule Pattern:**
- **Monday & Tuesday**: Antonio & Zakir
- **Wednesday**: Kabuswe & Collins
- **Thursday**: Kabuswe & Skills
- **Friday**: Skills & Collins
- **Weekend**: Reuben + rotating partners from weekday pairs

## 🛠️ Installation

### Option 1: Direct Download
1. Download the `index.html` file
2. Open it in any modern web browser
3. Start using immediately!

### Option 2: Clone Repository
```bash
git clone https://github.com/Zakir176/cooking-rota-manager.git
cd cooking-rota-manager
# Open index.html in your browser
```

### Option 3: GitHub Pages
Deploy directly to GitHub Pages for easy sharing with your housemates:
1. Fork this repository
2. Go to Settings → Pages
3. Select "Deploy from a branch" and choose `main`
4. Your rota will be available at `https://Zakir176.github.io/cooking-rota-manager`

## 📱 Usage

### Initial Setup
1. **Default Configuration**: The app loads with a pre-configured 6-person group
2. **Custom Groups**: Remove default names and add your own people
3. **Generate Rota**: Click "Generate Rota" once you have at least 4 people

### Navigation
- **Week Controls**: Use Previous/Next Week buttons to see different weeks
- **Group Management**: Click "Change Group" to modify participants
- **Responsive Layout**: Automatically adapts to your screen size

### Understanding the Rotation
The weekend rotation follows this pattern:
- **Week 1**: Weekend person + Monday/Tuesday pair
- **Week 2**: Weekend person + Wednesday pair  
- **Week 3**: Weekend person + Friday pair
- **Week 4**: Cycle repeats

## 🎨 Customization

### Changing the Color Scheme
Edit the CSS variables in the `<style>` section:
```css
/* Main gradient colors */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* Accent colors */
color: #5a67d8; /* Primary blue */
border-left-color: #ed8936; /* Weekend orange */
```

### Modifying the Schedule Logic
The rotation logic is in the JavaScript section. Key functions:
- `getWeekdayPair()`: Defines weekday cooking pairs
- `getWeekendPartner()`: Handles weekend rotation
- `setupDefaultRota()`: Sets default configuration

## 🏠 Use Cases

- **Student Housing**: Perfect for university dormitories or shared student houses
- **Co-living Spaces**: Organize cooking duties in co-working/co-living environments
- **Family Scheduling**: Large families with older children sharing cooking responsibilities
- **Office Lunch Groups**: Teams taking turns preparing group meals
- **Community Kitchens**: Shared community spaces with rotating cooking duties

## 🔧 Technical Details

- **Frontend**: Pure HTML5, CSS3, JavaScript (ES6+)
- **Storage**: Browser memory (no persistent storage required)
- **Compatibility**: Modern browsers (Chrome, Firefox, Safari, Edge)
- **Size**: Single file under 15KB
- **Performance**: Lightweight with smooth animations

## 📋 Requirements

- Modern web browser with JavaScript enabled
- Minimum group size: 4 people
- Recommended group size: 4-8 people

## 🤝 Contributing

Contributions are welcome! Here are some ideas for enhancements:

- **Persistent Storage**: Add localStorage for saving configurations
- **Export Features**: Generate printable PDF schedules
- **Notification System**: Email/SMS reminders for cooking duties
- **Recipe Integration**: Link to recipe suggestions for each day
- **Shopping Lists**: Generate weekly shopping lists based on planned meals
- **Mobile App**: Progressive Web App (PWA) features

### Development Setup
1. Fork the repository
2. Make your changes to `index.html`
3. Test in multiple browsers
4. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspired by the need for fair cooking duty distribution in shared living spaces
- Built with modern web technologies for maximum compatibility
- Designed with user experience and accessibility in mind

## 📞 Support

If you encounter any issues or have suggestions:
1. Check the [Issues](https://github.com/Zakir176/cooking-rota-manager/issues) page
2. Create a new issue with detailed description
3. Include your browser version and group size for bug reports

## 🔄 Changelog

### v1.0.0
- Initial release with core rotation functionality
- Responsive design implementation
- Default 6-person configuration
- Week navigation system
- Dynamic group management

---

**Made with ❤️ for better shared living experiences**
