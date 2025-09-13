# High School Course Guides & Dictionaries

A comprehensive web-based platform for high school course guides and subject dictionaries, designed to help students navigate their academic coursework with interactive, searchable resources. Most of this site was generated using Super Grok and Claude Sonnet 4.

Disclaimer: as is the nature of generative AI, small mistakes or incorrectly labeled unit numbers are possible. Use a variety of resources for your academic studies.

## Features

- **Interactive Course Guides**: Dynamic course templates that load content from JSON data files
- **Searchable Content**: Easy-to-navigate course materials and terminology
- **Responsive Design**: Works seamlessly across desktop and mobile devices
- **Modular Structure**: Template-based system for easy course addition and maintenance
- **JSON-Driven Content**: Structured data format for consistent course information

## Project Structure

```
├── index.html              # Main landing page
├── guide.html              # Course template (fetches data from JSON)
├── ap-guides-styles.css    # Main stylesheet with settings and styling
├── README.md               # Project documentation
├── LICENSE                 # MIT License file
└── data/
    ├── courses.json        # Course metadata and listings
    └── stats.json          # Example course data structure
```

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A local web server (recommended) or ability to serve files locally

### Installation

1. Clone or download this repository to your local machine
2. Ensure all files are in their proper directory structure as shown above
3. Open `index.html` in a web browser, or serve the files using a local web server

### Usage

1. **Main Site**: Open `index.html` to access the main course directory
2. **Course Guides**: Navigate to individual courses through the main interface
3. **Adding New Courses**: 
   - Add course metadata to `./data/courses.json`
   - Create corresponding data files in the `./data/` directory following the structure shown in `stats.json`

## File Descriptions

### Core Files

- **`index.html`**: The main landing page that displays available courses and provides navigation
- **`guide.html`**: A dynamic template that fetches and displays course data from JSON files
- **`ap-guides-styles.css`**: Contains all styling, layout settings, and responsive design rules

### Data Files

- **`./data/courses.json`**: Contains metadata for all available courses including titles, descriptions, and data file references
- **`./data/stats.json`**: Example structure showing how individual course data should be formatted

## Adding New Courses

To add a new course to the system:

1. Create a new JSON file in the `./data/` directory with your course content
2. Follow the structure demonstrated in `stats.json`
3. Update `./data/courses.json` to include metadata for your new course
4. The course will automatically appear in the main interface

## Data Structure

Course data files should follow this general structure:
- Course information and metadata
- Organized content sections
- Searchable terminology and definitions
- Any additional resources or references

See `./data/stats.json` for a complete example.

## Browser Compatibility

This project is designed to work with modern web browsers that support:
- ES6+ JavaScript features
- CSS Grid and Flexbox
- Fetch API for JSON loading
- Responsive CSS media queries

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes following the existing code structure
4. Test your changes across different browsers
5. Submit a pull request with a clear description of your changes

## Development Notes

- All files should maintain the directory structure as specified
- JSON data files should be properly formatted and validated
- CSS should follow the existing naming conventions
- New features should be responsive and accessible

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Support

For questions, issues, or suggestions, please create an issue in the project repository or contact the development team.

---

**Note**: This project is designed for educational use in high school environments. Content should be reviewed for accuracy and appropriateness for the target student audience.