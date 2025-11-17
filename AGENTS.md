# AGENTS.md

## Project Overview
Static HTML/CSS portfolio website served via nginx with Docker containerization.

## Build/Deploy Commands
```bash
# Build and run with Docker Compose
docker-compose up -d --build

# Stop containers
docker-compose down

# View logs
docker-compose logs -f
```

## Code Style Guidelines
- **HTML**: Use semantic HTML5 tags, lowercase tag names, proper indentation (4 spaces)
- **CSS**: Use kebab-case for class names, organize styles by section (body, tables, components)
- **File Structure**: Keep all static assets in `site/` directory, CSS in `site/css/`
- **Naming**: Use descriptive, lowercase names for files and classes
- **Images**: Store images in CSS directory, reference with relative paths
- **Docker**: Use multi-stage builds if needed, keep Dockerfile minimal
- **No JavaScript**: This is a static site, avoid adding JS unless specifically requested

## Testing
Manual testing by opening `site/index.html` in browser or checking deployed container.

## Agent Guidelines
- When communicating information to devs, be as concise as possible. Sacrifice grammar for the sake of concision.
