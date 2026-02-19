Project Overview
The College Cab System is a web-based application designed to streamline campus transportation. Students can book cabs, drivers can manage trips, and admins can oversee users, bookings, and complaints. The system also provides a complaint management module to track issues reported by students and drivers.
Tech Stack:
PHP (Backend)
MySQL (Database)
HTML, CSS, Bootstrap 5 (Frontend)
JavaScript (Optional for interactivity)
Features
Student
Book cabs for campus commute.
View and track active or past bookings.
Submit complaints regarding cabs or services.
Driver
View assigned trips.
Update trip status (completed, ongoing).
View and respond to complaints.
Admin
Manage student and driver accounts.
Manage cabs and their availability.
View all bookings and complaints in one dashboard.
General
Login and registration system with role-based access.
Responsive and modern UI (Black, Green, White theme).
Easy navigation via navbar.
Folder Structure:-
college_cab_system/
│
├─ index.php
├─ about.php
├─ login.php
├─ register.php
├─ logout.php
├─ config/
│   ├─ db.php
│   └─ config.php
├─ student/
│   ├─ book_cab.php
│   ├─ my_booking.php
│   ├─ complaint.php
├─ driver/
│   ├─ driver_dashboard.php
│   ├─ assigned_trip.php
│   ├─ driver_complaint.php
├─ admin/
│   ├─ admin_dashboard.php
│   ├─ manage_users.php
│   ├─ manage_cabs.php
│   ├─ all_bookings.php
│   ├─ all_complaints.php
├─ includes/
│   ├─ header.php
│   └─ footer.php
└─ css/
    └─ style.css
