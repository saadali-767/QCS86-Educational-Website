# QCS86 - Educational Platform

## About

This React application contains the initial pages and functionalities created for a client. It consists of Home, About, and Classes pages along with a settings panel where users can edit details and chat as well.

## Features

- **Home Page**: Landing page with hero section and key highlights
- **About Us**: Information about the platform and services
- **Courses/Classes**: Browse and explore available courses
- **User Profile**: View and manage user profile information
- **Settings Panel**: Edit user details and preferences
- **Group Chat**: Real-time messaging between users and tutors
- **Login/Sign-up**: User authentication and registration
- **Responsive Design**: Mobile-friendly interface for all devices
- **Newsletter**: Subscribe to updates and announcements

## Project Structure

```
src/
├── App.jsx                    # Main application component
├── main.jsx                   # Entry point
├── App.css                    # Global styles
├── index.css                  # Base styles
├── Components/                # Reusable UI components
│   ├── Navbar/               # Navigation component
│   ├── Header/               # Header section
│   ├── Hero/                 # Hero banner
│   ├── Login-Form/           # Login form component
│   ├── Signup-Form/          # Sign-up form component
│   ├── Sign-Tutor/           # Tutor signup form
│   ├── About-us/             # About section
│   ├── Courses-section2/     # Course listings
│   ├── Feature-section/      # Features showcase
│   ├── Choose-us/            # Why choose us section
│   ├── Testimonial/          # User testimonials
│   ├── ProfileCard/          # Profile card display
│   ├── ProfileComp/          # Profile component
│   ├── Account/              # Account settings
│   ├── Sidebar-settings/     # Settings sidebar
│   ├── Group-Chat/           # Chat functionality
│   ├── Footer/               # Footer component
│   └── [Other Components]/   # Additional components
├── pages/                     # Page components
│   ├── Home.jsx              # Home page
│   ├── Courses.jsx           # Courses page
│   ├── Profile.jsx           # User profile page
│   ├── Settings.jsx          # Settings page
│   ├── Welcome.jsx           # Welcome page
│   └── [Styles]/             # Page-specific styles
├── assets/                    # Static assets and images
└── assests/                   # Additional assets
```

## Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd QCS86-Stage-1
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Build for production**
   ```bash
   npm run build
   ```

## Technologies Used

- **React**: JavaScript library for building user interfaces
- **Vite**: Frontend build tool and development server
- **CSS**: Styling and responsive design
- **JavaScript (ES6+)**: Modern JavaScript syntax

## Available Scripts

- `npm run dev` - Start the development server with hot module replacement
- `npm test` - Run tests (currently not configured)

## Browser Support

This application works in all modern browsers that support ES6+ JavaScript.

## Contributing

For contributions or feature requests, please contact the development team.

## License

ISC

## Author

Created for QCS86 client

---

**Version**: 1.0.0  
**Status**: Initial Development Stage
