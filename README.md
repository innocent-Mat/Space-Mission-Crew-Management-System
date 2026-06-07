# Space Mission Crew Management System

## Overview

The Space Mission Crew Management System is a JavaScript-based application designed to manage and organize astronaut crews for a space mission. The project demonstrates the use of arrays, objects, loops, functions, sorting algorithms, and data manipulation techniques.

The system allows mission control to add astronauts to a squad, prevent duplicate crew IDs, swap crew positions, sort astronauts by mission priority, identify EVA-eligible crew members, divide crews into teams, and generate crew summaries.

## Features

### 1. Add Crew Members

* Adds astronauts to the mission squad.
* Prevents duplicate astronaut IDs from being added.

### 2. Swap Crew Members

* Exchanges the positions of two astronauts within the crew.
* Validates indices before performing the swap.

### 3. Priority Sorting

* Sorts astronauts by mission priority in descending order.
* Higher-priority crew members appear first.

### 4. EVA Crew Selection

* Filters astronauts eligible for Extravehicular Activity (EVA).
* Automatically sorts eligible astronauts by priority.

### 5. Crew Chunking

* Divides the crew into smaller groups of a specified size.
* Useful for team assignments and mission planning.

### 6. Crew Summary

* Generates a summary of crew members sorted by priority.
* Displays astronaut names in mission order.

## Technologies Used

* JavaScript (ES6)
* Arrays
* Objects
* Functions
* Loops
* Array Methods

## Project Structure

### Astronaut Object

Each astronaut contains the following properties:

| Property      | Type    | Description                 |
| ------------- | ------- | --------------------------- |
| id            | Number  | Unique astronaut identifier |
| name          | String  | Astronaut name              |
| role          | String  | Mission role                |
| isEVAEligible | Boolean | EVA eligibility status      |
| priority      | Number  | Mission priority level      |

Example:

```javascript
{
  id: 1,
  name: "Andy",
  role: "Commander",
  isEVAEligible: true,
  priority: 3
}
```

## Main Functions

### addCrewMember(crew, astronaut)

Adds an astronaut to the crew while preventing duplicate IDs.

### swapCrewMembers(crew, fromIndex, toIndex)

Swaps two astronauts based on their positions.

### sortByPriorityDescending(crew)

Sorts crew members by priority in descending order.

### getEVAReadyCrew(crew)

Returns a list of EVA-eligible astronauts sorted by priority.

### chunkCrew(crew, size)

Splits the crew into smaller groups of a specified size.

### printCrewSummary(crew)

Displays a priority-sorted list of astronaut names.

## Example Output

```text
Elise
Felix
Irene
Caroline
Andy
Hank
Diego
Joan
Bart
Gertrude
```

## Learning Objectives

This project demonstrates:

* Array manipulation
* Object-oriented data structures
* Bubble sort implementation
* Filtering data
* Input validation
* Function modularity
* Team organization algorithms

## Future Improvements

* User interface integration
* Database storage
* Mission assignment tracking
* Crew performance analytics
* Search and filtering capabilities
* Real-time crew updates

## Author

Developed as a JavaScript practice project for learning data structures, algorithms, and mission crew management concepts.
