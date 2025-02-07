# Event Management System

## Overview
- The Event Management System is a web application that allows event organizers to create, manage, and track events, while participants can register for events and receive confirmation emails. It streamlines event registration, automates participant tracking, and ensures a smooth event management process.

## Objective
- Enable organizers to create and manage events with details like date, time, venue, and capacity.
- Allow participants to register for events.
- Provide an admin dashboard for event monitoring and participants management.

## Project Workflow
1. **User Authentication & Role Management**  
   - Users sign up or log in  
   - Authentication is handled using Firebase Auth or JWT  
   - Role-based access control:  
     - Admin manages events  
     - Users browse and register for events  

2. **Admin Panel - Event Management**  
   - Admin logs in and accesses the dashboard  
   - Admin creates, edits, updates, and deletes events  
   - Events are stored in the database  
   - Admin views the list of registered participants  

3. **User Event Browsing & Registration**  
   - Users visit the events page  
   - Users view event details like title, date, time, and location  
   - Users register for events  
   - Registrations are saved in the database  
   - Users can view their registered events  

4. **Admin View - Participant Management**  
   - Admin selects an event to view registered users  
   - The system displays a list of participants  

5. **Database & API Integration**  
   - Events and registrations are stored in Firestore/MongoDB  
   - API handles event operations, authentication, and registrations  



## Tech Stack
- Frontend : React.js, Tailwind CSS
- Backend : Node.js
- Database : MongoDB.
- Deployment : Netlify,Render

   
