# UIDAI Aadhaar Data Hackathon Project

Analysis and visualization of Aadhaar-related API data (Biometric, Demographic, Enrolment, etc.)

## Project Structure

UIDAI_Data_Hackathon/
├── api_data_aadhar_biometric/ # Biometric data files
├── api_data_aadhar_demographic/ # Demographic data files
├── api_data_aadhar_enrolment/ # Enrolment data files
├── my_venv/ # Local virtual environment (ignored in git)
├── requirements.txt # All required Python packages + versions
├── .gitignore
├── LICENSE
└── README.md

## Quick Setup

Follow these steps after cloning the repository:

```bash
# 1. Clone the repository
git clone https://github.com/krishna1632/UIDAI_Data_Hackathon.git
cd UIDAI_Data_Hackathon

# 2. Create a virtual environment
python -m venv my_venv

# 3. Activate the virtual environment
# Windows (PowerShell / Command Prompt):
.\my_venv\Scripts\activate

# Linux / macOS :
source my_venv/bin/activate

# 4. Install all required packages
pip install -r requirements.txt

Important Commands (Cheat Sheet)

# Activate virtual environment
.\my_venv\Scripts\activate # For Windows

# Install a new package and update requirements.txt
pip install some-package
pip freeze > requirements.txt

# Deactivate when you're done
deactivate

```
