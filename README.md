
# HCMUT IC Design Lab - Single-Cycle RISC-V Processor

## Project Overview
This project involves the design and implementation of a single-cycle RISC-V processor using SystemVerilog. The processor supports 12 of the 47 RISC-V instructions, including core components such as the Arithmetic Logic Unit (ALU), register file, and control unit. The project focuses on RTL design, functional verification, and exploration of FPGA implementation.

## Technologies Used
- **SystemVerilog**: Hardware description language used for designing the processor.
- **QuestaSim**: Simulation tool for functional verification and testbench development.
- **RISC-V Architecture**: Open-standard instruction set architecture used as the foundation for the processor design.
- **DE10 Kit**: Targeted FPGA platform for potential hardware implementation.

## Responsibilities
- Designed and implemented a single-cycle RISC-V processor in SystemVerilog.
- Supported 12 out of 47 RISC-V instructions, covering:
  - Arithmetic and logical operations via the ALU.
  - Register file operations for data storage and retrieval.
  - Control unit for instruction decoding and processor control.
- Developed testbenches in QuestaSim for functional verification.
- Performed RTL synthesis to ensure design correctness.
- Explored FPGA implementation on the DE10 Kit.

## Results
- Successfully implemented a functional single-cycle RISC-V processor in SystemVerilog.
- Conducted rigorous functional verification using QuestaSim testbenches to validate processor behavior.
- Completed RTL synthesis, preparing the design for hardware realization.
- Investigated FPGA implementation on the DE10 Kit, laying the groundwork for future hardware deployment.

## Getting Started
To replicate or extend this project:
1. **Prerequisites**: Install QuestaSim for simulation and verification. Ensure access to a SystemVerilog-compatible IDE or editor.
2. **Setup**: Clone this repository and navigate to the project directory.
3. **Simulation**: Use QuestaSim to run the provided testbenches for functional verification.
4. **FPGA Implementation**: Target the DE10 Kit for hardware deployment (work in progress).
5. **Directory Structure**:
   - `/src`: SystemVerilog source files for the processor design.
   - `/testbenches`: QuestaSim testbench files for verification.
   - `/docs`: Additional documentation and design notes.

## Future Work
- Expand instruction set support to include more of the 47 RISC-V instructions.
- Optimize the design for performance and area during FPGA implementation.
- Enhance testbenches for more comprehensive coverage and edge-case testing.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments
- HCMUT IC Design Lab for providing resources and guidance.
- RISC-V Foundation for the open-standard ISA specification.
