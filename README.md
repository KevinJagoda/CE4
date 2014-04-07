CE4
===

Part A:

link:
https://github.com/KevinJagoda/CE4/blob/master/CE4a.psm

Information:

>Used LDAI to load the following values into the accumulator:
-> 9
-> 8
-> B

>Used STA to store the following values into the their respective locations:
-> 9 into B0
-> 8 into C4
-> B into CB

>Used JMP to finish the PRISM

----------------------------------------------------------------------------------------------

Part B:

link: 
https://github.com/KevinJagoda/CE4/blob/master/CE4b.psm

Information:

>Used LDAD to have the prism load the value located at B0, labeled "value"

>Used ADDD to have the PRISM add the "value" to itself. This can be done because "value" is
  now in the accumulator because of the above action.
  
>Used ADDI to subtract 4 from the new "value". This was done by adding the 2's complement
  instead of finding a way to subtract. Also, ADDI was used instead of ADDD because it is a fixed number.
  
>This part is finished by having the result displayed in port 2 using the OUT 2 instruction and finishing
  off the PRISM by using jump in the same method as Part 1.
  
-----------------------------------------------------------------------------------------------

Part C:

link:
https://github.com/KevinJagoda/CE4/blob/master/CE4c.psm

Information:

>Started by using the instruction IN 3 to allow the user to input a value.

>Had the input value display itself in output port 0. 

>Had the PRISM add the 2's complement using ADDI of 1, which is F. This subtracts 1 from the current value.
  This result is then displayed in Port 1. This proccess is repeated and displayed into Port 2.
  
>Added 1 to the current value using ADDI and had it displayed in Port 0.

>Had the program JMP to bullet two of Part C above to repeat the process in an infinite loop.

----------------------------------------------------------------------------------------------

Documentation:
None




O:::{===================>  <====================}:::O

