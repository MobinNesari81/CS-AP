---
type: assignment
date: 2023-02-23T0:00:00+4:30
title: <Assignment #2>

# optional 
pdf: https://google.com/

# optional
# set it to true if you don't want this assignment to appear in the announcements section
hide_from_announcments: true

due_event: 
    type: due
    date: 2023-02-29T0:00:00+4:30
    description: 'Assignment #2 due'
---
<!-- Other additional contents using markdown -->
# Weather App Assignment

## Introduction
In this assignment, you will build a simple Java application that connects to a weather API and retrieves information about the current weather conditions of a given city.

## Objectives
- Familiarize with the basics of Java programming
- Understand how to make HTTP requests to retrieve data from APIs
- Parse and process JSON data in Java
- Use Git for version control and collaborate on a codebase
- Use Maven or Gradle as a package manager

## Requirements
- Java 8 or later
- Git
- Maven or Gradle

## Tasks
1. Get an API key from `https://www.weatherapi.com/`. You need to sign up and verify your account.
2. Fork this repository and clone the fork to your local machine
3. Create a Java project using Maven or Gradle
4. Add org.json to Gradle `build.gradle` file to include the JSON library

5. Write a Java class `WeatherApp` that does the following:
    - Prompts the user for a city name
    - Parses the JSON response to extract the temperature and humidity
    - Prints the temperature and humidity to the console

6. Commit your changes and push them to your fork on Github

## Evaluation
- Your code should compile and run without any errors
- Your code should correctly retrieve and display the temperature and humidity for a given city
- Your code should be well-organized, readable, properly commented and follows clean code principles
- You should use Git for version control and include meaningful commit messages

## Bonus
1. Extend the WeatherApp class to also display the current wind speed and direction
2. Add error handling to handle cases where the API returns an error or the city name is not found

## Submission
- Push your code to your fork on Github

Good luck and happy coding!

