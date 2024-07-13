# FPGA-Based Home HVAC Control System

## Overview
This project demonstrates an FPGA-based control system for managing a home's HVAC (Heating, Ventilation, and Air Conditioning) system, including AC, Furnace, Fan, and Display functionalities. The system aims to provide efficient and reliable control, showcasing skills relevant to FPGA design, digital logic, and system integration.

## Features
- **AC Control:** Regulates the air conditioning unit based on temperature settings.
- **Furnace Control:** Manages the furnace operations for heating.
- **Fan Control:** Controls the ventilation fan for air circulation.
- **Display Interface:** Displays current status and settings on an LCD/LED display.
- **User Interface:** Provides a user-friendly interface for adjusting settings.

## Block Diagram
![Block Diagram](images/block_diagram.png)

## Technical Details
- **FPGA Board:** [Specify the FPGA board used, e.g., Xilinx Artix-7]
- **Programming Language:** VHDL/Verilog
- **Development Environment:** Vivado Design Suite
- **Sensors:** [Specify sensors used, e.g., temperature sensors]
- **Actuators:** [Specify actuators used, e.g., relays, motors]

## How It Works
1. **Initialization:** The FPGA initializes all components and sets default parameters.
2. **Temperature Reading:** Continuously reads temperature data from sensors.
3. **Control Logic:** Based on the temperature readings and user settings, the FPGA decides whether to activate the AC, furnace, or fan.
4. **Display Update:** Updates the display with current status and allows user interaction to change settings.

## Getting Started
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/username/fpga-hvac-control.git
   cd fpga-hvac-control
