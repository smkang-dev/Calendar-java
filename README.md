# Calendar-Java

## Project Overview
A desktop-based calendar application developed using Java Swing.  
Users can add, view, and manage schedules through an intuitive graphical user interface.

## Features
- View schedules by date
- Add schedules (title, time, description)
- Delete schedules
- Manage schedule lists
- GUI-based interaction using Java Swing

## Tech Stack
- **Language:** Java
- **GUI:** Java Swing
- **IDE:** IntelliJ IDEA

## Project Structure
- `CalendarGUI.java` : Main GUI and event handling
- `ScheduleManager.java` : Schedule management logic
- `HumanScheduleManager.java` : Extended user schedule management
- `ScheduleEvent.java` : Schedule data model

## Design Highlights
- Designed a separate `ScheduleEvent` class to represent schedule data as objects.
- Separated schedule management logic from the GUI through the `ScheduleManager` class.
- Improved maintainability by separating the presentation layer from business logic.

## Learning Outcomes
- Developed a desktop GUI application using Java Swing.
- Practiced object-oriented programming principles in Java.
- Gained experience in separating UI components from application logic.
- Improved understanding of event-driven programming.
