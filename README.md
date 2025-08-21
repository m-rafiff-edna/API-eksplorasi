Luxury Jokes App 🎭
A Flutter app that fetches random jokes from a free API and displays them with a luxury-themed UI ✨.
The project demonstrates API fetching, animations (fade, shimmer), and modern UI design in Flutter.

🚀 Features
🎉 Fetch random 10 jokes from Official Joke API

✨ Shimmer loading effect while fetching jokes

🎭 Animated fade-in jokes list with luxury card styling

🌌 Gradient background & custom text themes

🔄 Refresh button with rotation animation


🛠️ Tech Stack
Flutter (Dart SDK)

HTTP package for API requests

Official Joke API as data source

⚙️ Installation
Clone this repository and run the app:

bash
Copy
Edit
# Clone repo
git clone https://github.com/m-rafiff-edna/API-eksplorasi.git

# Navigate into project
cd API-eksplorasi

# Get dependencies
flutter pub get

# Run the app
flutter run
📂 Project Structure
bash
Copy
Edit
lib/
 ├── main.dart        # Entry point of the app
 ├── JokeApp          # Main widget & theme
 ├── JokeListPage     # Fetches and displays jokes
 
🔗 API Reference
This project uses Official Joke API.
Example endpoint:

http
Copy
Edit
GET https://official-joke-api.appspot.com/jokes/ten
Response example:

json
Copy
Edit
[
  {
    "id": 1,
    "type": "general",
    "setup": "Why don’t scientists trust atoms?",
    "punchline": "Because they make up everything!"
  }
]
💡 Future Improvements
🔎 Add search or filter jokes by type

📌 Save favorite jokes locally

🌐 Add multi-language support

👨‍💻 Author
Developed with ❤️ by m-rafiff-edna

