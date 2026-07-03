# Software Engineering Books Library

A curated collection of essential software engineering books covering architecture, clean code, best practices, and modern development frameworks.

## Overview

This repository hosts a personal collection of software engineering books, organized as a GitHub Pages site with an interactive book viewer. The collection includes titles on software architecture, coding practices, frameworks, and tools that every developer should know.

## Featured Books

| Title                                 | Author                                | Year | Topic                 |
| ------------------------------------- | ------------------------------------- | ---- | --------------------- |
| Clean Architecture                    | Robert C. Martin                      | 2017 | Software Architecture |
| Clean Code                            | Robert C. Martin                      | 2008 | Code Quality          |
| Spring in Action (6th Ed.)            | Craig Walls                           | 2022 | Java Framework        |
| Fullstack D3 and Data Visualization   | Amelia Wattenberger                   | 2020 | Data Visualization    |
| Modern Software Engineering           | David Farley                          | 2021 | Engineering Practices |
| Fundamentals of Software Architecture | Mark Richards, Neal Ford              | 2020 | Software Architecture |
| The Linux Command Line                | William Shotts                        | 2019 | System Administration |
| Refactoring (2nd Ed.)                 | Martin Fowler                         | 2018 | Code Improvement      |
| The C Programming Language            | Brian W. Kernighan, Dennis M. Ritchie | 1988 | Programming Languages |
| The Rust Programming Language         | The Rust Project Developers           | 2023 | Programming Languages |
| Learning Zig                          | Alex Rios                             | 2024 | Programming Languages |

## Features

- **Responsive Design**: Optimized for desktop, tablet, and mobile viewing
- **Dark/Light Mode**: Toggle between themes with preference persistence
- **PDF Viewer**: Read books directly in the browser with the integrated viewer
- **Book Categories**: Books are categorized by topic for easy navigation
- **Modern UI**: Clean, card-based interface with smooth animations

## Technology Stack

- **HTML5** - Semantic markup structure
- **CSS3** - Modern styling with CSS Variables for theming
- **Vanilla JavaScript** - No framework dependencies
- **GitHub Pages** - Static site hosting

## Getting Started

### Local Development

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/littlee.github.io.git
   cd littlee.github.io
   ```

2. Open `index.html` in your browser, or serve with a local server:

   ```bash
   # Using Python
   python -m http.server 8000

   # Using Node.js
   npx serve
   ```

3. Navigate to `http://localhost:8000`

### Adding New Books

1. Add the PDF file to the repository root
2. Edit the `books` array in `index.html`:
   ```javascript
   {
       id: 9,
       title: "Your Book Title",
       author: "Author Name",
       year: "2023",
       edition: "1st Edition",
       file: "Your.Book.File.pdf",
       description: "Brief description of the book...",
       category: "category-name"
   }
   ```
3. Add a corresponding CSS class for the book cover if desired

## Project Structure

```
├── index.html          # Main application with book viewer
├── index.js            # JavaScript utilities
├── README.md           # Project documentation
├── images/             # Assets (favicon, etc.)
│   └── favicon.png
├── lib/                # Third-party libraries
│   ├── lostkeys/       # Custom fonts
│   ├── lostkeys.css
│   ├── lostkeys-dark.css
│   ├── marked.min.js   # Markdown parser
│   ├── prism.css       # Syntax highlighting
│   └── prism.js
├── md/                 # Markdown content
│   └── 01/
│       └── index.md
└── *.pdf               # Book files
```

## Contributing

Contributions are welcome! If you'd like to suggest improvements or add new features:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is for educational purposes. All books remain the property of their respective authors and publishers. Please support authors by purchasing official copies of the books.

## Acknowledgments

- Original repository concept by [littlee](https://github.com/littlee)
- Book authors and publishers for their valuable content
- Open source community for the libraries used in this project

---

**Note**: This repository is maintained for personal educational use. If you are a copyright holder and would like content removed, please open an issue or contact the repository owner.

### [See the side here](https://books-software.netlify.app/)
