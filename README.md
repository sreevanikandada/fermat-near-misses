Fermat's Last Theorem Near Misses Search

Description
This Python program searches for near misses to Fermat's Last Theorem. It allows users to input a power 'n' and a maximum value 'k', then searches for the smallest relative miss within the given range.

Features
- User input validation for 'n' and 'k'
- Comprehensive search for near misses
- Real-time reporting of new smallest relative misses found
- Final report of the overall smallest relative miss

Requirements
- Python 3.x

Usage
1. Run the script:
python fermat_near_misses.py
2. Enter the power 'n' when prompted (must be between 2 and 12)
3. Enter the maximum value 'k' when prompted (must be greater than 10)
4. The program will display new smallest relative misses as they are found
5. After completion, the program will display the overall smallest relative miss

Functions
- get_input(): Handles user input for 'n' and 'k'
- find_near_misses(n, k): Performs the search for near misses
- main(): Orchestrates the program flow

Example Output
Enter the power n (2 < n < 12): 3
Enter the maximum value k (k > 10): 100
New smallest relative miss found: x=15, y=18, z=20, actual miss=217, relative miss=0.0178571429
...
Smallest relative miss overall: x=15, y=18, z=20, relative miss=0.0178571429

Note
The search can be computationally intensive for large values of 'k'. The program may take some time to complete for high values.

Authors
- Sreevani Kandada
- Sai Kiran Bairu

Course Information
- Course: Software Engineering
- Date Completed: 07/28/2024

