# Dictionary-in-list
## Overview
This program allows users to maintain a record of the countries they have visited, including the number of visits and the cities visited. This is achieved through a data structure that efficiently stores and manages the travel information.

# Concepts
## User Input:
The program prompts the user to input the name of the country, the number of visits, and the cities visited.
## Data Structures:

Dictionary: A dictionary is used to store the details of each country. Each dictionary contains keys for the country name, number of visits, and a list of cities visited.
List of Dictionaries: The travel_log is a list that contains multiple dictionaries. Each dictionary represents a country with its corresponding visits and cities.

## Functions:
The program includes a function to add a new country to the travel log. This function takes the country name, number of visits, and cities visited as inputs, creates a dictionary with this information, and appends it to the travel log.
## Data Access and Display:
The program accesses the travel log to retrieve and display information about the visits, including a summary of the countries and cities visited.
Program Flow
## Initialization:
The program starts with a predefined travel log containing some example entries.

## User Input:
The program prompts the user for new travel information, including the country name, number of visits, and cities visited.
## Function Execution:
The function to add a new country is called with the user-provided inputs. This updates the travel log with the new entry.
## Data Display:
The program accesses the updated travel log and prints a summary of the newly added travel information.
# Example Use Case

Input:

Country: "Italy"
Number of Visits: 3
Cities: ["Rome", "Venice", "Florence"]
Output:

A new entry for Italy is added to the travel log.
A summary message is printed, indicating the number of visits to Italy and the cities visited.
