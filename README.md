# personal_tutor_booking_system
A Django-based Personal Tutor Booking System that enables students to schedule meetings with tutors, track engagement, and manage records with Outlook integration.r

Personal Tutor Booking System
- This project is a web-based Personal Tutor Booking System developed using Django as part of the CIS4509 module. It is designed to support student–tutor interactions by enabling efficient scheduling, tracking, and management of one-to-one meetings.

Project Aim
- To create a system that allows students to easily book meetings with their personal tutors while providing tutors with tools to manage appointments, track attendance, and maintain meeting records.

Key Features
- Students can book meetings with available tutors

Role-based access:
- Students can only select tutors
- Tutors can only view/select their assigned students
- Calendar view and meeting scheduling
- Meeting reminders (planned integration)
- Track student engagement and attendance
- View meeting history and discussion notes
- Integration with Outlook / Microsoft Bookings (conceptual or partial)

Technologies Used
- Python (Django) – Web framework
- SQLite – Database (default Django setup)
- HTML/CSS – Frontend templates
- Microsoft Outlook / Bookings – External integration (design consideration)

System Structure
- Models for managing users, meetings, and roles
- Forms for booking and managing meetings
- Views to control user access and functionality
- Templates for user interface (student/tutor dashboards)

Access Control
- Students can only view and book meetings with tutors
- Tutors can only access their assigned students
- Data visibility is restricted based on user roles

Future Improvements
- Full Outlook calendar integration
- Email notifications and reminders
- Enhanced dashboard with analytics (e.g., engagement trends)
- UI/UX improvements

Purpose
- This project demonstrates practical skills in:
- Web development using Django
- Database design and management
- Role based system implementation
- Real-world problem solving in an academic support context

Download: https://www.python.org/downloads/ (Version: Python 3.12.7)
