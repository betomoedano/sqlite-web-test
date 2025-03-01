# Expo SQLite Web Support Example 🌐

This is an example project showcasing how to use SQLite in an [Expo](https://expo.dev) web application, powered by [Bun](https://bun.sh).

## Features

- SQLite database support for web platform
- Cross-platform compatibility (iOS, Android, Web)
- Example CRUD operations

## Getting Started

1. Install Bun if you haven't already:

   ```bash
   curl -fsSL https://bun.sh/install | bash
   ```

2. Install dependencies:

   ```bash
   bun install
   ```

3. Start the development server:
   ```bash
   bun run web
   ```

The app will open in your default browser. You can also run it on other platforms:

- Web: `bun run web`
- iOS: `bun run ios`
- Android: `bun run android`

## Project Structure

The main code is in the `app` directory, demonstrating:

- SQLite database initialization
- Basic CRUD operations
- Web-specific SQLite implementation
- Cross-platform data persistence

## Learn More

- [Expo SQLite Documentation](https://docs.expo.dev/versions/latest/sdk/sqlite/)

## Contributing

Feel free to open issues or submit pull requests if you find any bugs or have suggestions for improvements.
