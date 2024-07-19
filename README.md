Catapult - Cat Knowledge Quiz & Catalog
Welcome to Catapult, an Android application designed to provide users with an engaging experience of learning about various cat breeds and testing their knowledge through quizzes. This README will guide you through the project setup, structure, and functionality.

Table of Contents
Project Overview
Features
Installation
Usage
Technologies Used
API Documentation
Contributing
License
Project Overview
Catapult is a Kotlin-based Android application that offers:

A catalog of various cat breeds.
Detailed information about each breed.
A photo gallery for each breed.
A knowledge quiz about cats.
A leaderboard to track quiz scores.
Features
1. Creating Local Account
On the first start, users must create a local account with the following details:
Name and surname
Nickname (no spaces, only letters, numbers, and underscores)
Valid email address
If the account already exists, users are directed to the main screen.
2. Catalog of Cat Breeds
List of breeds with a search option.
Detailed information about each breed.
Photo gallery of selected breeds.
Full-screen photo viewer with swipe functionality.
3. Cat Knowledge Quiz
20 questions displayed one by one in full screen.
Questions generated randomly from three main categories:
Guess the Fact
Guess the Cat
Left or Right Cat
Scoring and time-limited gameplay.
Option to post results to a global leaderboard.
4. Leaderboard
Global leaderboard displaying the best scores.
Sorted by category and overall performance.
5. Account Details
View current account information.
Edit account details with validation.
View historical quiz results and best scores.

Usage
Create an Account:

Launch the app and follow the on-screen instructions to create an account.
Explore Cat Breeds:

Use the catalog to browse and search for cat breeds.
Click on a breed to view detailed information and photos.
Take a Quiz:

Select the quiz option from the main menu.
Choose a category and start answering questions.
Submit your score to see how you rank on the leaderboard.
View Leaderboard:

Check the global leaderboard to see top scores.
Manage Account:

View and edit your account details from the profile section.
Technologies Used
Kotlin
Coroutines
Flow
Jetpack Compose
MVI Architecture
Jetpack Navigation
Retrofit
OkHttp
KotlinX Serialization
Jetpack Room
Jetpack DataStore
Hilt DI
Material Design 3
API Documentation
Cats API
Used for fetching cat breed information and images.
Example endpoint: {{cats_endpoint}}/v1/images/search?breed_ids=BREED_ID&format=json
Official documentation: The Cat API
Leaderboard API
Used for submitting and retrieving quiz results.
Example endpoints:
GET leaderboard: /leaderboard?category=Integer
POST leaderboard: /leaderboard
