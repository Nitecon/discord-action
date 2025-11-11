# Contributing to Discord Action

Thank you for considering contributing to this GitHub Action!

## Development Setup

1. Fork the repository
2. Clone your fork:
   ```bash
   git clone https://github.com/YOUR_USERNAME/discord-action.git
   cd discord-action
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

## Making Changes

1. Create a new branch for your feature or bugfix:
   ```bash
   git checkout -b feature/your-feature-name
   ```

2. Make your changes to `index.js`

3. Build the action:
   ```bash
   npm run build
   ```

4. Test your changes locally (see Testing section below)

5. Commit your changes:
   ```bash
   git add .
   git commit -m "Description of your changes"
   ```

6. Push to your fork and create a Pull Request

## Testing

Since this is a GitHub Action that relies on GitHub context and Discord webhooks, full integration testing requires:

1. A Discord webhook URL
2. Running in a GitHub Actions environment

For local testing:
- Verify the code syntax: `node -c index.js`
- Check the build: `npm run build`
- Validate no npm vulnerabilities: `npm audit`

## Code Style

- Use clear, descriptive variable names
- Add JSDoc comments for functions
- Follow the existing code structure
- Keep functions focused and modular

## Submitting Pull Requests

1. Ensure your code builds without errors: `npm run build`
2. Update documentation if you're adding new features
3. Include a clear description of the changes in your PR
4. Link any related issues

## Questions?

Feel free to open an issue for questions or discussions about contributing!
