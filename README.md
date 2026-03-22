# OSI Model Simulation in Python

## Overview

This project provides a comprehensive simulation of the OSI (Open Systems Interconnection) model layers. It is designed for educational purposes and as a tool for researching network protocol interactions in a controlled software environment.

## Project Structure

- **src/**: Core simulation logic for each OSI layer (Physical to Application).
- **docs/**: Detailed documentation on the simulation architecture and layer-by-layer methodology.
- **experiments/**: Scripts for testing data flow between simulated nodes.
- **tests/**: Unit tests for validating the behavior of individual layer abstractions.
- **scripts/**: Orchestration scripts to run end-to-end simulations.

## Implementation Details

The simulation mimics:
- **Encapsulation/Decapsulation**: Process of adding and removing headers as data moves through the layers.
- **Addressing**: Simulated MAC and IP addressing for the Data Link and Network layers.
- **Error Handling**: Basic checks for data integrity during transition between layers.

## Usage Instructions

1. Install necessary dependencies as listed in `requirements.txt`.
2. Configure simulation parameters in the `config/` directory (if applicable).
3. Execute simulation scripts from the `scripts/` folder or run individual layer tests from `tests/`.

## Future Enhancements

- Implementation of advanced routing algorithms in the Network layer simulation.
- Support for more complex Transport layer protocols (e.g., simulated TCP windowing).
- Integration of a visual dashboard for real-time packet tracking.
