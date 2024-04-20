# EEE3088F Group 10 Micro-Mouse Project 2024

## Project Overview
The goal of the Micro-Mouse Project is designing and building a maze-solving robot, inspired by the principles and competition of Micro-Mouse robots. This project focuses on the hardware development of the robot, particularly the sensing and power subsystems, while integrating provided processor and motherboard modules.

### Components
- **Processor Module:** Utilizes a STM32L476 microcontroller for processing and programming.
- **Motherboard Module:** Serves as the foundational circuit board connecting all the other modules.
- **Sensing Module:** Designed to detect obstacles, aiding the robot in navigation.
- **Power Module:** Manages power distribution, motor operation, and battery charging.

## Installation & Setup
This section will guide you through setting up your development environment and assembling the Micro-Mouse robot.

### Prerequisites
- STM32CubeIDE for firmware development.
- Basic soldering equipment and electronic component handling knowledge.
- KiCad or any other electronics CAD software

### Assembly Instructions
1. **Processor & Motherboard Connection:** Start by connecting the processor module to the motherboard using the provided pin headers.
2. **Sensing Module Assembly:** Follow the schematic in `Docs/Sensing_Module_Schematic.pdf` to assemble your sensing module. Attach it to the motherboard as indicated.
3. **Power Module Assembly:** Assemble the power module according to `Docs/Power_Module_Schematic.pdf` and attach it to the designated motherboard location.
4. **Final Assembly:** Secure all connections and mount the assembled motherboard into the chassis and connect the motors and battery.

## Usage
To operate the Micro-Mouse:
1. **Firmware Upload:** Use STM32CubeIDE to open the project from `Firmware/` and flash it onto the processor module.
2. **Power On:** Switch on the Micro-Mouse using the power module's ON/OFF switch.
3. **Maze Testing:** Place the Micro-Mouse at the start of a maze and observe its operation and maze-solving capability.

## Contributing
We welcome contributions to the Micro-Mouse Project! If you have suggestions, improvements, or bug fixes, please follow the steps below:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.

## Project Structure
- `/Firmware`: Contains all firmware code for the Micro-Mouse.
- `/Docs`: Documentation, including module schematics and assembly guides.
- `/Tools`: Auxiliary tools for development and testing.
- `/Designs`: CAD designs for optional chassis and mechanical parts.

## Support
For support, please open an issue in the repository or contact the project maintainers directly via email.

## Acknowledgements
- **Veritasium:** For the inspirational content on Micro-Mouse robots.
- **STM32L476 Community:** For resources and support in firmware development.

## License
This project is licensed under the MIT License - see the `LICENSE` file for details.

---

We hope this project inspires and educates all participants and observers alike. Happy building!
