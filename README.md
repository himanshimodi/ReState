Real Estate App using Expo, TypeScript, Appwrite, and Tailwind CSS

Introduction

Build a full-stack Real Estate application with React Native, featuring Google authentication, dynamic property listings, and user profiles. Designed with modern tools like Expo SDK 52, Appwrite, Tailwind CSS, and TypeScript for a seamless and scalable experience.

If you're getting started and need assistance or face any bugs, join our active Discord community with over 50k+ members. It's a place where people help each other out.

Features

Authentication with Google: Secure and seamless user sign-ins using Google’s authentication service.

Home Page: Displays the latest and recommended properties with powerful search and filter functionality.

Explore Page: Allows users to browse all types of properties with a clean and intuitive interface.

Property Details Page: Provides comprehensive information about individual properties, including images and key details.

Profile Page: Customizable user settings and profile management.

Centralized Data Fetching: Custom-built solution inspired by TanStack’s useQuery for efficient API calls.

And many more, including code architecture and reusability.

🤸 Quick Start

Follow these steps to set up the project locally on your machine.

Prerequisites

Make sure you have the following installed on your machine:

Git

Node.js

npm (Node Package Manager)

Cloning the Repository
git clone https://github.com/himanshimodi/ReState.git

Installation
npm install

Set Up Environment Variables

Create a new file named .env.local in the root of your project and add the following content:
EXPO_PUBLIC_APPWRITE_ENDPOINT=https://cloud.appwrite.io/v1
EXPO_PUBLIC_APPWRITE_PROJECT_ID=
EXPO_PUBLIC_APPWRITE_DATABASE_ID=
EXPO_PUBLIC_APPWRITE_GALLERIES_COLLECTION_ID=
EXPO_PUBLIC_APPWRITE_REVIEWS_COLLECTION_ID=
EXPO_PUBLIC_APPWRITE_AGENTS_COLLECTION_ID=
EXPO_PUBLIC_APPWRITE_PROPERTIES_COLLECTION_ID=

Replace the values with your actual Appwrite credentials. You can obtain these credentials by signing up & creating a new project on the Appwrite website.

Start the App
npx expo start

In the output, you'll find options to open the app in a:

1]Development build

2]Android emulator

3]iOS simulator

4]Expo Go, a limited sandbox for trying out app development with Expo
