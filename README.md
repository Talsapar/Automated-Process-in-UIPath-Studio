# automated-process-in-UIPath Studio
Building a Flow that will perform an automatic process that will add contacts to Outlook, according to the attached Excel file.

* >The development in UiPath Studio is done in the .NET environment, when specifically in this process VB.NET is used.

# The process: 
Building a Flow that will perform an automatic process that will add contacts to Outlook, according to the attached Excel file (where during the automation process the Excel file will be closed).

For each contact, the process will save their full name, email address and phone number in Outlook.

In addition, a search will be made for each of the contacts on the Google.com website (on the website itself). 
This is only a search and the search results have no meaning.

In the contact card in Outlook, in the Job title field, one of the following options will be written: "Does not exist in Google", "The phone in Google is compatible", "The phone in Google is not compatible".
The Flow will choose the correct option according to the comparison between the data in column D and the data in column E in the Excel file.
At the end of handling the contact, the current date and time will be entered in the "Treated B" cell.

