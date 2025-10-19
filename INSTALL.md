Thank you for buying Power Dolphin🐬. It will allow you to use the modern USB-C PD(Power Delivery protocol) / QC(Quick Charge protocol) chargers to power your Nintendo GameCube. This guide will help you get it installed on your GameCube.

# Prerequisition

You will need:

- Gamebit screwdriver to open up the shell of GameCube  
- A compatible USB-C charger that supports PD/QC on 12V and 3A(more on this in [Troubleshooting](#troubleshooting))  
- A small phillips screwdriver(PH0) to secure the Power Dolphin power mod  
- Optionally, a fine tip tweezer will help

# Test Your USB-C Charger with Power Dolphin

Before you open up the GameCube, let’s try if the charger is compatible with Power Dolphin. Simply put the charger onto the wall and connect a USB C cable from the charger to Power Dolphin. A green LED should light up in just a few seconds, which means your charger can output 12V which is what GameCube needs. If the LED doesn’t light up, you’ll need to inspect the spec of the charger, it might not be able to output 12V. Some cheap USB-C cables do not include crucial data wires that Power Dolphin needs to negotiate a PD/QC protocol with the charger, so those cables won’t work either. More compatibility details in the [Troubleshooting](#troubleshooting) section.

![20251018_220642.jpg](images/20251018_220642.jpg)

# Installation

If your charger is ready to go, then it’s time to open up the GameCube.

1. Use the gamebit screwdriver to remove 4 long gamebit screws on each corner of the bottom.
![20251018_214945.jpg](images/20251018_214945.jpg)

2. Carefully flip the GameCube over and lift the top shell.
![20251018_215026.jpg](images/20251018_215026.jpg)

3. Tilt and pull the black back cover out.
![20251018_215053.jpg](images/20251018_215053.jpg)

4. Now turn the GameCube’s back towards you.  
![20251018_215115.jpg](images/20251018_215115.jpg)

5. Start by carefully pulling two connectors out.   
   The thicker one is the power connector, the thinner one is the fan connector.
![20251018_215147.jpg](images/20251018_215200.jpg)
![20251018_215200.jpg](images/20251018_215200.jpg)

6. Use the PH0 screwdriver to remove the black screw in the middle of the power board.
![20251018_215215.jpg](images/20251018_215215.jpg)

7. After removing the screw, you should be able to take the power board out easily.  
![20251018_215233.jpg](images/20251018_215233.jpg)

8. Now put the Power Dolphin board back to the place the original power board stayed.
![20251018_215245.jpg](images/20251018_215245.jpg)

9. Fasten Power Dolphin board using the PH0 screwdriver with the black screw.
![20251018_215308.jpg](images/20251018_215308.jpg)

10. Reconnect the power connector and fan connector to Power Dolphin. Note Power Dolphin came with a third connector in the middle, which is for a PC standard fan(Molex KK 254). If you have a fan mod(e.g. Noctua 4010 fan) with a PC fan connector, you can directly put the fan connector in the middle.
![20251018_215357.jpg](images/20251018_215357.jpg)

11. Gently push the back cover into place. And that will finish the bottom part of the installation. Now it’s time to turn to the top shell.  
![20251018_215434.jpg](images/20251018_215434.jpg)

12. You’ll need to swap out the original power button, with the supplied Power Dolphin’s button. From the inside of the topshell, gently prick the power button with a tweezer or screwdriver or your fingers.
![20251018_220007.jpg](images/20251018_220007.jpg)
![20251018_220023.jpg](images/20251018_220023.jpg)

13. Now from the topside of the topshell, align and push the supplied Power Dolphin’s button in. This should finish the power button’s installation.
![20251018_220114.jpg](images/20251018_220114.jpg)
![20251018_220131.jpg](images/20251018_220131.jpg)

14. Before you putting the top shell back, it’s important to check

    1. The power wires are tugged into the groove
![20251018_215904.jpg](images/20251018_215904.jpg)

    2. The fan wires are tugged into the groove
![20251018_215411.jpg](images/20251018_215411.jpg)

15. Now put the top shell back into place, make sure all 4 corners all have an even contact with the bottom shell.
![20251018_215504.jpg](images/20251018_215504.jpg)
![20251018_215512.jpg](images/20251018_215512.jpg)

16. Carefully flip the GameCube over, use the gamebit screwdriver to fasten the 4 long gamebit screws back.
![20251018_215529.jpg](images/20251018_215529.jpg)

17. Tada🎉 Your Power Dolphin’s installation has finished.
![20251018_220347.jpg](images/20251018_220347.jpg)
![20251018_220458.jpg](images/20251018_220458.jpg)


# Troubleshooting {#troubleshooting}

If the green LED on the Power Dolphin board doesn’t light up, it means the Power Dolphin cannot negotiate 12V voltage output with the connected USB-C PD/QC charger. There are many chargers on the market that don't specify what voltage and what ampere it can provide. Even established brands like Belkin, Anker, Ugreen do that too. So it’s important to check the spec on the charger’s body, which usually will tell you about the actual spec, like this:

![20251018_220903.jpg](images/20251018_220903.jpg)

Even with the right charger, it’s important to note not all ports provide the same voltage/current combination. Take the above example. There are 4 ports on this charger, USB-C1, USB-C2, USB-C3 and USB-A. USB-C1 and USB-C2 can output 12V at 3A(good). USB-C3 can output 12V at 2.5A(minimum, not recommended). USB-A can output 12V at 1.5A(no good, struggle to power on or to read disc). So for this charger, only USB-C1 and USB-C2 should be used to power the GameCube.

**TL;DR, you will need to find a proper charger with a right port that provides:**  
**Voltage: Exactly 12V**  
**Current: 2.5A(minimum), 3A(recommended) or higher**

The cable is another thing that can stop Power Dolphin from negotiating a 12V voltage with the charger. Some cheap cables only provide 2 or 4 wires, dubbed as “charging only cable”. Those cables can only provide 5V from any charger, so don’t use them.

If the 3D printed USB-C port cover fell off during transportation, you can easily push it back like this:

![20251018_215625.jpg](images/20251018_215625.jpg)
![20251018_215638.jpg](images/20251018_215638.jpg)