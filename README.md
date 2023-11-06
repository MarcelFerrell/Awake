# AAwake

## Challenge Statement(s) Addressed 🎯
** How might we improve the in-flight catering experience for passengers to increase customer satisfaction and optimize airline operations?**

## Project Description 🤯
AAwake is a web application that allows users to set preferences and customize their catering experience. Specifically, AAwake allows users to choose whether or not to be awoken during the catering service. AAwake thrives to increase customer satisfaction, flight attendants' employee experience, and optimize in flight operations.


## Project Value 💰
 Target customer is American Airline customers. We want them to be able to enjoy all their perks while in flight. Currently in flight experience are directly connected to catering services provided by the flight attendents. As well as satifying the customers we want to increase the operations of the airline overall. By allowing flight attendents to prepare from diet soda, service times are decreased. Also when customers chose to be woken up to recieve bevergaes they then use more supplies and reduce the food waste, while optimizing the customer experience.**


## Tech Overview 💻
Full Stack Web App

Frontend - Javascript, HTML, CSS
Backend - FastAPI | Python
Database - SQLite | SQLAlchemy

## How to Run
After cloning this repository you will need to install the necessary dependencies 

pip install "fastapi[all]"

pip install SQLAlchemy

**Then you will run this command in the terminal to start the backend

uvicorn server.main:app --reload

** For the front end you will need to run both the passengerview.html && attendant.html
I am using live server. They both are set to run on local host port 5500, if you change the port you may need to update the CORS middleware in main.py to allow cross origin communication from your new port. The backend runs on port 8000.

** You can test the functionality by selecting your preferences in the passenger view then hit submit && you can verify the changes in the attendant view






