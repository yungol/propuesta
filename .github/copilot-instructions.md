
# Copilot Instructions for AI Coding Agents

## Project Overview
This project creates sophisticated visual mockups for client quotation proposals. Each mockup should showcase a polished, production-ready appearance to demonstrate the final application's potential.

## Technology Stack & Architecture
- **JavaScript**: Vanilla JavaScript only (minimal usage)
- **Styling**: Tailwind CSS via CDN
- **Icons**: Google Material Icons via CDN
- **Structure**: Self-contained HTML files with embedded `<script>` and `<style>` tags
- **Dependencies**: No external frameworks or libraries

## Design Standards
### Visual Requirements
- **Background**: Light gray (`bg-gray-100`)
- **Buttons**: Dark gray (`bg-gray-700`) with blue hover state (`bg-blue-600`)
- **Design Quality**: Create elaborate, professional CSS designs as if building a final production application
- **User Experience**: Focus on polished interactions, smooth transitions, and modern UI patterns
- **Language**: All user-facing text must be in Spanish

### Responsive Design
- **Mobile mockups**: Optimize for mobile-first design patterns and touch interactions
- **Desktop mockups**: Utilize full screen real estate with desktop-appropriate layouts
- **Breakpoints**: Use Tailwind's responsive utilities (`sm:`, `md:`, `lg:`, `xl:`)

## File Structure Guidelines
Each HTML file should be completely self-contained and represent a specific application screen or user flow.

### Template Structure
```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Screen Name - Mockup</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
    <script>
      // Minimal vanilla JavaScript for interactions
    </script>
    <style>
      /* Custom CSS for advanced styling and animations */
    </style>
  </head>
  <body class="bg-gray-100 min-h-screen">
    <!-- Sophisticated UI components and layouts -->
    <!-- Use Material Icons: <span class="material-icons">icon_name</span> -->
    <!-- All user-facing text must be in Spanish -->
  </body>
</html>
```

## Development Principles
- **Visual Fidelity**: Mockups should look indistinguishable from production applications
- **Interactive Elements**: Include hover states, focus states, and subtle animations
- **Typography**: Use Tailwind's typography scale for consistent text hierarchy
- **Spacing**: Apply consistent spacing patterns using Tailwind's spacing system
- **Components**: Create reusable component patterns within each file
- **Icons**: Use Google Material Icons with `<span class="material-icons">icon_name</span>` syntax

## Update Guidelines
Update this file when introducing new design patterns, interaction models, or architectural decisions.