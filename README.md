# HTML Authentication POC

A simple HTML-only authentication proof of concept with 5 interconnected pages.

## Pages

1. **login.html** - Main login page with links to register and forgot password
2. **register.html** - User registration page with form validation
3. **forgot-password.html** - Password recovery request page
4. **reset-password.html** - Password reset form page
5. **dashboard.html** - Protected dashboard page accessible after login

## Navigation Flow

- Login → Register → Forgot Password → Reset Password → Dashboard
- All pages are interconnected with proper anchor tag navigation
- No CSS or JavaScript - pure HTML structure only

## Features

- Semantic HTML5 structure
- Proper form labels and input types
- Cross-page navigation using anchor tags
- Responsive viewport meta tags
- Accessible form elements

## Usage

Open any HTML file in a web browser to test the navigation flow between pages.

## Redirections Tested

✓ login.html → register.html  
✓ login.html → forgot-password.html  
✓ register.html → login.html  
✓ forgot-password.html → login.html  
✓ forgot-password.html → register.html  
✓ reset-password.html → login.html  
✓ dashboard.html → login.html (logout)
