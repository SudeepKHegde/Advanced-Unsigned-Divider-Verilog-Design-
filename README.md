# Advanced Unsigned Divider Verilog Design
One of the fundamental arithmetic operations in mathematics is division, which is the process of dividing a group of things into equal parts. Divide the dividend X by the divisor Y to get the quotient Q and the remainder R, which equals X = Y*Q + R. Consider a binary division condition, for instance, where X = 10010 and Y = 11. Q = 110 & R = 0 where Q = Quotient and R = Remainder are the results of the long division. 
Electrostatic discharge (ESD), electromagnetic interference (EMI), and power supply transients are all common in severe situations where microcontrollers are used. A microprocessor may carry out incorrect instructions as a result of system corruption brought on by electromagnetic discharges and bus corruption. A watchdog timer is a practical accessory in these settings that can assist in catching and resetting a microcontroller that has gone out of control. 
The division process was given a set amount of time in this particular design to produce an output. With the aid of the watchdog timer, let's say it doesn't provide an output within the allotted time, in which case the output is set to zero, acting as a reset without requiring human interaction. 

## Schematic [Vivado 2018.3]
![image](https://user-images.githubusercontent.com/123441538/224463647-e4af8351-7be1-4af9-9e77-cdb97ff07ad8.png)

## Output:

When a user tries to divide a number by zero, the design features a divide-by-zero flag that raises a flag. 
![image](https://user-images.githubusercontent.com/123441538/224463712-7dfd2220-1999-47c4-92df-7ec0cff0f493.png)


### Normal Division Output:

![image](https://user-images.githubusercontent.com/123441538/224463769-b7155529-1066-4173-988c-d6b2551caa1d.png)

