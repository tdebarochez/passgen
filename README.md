# Password Generator

A simple, secure password generator web application that creates strong passwords with customizable options.

## Features

- **Customizable Length**: Generate passwords from 1 to 64 characters using an intuitive slider
- **Character Types**: Toggle inclusion of:
  - Capital letters (A-Z)
  - Numbers (0-9)
  - Symbols (!@#$%^&*...)
- **Real-time Generation**: Passwords update automatically when settings change
- **Strength Indicator**: Visual password strength meter with color-coded feedback
- **Copy to Clipboard**: One-click copying with visual confirmation
- **Clean Interface**: Modern, responsive design with icon-based controls

## Usage

1. Open `index.html` in your web browser
2. Adjust the password length using the slider
3. Toggle character types using the checkboxes
4. Password generates automatically as you change settings
5. Click the copy icon (📋) to copy the password to your clipboard
6. Click the refresh icon (🔄) to generate a new password with the same settings

## Password Strength

The strength indicator evaluates passwords based on:
- Length (longer is stronger)
- Character diversity (more character types = stronger)
- Bonus points for very long passwords (24+ characters)

Strength levels:
- **Weak** (Red): Basic passwords with limited length/diversity
- **Fair** (Orange): Moderate strength passwords
- **Good** (Yellow): Strong passwords with good length and diversity
- **Strong** (Green): Very strong passwords with excellent security

## Security

- All password generation happens locally in your browser
- No passwords are sent to any server or stored anywhere
- Uses JavaScript's `Math.random()` for password generation
- Cryptographically secure random generation recommended for high-security use cases

## Browser Compatibility

Works in all modern browsers that support:
- ES6 JavaScript
- CSS Flexbox
- Clipboard API (for copy functionality)

## License

This project is open source and available under the MIT License.