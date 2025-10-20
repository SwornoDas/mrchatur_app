# Welcome to your Expo app 👋

This is an [Expo](https://expo.dev) project created with [`create-expo-app`](https://www.npmjs.com/package/create-expo-app).

## Get started

1. Install dependencies

   ```bash
   npm install
   ```

2. Start the app

   ```bash
   # To start with all options (iOS, Android, and Web)
   npx expo start

   # To run specifically in web browser
   npx expo start --web
   ```

In the output, you'll find options to open the app in:

- Web browser (using `--web` flag)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go) mobile app
- [development build](https://docs.expo.dev/develop/development-builds/introduction/)

You can start developing by editing the files inside the **app** directory. This project uses [file-based routing](https://docs.expo.dev/router/introduction).

## Get a fresh project

When you're ready, run:

```bash
npm run reset-project
```

This command will move the starter code to the **app-example** directory and create a blank **app** directory where you can start developing.

## Web Development

When running the app in web mode (`npx expo start --web`), your app will open in your default web browser. The web version supports:

- Hot reloading for quick development
- Web-specific APIs and components
- Responsive design testing
- Browser developer tools integration

For web-specific configuration, you can modify:

- `app.json` for web-specific settings
- Use platform-specific code with `Platform.select({ web: ... })`
- Style adaptations for web using CSS media queries

## Learn more

To learn more about developing your project with Expo, look at the following resources:

- [Expo documentation](https://docs.expo.dev/): Learn fundamentals, or go into advanced topics with our [guides](https://docs.expo.dev/guides).
- [Learn Expo tutorial](https://docs.expo.dev/tutorial/introduction/): Follow a step-by-step tutorial where you'll create a project that runs on Android, iOS, and the web.
- [Expo Web Documentation](https://docs.expo.dev/workflow/web/): Learn more about web-specific features and configurations.

## Join the community

Join our community of developers creating universal apps.

- [Expo on GitHub](https://github.com/expo/expo): View our open source platform and contribute.
- [Discord community](https://chat.expo.dev): Chat with Expo users and ask questions.
