# Modenling-Mass-Spring-Damper-System-using-3-methods-Matlabe

This repository provides MATLAB code and Simulink models to simulate a mass-spring-damper system using three different methods: SimScape, Simulink, and Transfer Function. Each method is illustrated with two examples to demonstrate its implementation and analysis.

## SimScape Method

SimScape is a powerful tool in MATLAB for modeling physical systems without getting touch with math staff. The following examples demonstrate its usage:

### Example 1: Single Mass System

- **Description:** Simulate a simple mass-spring-damper system with only one mass.
![Screenshot 2024-04-16 015553](https://github.com/HashimAbdulaziz/Modenling-Mass-Spring-Damper-System-using-3-methods-Matlabe/assets/88584784/5ce6852c-f1cb-4256-9642-3b32870b3520)

- **Files:** `Single_Mass_System.mlx`, `Single_Mass_System_Model.slx`

 **Simscape Model**
  ![image](https://github.com/HashimAbdulaziz/Modenling-Mass-Spring-Damper-System-using-3-methods-Matlabe/assets/88584784/379a3cee-d555-4807-b11f-6094731baf69)

  1. Plot of displacement of the mass (x) against time.
     ![image](https://github.com/HashimAbdulaziz/Modenling-Mass-Spring-Damper-System-using-3-methods-Matlabe/assets/88584784/e3f5ca0f-38da-4630-bd47-0192db198cac)

  2. Plot showing the variation of displacement with changing damping coefficient to zero.
     ![image](https://github.com/HashimAbdulaziz/Modenling-Mass-Spring-Damper-System-using-3-methods-Matlabe/assets/88584784/4aa91712-dcb7-44c9-81d4-f6ad948943ce)
  Note that: when damping coffient equal to zero it will oscillate sinusoidally to infinty 

### Example 2: Two Mass System

- **Description:** Simulate a system with two masses connected by springs and dampers.
- **Files:** `Two_Mass_System.mlx`, `Two_Mass_System_Model.slx`
  **Simscape Model**
  ![image](https://github.com/HashimAbdulaziz/Modenling-Mass-Spring-Damper-System-using-3-methods-Matlabe/assets/88584784/cde84d82-7403-416c-b003-bd9b87ff45b9)

  1. Plot of displacement of the first mass and second mass (x1, x1) against time.
  ![image](https://github.com/HashimAbdulaziz/Modenling-Mass-Spring-Damper-System-using-3-methods-Matlabe/assets/88584784/dc85948d-64cf-421b-9d7a-fc38224f2f05)

  3. Interactive plot showing the effect of changing damping coefficient using sliders to Zero for b1 and b2.
  ![image](https://github.com/HashimAbdulaziz/Modenling-Mass-Spring-Damper-System-using-3-methods-Matlabe/assets/88584784/dc199996-88cd-4ee3-a48a-97d2d3be7827)


## Simulink Method

Simulink provides a graphical environment for modeling dynamic systems. The following examples demonstrate its usage:

### Example 1: Single Mass System

- **Description:** Simulate a simple mass-spring-damper system with only one mass.
- **Files:** `Single_Mass_System.mlx`, `Single_Mass_System_Model.slx`
- **Figures:** 
  1. Plot of displacement of the mass (x1) against time.
  2. Plot showing the variation of displacement with changing damping coefficient.

### Example 2: Two Mass System

- **Description:** Simulate a system with two masses connected by springs and dampers.
![image](https://github.com/HashimAbdulaziz/Modenling-Mass-Spring-Damper-System-using-3-methods-Matlabe/assets/88584784/4f6067c7-a738-4820-9388-60f5769cd5eb)

- **Files:** `Two_Mass_System.mlx`, `Two_Mass_System_Model.slx`
- **Figures:** 
  1. Plot of displacement of the first mass (x1) against time.
  2. Plot of displacement of the second mass (x2) against time.
  3. Interactive plot showing the effect of changing damping coefficient using sliders.

## Transfer Function Method

Transfer function modeling provides a mathematical representation of system dynamics. The following examples demonstrate its usage:

### Example 1: Single Mass System

- **Description:** Derive and simulate the transfer function of a single mass system.
- **Files:** `Single_Mass_System.mlx`
- **Figures:** 
  1. Plot of displacement of the mass (x1) against time.
  2. Pole-zero plot of the transfer function.

### Example 2: Two Mass System

- **Description:** Extend transfer function approach to a system with two masses.
- **Files:** `Two_Mass_System.mlx`
- **Figures:** 
  1. Plot of displacement of the first mass (x1) against time.
  2. Plot of displacement of the second mass (x2) against time.
  3. Pole-zero plot of the transfer function.

Each method includes MATLAB Live Script (.mlx) files for detailed explanations and Simulink models (.slx) for simulation. Explore the examples to understand and compare different approaches to modeling mass-spring-damper systems in MATLAB.
