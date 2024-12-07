# Lamport's Clock Simulation - Distributed Systems Assignment

## Assignment Overview

This project is part of my assignment on **Distributed Systems**, where I have implemented a simulation of **Lamport's Logical Clock** in Python. Lamport's Clock is a key concept in distributed systems, used to order events and synchronize processes without relying on a physical clock. The simulation allows for multiple processes to generate events, send and receive messages, and synchronize their clocks.

## Objective

The main objective of this assignment was to implement and demonstrate the working of Lamport's Logical Clock, which is used for event ordering in distributed systems. The system consists of several processes, each with its own logical clock, and the processes communicate via messages. When a process sends a message to another, it includes its logical clock value. The receiving process updates its clock based on the received timestamp, ensuring a consistent order of events across processes.

## Features Implemented

1. **Local Event Generation**: Each process can generate local events, which increment its Lamport clock.
2. **Message Sending**: A process can send a message to another process along with its current timestamp.
3. **Message Reception**: A process can receive a message and update its clock based on the received timestamp.
4. **Clock Display**: The simulation allows the user to display the current timestamp of all processes.
