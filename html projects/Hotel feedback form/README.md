# Hotel Feedback Form

A simple, accessible HTML form that collects guest feedback after a hotel stay. Built with semantic HTML only.

## Preview
Live link:https://Hasham-Hameed.github.io/frontend-projects/html%20projects/Hotel%20feedback%20form/index.html

## Features

- Semantic structure using `<header>`, `<main>`, `<form>`, `<fieldset>` and `<legend>`
- Every input is linked to a `<label>` via `for` / `id`
- Built-in validation with `required`, `type="email"` and `min` / `max`
- A mix of input types:
  - Text, email and number inputs
  - Radio buttons (first-time guest?)
  - Checkboxes (reasons for choosing the hotel)
  - Dropdowns (service and food ratings)
  - Textarea (extra comments)

## Form Sections

| Section | Input Type | Required |
|---------|-----------|----------|
| Name | `text` | Yes |
| Email address | `email` | Yes |
| Age | `number` (3 to 100) | No |
| First time at the hotel? | `radio` | No |
| Why did you choose us? | `checkbox` (multiple) | No |
| Service rating | `select` | No |
| Food rating | `select` | No |
| Other comments | `textarea` | No |

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/hotel-feedback-form.git
   ```
2. Open the folder:
   ```bash
   cd hotel-feedback-form
   ```
3. Open `index.html` in your browser.

