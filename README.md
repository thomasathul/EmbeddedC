# EmbeddedC

## Simulation

- Both the switches are OFF, so the LED and Heater is turned OFF.
  ![Simulation1](Simulation/Simulation1.jpg)

- The seat sensor is turned ON while the heater button is OFF, LED glows since the person is seated in the car but heater is turned OFF
  ![Simulation2](Simulation/Simulation2.jpg)

- The heater button is turned ON while the seat sensor is ON, both the LED and Heater is turned OFF because the person has exited the vehicle
  ![Simulation3](Simulation/Simulation3.jpg)

- Both the switches are ON, Heater is ON

  - The temperature is at 20%
    ![Simulation4](Simulation/Simulation4.jpg)
  - The temperature is at 25%
    ![Simulation5](Simulation/Simulation5.jpg)
  - The temperature is at 29%
    ![Simulation6](Simulation/Simulation6.jpg)
  - The temperature is at 33%
    ![Simulation7](Simulation/Simulation7.jpg)

- Transmitting data to another device using UART is shown in the serial monitor
  [!Simulation8](Simulation/Simulation8.jpg)

## Makefile contents

- `make` - To create hex and elf file in build folder.

  **Note**: The build file is automatically created once you have run the make function.

- `make clean` - To clean the build folder from the directory.
