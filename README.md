# AssistHand: Errand Assistance Platform <img src="logo.png" alt="AssistHand Logo" width="40" height="40"> 


🌟 Welcome to AssistHand, your go-to platform for finding reliable individuals to run your errands. Whether you need groceries, a quick pickup, or help with various tasks, AssistHand connects you with trustworthy helpers in your community. The platform features a robust Django backend for seamless server operations and a sleek React JS frontend for an intuitive user interface.🚀

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Links](#links)

## Features

### 1. User Authentication
One time password verification through mobile SMS is used to authenticate users.

### 2. Task Listings
Post and browse tasks effortlessly. Users can specify task details, location, and set the budget.

### 3. Real-Time Updates
Experience real-time updates on task status, communication with helpers, and completion notifications.

### 4. Task Matching Algorithm
Our smart algorithm connects users with the most suitable helpers based on location, availability, and task expertise.

### 5. Messaging System
Built-in messaging allows seamless communication between users and helpers to clarify task details and coordinate.

### 6. Review and Rating
Leave and receive reviews and ratings to build a community of reliable helpers and satisfied users.

### 7. Notifications
Receive timely notifications for task updates, messages, and new task opportunities.

## Installation

Follow these steps to set up AssistHand locally:

### Prerequisites
- Python (3.9 or above)
- Django (4.0)
- Node.js (18.15.0 or above)
- npm (9.5.0)

### Backend (Django)
1. Set up the server:
   ```bash
   git clone https://github.com/assist-hand/server.git
   cd server/
   python -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
   python manage.py migrate
   python manage.py createsuperuser
   python manage.py runserver


### Front-end (React JS)
1. Set up the UI:
   ```bash
   git clone https://github.com/assist-hand/app-ui.git
   cd app-ui/
   npm install
   npm start



## Usage

1. Open your web browser and go to `http://localhost:3000` to access the AssistHand web application.
2. Create an account by providing a phone number and get the OTP from the terminal of the running server.
3. Add environment variable in UI terminal to use remote service as the BE.
```
    $REACT_APP_PRODUCTION=1
```
4. Ensure you've populated the database through `http://localhost:8000/admin-panel` (using the superuser created), when running locally.

## Links

1. UI/UX design : https://figma.com
2. System design : https://docs.google.com/spreadsheets/d/1vKvkaMWE53IQnW-ejmScK8iRKmx4tecQvzgppkFp34s/edit#gid=1406017268
3. Software plan : https://docs.google.com/spreadsheets/d/1vKvkaMWE53IQnW-ejmScK8iRKmx4tecQvzgppkFp34s/edit#gid=1406017268
3. Task plan : https://github.com/orgs/Assist-Hand/projects/5
