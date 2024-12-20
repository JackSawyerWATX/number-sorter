# **Sorting Algorithm Project**

## Overview

This project demonstrates how to dynamically sort an array of user-selected values from a dropdown and update the UI with the sorted results. It leverages JavaScript's built-in .sort() method for efficient sorting and updates the displayed values in real-time.

## Features

    - Dropdown Input: Users select values from dropdown menus.
    - Sort Button: A button triggers the sorting functionality.
    - Real-Time Sorting: The selected values are sorted in ascending order.
    - UI Update: The sorted values are displayed dynamically in designated output elements.

## Technologies Used

    - HTML: Provides the structure for dropdowns and output fields.
    - CSS: Styles the UI components (optional).
    - JavaScript: Implements sorting logic and UI updates.

## How It Works

    - User Input:
        The user selects numeric values from dropdown menus.
    - Sorting:
        When the Sort button is clicked, the values are sorted in ascending order using the .sort() method with a comparator function.
    - UI Update:
        The sorted values are displayed in output fields corresponding to their new order.

## Example Usage

Input:
    Dropdown Values: 3, 10, 2, 5

Output:
    Sorted Values: 2, 3, 5, 10

## Future Enhancements

    1. Add support for different sorting orders (e.g., descending).
    2. Include animations for sorting visualization.
    3. Extend support for string sorting or custom objects.