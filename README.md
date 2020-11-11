# contact_organizer
Converts word document into excel and organizes information

# install:
python-docx
xlsxwriter

# rules made 
if a cell on that column is blank you skip it
•	if name is missing, you skip
•	If name is there but no phone number and/or address you still input the information
In summary, You only skip if there is No name or all of it is empty

The word document has to be organized on word document in this way
  name
  address 
  phone number
Program will read those and put them on three different cells on excel
