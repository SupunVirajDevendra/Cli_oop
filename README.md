# Real-Time Event Ticketing System - Command-Line Interface (CLI)

## Introduction

This is the command-line interface (CLI) component of the Real-Time Event Ticketing System. It provides a text-based interface to configure and operate the ticketing simulation, offering an alternative to the graphical UI. It supports all operations such as creating vendor or customers or setting limits for ticket availability. This allows easy configuration from within terminal.  It interfaces directly with backend and thus relies on configuration from other modules that handle API requests. This interface aims to replicate behavior as intended in overall project specifications in a thread-safe fashion and should support operations provided in a traditional UI, however it will rely only on text input as an alternative.

## Technologies Used

*   **Language:** Java 21
*   **Libraries:** standard java console handling tools
