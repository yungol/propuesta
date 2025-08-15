# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This project creates sophisticated visual mockups for client quotation proposals for a collection and warehouse management system. Each mockup showcases a polished, production-ready appearance to demonstrate the final application's potential. The project consists of self-contained HTML prototypes with complete user flows.

## Technology Stack & Architecture

- **JavaScript**: Vanilla JavaScript only (minimal usage)
- **Styling**: Tailwind CSS via CDN
- **Icons**: Google Material Icons via CDN
- **Structure**: Self-contained HTML files with embedded `<script>` and `<style>` tags
- **Dependencies**: No external frameworks or libraries
- **Language**: All user-facing text must be in Spanish

## Project Structure

- `login-movil.html` - Mobile login interface with email/password authentication
- `registro-movil.html` - Mobile registration interface with user type selection (Recolector/Almacén)
- `programar-recoleccion.html` - Collection scheduling interface for warehouse operations

## Design Standards

### Visual Requirements
- **Design Quality**: Create elaborate, professional CSS designs as if building a final production application
- **User Experience**: Focus on polished interactions, smooth transitions, and modern UI patterns
- **Visual Fidelity**: Mockups should look indistinguishable from production applications

### Current Design System
The existing pages use a glass morphism design with:
- **Background**: Blue-purple gradient (`#667eea` to `#764ba2`)
- **Containers**: White semi-transparent background (`rgba(255, 255, 255, 0.95)`) with backdrop blur
- **Glass Effect**: Semi-transparent containers with backdrop blur and subtle shadows
- **Animation**: Floating shapes, hover effects, and smooth transitions
- **Icons**: Google Material Icons throughout the interface

### Interactive Elements
- Password visibility toggles
- User type selection cards with hover/selection states
- Form submission with loading states and disabled buttons
- Responsive hover effects on buttons and inputs
- Payment option selection with visual feedback

## Development Guidelines

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

# Open collection scheduling page
open programar-recoleccion.html
# Or
firefox programar-recoleccion.html
```

### File Structure Template
Each HTML file should be completely self-contained and represent a specific application screen or user flow:

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Screen Name - La Vaquita</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
    <script>
      // Minimal vanilla JavaScript for interactions
    </script>
    <style>
      /* Custom CSS for advanced styling and animations */
    </style>
  </head>
  <body>
    <!-- Sophisticated UI components and layouts -->
    <!-- Use Material Icons: <span class="material-icons">icon_name</span> -->
    <!-- All user-facing text must be in Spanish -->
  </body>
</html>
```

### Code Architecture

All files follow a consistent structure:
1. External dependencies (Tailwind CSS, Material Icons)
2. Inline JavaScript for form handling and interactions
3. Inline CSS for custom styling and animations
4. HTML markup with semantic structure

### Key Features by Page

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
- Consistent design language with login page

#### Collection Scheduling Page (`programar-recoleccion.html`)
- Collection address input with textarea
- Date and time pickers with validation
- Packaging requirements checkbox
- Payment options: One-time or subscription
- Subscription frequency selection (weekly, biweekly, monthly)
- Additional notes field
- Form validation and loading states

## Development Principles

- **Visual Fidelity**: Mockups should look indistinguishable from production applications
- **Interactive Elements**: Include hover states, focus states, and subtle animations
- **Typography**: Use Tailwind's typography scale for consistent text hierarchy
- **Spacing**: Apply consistent spacing patterns using Tailwind's spacing system
- **Components**: Create reusable component patterns within each file
- **Icons**: Use Google Material Icons with `<span class="material-icons">icon_name</span>` syntax
- **Responsive Design**: Optimize for mobile-first design patterns and touch interactions
- **Language**: All user-facing text must be in Spanish

## JavaScript Functions

The JavaScript functions are simple and focused:
- `togglePassword()` - Shows/hides password fields
- `handleLogin()` / `handleRegister()` / `handleSubmit()` - Form submission simulation
- `selectPayment()` - Payment option selection for scheduling
- `goBack()` - Navigation helper
- Password confirmation validation in registration

## Project Purpose

This is a prototype/mockup project focusing on UI/UX demonstration for client quotation proposals rather than backend functionality. Each page demonstrates sophisticated visual design and user interaction patterns that would be expected in a production application.