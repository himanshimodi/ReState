# Real Estate App using Expo, TypeScript, Appwrite, and Tailwind CSS

## Introduction
Build a full-stack Real Estate application with React Native, featuring Google authentication, dynamic property listings, and user profiles. Designed with modern tools like **Expo SDK 52, Appwrite, Tailwind CSS, and TypeScript** for a seamless and scalable experience.

If you're getting started and need assistance or face any bugs, join our active **Discord community with over 50k+ members**. It's a place where people help each other out.

## Features

- **Authentication with Google**: Secure and seamless user sign-ins using Google’s authentication service.
- **Home Page**: Displays the latest and recommended properties with powerful search and filter functionality.
- **Explore Page**: Allows users to browse all types of properties with a clean and intuitive interface.
- **Property Details Page**: Provides comprehensive information about individual properties, including images and key details.
- **Profile Page**: Customizable user settings and profile management.
- **Centralized Data Fetching**: Custom-built solution inspired by TanStack’s `useQuery` for efficient API calls.
- And many more, including **code architecture and reusability**.

## 🤸 Quick Start
Follow these steps to set up the project locally on your machine.

### Prerequisites
Make sure you have the following installed on your machine:

- Git
- Node.js
- npm (Node Package Manager)

### Cloning the Repository
```sh
git clone https://github.com/himanshimodi/ReState.git
cd react_native-restate

# App Setup for Expo and Appwrite Integration

## Installation

1. Clone the repository or download the project files.
2. Install the necessary dependencies using npm:
    ```bash
    npm install
    ```

## Set Up Environment Variables

1. Create a new file named `.env.local` in the root of your project.
2. Add the following content to the `.env.local` file:
    ```bash
    EXPO_PUBLIC_APPWRITE_ENDPOINT=https://cloud.appwrite.io/v1
    EXPO_PUBLIC_APPWRITE_PROJECT_ID=
    EXPO_PUBLIC_APPWRITE_DATABASE_ID=
    EXPO_PUBLIC_APPWRITE_GALLERIES_COLLECTION_ID=
    EXPO_PUBLIC_APPWRITE_REVIEWS_COLLECTION_ID=
    EXPO_PUBLIC_APPWRITE_AGENTS_COLLECTION_ID=
    EXPO_PUBLIC_APPWRITE_PROPERTIES_COLLECTION_ID=
    ```
3. Replace the placeholder values with your actual Appwrite credentials. To get these credentials, sign up and create a new project on the [Appwrite website](https://appwrite.io/).

## Start the App

To start the application, run the following command:
```bash
npx expo start

After running the above command, you will have several options to open the app:

Development build
Android emulator
iOS simulator
Expo Go, a limited sandbox for trying out app development with Expo
