# Project Title: SeatMate

## Problem Statement: 
  Manual seating on paper takes a lot of time to erase and recheck, and students can get confused matching a drawn map to real desks. When we asked 10 teachers, **8 out of 10** said manual seating is time-consuming.

  Our system will use rule based checks to only allow seat numbers from 1 to 30, block assigning a seat that is already taken, and catch invalid inputs before saving any changes. Apps like **ClassDojo** and **Mega Seating Plan** already exist, but they often need internet, accounts, or paid plans. Ours will be a simple, offline program made for quick seating management in a 30-seat class.
  
## Project Objectives: 

### General Objective
The main goal of this project is to develop a simple, Python-based Student Seating Arrangement System that automates classroom seat assignments for up to 30 students and displays an organized seating layout for teachers and students.

### Specific Objectives
To achieve the general objective, the project aims to:

1. Data Storage: Store and manage student names in a structured Python list, with each position representing a specific seat.

2. Seat Assignment and Removal: Allow users to assign students to available seats and remove existing assignments when necessary.

3. Student Search: Locate and display the assigned seat number of a specific student.

4. Input and Occupancy Validation: Validate user inputs, restrict seat numbers to 1–30, and prevent duplicate or invalid seating assignments.

5. Seating Layout Display: Display an organized console-based seating arrangement showing all 30 seats, including occupied and vacant positions.

6. Status Notifications: Provide clear messages indicating successful operations, invalid inputs, and unavailable seats.

## Planned Features: 
1. Store Student Names – Stores student names in an array for easy access and management.

2. Assign Students to Seats – Allows the user to assign students to specific classroom seating positions.

3. Check Seat Availability – Checks whether a selected seat is occupied or vacant before assignment.

4. Remove Students from Seats – Removes a student's seating assignment, making the seat available again.

5. Search for Student Seats – Locates and displays the seat number assigned to a specific student.

6. Display Seating Arrangement – Shows the complete seating layout, indicating occupied and vacant seats.

7. Display Status Messages – Notifies the user of successful operations, invalid inputs, and errors.
   
## Planned Inputs:
1. Menu Choices – Accepts numerical inputs (1–5) from the user to select a specific operation from the main menu.

2. Student Names – Accepts text inputs containing student names for seating assignments, seat searches, and other student-related operations.

3. Seat Numbers – Accepts integer inputs ranging from 1 to 30 to identify specific seating positions for assignments, edits, or removals.

4. Swap Inputs – Accepts two seat numbers entered sequentially by the user to identify the seats whose assigned students will be exchanged.

## Planned Outputs:
  · Main Menu Display: Interactive text interface showing available options.
  · Seating Layout Display: Complete list of seats (1–30) showing which are assigned or marked as "Empty".
  · Search Results: Confirmation messages showing whether a student was found and their seat number.
  · Status & Error Messages: System feedback such as "Added [Name] in seat number [X]", "Seat Taken", or "Invalid Seat Number".

## Logic Plan (flowchart):

<img width="2272" height="3810" alt="Untitled Diagram drawio" src="https://github.com/user-attachments/assets/d31c3166-bce2-4db6-b6dc-1365cf59fb51" />

## Contributors: 
- Student 1: Marmita, Shaun Matthew P. - Made the Project Title upto Planned Outputs
- Student 2: Nervez, Dweezel Mae L. - Made the Logic Plan(flowchart)
- Student 3: Zarzua, Cleona Zareen G. - Organized the PROPOSAL.md
