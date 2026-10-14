# Multilingual Civics Complaint Router

A beginner-friendly civic-tech demo that classifies common civic complaints written in English, Telugu, or Hindi and suggests a possible category and department.

## Features

- Complaint input in English, Telugu, and Hindi
- Basic language-script detection
- Keyword-based categories: water supply, roads, electricity, drainage, sanitation, and other
- Suggested priority, department, and next step
- Responsive layout for desktop and mobile
- Example complaints for quick testing
- Clear disclaimer: this app does not submit complaints to government authorities

## Files

- `index.html` — app structure and form
- `style.css` — visual design and responsive layout
- `script.js` — language detection and keyword-based classification

## Run locally

1. Download or clone this repository.
2. Open `index.html` in a modern web browser.
3. Enter a complaint or click one of the example buttons.
4. Click **Find suggested department**.

No build step or API key is required.

## Deploy with GitHub Pages

1. Push all files to the root of a public GitHub repository.
2. Open the repository's **Settings → Pages**.
3. Under build and deployment, choose **Deploy from a branch**.
4. Select the `main` branch and `/(root)` folder, then save.
5. Wait for GitHub Pages to publish and open the URL shown on the Pages settings screen.

## Limitations and responsible use

This is a student demonstration, not an official government service. Classification uses keyword matching, not a trained AI model, and can be wrong or fail to understand mixed-language phrases and dialects. Department names are generic suggestions and vary by location. Users should verify the right department using official local-government sources. Do not enter private or sensitive personal information.

## Future improvements

- Add an optional translation or multilingual language model API
- Configure verified department directories for specific cities
- Add accessibility and usability testing
- Add a backend only if secure storage or official integrations are needed

## Project purpose

To explore how multilingual interfaces can make civic information and complaint guidance easier to access.
