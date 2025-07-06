# Facely AI - Premium Facial Analysis

## Overview

Facely AI is a premium facial analysis web application that provides AI-powered facial recognition and analysis capabilities. The application is built as a client-side web app using vanilla HTML, CSS, and JavaScript, with a focus on premium user experience through glassmorphism design and gradient aesthetics.

## System Architecture

### Frontend Architecture
- **Technology Stack**: Vanilla HTML5, CSS3, JavaScript (ES6+)
- **Styling Framework**: Tailwind CSS (via CDN)
- **Design System**: Premium glassmorphism with gold/neon color scheme
- **Font**: Google Fonts (Poppins)
- **Architecture Pattern**: Single-page application (SPA) with class-based JavaScript

### Backend Architecture
- **Server**: Simple Python HTTP server for development
- **Deployment**: Static file serving
- **Port**: 5000 (configured in .replit)

## Key Components

### 1. User Interface Components
- **Glass Cards**: Premium glassmorphism design with backdrop blur effects
- **Gradient Text**: Gold to neon cyan gradient branding
- **Responsive Design**: Mobile-first approach with Tailwind CSS
- **Interactive Buttons**: Animated buttons with hover effects and shine animations

### 2. JavaScript Application (FacelyAI Class)
- **User Management**: Local storage-based user data persistence
- **Daily Scan Limiting**: Built-in usage limits (2 scans per day)
- **Analysis History**: Persistent storage of analysis results
- **Onboarding System**: User registration and setup flow

### 3. Data Management
- **Local Storage**: All data persistence handled client-side
- **Session Management**: Day-based scan limit reset
- **User Preferences**: Stored locally for personalization

## Data Flow

1. **User Onboarding**: New users complete registration form
2. **Image Upload**: Users upload images for facial analysis
3. **Local Processing**: Analysis metadata stored locally
4. **History Tracking**: Results saved to analysis history
5. **Daily Limits**: Scan counts tracked and reset daily

## External Dependencies

### CDN Resources
- **Tailwind CSS**: `https://cdn.tailwindcss.com`
- **Google Fonts**: Poppins font family
- **Font Preconnection**: Optimized font loading

### Development Dependencies
- **Python 3.11**: HTTP server for development
- **Node.js 20**: Available for potential future enhancements

## Deployment Strategy

### Development Environment
- **Platform**: Replit
- **Server**: Python HTTP server on port 5000
- **Modules**: Node.js 20 and Python 3.11 configured
- **Workflow**: Parallel execution setup

### Production Considerations
- **Static Hosting**: Application is fully client-side
- **CDN Dependencies**: Relies on external CDNs for styling
- **No Backend Required**: Pure frontend application

### Key Architectural Decisions

1. **Client-Side Only**: Chosen for simplicity and cost-effectiveness
   - **Pros**: No server maintenance, easy deployment, fast loading
   - **Cons**: Limited by browser storage, no server-side processing

2. **Local Storage**: Used for all data persistence
   - **Rationale**: Eliminates need for backend database
   - **Limitation**: Data not synced across devices

3. **Daily Scan Limits**: Implemented to manage usage
   - **Purpose**: Prevent abuse while maintaining free tier
   - **Reset Logic**: Automatically resets based on date comparison

4. **Glassmorphism Design**: Premium aesthetic approach
   - **Goal**: Differentiate from competitors with modern design
   - **Implementation**: Custom CSS with backdrop filters

## Changelog
- June 15, 2025. Initial setup

## User Preferences

Preferred communication style: Simple, everyday language.