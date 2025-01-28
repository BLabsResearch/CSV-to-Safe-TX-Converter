# CSV-to-Safe-TX-Converter

This file aids sending batch transactions on SAFE using the Transaction Builder app.
The **BASE** USDC token contract is hardcoded. You can customise the form manually.
**Make sure to customise "Safe Address" by entering the address from where you wish to send your funds!**

First create a CSV file with two columns, no headings needed: 
* the amount to be transferred. Makes sure to use a "." as decimal separator.
* the recipient's address
You can create a CSV file by saving a spreadsheet file in CSV format.

Press "Choose File" to upload.
Press "Convert CSV" to create the JSON file.
The "Total Expected Amount to Send" is generated to indicate the balance requirement.
Press "Copy to Clipboard" at the bottom.

An easy way to create your JSON file is to use Notepad++ for this, available on Microsoft:
* press on "New" to open a new file,
* head to the "Language " tab,
* select "JSON",
* paste in the copied script and save.

The file is ready for upload onto the SAFE Transaction Builder app!
