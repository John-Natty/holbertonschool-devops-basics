# Exploring Your First Network

## Introduction and Context

Network activity is usually invisible during everyday computer use. A computer selects an interface, uses local and remote addresses, consults routing information, resolves hostnames, communicates with nearby devices, and opens or listens on network sockets without requiring the user to inspect those operations directly.

In this project, you will observe those operations in a Linux sandbox. You will create small Bash scripts that display network information or perform one focused network check. Each task asks for an observable result but does not prescribe the exact command or options. You are expected to consult the provided documentation, select the appropriate utility, test your script, and compare its output with the task requirements.

The project focuses on using existing Linux networking tools, not on advanced Bash programming. Standard pipelines and simple filtering are allowed when needed, but avoid unnecessary parsing or reformatting when a utility can already produce the required result.

The correction environment is volatile. Interface names, IP addresses, MAC addresses, routes, neighbor entries, and listening ports may change. Your scripts must inspect the current environment and must not contain hardcoded network values.

## General Requirements

- You may use any repository. Place all project files inside a directory named exploring_your_first_network.
- You should include a README.md file inside the project directory.
- Create only the files required by the tasks.