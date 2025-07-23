# Windows-11-Clone-made-by-using-html-css-and-javascript
I made this Windows 11 Clone using html, css and javascript it is still incomplete I am still working on it

Windows 11 Clone

Overview

This project is a web-based simulation of the Windows 11 interface, built using HTML, CSS, and JavaScript. It mimics the look and feel of Windows 11, including a start menu, taskbar, widgets, and interactive elements like draggable windows and a search bar. The project is designed to be responsive on larger screens but includes a mobile compatibility warning for smaller screens.
Features

Taskbar: A fixed bottom navigation bar with system icons, app shortcuts, and date/time display.
Start Menu: A grid-based app launcher with a search functionality to filter apps dynamically.
Widgets Panel: A sidebar with placeholders for weather, calendar, gallery, video, and to-do list widgets.
Draggable Windows: Simulated application windows that can be moved, maximized, minimized, or closed.
Shutdown Animation: A virtual shutdown effect triggered by the power button.
Responsive Design: Optimized for desktop screens (minimum 800px width, 600px height) with a fallback warning for unsupported devices.
Search Functionality: Filters app tiles in the start menu based on user input.

File Structure

index.html: Main HTML file containing the structure of the interface, including the taskbar, start menu, and widgets.
on.html: Placeholder HTML file (currently minimal, likely for future use).
time.html: Contains HTML for time-related components (currently minimal).
user.html: Contains user profile selection interface.
style.css: CSS file with styling for the interface, including glassmorphism effects, animations, and responsive design.
script.js: JavaScript file handling interactivity, such as toggling menus, dragging windows, filtering apps, and updating date/time.
images/: Directory for background images and app icons (e.g., 1dark.jpg for the desktop background).

Installation

Clone or download the repository to your local machine.
Ensure you have a web server (e.g., Live Server in VS Code) or open index.html directly in a modern web browser.
Place the images folder in the same directory as index.html to ensure background images and app icons load correctly.
Open index.html in a browser with a minimum resolution of 800x600 pixels.

Usage

Taskbar: Click the Windows logo to open the start menu, the search icon to open the search bar, or the widget icon to toggle the widgets panel.
Start Menu: Type in the search bar to filter apps. Click an app icon to open a simulated window.
Widgets: Toggle the widgets panel to view placeholders for weather, calendar, etc. (currently marked as "coming soon").
Windows: Drag the top bar of an app window to move it. Use the maximize, minimize, or close buttons to control the window.
Shutdown: Click the power button in the start menu to trigger a virtual shutdown animation. Click anywhere to return to the desktop.
Full-Screen Mode: Press F11 for full-screen mode or Ctrl + - to zoom out if needed.

Styling

Uses a glassmorphism design with blurred backgrounds and translucent elements.
Custom CSS variables (e.g., --nav-height, --w11-logo-gradient) for consistent theming.
Animations for transitions, such as the start menu sliding in or the shutdown effect.
Responsive media queries to adjust layout for different screen sizes and hide elements on smaller screens.

JavaScript Functionality

Dynamic Date/Time: Updates the system date and time every minute.
Window Management: Handles dragging, maximizing, minimizing, and closing app windows.
Search Filtering: Filters app tiles based on real-time input in the start menu search bar.
Event Listeners: Manages clicks, mouse movements, and window resizing for a smooth user experience.
Device Compatibility Check: Displays a warning if the screen size is below 800x600 pixels.

Limitations

Mobile Support: The project is not optimized for mobile devices (screen width < 800px or height < 600px) and displays a warning on unsupported screens.
Placeholder Content: Widgets and some app windows currently display "coming soon" placeholders.
Static Assets: Requires the images folder to be correctly set up for backgrounds and icons.

Future Improvements

Implement functional widgets (e.g., weather API integration, calendar events).
Add more interactive app windows with actual content.
Enhance mobile compatibility for smaller screens.
Expand user profile functionality in user.html.
Add settings panel for theme customization.

Dependencies

No external libraries are required; the project uses vanilla HTML, CSS, and JavaScript.
Icons and images should be provided in the images folder.

Notes

This is a simulation and not a full operating system. It is intended for demonstration purposes.
Ensure your browser is up-to-date for the best experience with CSS animations and grid layouts.
For optimal viewing, use a desktop browser with a resolution of at least 800x600 pixels.

License

This project is for educational and demonstration purposes. 

© Copyright 2025 Ahmad Samama. All Rights Reserved.

I am Providing some images of the Project Below:

1. Power ON

<img width="1440" height="811" alt="PowerOn" src="https://github.com/user-attachments/assets/33a8527b-13f6-46ac-b0cb-c4c06a15e914" />

2. Time and Date Interface

<img width="1440" height="811" alt="T D" src="https://github.com/user-attachments/assets/2b385f6e-e751-42e5-8d73-a723d6472335" />

3. User Login Page

<img width="1440" height="811" alt="UserLogin" src="https://github.com/user-attachments/assets/924a5195-9624-4d17-a5b6-dfb876a8af2d" />

4. Desktop and Taskbar

<img width="1440" height="811" alt="Desk Task" src="https://github.com/user-attachments/assets/a35a5b01-2b14-4a95-a966-6ed78daaa995" />

5. Search Menu

<img width="1440" height="811" alt="SearchMenu" src="https://github.com/user-attachments/assets/bf401fe2-82d4-4de1-bfe9-f042f69ae49f" />

6. Weather and Other Details

<img width="1440" height="811" alt="News" src="https://github.com/user-attachments/assets/8dd6c130-9411-4c39-afcd-cd18c7921ac0" />

7. Window Interface

<img width="1440" height="811" alt="Window" src="https://github.com/user-attachments/assets/6155d1fa-0d1d-4f70-85b5-e14b40706f92" />

8. Selection Area

<img width="1440" height="811" alt="Selection Area" src="https://github.com/user-attachments/assets/af6941a1-d9a3-4edf-9cd9-aeb3caeb48cd" />

