This script is a console helper bot that recognizes commands entered from the keyboard and responds accordingly.

The bot-assistant can save a name, a phone number and a birthday, find a phone number and birthday by name, change a recorded phone number, display all saved records in the console. It also gives the number of days to the next birthday for contact.

The bot accepts commands:

"hello", "hi" replies to the console "How can I help you?"

"add ...". With this command, the bot saves a new contact in memory or add a new phone number and birthday for the existing contact in memory. Instead of ... the user enters the name and phone number, necessarily with a space.

"add_birthday ...". With this command, the bot add a birthday for the existing contact in memory. Instead of ... the user enters the name and birthday, necessarily with a space.

"change ..." With this command, the bot stores the new phone number of the existing contact in memory. Instead of ... the user enters the name, the old phone number and the new phone number, necessarily with a space.

"phone ..." With this command, the bot outputs the phone number for the specified contact to the console. Instead of ... the user enters the name of the contact whose number should be displayed.

"get_birthday ..." With this command, the bot outputs the birthday and the numbers of days to the next birthday for the specified contact to the console. Instead of ... the user enters the name of the contact whose birthday should be displayed.

"remove ..." With this command, the bot removes the phone number for the specified contact to the console. Instead of ... the user enters the name of the contact and phone number that should be removed from the address book.

"show all". With this command, the bot outputs all saved contacts with phone numbers to the console.

"show_page ...". With this command, the bot outputs saved contacts with all information on the specified page of the address book to the console. Instead of ... the user enters the number of the page that should be displayed and the number of records on each page of the address book.

"good bye", "close", "exit" by any of these commands, the bot ends its work after outputting "Good bye!" to the console.