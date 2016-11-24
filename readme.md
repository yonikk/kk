Group Member : Yonas Lemmi

Discription
For part 1 of the lab, I use a shift register comprising of 8 D-Flip Flops.
the first flip flop is an asynchronous flip flop. I used that flip flop because
it help with which pushbutton was pressed. The shift register helped store the
last 8 inputs. Also used a 16 bit counter that was given to us by Prof Tao. The
counter locks once it reaches 16 inputs, and the user has to reset the counter to
continue. Once the user inputs the 8 bits the circuit compares it with the
secret input key which is 00100111. 


For Part 2 of the lab for the 8 bit sequencer, I used the same shift registers
as part 1 then transfered the values to the programmable usercode. The way I was 
able to store the secrete code is by using D flip flops. Once the user enters
the secret code, used a clock to save the input in the flip flops. Once the user
clicks on the save button, the clock cycles once storing the input in the flipflop.
They took the input from the 8 bit sequencer and secret code, and XOR them
one by one. After XOR, took the 8 bits and OR them and NOT that output which is
the ouput of the Status.

Secrete Key: 00100111

Files:
16-bit Lock.cct
Lab3Part2.cct
Lab3pu.cct
LemmiLab3Part1.cct
YonasLemmiLab3.clf