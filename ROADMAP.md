# Project Roadmap

## Overview

This roadmap outlines the planned development phases for our project, aiming to simplify and enhance cross-language development, testing, building, and execution processes. Our goal is to create a seamless, efficient, and scalable framework for running, testing, and developing applications using multiple programming languages.

## Milestones

### Milestone 1: Single File Scripts with Dependencies
**Target Release:** Version 1.0

- **Objective:** Enable the use of a single command to lint, test, build, and run code across all supported languages.
- **Key Features:**
  - Develop a CLI tool that abstracts away language-specific commands for linting, testing, building, and running applications.
  - Ensure compatibility with the top three languages Rust,Swift,Typescript and Python for the initial release.
  - Error and warnings are standardised for linting, testing and building.
  - Options are kept to a minimum with sensible standards.

### Milestone 2:  Cross-Calling Release
**Target Release:** Version 2.0

- **Objective:** Facilitate cross-language function calls, enabling scripts to run as long-lived processes that respond to simple RPC calls.
- **Key Features:**
  - Develop a framework for exposing functions across languages that can send and receive strings via RPC.
  - Implement an easy-to-use API for making cross-language RPC calls.
  - Abstract and hide this implementation from the developer.
  - Allow the user to inquire on the time spent crossing language barriers for their script. (Console only)

### Milestone 3: Adding More Languages
**Target Release:** Version 3.0

- **Objective:** Implement more languages.
- **Key Features:**
  - Go,C#,Cpp,C etc.
     
### Milestone 4: AI conversion between languages.
**Target Release:** Version 4.0

- **Objective:** As a nodule is a self-contained script, an LLM should be able to convert between languages.
- **Key Features:**
  - Using unit tests in python to exercise code in typescript allows us to give standardised feedback to the LLM.
  - Once a scripting project is complete you can get an LLM to convert it to all languages so that it can be launched simultaneously.
  - This release should be the conversion of Nodules into all the languages and tested and shown as an example.
  - The CLI for conversion should be in python and use LLM libraries to allow the user to choose any service to provide the conversion.

## Contributing

We welcome contributions at all levels and from all areas. Whether you're a developer, a designer, or a technical writer, there's a place for you to help out. Check out our CONTRIBUTING guide for more details on getting started.

## Feedback and Suggestions

Your feedback is invaluable to us. If you have any suggestions for improving the roadmap or any features you'd like to see, please reach out through our issues page or join our community discussions.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
