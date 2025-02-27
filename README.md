# Breadboard-Vending-Machine

## What is it? And how it works? 
This vending machine circuit uses a NOR gate (7402) and AND gate (7408) to trigger an output which is frequently used in electronic appliances such <br>
as vending machines. It is built upon the model of the SR Latch which takes inputs and called "Set" (S) and "Reset" (R) which can store a single binary <br>
value (either 0 or 1), similar to how a vending machine remembers the selection you made by storing the corresponding product code until you press the <br>
dispense button, essentially "setting" the machine to deliver that specific item; once the item is dispensed, the machine is essentially "reset" and 
ready for a new selection. <br>

## Recall the Truth Table for the SR Latch Operation

![Screenshot 2025-02-27 170519](https://github.com/user-attachments/assets/2a66e5f6-53b8-48e2-965a-cc7c4722212d)


## Diagram Showing Vending Machine Circuit

![Screenshot 2025-02-27 165710](https://github.com/user-attachments/assets/44c1ac37-5cf1-4551-866c-4e9e99b33a91)

In this diagram, you can see where the previously built SR latch was modified, adding on a few new devices onto the breadboard. The only differences are <br>
that the S button represents the COIN button and the out Q LED represents the COIN indicator LED. In addition, a capacitor is added to acquire the desired <br>
delayed reset in the circuit along with two resistors to control the current flow the LEDs and capcitors. 

## Circuit Showing 


## Works Cited 

Justice, M. (2020). How Computers Really Work: A Hands-On Guide to the Inner Workings of the Machine.[Book]. No Starch Press.
