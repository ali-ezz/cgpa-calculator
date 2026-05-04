# CGPA Calculator

Arabic university GPA calculator and course planner for semester performance tracking.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Status](https://img.shields.io/badge/status-early%20release-yellow.svg)
![Language](https://img.shields.io/badge/language-HTML%2FCSS%2FJavaScript-lightgrey.svg)

## Overview

This project is a static web tool for students to calculate current semester GPA and combined CGPA using course credits and percentage/grade-point values. It also includes Arabic university regulation text content and supports right-to-left layout.

## Quick Start

1. Clone the repository:
   ```bash
   git clone https://github.com/ali-ezz/the-list.git
   cd the-list
   ```
2. Open `index.html` in a browser, or serve locally:
   ```bash
   python3 -m http.server 8000
   ```
3. Open `http://localhost:8000` and use the GPA calculator.

## Features

- Semester GPA calculator with credit-weighted grading
- Percentage-to-grade-point conversion for Arabic GPA systems
- Optional previous CGPA and credit inputs
- Dynamic add/remove course entry rows
- Responsive RTL layout for Arabic content
- Lightweight static HTML/CSS/JavaScript implementation

## Usage

1. Enter previous CGPA and previous earned hours if available.
2. Add courses with credit hours and percentage or grade point values.
3. Remove any course row using the delete button.
4. Review the semester GPA and new cumulative CGPA results.

## Repository Layout

- `index.html` — main web page and calculator UI
- `ali-style.css` — page styling
- `ali.js` — calculator logic and input handling
- `imgs/` — project images and assets
- `README.md` — project overview and documentation
- `LICENSE` — open source license
- `CONTRIBUTING.md` — contribution guidelines
- `CODE_OF_CONDUCT.md` — contributor behavior policy
- `SECURITY.md` — security reporting instructions
- `.github/ISSUE_TEMPLATE/` — issue templates
- `.github/pull_request_template.md` — pull request template
- `CODEOWNERS` — reviewer ownership

## Contributing

Please read `CONTRIBUTING.md` before opening issues or pull requests. Contributions are welcome, especially for accessibility improvements, bug fixes, and documentation.

## License

This repository is licensed under the MIT License. See `LICENSE` for details.

## Policies

- `CODE_OF_CONDUCT.md` for expected community behavior.
- `SECURITY.md` for vulnerability reporting.
