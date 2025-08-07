## 📋 Table of Contents

1.  [Introduction](#introduction)
2.  [Tech Stack](#tech-stack)
3.  [Features](#features)
4.  [Quick Start](#quick-start)
5.  [Snippets (Code to Copy)](#snippets)
6.  [Assets](#links)
7.  [More](#more)

## 🤖 Introduction

Built with Expo, TypeScript, and Tailwind CSS, this app fetches movies and creates a popularity algorithm using Appwrite. It provides users with a seamless browsing experience, ranking movies based on various engagement metrics.

## ⚙️ Tech Stack

- Expo
- React Native
- Appwrite
- TypeScript
- Tailwind CSS

## 🔋 Features

👉 Real-time data  
👉 Home Page for featured/discover movies  
👉 Search Page  
👉 Popularity algorithm  

## 🤸 Quick Start

```bash
git clone https://github.com/Artur-Sahakyan/react-native-movie-app.git
cd rn-movie-app
npm install
```

### Set Up Environment Variables

Create a `.env` file and add:

```
EXPO_PUBLIC_MOVIE_API_KEY=your_api_key
EXPO_PUBLIC_APPWRITE_PROJECT_ID=your_project_id
EXPO_PUBLIC_APPWRITE_DATABASE_ID=your_db_id
EXPO_PUBLIC_APPWRITE_COLLECTION_ID=your_collection_id
```

### Run the Project

```bash
npx expo start
```

## 🕸️ Snippets

See `tailwind.config.js`, `app/globals.css`, and `interfaces/interfaces.d.ts` in the repo for examples.
