# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a mobile-focused web application mockup for a collection and warehouse management system. The project consists of static HTML prototypes with user authentication flows.

## Project Structure

- `login-movil.html` - Mobile login interface with email/password authentication
- `registro-movil.html` - Mobile registration interface with user type selection (Recolector/Almacén)

## Technology Stack

- **Frontend**: Pure HTML, CSS, and JavaScript
- **Styling**: Tailwind CSS (via CDN)
- **Icons**: Material Icons (via CDN)
- **No build system**: Direct HTML files that can be opened in browser

## Development

### Running the Application
Since this is a static HTML project, simply open the HTML files directly in a web browser:
```bash
# Open login page
open login-movil.html
# Or
firefox login-movil.html

# Open registration page  
open registro-movil.html
# Or
firefox registro-movil.html
```

### Key Features

#### Login Page (`login-movil.html`)
- Glass morphism design with gradient background
- Form validation and password visibility toggle
- Simulated authentication with 2-second loading state
- Social login option (Google placeholder)
- Responsive mobile-first design

#### Registration Page (`registro-movil.html`)
- User type selection: Recolector (Collector) or Almacén (Warehouse)
- Complete registration form with password confirmation
- Terms and conditions acceptance
- Form validation and loading states
- Similar design language to login page

### Design System

#### Visual Elements
- **Colors**: Blue-purple gradient background (`#667eea` to `#764ba2`)
- **Glass Effect**: Semi-transparent containers with backdrop blur
- **Animation**: Floating shapes, hover effects, and smooth transitions
- **Icons**: Material Icons throughout the interface

#### Interactive Elements
- Password visibility toggles
- User type selection cards with hover/selection states
- Form submission with loading states and disabled buttons
- Responsive hover effects on buttons and inputs

### Code Architecture

Both files follow a consistent structure:
1. External dependencies (Tailwind CSS, Material Icons)
2. Inline JavaScript for form handling and interactions
3. Inline CSS for custom styling and animations
4. HTML markup with semantic structure

The JavaScript functions are simple and focused:
- `togglePassword()` - Shows/hides password fields
- `handleLogin()` / `handleRegister()` - Form submission simulation
- Password confirmation validation in registration

This is a prototype/mockup project focusing on UI/UX demonstration rather than backend functionality.