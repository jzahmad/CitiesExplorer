# Android City App

This Android application allows users to explore cities from different continents.

## Brief Summary

The app is structured around two main activities:

* **MainActivity:** Displays a list of continents for the user to choose from.
* **MainContinentActivity:** Displays a list of cities within the selected continent.

Each city is represented by a card-view in the `MainContinentActivity` that contains the city's name and an image. When
a user taps on a city card, they are taken to `CityInfoActivity` where they can view more information about the city
through different fragments:

* **NameFragment:** Displays the city's name.
* **ImageFragment:** Displays a larger image of the city.
* **LanFragment:** Displays the city's language.
* **PopFragment:** Displays the city's population.

## Tech Stack

* **Language:** Kotlin
* **Framework:** Android SDK
* **Technologies:**
* RecyclerView
* Fragments
* Intents
* ListView
* CardView

## Installation and Running

1. **Prerequisites:**
* Java Development Kit (JDK) installed and configured
* Android Studio installed and configured
* Android Emulator or physical device connected

2. **Clone the repository:**
```bash
git clone <repository_url>
    ```

    3. **Open the project in Android Studio:**
    * Launch Android Studio.
    * Click "Open an existing Android Studio project".
    * Select the project directory you cloned.

    4. **Install dependencies:**
    Android Studio will automatically download and install the necessary dependencies. If you encounter any issues, sync
    the project with Gradle files by clicking "File" > "Sync Project with Gradle Files".

    5. **Run the app:**
    * In Android Studio, click "Run" > "Run 'app'".
    * Choose an Android Emulator or a connected device.
    * The app will launch and display the list of continents.

    ## Configuration

    No specific configuration settings need to be adjusted.

    ## Testing

    * **Unit Tests:** The project includes basic unit tests for the `ExampleUnitTest` class in the `app/src/test/java`
    directory. You can run these tests in Android Studio by clicking "Run" > "Run 'allTests'".

    * **UI Tests:** No UI tests are included in this project.

    ## Contributing

    Contributions are welcome!

    * **Fork the repository.**
    * **Create a branch.**
    * **Make your changes.**
    * **Open a pull request.**

    ## Licensing

    This project is licensed under the MIT License. See the `LICENSE` file for more information.
