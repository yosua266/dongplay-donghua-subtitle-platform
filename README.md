
Built by https://www.blackbox.ai

---

# DongPlay - Fansub Donghua Subtitle Indonesia

DongPlay is a web application designed for fans of Donghua, providing a platform to watch and download your favorite animated series with Indonesian subtitles. Users can browse the latest releases, manage bookmarks, and view upcoming schedules all in one place.

## Project Overview

DongPlay aims to deliver a user-friendly experience for fans of Donghua by allowing them to easily navigate through series, episodes, and download options while offering community features like comments and bookmarks. The application leverages modern web technologies to ensure a responsive and engaging experience.

## Installation

To run DongPlay locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-repo/dongplay.git
   ```

2. **Navigate to the Project Directory**:
   ```bash
   cd dongplay
   ```

3. **Open the `index.html` file** in your web browser to start using the application.

## Usage

Once the application is open in your browser, you can:

- **Browse Donghua**: Find new series or episodes in the "Donghua" section.
- **Watch Episodes**: Click on any episode to watch it on the video player.
- **Bookmark Videos**: Use the bookmark feature to save your favorite episodes for later viewing.
- **View Schedules**: Check the release schedule to keep track of when new episodes will be available.

## Features

- User-friendly navigation with a responsive design.
- Search and filter options for Donghua by genre, status, or title.
- Interactive features, such as bookmarking and commenting on episodes.
- Admin panel for managing video uploads, comments, and more.

## Dependencies

The project uses the following dependencies (as indicated in `package.json`):

- [Tailwind CSS](https://tailwindcss.com) - for rapid UI development.
- [Font Awesome](https://fontawesome.com/) - for icons.
- [Plyr](https://plyr.io/) - HTML5 media player.

### Example `package.json` Dependencies:
```json
{
  "dependencies": {
    "tailwindcss": "^2.2.19",
    "font-awesome": "^6.0.0",
    "plyr": "^3.7.2"
  }
}
```

## Project Structure

The project is organized as follows:

```
- dongplay/
  - index.html          # Main application page
  - admin.html          # Admin panel for adding/editing content
  - watch.html          # Video player for watching episodes
  - donghua.html        # List of Donghua series
  - bookmark.html        # User bookmarks
  - schedule.html       # Release schedule of episodes
  - js/
    - main.js           # Main JavaScript file for functionality
  - css/
    - style.css         # Custom styles
```

## Conclusion

DongPlay is a comprehensive platform for Donghua fans, combining ease of access to content with interactive features that enhance the viewing experience. For any contributions or feedback, feel free to open an issue or submit a pull request on GitHub.