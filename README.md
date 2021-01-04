# java-code
data structures and algorithms implementations using java
# 8086_steppermotor_assembly
# Used Devices
- 8086 microprocessor
- 74HC373 Latch
- 8255A I/O device
- Stepper Motor
- ADC0804 Digital to Analog Converter
- L293D Motor Driver Ic
- 2N1711 NPN Transitor
- Resistors
- LED
- Switch
- potentiometer
- Battery
# Resources
* [8086] - 8086 pinout
* [74HC373] - Latch pinout
* [8255A] -8255A I/O device
* [Stepper Motor] - Stepper Motor
* [ADC0804] - Digital to Analog Converter
* [L293D] - Motor Driver Ic
* [2N1711] -NPN transistor

 [8086]: <https://www.tutorialspoint.com/microprocessor/microprocessor_8086_pin_configuration.htm>
 [74HC373]: <https://assets.nexperia.com/documents/data-sheet/74HC_HCT373.pdf>
 [8255A]: <https://www.tutorialspoint.com/microprocessor/microprocessor_intel_8255a_programmable_peripheral_interface.htm>
 [Stepper Motor]: <https://www.monolithicpower.com/en/stepper-motors-basics-types-uses>
 [ADC0804]: <https://www.engineersgarage.com/knowledge_share/adc0804-pinout/> 
 [L293D]: <https://components101.com/l293d-pinout-features-datasheet>
 [2N1711]: <https://www.dummies.com/programming/electronics/diy-projects/electronics-projects-how-to-create-a-transistor-not-gate-circuit/>
 
 # Circuit Diagram
 ![alt circuit](https://raw.githubusercontent.com/Mohamed-Fathy-Salah/8086_steppermotor_assembly/main/images/Circuit%20Diagram.PNG)
 
# Features
* Change direction of rotation

    ![rotate](/images/rotate.gif "rotate GIF")


* Change rotation speed
    <p align="center">
      <table>
       <tr>
         <td>Slow</td>
         <td>Mid</td>
         <td>Fast</td>
       </tr>
         
     <tr>
      <td>sfsdf</td>
       <td>sdfsd</td>
       <td>dsf</td>
     </tr>
     <tr>
       <td>dsf</td>
       <td>sdff</td>
       <td>dsf</td>
     </tr>
     </table>
       
    | Slow | Mid | Fast |
    |:----:|:----:|:----:|
    |![slow](/images/slow.gif "slow speed rotation")|![mid](/images/mid.gif "mid speed rotation")|![fast](/images/fast.gif "fast speed rotation") |
    </p>
        
    
* On/Off Motor

    ![on/off](/images/onoff.gif "on/off GIF")
    
    
* Full/Half step

    ![on/off](/images/halfstepfullstep.gif "half/fullstep GIF") 
    
    
* Adjusting speed

    ![Speed](/images/speed.gif "speed GIF")    
        
    
    
## things to be added to readme file
 - Explanation for the code flow
 - Explanation how we control speed in motor 
 - Explanation for each component :
   - stepper motor 
   - 8255A - I/0 device
   - 74hc373 latch
   - l293d driver
   - ADC0804 converter
 - images for components
 - Explanation of half and full cycle
 - Explanation for getspeed and getdsplyd equation and function
 - Explanation for display function    

## Team members
- [Mohamed Fathy](https://github.com/Mohamed-Fathy-Salah)
- [Omar Mohamed](https://github.com/omarmohamed101)
- [Ahmed Nashaat](https://github.com/AhmadNashaat0)
- [Ahmed Yasser](https://github.com/ahmadyasser01)
- [Shahenda Hamdy](https://github.com/shahendahamdy)
