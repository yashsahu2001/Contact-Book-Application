# Contact Book Application

## Description
The **Contact Book Application** is a Java-based program that allows users to manage their contacts. With this application, you can:
- Add new contacts with name, phone number, and email.
- Delete existing contacts by name.
- Search for a contact by name to view their details.

The application uses **Java Collections** (`HashMap`) to store and manage contacts efficiently.

## Features
- **Add a new contact**: Save contact details such as name, phone number, and email.
- **Delete a contact**: Remove a contact from the contact book by name.
- **Search for a contact**: Find and display contact details by searching for a name.
- **Display for contact**: Displays the information from the stored contact.
- **Data stored in memory**: Contacts are stored in a `HashMap` and persist for the duration of the program session.

## Technologies Used
- **Language**: Java
- **Collections**: HashMap

## Installation

### Prerequisites
- **Java JDK 8 or higher**: Ensure that you have Java installed on your machine. You can download it from [here](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html).

### Steps to Run the Project
1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/contact-book-app.git
    ```
2. Navigate to the project directory:
    ```bash
    cd contact-book-app
    ```
3. Compile the Java files:
    ```bash
    javac Contact.java ContactBook.java Main.java
    ```
4. Run the application:
    ```bash
    java Main
    ```

The program will start and prompt you to interact with the contact book. You can add, delete, and search for contacts using the options provided.

## Usage
1. Run the application using the `java Main` command.
2. You will be presented with a menu to choose an action:
    - **1**: Add a new contact
    - **2**: Delete a contact by name
    - **3**: Search for a contact by name
    - **4**: Display contact
    - **5**: Exit the program
3. Follow the on-screen instructions to add, delete, or search for contacts.
