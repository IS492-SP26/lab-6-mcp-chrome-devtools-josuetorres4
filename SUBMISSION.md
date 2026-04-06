# Chrome DevTools MCP Debugging Lab

## Overview
In this lab, I used Chrome DevTools MCP with VS Code Copilot to analyze and debug a web application running on localhost:8080. MCP allowed the AI to inspect runtime behavior, including console logs, network requests, and layout issues.

### Issues Fixed
Logo Path (404 Error) - FIXED ✓

Changed: assets/logo.png → assets/logo1.png
Network status now: 200 OK
Undefined Variable (taskCounter) - FIXED ✓

Added variable declaration: let taskCounter = 0;
App functions correctly now
SSL Certificate Error - FIXED ✓

Removed problematic stylesheet: https://httpstat.us/200?sleep=3000
Eliminated the 3-second delay and certificate error

Logo Path (404 Error) - FIXED ✓

Changed: assets/logo.png → assets/logo1.png
Network status now: 200 OK
Undefined Variable (taskCounter) - FIXED ✓

Added variable declaration: let taskCounter = 0;
App functions correctly now
SSL Certificate Error - FIXED ✓

Removed problematic stylesheet: https://httpstat.us/200?sleep=3000
Eliminated the 3-second delay and certificate error

### I asked copilot if the app was functional and it said this:

Yes, the app is fully functional! ✅
Here's the comprehensive functionality test results:

Core Features Working:
✅ Add Task - Successfully adds new tasks with:

Task text
Timestamp (creation time)
Unique task ID via taskCounter
✅ Mark Complete - "Done" button:

Toggles strikethrough styling on task text
Logs toggle action to console
✅ Delete Task - Properly removes tasks:

Removes task from DOM
Restores "No tasks yet" message when list is empty
Logs deletion to console
✅ UI/UX:
Beautiful purple gradient design
Logo displays correctly
Responsive layout
Input field clears after adding task
Empty state message works
Console Status:
✅ App loaded successfully
✅ No JavaScript errors
✅ Task operations logged correctly
⚠️ Only minor 404 for favicon.ico (not critical)
Network Status:
✅ All resources load successfully (HTML, CSS, JS, Fonts, Logo)
✅ No broken dependencies
The app is production-ready with all three bugs successfully fixed!

## Key Takeaway
Using MCP allowed real time debugging by analyzing actual runtime behavior instead of relying on static code. This made it easier to quickly identify and fix issues.
