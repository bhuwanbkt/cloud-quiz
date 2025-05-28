# Cloud Computing Flashcard Quiz

This is a self-contained **flashcard-style quiz** focused on **Cloud Computing** concepts. The project is built using a single HTML file that includes embedded JavaScript and CSS. It runs entirely in your browser — no setup or installation required.

## File Included

- `index.html` — The only file you need. Contains HTML, CSS, and JavaScript in one.

## How to Use

1. Download or clone this repository.
2. Open the file `index.html` in any modern web browser.
3. Click or tap on a flashcard to flip and view the answer.

## Topics Covered

This flashcard quiz covers core data mining topics, including:

- Docker Container 
- IAM
- AWS ECR
- Microservices 
- Networking

## Customization

To modify or add new flashcards:

1. Open the `index.html` file in a text editor.
2. Locate the section where the flashcards are defined (inside the HTML or `<script>` tag).
3. Use this structure to create or edit cards:

```html
const flashcards = [
    {
        question: "How do you reduce Docker image size using multi-stage builds?",
        answer: "Use multiple FROM statements to copy only necessary artifacts between stages.",
        explanation: "Discards build dependencies in the final image (e.g., keep compiled binary but discard SDK).",
        category: "Docker Container",
        difficulty: "hard"
    },
    {
        question: "What is the purpose of Docker network create --driver overlay?",
        answer: "Creates a network spanning multiple Docker hosts (for Swarm/Kubernetes).",
        explanation: "Enables cross-host container communication.",
        category: "Docker Container",
        difficulty: "hard"
    }]
