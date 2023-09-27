# TinNews: A Tinder-like News App 📰

TinNews is a sophisticated and user-friendly news application designed to deliver the latest news articles in a Tinder-like card stack interface. Users can swipe right to like an article or swipe left to dislike it, providing an interactive and engaging user experience. The app is built following the Google Component Architectural MVVM Pattern, ensuring a clean, scalable, and maintainable codebase.

## 🌟 Features
- **Tinder-like User Interface**: Utilizes `CardStackView` to present news articles in a swipeable card stack format.
- **Instagram-like User Experience**: Offers a smooth and intuitive user experience with modern design principles.
- **Offline Support**: Implements Room Database for local caching, allowing users to access articles even when offline.
- **Latest News**: Integrates with a RESTful endpoint using Retrofit to fetch the most recent news articles.
- **Navigation Component**: Employs JetPack navigation component for efficient in-app navigation.

## 🛠️ Tech Stack
- **MVVM Architecture**: Adopts Model-View-ViewModel pattern for a clear separation of concerns and improved testability.
- **LiveData**: Uses LiveData for lifecycle-aware data observation, ensuring UI consistency.
- **Retrofit**: Leverages Retrofit for type-safe HTTP client operations, simplifying network requests and response handling.
- **Room Database**: Implements Room for abstracting SQLite operations, providing a robust and optimized local database.
- **JetPack Navigation Component**: Utilizes this component for simplified and standardized in-app navigation.
- **CardStackView**: Implements this third-party library built on RecyclerView for the card stack interface.

## 📱 Demo
[demo](https://user-images.githubusercontent.com/85295108/190264323-b06596a1-d2ee-47ae-a893-82f6daa01595.gif)






