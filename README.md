
# WishList Android App

This is a simple Android app that allows users to create and manage their personal wishlist. The app uses Kotlin and Jetpack components to provide an efficient and user-friendly experience. Wishes are stored in a local Room Database for persistent data management.

* Features
- Add new wishes to the list.
- View all stored wishes in a list.
- Edit and remove wishes from the list.
- Data is persisted using Room Database, so your wishlist is saved even when you close the app.

* Technologies Used
- **Kotlin**: The programming language used to build the app.
- **Jetpack**: Utilized for UI components and architecture patterns.
  - **Room Database**: Used for local storage to save wishes.

* Prerequisites
- Android Studio
- Kotlin (latest version)
- Android SDK

* Room Database
- The app uses the Room persistence library to store wishes locally.
- The database has entities representing wishes and a DAO for performing database operations.
