# Riverdale Football Club Website

This is a simple static website for Riverdale FC, showcasing the team, fixtures, and media (images, audio, and video).

---

## 📂 Project Structure
- `index.html` → Homepage
- `about.html` → About the club
- `fixtures.html` → Match fixtures
- `contact.html` → Contact information
- `style.css` → Styling for all pages
- `Dockerfile` → For containerizing the project
- `.dockerignore` → Exclude unnecessary files from Docker builds

---

## 🚀 Running Locally (Without Docker)
1. Open `index.html` in any browser.

---

## Running with Docker
You can serve the site using **nginx in Docker**.

### 1. Build the Image
```bash
docker build -t riverdale-fc .
