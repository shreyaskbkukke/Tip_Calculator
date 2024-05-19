**Tip Calculator App for Android**

This is a user-friendly Tip Calculator app built with Jetpack Compose for Android. It allows you to easily calculate the tip amount for your restaurant bill, taking into account the bill amount, tip percentage, and optional round-up preference.

**Features:**

* **Clear and concise interface:** The app features a clean and modern design with an intuitive layout for easy navigation.
* **Effortless calculation:** Enter the bill amount and tip percentage, and the app instantly displays the calculated tip amount.
* **Round-up option:** Choose to round the tip up to the nearest whole number for convenience.
* **Multilingual support (potential):** The app can potentially be adapted to display tip amounts in different currencies based on user locale (not currently implemented in this code example).

**Getting Started**

1. **Clone the repository** or download the source code.
2. **Open the project in Android Studio.** Ensure you have the latest Android SDK and tools installed.
3. **Run the app** on an Android device or emulator.

**Code Structure**

The code is organized into well-defined composable functions:

* `MainActivity`: The entry point of the app, setting up the content using Jetpack Compose.
* `TipCalculatorApp`: The main composable function that displays the entire tip calculator UI.
* `EditNumberField`: A custom composable for text fields with labels and leading icons, specifically designed for entering numerical data.
* `RoundTheTipRow`: A composable function for the row displaying the round-up tip toggle.
* `calculateTip`: A function that calculates the tip amount based on bill amount, tip percentage, and round-up option.

**Dependencies**

The app relies on the following libraries:

* Jetpack Compose
* AndroidX libraries (Activity, Material3)

**License**

This project is available under the Apache License 2.0. See the LICENSE file for more details.

**Contributing**

We welcome your contributions! Feel free to fork the repository, make changes, and submit pull requests.

**Here's what the Tip Calculator app might look like:**

![te](https://github.com/shreyaskbkukke/Tip_Calculator/assets/96857515/dbf6ec31-7fba-446a-8565-5b7378388b01)


**Note:** This is just a visual representation based on the code. The actual appearance might differ based on your theme or device.
