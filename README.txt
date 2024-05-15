Unique Email Generator

This project generates unique email addresses for students based on their names. It reads an Excel file containing student names and generates email addresses in the format `first_initial + last_name@gmail.com`.
   

Code Explanation

1. The code imports the necessary library (Pandas).
2. It reads the Excel file containing student names into a DataFrame.
3. The script generates unique email addresses by iterating over each row in the DataFrame.
4. For each student name, it splits the name into parts using a comma as the separator.
5. The code extracts the first name and last name based on the number of parts.
6. It generates the email address using the first initial of the first name and the entire last name.
7. The script ensures that the generated email addresses are unique by appending a number if necessary.
8. The unique email addresses are stored in a list called `email_addresses`.
9. Finally, the code displays each student's name and their corresponding email address using a loop that zips the `df['Student Name']` and `email_addresses` lists together.

Contributing

If you find any issues or have suggestions for improvements, feel free to create a new issue or submit a pull request.

