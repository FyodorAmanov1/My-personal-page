# Personal Portfolio Website

A lightweight personal website presenting an introduction, selected projects and a contact interface. The implementation uses plain HTML, CSS and a small amount of JavaScript, making the structure easy to inspect and customize.

## Page sections

- **Home:** an introductory landing section.
- **About:** a profile image and background information.
- **Projects:** links to selected work in education, quantum physics and AI.
- **Contact:** a styled form layout.

The page includes section navigation, a profile-image hover interaction and scroll-triggered reveal effects.

## Preview locally

From the repository root:

```bash
python -m http.server 8000
```

Open <http://localhost:8000>. No package installation, frontend framework or build step is required.

## Customize the site

| File | Change here |
|---|---|
| [index.html](index.html) | Biography, navigation, project links and page content |
| [style.css](style.css) | Layout, typography, colors and transitions |
| [Profile_photo.jpg](Profile_photo.jpg) | Profile image asset |

Keep the section IDs aligned with navigation links when adding new sections. If replacing the portrait, update the image reference in the HTML as needed.

## Contact-form behavior

The contact section is a frontend form only. No message-delivery service or backend endpoint is included, so submitting the form does not establish that a message was sent. Connect a chosen delivery service before presenting it as a working contact channel.
