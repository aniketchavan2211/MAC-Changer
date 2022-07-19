# MAC Changer 
 ![License](https://img.shields.io/github/license/aniketchavan2211/MAC-Changer?style=for-the-badge)     
 
 A `Media Access Control` address 
 (MAC address) is a unique identifier 
 assigned to a `Network Interface Controller` 
 (NIC) for use as a network address in 
 communications within a network segment.

 Media Access Control
 - Permanent
 - Physical
 - Unique
 - Assigned by Manufacturer

 **Why to change the MAC Address?**
 - Increase anonymity
 - Impersonate other devices
 - Bypass filters

## Python

### Variables

 A variable is a location in memory that
 contain a certain value.
 
 Similar to maths, it's a name that is used 
 to store information.

 Examples:
 `X = 1`
 Now X has a value of one, so we can do
 `Y = X+X`
 and y has a value of 2 now.
 ```
 print (Y)
 ```
 will print the value of y on screen which is 2.
 ```
 2
 ```

### Handling User Input

 - Easiest way of getting user input is through
 keyboard.
 - There are a number of ways to achieve that
 - input() function prompts the user to enter
 a value.

 Examples:     
 `age = input ("What is your age")`
 Result 
 ```
 What is your age
 ```
 The variable age will hold the value of the 
 user input.

### Function

 - Set of instructions to carry out a task.
 - Can take input, and return result.
 - Make the code cleaner, reusable, and more
 abstract.
 - input() function prompts the user to enter
 a value.

 Examples:     
 We can define a function like so:
 ```
 def function_name (variable1, variable2...)
 ```
 And call it in code like so:
 ```function_name(values,values)```
### Decision Making 
 
 Execute code `ONLY` if a condition is true
 ```
 if condition1:
   # Code to execute when
   # Condition 1 is true
 elif condition2:
   # Code to execute when
   # Condition 2 is true AND
   # Condition 1 is false
 else:
   # Code to execute when
   # All conditions are false
 # Rest of Code
 ```

### Simple Algorithm
 Goal -> Check if MAC address was changed
 
 steps :

 1. Execute and Read ifconfig.
 2. Read the mac address from output.
 3. Check if MAC in ifconfig is what the user requested.
 4. Print appropriate message.

### Regular Expression (Regex)

 - Search for specific patterns within in a string.
 - Uses rules to match patterns.

## Help

 `-i`, `--interface`, help="Interface to change its MAC address"
 `-m`, `--mac`, help="New MAC address"

