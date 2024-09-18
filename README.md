#rezwan Assignment 3
# Requisition System

## Overview

A Python program called the Requisition System is used to handle purchase requisitions. Users can enter requisition items and personnel details, compute the total cost, and utilize the total value to determine if the request is granted or pending. The object-oriented design and user input handling fundamentals of Python programming are demonstrated in this application.

## Features

- Collect Staff Information: Gathers details including the date, staff ID, staff name, and generates a unique requisition ID.
- Requisition Item Entry: Allows the user to enter details for up to three requisition items, including the item name and cost.
- total prize Calculation: Computing the total prizes of all items.
- Approval: Determining if the requisition is approved or pending.
## Code Features

1. Class Definition:
   - The `RequisitionSystem` class encapsulates all functionality related to requisitions.

2. Initialization:
   - `__init__`: Initializing the system with a starting requisition ID and empty dictionaries for staff information and requisition items.

3. Collect Staff Information:
   - `collect_staff_info()`: Prompting the user for staff details and generates a unique requisition ID for each request.

4. Collect Requisition Items:
   - `collect_requisition_items()`: Allowing the user to input details for up to three items, including their price. Calculates and displays the total cost.

5. Approve Requisition:
   - `approve_requisition()`: Evaluating the total cost and prints whether the requisition is approved or pending based on a $500 threshold.

6. Display Requisitions:
   - `display_requisitions()`: Calling other methods to collect staff information and requisition items, determine approval status, and display the details.






