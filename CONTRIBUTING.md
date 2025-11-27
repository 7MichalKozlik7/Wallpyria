# Contributing to Wallpyria Website

Thank you for your interest in contributing to the Wallpyria website!

## How to Contribute

### Reporting Issues

If you find a bug or have a suggestion:

1. Check if the issue already exists in the [Issues](../../issues) section
2. If not, create a new issue with a clear description
3. Include screenshots if relevant
4. Specify your browser and operating system

### Translation Improvements

We welcome improvements to our translations! The website supports 9 languages:

- English (en)
- Polish (pl)
- German (de)
- French (fr)
- Spanish (es)
- Italian (it)
- Russian (ru)
- Japanese (ja)
- Chinese Simplified (zh-Hans)

Translation files are located in the `messages/` directory.

#### To suggest a translation fix:

1. Fork the repository
2. Edit the relevant `messages/{language}.json` file
3. Submit a pull request with a clear description of the change

### Code Contributions

For code contributions:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Test locally with `npm run dev`
5. Build to ensure no errors: `npm run build`
6. Commit your changes (`git commit -m 'Add amazing feature'`)
7. Push to the branch (`git push origin feature/amazing-feature`)
8. Open a Pull Request

## Development Setup

```bash
# Clone your fork
git clone https://github.com/YOUR_USERNAME/wallpyria-website.git

# Install dependencies
npm install

# Start development server
npm run dev

# Open http://localhost:3000
```

## Code Style

- Use TypeScript for all new code
- Follow existing code formatting
- Use meaningful variable and function names
- Add comments for complex logic

## Questions?

If you have questions, feel free to:

- Open an issue with the "question" label
- Contact us at support@wallpyria.app

Thank you for helping make Wallpyria better!
