# links for the Oscilliscope Assignment 8: 
  - This link for the connection of the built-in function generator.
   link: (http://imgur.com/gallery/hEh2QPw)
  - This link is for the connection of the ossiliscope.
   link: (http://imgur.com/gallery/7WLgX39)
  -This link is for the one line program for the LED and oscilliscope connection.
   link: (http://imgur.com/gallery/IUjgB4M)
  - This link is for the loop in the program that varies the duty cycle of the LED.
   link: (http://imgur.com/gallery/I8iRtUu)
  - This link is the sevo connection also with the duty cycle of the LED being controled by the movement of the servo.
   link: (http://imgur.com/gallery/RdFtBsm) 

# Questions & Answers

What are the disadvantages of the other two serial communication channels, UART and SPI, and how does I2C improve on them?
 - SPI is only intended for short distances, the biggest problem is the pin connection and the number of pins required. Making connections from multiple devices only slaved to one master.  UART is difficult to implent into your software if intended to do so.  This task eats up alot of data and slows the system down.  Where I2C improves in these areas begins with using only 2 wires and being able to connect to 1008 slave devices, the speed isnt as fast as SPI but gets the job done more efficently.
 
I2C is a two-wire serial communication channel. What are the two wires, SDA and SCL? 
 - SCL is a Clock Sigal, & SDA is a Data Signal.
 
What distinguishes the master and the slaves? 
 - The Clock signal being located in the master is the difference between the two.
 
How are the two types of protocol frames different?
 - the first being the Adress Frame, is where the master lets the slave know where the message needs to be sent triggering one or multiple frames that are 8 bit. The second one being Data Frames, the data first is sent to the SDA which is chosen by the master or slave dependings of the R/W bit was written or read.
 
What is the most appropriate trigger for capturing an I2C frame on the oscilloscope?
 - the appropriate trigger to go with first is the SDA trigger becasue of its intial falling edge.
 
If the micro:bit is configured by default as a master, and two micro:bits, connected to each other via the SDA and SCL lines, communicate over I2C? (Bonus for a convincing argument, one way or another.)
 -
 
 
