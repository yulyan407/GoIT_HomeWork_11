This script is a console helper bot that recognizes commands entered from the keyboard and responds accordingly.

The bot-assistant can save a name and a phone number, find a phone number by name, change a recorded phone number, display all saved records in the console

The bot accepts commands:

"hello", replies to the console "How can I help you?"

"add ...". With this command, the bot saves a new contact in memory or add a new phone number for the existing contact in memory. Instead of ... the user enters the name and phone number, necessarily with a space.

"change ..." With this command, the bot stores the new phone number of the existing contact in memory. Instead of ... the user enters the name, the old phone number and the new phone number, necessarily with a space.

"phone ...." With this command, the bot outputs the phone number for the specified contact to the console. Instead of ... the user enters the name of the contact whose number should be displayed.

"remove ...." With this command, the bot removes the phone number for the specified contact to the console. Instead of ... the user enters the name of the contact and phone number that should be removed  from the address book.

"show all". With this command, the bot outputs all saved contacts with phone numbers to the console.

"good bye", "close", "exit" by any of these commands, the bot ends its work after outputting "Good bye!" to the console.