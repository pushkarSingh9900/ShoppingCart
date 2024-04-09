# Shopping Cart Application

## Abstract
This document presents a JavaFX application designed to simulate a shopping cart. The application allows users to add items with different prices to the cart and view them in a list format. It provides a graphical user interface (GUI) for managing shopping cart interactions.

## I. Introduction
The Shopping Cart Application is developed using JavaFX, a platform for creating rich internet applications. The application aims to provide a user-friendly interface for managing shopping cart operations such as adding items and viewing them in a list.

## II. Prerequisites
Before running the application, users must ensure the following prerequisites are met:
- Java Development Kit (JDK) 8 or higher
- JavaFX SDK (included in JDK 8 until JDK 10, separate download for JDK 11 and later versions)

## III. Running the Application
To run the application, follow these steps:
1. Compile the Java file:
    ```
    javac Main.java
    ```
2. Run the compiled Java class:
    ```
    java Main
    ```

## IV. Usage
Upon launching the application, users will see a window titled "Shopping Cart" with buttons to add items. They can click on any "Add [Item] to Cart" button to add the corresponding item to the shopping cart. The shopping cart will display the added items along with their prices. The label above the shopping cart dynamically updates to show the number of items in the cart.

## V. Application Structure
The application comprises a single Java class `Main.java`, which includes the following methods:
- `start(Stage primaryStage)`: Initializes the JavaFX application window and layout.
- `createAddItemButton(String itemName, double itemPrice)`: Creates a button to add an item to the cart.
- `addItemToCart(String itemName, double itemPrice)`: Adds the specified item to the shopping cart.
- `updateCartLabel()`: Updates the label displaying the number of items in the cart.

## VI. Images
Below are screenshots demonstrating the user interface and functionality of the Shopping Cart Application:

- *Image1*: [Initial Window]
![Screenshot 1](/Source-image/Image1.png)

- *Image2*: [Adding Items to cart]
![Screenshot 2](/Source-image/Image2.png)

## VII. Conclusion
The Shopping Cart Application provides a straightforward example of building a GUI-based shopping cart using JavaFX. It offers a foundation for further customization and extension to meet specific requirements.

## VIII. License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## IX. Acknowledgments
The development of this application was inspired by the need for a simple and intuitive shopping cart interface using JavaFX.
