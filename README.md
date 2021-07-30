# EmbeddedC

## Simulation

- Both the switches are OFF, so the LED and Heater is turned OFF.

  ![Simulation1](Simulation/Simulation1.JPG)

- The seat sensor is turned ON while the heater button is OFF, LED glows since the person is seated in the car but heater is turned OFF.

  ![Simulation2](Simulation/Simulation2.JPG)

- The heater button is turned ON while the seat sensor is ON, both the LED and Heater is turned OFF because the person has exited the vehicle.

  ![Simulation3](Simulation/Simulation3.JPG)

- Both the switches are ON, Led glows and Heater is ON,

  - The temperature is at 20°C
    ![Simulation4](Simulation/Simulation4.JPG)
  - The temperature is at 25°C
    ![Simulation5](Simulation/Simulation5.JPG)
  - The temperature is at 29°C
    ![Simulation6](Simulation/Simulation6.JPG)
  - The temperature is at 33°C
    ![Simulation7](Simulation/Simulation7.JPG)

- Transmitting data to another device using UART is shown in the serial monitor.

  ![Simulation8](Simulation/Simulation8.JPG)

## Makefile contents

- `make` - To create hex and elf file in build folder.

  **Note**: The build file is automatically created once you have run the make function.

- `make clean` - To clean the build folder from the directory.
