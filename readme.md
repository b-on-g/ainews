# ainews

![License](https://img.shields.io/github/license/best-online-games/ainews?style=flat&logo=opensourceinitiative&logoColor=white&color=blue)
[![OSA-improved](https://img.shields.io/badge/improved%20by-OSA-yellow)](https://github.com/aimclub/OSA)

## Overview

ainews provides a personalized, multilingual news experience by aggregating AI and technology-related content from diverse sources. It empowers users to quickly digest, filter, and organize articles through intelligent summarization, translation, and customizable categories, making it easier to stay informed with minimal effort.

## Table of Contents

- [Core features](#core-features)
- [Installation](#installation)
- [Getting Started](#getting-started)
- [Documentation](#documentation)
- [Contributing](#contributing)
- [License](#license)
- [Citation](#citation)

## Core features

1. **RSS Feed Aggregation**: The application aggregates news articles from multiple RSS feeds across various categories such as AI, Technology, Science, Business, and more. It parses RSS XML content to extract article titles, descriptions, publication dates, links, and images, providing a centralized news dashboard.
2. **AI-Powered Text Translation**: The app integrates with an AI translation service (via Novita API) to automatically translate article titles and descriptions into the user's preferred language. Translation is triggered based on language detection and user settings, supporting multilingual news consumption.
3. **AI-Based Content Summarization**: Utilizes AI to generate concise summaries of news articles or collections of articles. Users can summarize individual descriptions or view a global summary of all recent news across selected categories, enhancing quick information digestion.
4. **RSS Proxy Service**: Provides a backend proxy server to fetch RSS feeds from external sources, bypassing CORS restrictions. The proxy also handles character encoding fixes (e.g., for opennet.ru) and forwards responses with appropriate headers to the frontend.
5. **Category-Based News Organization**: Organizes news into user-defined categories (e.g., AI, Technology, Russia, Sports). Users can customize which RSS sources belong to each category, enabling personalized news filtering and navigation through tabs.
6. **Content Filtering by Keywords**: Allows users to filter news articles based on include and exclude keyword rules. Articles are matched against user-defined regular expressions in their titles, enabling fine-grained control over displayed content.
7. **User Preferences and Settings Persistence**: Stores user settings such as language preference, font size, auto-translate toggle, and link behavior (open in new tab) using localStorage, ensuring a consistent experience across sessions.
8. **Dynamic Source Configuration**: Supports dynamic configuration of RSS sources through a structured source map. New feeds can be added under categories without code changes, allowing flexible customization and expansion of news sources.
9. **Responsive UI with Expandable Articles**: Features a clean, responsive user interface where news articles are displayed in expandable spoilers. Users can click to reveal full content, with options to translate or summarize on demand.

## Installation

Install ainews using one of the following methods:

**Build from source:**

1. Clone the ainews repository:
```sh
git clone https://github.com/best-online-games/ainews
```

2. Navigate to the project directory:
```sh
cd ainews
```

## Getting Started

To get started with ainews, after cloning the repository, ensure you have Node.js and npm installed. Then install dependencies and start the development server:

```sh
npm install
npm run dev
```

Open your browser and navigate to `http://localhost:3000` (or the port specified in the output) to access the application.

## Documentation

A detailed ainews description is available [here](https://best-online-games.github.io/ainews/).

## Contributing

- **[Report Issues](https://github.com/best-online-games/ainews/issues)**: Submit bugs found or log feature requests for the project.
- **[Submit Pull Requests](https://github.com/best-online-games/ainews/pulls)**: Contribute directly by forking the repository and submitting pull requests. Detailed guidelines can be found in the [CONTRIBUTING.md](https://github.com/best-online-games/ainews/blob/master/.github/CONTRIBUTING.md) file.

## License

This project is protected under the MIT License. For more details, refer to the [LICENSE](https://github.com/best-online-games/ainews/blob/master/LICENSE) file.

## Citation

If you use this software, please cite it as below.

### APA format:

```
best-online-games (2025). ainews repository [Computer software]. https://github.com/best-online-games/ainews
```

### BibTeX format:

```bibtex
@misc{ainews,
    author = {best-online-games},
    title = {ainews repository},
    year = {2025},
    publisher = {github.com},
    journal = {github.com repository},
    howpublished = {\url{https://github.com/best-online-games/ainews}},
    url = {https://github.com/best-online-games/ainews}
}
```