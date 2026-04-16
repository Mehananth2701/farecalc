FareCalc – Travel Optimizer
 Overview

FareCalc is a simple Python-based ride fare calculator designed for a ride-sharing service like **CityCab**.
It calculates the total ride cost based on distance, vehicle type, and time of travel, including surge pricing during peak hours.

 Features

* Calculates fare based on distance (per km rate)
* Supports multiple vehicle types:

  * Economy
  * Premium
  * SUV
* Applies **surge pricing (1.5x)** during peak hours (5 PM – 8 PM)
* Handles invalid inputs with proper error messages
* Displays a clean and formatted ride receipt

---

 Technologies Used

* Python (Core Concepts)

  * Functions
  * Dictionary
  * Conditional Statements
  * Error Handling (try-except)

---

 How It Works

1. User enters:

   * Distance (in km)
   * Vehicle type
   * Travel time (hour)
2. The system:

   * Fetches rate from dictionary
   * Calculates base fare
   * Applies surge pricing if applicable
3. Displays final fare in receipt format

---

 How to Run the Project

1. Make sure Python is installed
2. Open terminal in project folder
3. Run the script:



---

 Sample Output
====== Ride Receipt ======
Distance Travelled : 10 km
Vehicle Type       : SUV
Travel Hour        : 18
Surge Applied      : YES (1.5x)
Total Fare         : ₹ 375.0

 Future Enhancements

* Add graphical user interface (GUI)
* Include more vehicle categories
* Add discount coupons
* Store ride history

---

 Author

Developed as a beginner-friendly Python project to understand real-world problem solving using programming concepts.

---
