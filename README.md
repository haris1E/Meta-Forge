# Meta-Forge - Advanced SEO Meta Generator

## Overview

Meta-Forge is a powerful, cloud-based SEO meta tag generator that leverages Claude AI technology to create optimized metadata for websites, blogs, forums, and web applications. It helps boost search engine rankings by generating intelligent, keyword-rich meta tags and descriptions.

## Features

🎯 **AI-Powered Generation**
- Uses Claude AI for intelligent meta tag creation
- Analyzes content and generates contextually relevant metadata
- Supports multiple content types and industries

📱 **Responsive Design**
- Works seamlessly on desktop, tablet, and mobile devices
- Modern, intuitive user interface
- Real-time preview of generated meta tags

🔍 **SEO Optimization**
- Generates meta titles optimized for search engines
- Creates compelling meta descriptions
- Suggests relevant keywords and tags
- Follows best practices for meta tag length and format

⚡ **Fast & Efficient**
- Instant meta tag generation
- Batch processing capabilities
- Export results in multiple formats

🌐 **Multi-Language Support**
- Support for multiple languages
- Automatic language detection
- Localized meta tag generation

## Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection

### Usage

1. **Visit the Application**
   - Open `seo-meta-generator.html` in your web browser
   - Or visit the deployed instance at: https://indexhtml-mauve-one.vercel.app

2. **Generate Meta Tags**
   - Enter your content or URL
   - Select the content type
   - Choose target keywords
   - Click "Generate"

3. **Review & Export**
   - Preview generated meta tags
   - Copy individual tags or export as HTML
   - Implement on your website

## File Structure

```
Meta-Forge/
├── seo-meta-generator.html  # Main application file
├── README.md               # This file
├── CONTRIBUTING.md         # Contributing guidelines
├── CHANGELOG.md            # Version history
├── LICENSE                 # BSD 3-Clause License
└── .gitignore             # Git ignore rules
```

## API Integration

### Claude AI Integration

The application uses Anthropic's Claude API for intelligent meta tag generation.

```javascript
// Example API call
const response = await fetch('/api/generate-meta', {
  method: 'POST',
  headers: {
    'Content-Type': 'application/json',
  },
  body: JSON.stringify({
    content: 'Your content here',
    keywords: ['keyword1', 'keyword2'],
    language: 'en'
  })
});
```

## Configuration

### Environment Variables

Create a `.env` file with:

```env
VITE_CLAUDE_API_KEY=your_api_key_here
VITE_API_URL=http://localhost:3000
```

## Development

### Setup

```bash
# Clone the repository
git clone https://github.com/haris1E/Meta-Forge.git
cd Meta-Forge

# Install dependencies (if using build tools)
npm install

# Start development server
npm run dev
```

### Building

```bash
# Build for production
npm run build

# Preview production build
npm run preview
```

## Deployment

### Vercel

```bash
# Deploy to Vercel
vercel
```

### GitHub Pages

1. Push to GitHub
2. Enable GitHub Pages in repository settings
3. Select `main` branch as source

## Contributing

Contributions are welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct and the process for submitting pull requests.

## License

This project is licensed under the BSD 3-Clause License - see the [LICENSE](LICENSE) file for details.

## Support

- 📖 [Documentation](https://github.com/haris1E/Meta-Forge/wiki)
- 🐛 [Report Issues](https://github.com/haris1E/Meta-Forge/issues)
- 💬 [Discussions](https://github.com/haris1E/Meta-Forge/discussions)

## Acknowledgments

- Claude AI by Anthropic
- Built with modern web technologies
- Community contributions and feedback

## Roadmap

- [ ] Multi-language support expansion
- [ ] Advanced analytics dashboard
- [ ] API for programmatic access
- [ ] Batch processing for multiple URLs
- [ ] Integration with popular CMS platforms
- [ ] Browser extensions

---

Made with ❤️ by the Meta-Forge team
