# prog1_project
project for programming 1 term 3 
Requirements:
it is required to write a program that will create and maintain a company management system to keep track of Employees inside the company. Each Employee has Id, last name, first name, salary, birth date (another struct of day, month, and year), the address, phone number, and email. Your program should allow the user to execute the following commands:
1-LOAD (Read from file): This command reads in a file name and loads the employee’s data from this file. The file is a text file that is comma delimited in which each entry is found on a separate line. Each entry must contain the Id, last name, first name, salary, date of birth, address, phone number and email. An example of one line in the file is as follows: 123,Steven,Thomas,2000,10-06-1995,26 Elhoreya Street,01234567899,sthomas@gmail.com 
2-QUERY (Search): The system should process a request by the user to look up information about a specific Employee. The user must supply the employee’s last name, and the system should provide all data for all employees of that last name.
3-ADD: The system should prompt the user field by field for the data of a single employee and add it to the system.
4-DELETE: The user should be prompted for the name – last and first and all employees associated with that name should be deleted from the system.
5-MODIFY: The user should be prompted for id of an employee. Then the user should be prompted field by field to modify the information for that employee.
6-Print (Sort): Print the data of all employees, in sorted order. You should prompt the user to choose if sort should be done based on either last name or salary or Date of Birth. The program should check for errors and print appropriate messages (e.g. trying to delete an employee that is not in the file). The program should validate all entered data. Validate a number in the phone number.
Validate the email address (example@domain.com). 
Validate the date in Date of birth.
