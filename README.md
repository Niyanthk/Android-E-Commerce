# 🛒 E-Commerce 🛍


## 📸 Screenshots

<table>
  <tr>
    <th>Adress</th>
    <th>Cart</th>
    <th>Home</th>
  </tr>
  <tr>
    <td><img src="https://github.com/KulkarniAtharva/E-Commerce-Android/blob/master/Screenshots/address.jpg" width="250px"></td>
    <td><img src="https://github.com/KulkarniAtharva/E-Commerce-Android/blob/master/Screenshots/cart.jpg" width="250px"></td>
    <td><img src="https://github.com/KulkarniAtharva/E-Commerce-Android/blob/master/Screenshots/home.jpg" width="250px"></td>
  </tr>
 
 <tr>
    <th>Navigation Drawer</th>
    <th>Order Summary</th>
    <th>Payment</th>
  </tr>
  <tr>
    <td><img src="https://github.com/KulkarniAtharva/E-Commerce-Android/blob/master/Screenshots/navigation%20drawer.jpg" width="250px"></td>
    <td><img src="https://github.com/KulkarniAtharva/E-Commerce-Android/blob/master/Screenshots/order%20summary.jpg" width="250px"></td>
    <td><img src="https://github.com/KulkarniAtharva/E-Commerce-Android/blob/master/Screenshots/payment.jpg" width="250px"></td>
  </tr>
  
  <tr>
    <th>Payment 2</th>
    <th>Sign In</th>
    <th>Sign Up</th>
  </tr>
  <tr>
    <td><img src="https://github.com/KulkarniAtharva/E-Commerce-Android/blob/master/Screenshots/payment2.jpg" width="250px"></td>
    <td><img src="https://github.com/KulkarniAtharva/E-Commerce-Android/blob/master/Screenshots/signin.jpg" width="250px"></td>
    <td><img src="https://github.com/KulkarniAtharva/E-Commerce-Android/blob/master/Screenshots/signup.jpg" width="250px"></td>
  </tr>
</table>

  
<BR><BR>
   
## Features

<BR><BR>
  
  
## Built With 🛠
- [Java](https://www.java.com/en/) - Most widely used programming language for Android development.
- [Coroutines](https://kotlinlang.org/docs/reference/coroutines-overview.html) - For asynchronous and more..
- [Android Architecture Components](https://developer.android.com/topic/libraries/architecture) - Collection of libraries that help you design robust, testable, and maintainable apps.
  - [LiveData](https://developer.android.com/topic/libraries/architecture/livedata) - Data objects that notify views when the underlying database changes.
  - [ViewModel](https://developer.android.com/topic/libraries/architecture/viewmodel) - Stores UI-related data that isn't destroyed on UI changes. 
  - [ViewBinding](https://developer.android.com/topic/libraries/view-binding) - Generates a binding class for each XML layout file present in that module and allows you to more easily write code that interacts with views.
- [Koin](https://insert-koin.io) - Dependency Injection Framework
- [Retrofit](https://square.github.io/retrofit/) - A type-safe HTTP client for Android and Java.
- [GSON](https://github.com/google/gson) - A Java serialization/deserialization library to convert Java Objects into JSON and back.
- [GSON Converter](https://github.com/square/retrofit/tree/master/retrofit-converters/gson) - A Converter which uses Gson for serialization to and from JSON.
- [OkHttp3](https://github.com/square/okhttp) -  For implementing interceptor, logging and mocking web server.
- [Glide](https://github.com/bumptech/glide) - An image loading and caching library for Android focused on smooth scrolling.
- [Material Components for Android](https://github.com/material-components/material-components-android) - Modular and customizable Material Design UI components for Android.

Broadcast receiver  <BR>
Room Persistence Library   <BR>



### Other Concepts included
- RecyclerView
- GridView
- CardView
- CircularImageView
- ImageSlider
- Fragments
- Passing data between activities, fragments
- SearchView
- SwipeRefresh
- BottomSheet

<BR><BR>
  
  
# Package Structure
    
    dev.atharvakulkarni.e_commerce   # Root Package
    .
    ├── data                # For data handling.
    │   ├── model           # Model classes
    │   ├── network         # Remote Data Handlers     
    |   │   ├── api         # Retrofit API for remote end point.
    │   └── repository      # Single source of data.
    |
    |
    ├── ui                  # Activity/View layer
    │   ├── main            # Main Screen Activity & ViewModel
    |   │   ├── adapter     # Adapter for RecyclerView
    |   │   ├── viewmodel   # ViewHolder for RecyclerView   
    │   └── details         # Detail Screen Activity and ViewModel
    |
    └── utils               # Utility Classes / Kotlin extensions
    
    
<BR><BR>
  
    
## 👨‍🔧 Architecture
This app uses [***MVVM (Model View View-Model)***](https://developer.android.com/jetpack/docs/guide#recommended-app-arch) architecture.

![](https://developer.android.com/topic/libraries/architecture/images/final-architecture.png)


