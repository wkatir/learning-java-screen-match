# ScreenMatch

ScreenMatch is a Java-based project designed to explore and demonstrate various Java programming concepts, including object-oriented programming (OOP), API integration, file handling, and sorting mechanisms. The project provides functionalities such as searching for movie details, managing a list of titles, and calculating durations. It is an educational tool aimed at enhancing Java development skills.

## Features

- **Movie Search via OMDB API**: Search for movie details by providing a title. The program fetches movie information from the OMDB API and processes it using the Gson library.
- **Data Storage**: Saves movie details as JSON to a file for later use.
- **Title Management**: Allows the addition, evaluation, and sorting of movies and series based on various criteria.
- **Recommendation Filtering**: Provides basic filtering recommendations for titles and episodes.
- **Time Calculation**: Calculates the total duration of movies and series added to the list.
- **Sorting**: Demonstrates sorting of titles and lists by attributes such as release date.

## Learning Objectives

This project was created as a learning tool for the following Java concepts:

1. **Object-Oriented Programming (OOP)**:
   - Classes and Objects
   - Inheritance and Polymorphism
   - Interfaces

2. **API Integration**:
   - Making HTTP requests using `HttpClient`
   - Parsing JSON responses using Gson

3. **File Handling**:
   - Reading and writing to files (e.g., saving JSON data)

4. **Data Structures**:
   - Lists and ArrayLists
   - Sorting with `Collections.sort()` and Comparators

5. **Exception Handling**:
   - Managing custom and built-in exceptions


## Prerequisites

- Java Development Kit (JDK) 11 or higher
- An API key from [OMDB API](http://www.omdbapi.com/)

## How to Run

1. Clone the repository.
2. Replace `YOUR-API-KEY` in the `PrincipalConBusqueda` class with your OMDB API key.
3. Compile and run the desired main class using a Java IDE or terminal.

## License

This project is for educational purposes only and is not intended for commercial use.

