# dc-motor-control-pic32

In this project, I designed and implemented a DC motor control system using the PIC32MX795F512L microcontroller on the Explorer 16/32 development board, programmed with MPLAB X IDE. The system offers three control modes: manual (potentiometer-based), proportional (P), and proportional-integral (PI) control, which allow precise control of motor speed and direction.

To achieve this, I used UART communication to receive reference angles from MATLAB, implemented PWM signals through Output Compare (OC) modules for speed control, and processed rotary encoder signals with change notification interrupts for real-time angle feedback. I developed control algorithms to compare the current and target angles, enabling the motor to adjust its speed and direction based on user-selected control modes.

Key Features and Technologies Used:
Control Algorithms: Implemented Proportional (P) and Proportional-Integral (PI) control to manage motor speed and direction.
UART Communication: Integrated two-way communication with MATLAB for sending reference angles and receiving real-time feedback.
PWM Motor Control: Generated PWM signals via Output Compare (OC) modules to control motor speed.
Encoder Feedback: Used rotary encoders and processed signals through change notification interrupts to track the motor’s current angle.
H-Bridge Driver: Controlled motor direction using a Dual MC33926 H-Bridge motor driver.
Hardware Inputs: Integrated hardware switches to toggle between manual, P, and PI control modes.
Development Tools: C programming with MPLAB X IDE and angle tracking with MATLAB for real-time visualization.
This project strengthened my skills in embedded systems, real-time control, motor dynamics, and hardware-software integration, giving me hands-on experience with microcontrollers, UART protocols, and control theory.
