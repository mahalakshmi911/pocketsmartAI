# PocketSmart AI – Smart Budget & Recommendation Assistant

A student-friendly FastAPI web project inspired by the supplied project document.

## Modules
- Home Interior Budget Planner
- Party Budget Planner
- Jewelry Budget Planner with optional outfit upload
- Register / Login / Logout
- Recommendation history
- Gemini API integration with local fallback demo recommendations

## Requirements
Python 3.10+ recommended.

## Run on Windows
1. Extract the ZIP.
2. Open the project folder in Command Prompt / PowerShell.
3. Create a virtual environment:
   `python -m venv venv`
4. Activate:
   `venv\Scripts\activate`
5. Install packages:
   `pip install -r requirements.txt`
6. Copy `.env.example` to `.env`.
7. Optional: put your Gemini API key in `.env`.
8. Start:
   `python main.py`
9. Open:
   `http://127.0.0.1:8000`

## Run without Gemini
The project still works in demo mode using built-in fallback recommendations.

## Important
The supplied document mentions Amazon, Flipkart, IKEA, Swiggy, Zomato and OYO. This student project uses those names as recommendation-platform examples; it does not scrape or call their private APIs.

## Project structure
main.py
requirements.txt
.env.example
README.md
templates/
static/
