# Car Rental System with GUI

This is a **Java-based Car Rental System** with a **Graphical User Interface (GUI)** built using **Java Swing**. The program allows users to rent and return cars through a simple and intuitive interface.

---

## Features

### 1. **Rent a Car**
   - Enter your name.
   - Select an available car from the list.
   - Specify the number of rental days.
   - Confirm the rental.

### 2. **Return a Car**
   - Select a rented car from the list.
   - Confirm the return.

### 3. **Exit**
   - Close the application.

---

## How It Works

- The program uses **JFrame** for the main window, **JPanel** for organizing buttons, and **JOptionPane** for input dialogs.
- Cars are stored in a list, and their availability is tracked.
- The GUI provides buttons for renting, returning, and exiting.

---

## Code Structure

### Classes:
1. **Car**: Represents a car with attributes like `carId`, `brand`, `model`, and `basePricePerDay`.
2. **Customer**: Represents a customer with attributes like `customerId` and `name`.
3. **Rental**: Represents a rental transaction linking a car, customer, and rental days.
4. **CarRentalSystem**: Manages the list of cars, customers, and rentals, and provides methods for renting and returning cars.
5. **Main**: Contains the `main` method and implements the GUI using Java Swing.

---

## How to Run

1. **Prerequisites**: Ensure you have Java installed on your system.
2. **Download the Code**: Clone the repository or copy the code into a Java file (e.g., `Main.java`).
   ```bash
   git clone https://github.com/Pawan-Makhare/Car-Rental-System.git
   cd Car-Rental-System
   ```
3. **Compile and Run**:
   - Open a terminal or command prompt.
   - Navigate to the directory containing the file.
   - Compile the code:
     ```bash
     javac Main.java
     ```
   - Run the program:
     ```bash
     java Main
     ```
4. **Use the GUI**: Interact with the system using the buttons provided.

---

## Screenshots

(You can add screenshots of the GUI here if available.)

---

## Example Code

Here is the core Java code for the Car Rental System:

```java
public class Main {
    public static void main(String[] args) {
        CarRentalSystem rentalSystem = new CarRentalSystem();

        Car car1 = new Car("C001", "Toyota", "Camry", 60.0);
        Car car2 = new Car("C002", "Honda", "Accord", 70.0);
        Car car3 = new Car("C003", "Mahindra", "Thar", 150.0);
        rentalSystem.addCar(car1);
        rentalSystem.addCar(car2);
        rentalSystem.addCar(car3);

        rentalSystem.menu();
    }
}
```

---

## Future Enhancements

1. Add more features like viewing rental history or calculating total revenue.
2. Improve the GUI with additional styling and functionality.
3. Add a database to store car and customer information persistently.

---

## License

This project is open-source and available under the MIT License. Feel free to modify and distribute it as needed.

---

## Contact

For questions or feedback, feel free to reach out to [Your Email/Contact Info].

---

Enjoy using the Car Rental System! 🚗✨

