## Daisy and the Silent Streets

An interactive **Choose Your Own Adventure** story where you guide Daisy through mysterious silent streets, making choices that shape her journey.

## Overview


This project is a narrative-driven interactive experience built with pure HTML and served through NGINX. Navigate through branching storylines where your decisions matter, all rendered without CSS or JavaScript—a minimalist approach to interactive storytelling.

## echnologies Used

- **HTML** - Pure semantic markup for structure and navigati
- **NGINX** - High-performance web server
- **Git & GitHub** - Version control and collaboration
- **WSL** - Ubuntu/Debian Linux subsystem for Windows development

## Getting Started

### Prerequisites

- NGINX installed and running on your system
- Access to terminal/command line
- Basic familiarity with Linux commands

### Installation & Deployment

1. **Clone the repository** (if applicable):
   ```bash
   git clone <repository-url>
   cd laboratorio-adventure
   ```

2. **Copy project files to NGINX web directory**:
   ```bash
   sudo cp -r laboratorio-adventure /var/www/html/adventure
   ```

3. **Set appropriate permissions**:
   ```bash
   sudo chmod -R 755 /var/www/html/adventure
   ```

4. **Access the story** in your web browser:
   ```
   http://localhost/adventure/intro/index.html
   ```
