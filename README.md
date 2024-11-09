StocksApp
StocksApp is a Kotlin-based stock portfolio tracking application designed for individual investors and traders to monitor stock prices in real-time and manage their investments. Built with a user-friendly interface, it utilizes modern Android development tools for a seamless user experience.

#Features
Real-time Stock Data: Track live stock prices using data from the Finnhub API.
Portfolio Management: Allows users to manage their stock investments and monitor changes over time.
User-Friendly UI: Incorporates RecyclerView for organized data display.
Local Data Storage: Utilizes Room Database for efficient local data management.
Multi-language Support: Available in English and Hebrew for localized experience.
Modern Android Tools: Integrates Dagger-Hilt for dependency injection and Kotlin Coroutines for efficient asynchronous operations.
#Tech Stack
Language: Kotlin
Libraries:
Retrofit for API integration with Finnhub
Room Database for local storage
Dagger-Hilt for dependency injection
LiveData for reactive programming
Kotlin Coroutines for asynchronous tasks
#Getting Started
##Prerequisites
Android Studio (latest version recommended)
A Finnhub API key for real-time stock data
##Installation
Clone the repository:
bash
Copy code
git clone https://github.com/yourusername/StocksApp.git
cd StocksApp
Open the project in Android Studio.
Add your Finnhub API key in ApiService.kt.
Build and run the app on an Android device or emulator.
##Usage
Add stocks to your portfolio to monitor their performance.
View live stock prices and track your portfolio's value over time.
Switch between English and Hebrew language options for localized support.
##Contributing
Contributions are welcome! Please submit a pull request or open an issue for feature requests and bug fixes.
