# 😂 Random Joke Generator

A fun and interactive web application that generates random jokes using the [JokeAPI](https://jokeapi.dev/).

## Features

✨ **Features Included:**
- 🎭 Random joke generation from multiple categories
- 🏷️ Category filtering (General, Knock-Knock, Programming, Miscellaneous)
- 📋 Copy jokes to clipboard
- 📤 Share jokes (native share on mobile devices)
- 🎨 Beautiful, responsive UI
- ⚡ Real-time API integration
- 🔄 Filter by joke type (single or two-part)
- 📱 Mobile-friendly design

## Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Aravind102030/A10.git
cd A10/joke-generator
```

2. Open `index.html` in your browser:
```bash
open index.html
```

Or simply double-click the `index.html` file.

## Usage

1. **Get a Joke**: Click the "Get a Joke" button to fetch a random joke
2. **Filter by Category**: Select a category from the dropdown
3. **Filter by Type**: Check/uncheck joke types (Single or Two-Part)
4. **Copy**: Click "Copy" to copy the joke to your clipboard
5. **Share**: Click "Share" to share the joke (works best on mobile)

## API

This project uses [JokeAPI v2](https://jokeapi.dev/), a free API with:
- No authentication required
- Multiple joke categories
- JSON responses
- CORS enabled

### API Endpoint
```
https://v2.jokeapi.dev/joke/{category}/random?type={type}&format=json
```

## File Structure

```
joke-generator/
├── index.html       # Main HTML file
├── styles.css       # Styling
├── script.js        # JavaScript functionality
└── README.md        # Documentation
```

## Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

## Troubleshooting

**"No jokes found for selected filters"**
- Try selecting different joke types or categories
- Ensure you have internet connection

**Copy not working**
- Check if your browser supports the Clipboard API
- Try using the Share button instead

## Future Enhancements

- [ ] Joke history
- [ ] Favorite jokes storage (LocalStorage)
- [ ] Dark mode
- [ ] Joke rating system
- [ ] Custom API integration
- [ ] Export jokes as PDF

## License

MIT License - Feel free to use this project for any purpose!

## Credits

- [JokeAPI](https://jokeapi.dev/) - Free joke API
- Icons: Unicode emoji

---

**Made with ❤️ by Aravind102030**