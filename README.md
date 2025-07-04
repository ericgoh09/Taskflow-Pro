# TaskFlow Pro - All-In-One To-Do List Application

![Task Management App](https://github.com/ericgoh09/Taskflow-Pro/blob/main/assets/Banner.png)

## Overview

TaskFlow Pro is a comprehensive task management application with a sleek, modern interface and powerful features to help you stay organized and productive. With natural language processing, customizable filters, statistics tracking, and theme options, TaskFlow Pro offers a complete solution for managing your daily tasks.

## Features

### 🚀 Advanced Task Management
- **Natural Language Processing**: Add tasks with due dates and priorities using natural language (e.g., "Meeting tomorrow at 2pm #work !high")
- **Smart Task Parsing**: Automatically extracts dates, tags, and priorities from task descriptions
- **Detailed Task Editing**: Modify task title, due date, priority, tags, and notes
- **Completion Tracking**: Visual indicators for completed tasks
- **Priority Levels**: Assign high, medium, or low priority to tasks
- **Task Notes**: Add detailed descriptions to tasks

### 🏷️ Intelligent Organization
- **Custom Tag System**: Create and manage custom tags
- **Smart Filtering**: Filter tasks by status (all/active/completed) and tags
- **Smart Sorting**: Tasks automatically sorted by due date with overdue tasks highlighted
- **Tag Management**: Add, edit, and remove custom tags

### 📊 Productivity Analytics
- **Progress Tracking**: Visual progress bar shows completion percentage
- **Task Statistics**: View total tasks, completed tasks, in progress, overdue, and due today
- **Completion Rate**: Track your overall productivity rate

### 🔄 Data Management
- **CSV Export**: Export all tasks to CSV file
- **CSV Import**: Import tasks from CSV with merge/replace options
- **Local Storage**: All data persists in browser's localStorage

### 🎨 Customizable Experience
- **Theme Options**: Light, dark, and high-contrast themes
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Visual Feedback**: Notification system for user actions

## How to Use

### Adding Tasks
1. Type your task in the input field at the top
2. Use natural language: "Meeting tomorrow at 2pm #work !high"
3. Click "Add Task" or press Enter
4. The system will automatically parse:
   - Due date (tomorrow, today, next week, specific dates)
   - Tags (#work, #personal)
   - Priority (!high, !medium, !low)

### Managing Tasks
- ✅ **Complete tasks**: Click the checkbox
- ✏️ **Edit tasks**: Click the edit icon
- 🗑️ **Delete tasks**: Click the trash icon
- 🔍 **Filter tasks**: Use the sidebar filters or view buttons

### Organizing with Tags
1. To add a new tag:
   - Type in the "Add new tag" field in the sidebar
   - Click "Add Tag"
2. To filter by tag:
   - Click any tag in the sidebar
3. To remove a tag:
   - Click the × icon on any tag

### Importing/Exporting Data
1. **Export tasks**:
   - Click "Export CSV" in the header
   - Tasks will be downloaded as a CSV file
2. **Import tasks**:
   - Click "Import CSV" in the header
   - Select a CSV file
   - Choose to merge with existing tasks or replace all tasks

### Customizing Appearance
- Switch between themes using the theme buttons in the header:
  - ☀️ Light mode (default)
  - 🌙 Dark mode
  - 👁️ High contrast mode

## Getting Started

Simply open the `LINK` below to start playing. No installation required!



## Technical Implementation

- **Frontend**: HTML5, CSS3, JavaScript (ES6)
- **UI Libraries**: 
  - [Font Awesome](https://fontawesome.com) for icons
  - [Google Fonts](https://fonts.google.com) (Poppins) for typography
- **Storage**: Browser localStorage for data persistence
- **Responsive Design**: Flexbox and CSS Grid
- **Natural Language Processing**: Custom parsing engine
