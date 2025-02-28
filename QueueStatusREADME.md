# 🚀 PaaloX App

PaaloX App is a Flutter application that allows users to check the real-time queue status of stores such as hospitals, barber salons, and other service providers. The app features a map-based UI to display store details and queue information without requiring authentication.

## ✨ Features

- 📊 **Real-time Queue Status:** View the current queue length at various stores.
- 🗺️ **Map Integration:** Display store locations on an interactive map.
- 🏪 **Store Details:** Get information about stores including name, address, and queue status.
- 🔳 **QR Code Support:** Scan and generate QR codes for queue management.
- 🔒 **No Authentication Required:** Users can access queue details without signing in.

## 🛠️ Technologies Used

- 🎯 **Flutter** - Cross-platform app development framework.
- 🌍 **OpenStreetMap API** - For displaying store locations.
- 📌 **QR Code Generator** - Using `QrImageView` for generating QR codes.
- 🏗️ **Dart** - Primary programming language.

## 📱 Screenshots

### Preview

<center>
<div style="display:flex;gap:20px;">
<img src="https://github.com/0sureshyadav0/asstets/blob/main/image1.png?raw=true" height = "20%" width="20%">
<img src="https://github.com/0sureshyadav0/asstets/blob/main/image2.png?raw=true" height = "20%" width="20%">
<img src="https://github.com/0sureshyadav0/asstets/blob/main/image3.png?raw=true" height = "20%" width="20%"><br>
<img src="https://github.com/0sureshyadav0/asstets/blob/main/image4.png?raw=true" height = "20%" width="20%">

   
</div>

</center>

## 📥 Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/0sureshyadav0/queue_status_.git
   ```
2. Navigate to the project directory:
   ```sh
   cd queue_status_
   ```
3. Install dependencies:
   ```sh
   flutter pub get
   ```
4. Run the application:
   ```sh
   flutter run
   ```

## 📂 Project Structure

```
queue_status_/
│── lib/
│   ├── main.dart  # Entry point of the application
│   ├── firebase_options.dart
│── screens/       # Contains UI screens
|   │── qr/
|   |   ├── qr_generator.dart
|   |   ├── qr_scanner.dart
│   ├── about.dart
│   ├── developer.dart
│   ├── home_screen.dart
│   ├── login.dart
│── assets/
│── pubspec.yaml   # Project dependencies
```

## 🤝 Contribution

Contributions are welcome! Feel free to fork the repository and submit a pull request.

## 👨‍💻 Developer

- 🧑 Suresh Yadav
- 🌐 [sureshyadav.info.np](sureshyadav.info.np)

## 📞 Contact

For any inquiries or support, feel free to reach out:

- 📧 Email: [sureshyadav.info.np@gmail.com](mailto:sureshyadav.info.np@gmail.com)

## 📜 License

This project is licensed under the MIT License.
