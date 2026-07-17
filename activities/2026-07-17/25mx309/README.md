# Dynamic JSON-Driven Form Generator

## Overview
This project is a dynamic JSON-driven form generator built using React/Next.js. The form is generated from a JSON schema instead of hardcoding the fields. It supports input validation, nested questionnaires, and conditional field rendering.

## Features
- Generates forms dynamically from JSON.
- Supports nested sections and questions.
- Validates user inputs (for example, age must be greater than 18).
- Displays fields based on user responses (for example, Company Name is shown only if Employed is selected).
- Uses reusable React components for better maintainability.

## Architecture
The application reads the JSON schema, renders the form fields dynamically, validates user input, and applies conditional logic before submission. This modular design makes the application scalable and easy to extend.

## Big-O Analysis
- Form rendering: O(n), where n is the number of fields.
- Validation: O(n).
- Conditional logic evaluation: O(n).
- Space complexity: O(n).

## Trade-offs
Using a JSON-driven approach makes the application flexible and reusable because new forms can be created by updating the JSON schema without changing the source code. However, processing large and deeply nested schemas may slightly increase rendering time.

## Technologies Used
- React
- Next.js
- JavaScript
- JSON
