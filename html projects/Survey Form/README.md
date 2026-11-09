# Platform Survey Form

A simple HTML survey form that collects feedback about a learning platform. Built with semantic HTML only (no CSS or JavaScript yet).

**[View Live Demo](https://hasham-hameed.github.io/frontend-projects/html%20projects/Survey%20Form/index.html)**

> Part of my [frontend-projects](https://github.com/Hasham-Hameed/frontend-projects) repository, a collection of HTML, CSS and JavaScript practice projects.

## Features

- Form built with `<form>`, `<label>`, `<input>`, `<select>` and `<textarea>`
- Every input is linked to a `<label>` via `for` / `id`
- Built-in validation with `required`, `type="email"` and `min` / `max`
- Placeholder text to guide the user
- A mix of input types:
  - Text, email and number inputs
  - Dropdown menus (current role, favorite feature)
  - Radio buttons (would you recommend the platform?)
  - Checkboxes (what should be improved?)
  - Textarea (comments and suggestions)

## Form Fields

| Field | Input Type | Required |
|-------|-----------|----------|
| Name | `text` | Yes |
| Email | `email` | Yes |
| Age | `number` (3 to 100) | No |
| Current role | `select` | No |
| Would you recommend the platform? | `radio` | No |
| Favorite feature | `select` | No |
| What would you like improved? | `checkbox` (multiple) | No |
| Comments or suggestions | `textarea` | No |

## Project Location

```
frontend-projects/
├── html projects/
│   ├── Survey form/
│   │   ├── index.html
│   │   └── README.md
│   └── ... (other projects)
└── ...
```
