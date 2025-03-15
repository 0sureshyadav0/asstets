# मेरो सिनेमा

मेरो सिनेमा is a Flutter-based movie streaming app that allows users to browse, search, and watch Nepali movies. It supports authentication, favorite movie selection.

## Features

- **Movie Listing**: Browse and search for movies.
- **Movie Filtering**: Filter movies based on categories.
- **Movie Player**: Watch movies via YouTube Player.
- **Authentication**: Supports Google Sign-In.
- **Favorites**: Mark movies as favorites.
## 📱 Screenshots

### Preview

<center>
<div style="display:flex;gap:20px;">
<img src="https://github.com/0sureshyadav0/asstets/blob/main/merocinema1.png?raw=true" height = "30%" width="30%">
<img src="https://github.com/0sureshyadav0/asstets/blob/main/merocinema2.png?raw=true" height = "30%" width="30%"><br>
<img src="https://github.com/0sureshyadav0/asstets/blob/main/merocinema3.png?raw=true" height = "30%" width="30%">
</div>

</center>
## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/0sureshyadav0/mero_cinema.git
   ```
2. Navigate to the project folder:
   ```sh
   cd mero_cinema
   ```
3. Install dependencies:
   ```sh
   flutter pub get
   ```
4. Set up Firebase:
   - Add `google-services.json` (for Android) and `GoogleService-Info.plist` (for iOS) in the appropriate folders.
   - Enable Firestore, Authentication, and Storage in Firebase Console.
5. Run the app:
   ```sh
   flutter run
   ```

## Firebase Setup

Ensure you have the following Firebase services enabled:

- Firestore Database
- Authentication (Google)
- Firebase Storage

## Usage

- Sign in using Google authentication.
- Browse and search for movies.
- Filter movies by category.
- Mark movies as favorites.
- Watch movies using the built-in YouTube player.

## Contributing

1. Fork the repository.
2. Create a new branch:
   ```sh
   git checkout -b feature_name
   ```
3. Make changes and commit:
   ```sh
   git commit -m "Add new feature"
   ```
4. Push to your fork:
   ```sh
   git push origin feature_name
   ```
5. Submit a pull request.

## License

This project is licensed under the MIT License.

## Contact

For any inquiries or issues, contact us at [sureshyadav.info.np@gmail.com](mailto:sureshyadav.info.np@gmail.com).
