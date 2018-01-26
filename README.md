# Shift-o-matic
A program that automatically schedules staff shifts based on holidays, hours on the shift, day, night shift and other parameters.
Exports printable calendars for staff as well as a full overview for supervisors.

How to use Shift-o-matic

Enter the following information:
Month and year that the monthly roster should start on.
Names of all employees
Day shift hours
Night shift hours
Holidays with start and end date (end date is the day before they are supposed to be back at work)
Number of days shifts needed before another night shift
Maximum number of consecutive night shifts allowed for any employee
Maximum number of hours an employee can work during a month.


The algorithm will then take this information and spit out a suggested plan.

If there are not enough employees available to fill all the spaces with the parameters you put in it will suggest
hiring daily workers.

Each employee will have the total number of hours displayed on their individual calendar
The master calendar will display all the names of the employees, shifts, and highlight employees who have not worked the maximum
number of hours in the month. These employees can be used as gap fills in case a shifted employee falls sick.

You can go back and change your parameters to produce another calendar if you are not happy with the results.

