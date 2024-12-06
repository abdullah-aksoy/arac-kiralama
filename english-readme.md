# Car Rental System

This C++ program is used to manage car rental operations. Users can rent cars, return cars, and check their balance status.

## Features

- Start car rental process
- Return rented car
- Calculate rental fee and deduct from balance
- Warn in case of insufficient balance

## Requirements

- C++ compiler (e.g., g++)

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/abdullah-aksoy/arac-kiralama
    cd car-rental
    ```

2. Compile the program:
    ```sh
    g++ -o arac-kiralama arac-kiralama.cpp
    ```

## Usage

1. Run the compiled program:
    ```sh
    ./arac-kiralama
    ```

2. Select an operation from the menu and enter the required values.

## Code Explanation

The program performs the following steps:

1. Takes the balance information from the user.
2. Asks the user to select an operation.
3. Takes the necessary values from the user based on the selected operation.
4. Performs the calculations and displays the results.
5. Repeats these steps until the user exits.
