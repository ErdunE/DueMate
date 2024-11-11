# DueMate

**DueMate** is a unified bill management and payment reminder application designed to help users keep track of various payment deadlines and simplify bill payments all in one place.

## Overview
DueMate is aimed at reducing the hassle of managing multiple bill payment platforms and deadlines. With DueMate, users can view and pay all their bills in one application, receive timely reminders, and keep their finances organized effortlessly.

## Features
- **Unified Bill Overview**: Manage and track multiple bills from different platforms in one place.
- **Deadline Reminders**: Get notifications before each payment is due, reducing the chance of missing deadlines.
- **Future Integration for Payment Processing**: Plan to support in-app bill payments to simplify the payment process even further.

## Installation

### Prerequisites
- **Python 3.8+** is required.

### Quick Start
1. **Clone the Repository**:
    ```bash
    git clone https://github.com/ErdunE/DueMate.git
    cd DueMate
    ```

2. **Set Up Virtual Environment**:
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    # For Windows use: venv\Scripts\activate
    ```

3. **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Application**:
    - If using Django:
      ```bash
      python manage.py runserver
      ```
    - If using FastAPI:
      ```bash
      uvicorn main:app --reload
      ```

5. Open your browser and navigate to `http://127.0.0.1:8000` to see the app in action.

## Project Structure

```plaintext
DueMate/
├── src/
│   ├── core/                       # Core application logic
│   │   ├── models/                 # Data models (e.g., Bill, User)
│   │   ├── services/               # Business logic for bill management, reminders
│   │   └── utils/                  # Utility functions and helpers
│   ├── api/                        # API endpoint definitions
│   │   ├── routes/                 # Individual route definitions or view functions
│   │   └── dependencies/           # Dependencies for routing, security, etc.
│   ├── config/                     # Configuration files and environment settings
│   ├── main.py                     # Main entry point for FastAPI/Django
├── tests/                          # Test files
│   ├── unit/                       # Unit tests for models, services
│   ├── integration/                # Integration tests for API endpoints
│   └── e2e/                        # End-to-end tests
├── docs/                           # Documentation files
│   └── README.md                   # Main project README
├── requirements.txt                # Project dependencies
├── LICENSE                         # Open source license
└── .gitignore                      # Git ignore file
