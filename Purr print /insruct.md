# Instructions  

Our goal is to take a street address and "pretty-print" it!

Pretty-printing is the method of "cleaning up" or organizing your code. It essestally means taking any input text, and outputting it in the same format, every  time.

Your goal for this assignment is to take input from the user (they will be entering an address), and printing it to the screen in a proper street syntax/format.

A properly formatted address:
- Starts with a number
- Has a street name that is **capitalized**
- Has the type of the street (Crescent, Boulevard etc.) that is also **capitalized**

### Input
You will take 1 input from the user for each part of the address. Here is how the address is broken up:

- First 4 characters are the number of the address
- The next 10 character are the name of the street
- The next 10 characters are the type of street it is


For example

```
> What is the address: 123 ceNtrAl ParkWAY
> Your pretty-printed address is: 123 Central Parkway
```

Make sure to tell the user which part of the string will be used for each part of the address!

## Extension
You can add more sections to the input. For example, an address is usually made up of more then just a street number, name and type; there is usually a city, province and postal code.

Your extension is to add more elements to the input. Make sure to tell the user which index's are part of each element in input string. Also, the output is usually formatted in multiple lines.

For example:

```
> What is the address: 
42   QUEEN   street  BRAMPTONOntario L6P3J1
> 42 Queen Street
  Brampton, ON
  L6P 3J1
```
For the province abbreviation (changing Ontario to ON), take the first 2 characters of the province they give you.

Make sure to tell the user which part of the string will be used for each part of the address!