
# AI Attendance Management System

## Project Overview
The AI Attendance Management System is a Python-based project that uses the OpenRouter API to understand natural-language instructions and manage student attendance records.

## Features
- View attendance for an individual student.
- Display attendance records for all students.
- Calculate attendance percentages.
- Calculate the class average attendance.
- Update attendance for a specific day.
- Remove a day's attendance record.

## Technologies Used
- Python
- OpenRouter API
- JSON
- Requests
- Python-dotenv

## Project Files
- `main.py` – Runs the attendance application.
- `app.py` – Additional application entry point, if used.
- `attendance_tools.py` – Handles attendance operations and calculations.
- `students.json` – Stores sample student attendance data.
- `test_attendance.py` – Tests attendance calculations.
- `test_openrouter.py` – Tests the OpenRouter API connection.

## Setup Instructions
1. Install Python.
2. Open the project folder in VS Code.
3. Create and activate a virtual environment.
4. Install the required libraries:

   `python -m pip install requests python-dotenv`

5. Create a `.env` file and add your OpenRouter API key:

   `OPENROUTER_API_KEY=your_api_key_here`

6. Test the API connection:

   `python test_openrouter.py`

7. Run the application:

   `python main.py`

## Security
Never upload the `.env` file or expose your API key on GitHub. Use fictional sample student records when sharing the project.

## Learning Objectives
This project demonstrates Python programming, API integration, natural-language instruction processing, JSON file handling, and attendance calculations.
