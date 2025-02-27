# Breadboard-Vending-Machine

## What is it? And how it works? 
This vending machine circuit uses a NOR gate (7402) and AND gate (7408) to trigger an output which is frequently used in electronic appliances such
as vending machines. It is built upon the model of the SR Latch which takes inputs and called "Set" (S) and "Reset" (R) which can store a single binary 
value (either 0 or 1), similar to how a vending machine remembers the selection you made by storing the corresponding product code until you press the
dispense button, essentially "setting" the machine to deliver that specific item; once the item is dispensed, the machine is essentially "reset" and 
ready for a new selection.

## Recall the Truth Table for the SR Latch Operation

![Screenshot 2025-02-27 170519](https://github.com/user-attachments/assets/2a66e5f6-53b8-48e2-965a-cc7c4722212d)


## Diagram Showing Vending Machine Circuit

![Screenshot 2025-02-27 165710](https://github.com/user-attachments/assets/44c1ac37-5cf1-4551-866c-4e9e99b33a91)

In this diagram, you can see where the previously built SR latch was modified, adding on a few new devices onto the breadboard. The only differences are
that the S button represents the COIN button and the out Q LED represents the COIN indicator LED. In addition, a capacitor is added to acquire the desired
delayed reset in the circuit along with two resistors to control the current flow the LEDs and capcitors. 

## Circuit Showing Both COIN and VEND Set to Off "0"

![off](https://github.com/user-attachments/assets/14dcaa3d-d644-4973-9b0d-cb9cfc56eda6)

The circuit shows two inputs: a COIN and a VEND buttoN. Pressing COIN represents inserting a coin & pressing vend represents the machine doing the vending
action of an item. In this case both of the buttons are set to OFF "0" therefore neither the COIN or VEND LEDs are lit up. 

## Circuit Showing COIN set to On "1" and VEND Set to Off "0"

![coin](https://github.com/user-attachments/assets/7c2b2605-c4ce-41c6-8ef7-cd737a3c097a)

In this scenario, the COIN button is pressed and the input crosses the gates which causes an output of "1" or ON state in the COIN LED, which is why it is
lit, however the VEND button isn't pressed, hence still in the OFF state "0".

## Circuit Showing COIN set to On "1" and VEND Set to On "1"

![vend](https://github.com/user-attachments/assets/04b37ea9-f49b-49d2-aeff-53176f36e124)

Finally, the VEND button is click after the coin is inserted (COIN button pressed) and the both LEDS are lit up for a short period. This portrays that an
item is being vended. The delayed reset is important for the action to be completed. After the action is completed, the circuit repeats itself by returning
to the "no coin" state which causes both the COIN and VEND LEDs to come off after the delayed reset. 

### NB : For simnplicity of this circuit, assume only one coin can be inserted at a time. Inserting another coin won't change the state of the circuit. 

## Works Cited 

Justice, M. (2020). How Computers Really Work: A Hands-On Guide to the Inner Workings of the Machine.[Book]. No Starch Press.
