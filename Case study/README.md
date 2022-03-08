# Case Study 1

# Water Level Alarm Circuit



Introduction:

 Water is a very important part of everyone's life, so there are water tanks in different places such as housing, industry and farms. Everyone faces the problem of overflow and wasted water on a daily basis.
And thus comes the need for the water level alarm circuit. This simple DIY project can be the best solution for this problem.

8051 microcontroller is the main part of this project (89s51 to be specific). We have used a float sensor In this project. This float sensor is used to detect the level of the water inside a water tank. Ideally, this sensor should be attached to the top lid of the water tank or the liquid tank. The float attached to the sensor will move up and down as the water level increases or decreases.
The output voltage from the sensor is given to a comparator circuit. This comparator has second input from a variable resistor. This variable resistor is used to decide the threshold water level for which the buzzer should be turned on.
This potentiometer and sensor provide an extra feature to this project. Other water level alarm circuits do not have a user-defined threshold level. However, in this project users can define their own threshold level using this potentiometer.

 ![water-level-alarm-circuit](https://user-images.githubusercontent.com/98813874/154856662-d11e703d-5565-4435-b2e7-7b4cdad5923c.png)

 
## Low level requirements:

-	Measure the water level when the circuits indicate when the tank its half and full

-	When the water level is too high or too low or exceeds the higher limit, it can detect the water level easily by hearing an alarm sound

-	the toggle switch  is used to turn on & turn off the buzzer.

## High level requirements:

-	The output voltage from the sensor is given to a comparator circuit.

-	8051 microcontroller is the main requirement of this project.

- This buzzer is turned on whenever the water level is above the threshold level.

-	We include Red LED for the visual indication of the threshold level. LED and buzzer are turned on at the same time.

 
## Components:

1) Microcontroller:  We use Arduino Uno is used as microcontroller here.
2) Water level sensor: We have used a float sensor here. This float sensor is used to detect the level of the water inside a water tank. Ideally, this sensor should be attached to the top lid of the water tank or the liquid tank. The float attached to the sensor will move up and down as the water level increases or decreases.
3)1-Buzzer: On the output side, we have the main component to alert the user and that is a piezoelectric buzzer. This buzzer is turned on whenever the water level is above the threshold level
4)Comparator: This comparator has second input from a variable resistor. This variable resistor is used to decide the threshold water level for which the buzzer should be turned on.
5)LCD Display: We also have a Red LED for the visual indication of the threshold level. LED and buzzer are turned on at the same time.

# Case Study 2
# Washing Machine 
![embedde](https://user-images.githubusercontent.com/46950972/154841160-d8c08454-0d49-4d2c-bdd8-a89706f937d2.png)

## High level Requirements
- Washing machine should provide one option to wash their laundry quickly.
- User should make sure that higher the RPM, the faster it rotates to remove water from cloths.
- User should make sure that water supply is given before starting.
- User make sure that wheather detergent and other things are placed in given space.

## Low level Requirements
-  User should place their cloths into the washing machine.
-  Once after complition washing cloths it should notify using buzzer.
## Components
1) Power Supply
In the power supply, step doen transformer is used to reduce the nececcery voltage for the control unit and other components.
2)Microcontroller
Microcontroller is used to cotrol the process of washing cycle and to drive the external output devices such as water inlet value, water drain value.
3)Driver Circuit 
The driver circuit gives signal to power electronics devices such as relays, triacs.
4)Water level sensor 
It detects the water level in the tub.
5)Motor control 
The motor can be used to agitate the drum by switching the field winding with respect to the armature.
