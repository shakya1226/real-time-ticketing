# Real-Time Event Ticketing System

The Real-Time Event Ticketing System is designed to efficiently manage ticket sales for events using a real-time approach. It includes a command-line interface (CLI) implemented in Java for managing configurations, a Spring Boot backend for handling business logic and APIs, and a React frontend for user interaction.

## Features

- **Vendor Management**: Vendors have the ability to add tickets to the system at a customizable rate.
- **Customer Access**: Customers can purchase tickets instantly.
- **Dynamic Configuration**: Modify the ticket pool size, release rates, and retrieval rates on the fly.
- **Real-Time Status**: Keep track of ticket availability in real time.
- **Multithreading Support**: Handles multiple concurrent accesses to the ticket pool efficiently.
- **JSON Configuration**: Save and load system configurations using JSON files.

## Architecture

- **Frontend**: React application for a user-friendly interface.
- **Backend**: Spring Boot application providing APIs for managing ticket transactions and configurations.
- **CLI**: Java-based interface for configuring and testing the system.

## Prerequisites

- **Java Development Kit (JDK) 17 or higher**
- **Node.js, npm, and VS Code** (for the React frontend)
- **Maven** (for the Spring Boot backend)
- **Git** (to clone the repository)
