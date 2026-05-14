 # Personal Portfolio

A simple static portfolio site introducing me and giving people a way to get in touch. Built with plain HTML as a foundation — focused on getting the semantics and accessibility right before adding styles and interactivity.

## Features

- **About** — short bio with a profile photo
- **Skills** — current tech stack
- **Contact form** — name, email, subject, and message fields with built-in validation
- **Social links** — LinkedIn and GitHub in the footer

## Tech Stack

- HTML5

CSS and JavaScript will be added as the project grows.

## Running Locally

Clone the repo and open the file in a browser:

```bash
git clone https://github.com/your-username/portfolio.git
cd portfolio
open index.html
```

Or, in VS Code, install the **Live Server** extension, right-click `index.html`, and select "Open with Live Server" for auto-reload on save.

## What I Focused On

- **Semantic HTML** — proper use of `<header>`, `<main>`, `<section>`, `<footer>`, and `<nav>` instead of generic `<div>`s
- **Heading hierarchy** — a single `<h1>` per page, with `<h2>`s and `<h3>`s nested correctly so screen readers can navigate the outline
- **Accessible forms** — every input paired with a `<label>`, `autocomplete` hints for browser autofill, and `aria-describedby` for hint text
- **ARIA labels** — `aria-label` on `<nav>` elements to distinguish main nav from social links
- **Meaningful alt text** — describing what the image shows, not that it's an image

## What's Next

- [ ] Add CSS for layout, typography, and color
- [ ] Make it responsive with media queries
- [ ] Hook the contact form up to a real backend (Formspree, Resend, or a Next.js API route)
- [ ] Rebuild in Next.js + Tailwind CSS once the static version is polished
- [ ] Add a Projects section showcasing things I've built

## What I Learned

- Semantic HTML elements aren't interchangeable with `<div>` — each one carries meaning that browsers, search engines, and assistive tech rely on
- Heading levels reflect *hierarchy*, not visual size — CSS handles size
- `<nav>` is specifically for navigation links, not just any list
- Accessibility isn't a separate step you add at the end; it's baked into the markup choices you make from the start

## Author

**Aman Gurung**

- LinkedIn: [linkedin.com/in/your-handle](https://linkedin.com/in/your-handle)
- GitHub: [github.com/your-handle](https://github.com/your-handle)

---

Built while learning. Feedback welcome.