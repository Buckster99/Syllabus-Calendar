# Syllabus & Calendar Management App

A modern, responsive web application for managing course syllabi and assignment deadlines built with React and TypeScript.

## Features

### 📊 Dashboard
- Real-time statistics showing total syllabi, pending/completed/overdue assignments
- Upcoming assignments section with due date tracking
- Overdue assignments with visual indicators
- Clean, responsive design with modern UI

### 📚 Syllabi Management
- Create, edit, and delete course syllabi
- Comprehensive course information (title, code, instructor, semester, year)
- Assignment listings under each syllabus
- Modal-based forms with validation

### ✅ Assignment Tracking
- Create assignments linked to specific syllabi
- Due date management with automatic overdue detection
- Completion status toggling
- Assignment details and descriptions

### 📅 Calendar View
- Assignments grouped by due date
- Visual indicators for overdue, today, and upcoming assignments
- Interactive completion toggling from calendar view
- Clean date-based organization

## Technology Stack

- **React 19** with TypeScript for type safety
- **React Router** for navigation
- **Tailwind CSS** for styling
- **Lucide React** for icons
- **Local Storage** for data persistence (no backend required!)

## Installation & Setup

### Prerequisites
- Node.js (version 16 or higher)
- npm or yarn package manager

### Getting Started

1. **Install dependencies:**
   ```bash
   npm install
   # or
   yarn install
   ```

2. **Start the development server:**
   ```bash
   npm start
   # or
   yarn start
   ```

3. **Open your browser:**
   Navigate to `http://localhost:3000` to view the application.

## Usage

### Creating Your First Syllabus
1. Click "Add Syllabus" button
2. Fill in course details (title, code, instructor, etc.)
3. Click "Create" to save

### Adding Assignments
1. Click "Add Assignment" button  
2. Select the course from dropdown
3. Enter assignment details and due date
4. Click "Create" to save

### Managing Assignments
- **Mark Complete**: Click the circle icon next to any assignment
- **View by Date**: Use the Calendar view to see assignments organized by due date
- **Track Progress**: Dashboard shows real-time statistics

## Data Storage

This application uses **browser local storage** to persist your data:
- No database setup required
- Data stays on your local computer
- Works offline after initial load
- Data persists between browser sessions

## Building for Production

To create a production build:

```bash
npm run build
# or
yarn build
```

This creates a `build` folder with optimized files ready for deployment.

## Browser Support

- Chrome (latest)
- Firefox (latest)  
- Safari (latest)
- Edge (latest)

## Features Overview

| Feature | Description |
|---------|-------------|
| **Dashboard** | Overview with statistics and quick access to recent assignments |
| **Syllabi Management** | Full CRUD operations for course syllabi |
| **Assignment Tracking** | Create, complete, and manage assignments with due dates |
| **Calendar View** | Visual timeline of all assignments by due date |
| **Responsive Design** | Works on desktop, tablet, and mobile devices |
| **TypeScript** | Full type safety for better development experience |
| **Local Storage** | No server required - all data stored locally |

## Contributing

This is a standalone application. To customize:

1. Clone or download the source code
2. Modify components in `src/` directory
3. Update styling in `src/App.css` or Tailwind classes
4. Add new features by extending the existing components

## License

This project is open source and available under the MIT License.