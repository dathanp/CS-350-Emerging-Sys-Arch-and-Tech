# CS-350-Emerging-Sys-Arch-and-Tech
Summarize the project and what problem it was solving.

1.LED State machine, this project was to create a system that can adapt and effectively manage hardware as well as respond to user input through UART. It solves the problem of managing transitions between states ON, OFF through button presses.
2. Thermostat, this project controlled an LED to indicate the heating state through  GPIO, it also managed state on and off which was based on temperature and set points.

What did you do particularly well?

1. I was able to document the state machine into code and had transitions between the states by button presses. I used GPIO to control the LED and used UART for the serial communication.
2. I was able to create state machine functionality which allowed me to manage the heating states when the sensor detected temperature.

Where could you improve?

1. For my LED state machine, I could have created better error handling in case invalid UART inputs were made just so that the system is more full proof.
2. I could have created better testing methods to solve edge cases like in case the state changes too fast or if it receives an unusual temperature. 

What tools and/or resources are you adding to your support network?

1. I used online resources as well as school resources provided by my professor, I also used draw.io to create a UML design of this project.
2. I needed to refer to API documentation of UART2, the Embedded systems forums also helped aid me with integrating hardware such as the temperature sensor. TI's documentation was also a very big help with understanding how to configure these tasks.


What skills from this project will be particularly transferable to other projects and/or course work?

1. Having the ability to design state machines is very important for embedded systems, as well as when it comes to software development.
2. Creating a real-time system that has task schedulers and timers was an amazing skill I gained. As well as being able to manage many different types of peripherals to have a working system.


How did you make this project maintainable, readable, and adaptable?

1. I organized my code so that it is modular in order for the state machine to have proper transitions, it had UART handling and great LED control. It was readable because I made sure to use naming conventions that made sense and added comments trhoughout my code to explain functionality. Lastly, having a diagram made for my project will help me understand its functionality in the future.
2.  I made my project maintainable by keeping functions separate and having them in reusable functions, for instance a function for temperature reading or updating an LED. It is readable because of its well documented task schedular logic. My system is adaptable because of the extra features like the temperature sensor so in case you want to add more, my state transitions will be able to handle it.

