# Catapult - Cat Knowledge Quiz & Catalog

Welcome to **Catapult**, an Android application designed to provide users with an engaging experience of learning about various cat breeds and testing their knowledge through quizzes. This README will guide you through the project setup, structure, and functionality.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Technologies Used](#technologies-used)
6. [API Documentation](#api-documentation)
7. [Contributing](#contributing)
8. [License](#license)

## Project Overview

**Catapult** is a Kotlin-based Android application that offers:
- A catalog of various cat breeds.
- Detailed information about each breed.
- A photo gallery for each breed.
- A knowledge quiz about cats.
- A leaderboard to track quiz scores.

## Features

### 1. Creating Local Account
- On the first start, users must create a local account with the following details:
  - Name and surname
  - Nickname (no spaces, only letters, numbers, and underscores)
  - Valid email address
- If the account already exists, users are directed to the main screen.

### 2. Catalog of Cat Breeds
- List of breeds with a search option.
- Detailed information about each breed.
- Photo gallery of selected breeds.
- Full-screen photo viewer with swipe functionality.

### 3. Cat Knowledge Quiz
- 20 questions displayed one by one in full screen.
- Questions generated randomly from three main categories:
  - Guess the Fact
  - Guess the Cat
  - Left or Right Cat
- Scoring and time-limited gameplay.
- Option to post results to a global leaderboard.

### 4. Leaderboard
- Global leaderboard displaying the best scores.
- Sorted by category and overall performance.

### 5. Account Details
- View current account information.
- Edit account details with validation.
- View historical quiz results and best scores.
