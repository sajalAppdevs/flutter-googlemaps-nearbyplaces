# Google Maps Nearby Places App

A Flutter application that helps users discover and explore interesting places in their vicinity using Google Maps. The app provides an interactive map interface with features like place search, favorites, directions, and detailed place information.

## Features

- 🗺️ Interactive Google Maps integration
- 🔍 Search for places with autocomplete suggestions
- 📍 View nearby places with detailed information
- ⭐ Save favorite places
- 🛣️ Get directions between locations
- 📱 Beautiful and responsive UI
- ⚡ Smooth animations and transitions
- 💫 Place details including ratings and reviews

## Prerequisites

- Flutter SDK (>=2.15.1 <3.0.0)
- Google Maps API Key
- Android Studio / VS Code
- Basic knowledge of Flutter development

## Dependencies

- google_maps_flutter: For Google Maps integration
- flutter_polyline_points: For drawing routes on the map
- http: For API calls
- flutter_riverpod: For state management
- fab_circular_menu: For floating action menu
- flutter_rating_stars: For place ratings
- flip_card: For place card animations
- lottie: For animations

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/flutter-googlemaps-nearbyplaces.git
   ```

2. Get dependencies:
   ```bash
   flutter pub get
   ```

3. Configure Google Maps API:
   - Get an API key from [Google Cloud Console](https://console.cloud.google.com)
   - Enable the following APIs:
     - Maps SDK for Android/iOS
     - Places API
     - Directions API
   - Replace `<yourkeyhere>` in `lib/services/map_services.dart` with your API key

4. Run the app:
   ```bash
   flutter run
   ```

## Project Structure

- `lib/screens/`: Contains the main UI screens
- `lib/services/`: Contains API and map services
- `lib/models/`: Contains data models
- `assets/`: Contains fonts, icons, and animation files

## Features in Detail

### Place Search
- Autocomplete suggestions while typing
- Search for specific locations
- View place details including address, ratings, and photos

### Navigation
- Get directions between two locations
- View route on the map
- Animated camera movements

### UI/UX
- Custom markers for locations
- Smooth animations for place cards
- Interactive floating action menu
- Custom fonts and styling

## Screenshots

![Screenshot_20220606-055028](https://user-images.githubusercontent.com/8137504/172486850-864ac272-6a0a-4775-add3-4c5271220c2c.png)
![Screenshot_20220606-054938](https://user-images.githubusercontent.com/8137504/172486852-a35ba6db-6438-4457-bfc3-25ea01720e12.png)
![Screenshot_20220606-054920](https://user-images.githubusercontent.com/8137504/172486856-b3b66457-85a0-4dcb-b9a2-ac159fc7988b.png)
![Screenshot_20220606-054909](https://user-images.githubusercontent.com/8137504/172486857-b2c1a8b5-206c-4e31-aee1-c242afbf0b42.png)
![Screenshot_20220606-054857](https://user-images.githubusercontent.com/8137504/172486860-d9ce76ad-e452-4f1b-96c8-4bf9523ce141.png)
![Screenshot_20220606-055428](https://user-images.githubusercontent.com/8137504/172486822-2ca62aa9-ef93-4802-8e17-77c94e19de6e.png)
![Screenshot_20220606-055329](https://user-images.githubusercontent.com/8137504/172486828-7b06c190-d173-4c1d-b5be-52e4e025a779.png)
![Screenshot_20220606-055258](https://user-images.githubusercontent.com/8137504/172486832-ab25cf9d-6870-4883-b5b4-2dda9d5199c6.png)
![Screenshot_20220606-055230](https://user-images.githubusercontent.com/8137504/172486835-13f11d42-a50e-44dd-aebc-ef4b1102bbf3.png)
![Screenshot_20220606-055138](https://user-images.githubusercontent.com/8137504/172486844-9a754824-34c8-447c-a462-908daa268307.png)
![Screenshot_20220606-055123](https://user-images.githubusercontent.com/8137504/172486845-b11627e6-00c6-480b-899f-088af63c0ab5.png)
![Screenshot_20220606-055100](https://user-images.githubusercontent.com/8137504/172486848-7dfad88e-0cab-4b37-b3a2-835974857d96.png)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.



