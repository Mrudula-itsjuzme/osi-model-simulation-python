# OSI Model Simulation in Python

An educational Python simulation of the OSI network model, showing how data moves through networking layers using encapsulation, addressing, and basic integrity checks.

---

## Problem statement

The OSI model is easier to understand when you can see data moving layer by layer instead of only memorizing theory.

This project simulates how data is passed through the Physical, Data Link, Network, Transport, Session, Presentation, and Application layers.

---

## What this project demonstrates

- layer-by-layer data flow
- encapsulation and decapsulation
- simulated headers
- MAC and IP-style addressing concepts
- basic data integrity checks
- modular layer abstractions
- end-to-end network communication flow

---

## Simulation flow

```text
Application Layer
       ↓
Presentation Layer
       ↓
Session Layer
       ↓
Transport Layer
       ↓
Network Layer
       ↓
Data Link Layer
       ↓
Physical Layer
       ↓
Transmission
       ↓
Reverse Decapsulation
```

---

## Repository structure

```text
osi-model-simulation-python/
├── src/          # core simulation logic for each OSI layer
├── docs/         # layer-by-layer documentation
├── experiments/  # data-flow experiments
├── tests/        # unit tests for layer behavior
├── scripts/      # end-to-end simulation runners
└── README.md
```

---

## How to run

```bash
git clone https://github.com/Mrudula-itsjuzme/osi-model-simulation-python.git
cd osi-model-simulation-python

pip install -r requirements.txt
```

Run the simulation scripts from the `scripts/` folder or execute individual tests from the `tests/` folder.

---

## Tech stack

- Python
- Computer networks
- OSI model
- Protocol simulation
- Unit testing

---

## Future improvements

- add routing algorithms at the Network layer
- add simulated TCP windowing
- add packet-loss and retransmission scenarios
- create a visual dashboard for packet tracking
- add CLI options for selecting simulation scenarios

---

## Author

Built by [Pedamallu Sai Mrudula](https://github.com/Mrudula-itsjuzme) as part of a computer-networks and systems-learning portfolio.
