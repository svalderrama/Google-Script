# Google-Script
Compilation of Google script functions and menus in Javascript

# Custom Menu 
This file creates a custom menu option in google sheets called 'github' with options to export a range in a column to a new doc in google drive, or format values  into into the range. Ideally, there are columns with data values starting in col A. Highlight an empty range next to the last column with data in it in order to use the "Format" option in the "Github" menu. To export a range, highlight it, and use the "Export" option in the Github Menu. Exporting ranges only works if the range is within a column. It does not function across rows. 

# URL List to Table
This file is creates a custom function that turns a column range into a table using a url to indicate a new row. I was using this funtion when trying to extract library information from a list of library details. The name of the library was a url, the address entered into a line underneath, and in the row below that was the phone number. This custom turned the list into a table in which the first row contained the name, second the address, and third the name. The reason I had to use the url as an indicator is because some entries contained additional information like available hours and accessibility options that made each entry take a different amount of rows in the initial list. 


