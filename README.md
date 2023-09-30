# React Native To-Do App

This is a basic to-do list app built using React Native. It allows users to create, update, and delete tasks, as well as mark tasks as completed. This README will guide you through setting up the project and running it in your local development environment.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js and npm installed on your development machine. You can download them from [nodejs.org](https://nodejs.org/).
- Expo CLI installed globally. You can install it using npm by running the following command:

```bash
npm install -g expo-cli
```

## Getting Started

Follow these steps to get the app up and running on your local machine:

1. Clone the repository:

```bash
git clone https://github.com/shenaltissera/todo_app_react_native.git
```

2. Navigate to the project directory:

```bash
cd react-native-todo-app
```

3. Install project dependencies:

```bash
npm install
```

4. Start the development server:

```bash
expo start
```

This will start the Expo development server and open a web page in your default browser. You can use this web page to launch the app on an emulator/simulator or a physical device.

5. To run the app on an emulator/simulator, press `a` for Android or `i` for iOS in the terminal where the Expo server is running.

6. To run the app on a physical device, install the Expo Go app from the App Store (iOS) or Google Play Store (Android). Scan the QR code displayed in the terminal with the Expo Go app.

## Project Structure

The project structure is organized as follows:

- `App.js`: The main entry point of the application.
- `components/`: Contains reusable components used in the app.
- `screens/`: Contains the different screens of the app (e.g., HomeScreen, AddTaskScreen).
- `utils/`: Contains utility functions and constants.
- `data/`: Contains a sample data file to initialize the task list.

## Features

- Create a new task with a title and description.
- Edit existing tasks.
- Mark tasks as completed.
- Delete tasks.
- View a list of tasks on the home screen.

## Technologies Used

- React Native: A JavaScript framework for building native mobile applications.
- Expo: A framework and platform for building and deploying React Native applications.
- AsyncStorage: A simple, unencrypted, asynchronous, persistent, key-value storage system.

## Contributing

If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your fork.
5. Submit a pull request with a clear description of your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- This project was inspired by various to-do list apps and tutorials in the React Native community.
- Special thanks to the React Native and Expo teams for their fantastic work.

## Contact

If you have any questions or need further assistance, feel free to contact us at judeshenal.st@gmail.com

Happy coding!
