# birthday-wisher-in-python-
 birthday mailing program
This Python script sends automated birthday emails to people in a CSV file if their birthday is today.

First, it imports necessary modules and defines required variables such as email and password to log into the SMTP server. Then, it retrieves today's date information and reads a CSV file that contains information about people's birthdays.

It creates a dictionary with tuples of month and day as keys and row data from the CSV file as values. It checks if the current date tuple matches any of the keys in the dictionary. If it does, it retrieves the data of the person whose birthday is today.

Then, it randomly selects one of the three letter templates and replaces the "[NAME]" placeholder in the selected template with the name of the person whose birthday is today.

Finally, it logs into the SMTP server, sets up a secure connection, and sends an email to the person with the birthday using the customized message.
