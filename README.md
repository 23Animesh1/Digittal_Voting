# Online Voting System in Django

An **Online Voting System** built with **Python** and **Django Web Framework**, designed for a seamless and secure online voting experience. This project is ideal for IT students, especially in their second year, as it demonstrates real-life voting scenarios. 

## Project Features
- **Voter Panel**: Register, cast votes, view ballots, and select multiple candidates (up to 20).
- **Admin Panel**: Manage voters, candidates, and positions, tally votes, download results, and update the election title.
- **Vote Management**: Ensures each user can vote only once; provides real-time vote counting and results display.
- **User-Friendly UI**: Built with Bootstrap and Vanilla CSS for a clean, easy-to-navigate interface.

## Project Details
- **Technologies**: Python, Django, SQLite (Database)

## Installation Guide
1. **Unzip** the project and navigate to the root folder.
2. **Set up** a Virtual Environment and activate it.
3. **Install requirements**: `pip install -r requirements.txt`
4. **Run Migrations**:
   ```bash
   python manage.py makemigrations
   python manage.py migrate
