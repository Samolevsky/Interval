# Interval

A modern productivity timer app with integrated task management, designed to help you focus and track your work sessions.

## Overview

Interval is a desktop application built with Electron that combines a customizable Pomodoro-style timer with a powerful task management system. Track your work sessions, manage tasks with priorities and subtasks, and maintain focus with visual progress indicators.

## Features

- **Customizable Timer**: Adjustable work and break durations with visual progress ring
- **Task Management**: Create, organize, and track tasks with drag-and-drop support
- **Subtasks**: Break down complex tasks into manageable subtasks
- **Priority System**: Color-coded priority indicators (High, Medium, Low, Green, Blue, Purple)
- **Session Tracking**: Automatic tracking of completed work sessions and breaks
- **Session Reflection**: Add notes and reflections after each session
- **Daily Progress**: Visual progress bar showing your daily productivity
- **Session History**: Review past sessions with timestamps and notes
- **Dark Mode**: Automatic dark mode support with manual toggle
- **Sound Notifications**: Customizable audio alerts when timers complete
- **Persistent Storage**: All data saved locally using localStorage
- **Responsive Design**: Works seamlessly on desktop and mobile screens


## User Guide

### Getting Started

1. **Launch the App**: Open Interval to see the main timer interface
2. **Set Your Timer**: The default work session is 25 minutes, break is 5 minutes
3. **Start Working**: Click the "Start" button to begin your work session
4. **Take Breaks**: When the timer completes, you'll be prompted to start a break

### Timer Controls

- **Start/Pause**: Begin or pause the current timer
- **Reset**: Reset the timer to its initial duration
- **Skip**: Skip to the next session (work → break or break → work)
- **Adjust Duration**: Hover over the timer display to reveal +/- buttons for quick adjustments

### Managing Tasks

#### Creating Tasks

1. Type your task in the "Add a task..." input field
2. Press Enter or click the "+" button to add the task
3. Tasks appear in the task list below

#### Task Features

- **Complete Tasks**: Click the checkbox to mark tasks as complete
- **Priority**: Click the colored dot to cycle through priority levels
- **Play Button**: Start the timer with a specific task selected
- **Edit**: Click on the task text to edit it inline
- **Delete**: Click the "×" button to remove a task
- **Drag & Drop**: Reorder tasks by dragging them

#### Working with Subtasks

1. Click the "+" button next to a task to add a subtask
2. Type the subtask description and press Enter
3. Subtasks can be completed, edited, and deleted independently
4. Collapse/expand subtasks using the arrow button
5. Drag subtasks to reorder or convert them to main tasks

#### Task Progress

- View completion percentage in the task counter
- Progress bar shows visual representation of completed tasks
- Clear completed tasks using the "Clear Completed" button

### Customizing Settings

Access settings in the Settings card:

- **Work Duration**: Set your preferred work session length (minutes)
- **Break Duration**: Set your preferred break length (minutes)
- **Auto-start Breaks**: Automatically start break timer when work completes
- **Auto-start Work**: Automatically start work timer when break completes
- **Sound Notifications**: Enable/disable audio alerts
- **Notification Volume**: Adjust the volume of timer completion sounds
- **Session Name**: Add a custom name for your current session

### Session Tracking

#### During a Session

- **Session Times**: View start time, elapsed time, and end time
- **Reflection**: Add notes about what you accomplished
- **Reward**: Set a reward for completing your session

#### Session History

- View all completed sessions in the Session History card
- Sessions show type (Work/Break), duration, and timestamp
- Click on sessions with notes to view reflection details
- Edit or delete session notes from the modal

### Daily Progress

- Track your daily productivity with the progress bar
- Shows percentage of your daily goal completed
- Resets at midnight each day

### Keyboard Shortcuts

- **Cmd/Ctrl + N**: Start a new timer session (reloads the app)
- **Enter**: Add task when input is focused
- **Escape**: Cancel task editing

### Theme Options

- **Auto**: Follows your system theme preference
- **Light**: Always use light theme
- **Dark**: Always use dark theme

Toggle themes using the buttons in the header.

## Tips for Maximum Productivity

1. **Set Realistic Goals**: Start with 25-minute work sessions if you're new to focused work
2. **Take Breaks**: Don't skip breaks - they're essential for maintaining focus
3. **Prioritize Tasks**: Use the priority system to focus on what matters most
4. **Break Down Large Tasks**: Use subtasks to make big projects less overwhelming
5. **Review Your Progress**: Check your session history to see patterns and improve
6. **Add Reflections**: Take a moment after each session to note what you accomplished
7. **Customize Your Timer**: Adjust durations to match your natural focus rhythm

## Data Storage

All data is stored locally in your browser's localStorage:

- Tasks and subtasks
- Timer settings
- Session history
- Daily progress
- Theme preferences

Your data never leaves your device and is automatically saved as you work.


## Version

Current version: 0.2.9.4

## License

All Rights Reserved

## Author

Arseny Samolevsky

---

**Need Help?** Click the app icon in the header to view the About modal with feature highlights and usage tips.
