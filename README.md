# SPSGP-79993-Virtual-Internship---Android-Application-Development-Using-Kotlin

This repository contains two Android applications developed as part of a virtual internship focusing on Android application development using Kotlin. The applications utilize modern libraries and follow best practices in Android development.

## Projects Overview

### 1. **Nearby Places Finder**

This project is a single-activity Android application that leverages the Google Places API to fetch and display nearby places. The app supports three categories: Cafes, Bars, and Restaurants. It displays a paged list of places along with ratings and an indicator of whether the place is open or closed. Users can also view the location on a map by selecting an item from the list.

#### Key Features:
- **Device Location Access**: Fetch nearby places based on the user’s location.
- **Category Filter**: Choose between Cafes, Bars, and Restaurants.
- **Paging Support**: Efficient loading of place listings.
- **Caching**: Prevent multiple API calls for the same location/page.
- **Place Details**: Display the place rating and an open/closed indicator.
- **Map Integration**: View selected places on a map.

#### Libraries Used:
- **Koin** for dependency injection.
- **Coroutines** for multithreading.
- **Retrofit** for API requests.
- **Navigation** for handling navigation.
- **DataBinding** for binding data to views.
- **Paging** for handling paginated lists.
- **Moshi** for JSON parsing.
- **Timber** for logging.
- **Glide** for image loading.
- **SwipeRefreshLayout** for pull-to-refresh.
- **ConstraintLayout** for flexible layouts.
- **Lottie** for animations.
- **CardView** for displaying card-like UI components.
- **KTX** for Kotlin extensions.
- **Google Play Services** for accessing Google APIs.
- **Espresso** for instrumented testing.
- **Mockito** for unit testing.

#### Functionality:
- Fetches nearby places using the device’s location.
- Displays place details, including ratings and open/closed status.
- Caches results to minimize API calls.
- Integrates maps for viewing the location of selected places.

---

### 2. **Grocery List App**

The Grocery List app is designed to help users keep track of groceries they need to purchase. It provides a simple interface where users can add grocery items and mark them as completed once purchased.

#### Key Features:
- **Add Groceries**: Input items that need to be purchased.
- **Mark as Completed**: Check off items once purchased.
- **Minimalistic UI**: Simple and easy-to-use design.

#### Libraries Used:
- **ConstraintLayout** for layout design.
- **DataBinding** for connecting UI components to the underlying logic.
- **Paging** for handling large lists of grocery items.
- **Navigation** for moving between screens.
- **Kotlin** for business logic implementation.

#### Functionality:
- Allows users to add and manage grocery items.
- Users can mark items as completed after purchase.

---


## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

### Video Demonstrations:
For video demonstrations of both apps, please refer to the following link:  
[Project Videos](https://drive.google.com/drive/folders/1_X8SLXs27EIHxMGAceDJTtuUSm8HISkN?usp=sharing)


---

Feel free to explore, modify, and use the code in this repository as per the license terms. Contributions are welcome!

---

### Contact
If you have any questions, feel free to reach out.
