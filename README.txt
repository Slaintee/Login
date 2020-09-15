Lab 1
Ken Zhang
CS 166 / Fall 2020

This program is to create a login and menu to a company intranet system that requires users (employees)
to enter a username and password in order to view a menu of options
(such as Time Reporting, Accounting, IT Helpdesk, Engineering Documents, etc.).

main.py is the program.
list.csv is the authorized user list includes user name, password, and level.

alpha is level 1 and can only access Time Reporting area.
beta is level 2 and can access all area but Engineering Documents area.
gamma is level 3 and can access all area.

Direction：
1. The system is showing welcome, and ask for input of user name and password.
2. If mismatching, the system will ask for input again.
3. After login, the system will show welcome and ask for input of area number. (There is no such Area 51)
4. Press 1 for Time Reporting area, Press 2 for Accounting area, Press 3 for IT Helpdesk area, Press 4 for Engineering Documents area, Press 5 for Log out.
5. Authorized will be permit to access the specific area. Otherwise the access will be denied.
6. If the input is invalid, the system will automatically log out.