# ReadMe.md

# Gutenberg Book Explorer

## Java Programming – Assignment 2

### Project Description
Gutenberg Book Explorer is a Java console application that uses JSoup to retrieve book information from Books to Scrape and manage a personal reading list.

**Website:** https://books.toscrape.com/

### Objective
The objective of this project is to develop a Java application that connects to a website, extracts book information, allows users to search for books, and manages a personal reading list.

### Technologies Used
- Java 17
- Apache Maven
- JSoup 1.21.2
- Visual Studio Code

### Website Replacement
The original assignment uses Project Gutenberg. However, Project Gutenberg was unavailable for maintenance, so Books to Scrape was selected as an alternative website for web scraping.

### Project Requirements

The application includes the following features:

1. Explore Books.
2. Search Books by Title.
3. Search Books by Author.
4. Add Books to Reading List.
5. View Reading List.
6. Remove a Book.
7. Display Book Details.
8. Exit the Application.

### Programming Concepts

**1. Arrays**
Fixed-size arrays are used to store books and manage the reading list. ArrayList is not used.

**2. Loops**
Do-while and for loops are used to display the menu and process books.

**3. Conditions**
If/else statements are used for decision-making and input validation.

**4. Methods**
The application contains multiple user-defined methods.

**5. Method Overloading**
Two searchBook methods are implemented with different parameters.

**6. JSoup**
JSoup is used to connect to Books to Scrape and extract information from HTML.

**7. Scanner**
Scanner is used to receive input from the user.

**8. Error Handling**
The program handles connection errors, invalid input, empty results, and full reading lists.

### Data Extracted

The application extracts:
- Book Title
- Price
- Availability
- Rating
- Book URL

**Note:** The standard book catalog does not provide author names. Therefore, the author search option displays a notice explaining this limitation.

### Project Structure

```text
GutenbergBookExplorer/
│
├── pom.xml
├── README.md
│
└── src/
    └── main/
        └── java/
            └── com/
                └── student/
                    └── App.java
```

### How to Run the Project

**Requirements:**
- JDK 17 or later
- Apache Maven
- Visual Studio Code
- Internet connection

**Steps:**

1. Open the project in Visual Studio Code.
2. Open the terminal.
3. Run:

```bash
mvn clean compile
```

4. Run the application:

```bash
mvn exec:java -Dexec.mainClass="com.student.App"
```

5. Follow the menu instructions.

### Conclusion

This project demonstrates the use of Java, JSoup, and Maven to retrieve book information from a website and manage a personal reading list.

It also demonstrates important Java programming concepts, including arrays, loops, conditions, methods, method overloading, and exception handling.
