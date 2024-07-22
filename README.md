# ATM_MACHINE
Behavioral Model for ATM Machine using Non-Syntesizable Verilog constructs.

This project involves the development of a behavioral model for an ATM machine, implemented using non-synthesizable Verilog constructs. The model simulates various operations such as card reading, PIN verification, transaction selection, and transaction execution, providing debugging outputs for each state.

Features:
->State Transitions: Implements state transitions for operations including IDLE, READING_CARD, READ_PIN, CHOOSING_TRANSACTION, PERFORMING_TRANSACTION, and EJECTING_CARD.
->Debugging Outputs: Provides clear debugging messages for each state transition to facilitate testing and verification.

Code Overview:
The main module 'ATM_MACHINE' handles the state transitions based on the current state ('ps'), next state ('ns'), and operations, while providing feedback through debugging messages.

Usage:
->Clone the repository.
->Simulate the Verilog code using your preferred simulation tool (e.g., ModelSim, Vivado).
->Verify the state transitions and debug outputs.
