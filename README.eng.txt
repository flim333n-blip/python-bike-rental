# Bike rental

A simple Python console program that simulates the operation of a bicycle rental point.

## Description

This program helps automate the bike rental process. She consistently:
1. Checks if there are any available bicycles.
2. Requests the age of the user (rent only from 18 years old).
3. For older customers (59+ years old) gives a recommendation to take a guided walk.
4. Calculates the rental price (500 rubles per hour).
5. Offers to choose a payment method: card or cash.

##reason for creation
The desire to learn Python coding

## Technology

* **Language:** Python 3.13.4

## How to launch

1. Make sure that you have Python installed (version 3.13.4 or higher).
2. Download the file with the code.
3. Open the terminal (command prompt) in the folder with the file.
4. Run the program with the command:
    ```bash
    python bike_rental.py
    ```

## Work example

Here's what a successful lease looks like:

Enter your age: 25
Enter the rental time in hours: 3,500 rubles

Choose a payment method: 1)By card 2)Cash: 2
Cash payment. Thanks for the rent!
Have a good trip!!!


Otherwise, if the terminal is broken:
Enter your age: 30
Enter the rental time in hours: 2
1000 rubles
Choose a payment method: 1)By card 2)Cash: 1
The terminal is broken, we apologize for the inconvenience, come back tomorrow.


## What can be improved

* Add a check for negative rental time.
* Reduce the available bike counter after each rental.
* Add a full-day rental discount.


## Author

flim333n