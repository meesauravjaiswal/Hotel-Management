🏨 Hotel Management System – Java (Console Based)

A menu-driven Hotel Management System implemented in Java using Object-Oriented Programming and file serialization.
This project manages room bookings, food orders, billing, availability, and persistent storage of customer data.

🚀 Features
🛏️ Room Management

Four room categories:

Luxury Double Room (1–10)

Deluxe Double Room (11–30)

Luxury Single Room (31–40)

Deluxe Single Room (41–60)

Check availability of each room type

View room features (AC, bed type, breakfast, cost)

Book rooms with customer details

Checkout and free the room

🍽️ Food Ordering System

Order items directly for any booked room

Menu includes:

Sandwich – ₹50

Pasta – ₹60

Noodles – ₹70

Coke – ₹30

Each order is stored in a list and added to the final bill

🧾 Billing

Room cost based on room type

Food cost based on items ordered

Clean and formatted bill generation

💾 Data Persistence

Uses Java Serialization to store:

Room allocations

Customer details

Food orders

Data is saved in a backup file

Automatically loads data on startup

🧱 Project Structure
├── Main.java
├── Hotel.java
├── holder.java
├── Food.java
├── Singleroom.java
├── Doubleroom.java
├── NotAvailable.java
└── backup (auto-created on runtime)

📌 Technologies Used

Java (Core)

OOP Concepts

Inheritance

Polymorphism

Encapsulation

Composition

Exception Handling

Serialization (ObjectInputStream and ObjectOutputStream)

Multithreading (for saving backup)

▶️ How to Run

Clone the repository:

git clone https://github.com/meesauravjaiswal/Hotel-Management


Navigate to the folder:

cd Hotel-Management-Project-Java


Compile the project:

javac Main.java


Run the program:

java Main

📋 Menu Options (User Interface)
1. Display room details
2. Display room availability
3. Book a room
4. Order food
5. Checkout
6. Exit

🧠 Key Concepts Demonstrated

Object-Oriented Design with inheritance hierarchy (SingleRoom, DoubleRoom)

Persistent storage using serialization

Custom Exception (NotAvailable)

Thread-based asynchronous backup writing

Array-based room management logic

Menu-driven input via Scanner

📸 Sample Output
Enter your choice:
1.Display room details
2.Display room availability
3.Book
4.Order food
5.Checkout
6.Exit

🔮 Future Improvements (Optional for GitHub)

Add GUI using Swing / JavaFX

Use database instead of serialization

Implement online booking system

Add date-based billing and stay duration

Improve food menu with dynamic pricing

