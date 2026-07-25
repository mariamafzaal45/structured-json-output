# Structured JSON Output Using Prompt Engineering

## Overview

This project demonstrates how to make an AI return structured JSON instead of normal text. The AI is instructed to produce only valid JSON that follows a predefined schema. This makes the output easy to use in real applications.

## Objective

The objective of this project is to:

- Design a JSON schema for a real-world use case.
- Write a prompt that forces the AI to return only valid JSON.
- Test the prompt with multiple inputs.
- Validate that the JSON is correctly formatted.
- Improve the prompt after testing it with a tricky input.

## Project Files

```
structured-json-output/
│── schema.json
│── prompt.txt
│── test.py
│── test1.json
│── test2.json
│── test3.json
│── test4.json
│── test5.json
│── README.md
```

## Files Description

### schema.json
Defines the structure of the JSON output.

### prompt.txt
Contains the prompt used to instruct the AI to return only valid JSON.

### test.py
Python script used to validate that the JSON file can be parsed successfully.

### test1.json – test5.json
Sample JSON outputs generated from different customer support messages.

## How to Run

1. Clone or download this repository.
2. Open the project folder in Visual Studio Code.
3. Open the terminal.
4. Run the following command:

```bash
python test.py
```

If the JSON is valid, the program will display:

```
JSON Parsed Successfully!
```

## Technologies Used

- Python 3
- JSON
- Visual Studio Code
- ChatGPT

## Sample Use Case

The AI extracts the following information from customer support messages:

- Name
- Email
- Issue Type
- Urgency
- Summary

## Testing

The prompt was tested using five different customer messages. Each output was checked to ensure it was valid JSON.

A tricky input with missing and uncertain information was also tested. The prompt was improved by adding instructions to avoid guessing missing values.

## Conclusion

This project demonstrates how prompt engineering and JSON schemas can be combined to produce structured, predictable AI outputs suitable for software applications.
