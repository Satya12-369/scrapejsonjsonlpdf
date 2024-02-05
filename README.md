# Documentation Converter

## Overview
The Documentation Converter is a versatile tool crafted to transform PDF documents into structured JSON and JSONL formats. This conversion is essential for training advanced AI models, ensuring they consume and understand the information as intended. The tool is designed with a focus on usability and automation, streamlining the process to facilitate ease of integration into AI-powered systems.

## Features
- **PDF to JSON**: Converts PDF documents into a JSON format, preserving the structure and content of the original documentation.
- **JSON to JSONL**: Transforms JSON files into the JSONL (JSON Lines) format, which is suitable for machine learning model training, including GPT-3.5 fine-tuning.
- **Customizable Conversion**: Through a user-friendly GUI, users can select files, specify the target directory, and manage the conversion process.
- **Progress Tracking**: A progress bar and logging system provide real-time feedback on the conversion process.
- **State Management**: The application remembers your previous session's settings, making it easy to pick up where you left off.

## Getting Started
To get started with the Documentation Converter, clone this repository to your local machine. Ensure you have the required dependencies installed, which include Python libraries such as `PyMuPDF` for PDF reading and PySide6 for the GUI components.

Installation of dependencies:
```bash
pip install PyMuPDF PySide6
```

To run the converter:
```bash
python converter.py
```

## Collaboration & Contact
This project is open to collaboration! If you have ideas for improvement, features requests, or want to use the Documentation Converter as part of a larger AI integration project, don't hesitate to reach out.

For potential collaborations or inquiries, please [send a message on Discord @sacredom369].
