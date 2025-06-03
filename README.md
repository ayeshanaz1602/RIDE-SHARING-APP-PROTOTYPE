COMPANY: CODTECH IT SOLUTIONS

NAME: AYESHA NAZNEEN

INTERN ID :CT04DL1293

DOMAIN: ANDROID DEVELOPMENT

DURATION: 4 WEEKS

MENTOR: NEELA SANTOSH

Ride-Sharing App Prototype
A simple and functional ride-sharing app prototype that demonstrates core features such as real-time location tracking, ride request creation, and driver detail viewing. Built with the Google Maps SDK for map functionalities and Firebase Realtime Database for backend support, this app serves as a solid foundation for developing a full-scale ride-hailing platform.

📱 Features
Live Location Tracking: View your current location on the map with real-time updates.
Ride Requesting: Send a ride request by specifying your current location as the pickup point.
Driver Information: Fetch and display driver details such as name, car model, and live location.
Google Maps Integration: Seamless integration with Google Maps for geolocation and UI.
Firebase Backend: Realtime data handling with Firebase Authentication and Realtime Database.

🔧 Tech Stack
Frontend: Native Android (Java)
Backend: Firebase Realtime Database, Firebase Authentication
Maps & Location: Google Maps SDK, FusedLocationProviderClient
Tools: Android SDK, VS Code, Firebase Console

🛠️ Installation & Setup
Clone the Repository:
bash
Copy code
git clone https://github.com/yourusername/ride-sharing-prototype.git
cd ride-sharing-prototype
Firebase Setup:
Create a new project on Firebase Console.
Add your Android app package name.
Download google-services.json and place it in the app/ directory.
Google Maps API Key:
Go to Google Cloud Console.
Create an API key and enable Maps SDK for Android.
Add the API key to AndroidManifest.xml.
Build & Run the App:
Use an Android device/emulator with location services enabled.
Grant location permissions when prompted.
The map should render your live location.

🧪 Usage
Launch the app.
Your current location is shown on the map.
Tap a "Request Ride" button (to be implemented in UI) to create a ride request.
The app stores the ride request in Firebase with pickup coordinates and user ID.
Driver data (mocked in Firebase) can be fetched to simulate driver assignment and details.

📂 Firebase Database Structure
json
Copy code
{
  "rides": {
    "ride123": {
      "user": "user123",
      "pickup": { "lat": 19.0760, "lng": 72.8777 },
      "driver": "driver456",
      "status": "requested"
    }
  },
  "drivers": {
    "driver456": {
      "name": "John",
      "car": "Tesla Model 3",
      "location": { "lat": 19.0800, "lng": 72.8800 }
    }
  }
}

OUTPUT

![image](https://github.com/user-attachments/assets/0d63d3ec-63d7-4068-a061-ff1173964813)


