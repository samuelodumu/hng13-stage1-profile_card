# hng13-stage1-profile_app

A responsive profile card website showcasing personal information, social links, a real-time UTC clock, and about and contact pages. This is an improvement on the HNG Stage 0 task with enhanced accessibility and interactive features.

## Features

- **Responsive Design**: Mobile-first design that works on all screen sizes
- **Real-time Clock**: Live UTC time display with milliseconds precision
- **Social Media Links**: Direct links to professional social profiles
- **Accessibility**: ARIA labels, keyboard navigation, and semantic HTML
- **Modern UI**: Clean design using Bootstrap 5 and custom styling

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- Bootstrap 5.3.2
- Bootstrap Icons 1.13.1

## Project Structure

```
hng13-stage1-profile_card/
│
├── index.html          # Main HTML file
├── style.css          # Custom CSS styles
├── img/               # Image assets
│   ├── samuel_profile.png
│   └── favicon-32x32.png
└── README.md          # Project documentation
```

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional software installation required

### Running Locally

1. **Clone or Download the Project**
   ```bash
   git clone <repository-url>
   cd hng13-stage1-profile_card
   ```

2. **Open the Project**
   - Simply double-click `index.html` to open in your default browser
   
   **OR**
   
   - Right-click `index.html` → "Open with" → Choose your preferred browser

3. **Alternative: Using Live Server (Recommended for Development)**
   
   If you have VS Code with Live Server extension:
   - Open the project folder in VS Code
   - Right-click `index.html`
   - Select "Open with Live Server"
   - The site will open at `http://localhost:5500` with auto-reload

### Using Python's Built-in Server

If you prefer using a local server:

```bash
# Navigate to project directory
cd hng13-stage1-profile_card

# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

Then open `http://localhost:8000` in your browser.

## Features Overview

### Real-time Clock
- Displays current UTC time with milliseconds
- Updates every 10ms for smooth animation
- Format: `Time: HH:MM:SS.mmm GMT`

### Social Links
- Keyboard accessible navigation
- Opens in new tabs with security attributes
- ARIA labels for screen readers
- Links to:
  - Threads (@themainsamuel)
  - Twitter/X (@themainsamuel)
  - LinkedIn (samuelodumu)
  - GitHub (samuelodumu)

### Accessibility Features
- Semantic HTML structure
- ARIA labels and roles
- Keyboard navigation support
- Screen reader friendly
- High contrast text

## Customization

### Updating Profile Information

1. **Name and Bio**: Edit the content in `index.html` lines 24-25
2. **Profile Picture**: Replace `img/samuel_profile.png` with your image
3. **Social Links**: Update the `href` attributes in the social links section
4. **Hobbies/Dislikes**: Add content to the respective sections

### Styling

- Modify `style.css` for custom styling
- Bootstrap classes can be adjusted directly in HTML
- Color scheme uses Bootstrap's utility classes

## Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Create a Pull Request

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

- **GitHub**: [@samuelodumu](https://github.com/samuelodumu)
- **LinkedIn**: [Samuel Odumu](https://www.linkedin.com/in/samuelodumu)
- **Twitter**: [@themainsamuel](https://x.com/themainsamuel)

## Acknowledgments

- HNG Internship Program
- Bootstrap team for the excellent framework
- Bootstrap Icons for the icon set

---

**Note**: This is a portfolio project created as part of the HNG Stage 1 task. The live clock feature demonstrates JavaScript DOM manipulation and real-time updates.