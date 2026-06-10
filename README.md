# clump

Beta version of clump, a full-stack calendar Flask web app for the Wellesley College 
community. This project aims to provide a centralized platform where users can form groups (or clumps), 
whether for convenience, companionship, or saving money. Users can access multiple categorical calendars, 
create and view events for others to join, and establish lines of communication under event-specific chat 
forums to coordinate plans. 

## Demo
[Check out clump in action!](https://drive.google.com/file/d/1tjqhP267JTkPPPoezdx8gc6kjcRQIp0T/view?usp=sharing)

## Built With
Flask, Python, SQL, JavaScript

## Features
- User authentication (Wellesley email required, passwords hashed with bcrypt, 
  thread-safe signups)
- Weekly calendar view with toggleable event categories
- Create, edit, join, and leave events 
- Event-specific comment forums 
- User profiles with photo and file upload
- Client and server-side form validation

## Structure
- `app.py` — main routes and backend functionality
- `event.py` — event-related database operations
- `profile.py` — profile-related database operations
- `forum.py` — forum/comment-related database operations
- `form.py` — form handling and file upload logic
- `templates/` — HTML templates for the site
- `static/` — CSS and JavaScript files
- `uploads/` — stores user-uploaded event files
- `profile_uploads/` — stores user-uploaded profile photos

## Notes
Built as a collaborative course project (CS304, Fall 2025) with Bessie Li and Samiksha Singh. 
