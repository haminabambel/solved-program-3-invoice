Download Link: https://assignmentchef.com/product/solved-program-3-invoice
<br>
A gas station has three different qualities of gasoline for its customers.Unleaded – 87Unleaded Plus – 89Premium – 91$2.47$2.58$2.61Write a program titled “YourLastName_Invoice” that prompts for input (from the standard input stream) about gas sold and prints out an invoice for the total charge, including taxes. The output should be printed to the terminal using the standard output stream.The program should prompt for the following input: Membership, a string of with the answer “yes” or “no” if the user is a member of a club for discounts. Quality, the number for the type of gas chosen (87, 89, 91). Quantity, the number of gallons sold.After acquiring the input, the program should apply any discounts due to membership ($0.10 per gallon if they’re a member), compute the subtotal (quantity times price, remember the membership discount to price if applicable), county tax (7% of the subtotal), city tax (3.75% of the subtotal) and total, and print an invoice.For example:The following shows an example interaction captured in a file by the command “% script Invoice.out” (bolded areas represent the user’s input):Script started on Wed Sep 18 10:23:58 2013% java Diaz_InvoiceAre you a member? yesQuality of gas: 87Gallons sold: 13INVOICE FOR GASOLINEMember Status: YesGasoline Sold/Price: 13 @ $2.37Subtotal: $ 30.81County Tax: $ 2.16City Tax: $ 1.16—————–Total: $ 34.13% exitscript done on Wed Sep 18 10:24:17 2013Use constants (declared with the modifier final) to represent the membership discount, the prices for gas, as well as the county and city tax rates. Format your invoice exactly as shown in the example above.Run the program three times with different input and capture all interaction in a file using the script command.What to turn in:– Soft copy of the results using the script command– Soft copy of the programs (the .java files submitted to Blackboard)