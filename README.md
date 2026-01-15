# Part 0 - Fundamentals of Web Apps

This folder contains exercises demonstrating the fundamentals of web applications and how browsers interact with servers.

## Exercises

### exercise0.4.md
A sequence diagram showing the traditional multi-page application flow:
- User creates a new note via POST request
- Server responds with a 302 redirect status
- Browser follows the redirect and fetches the updated notes page
- Resources (CSS, JavaScript, JSON data) are loaded

### exercise0.5.md
A sequence diagram showing the initial load of a single-page application (SPA):
- Browser requests the SPA at `/exampleapp/spa`
- Server returns the HTML page with embedded resources
- CSS and JavaScript files are loaded
- JavaScript fetches the JSON data and renders the notes
- No page reloads occur after the initial load

### exercise0.6.md
A sequence diagram showing note creation in a single-page application:
- User fills in a form and submits
- Browser sends a POST request with the new note data
- Server responds with the new note as JSON
- JavaScript dynamically updates the UI without page reload

## Key Concepts

- **Traditional Web Apps**: Server-driven, full page reloads for each interaction
- **Single-Page Applications (SPAs)**: Client-driven, dynamic UI updates without page reloads
- **Sequence Diagrams**: Visual representation of interactions between browser and server
