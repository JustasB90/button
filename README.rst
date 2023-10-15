.. _button-sample:

Button
######

Overview
********
This is a modified sample from the SDK which demonstrated how to:

1. Trigger an interrupt from a button.
2. Debounce the button.
3. Toggle an LED.

Board: nRF52840DK

SDK: nRF Connect SDK 2.4.2

Questions
********

1. What are the hardware registers that cause the LED to turn on and off? 
OUT . Datasheet pg 152

2. What are the registers that you read in order to find out the state of the button?
IN . Datasheet pg 153

3. Can you read the register directly and see the button change in a debugger or by printing out thes value of the memory at the register’s address?
I can toggle the LED by changing PIN13 in OUT register in the debugger. So far it looks like a standard debugger. 
